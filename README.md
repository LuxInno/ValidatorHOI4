# ValidatorHOI4
This is a syntax validator that runs through the HOI4 mod files and highlights a variety of issues not found in the normal debug mode.

# Configuration
First you need to change the config file to point towards the mod files you want to scan. Second, tweak the config file to scan for what you want; the default delivered config file does not highlight all potential problems. There is a setting to show you everything, but depending on how much that is you may get an overwhelmingly long log file.

# Usage
Once you have configured the config file with your mod name and the settings that you want simply run the exe. It will generate a log.txt in the same directory once it has finished running. You can then open the logfile to start cleaning up your mod.

# Notes
Some of the issues listed do not directly create problems, but may be indirectly responsible for bugs. Bad formatting can eventually lead to syntax errors, whilst other issues may lead directly to crashing the game.

# Credits
A special thanks goes to the Kaiserreich development team for testing the early versions of the validator, providing ideas for features as well as valuable feedback. A big additional thanks goes to Zankoas, one of the project leads, who has maintained the changelog and coordinated feedback.

# Contact
Please use the Issues in github to report bugs or request features.
