## Open x64 X-Ray Call of Chernobyl Edition

This repository contains X-Ray Engine sources based on version 1.6.02 for specific use with the Call of Chernobyl modification.
The original engine is used in S.T.A.L.K.E.R. Call of Pripyat game released by GSC Game World and any changes to this engine are allowed for ***non-commercial*** use only (see [License.txt](https://github.com/avoitishin/xray-16/blob/master/License.txt) for details).

**Note** that the original [Master](https://github.com/revolucas/CoC-Xray/tree/master) branch contains stable code that is documented on [Wiki](https://github.com/revolucas/CoC-Xray/wiki).

## Build instructions

### 1. Prerequisites
* **Visual Studio 2022** with the following workloads/components:
  * *Desktop development with C++* (**MSVC v143** build tools)
  * *C++ MFC for latest v143 build tools (x86 & x64)*
* **Windows 10/11 SDK**.

---

### 2. Building the Solution
1. Open **`engine.sln`** from the root directory of the repository.
2. In the top toolbar of Visual Studio, set:
   * **Solution Configuration:** `Release`
   * **Solution Platform:** `x64`
3. Build the solution via **Build -> Build Solution** (`Ctrl + Shift + B`).

---

### 3. Installation and Running (Call of Chernobyl 1.4.22)
1. Back up the original `bin` folder in your game's root directory (e.g., rename it to `bin_backup`) and create a new empty **`bin`** folder.
2. Copy all compiled binaries from the build output folder `bin\Release\x64` into your game's `bin` folder.
3. Make sure **Microsoft Visual C++ Redistributable 2015–2022 (x64)** is installed on your system.
4. Launch the game via **`Stalker-CoC.exe`** in the game's root folder.

## Wiki
* Please go to the [Wiki](https://github.com/avoitishin/xray-16/wiki) pages for detailed description of changes and other useful information.