# nemo-gdrive-tools

Werkzeuge für die Arbeit mit **Google Drive** im [Nemo](https://github.com/linuxmint/nemo)-Dateimanager — für rclone-Mounts und GVFS.

Teil von [linux-nemo-tools](https://github.com/AndiWitt/linux-nemo-tools).

---

## Tools

### [nemo-file-type-icons](https://github.com/AndiWitt/nemo-file-type-icons)
> Nemo Python-Erweiterung, die korrekte Icons für Google Drive-Dateien (Docs, Sheets, Slides), PDFs und Videos anzeigt — behebt das generische weiße Seiten-Icon bei 0-Byte-Dateien im rclone-Mount.

```bash
git clone https://github.com/AndiWitt/nemo-file-type-icons.git
cd nemo-file-type-icons && bash install.sh
```

---

### [nemo-gdrive-download](https://github.com/AndiWitt/nemo-gdrive-download)
> Rechtsklick auf eine Datei im Google Drive-Mount → Format wählen → herunterladen. Exportiert Google Docs als .docx/.odt/.pdf, Sheets als .xlsx/.ods/.csv, Slides als .pptx/.odp/.pdf und mehr.

```bash
git clone https://github.com/AndiWitt/nemo-gdrive-download.git
cd nemo-gdrive-download && bash install.sh
```

---

### [nemo-gdrive-open](https://github.com/AndiWitt/nemo-gdrive-open)
> Rechtsklick auf eine Google Drive-Datei → direkt im Browser zum Bearbeiten öffnen. Öffnet Docs, Sheets und Slides im nativen Google-Editor ohne Download.

```bash
git clone https://github.com/AndiWitt/nemo-gdrive-open.git
cd nemo-gdrive-open && bash install.sh
```

---

## Voraussetzungen

- Linux Mint oder ein beliebiger Cinnamon-Desktop mit Nemo
- rclone mit konfiguriertem Google Drive Remote (für gdrive-download und gdrive-open)

Jedes Tool listet seine vollständigen Abhängigkeiten in seiner eigenen README.

## Lizenz

MIT
