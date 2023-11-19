# Firmware_template
template for new firmware project

## Prerequisite
You need to have platform io installed on your computer.

Follow installation instructions here: https://platformio.org/platformio-ide

### Mbed download bug
As of 2023, platform io has a bug where it will not download mebedOS full. So far our fix as been to mannually download and copy it to the platform io folder.


You may download MbedOS 5 from here: https://etsmtl365.sharepoint.com/:u:/s/CLUB-SONIA-GTO365/ERkumGq4ajRKpL84vJ7AhXcBgjgsxvdq-JVK0-smLZ5NpA?e=QomwSw


The mbed OS folder needs to be copied to your .platformio\packages folder in your home dirrectory. For example, on windows that would be `C:\Users\sonia-ele\.platformio\packages`. On linux that would be `/home/sonia-ele/.platformio/packages`. Replace `sonia-ele` your username. 
