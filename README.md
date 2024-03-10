# Anytone-AT-D578UVIII-Plus-Codeplug
 
> [!CAUTION]
> For AnyTone radios, the codeplug version, CPS programming software version, and the firmware version installed on the radio must all be from the same version.
>
> You must [REBUILD](#rebuild) your codeplug every time a new CPS or firmware version is installed.

## Table of Contents
 - [Background](#background)
 - [Features](#features)
 - [Usage](#usage)
 - [Rebuild](#rebuild)
 
## Background
This codeplug, if you haven't guessed, is for the AnyTone AT-D578UBIII Plus mobile radio. This is the Amateur Radio version of their models and is a tri-band radio covering the 2 meter, 1.25 meter and 70 centimeter bands.

This codeplug is a work in progress, please reach out to me if you notice any inaccuracies or would like to add repeaters in your Mississippi County.

## Features
 - 1297 Channels
 - 1167 Talk Groups
 - 65 Zones (so far)

Most English language BrandMeister talk groups are included, I have just started adding talk groups from TGIF and FreeDMR networks.

 - George County zone included
 - Stone County zone is included
 - Forest County zone is in the works
 - Lamar County zone is also in the works

Did I mention that this is primarily a codeplug for the amateur's located in the state of Mississippi?

The simplex frequencies channelized in this codeplug are as listed in the [SERA](https://sera.org/) Frequency Utilization Plans, as the frequency coordination in Mississippi is provided by them. (Could they make their website any less user friendly?) The exception(s) to this is where specific requests by specific Emergency Coordinator's were made and honored.

## Useage
This repository hosts the codeplug (RDT file) is for the Anytone AT-D858UVIII Plus radio. The codeplug is for:

 - CPS Version: 1.20 (Released 01/31/2024)
 - Firmware Version: 2.07

If your radio is not configured as above, this codeplug file should not be installed onto your radio. I do provide all of the exported .CSV files so that you may easily build them directly into a new codeplug and achieve the same results.

Using your favorite text editor or spreadsheet software, search for the hotspot frequency of **438.8000** and replace it with the frequency that you used in your hotspot. You will need to search and replace the entries in both the *channels.csv* and *zones.csv* files.

## Rebuild
Virtually all problems with the AnyTone radios are caused by residual data in a codeplug file. Rebuilding your codeplug with fresh data will help with many problems and eliminate your radio from experiencing lockups or freezing.

Do not take any shortcuts with this process. It does require a little bit of effort on your part.

 1. Make sure your CPS software version matches the firmware version currently installed in your radio.
 2. Using your CPS software, open your existing codeplug and export everything (Tool --> Export --> Export All)
 3. Use the Windows Snipping tool to record every screen in your Optional Settings or write them down. If you are using encryption, you will need to record all your encryption keys. These settings and encryption keys are not saved by the Export All process.
 4. RESET the radio. This step is very important. If you do not do this, the old and possibly problematic data in the radio will not be removed.
 5. Using your CPS software, read from the freshly reset radio.
 6. Import everything that you saved from Step 1.
 7. Complete your codeplug by reviewing your Optional Settings and encryption keys if applicable and confirm all is correct. Now is also a good time to update your DMR ID contacts list.
 8. Send the freshly rebuilt codeplug to the radio.
 9. If you had a custom startup picture or background pictures, send those to the radio.
 10. Save the new codeplug file. You should use this new save as the baseline for any future changes you may wish to make. You should also delete your old codeplug file.
 11. Use these steps to rebuild your codeplug EVERY time you upgrade your radio's firmware.