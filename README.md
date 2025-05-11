# 🦆 CyberEnte-Mod

[![Build](https://img.shields.io/github/actions/workflow/status/keksgauner/minecraft-cyberente-mod/build.yml?branch=master&label=Build&style=for-the-badge)](https://github.com/keksgauner/minecraft-cyberente/actions)
[![Release](https://img.shields.io/github/v/release/keksgauner/minecraft-cyberente-mod?label=Release&style=for-the-badge)](https://github.com/keksgauner/minecraft-cyberente/releases)
[![Java](https://img.shields.io/badge/Java-21+-orange?style=for-the-badge&logo=openjdk)](https://jdk.java.net/21/)
[![License](https://img.shields.io/github/license/keksgauner/minecraft-cyberente-mod?style=for-the-badge)](https://github.com/keksgauner/minecraft-cyberente/blob/main/LICENSE)

> 🛠️ Ein maßgeschneidertes **Minecraft Fabric-Mod** für den privaten CyberEnte-Server.

---

## 👥 Autoren

- 🐤 [@CyberEnte](https://www.github.com/cyberente)
- 🍪 [@KeksGauner](https://www.github.com/keksgauner)

---

## 📥 Installation

1. Lade die neueste Version von der [**Releases-Seite**](https://github.com/keksgauner/minecraft-cyberente-mod/releases) herunter.
2. Kopiere die `CyberEnte-${version}.jar` in den `mods`-Ordner deines Fabric-Servers.
3. Starte den Server neu.

---

## 🧪 Kompilieren aus dem Quellcode

**Voraussetzungen:**

- ✅ JDK 21 oder höher
- 🌐 Internetverbindung

**Schritte:**

```bash
git clone https://github.com/keksgauner/minecraft-cyberente-mod.git
cd minecraft-cyberente-mod
./gradlew build
```

🗃️ Das fertige Plugin befindet sich anschließend in `build/libs` und trägt den Namen:
`CyberEnte-${version}.jar`

---

## 🧹 Code-Check & Formatierung

- 🔍 Code prüfen:
  `./gradlew spotlessCheck`

- 🎨 Code formatieren:
  `./gradlew spotlessApply`

---
