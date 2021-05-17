# unMineable - Easy mining app releases
Official repository for hosting the latest versions of our easy mining app!

## Versions and info

Two versions are available, main version and "Mining files included" (MFI) version, previously known as "Unpacked" and "Packed" versions respectively.

Using the MFI version is very straight forward to use as it already includes the mining files (PhoenixMiner.exe / xmrig.exe), however **it is not recommended**, because the mining files can be removed during the download (by an antivirus or similar), rendering the app unusable, you would need to re-download and point the app to the new miner files, which is the same as using the main version anyway :) (Main version was previously known as the unpacked version).

#### We recommend using the main (unpacked) version against the packed one (MFI) because if the mining files are ever removed or blocked by your antivirus or similar, you will have more control to whitelist the files or re-download them. Mining files are stored in temp folders on the MFI version, which can be harder to find and to fix.

## Upgrading from 1.0.1-beta

If you are upgrading from the previous version, download the new main version (not the MFI), it will use your previously saved address and settings. The MFI and the main version not longer share the same settings (are independent), so if you download the MFI version now you will need to set your address and coin again.

## How to setup

Both versions have the same configuration and options, the setup is the same for both:

1. Download the latest mining app from releases.
2. Unzip the file and run it, then go to the mining hardware screen, _if you downloaded the MFI version go to step 6._
3. You will be asked to select the miner file location, **PhoenixMiner.exe for GPU mining or xmrig.exe for CPU mining.**, you need to manually download the files from their official repositories / links, it's very easy actually. :)

![2](https://user-images.githubusercontent.com/83843443/117513094-9bbf8400-af56-11eb-9f5a-baf230ddc3b9.PNG)

You can get both files from here:

* PhoenixMiner: https://phoenixminer.info/downloads/
* xmrig: https://github.com/xmrig/xmrig/releases

![Screenshot 2021-05-16 195321](https://user-images.githubusercontent.com/83843443/118419082-a083e680-b680-11eb-9ff0-108d871962e4.png)

![xmrig](https://user-images.githubusercontent.com/83843443/117563186-ccdca900-b069-11eb-8356-de813dd9e089.PNG)

Download the latest version available (the app is designed for Windows 10 x64), after unzipping the files **you will have the PhoenixMiner.exe and / or xmrig.exe files.**

4. Simply point the app to the just downloaded .exe **(GPU -> PhoenixMiner.exe, CPU -> xmrig.exe).**

![2](https://user-images.githubusercontent.com/83843443/117513094-9bbf8400-af56-11eb-9f5a-baf230ddc3b9.PNG)

5. Follow the UI and enjoy mining !
6. If you are using the MFI version you will see an "Update miner file location" link on the first start, meaning that the miner files are correctly found and you don't have to do anything else (be aware that the mining process can still be blocked after by your antivirus). You can choose to update the files or leave it by default.

![1](https://user-images.githubusercontent.com/83843443/117512936-353a6600-af56-11eb-9f86-b232b80693ac.PNG)
