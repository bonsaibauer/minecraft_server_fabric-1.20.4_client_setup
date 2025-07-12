# 🎮 Minecraft Fabric Server Setup (mit AutoModpack)

## 📦 Direkt-Download (Empfohlen)

👉 **[🡇 Repository als ZIP herunterladen (empfohlen)](https://github.com/bonsaibauer/minecraft_server_fabric-1.20.4_client_setup/releases/latest)**

Enthält alles, was du brauchst:
- `iris-installer-universal.jar`
- `automodpack-mc1.20.4-fabric-4.0.0-beta18.jar`
- `README.md`

## ⚙️ Voraussetzungen

- Minecraft Java Edition installiert
- Mindestens 8 GB RAM empfohlen
- Windows-Betriebssystem

## 1️⃣ Iris Universal Installer starten

1. ZIP-Datei entpacken
2. `iris-installer-universal.jar` öffnen  
   Falls sich die Datei nicht öffnet:
   - Stelle sicher, dass Java installiert ist ([Java Download](https://www.java.com/de/download/))
   - Rechtsklick → Öffnen mit → Java(TM) Platform
   - Oder im Terminal:
     java -jar iris-installer-universal.jar
3. Im Installer:
   - Version: 1.20.4
   - Modloader: Fabric + Iris anklicken
   - Auf 'Installieren' klicken

✅ `iris` und `sodium` werden automatisch installiert

## 2️⃣ RAM erhöhen

1. Minecraft Launcher öffnen
2. Reiter "Installationen" → Fabric Loader → auf die drei Punkte klicken → Bearbeiten
3. Mehr Optionen → JVM-Argumente z. B. `-Xmx8G` setzen für 8GB RAM
4. Speichern

## 3️⃣ Fabric Loader starten

1. Minecraft mit Fabric Loader 1.20.4 starten
2. Im Menü angekommen: Minecraft schließen

## 4️⃣ Mod hinzufügen

1. Windows-Taste + R → `%appdata%`
2. `.minecraft` → `mods`-Ordner öffnen
3. Datei `automodpack-mc1.20.4-fabric-4.0.0-beta18.jar` aus Repository einfügen
4. Die Dateien `iris-1.7.2+mc1.20.4` und `sodium-fabric-0.5.8+mc1.20.4` sollten auch vorhanden sein, sonst Schritt 1 wiederholen.

## 5️⃣ Server beitreten

1. Minecraft starten
2. Multiplayer → Server hinzufügen: `167.235.XX.XXX`
3. Beitreten klicken

## 6️⃣ AutoModpack Download

- Beim ersten Join lädt AutoModpack automatisch alle benötigten Mods, Shader und Ressourcen
- Nach dem Download auf schließen von Minecraft klicken (Crash ist normal)
- Minecraft neu starten und erneut beitreten

## 🔄 Updates

- Änderungen am Modpack werden beim Joinen erkannt
- AutoModpack lädt Updates automatisch herunter

---

# Aktuelle Mod-Sammlungen auf dem Server

## 1.1 🎨 Shader & Resource Packs
- **Amodp_shaderpacks** – Sammlung verschiedener Shader-Packs zur visuellen Verbesserung  
  👉 https://modrinth.com/collection/8r7aWpCm

- **Amodp_resourcepacks** – Auswahl an Resource-Packs für individuelle Texturverbesserungen  
  👉 https://modrinth.com/collection/VIlw5fEl

## 1.2 🧩 Client-Side Mods
- **Client_Side_Mods** – Nützliche Mods, die direkt auf dem Spielclient laufen  
  👉 https://modrinth.com/collection/tVuiNvdb

## 1.3 🛠️ Server-Side Mods
- **Server_Side_Mods** – Serverseitige Mods  
  👉 https://modrinth.com/collection/QJaDYdhN

---

## 📚 Quellen

- Iris Installer: https://www.irisshaders.dev/download  
- AutoModpack: https://modrinth.com/mod/automodpack/version/GrSJt2jh
