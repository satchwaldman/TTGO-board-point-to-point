# TTGO-board-point-to-point

INSTALLATION INSTRUCTIONS:
1. Setup PlatformIO for VSCode, following the instruction [here](https://www.youtube.com/watch?v=JmvMvIphMnY). Though this is a bit of a long video, I recommend watching it in its entirely tp fully understand the nuance of PlatformIO.
2. Once PlatformIO is set up, navigate to to desired location for the repository and clone the Github repository as usual. 
3. Once the repository is cloned, open it in VSCode. After a few seconds, VSCode should automatically add two folders: .pio and .vscode. We will leave the .vscode folder alone but we must make changes to the .pio folder to include the Arduino LoRa library.
4. At this stage, the .pio folder should contain a folder called build, which in turn contains a folder called ttgo-lora32-v21 as well as a project.checksum file.
5. Add a folder called libdeps to the .pio folder.
6. Within the libdeps folder, add another folder called ttgo-lora32-v21.
7. Within this new ttgo-lora32-v21 folder, we will add both the Arduino LoRa library itself and an integrity.dat file. 
8. Navigate to Sandeep Minstry's Arduino LoRa library, found [here](https://github.com/sandeepmistry/arduino-LoRa)
9. Either through the terminal or by dragging the file from your folder, insert the Arduino LoRA library into the build>libdeps>sparkfun_samd21_proRF folder.
