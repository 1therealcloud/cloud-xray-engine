X-Ray Engine 1.6 sources
========================
## Зміни порівняно з оригінальним рушієм:
*  BugTrap замінений на вже зібраний (https://github.com/bchavez/BugTrap).
*  Збірка на 2022 студії. 
*  Наявність DXSDK на ПК не обов'язкова, він підключений через NuGet.

## збірка:
  1. Клонуєм репозиторій (git clone https://github.com/1therealcloud/cloud-xray-engine.git).
  2. Відкриваєм cloud-xray-engine/src/engine.sln.
  3. Вибираєм кофігурацію Release | Win32 (Інші не налаштовані).
  4. Збираєм рушій настиснувши Build - Build Solution (Ctrl + Shift + B).
  5. Зібраний рушій буде в папці engine_build\binaries\Win32\Release.
  6. Файли з розширенням ".pdb" не обов'язкові.
  7. Потрібено поставити в папку "bin" BugTrap. Він знаходится в папці sdk/binaries/BugTrap.dll.

При встановленні Visual Studio 2022 потрібно встановити
Desktop development with C++. (Всі стандартні компоненти), та доповнення до цього компоненту:
C++ MFC for latest v143 bulid tools (x86 & x64)
