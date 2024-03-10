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

## Introduction
This codeplug was started as a personal project, then added entries for the George County ARES group when they got their DMR repeater back on the air. Now the focus has been shifted to make something for the State of Mississippi ARES team. Our goal would be to add all Mississippi Counties to the codeplug.

Mississippi ARES EC's please reach out to me and let me know how you would like your county's zone configured. This should reflect the VHF/UHF information in your ICS-205.

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

Most simplex frequencies channelized in this codeplug are as listed in the [SERA](https://sera.org/) Frequency Utilization Plans, as the frequency coordination in Mississippi is provided by them. (Could they make their website any less user friendly?) The exception(s) to this is where specific requests by specific Emergency Coordinator's were made and honored.

## Use
This codeplug (RDT file) is for the Anytone AT-D878UVII Plus radio with firmware version 3.03 running CPS version 3.03 and the radio is configured for Mode 14 (Maintenance Mode).

If your radio is not configured for Mode 14, this codeplug file cannot be installed onto your radio. We do provide all of the exported .CSV files so that you may easily import them directly into your codeplug and achieve the same results.

If there is enough interest, I may start another project to support Mode 7 (US Amateur Radio mode).

Using your favorite text editor or spreadsheet software, search for the hotspot frequency of **438.8000** and replace it with the frequncy that you used in your hotspot. You will need to search and replace the entries in both the *channels.csv* and *zones.csv* files.
