# WMIC Commands
The WMIc command-line (WMIC) utility provides a command-line interface for Windows Management Instrumentation (WMI). WMIC is compatible with existing shells and utility commands

An alias is a friendly renaming of a class, property, or method that makes WMI easier to use and read. 

A switch is a WMIC option that you can set globally or optionally. For a list of available switches, see WMIC switches.

To use verbs in WMIC, enter the alias name followed by the verb. If an alias doesn't support a verb, you receive the message "provider is not capable of the attempted operation." For more info, see WMIC verbs.

Returns the result of the Associators of (<wmi_object>) query where <wmi_object> is the path of objects returned by the PATH or CLASS commands. 
 ## Here is the three Links

 [Microsoft WMIC Documentation](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/wmic)

 [Microsoft Commaands Overview](https://www.sciencedirect.com/topics/computer-science/wmic-command)

 [WMIC Tutorial](https://ss64.com/nt/wmic.html)

## Here are some examples

Disk Information: You can use the following command to get disk information on your computer:

wmic diskdrive get caption, size, model


Memory Information: To get information about the physical memory, use this command:

wmic memorychip get capacity, speed, devicelocator


Video Card Information: To check your system's video card details, use this command:

wmic path win32_videocontroller get caption, deviceid, name

