# BullsEyeHelper

https://play.google.com/store/apps/details?id=com.companyname.BullsEyeHelper

General functionality
=====================
Enter ownship coordinates in two formats, either as dash-separated values eg. "220-50-45" (without the quotes) or equivalently "220050045" (without the quotes). This means that you are on radial 220, 50 miles out, currently heading 045. The latter format without the dashes needs to have 3 digits per coordinate value, ie. 3 digits for radial, 3 digits for distance and 3 digits for heading.
Same with enemy except no heading: An enemy on radial 135, 80 miles out from bullseye should be entered as "135-80" or "135080" (without the quotes). 
You may enter values with a leading zero (convention for heading calls), eg. 050 or 50 will work the same

New in version 2.0
==================
1) A practice mode: Figure out if an enemy aircraft is an imminent threat within 10 seconds

2) Integration with Falcon BMS: (Optional) 
  - Keying in your ownship coordinates can cost precious seconds while in the air
  - Run the companion server app BMSBullsEyeServer on the computer where Falcon BMS is running
  - Use the BMS button on the app to load the ownship coordinates directly
  - The server app BMSBullsEyeServer can be placed anywhere on the computer. First time it runs, it will usually trigger
    a firewall warning. The app needs to be whitelisted that one time and will open without issues on all subsequent invocations
 
 
