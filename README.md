# M2KC-Streamdeck-profile-for-DCS-Interface
Mirage 2000C profile for use with DCS interface on a Stream Deck

ALPHA version 0.8

This alpha release of a Mirage 2000 profile to be used with DCS Interface for Streamdeck

what you need:
- DCS
- the Mirage 2000C module by Razbam
- a streamdeck
- DCS Interface ==> https://github.com/charlestytler/streamdeck-dcs-interface
- DCS Interface requires DCS Exports Scripts (https://github.com/s-d-a/DCS-ExportScripts)
- DCS Export Scripts M-2000 module is not working properly, until this is corrected, you'll need to swap this my version with the one supplied by DCS Export Scipts (MANDATORY for PCA and Fueld Flow display to work !)

Once you have all DCS Export Scripts and DCS Interface running, just upload the profile and off you go...

What's new in this version:
 Implementation of the VHF radio (Absolutely requires the M-2000C.lua file !!)
 Implementation of the test for Autopilot and Fly-by-Wire systems
 Correction of a bug in the fuel pump


What works:
Master Arm / PCA / PPA
Autopilot (basic functions)
Fuel Flow and Afterburner indicators
master caution indicator
Radio (only frequency display ATM)
PCN / INS (basic functions to enable you to align when on the ground)
TACAN frequency setting
Engine management
Caution / Warning Lights
External lights
VTH panel
Radar (base functions)

What does not work well : VOR/ILS frequency setting
Radio UHF frequency setting

What is to be implemented next
ECM / countermeasures
internal lights

Please let me know any issue/bug you encounter and what you'd really want to have

INS icons from RazzleeffDazzle ==> https://www.digitalcombatsimulator.com/en/files/3309542/
M-2000 icon from Togg
