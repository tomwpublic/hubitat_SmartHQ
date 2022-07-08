# hubitat_SmartHQ

This provides various driver capabilities for SmartHQ appliances.  Note that all operations have a cloud (internet) interaction.

This implementation is substantially based on and is mostly a direct port of this work:  https://github.com/simbaja/gehome

Installing with Hubitat Package Manager (HPM) is recommended.


# Manual Installation instructions:

Install using HPM if you can.  If you must install manually, follow these steps:

* In the *Bundles* section of hubitat, import the hubitat_smartHQ.zip bundle.
* In the *Drivers Code* section of Hubitat, add any drivers that apply to your system: smartHQ_system (always required), plus others in the `devices` subdirectory of this repository.
* In the *Devices* section of Hubitat, add a *New Virtual Device* of type SmartHQ System
* On the SmartHQ System device page, enter your SmartHQ username and password and *Save Preferences*.
    * Refresh the browser window and scroll down to confirm that component devices were created for each of your appliances.

# Usage instructions:

* Most of the commands and attributes are self explanatory.  Try things out!
* If you would like to request support for a new appliance type of additional attributes or commands:
    * Enable debug logging on the SmartHQ System device in Hubitat.
    * Open the *Logs* view in another browser tab or window and leave it open.
    * Operate the appliance manually and save the logs, then contact me on the Hubitat forum with the log and a description of what you were adjusting or operating on the appliance at the time of the log.

# Disclaimer

I have no affiliation with any of the companies mentioned in this readme or in the code.
