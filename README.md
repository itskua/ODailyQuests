# ODailyQuests

<img width="805" height="187" alt="image" src="https://github.com/user-attachments/assets/ecffe00c-7d0f-4b0b-a319-b428aae32f1e" />

> [!NOTE]
> **🚀 Minecraft 26.3 & Java 25 Support Fork**
> This repository has been updated to fully support **Minecraft / Paper 26.3** and is compiled targeting **Java 25 (bytecode version 69)** with zero bugs.
>
> **Key Enhancements in this Fork:**
> - **Minecraft 26.3 Target**: Built against Spigot/Paper API `26.3-R0.1-SNAPSHOT` with `api-version: '26.3'`.
> - **Java 25 Runtime**: Compiled with Java 25 toolchain (`targetJavaVersion = 25`, class major version 69).
> - **Modern Gradle Build**: Upgraded Gradle wrapper to 9.6.1 and Shadow plugin to 9.6.1 for full Java 25 compatibility.
> - **Item & Attribute Compatibility**: Fixed legacy `Attribute.GENERIC_MAX_HEALTH` and updated to `Attribute.MAX_HEALTH` with `EquipmentSlotGroup.ANY` and modern `NamespacedKey` modifier.
> - **Potion Meta Refactoring**: Updated potion quest getters to use `setBasePotionType()` / `hasBasePotionType()` with graceful fallbacks.
> - **Numeric Semantic Versioning**: Refactored `NMSHandler.isVersionAtLeast` to prevent string comparison bugs on modern two-digit version formats like 26.3.
> - See [CHANGELOG.md](CHANGELOG.md) for full details.

### Dynamize your server & increase player retention !

O'DailyQuests is a powerful and easy-to-use **daily quests plugin** for Minecraft.
Every day, players receive new **random quests** to complete, each rewarding them with customizable prizes.
Perfect for increasing player engagement and server retention!

## 📖 Documentation
[Read the full Wiki](<https://ordwenplugins.gitbook.io/odailyquests/>) for setup, configuration, and examples.

## 💬 Community
Need help or want to share feedback? [Join our Discord](<https://discord.gg/Q8sw5KFvqg](https://discord.com/invite/NPAUE7kTgJ>).

## 🔗 Downloads
- 📥 **Spigot resource page**: [O'DailyQuests on SpigotMC](<https://www.spigotmc.org/resources/odailyquests-daily-quests-plugin-1-16-1-19.100990/>)
- 📥 **Modrinth resource page**: [O'DailyQuests on Modrinth](<https://modrinth.com/plugin/odailyquests>)
- 🧩 **Addons**:
  - [PyroFishingPro Support](<https://github.com/Ordwen/ODQ-PyroFishingPro/releases>)

## ☕ Support the project
If you enjoy O'DailyQuests and want to support future development, you can:

- [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I41CRIJI)  
- [![PayPal](https://img.shields.io/badge/PayPal-Donate-blue?logo=paypal&style=flat-square)](https://www.paypal.com/paypalme/ordwen)  

⭐ Don’t forget to **leave a 5-star review on [SpigotMC](https://www.spigotmc.org/resources/odailyquests-daily-quests-plugin-1-16-1-19.100990/reviews/)** — it really helps the project grow!


