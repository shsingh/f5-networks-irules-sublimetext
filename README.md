sublime-iRules
==============

# About

iRules Syntax Highlighting for F5 Networks BIG-IP iRules syntax (http://devcentral.f5.com) for the Sublime Text Editor http://www.sublimetext.com

This was created from content found on DevCentral (http://devcentral.f5.com).

* The command completion and syntax highlighting should be complete as of TMOS v11.6 including special highlighting for deprecated commands, functions, and events.

* This includes highlighting and command completion:

   ![a relative link](../screenshots/commands.png?raw=true)

   ![a relative link](../screenshots/if.png?raw=true)

   ![a relative link](../screenshots/when.png?raw=true)


* And highligting of deprecated, removed, and illegal functions/events/commands (requires a scheme that supports the "invalid.illegal" and "invalid.deprecated" scopes and not all do. "Monokai" that ships with Sublime Text 3 does, so you can use that to test things out:

   ![a relative link](../screenshots/deprecated.png?raw=true)

This bundle was updated on July 29th, 2015 and is currently maintained by Bill Church (https://github.com/billchurch/sublime-iRules).

Any suggestions or improvements, please feel free to contact me.

The new TCL syntax was pulled from the TCL bundle that ships with Sublime Text 3.

# Installation (Package Management)

## New Way
iRules is now in the the main repository. (preferred)

- go to the command pallete (⌘+⇧+P)
- select "Package Control: Install Package"
- type "iRules" and select the iRules package

## Old Way
Using Package Control at https://packagecontrol.io/installation:

- Remove the package, if installed manually
- Add a repository: https://github.com/billchurch/sublime-iRules
- Install sublime-iRules with Package Control. It should pull the correct branch from Github

# Notes

* Verified working with Sublime Text 3 (what I'm targeting from this point).

* Deprecated events, commands, and statements obtained from: https://devcentral.f5.com/wiki/iRules.BIGIP_Commands_by_Version.ashx
