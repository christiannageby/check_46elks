# check_46elks
Simple icinga / nagios plugin for checking the current balance at 46elks account, 

## Installation
Define a new CheckCommand and insert the flags
-u <API_USERNAME> -p <API_PASSWORD>

if you want to use custom values as warning and critical statuses, append the flags
-w <WARNING_THRESHOLD> -c <CRITICAL_THRESHOLD> for a total of 4 flags.

## Disclaimer
This script is not in any way developed or maintained by 46 elks.
If you have any troubble with the service you should contact them.

