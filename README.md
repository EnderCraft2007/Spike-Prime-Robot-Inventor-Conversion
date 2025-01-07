You can either create a .zip file your self or just use the ones I included in this repo.

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*--*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*--*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*--*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*--*-*-*-*-*-*-*-*-*-*-

To create a file usable to flash the firmware onto a Spike/RI hub you will have to 
1. download the file I provided in this repository.
2. get a firmware .bin file from this repo:
   https://github.com/gpdaniels/spike-prime/tree/master/firmware
   the biger the number, the newest the version is. You can find Mindstorms,Spike 3 , Spike 2, and older Spike firmwares there. But don't try the Essential firmware for obvious reasons on your Spike/RI!
//I recommend enabling file extensions in your file explorer.
//DON'T rename the .bin file yet, you will need that name!
4. Put the .bin file into a provided .zip file! (7Zip or Winrar is a must for this task.)
5. Open the firmware.metadata.json file with a text editor! You can see where the .bin file's curent name should go. (right click on the .bin file, then rename, and you can copy and paste the name of the file.)
6. Save it, make sure it get's saved inside the .zip file!
7. change the .bin file's name to "firmware-base.bin"!
