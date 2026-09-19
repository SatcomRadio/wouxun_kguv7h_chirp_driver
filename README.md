# Chirp driver for the Wouxun KG-UV7H

This repo consists of a chirp driver for controlling the Wouxun KG-UV7H radio

<img src="./doc/kguv7h.jpeg" alt="KG-UV7H Radio" width="300"/>

----

To run it, please follow this instructions:

1 - Make sure you have a **recent** version Chirp. You can download the latest version from its [official site](https://chirpmyradio.com/projects/chirp/wiki/Download#)

2 - Download the kg-uv7h driver from [here](https://github.com/SatcomRadio/wouxun_kguv7h_chirp_driver/blob/main/kguv7h.py)

You need to press this button to download the file

<img src="./doc/download.png" alt="Download driver" width="600"/>

3 - Open Chirp and enable developer mode

<img src="./doc/dev.png" alt="Developer mode" width="400"/>

4 - Press ok on the warning and **restart** Chirp. Close the program and open it again

<img src="./doc/devwarn.png" alt="Developer mode warning" width="400"/>

<img src="./doc/devwarn2.png" alt="Developer mode warning" width="400"/>

5 - Open the option `File->Load Module`. If this option does not appear, make sure that you've enabled developer mode and **restart** Chirp

<img src="./doc/loadmod.png" alt="Load module" width="400"/>

6 - Select the driver file you've downloaded in step #2

<img src="./doc/modselect.png" alt="Select driver" width="600"/>

7 - Select the option `Radio->Download from radio` to read the radio configuration

<img src="./doc/readradio.png" alt="Download from radio" width="400"/>

8 - As the driver is now loaded, the KG-UV7H model should be displayed in the dropdown

<img src="./doc/modelselect.png" alt="Radio model select" width="400"/>

9 - Make a backup of your file by going to `File->Save As` and save it as `OriginalFW.img`

<img src="./doc/save.png" alt="Save file" width="200"/>

9 - You can now edit advanced features of the radio such as RX, modulation, bands and power levels.

10 - Once you are happy with the results go again to `File->Save As` and save it as `ModdedFW.img`

<img src="./doc/save.png" alt="Save file" width="200"/>

11 - You can now write the changes to the radio by going to `Radio->Upload to radio`

<img src="./doc/upload.png" alt="Save file" width="200"/>


-----

In case you need an original firmware, you can download the original .img files that my radio uses.