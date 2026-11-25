# ClipTrellis user guide

[Project and download](../README.md) · [Русская версия](guide.ru.md)

- [Review and select clips](#review-and-select-clips)
- [Work across folders](#work-across-folders)
- [File handling](#file-handling)
- [Formats and playback](#formats-and-playback)

## Review and select clips

**Ctrl+O** opens a folder. The grid shows videos in the current folder. Subfolders open separately.

| To do this | Use |
| --- | --- |
| Open a clip next to the grid | Double-click a tile by default, or select it and press **Enter**. |
| Play, pause or step through clips | **Space** plays or pauses. **PgUp / PgDn** opens the previous or next clip. **Ctrl+M** toggles sound. |
| Select several clips | **Ctrl+click** adds or removes a tile. **Shift+click** selects a range. With focus on the grid, **Ctrl+A** selects all visible results. |
| Give candidates a rating | **Ctrl+1–5** sets a rating. **Shift+R** or **Clear rating** in the tile menu removes it. Both work on a selection. |
| Label clips by scene | **Alt+1–5** assigns a color. **Alt+0** clears the label. **Ctrl+G** toggles grouping by color. |
| Number candidates | Select the clips and press **N**. It numbers the unnumbered clips in the selection. If they're all numbered, **N** clears the numbers. Select a single clip and press **Shift+N** to enter a specific number. |
| Change what comes first | Open **Sort** with **Alt+S** and choose an order, such as highest rated first. Drag tiles within the grid to set a manual order. Manual order pauses automatic grouping. |

**Ctrl+F** opens file name search. Multiple names or paths can be entered one per line. **F1** opens the full shortcut list.

## Work across folders

**Ctrl+T** or the **+** button opens a folder in a new tab. **Ctrl+Tab** switches forward and **Ctrl+Shift+Tab** switches back. Each tab keeps its search, selection, scroll position and preview position while ClipTrellis is open. A restored preview stays paused. **Ctrl+W** closes the active tab.

The active folder refreshes when files change. When you return to a background tab, ClipTrellis checks the folder again. **F5** refreshes the folder manually.

## File handling

**Dragging clips to other apps.** Tiles and preview videos can be dragged into apps that accept files. The original stays in its folder. The **Move clips to Used after dragging** setting marks a clip as used after the receiving app accepts it for copying.

**Used clips, Trash, and recovery.** **✓** and **Ctrl+Delete** mark a clip as used. **Delete** in the main grid sends it to ClipTrellis **Trash**. Both actions hide clips while keeping the files in place. In **Used** and **Trash**, **Ctrl+Enter** restores the selected clips to the grid. **Delete** in these sections asks for confirmation before deleting from disk.

**Importing from Explorer.** Dropping supported videos onto the grid copies them into the open folder. ClipTrellis keeps both files when names collide by giving the new copy a suffix like `(2)`.

**Moving a color group.** **Move color group to a new folder** is available in the context menu of a labeled tile. It moves the whole group on disk, including clips hidden by search, and opens its new subfolder. The clips keep their color labels, ratings and numbers.

![The tile menu in ClipTrellis offers Move color group to a new folder for a labeled clip](../images/group-en.jpg)

## Formats and playback

ClipTrellis lists files with the extensions `MP4`, `M4V`, `MOV`, `MKV`, `WEBM`, `AVI`, `WMV`, `MPEG`, `MPG`, `TS`, `MTS`, `M2TS` and `3GP`. Preview playback depends on the codecs available in Windows. If one file fails, try a known-good MP4 in the same folder and open the problem file in a Windows player to narrow down the cause.

**Settings** offers single- or double-click to open a clip, autoplay when opened manually, and options for hover playback. **Settings → Interface language** switches languages. Changes take effect after restarting the app.

If you need help, [open a GitHub issue](https://github.com/korzhy/VideoWall-Releases/issues/new) with the ClipTrellis version, the steps you followed and what happened. For playback issues, include the file extension and codec if known.
