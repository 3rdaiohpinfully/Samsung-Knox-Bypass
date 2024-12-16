# Samsung-Knox-Bypass
Oblivion-X is a high-risk script designed to modify system configurations on Samsung government-issued devices, disabling security features like Knox. It is intended for advanced users and should only be used on supported devices. Use at your own risk—it may cause permanent damage or bricking of the device.
README
Title: Oblivion-X Script: Overview & Functionality

The Oblivion-X Script is a powerful tool designed for advanced users to disable, remove, and bypass specific system-level restrictions and services on Samsung government-issued devices. It is intended for highly specialized scenarios, such as:

Disabling mandatory enrollment services.
Removing Samsung Knox and associated enterprise control mechanisms.
Modifying system partitions to allow full write access for customization.
Disabling SELinux for unrestricted system modifications.
Ensuring persistence by modifying boot-time initialization scripts.
Key Features:
SELinux Override: Switches SELinux from enforcing mode to disabled mode permanently, allowing unrestricted system modifications.
System Partition Remount: Grants full read-write access to protected system directories such as /system, /vendor, and /oem.
Service Removal: Aggressively stops, disables, and uninstalls enrollment and Knox-related services using both binary and package-level methods.
Boot Script Modification: Ensures that changes persist across reboots while preventing boot loops.
Reboot Management: Forces a reboot at the end of the script for changes to take effect.
How It Works:
The script executes a series of commands that directly alter the device's configuration, bypassing default protections. These include modifying SELinux policies, remounting system directories with write permissions, and forcibly removing or disabling enterprise-related packages and services.

Compatibility:
This script is compatible exclusively with Samsung government-issued devices running Android. It is not tested on consumer devices or non-Samsung hardware.

Prerequisites:
Root or administrative access on the device.
ADB setup (if using a PC to execute the script).
File manager or terminal app with support for script execution.
NOTE: The script should only be used by individuals with advanced technical knowledge and a clear understanding of its functionality.
