![X-Ray_Engine.jpg](https://upload.wikimedia.org/wikipedia/ru/b/bc/X-Ray_Engine.jpg)

*Leaked* X-Ray Engine 1.6.02 <img width="16" height="16" alt="8896523" src="https://github.com/user-attachments/assets/b58cd067-7ef4-41f0-80cc-5304cc6d7a45" /> sources
===========================================================================

## Changes compared to the original engine:

 * Project migrated to Visual Studio 2022 <img width="16" height="16" alt="Visual_Studio_Icon_2022 svg" src="https://github.com/user-attachments/assets/b64c7deb-a1b9-406f-9620-1362eb97b74c" />.
 * [BugTrap replaced with a prebuilt version](https://github.com/bchavez/BugTrap). <img width="16" height="16" alt="1" src="https://github.com/user-attachments/assets/2e3ceb43-b9da-4ea3-9215-d432cdd02f6d" />


 * [DXSDK](https://www.microsoft.com/download/details.aspx?id=6812) <img width="16" height="16" alt="directx-logo" src="https://github.com/user-attachments/assets/18c56f8d-94f3-4f8c-a303-b46572a55ed9" />
 is no longer required, it is connected via [NuGet](https://www.nuget.org/) <img width="16" height="16" alt="NuGet_project_logo svg" src="https://github.com/user-attachments/assets/07664988-09fa-406e-a68a-056977105c2a" />.
 * Fixed the "*blurred*" font issue on **DirectX 11** <img width="16" height="16" alt="directx-logo" src="https://github.com/user-attachments/assets/18c56f8d-94f3-4f8c-a303-b46572a55ed9" /> | [73ccafa](https://github.com/1therealcloud/cloud-xray-engine/commit/73ccafabe27a7e955814b0f2db6bf4a34cacd759).

## Building the engine:

  1. Clone the repository **(git clone https://github.com/1therealcloud/cloud-xray-engine.git)**.
<img width="801" height="16" alt="image" src="https://github.com/user-attachments/assets/d73ca0a3-658e-4da4-a3dd-f0d0ed2b3943" />

  2. Open the file **cloud-xray-engine/src/engine.sln**.
<img width="406" height="27" alt="image" src="https://github.com/user-attachments/assets/3c1a393c-9f2d-4aae-aed4-5bc0c00632d3" />

  3. ~~Select the configuration **Release | Win32** (others are not configured)~~.
<img width="185" height="26" alt="image" src="https://github.com/user-attachments/assets/89e761cb-41ce-44a8-90ad-fccef97ab6cc" />

  4. Build the engine by pressing **Build - Build Solution** **(Ctrl + Shift + B)**.
<img width="324" height="344" alt="image" src="https://github.com/user-attachments/assets/c4fd77d5-b040-482f-8596-aa7214beaa99" />

  5. The built engine will be located in **cloud-xray-engine\engine_build\binaries\Win32\Release**.
<img width="559" height="701" alt="image" src="https://github.com/user-attachments/assets/84d11ae6-fd4f-42d6-9fbd-650731fa26d4" />

  6. **BugTrap** <img width="16" height="16" alt="1" src="https://github.com/user-attachments/assets/2e3ceb43-b9da-4ea3-9215-d432cdd02f6d" /> must be placed in the **bin** folder. It can be found at **sdk/binaries/BugTrap.dll**.
<img width="445" height="26" alt="image" src="https://github.com/user-attachments/assets/c5be67d3-530f-4735-9d2f-8626d9589c3a" />

* Files with the **.pdb** extension are optional.
<img width="474" height="784" alt="image" src="https://github.com/user-attachments/assets/1d4e9c6b-5820-4402-a763-d92435df22e6" />

* When installing **Visual Studio 2022** <img width="16" height="16" alt="Visual_Studio_Icon_2022 svg" src="https://github.com/user-attachments/assets/b64c7deb-a1b9-406f-9620-1362eb97b74c" />, make sure to install
  **Desktop development with C++** (all default components), and the following additional component:
  **C++ MFC for latest v143 build tools (x86 & x64)**.
<img width="409" height="103" alt="image" src="https://github.com/user-attachments/assets/5bb1707c-ef0d-4635-9917-3300a253234c" />
<img width="329" height="76" alt="image" src="https://github.com/user-attachments/assets/50bf3a72-e1a1-4fbd-9929-aa1a29b69deb" />

## Thanks:

* [d5fa876](https://github.com/1therealcloud/cloud-xray-engine/commit/c6ef53c3806618093f9d270eaa9e53c2d648f206); [d0d0d9c](https://github.com/1therealcloud/cloud-xray-engine/commit/d0d0d9ca824b984a67b51728b32a7fe2a13628bc); [cf2a48f](https://github.com/1therealcloud/cloud-xray-engine/commit/cf2a48fed4685e09b4f5612799d668d39e34b88b);
  [PilotOfTheHighestSeniority](https://github.com/PilotOfTheHighestSeniority) <img width="16" height="16" alt="146639012" src="https://github.com/user-attachments/assets/0dc83b96-4bdb-41a6-939c-2a7ee5059ca3" />.

* [73ccafa](https://github.com/1therealcloud/cloud-xray-engine/commit/73ccafabe27a7e955814b0f2db6bf4a34cacd759);
  [Xottab-DUTY](https://github.com/Xottab-DUTY) <img width="16" height="16" alt="2989212" src="https://github.com/user-attachments/assets/7ca33f84-a6f1-429f-b684-96304a541006" />.

* [GSC GAMEWORLD](https://www.gsc-game.com/) <img width="16" height="16" alt="gsc_gameworld_logo" src="https://github.com/user-attachments/assets/25323c0f-69c4-4ee2-ba44-bab23b3627d4" />.

*Злитий* вихідний код X-Ray Engine 1.6.02 <img width="16" height="16" alt="8896523" src="https://github.com/user-attachments/assets/a4a4202d-6da2-4712-9dcc-89b3c4fcf58f" />
===========================================================================

## Зміни порівняно з оригінальним рушієм:
*  Проект перенесено на Visual Studio 2022 <img width="16" height="16" alt="Visual_Studio_Icon_2022 svg" src="https://github.com/user-attachments/assets/b64c7deb-a1b9-406f-9620-1362eb97b74c" />.
*  [BugTrap замінено на вже зібраний](https://github.com/bchavez/BugTrap). <img width="16" height="16" alt="1" src="https://github.com/user-attachments/assets/2e3ceb43-b9da-4ea3-9215-d432cdd02f6d" />
*  Наявність [DXSDK](https://www.microsoft.com/download/details.aspx?id=6812) <img width="16" height="16" alt="directx-logo" src="https://github.com/user-attachments/assets/18c56f8d-94f3-4f8c-a303-b46572a55ed9" /> не обов'язкова, він підключений через [NuGet](https://www.nuget.org/) <img width="16" height="16" alt="NuGet_project_logo svg" src="https://github.com/user-attachments/assets/07664988-09fa-406e-a68a-056977105c2a" />.
*  Виправлено "*мильний*" шрифт на **DirectX 11** <img width="16" height="16" alt="directx-logo" src="https://github.com/user-attachments/assets/18c56f8d-94f3-4f8c-a303-b46572a55ed9" /> | [73ccafa](https://github.com/1therealcloud/cloud-xray-engine/commit/73ccafabe27a7e955814b0f2db6bf4a34cacd759).

## Збірка рушія:
  1. Клонуєм репозиторій **(git clone https://github.com/1therealcloud/cloud-xray-engine.git)**.
<img width="801" height="16" alt="image" src="https://github.com/user-attachments/assets/adcb816d-6c1c-4f59-8a24-3ab202a27156" />

  2. Відкриваємо файл **cloud-xray-engine/src/engine.sln**.
<img width="406" height="27" alt="image" src="https://github.com/user-attachments/assets/ba3b2d4c-bdf4-40eb-b5a9-021736d20ff3" />

  3. ~~Вибираєм кофігурацію **Release | Win32** (Інші не налаштовані)~~.
<img width="185" height="26" alt="image" src="https://github.com/user-attachments/assets/d47018fe-1c0a-4e22-8503-cd4382b58866" />

  4. Збираєм рушій настиснувши **Build - Build Solution** **(Ctrl + Shift + B)**.
<img width="324" height="344" alt="image" src="https://github.com/user-attachments/assets/1dfcaa41-0474-49b8-ae86-0b8aea9e9a4b" />

  5. Зібраний рушій буде в папці **cloud-xray-engine\engine_build\binaries\Win32\Release**\.
<img width="559" height="701" alt="image" src="https://github.com/user-attachments/assets/4677df3d-3252-4fa0-be8c-56f64b7dd7f5" />

  6. **BugTrap** <img width="16" height="16" alt="1" src="https://github.com/user-attachments/assets/2e3ceb43-b9da-4ea3-9215-d432cdd02f6d" /> потрібно поставити в папку **bin**. Він знаходится по шляху **sdk/binaries/BugTrap.dll**.
<img width="445" height="26" alt="image" src="https://github.com/user-attachments/assets/af645c7f-d1cf-4183-b286-660e34c37da6" />

* Файли з розширенням **.pdb** не обов'язкові.
<img width="474" height="784" alt="image" src="https://github.com/user-attachments/assets/0fcb7a9c-ce08-46cd-8863-62eafc2b71d4" />

* При встановленні **Visual Studio 2022** <img width="16" height="16" alt="Visual_Studio_Icon_2022 svg" src="https://github.com/user-attachments/assets/b64c7deb-a1b9-406f-9620-1362eb97b74c" /> потрібно встановити
**Desktop development with C++**. (Всі стандартні компоненти), та доповнення до цього компоненту:
**C++ MFC for latest v143 bulid tools (x86 & x64)**.
<img width="409" height="103" alt="image" src="https://github.com/user-attachments/assets/5bb1707c-ef0d-4635-9917-3300a253234c" />
<img width="329" height="76" alt="image" src="https://github.com/user-attachments/assets/50bf3a72-e1a1-4fbd-9929-aa1a29b69deb" />

## Подяка:
* [d5fa876](https://github.com/1therealcloud/cloud-xray-engine/commit/c6ef53c3806618093f9d270eaa9e53c2d648f206); [d0d0d9c](https://github.com/1therealcloud/cloud-xray-engine/commit/d0d0d9ca824b984a67b51728b32a7fe2a13628bc); [cf2a48f](https://github.com/1therealcloud/cloud-xray-engine/commit/cf2a48fed4685e09b4f5612799d668d39e34b88b);
[PilotOfTheHighestSeniority](https://github.com/PilotOfTheHighestSeniority) <img width="16" height="16" alt="146639012" src="https://github.com/user-attachments/assets/9b00d3f8-8f69-4820-8eb2-8ec5077ea6b9" />.

* [73ccafa](https://github.com/1therealcloud/cloud-xray-engine/commit/73ccafabe27a7e955814b0f2db6bf4a34cacd759);  
[Xottab-DUTY](https://github.com/Xottab-DUTY) <img width="16" height="16" alt="2989212" src="https://github.com/user-attachments/assets/ec98f8db-bc05-4a3f-adaf-83c86744296c" />.

* [GSC GAMEWORLD](https://www.gsc-game.com/) <img width="16" height="16" alt="gsc_gameworld_logo" src="https://github.com/user-attachments/assets/89666760-2756-40c1-bc1f-caa14a6e47ed" />.
