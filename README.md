# Clear Event Logs

This is a simple batch script that clears all Windows Event Logs. It uses the `wevtutil` command-line tool to clear each log.

## Prerequisites

To run this script, you need to have administrative privileges on your computer. If you do not have administrative privileges, the script will display an error message and exit.

## How to Use

* Download the file Clear_Event_Viewer_Logs.bat
* Run it as Administrator.

## Notes

* The script saves the output of the `bcdedit` and `wevtutil` commands to temporary files in the same directory as the script. These files are deleted after the script completes.
* The script has been tested on Windows 10, but should work on other versions of Windows as well.
