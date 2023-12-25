# Add ESP8266Littles Tool Folder

Make sure you use one of the supported versions of Arduino IDE and have ESP8266 core installed.

Download the tool from (https://github.com/ckdada1423/esp8266littlefs.git).

In your Arduino sketchbook directory, create tools directory if it doesn't exist yet.

Copy the tool into tools directory (the path will look like <home_dir>/Arduino/tools/ESP8266LittleFS/tool/esp8266littlefs.jar).

<img width="768" alt="image" src="https://github.com/ckdada1423/esp8266littlefs/assets/43586263/be8712cc-4efd-47f0-9bf7-e4d53f806af7">

Restart Arduino IDE.


# Add data folder on Arduino IDE

Open a sketch (or create a new one and save it).

Check on Tools, It will show the folder like below
<img width="593" alt="image" src="https://github.com/ckdada1423/esp8266littlefs/assets/43586263/db00bf70-6c61-413d-8f84-c14b7d589b3d">

Go to sketch directory (choose Sketch > Show Sketch Folder).

Create a directory named data and any files you want in the file system there.

Make sure you have selected a board, port, and closed Serial Monitor.

Select Tools > ESP8266 LittleFS Data Upload menu item. This should start uploading the files into ESP8266 flash file system. 

When done, IDE status bar will display LittleFS Image Uploaded message. Might take a few minutes for large file system sizes.




