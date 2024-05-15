# Install Printers Batch Script

## Introduction

This batch script is designed to automate the installation of printers on a Windows system. The script installs several printers from a specified network path. It provides feedback on each printer's installation status, indicating success or failure.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Script Details](#script-details)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Requirements

- **Operating System**: Windows 7 or later.
- **Permissions**: You must have administrative privileges to run this script.
- **Network Access**: Access to the network path `\\AHW-host` where the printers are located.

## Usage

To use this script, follow these steps:

1. **Download the script**: Download the `Install_Printers.bat` or `Teacher_Printers.bat`file to your local machine, depending on what printers you want added to the computer.
2. **Run the script**: Right-click on the script file and select "Run as administrator".
3. **Follow prompts**: The script will pause for you to review the printer installation initiation. Press any key to continue.
4. **Review results**: After executing, the script will report the status of each printer installation.

## Script Details

The script performs the following actions:

1. **Initiates**: Displays an ASCII art title.
2. **Pauses**: Waits for user confirmation to proceed.
3. **Installs Printers**:
   - Installs four printers from `\\AHW-host`:
     - `Bizhub 2100 - AHW - Teachers Lounge - A`
     - `Library`
     - `Teachers Lounge - B`
     - `Front Office` (Will not be added if you are using `Teacher_Printers.bat`
   - Checks the status after each installation and displays either "SUCCESS" or "ERROR".

4. **Completes**: Indicates completion of all printer installations.

## Troubleshooting

If the script fails to install a printer, check the following:

- Ensure you have network access to `\\AHW-host`.
- Verify that you have sufficient permissions to install printers.
- Check if the specified printer paths are correct and accessible.
- If issues continue to occur, drop me an email at portpozse@gmail.com

## Contributors

- Github.com/Pozse
