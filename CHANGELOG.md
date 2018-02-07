Changelog:

# Version 0.72
Fixed false positive caused by leaders added via IF statements

# First Public Release

# Version 0.71
Added checking for missing shine effects

# Version 0.70
Removed false positives on EventOption missing name on hidden events
Added check for redundant EventOption name on hidden events

# Version 0.69
Added checking for non-existent unit leaders on remove_unit_leader

# Version 0.68
Fixed false positives caused by scanning for diplomatic actions in history files

# Version 0.67
Added scanning for option.d
Refined scanning for failing to check a tag is alive when firing an event; replaced with scanning for diplomatic actions

# Version 0.66
Fixed errors showing twice
Added scanning for failing to check a tag is alive when firing an event

# Version 0.65
Reworked internal code

# Version 0.64
Fixed some false positives in the flag scanning
Reworked internal code

# Version 0.63
Added scanning for spaces either side of '\n'
Added scanning for incorrect text colouring
Fixed giving an error for ideas that can be manually added

# Version 0.62
Fixed some errors being shown twice in the logs

# Version 0.61
Fixed dynamic localisation showing as missing
Fixed great war tanks showing as invalid
Fixed non-English localisation showing as invalid
Fixed scripted effects always showing as broken
Fixed firing more than one event at a time giving an error
Added checking for events with AI code but only one option
Added checking for event ID's over 10,000

# Version 0.60
Added support for checking multiple mods

# Version 0.59
Added opinion modifier checking

# Version 0.58
False positive on history/countries fixed

# Version 0.57
Fixed an error in equipment scanning

# Version 0.56
Added idea_tag problems for has_idea for custom types

# Version 0.55
Quick Fix to inverse error display

# Version 0.54
Added redundant detection for desc/picture/title on hidden events

# Version 0.53
Added invalid event definition detection

# Version 0.52
Invalid scripted_triggers usage detection added

# Version 0.51
Fixed hidden_effect false positive
Added Boolean operator redundancy check

# Version 0.50
Ideas false positive fix

# Version 0.49
Fixed some false positives

# Version 0.48
Added idea checking

# Version 0.47
More OOB checking
GFX checking added

# Version 0.46
Fixed bracket detection

# Version 0.45
Fixed config case-sensitivity bug
Fixed small parsing bugs with the new system

# Version 0.44
Completely rewrote the parser logic and made it line-based to better detect syntax errors

# Version 0.43
Country leader desc now optional

# Version 0.42
Added exception for generic focus tree

# Version 0.41a
Fixed focus checking error

# Version 0.41
Added an all config value to quickly enable all errors to show

# Version 0.40
Added mutual exclusivity checks

# Version 0.39
Improved location identification

# Version 0.38
Config logic fix

# Version 0.37
Added more focus Checks
Removed some more false positives on events

# Version 0.36
Added duplicate id checking for news events

# Version 0.35
Added news event support

# Version 0.34a
Removed some debug code

# Version 0.34
Improved event scanning

# Version 0.33
Updated config file

# Version 0.32
Added event scanning

# Version 0.31
Split up flag errors

# Version 0.30
Added a config file

# Version 0.29
Added localisation scanned, separate exe for now

# Version 0.28
Added autonomous_states and scripted_effects scanning
Added hard coded exception for minister file flag checking a.k.a. I told you so Zankoas

# Version 0.27
Flag checking added

# Version 0.26
Improved HOI4 directory detection

# Version 0.25
Made HOI4 directory detection automatic

# Version 0.24
More performance improvements
GFX parsing added but currently disabled

# Version 0.23
Vastly improved performance

# Version 0.22
Fixed broken quote detection

# Version 0.21
Minor bug fixes

# Version 0.20
Added incorrect localisation quotes detection

# Version 0.19
Added reverse OOB check

# Version 0.18
Replaced equals sign detection with line number

# Version 0.17
Disabled missing OOB
White listed give military access

# Version 0.16
Disabled empty scope
Disabled missing swap ideas

# Version 0.15
Empty value parsing fixed
Empty scope detection added

# Version 0.14
Unused unit OOB detection fixed

# Version 0.13
Unused unit OOB detection added

# Version 0.12
Added syntax checking for missing equals sign and correct bracket count

# Version 0.11
Added missing swap ideas detection

# Version 0.10
Reverse add opinion modifier CTD detection added 

# Version 0.9
Missing template detection added

# Version 0.8
Automatic mod folder detection added without breaking things

# Version 0.7
Automatic mod folder detection added
Reduced number of false positives again

# Version 0.6
Empty key value pairs now have a location

# Version 0.5b
Empty log file bug fixed

# Version 0.5
Now scans leader files for errors

# Version 0.4
Reduced number of false positives again

# Version 0.3
Reduced number of false positives

# Version 0.2
Now outputs to a log file

# Version 0.1
Initial release
