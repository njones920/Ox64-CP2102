# How to Configure CP2102 USB Adapters for High Baud Rates with Ox64

## Introduction

This guide demonstrates how to configure the CP2102 USB-to-UART adapters for high baud rates. This is essential for applications requiring faster data transfer rates, such as interfacing with the Ox64 board.

## Configuration Procedure

### 1. Download and Launch CP21xxCustomizationUtility
Begin by downloading the AN721SW software package, which includes the CP21xxCustomizationUtility.

**Download AN721SW software package:** [AN721SW.zip](https://www.silabs.com/documents/public/example-code/AN721SW.zip)

Extract and run the utility on your computer.



### 2. Device Selection
With the utility open, select your connected CP2102 device from the list. If it doesn't appear, verify that the adapter is properly connected and that the drivers are installed.

**Silicon Labs' official VCP drivers:** [VCP Drivers](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)



### 3. Baud Rate Alias Configuration
Go to the "Baud Rate Alias" section within the utility and expand it to access the baud rate range settings.



### 4. Set High Baud Rates
Change the upper baud rate ranges (1474561-2457600 and 2457601-xxxxxxxxx) to **2000000**. Then, click "Program Device" to update the adapter's settings.



### 5. Confirmation of Success
Once the programming is complete, the columns for the baud rate ranges should turn green, indicating a successful update.



## Verifying the Configuration
To verify the new configuration, connect the CP2102 to the Ox64 and initiate a serial session with the set baud rate. If the communication is clear, the setup is correct.

## Troubleshooting
If you encounter issues, confirm the drivers are up-to-date and the device is properly connected. Review the steps to ensure all settings are correctly applied.

For questions or further assistance, please refer to the Ox64 community forums or the GitHub issue tracker for this project.
