# Changelog

All notable changes to this fork of **ODailyQuests** are documented here.

## [3.0.2-26.3] - 2026-10-27

### Added / Updated
- **Minecraft 26.3 API Support**:
  - Upgraded compile target to Spigot/Paper API `26.3-R0.1-SNAPSHOT`.
  - Updated `plugin.yml` `api-version` to `'26.3'`.
- **Java 25 Bytecode Target**:
  - Configured Gradle toolchain and Java compilation for Java 25 (`targetJavaVersion = 25`, class major version 69).
  - Configured `gradle.properties` to ensure Java 25 home is recognized.
- **Gradle 9 & Shadow 9 Upgrade**:
  - Upgraded Gradle wrapper to `9.6.1-bin`.
  - Upgraded Gradle Shadow plugin to `9.6.1` to support Java 25 bytecode and eliminate classfile major version 69 errors.
- **Attribute Modifier Compatibility**:
  - In `PlayerQuestsInterface.java`, replaced removed `Attribute.GENERIC_MAX_HEALTH` and deprecated modifier constructor with `Attribute.MAX_HEALTH`, `NamespacedKey.minecraft("dummy")`, and `EquipmentSlotGroup.ANY`.
- **Potion Meta Modernization**:
  - In `QuestItemGetter.java` and `ItemQuest.java`, modernized deprecated `PotionData` to use `setBasePotionType()` / `hasBasePotionType()` with graceful fallback to prevent runtime null pointer exceptions on 26.3.
- **Semantic Version Parser**:
  - In `NMSHandler.java`, implemented numeric semantic version comparison to fix incorrect version checks where two-digit Minecraft versions like `26.3` failed lexical string comparison against older versions like `1.20`.
- **Build Reproducibility**:
  - Included compileOnly dependency stubs for offline/reproducible builds.
