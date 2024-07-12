# DLSS-Enabler
Simulate DLSS Upscaler and DLSS-G Frame Generation features on any DirectX 12 compatible GPU in any DirectX 12 game that supports DLSS2 and DLSS3 natively.

## How to

### How to build a setup application

In order to build the setup application for DLSS Enabler, you need to install InnoSetup software first. The most optimal version is 6.2.0 (nothing below, nothing above - mainly due to the craziness of some AVs that raise the false positives randomly).

After installing the InnoSetup software, double click "DLSS enabler.iss" file and edit its contents (such as build version, etc) in InnoSetup Editor.

Before building new package, you need to download latest libxess.dll file from INTEL repository and place it into "Dll version" subdirectory, otherwise the setup build process will fail due to the missing file.

After successful build, the resulting setup app will be created inside of "Output" directory.
