# Mobile Legends on EXTERNAL_SDCARD

## Introduction

This script allow you to mount your Mobile Legends folder on EXTERNAL_SDCARD without reformatting it.
Using bindfs as a program to mount folders.

## Current Issues

1. Must run the script before putting in service.d directory to get full path of EXTERNAL_SDCARD.
2. In order to get full path of EXTERNAL_SDCARD, the device must have 1 External Storage attached or it will crash.

## Usage
1. Download bindfs and put it on /sdcard
2. Run the script first before putting the script to directory
3. Put the script into magisk service.d directory `/data/adb/service.d`
4. Restart to get it mounted
