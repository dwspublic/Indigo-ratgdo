# Indigo-ratgdo
Plugin for the Indigo Home Automation system to communicate with the ratgdo controller via MQTT

## Installation

Install ratgdo controller per the instructions at https://paulwieland.github.io/ratgdo/. Install the 
default firmware for MQTT support.  Configure the controller to connect to your MQTT broker. Set the
MQTT topic prefix to "ratgdo/"

Install the plugin as usual.  Create a new ratgdo device and enter the name of the controller (same as
the "Device Name" in the ratgdo configuration).

Create a trigger using the plugin Menu command.  This is only done once.

Since Indigo does not have a cover (door) device, the plugin represents the door as a lock device. 
The device is locked when the door is closed and unlocked when the door is open.
