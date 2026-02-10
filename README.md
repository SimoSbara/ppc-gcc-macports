# 🍎 MacPorts PowerPC G4 Packages for Developers (OS X 10.5 Leopard)

**Disclaimer**
This repository hosts pre-compiled MacPorts packages (binary installers) for PowerPC G4 machines running Mac OS X 10.5.8 (Leopard).
Compiling GCC 13 on a G4 processor can take days (literally 40+ hours).

**🏗 Build Environment:**
* **Machine:** PowerBook G4 (Aluminum)
* **CPU:** PowerPC G4 @ 1.33 GHz
* **RAM:** 1.5 GB
* **OS:** Mac OS X 10.5.8 Leopard
* **MacPorts Version:** [PPCPorts](https://macos-powerpc.org/)

**📦 How to install:**
These are `.mpkg` (Meta-Packages). They are standalone installers that **include all necessary dependencies** (like GMP, MPC, ISL, ZSTD, etc.).
1.  Download the `.zip` from the [Releases](https://github.com/SimoSbara/ppc-dev-macports/releases) section.
2.  Double-click to open the standard macOS Installer.
3.  Follow the instructions.

**🚀 Current Packages:**
* **GCC 13** (Includes C, C++, Fortran, LTO)
* **GCC 10 Bootstrap** (Includes C, C++, Fortran, LTO)
* *(More ports will be added gradually as I compile them)*
