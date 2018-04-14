
<div align='center'>
	<img src='https://raw.githubusercontent.com/computingfoundation/gnu-linux-shell-use/images/logo.png' width='40%' alt='logo.png'>
</div>
<br><br><br>

**Gnu-linux-shell-use** is a resource of shell solutions functioning as a foundation for GNU/Linux shell use.

# Paradigms

It provides solutions in the following paradigms:

## Application management

Solutions for managing applications

* [Generic RDBMS utility functions for a MySQL database](functions_scripts/application_management/database/mysqldbutils)
* [Check if a PostgreSQL database exists.](one-liners/application_management/database/postgresql-database.one-liners)

## Scripting

Solutions for scripting

* [Bash array utilities](functions_scripts/scripting/bash/arrayutils.bash)
* [Bash date and time utilities](functions_scripts/scripting/bash/dateandtimeutils.bash)

## File management

Solutions for managing files

* [Rename all files matching a name recursively.](scripts/file_management/file_name_manipulation/renmrecr)
* [Get the size in megabytes of one or more files and/or directories.](one-liners/file_management-output_only/file_information/file-property-information-retrieval.one-liners)

## System management

Solutions for managing the system

* [List all processes owned by the current user.](aliases/system_management-output_only/process_information/process-general-information-retrieval.aliases)
* [Print the target architecture of the current operating system.](one-liners/system_management-output_only/operating_system_information/operating-system-property-information-retrieval.one-liners)

## Hardware management

Solutions for managing hardware

* [Check if the primary wireless local area network device interface is soft blocked.](scripts/hardware_management-output_only/device_information/iswlanblocked)
* [Get the vendor name of the current CPU.](one-liners/hardware_management-output_only/cpu_information/cpu-property-information-retrieval.one-liners)

## Shell management

Solutions for managing the shell

* [Execute a command in the background.](scripts/shell_management-modules/process_management/execinbg)
* [Remove the last N entries from the bash history.](scripts/shell_management/history_management/remvlastnentriesfrombashhist)

## X11 management

Solutions for managing X11

* [Get the ID of the active window.](scripts/x11_management-output_only/window_property_information/getactvwindid)
* [Get the class of a window by ID.](scripts/x11_management-output_only/window_property_information/getwindclassbyid)

## Mobile device management

Solutions for managing mobile devices

* [Watch the X and Y screen tap positions of an Android device.](scripts/mobile_device_management-android/hardware_management/watchandroiddevscreentappos)
* [Mount and unmount an MTP device.](scripts/mobile_device_management-generic/mounting/mntmtp)

## Text manipulation

Solutions for manipulating text

* [Replace all occurrences of a string recursively.](scripts/text_manipulation/matching/replrecr)

## Text processing

Solutions for processing text

* [Count the number of characters in a string.](aliases/text_processing/numeric_processing/basic-numberic-processing.aliases)

## Number processing

Solutions for processing numbers

* [Convert a hexidecimal number to decimal.](aliases/number_processing/conversion/base-conversion.aliases)

# Packaged solutions

**Gnu-linux-shell-use** has an extension repository for solutions consisting of more than one file [here](https://github.com/computingfoundation/gnu-linux-shell-use.packaged-solutions).

# Contributing

If you would like to contribute, please ensure that your contribution adheres to the respective [guideline](https://github.com/computingfoundation/gnu-linux-shell-use/wiki). Here is a list of [needed solutions](https://github.com/computingfoundation/gnu-linux-shell-use/wiki/Needed-solutions); it can be used for ideas.

An alternative implementation to an already existing solution will be accepted only if it has substantial reason, such as using a different dependency or language.

Finally, credits will be placed in the wiki.

Please send an email to main@computingfoundation.org with any suggestions, comments or questions.

Thanks.

