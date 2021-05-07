# unMineable - Easy mining app releases
Official repository for hosting the latest versions of the easy mining app!

## Versions and info

Two versions are available, main version and "Miner files included" (MFI) version, previously known as "Packed" and "Unpacked" versions.

Using the MFI version is the most direct way to start, but is not recommended, it includes the mining files (PhoenixMiner and xmrig) which can be removed during the download (by an antivirus or similar), rendering the app unusable. 

You will need to re-download and point the app to the new miner files if that's the case, which is the same as using the Main version anyway :) (Main version is now the unpacked version).

## How to setup

Both versions have the same configuration options, the setup is the same for both:

1. Download the latest mining app from releases.
2. Open it and go to the type of mining selection screen, if you are using the MFI version you will see an "Update miner file location" link, it means the miner files are correctly found (be aware that the mining process can be blocked after by your antivirus). You can choose to update the files or leave it like default, **if you are using the Main version (recommended) continue to step 3.**

![1](https://user-images.githubusercontent.com/83843443/117512936-353a6600-af56-11eb-9f86-b232b80693ac.PNG)

3. You will be asked to select the miner file location, which are **PhoenixMiner.exe for GPU mining or xmrig.exe for CPU mining.**, you need to manually download the files from their official repositories / links, it isn't that hard really :)

![2](https://user-images.githubusercontent.com/83843443/117513094-9bbf8400-af56-11eb-9f5a-baf230ddc3b9.PNG)

These are the ones we use for the MFI version, and the ones you need to download for the main version:

* PhoenixMiner: https://github.com/PhoenixMinerDevTeam/PhoenixMiner/releases
* xmrig: https://github.com/xmrig/xmrig/releases

Go to **Assets** and download the latest version available for your platform (we currently support Windows 10 x64), after unzipping the files you will have the PhoenixMiner.exe and / or xmrig.exe files.

4. Simply point the app to the just downloaded .exe, depending on your mining type (GPU -> PhoenixMiner.exe, CPU -> xmrig.exe).
5. Follow the UI and enjoy mining !
