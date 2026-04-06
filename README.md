# nemo-gdrive-tools

Tools for working with **Google Drive** from within the [Nemo](https://github.com/linuxmint/nemo) file manager — for rclone mounts and GVFS.

Part of [linux-nemo-tools](https://github.com/AndiWitt/linux-nemo-tools).

---

## Tools

### [nemo-file-type-icons](https://github.com/AndiWitt/nemo-file-type-icons)
> Nemo Python extension that displays correct icons for Google Drive files (Docs, Sheets, Slides), PDFs and videos — fixing the generic white-page icon that appears for 0-byte rclone-mounted files.

```bash
git clone https://github.com/AndiWitt/nemo-file-type-icons.git
cd nemo-file-type-icons && bash install.sh
```

---

### [nemo-gdrive-download](https://github.com/AndiWitt/nemo-gdrive-download)
> Right-click any file in your Google Drive mount → choose a format → download. Exports Google Docs as .docx/.odt/.pdf, Sheets as .xlsx/.ods/.csv, Slides as .pptx/.odp/.pdf, and more.

```bash
git clone https://github.com/AndiWitt/nemo-gdrive-download.git
cd nemo-gdrive-download && bash install.sh
```

---

### [nemo-gdrive-open](https://github.com/AndiWitt/nemo-gdrive-open)
> Right-click any Google Drive file → open it directly in your browser for editing. Opens Docs, Sheets and Slides in their native Google editor without downloading.

```bash
git clone https://github.com/AndiWitt/nemo-gdrive-open.git
cd nemo-gdrive-open && bash install.sh
```

---

## Requirements

- Linux Mint or any Cinnamon desktop with Nemo
- rclone configured with a Google Drive remote (for gdrive-download and gdrive-open)

Each tool lists its full dependencies in its own README.

## License

MIT
