# DragLaCraft Launcher Updates

Этот репозиторий хранит только файлы автообновления DragLaCraft Launcher.

Папка `build/` создаётся скриптом `prepare_launcher_release.ps1` в основном проекте.
В ней должны находиться:

- `DragLaCraft.exe`
- `DragLaCraftUpdater.exe`
- `manifest.json`

Не редактируйте `manifest.json` вручную: он содержит размеры и SHA-256 файлов.
