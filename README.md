[![GitHub license](https://img.shields.io/github/license/SkyCD/SkyCD.TextFormat.dll)](https://github.com/SkyCD/SkyCD.TextFormat.dll/blob/main/LICENSE)
[![GitHub release](https://img.shields.io/github/release/SkyCD/SkyCD.TextFormat.dll.svg)](https://github.com/SkyCD/SkyCD.TextFormat.dll/releases/latest)

# SkyCD.TextFormat.dll

SkyCD.TextFormat.dll is a plugin for SkyCD that allows it to read SkyCD TextFormat type files.

## Installation

To install SkyCD.TextFormat.dll, simply copy the DLL file into the `Plug-Ins` folder of your SkyCD installation.

## SkyCD Text File Format

SkyCD Text Format is a way to store data as a list. Each entity begins with a prefix such as `[DISKNAME]`, where `DISKNAME` is the label of the disk where the file can be found. Brackets are required to separate the label from another content. Next, the full path without the disk letter where the item is located follows (e.g. `\Music\`). After that, the file size in fixed size brackets (e.g. `3.84591197 MB   `) and then the filename (e.g. `Nakhayb_Iraq.mp3`).

#### Example
```text
[Game.EXE CD #7 (2000)]
[Game.EXE CD #7 (2000)]\[3.5        Bytes] AUTORUN.INF
[Game.EXE CD #7 (2000)]\[310.302734 KB   ] EXECD700.dxr
[Game.EXE CD #7 (2000)]\[2.41362953 MB   ] EXECD700.exe
[Game.EXE CD #7 (2000)]\[9.44776916 MB   ] Pics.cxt
[Game.EXE CD #7 (2000)]\Music
[Game.EXE CD #7 (2000)]\Music\[3.84591197 MB   ] Al_Basrah.mp3
[Game.EXE CD #7 (2000)]\Music\[1.86976814 MB   ] Cairo_Egypt.mp3
[Game.EXE CD #7 (2000)]\Music\[1.74490737 MB   ] Finland.mp3
[Game.EXE CD #7 (2000)]\Music\[1.87395381 MB   ] Greece.mp3
[Game.EXE CD #7 (2000)]\Music\[1.84709835 MB   ] Helsinki_Sweden.mp3
[Game.EXE CD #7 (2000)]\Music\[2.08496093 MB   ] Jerusalem_Israel.mp3
[Game.EXE CD #7 (2000)]\Music\[837.5      KB   ] Munich_Germany.mp3
[Game.EXE CD #7 (2000)]\Music\[1.20744895 MB   ] Nakhayb_Iraq.mp3
[Game.EXE CD #7 (2000)]\Music\[2.04973506 MB   ] Naples_Italy.mp3
[Game.EXE CD #7 (2000)]\Music\[1.46100711 MB   ] Norway_Nephelim_Battle.mp3
[Game.EXE CD #7 (2000)]\Music\[1.95975112 MB   ] Rome_Italy.mp3
[Game.EXE CD #7 (2000)]\Music\[961.428710 KB   ] Splash_Screen_Opus.mp3
[Game.EXE CD #7 (2000)]\Music\[3.24288463 MB   ] Turin_Italy.mp3
[Game.EXE CD #7 (2000)]\Music\[1.53459835 MB   ] Vienna_Austria.mp3
[Game.EXE CD #7 (2000)]\Music\[2.43756961 MB   ] Zurich_Switzerland.mp3
```

## License

SkyCD.TextFormat.dll is licensed under the [MIT License](LICENSE). Please see the LICENSE file for more information.
