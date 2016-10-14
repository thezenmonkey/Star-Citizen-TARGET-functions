# Star-Citizen-TARGET-functions
Thrustmaster TARGET script keymap for Star Citizen

To use this file, include it your main target script
```
include "target.tmh"
include "Macros Star Citizen PreAlpha.ttm"  //call the other file with keystrokes
					// create a Virtual device
int main()
{
//Your Script Goes Here
}
int EventHandle(int type, alias o, int x)
{
	DefaultMapping(&o, x);
}
```

Then use the defined macros instead of hardcoding the keybings 
```
MapKey(&T16000L, TS3, Afterburner);
```

When keybinds change, just download the new Macro file and leave your target bindings as is
