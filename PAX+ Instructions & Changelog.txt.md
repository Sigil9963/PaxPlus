# PaxPlus
A set of configurations for the PAX build of Hawken

#Installation Instructions:

-Extract the [PAX Client](https://drive.google.com/file/d/1bXj0wxjNct_kvndWWufxPqKWVnHdP2zV/view?usp=sharing) to a location of your choice.  
-Download this ini mod.  
-Navigate to `pax-client\hawken\Hawken-PC-Shipping\` folder, drag and drop the `HawkenGame` folder from this mod.  
-Navigate to `Documents\My Games` folder, drag and drop the `Hawken` folder from this mod.  
-Run the PAX Client from its included .bat file as normal.  

###Resolving conflicts with multiple installations

This allows you to have Hawken PAX and Hawakening installed at the same time without having setting conflicts.

Navigate to `pax-client\hawken\Hawken-PC-Shipping\HawkenGame\Config` and open `DefaultEngine.ini`
-Ctrl+F for `MyDocumentsSubDirName=Hawken` in `DefaultEngine.ini` and change the line to `MyDocumentsSubDirName=HawkenPAX`
-Navigate to `Documents\My Games` folder, drag and drop the `Hawken` folder from this mod, rename the folder to `HawkenPAX`

###Default Settings & Additional Configuration

By default the following settings will be applied:

-FOV set to 110. Override in `Documents\My Games\Hawken\HawkenGame\Config\HawkenGame.ini`  
-Visual noise effect will be disabled. Enabled via `Documents\My Games\Hawken\HawkenGame\Config\HawkenEngine.ini`  
-Motion Blur and Depth of Field are disabled. Enabled via `Documents\My Games\Hawken\HawkenGame\Config\HawkenSystemSettings.ini`  
-To change keybind for utility function of secondary weapons, change `Bindings=(Name="MiddleMouseButton",` in `Documents\My Games\Hawken\HawkenGame\Config\HawkenInput.ini`.  
Mouse 4 and Mouse 5 are `ThumbMouseButton` and `ThumbMouseButton2` respectively.

#Changes:  
-Weapon stats changed to Hawken 2017 patch values
-Mech stats changed to Hawken 2017 patch values
-Item stats changed to Hawken 2017 patch values
-Dodge no longer costs fuel
-Dodge cooldowns changed to 1s/1.2s/1.4s for A-/B-/C-Classes
-Created Incinerator preset
-Created Marauder preset
-Created M2-Assault preset
-Created Prototype Predator preset
-Unlocked Seeker, Tri-Seeker primary weapons
-Unlocked Sticky Mine, Proximity Mine, Homing Missile Turret, Drone Fighter Offensive items
-Unlocked Blockade Defensive item
-Unlocked Radar, Sensor, Utility items

Modifications to the base mech format was done through use of the Optimization Tree System. **DO NOT USE THE OPTIMIZATION TREE SYSTEM WITH THIS MOD**

#Items
Some of the unlocked items may not work correctly or at all.
###Sticky Mine
-Launches a proximity mine that explodes for 60 damage in a 9m radius.

###Laser Mine
-Launches a laser-tripwire mine that explodes for 65 damage in a 11m radius.

###Homing Missile Turret
-Deploys a turret that fires seeking missiles. Missiles do 35 damage.

###Drone Fighter
-Deploys a wandering allied drone that fires on enemies with a machine gun. Fights until destroyed. Retaliates to friendly fire.

###Shield
-Launches an orb that projects a bubble shield on impact. Shields are one way barriers with 450 health. Shields can be stuck to allied mechs.

###Blockade  
-Launches an orb that transforms into a large, hardlight barrier on contact with a surface. Lasts 20 seconds before slowly shrinking over 8 seconds.

###EMP
-Disables weapons and items from mechs caught in the blast radius.
-Reduced EMP duration from 6 seconds to 4.25 seconds. Reduced blast radius from 25m to 24m.

#Abilities
###Damage Boost
-Deal 15% more damage for 6.5 seconds. 52 second recharge.

###Damage Absorb
-Absorb 65% of incoming damage for 1.25 seconds. 16 second recharge.

###Camoflage
-Become nearly invisible for 8 seconds and gain a 6m/s boost speed increase. 40 second recharge.

###Fuel Reserves
-Recharge 5.7 units of fuel over 1 second, and gain a brief 6m/s boost speed increase. 52 second recharge

###Jet Boosters
-Increase walk speed by 12.4m/s and boost speed by 14.8m/s for 8 seconds. 55 second recharge

#Mech Presets:
##A-Class
###Berserker
-Ability: Damage Absorb
-Default Weapons: SMC & Point-D Vulcan, also intended to work with Assault Rifle
-Secondary: TOW Rocket

###Infiltrator
-Ability: Camoflage
-Default Weapons: Assault Rifle and HEAT Cannon, also intended to work with EOC Repeater
-Secondary: Grenade Launcher

###Reaper*
-Ability: Damage Boost
Default Weapons: SA-Hawkins and Slug Rifle
-Secondary: Sabot Rifle
*The Reaper has extensive modifications to increase its rate of fire and reduce its heat generation compared to the Sharpshooter platform, at the cost of firepower

###Scout
-Ability: Fuel Reserves
Default Weapons: Mini-flak and Flak Cannon, also intended to work with HEAT Cannon
-Secondary: TOW Rocket

##B-Class
###Assault
-Ability: Damage Absorb
-Default Weapons: SMC & Point-D Vulcan, also intended to work with Assault Rifle
-Secondary: TOW Rocket

###M2-Assault*
-Ability: Damage Boost
-Default Weapons: Point-D Vulcan
-Secondary: Sabot Rifle
Sentium refinements on Prosk's Reaper-modified Sabot Rifle have allowed for belt fed, small caliber rounds, combined with improvements to the Assault plaform since its inception create a terrifying skirmisher and a hail of hot lead.

###Bruiser
-Ability: Damage Absorb
-Default Weapons: Point-D Vulcan & Assault Rifle, also intended to work with SMC
-Secondary: Hellfire Missiles

###Prototype Predator*
-Ability: Camoflage
-Default Weapons: Slug Rifle & Flak Cannon, NOT intended to work with EOC Repeater 
-Secondary: Grenade Launcher
*Pressed into service well before it was ready for the field, this prototype mech builds off the success of the Infiltrator platform but lacks the developments that the heavier B-Class chassis was intended to use.

###Raider*
-Ability: Jet Boosters
-Default Weapons: Mini-flak and Flak Cannon, also intended to work with EOC Repeater
-Secondary: TOW Rocket
*The Raider platform sacrifices armor for speed and firepower. Its TOW Rockets have increased damage.

###Sharpshooter
-Ability: Damage Boost
-Default Weapons: SA-Hawkins and Slug Rifle
-Secondary: Sabot Rifle

##C-Class
###Brawler
-Ability: Damage Absorb
-Default Weapons: Flak Cannon & SA-Hawkins, also intended to work with Point-D Vulcan
-Secondary: TOW Rocket

###Grenadier
-Ability: Damage Boost
-Default Weapons: Point-D Vulcan & HEAT Cannon
-Secondary: Grenade Launcher

###Incinerator*
-Ability: None
-Default Weapons: Point-D Vulcan & SMC
-Secondary: MRLS
*The Incinerator platform's weapons have massive heat generation to feed its MRLS secondary, which discharges this heat as a cluster of fireballs.

###Marauder*
-Ability: Jet Boosters
-Default Weapon: Flak Cannon
-Secondary: TOW Rocket
*Prosk modifications to the Sentium Raider platform. Slower, but more heavily armored and packing even more powerful TOW Rockets.

###Rocketeer
-Ability: Damage Absorb
-Default Weapons: Seeker & HEAT Cannon,also intended to work with EOC Repeater
-Secondary: Hellfire Missiles

###Vanguard
-Ability: Damage Absorb
-Default Weapons: SMC & Mini-flak Cannon, also intended to work with Point-D Vulcan
-Secondary: Grenade Launcher

#Changelog

1.2: Corrected splash radius on explosive weapons. Reduced Incinerator heat generation. Reduced MRLS heat dispersion. Corrected Seeker flight speed.
1.1: Changed a line to properly not affect mech speed. #decreasethespeeds.
1.0: Initial release.
