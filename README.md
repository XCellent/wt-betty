# wt-betty
War Thunder's Betty. Cockpit warning sounds for simulator pilots.

************************************************************************************
This sofware does not modify or comprimise the integrity of any of
the core War Thunder game files nor it does not have direct access to
memory or decompile binary files rather It simply reads Json data from
web client  at http://localhost:8111  which is available when the
game starts.
************************************************************************************

========================
ZdrytchX's Changes 2018
========================

Contacts: https://discord.gg/NKMrMxw (Kirumovka@ZdrytchX#4887) or through Github.com/ZdrytchX or through war thunder forums

-Modified "Gear Down" warning from below 500 metres / combat flaps minimum, to 20% throttle, as that's more realistic like used in aircraft like the spitfire. Previous landing warning wouldn't function above 500 metres from sea level which meant people flying on some tank arcade maps wouldn't hear the warning.

-Added "Bingo Fuel" warning with the already present sound sample, it activates between 10% and 10.2% fuel remaining, which is enough to allow even Me 163 pilots to hear the warning. This means players with about 60 minutes of fuel max will retain the warning for about 10 seconds. As long as you aren't using a long range bomber like the B-29, it should function fine. There seems to be no other reliable alternative way to code this warning in.

-Swapped the stall horn sound for the two-layererd stall sound used in jets, because it's less annoying and the information is better. Stall warning bleeps like a phone, deeper-stall warning (+ 2 degrees of user setting) is a solid tone.

========================
Before You Start
========================
This software is currently BETA and I am the only tester so there may be bugs. Please feel free to report any bugs.

========================
Bitching Betty
========================
Source: https://www.wikiwand.com/en/Bitching_Betty

Bitching Betty is a slang term used by some pilots and aircrew (mainly North American), when referring to the voices used by some aircraft warning systems.

The name "Betty" is a generic popular traditional name from American culture, and is thought not to be derived from its more recent uses to describe an attractive female (in reference to Betty Boop or Betty Rubble of The Flintstones).

The enunciating voice, in at least some aircraft systems, may be either male or female and in some cases this may be selected according to pilot preference. If the voice is female it may be referred to as Bitching Betty; if the voice is male it may be referred to as Barking Bob. A female voice is heard on military aircraft such as the F-16 Fighting Falcon, the Eurofighter Typhoon and the Mikoyan MiG-29. A male voice is heard on Boeing commercial airliners and is also used in the BAE Hawk.

===========================
What is War Thunder's Betty
===========================
War Thunder's Betty is an add-on utility for Gaijin's War Thunder. The aim of the utility is to help simulator pilots by audible warnings as desktop pilots lack the real sense of flight and a physical cockpit environment. It will forewarn before you stall your aircraft, spin your aircraft or black out. It is very useful especially for new pilots or for those who have difficulties controlling the aircraft.

===========================
Installation
===========================
1. Download
2. Unzip
3. Execute the wt-betty.exe executable (for example you may double click if you like ;)).

===========================
How to use it
===========================
Just run the software and it will begin listening for a valid flight and will start automatically when you jump into a flight. You dont have to worry about it. Just let it do its job in the background. But if you like you can still start/stop manually.

===========================
Behaviour
===========================
Currently there are 3 annunciator sounds.

1. Over G warning
2. Angle of Attack warning
3. Gear Warning (Gear Up & Gear Down)

Over-G warning annunciator will be activated when the G-Force exceeds the given threshold then Betty will call out "Over G" repeatedly. The default threshold is "6 G's", but the user can change it from options tab and save. 

Angle of Attack warning annunciator will be activated when Angle of Attack exceeds the given threshold then Betty will call out a "Stall Horn" which means you are about to stall your aircraft. Stalls can happen at any speed if you pull too hard on the stick. The Angle of Attack annuciator will be available if the gears are retracted so you will not hear anything if you are about to stall in a landing configuration (gears down position). Default threshold is 12 degrees.

Gear warning annunciator will be activated when you forget to gear up or gear down. While airborne if you forget to gear up at speeds greater than 250 km/h Betty will call "Gear up" and if you forget to gear down when you are about to land with flaps at landing configuration below 210 km/h.

I believe it is a better practice to warn the pilot earlier so thresholds are a little bit lower than the actual limits.

If you like you can enable or disable the annunciators by clicking the checkboxes next to them at options. Default they will be all enabled.

===========================
Options
===========================
Checboxes: Enable/Disable
Sliders: Change Thresholds
Text Boxes: Just edit them

===========================
Aircraft Flight Models
===========================
Not all aircraft are same. They have different performance. This software will not and can not calculate dynamic performance data for particular flight models. They are just simple thresholds. Therefore you have the option to assign your own values and save them to your preferences from the options tab.

===========================
Known Issues
===========================
The utility may not perform properly with the bombers as there is no indicator values present for bomber types.

===========================
License
===========================
GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

Copyright (c) 2016 Ahmet 'Europa' Mehmetbeyoglu
Contact me in the War Thunder forums. 
