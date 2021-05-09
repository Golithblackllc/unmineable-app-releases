# unMineable - Easy mining app releases
Official repository for hosting the latest versions of the easy mining app!

## Versions and info

Two versions are available, main version and "Mining files included" (MFI) version, previously known as "Packed" and "Unpacked" versions.

Using the MFI version is very straight forward to use as it already includes the mining files, however **it is not recommended**, because the mining files can be removed during the download (by an antivirus or similar), rendering the app unusable, you will need to re-download and point the app to the new miner files, which is the same as using the main version anyway :) (Main version was previously known as the unpacked version).

## How to setup

Both versions have the same configuration and options, the setup is the same for both:

1. Download the latest mining app from releases.
2. Unzip the file and run it, then go to the mining hardware screen, _if you are using the MFI version go to step 6._
3. You will be asked to select the miner file location, **PhoenixMiner.exe for GPU mining or xmrig.exe for CPU mining.**, you need to manually download the files from their official repositories / links, it isn't that hard really :)

![2](https://user-images.githubusercontent.com/83843443/117513094-9bbf8400-af56-11eb-9f5a-baf230ddc3b9.PNG)

These are the ones we use for the MFI version, and the ones you need to download for the main version:

* PhoenixMiner: https://github.com/PhoenixMinerDevTeam/PhoenixMiner/releases
* xmrig: https://github.com/xmrig/xmrig/releases

![PhoenixMiner](https://user-images.githubusercontent.com/83843443/117563179-c817f500-b069-11eb-9e5f-32b1b27179d5.png)
![xmrig](https://user-images.githubusercontent.com/83843443/117563186-ccdca900-b069-11eb-8356-de813dd9e089.PNG)

Go to **Assets** and download the latest version available for your platform (we currently support Windows 10 x64), after unzipping the files you will have the PhoenixMiner.exe and / or xmrig.exe files.

4. Simply point the app to the just downloaded .exe, depending on your mining type (GPU -> PhoenixMiner.exe, CPU -> xmrig.exe).

![2](https://user-images.githubusercontent.com/83843443/117513094-9bbf8400-af56-11eb-9f5a-baf230ddc3b9.PNG)

5. Follow the UI and enjoy mining !
6. If you are using the MFI version you will see an "Update miner file location" link, meaning that the miner files are correctly found and you don't have to do anything else (be aware that the mining process can still be blocked after by your antivirus). You can choose to update the files or leave it by default.

![1](https://user-images.githubusercontent.com/83843443/117512936-353a6600-af56-11eb-9f86-b232b80693ac.PNG)

### The reason why we recommend using the main (unpacked) version against the packed one (MFI) is because if the mining files are ever removed or blocked by some antivirus or similar on your PC, you will have more control to whitelist the files or re-download them. Mining files are stored in temp folders on the MFI version, which can be harder to find and to fix.
