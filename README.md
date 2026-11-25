<h1><img src="images/cliptrellis.png" width="40" height="40" align="middle" alt=""> ClipTrellis</h1>

**Browse, shortlist, and organize videos in folders.** A thumbnail grid keeps the other clips in view while you preview one. Color labels, ratings, and numbers help you build a shortlist.

**Просмотр, отбор и организация видео в папках.** Сетка миниатюр с предпросмотром, цветовыми метками, рейтингами и номерами.

**[Download for Windows / Скачать для Windows](https://github.com/korzhy/VideoWall-Releases/releases/latest/download/VideoWall-Setup-x64-with-dotnet.exe)** · x64, .NET included / .NET включён

[Полная страница на русском](README.ru.md) · [User guide](docs/guide.md) · [What's new](https://github.com/korzhy/VideoWall-Releases/releases/latest)

![Thumbnail grid with color labels, ratings and numbers, two folder tabs, and a paused preview on the right](images/workflow-en.jpg)

*Color borders separate groups, stars show ratings, and numbers help set a viewing order. The preview is on the right, with another folder (B-roll) open in the next tab.*

## Features

- **Clip preview.** **Ctrl+O** opens a folder. By default, a double-click opens the preview beside the grid. **Space** plays or pauses and **PgUp / PgDn** steps through clips.
- **Labels, ratings, and order.** **Alt+1–5** assigns a color label, **Ctrl+1–5** sets a rating, and **N** numbers selected clips. The grid can be sorted by rating or number.
- **Folder tabs.** **Ctrl+T** opens a folder in a new tab and **Ctrl+Tab** switches tabs. Each tab keeps its search, selection, scroll position, and preview position for the session. A restored preview stays paused.
- **Drag and drop to other apps.** Tiles and preview videos can be dragged into apps that accept video files, such as Clipchamp. **✓** marks a clip as used. Settings can apply that mark automatically after an accepted drop. When ClipTrellis advances automatically, the next clip opens paused.

## What happens to your files

| Action | Result |
| --- | --- |
| Drag a clip **out** of ClipTrellis | The receiving app gets the original file path. The original stays in its folder. |
| Drag a video **in** from Explorer | ClipTrellis copies it into the open folder. A colliding name gets a numbered suffix. When you add videos directly to the folder in Explorer, the grid and count update automatically. |
| Send a clip to **Used** or **Trash** | ClipTrellis hides it from the main grid. You can restore it from that section. |
| Choose **Move color group to a new folder** | ClipTrellis moves the group on disk and opens the new subfolder. Labels, ratings and numbers move with the clips. |

Permanent deletion is a separate, confirmed action inside **Trash** or **Used**. [File handling and recovery](docs/guide.md#file-handling)

## Install and get help

- **System requirements.** Windows 10 version 21H2 or later, or Windows 11, x64. The installer name starts with `VideoWall-Setup`.
- **Smaller download.** PCs with .NET 10 Desktop Runtime x64 can use the [installer without the runtime](https://github.com/korzhy/VideoWall-Releases/releases/latest/download/VideoWall-Setup-x64-without-dotnet.exe).
- **Updates.** **Settings → Check for updates** checks for new versions. Manual updates use the same installer variant.
- **Interface language.** English and Russian are available under **Settings → Interface language**. Changes take effect after restarting the app. [Русская инструкция](docs/guide.ru.md)
- **Help and support.** Shortcuts, preview settings, and formats are covered in the [user guide](docs/guide.md). Problems can be reported in [GitHub Issues](https://github.com/korzhy/VideoWall-Releases/issues/new).
