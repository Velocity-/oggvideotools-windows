# oggvideotools-windows
Oggvideotools project ported to Windows (MinGW32). Includes a patch file which can be applied on the `src` directory of [Oggvideotools-0.7a](http://www.streamnik.de/uploads/media/oggvideotools-0.7a.tar.gz) (untested on any previous version).

Binaries are included at the [release](https://github.com/Velocity-/oggvideotools-windows/releases) (`oggCat.exe`, `oggCut.exe`, `oggDump.exe`, `oggJoin.exe`, `oggLength.exe` and `oggSplit.exe`). These are statically linked and do not depend on the MinGW32 runtime or any other dependencies (except `Kernel32.dll` and `MSVCRT.dll` which are present on Windows by default).