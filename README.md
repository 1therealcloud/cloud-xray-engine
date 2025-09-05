X-Ray Engine 1.6 sources (T-6638)
========================
## Изменения по сравнению с оригинальным движком:
*  BugTrap заменён на уже собраный (https://github.com/bchavez/BugTrap)
*  Сборка под 2022 студией
*  Теперь наличие DXSDK на ПК не требуется, он подключён через NuGet
## Сборка:
  1. склонировать репозиторий
  2. открыть engine.sln
  3. собрать под конфигурацией Release | Win32 (Остальные не настроены)
  4. забрать собраный двиг в папке engine_build\binaries

## Changes compared to the original engine:
* BugTrap replaced with already built (https://github.com/bchavez/BugTrap)
* Build on Visual Studio 2022
* DXSDK is no longer required on PC, it is now connected via NuGet.
## Build:
  1. clone the repository
  2. open engine.sln
  3. build Release | Win32 configuration (the others are not configured)
  4. get the built engine in the engine_build\binaries folder
