# NFSC - Tier 3 Car Balancing Update
### Changelog/Patch Notes:  
*Note: Changes to Tier 1 and 2 Cars only apply to the 'MW Style Upgrades' installation options, or to Ultimate Mod installation.

**v1.7 - Lots of changes, Engine sounds from MW, Engine + Caraudio mini-overhaul.**  
**(dd/mm/yyyy)**  
**(02/09/2026)**  

# Scripts and installation

### MW Style Upgrades
You now have the option to add cop car frontend logos during the Binary/Binarius installation.
These were *finally* copied over from the bonus cars mod, so you no longer have to download and install only the binary part of an entirely separate mod.

Added several engine sounds from NFSMW 2005, and a few sounds from Prostreet.
Not all sounds are listed, only the notable ones.

NFSMW Sounds:
- corvette_z06_v2 (CarID 74) (NFSMW Corvette C6 Sound)
- pon_gto_exh (GIN_GTO_65.gin) (CarID 73)
- for_mus_gt_c (GIN_Mustang_GT_C.gin) (CarID 74)
* for_mus_gt_b was planned, but the abk files are bugged out, basically a combination of for_mus_a and for_mus_b, but sounds aren't correctly pitched.
- am_db9 (GIN_DB9.gin) (CarID 75) (Stock DB9 sound from MW)
- am_db9_upgr (GIN_DB9_upgrd.gin) (CarID 75)
- mbz_clk500 (GIN_MBZ_CLK500.gin) (CarID 57)

Prostreet Sounds:
Note: All Prostreet sounds are from Yash's 'Prostreet Car Sounds (gin files) to Carbon (Moddders Resource)' Mod.
Full credit goes to Yash for converting tmx files to gin, and the mod itself.
- https://nfsmods.xyz/mod/693
Please note that for the prostreet sounds, the intention isn't for them to be 1:1 re-creations as they were in Prostreet.
Prostreet TMX -> Ginsu sounds were mainly used to create new car sounds that also use existing ABK's from MW and Carbon.
Keep in mind that using a CarID of 100 or above will cause the car to use the dump truck audio, so vanilla CarID's had to be repurposed.
Some engineaudio files are not named correctly (compared to Prostreet), either because they match with a certain CarID, or they were initially made for a certain car.

- cor_z06_a_eng (car-073-eng-3.gin) (CarID 85)
- cor_z06_a_eng_2 (car-073-eng-1.gin) (CarID 85)
- pon_gto_exh_2 (car-073-exh-2.gin) (CarID 73) *cor-z06-a in prostreet, but matches with the CarID of GIN_GTO_65.gin.
- pon_gto_exh_3 (car-101-exh-2.gin) (CarID 73) *pon_gto_a in prostreet.
- mbz_sl65_2 (car-128-exh-1.gin) (CarID 59, same as MW/C Sl65)
- kon_ccx_exh (car-106-exh-2.gin) (CarID 85)
- aud_r8_eng (car-120-eng-3.gin) (CarID 87) (used where high revving v8 front engine sounds are needed, mainly for V8 Exotics)

# Cop Cars 

## Player Police Civic Cruiser (Tier 3) (Vanilla, ImpMod)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9.875 to 9

- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.1 to 2.9
	
## Player Police Cross C6 (Tier 3) (Vanilla)
- ecar:
	- Reduced RideHeight from 0 to -0.3

- Engine Max Upgraded:
	- Slightly increased torque values (MW 1.125x -> MW 1.15x)
	
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.5 to 3.3

- Stock Suspension:
	- Increased RIDE_HEIGHT Front from 7 to 8.85
	- Increased RIDE_HEIGHT Rear from 7 to 8.85
	
- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.33 to 0.35
	- Increased RIDE_HEIGHT Front from 6 to 7.5
	- Increased RIDE_HEIGHT Rear from 6 to 7.5
	- Increased SHOCK_EXT_STIFFNESS Front from 85 to 95
	- Increased SHOCK_EXT_STIFFNESS Rear from 85 to 95
	- Increased SHOCK_STIFFNESS Front from 70 to 80
	- Increased SHOCK_STIFFNESS Rear from 70 to 80
	- Increased SPRING_STIFFNESS Front from 650 to 750
	- Increased SPRING_STIFFNESS Rear from 675 to 875
	- Increased SWAYBAR_STIFFNESS Front from 260 to 360
	- Increased SWAYBAR_STIFFNESS Rear from 260 to 360
	
- Tires Max Upgraded:
	- Increased STEERING from 1 to 1.05

## Player Police Corvette Z06 (Normal and Undercover) (Tier 3) (Vanilla, ImpMod)
- Stock Engine:
	- Increased FLYWHEEL_MASS from 14 to 15

- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.44 to 0.45
	- Reduced SHOCK_VALVING Front from 24 to 22
	- Reduced SHOCK_VALVING Rear from 24 to 22
	- Reduced SPRING_PROGRESSION Front from 7.5 to 7
	- Increased TRAVEL Front from 7 to 7.5
	- Increased TRAVEL Rear from 7 to 7.5

- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.44 to 0.45
	- Reduced RENDER_MOTION from 1 to 0.75
	- Increased RIDE_HEIGHT Front from 7 to 7.5
	- Increased RIDE_HEIGHT Rear from 7 to 7.5
	- Increased SHOCK_DIGRESSION Front from 0.2 to 0.45
	- Increased SHOCK_DIGRESSION Rear from 0.2 to 0.45
	- Increased SPRING_PROGRESSION Front from 7 to 7.5

# Vanilla Cars

# Exotics

## Alfa Romeo Brera (Tier 1)
- Changed stock exhaustaudio sound from nis_sky to nis_300zx.

- Stock Engine:
	- Slightly increased torque values (1.025x -> 1.044x)
	
- Suspension Max Upgraded:	
	- Reduced ROLL_CENTER from 10.5 to 10
	
- Tires Max Upgraded:
	- Increased GRIP_SCALE Front from 1.05 to 1.1
	- Increased GRIP_SCALE Rear from 1.1 to 1.11
	- Increased STEERING from 0.8 to 0.9

## Mercedes Benz CLK-500 (Tier 1)
- Engine Max Upgraded:
	- Slightly increased torque values (MW 1.1x -> MW 1.119x)

- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.35 to 0.3375

- Induction Max Upgraded:
	- Reduced LOW_BOOST from 0.11 to 0.1
	
## Aston Martin DB9 (Tier 2)
- Engine Max Upgraded:
	- Slightly increased torque values (MW 1.0605x -> MW 1.09x)
	
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.3525 to 0.35
	
## Lotus Elise (Tier 2)
> The Elise should now handle faster and feel more like its MW counterpart.

- Stock Suspension:
	- Reduced SHOCK_EXT_STIFFNESS and SHOCK_STIFFNESS values to match the MW stock values.

- Suspension Max Upgraded:
	- Reduced SHOCK_EXT_STIFFNESS Front from 70 to 45
	- Reduced SHOCK_EXT_STIFFNESS Rear from 72 to 45
	- Reduced SHOCK_STIFFNESS Front from 65 to 35
	- Reduced SHOCK_STIFFNESS Rear from 62 to 35 
	- Reduced SPRING_STIFFNESS Front from 585 to 500
	- Reduced SPRING_STIFFNESS Rear from 485 to 400

- Tires Max Upgraded:
	- Improved steering range by 12.5%.
	- Ported over MW YAW_CONTROL values.
	
## Lotus Europa (Tier 2)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9.75 to 9

## Jaguar XK (Tier 2)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9.5 to 9

- Tires Max Upgraded:	
	- Increased STEERING from 0.9 to 0.925

## Porsche Cayman S (Tier 2)
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.2725 to 0.27
	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.375 to 0.4

## Ford GT (Tier 3)
> The stock Ford GT is now faster, with some trade-offs to its stock chassis and transmission.

- Stock Engine:
	- Now uses torque values from MW's stock Ford GT
	
- Stock Transmission:
	- Reduced GEAR_EFFICIENCY[2] from 0.98 to 0.8 (First Gear)
	- Reduced GEAR_EFFICIENCY[3] from 1 to 0.82 (Second Gear)
	- Reduced GEAR_EFFICIENCY[4] from 1 to 0.98 (Third Gear)
	
- Transmission Max Upgraded:
	- Increased CLUTCH_SLIP from 0.75 to 0.9
	
- Stock Suspension:
	- Increased AERO_COEFFICIENT from 0.205 to 0.215
	- Increased DRAG_COEFFICIENT from 0.3 to 0.38
	- Reduced SHOCK_VALVING Front from 20 to 17
	- Reduced SHOCK_VALVING Rear from 20 to 17
	- Reduced SPRING_PROGRESSION Front from 7.6 to 6.6
	- Reduced SPRING_PROGRESSION Rear from 8 to 7
	
- Stock Supercharger:
	- Increased HIGH_BOOST from 0.2 to 0.25
	- Increased LOW_BOOST from 0.2 to 0.25
	- Increased SPOOL_TIME_DOWN from 0 to 0.25
	- Increased SPOOL_TIME_UP from 0 to 1.5
	
## Koenigsegg CCX (Tier 3)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9.251 to 8.551
	
## Lamborghini Gallardo (Tier 3)
- Suspension Max Upgraded:
	- Increased AERO_CG from 46.25 to 47.75
	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.305 to 0.325
	
## Lamborghini Murcielago (Tier 3)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9 to 8.7 (MW Value)

- Tires Max Upgraded
	- Increased GRIP_SCALE Front from 1.05 to 1.1
	- Increased GRIP_SCALE Rear from 1.1 to 1.12
	
## Porsche 911 GT3-RS 997 (Tier 3)
- Suspension Max Upgraded:
	- Increased RIDE_HEIGHT Front from 8.5 to 9
	- Increased RIDE_HEIGHT Front from 8.5 to 9
	- Reduced ROLL_CENTER from 9 to 8.5
	- Increased SPRING_STIFFNESS Rear from 830 to 925
	
- Tires Max Upgraded:
	- Slightly improved steering range
	
## Porsche Carrera GT (Tier 3)
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.29 to 0.3
	
## Porsche 911 Turbo 997 (Tier 3)
- Transmission Max Upgraded:
	- Increased FINAL_GEAR from 3.025 to 3.125 (Vanilla value)
	
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 10 to 9
	
# Muscle Cars

## Chevrolet Camaro SS (Tier 1)
- Suspension Max Upgraded:
	- Reduced RIDE_HEIGHT Front from 7 to 6.75
	- Reduced RIDE_HEIGHT Rear from 7 to 6.75
	- Reduced ROLL_CENTER from 11.5 to 11
	
## Chevrolet Chevelle SS (Tier 1)
- Suspension Max Upgraded:
	- Increased SPRING_PROGRESSION Front from 6 to 7.25
	- Increased SPRING_PROGRESSION Front from 7 to 8.25
	
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.266 to 0.269
	- Increased LOW_BOOST from 0.266 to 0.269
	- Reduced SPOOL_TIME_UP from 1.75 to 0.75

## Chrysler 300c SRT-8 (Tier 1)
- Stock Engine:
	- Increased torque values by 21%

## Dodge Charger R/T 1969 (Tier 2)
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.3325 to 0.35
	- Increased LOW_BOOST from 0.3325 to 0.35
	
## Dodge Charger SRT-8 2006 (Tier 2)
- Stock Engine:
	- Increased torque values by 7.5%

- Suspension Max Upgraded:
	- Increased AERO_CG from 47.5 to 51
	
## Ford Mustang GT (Tier 2)
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.385 to 0.44
	
## Plymouth Roadrunner (Tier 2)
- Tires Max Upgraded:
	- Reduced YAW_CONTROL[0] from 0.1 to 0.025
	- Reduced YAW_CONTROL[1] from 0.2 to 0.05
	- Reduced YAW_CONTROL[2] from 0.3 to 0.075
	- Reduced YAW_CONTROL[3] from 0.35 to 0.15
	
## Vauxhall Monaro VXR (Tier 2)
- Engine Max Upgraded:
	- Very slightly improved mid range torque values.

## Chevrolet Camaro Concept (Tier 3)
- Suspension Max Upgraded
	- Reduced RENDER_MOTION from 0.75 to 0.5

## Dodge Challenger Concept (Tier 3)
- Brakes Max Upgraded:
	- Increased EBRAKE power from 750 to 900
	
## Shelby GT500 1967 (Tier 3)
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.325 to 0.33
	- Increased LOW_BOOST from 0.325 to 0.33
	
## Shelby GT500 2007 (Tier 3)
- Transmission Max Upgraded:
	- Increased CLUTCH_SLIP from 0.701 to 0.8
	
- Suspension Max Upgraded:
	- Increased AERO_CG from 47.75 to 48

# Tuners

## Lexus IS300 (Tier 1)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.4 to 3

- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.33 to 0.3325
	- Increased LOW_BOOST from 0.33 to 0.3325

## Mazda Mazdaspeed 3 (Tier 1)
- Suspension Max Upgraded:
	- Increased SHOCK_STIFFNESS Rear from 55 to 60
	- Increased SPRING_STIFFNESS Rear from 600 to 650

- Tires Max Upgraded:
	- Increased GRIP_SCALE Front from 1.05 to 1.06
	- Increased GRIP_SCALE Rear from 1.075 to 1.09
	- Increased STATIC_GRIP Front from 1.95 to 2
	- Increased STATIC_GRIP Rear from 2.05 to 2.1
	- Increased YAW_SPEED from 0.385 to 0.4
	
## Mazda RX-8 (Tier 1)
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.305 to 0.3065
	- Increased LOW_BOOST from 0.305 to 0.3065

## Nissan 240sx (Tier 1)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 9.25 to 8.5
	- Slightly increased torque values.
	
- Suspension Max Upgraded:
	- Reduced AERO_COEFFICIENT from 0.2565 to 0.2425
	- Reduced ROLL_CENTER from 8.9 to 8.5
	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.3825 to 0.385
	
## Mazda RX-7 (Tier 2)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 8.8 to 8.5
	
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.25 to 0.2533
	- Increased LOW_BOOST from 0.25 to 0.2533

## Mitsubishi Eclipse GS-T 1999 (Tier 2)
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 1.6 to 1.7
	- Increased DYNAMIC_GRIP Rear from 1.7 to 1.8
	- Increased STATIC_GRIP Rear from 2 to 2.05
	
## Mitsubishi Eclipse GT (Tier 2)
- Suspension Max Upgraded:
	- Reduced AERO_COEFFICIENT from 0.265 to 0.26

- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.4 to 0.425
	- Increased LOW_BOOST from 0.4 to 0.425
	
## Renault Clio V6 (Tier 2)
- Stock Suspension:
	- Increased AERO_COEFFICIENT from 0.16 to 0.17
	
- Stock Tires:
	- Increased YAW_SPEED from 0.315 to 0.325
	
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 12 to 11.75
	
## Toyota Corolla GT-S (Tier 2)
- Tires Max Upgraded:
	- Improved steering range.
	- Reduced YAW_CONTROL[0] from 0.4 to 0.1
	
## Toyota MR2 (Tier 2)
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 1.925 to 2
	- Increased DYNAMIC_GRIP Rear from 1.975 to 2.1

## Volkswagen Golf R32 (Tier 2)
- Stock Engine
	- Increased torque values by 8.96%
	
- Stock Suspension
	- Increased DRAG_COEFFICIENT from 0.3 to 0.35
	- Increased TRAVEL Front from 7 to 7.1
	- Increased TRAVEL Rear from 7 to 7.1

## Infiniti G35 (Tier 3)
- Engine Max Upgraded:
	- Slightly increased torque values (1.885x -> 1.893x)
	
## Mitsubishi Lancer Evolution 9 (Tier 3)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.475 to 3.4
	- Increased SHIFT_SPEED from 0.1 to 0.2
	
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.39 to 0.38225
	
- Tires Max Upgraded:
	- Reduced STEERING from 1.15 to 1.1
	
- Induction Max Upgraded:
	- Reduced SPOOL_TIME_UP from 2 to 1.5

## Nissan 350z Z33 (Tier 3)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 2.84 to 2.8

## Nissan Skyline GTR R-34 (Tier 3)
- Induction Max Upgraded:
	- Increased LOW_BOOST from 0.2 to 0.225
	
## Subaru Impreza WRX ST-i GDB-F (Tier 3)
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.39 to 0.38225
	- Increased SHOCK_EXT_STIFFNESS Front from 75 to 80
	- Increased SHOCK_STIFFNESS Rear from 60 to 65
	- Increased SHOCK_VALVING Front from 24 to 25
	- Increased SHOCK_VALVING Rear from 24 to 25
	- Reduced TRAVEL Front from 6 to 5.75
	- Reduced TRAVEL Rear from 6 to 5.75
	
- Tires Max Upgraded:
	- Reduced STEERING from 1.175 to 1.1
	- Improved steering range by 12.5%

## Toyota Supra:
- Engine Max Upgraded:
	- Slightly increased torque values (MW 1.075x -> MW 1.09x)
	
- Transmission Max Upgraded:
	- Increased FINAL_GEAR from 2.64 to 2.7
	
- Suspension Max Upgraded:
	- Increased SPRING_STIFFNESS Rear from 725 to 775

# Improvement Mod v2 + Ultimate Mod Shared Cars

# Exotics

## Porsche 911 Turbo 996 (Tier 3)
- Engine Max Upgraded:
	- Increased FLYWHEEL_MASS from 9.5 to 10

- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.35 to 0.36
	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.475 to 0.485
	
- Stock Brakes:
	- Reduced Front brake power from 450 to 400
	
- Brakes Max Upgraded:
	- Ported over MW Brakes values
	
- Induction Max Upgraded
	- Increased HIGH_BOOST from 0.3 to 0.32
	- Increased LOW_BOOST from 0.4 to 0.43

# Improvement Mod v2 Cars

# Exotics

## Audi A3 (Tier 2)
- Stock Engine:
	- Increased RED_LINE from 6500 to 7000
	- Increased MAX_RPM from 7500 to 8000

- Engine Max Upgraded:
	- Increased RED_LINE from 6750 to 7000
	- Increased MAX_RPM from 7750 to 8000
	
- Transmission Max Upgraded:
	- Increased FINAL_GEAR from 3.4 to 3.625
	
- Stock Suspension:
	- Reduced SWAYBAR_STIFFNESS Rear from 230 to 220
	- Increased SHOCK_DIGRESSION Front from 0.1 to 0.2
	- Increased SHOCK_DIGRESSION Rear from 0.1 to 0.2
	
- Suspension Max Upgraded:
	- Reduced SHOCK_DIGRESSION Front from 0.2 to 0.1
	- Reduced SHOCK_DIGRESSION Rear from 0.2 to 0.1
	- Increased SWAYBAR_STIFFNESS Rear from 220 to 230
	
- Tires Max Upgraded:
	- Reduced GRIP_SCALE Front from 1.025 to 1
	- Reduced GRIP_SCALE Rear from 1.075 to 1
	- Increased YAW_SPEED from 0.6 to 0.61

#Audi TT (Tier 2)
- Suspension Max Upgraded:
	- Reduced TRAVEL Front from 7 to 6.5
	- Reduced TRAVEL Rear from 7 to 6.5
	
- Tires Max Upgraded:
	- Reduced GRIP_SCALE Rear from 1.025 to 1.01 (MW Value).
	
## Audi R8 4.2 FSI Quattro (V8 production model) (Tier 3)
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.225 to 0.233
	- Increased LOW_BOOST from 0.225 to 0.233
	
## BMW M3 CSL (Tier 3)
- Tires Max Upgraded:
	- Slightly improved steering range.
	
## BMW M3 GTR Street (Tier 3)
- Tires Max Upgraded:
	- Increased STATIC_GRIP Front from 2.25 to 2.3
	- Increased STATIC_GRIP Rear from 2.35 to 2.4
	
# Muscle Cars

## Cadillac CTS (Tier 1)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 14 to 13.5

- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.8 to 3.6

- Suspension Max Upgraded:
	- Ported over all MW suspension values.

- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.32 to 0.35

## Corvette C6 + Player Cop Cross C6 (Tier 3)
- ecar [copsport + copsportb]
	- Ported over MW C6 BodyDive, BodyRoll and BodySquat values.

- Engine Max Upgraded:
	- Slightly increased torque values (MW 1.125x -> MW 1.15x)

- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.5 to 3.3

- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.33 to 0.35
	- Increased SHOCK_EXT_STIFFNESS Front from 85 to 95
	- Increased SHOCK_STIFFNESS Front from 70 to 80
	- Increased SPRING_STIFFNESS Front from 650 to 750
	- Increased SWAYBAR_STIFFNESS Front from 260 to 360
	
- Tires Max Upgraded:
	- Increased STEERING from 1 to 1.05
	
## Corvette C6R (Tier 3)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.3 to 3.1

- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.35 to 0.38
	
- Tires Max Upgraded:
	- Ported over MW YAW_CONTROL values.

# Tuners

## Fiat Punto (Tier 1)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 10 to 9
	- Increased torque values by 6.6%
	
- Transmission Max Upgraded:
	- Reduced DIFFERENTIAL[1] from 0.7 to 0
	- Reduced FINAL_GEAR from 2.8 to 2.6

- Suspension Max Upgraded:
	- Reverted DRAG_COEFFICIENT change from 1.6.3 (0.3 -> 0.32)
	
- Induction Max Upgraded:
	- Reduced HIGH_BOOST from 0.25 to 0.2
	- Reduced LOW_BOOST from 0.125 to 0.1
	
## Mazda 3 Sport (Tier 1)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 11.5 to 11.25
	
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.3825 to 0.38
	
- Induction Max Upgraded:
	- Reduced SPOOL from 0.2 to 0.17

## Mitsubishi Lancer Evolution 8 (Tier 3)
- Suspension Max Upgraded:
	- Ported over MW suspension values.
	
- Tires Max Upgraded:
	- Reduced GRIP_SCALE Front from 1.2 to 1.05
	- Reduced GRIP_SCALE Rear from 1.2 to 1.075
	
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.33 to 0.365
	- Increased LOW_BOOST from 0.22 to 0.26

## Subaru Impreza WRX ST-i GDB-D (Tier 3)
- Tires Max Upgraded:
	- Reduced DYNAMIC_GRIP Front from 2.1 to 1.9
	- Reduced DYNAMIC_GRIP Rear from 2.1 to 1.9
	- Reduced STATIC_GRIP Front from 2.35 to 2.15
	- Reduced STATIC_GRIP Rear from 2.4 to 2.2
	
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.22 to 0.26
	- Increased LOW_BOOST from 0.33 to 0.365
	
# Ultimate Mod Cars

# Tuners

## Nissan Silvia (Tier 2)
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9.5 to 9
	
---
**v1.6.3.1 - Improvement Mod v2 compatibility hotfix**  
**(dd/mm/yyyy)**  
**(31/05/2026)**  

# Scripts and installation

### Improvement Mod v2:
- Disabled Cop Cross C6 and Cop Corvette z06 installation scripts, 
as they use parts from the normal C6 and z06 in newer versions of Improvement Mod v2.
	
---
**v1.6.3 - Lots of small changes, fixes, improved Ultimate Mod support**  
**(dd/mm/yyyy)**  
**(27/01/2026)**  

# Scripts and installation

### MW Style Upgrades fixes:
- Fixed Race Package brakes tuning sliders for tier 1 and 2 tuners displaying incorrectly.
- Fixed the MW Style Upgrades installer for Improvement Mod v2 applying the TT script twice.

### Ultimate Mod:
- Added more support for the Ultimate Mod Tier 1 and 2 cars.

Disclaimer: The uninstaller for Ultimate Mod has been temporarily disabled.
Having uninstall scripts for both every vanilla car with ultimate mod's stats, 
along with ultimate mod's addon cars, is a tedious, time-consuming headache.
It is better practice to just have the UltMod uninstaller disabled until a later date, rather than potentially mislead people with an incomplete uninstaller.

The UltMod T1/2 vanilla car scripts are mostly copy and pasted from the MW Style Upgrades car scripts,
but with some of the attribulator data (ShiftSND, TurboSND, engine/caraudio, number of upgrades etc) removed.
This is to account for Ultimate Mod's slightly different upgrades system, and to also not override Ultimate Mod's car sounds.
While most cars share identical performance stats, 
some cars have slightly different, or entirely different stats to account for differences in mass and or tensor scale.
These include:

- Audi S3 (partially based on MW/ImpMod A3)
- Audi RS4 (partially based on MW/ImpMod A4)
- Cadillac CTS (partially based on MW/ImpMod CTS)
- Lexus IS300
- Mazda RX8 
- Mazdaspeed 3
- Mercedes Benz SL500
- Toyota MR2
- VW Golf R32


# Vanilla Cars 

# Exotics

## Alfa Romeo Brera (Tier 1)
- Tires Max Upgraded
	- Increased DYNAMIC_GRIP Front from 1.75 to 1.8
	- Increased DYNAMIC_GRIP Front from 1.8 to 1.85
	- Reduced YAW_SPEED from 0.42 to 0.4

## Aston Martin DB9 (Tier 2)
- Engine Max Upgraded:
	- Slightly increased torque values (MW 1.04x -> 1.0605x)
	
- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.35 to 0.3525
	
- Tires Max Upgraded:
	- Increased STEERING from 0.875 to 0.9

## Jaguar XK (Tier 2)
- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.272 to 0.275
	
## Lotus Elise (Tier 2)
- Suspension Max Upgraded:
	- Increased SHOCK_VALVING Front from 17 to 18
	- Increased SHOCK_VALVING Rear from 17 to 18
	
## Lamborghini Gallardo (Tier 3)
- Suspension Max Upgraded:
	- Reduced AERO_CG from 48.75 to 46.25
	
- Tires Max Upgraded:
	- Increased GRIP_SCALE Front from 1.1 to 1.15
	- Increased GRIP_SCALE Rear from 1.1 to 1.15
	- Reduced YAW_SPEED from 0.325 to 0.305

## Porsche 911 GT3 RS 997 (Tier 3):
- Suspension Max Upgraded:
	- Increased RIDE_HEIGHT Front from 8.5 to 9
	- Increased RIDE_HEIGHT Front from 8.5 to 9
	- Reduced ROLL_CENTER from 9 to 8.75
	- Increased SPRING_STIFFNESS Rear from 830 to 925

# Muscle Cars

## Chevrolet Camaro SS (Tier 1)
- Suspension Max Upgraded:
	- Reduced TRAVEL Front from 8.5 to 8
	- Reduced TRAVEL Rear from 8.5 to 8

- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.3 to 0.3175
	- Increased LOW_BOOST from 0.3 to 0.3175

## Chevrolet Chevelle SS (Tier 1)
- Induction Max Upgraded:
	- Reduced SPOOL_TIME_UP from 2 to 1.75
	
## Dodge Charger R/T 1969
- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.2 to 0.201

- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.33 to 0.3325
	- Increased LOW_BOOST from 0.33 to 0.3325
	
- Brakes Max Upgraded:
	- Increased EBRAKE from 750 to 800

## Plymouth Roadrunner (Tier 2)
- Engine Max Upgraded:
	- Reduced torque values from 2x to 1.96x of original values.
	
- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.45 to 0.46

- Stock Tires:
	- Increased rear tire width from 245mm to 255mm
	
- Tires Max Upgraded:
	- Increased rear tire width from 245mm to 255mm

## Shelby GT500 1967 (Tier 3)
- Suspension Max Upgraded:
	- Increased FRONT_WEIGHT_BIAS from 51 to 52.25
	- Reduced AERO_CG from 50 to 49

- Tires Max Upgraded:
	- Reduced DYNAMIC_GRIP Front from 1.7 to 1.675
	- Reduced DYNAMIC_GRIP Rear from 1.7 to 1.675
	
## Shelby GT500 2007 (Tier 3)
- Transmission Max Upgraded:
	- Increased FINAL_GEAR from 3.95 to 4
	- (Top Speed: 390km/h -> 386km/h [Manual Transmission])

- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.4 to 0.425 
	- Increased SHOCK_EXT_STIFFNESS Front from 70 to 90
	- Increased SHOCK_EXT_STIFFNESS Front from 75 to 90
	- Increased SHOCK_STIFFNESS Front from 67.5 to 80
	- Increased SHOCK_STIFFNESS Front from 70 to 80
	
- Brakes Max Upgraded:
	- Reduced front brake power from 630 to 625
	- Reduced rear brake power from 755 to 750

# Tuners 

## Mazda RX-8 (Tier 1)
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.3025 to 0.305
	- Increased LOW_BOOST from 0.3025 to 0.305

## Mazda RX-7 (Tier 2)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.7 to 3.55

- Suspension Max Upgraded:
	- Reverted weight and aero distribution changes from 1.6.2
	
- Tires Max Upgraded:
	- Increased STEERING from 1 to 1.1
	
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.233 to 0.25
	- Increased LOW_BOOST from 0.233 to 0.25
	
## Renault Clio V6 (Tier 2)
- Suspension Max Upgraded:
	- Increased SHOCK_VALVING Front from 20 to 24
	- Increased SHOCK_VALVING Rear from 20 to 24
	
## Toyota Corolla GTS (Tier 2)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 13 to 9.5
	
- Suspension Max Upgraded:
	- Increased SWAYBAR_STIFFNESS Front from 200 to 225
	- Increased SWAYBAR_STIFFNESS Rear from 220 to 225
	
## Toyota MR2 (Tier 2)
- Tires Max Upgraded:
	- Increased GRIP_SCALE Front from 1.1 to 1.125
	- Increased GRIP_SCALE Rear from 1.15 to 1.175

## Mitsubishi Eclipse GS-T 1999 (Tier 2):
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9.5 to 8.875
	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.34 to 0.3725	

## Nissan 350z Z33 (Tier 3)
- Suspension Max Upgraded:
	- Reduced TRAVEL Front from 7 to 6.9
	- Reduced TRAVEL Rear from 7 to 6.9
	
## Infiniti G35 (Tier 3)
- Engine Max Upgraded:
	- Slightly increased torque values (1.875x -> 1.885x)
	
## Subaru Impreza WRX ST-i GDB-F (Tier 3)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 9.5 to 8.95
	
- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 9 to 8.5
	
# Improvement Mod v2 Cars

#Tuners

## Chevrolet Cobalt SS (Tier 1)
- Suspension Max Upgraded
	- Reduced DRAG_COEFFICIENT from 0.375 to 0.3725
	
## Fiat Grande Punto (Tier 1)
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.32 to 0.315

## Subaru Impreza WRX ST-i GDB-D (Tier 3)
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 2.05 to 2.1
	- Increased DYNAMIC_GRIP Rear from 2.05 to 2.1
	- Increased STATIC_GRIP Front from 2.25 to 2.35
	- Increased STATIC_GRIP Rear from 2.3 to 2.4
	- Reduced YAW_SPEED from 0.425 to 0.4

# Ultimate Mod Cars

# Exotics
## Audi S3 (Tier 1)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 10 to 9.5
	
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.55 to 3.4
	
- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.245 to 0.275
	- Reduced DRAG_COEFFICIENT from 0.38 to 0.34
	- Increased FRONT_WEIGHT_BIAS from 53.15 to 53.7
	- Increased SHOCK_EXT_STIFFNESS Front from 77 to 80
	- Increased SHOCK_EXT_STIFFNESS Rear from 77 to 80
	- Increased SHOCK_VALVING Front from 18.5 to 20
	- Increased SHOCK_VALVING Rear from 18.5 to 20
	- Increased SPRING_STIFFNESS Front from 770 to 800
	- Increased SPRING_STIFFNESS Rear from 790 to 800
	- Reduced TRAVEL Front from 7 to 6
	- Reduced TRAVEL Rear from 7 to 6

- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.335 to 0.375

## Audi RS4 (Tier 2)
- Stock Engine:
	- Increased RED_LINE from 7400 to 8250
	- Increased MAX_RPM from 8400 to 9250

- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS from 15 to 13
	- Increased RED_LINE from 7400 to 8250
	- Increased MAX_RPM from 8400 to 9250
	
- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.33 to 0.36
	
- Suspension Max Upgraded:
	- Reduced AERO_CG from 47 to 46.5
	- Increased AERO_COEFFICIENT from 0.25 to 0.275
	- Increased FRONT_WEIGHT_BIAS from 53.5 to 54.2
	- Increased SPRING_STIFFNESS Front from 750 to 775
	- Increased SPRING_STIFFNESS Rear from 700 to 725
	
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 1.8 to 1.925
	- Increased DYNAMIC_GRIP Rear from 1.9 to 2
	- Increased GRIP_SCALE Front from 1.035 to 1.05
	- Increased GRIP_SCALE Rear from 1.035 to 1.1
	- Increased STATIC_GRIP Front from 2 to 2.15
	- Increased STATIC_GRIP Rear from 2.1 to 2.25
	- Increased STEERING from 0.98 to 1
	
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.275 to 0.325
	- Increased LOW_BOOST from 0.255 to 0.325
	
# Muscle Cars

## Pontiac Firebird 1978 (Tier 1)
- Suspension Max Upgraded:
	- Increased SPRING_STIFFNESS Front from 370 to 425
	- Increased SPRING_STIFFNESS Rear from 370 to 525
	

## Chevrolet Corvette 1967 (Tier 2)
- Transmission Max Upgraded:
	- Increased DIFFERENTIAL[1] from 0.7 to 0.75

- Suspension Max Upgraded:
	- Reduced AERO_CG from 50 to 47.75
	- Increased AERO_COEFFICIENT from 0.2 to 0.24
	- Increased FRONT_WEIGHT_BIAS from 50.8 to 53.5
	- Reduced RENDER_MOTION from 0.55 to 0.5
	- Reduced ROLL_CENTER from 10.75 to 10.7
	- Increased SPRING_STIFFNESS Front from 660 to 680
	- Increased SPRING_STIFFNESS Rear from 680 to 690
	
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Rear from 1.75 to 1.775

- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.3 to 0.33
	- Increased LOW_BOOST from 0.3 to 0.33
	
# Tuners

## Nissan Silvia (Tier 2)
- Engine Max Upgraded:
	- Slightly increased torque values (1.59x -> 1.61x)

- Suspension Max Upgraded:
	- Reduced ROLL_CENTER from 10 to 9.5
	- Increased SHOCK_VALVING Front from 16 to 17
	- Increased SHOCK_VALVING Rear from 16 to 17
	
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 1.75 to 1.8
	- Increased DYNAMIC_GRIP Rear from 1.75 to 1.9
	- Increased GRIP_SCALE Front from 1 to 1.1
	- Increased GRIP_SCALE Rear from 1 to 1.1
	- Increased STATIC_GRIP Front from 1.9 to 2
	- Increased STATIC_GRIP Rear from 2.05 to 2.15
	- Increased STEERING from 1.02 to 1.04
	- Increased YAW_SPEED from 0.335 to 0.345
	
## Acura NSX (Tier 3)
- Stock Engine:
	- Increased RED_LINE from 7000 to 8000
	- Increased MAX_RPM from 8000 to 9000

- Engine Max Upgraded:
	- Slightly increased torque values (1.22x -> 1.245x)
	- Increased RED_LINE from 7000 to 8000
	- Increased MAX_RPM from 8000 to 9000
	
- Transmission Max Upgraded:
	- Reduced SHIFT_SPEED from 0.27 to 0.25
	
- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.31 to 0.38
	- Reduced SHOCK_VALVING Front from 20.5 to 19.5
	- Reduced SHOCK_VALVING Rear from 20.5 to 19.5
	
- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.35 to 0.4
	- Increased SPRING_STIFFNESS Front from 670 to 675
	- Increased SPRING_STIFFNESS Rear from 670 to 675
	
- Tires Max Upgraded:
	- Increased GRIP_SCALE Front from 1.05 to 1.1
	- Increased GRIP_SCALE Rear from 1.05 to 1.1
	- Increased STATIC_GRIP Front from 2 to 2.1
	- Increased STATIC_GRIP Rear from 2 to 2.1

	
## Mitsubishi Lancer Evo X (Tier 3)
- Engine Max Upgraded:
	- Increased torque values (1.12x -> 1.206x)
	
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.63 to 3.33
	
- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.27 to 0.2725
	- Increased SPRING_STIFFNESS Rear from 730 to 810
	- Increased SHOCK_EXT_STIFFNESS Front from 78 to 82
	- Increased SHOCK_EXT_STIFFNESS Rear from 78 to 84
	- Increased SHOCK_STIFFNESS Front from 64 to 68
	- Increased SHOCK_STIFFNESS Rear from 64 to 70
	
## Nissan GTR R35 (Tier 3)
- Engine Max Upgraded:
	- Very slightly increased torque values (1.25x -> 1.272x)

- Transmission Max Upgraded:
	- Reduced CLUTCH_SLIP from 0.85 to 0.725
	- Reduced FINAL_GEAR from 3.34 to 2.65
	
- Suspension Max Upgraded:
	- Reduced AERO_CG from 48.5 to 47.25
	- Increased AERO_COEFFICIENT from 0.297 to 0.3
	- Increased FRONT_WEIGHT_BIAS from 53.8 to 53.85
	- Increased SPRING_STIFFNESS Front from 810 to 840
	- Increased SPRING_STIFFNESS Rear from 790 to 825
	
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 2.1 to 2.25
	- Increased DYNAMIC_GRIP Front from 2.125 to 2.25
	- Increased GRIP_SCALE Front from 1.185 to 1.22
	- Increased GRIP_SCALE Rear from 1.185 to 1.245
	- Increased STATIC_GRIP Front from 2.275 to 2.4
	- Increased STATIC_GRIP Rear from 2.3 to 2.5
	- Increased YAW_CONTROL[0] from 0.2 to 0.45
	- Increased YAW_CONTROL[1] from 0.75 to 1
	- Increased YAW_CONTROL[2] from 0.85 to 1.1
	- Increased YAW_CONTROL[3] from 1 to 1.35
	
- Induction Max Upgraded:
	- Increased LOW_BOOST from 0.32 to 0.35
	- Increased SPOOL_TIME_DOWN from 0.25 to 0.26
	
---
**v1.6.2 - Improvements to Tier 3 Tuner top speed, Viper vanilla grip and downforce, various small changes**  
**(dd/mm/yyyy)**  
**(21/11/2025)**  

### This update includes:

- Tier 3 Tuners now have a similar top speed potential to their MW counterparts.  
They're still somewhat held back by their average overall power output and moderate  
to moderate-high drag coefficients, meaning they still experience greater slowdown at  
higher speeds compared to other car classes, but the potential is there.  

- Several Tier 3 Tuners (350z, Impreza WRX STi, Lancer Evo 9, Skyline) got a small re-work to their stock performance and handling.

- The Viper gets its vanilla grip and downforce, but maintains its weight and aerodynamic distribution from MW.

- Various small changes and adjustments.


# Vanilla Cars  

# Exotics

## Porsche Cayman S (Tier 2)
- Stock Engine:
	- Improved torque values.

- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.25 to 0.32
	
- Stock Tires:
	- Reduced GRIP_SCALE Rear from 1.075 to 1
	
- Suspension Max Upgraded:
	- Reduced SHOCK_DIGRESSION Front from 0.25 to 0.1
	- Reduced SHOCK_DIGRESSION Rear from 0.25 to 0.1

## BMW M3 GTR Race (Tier 3) (Vanilla, already have bonus cars installation option)
- Engine Max Upgraded:
	- Fixed torque value discrepancy between the add bonus cars, and already have bonus cars installation script.
	- It now correctly uses the torque vales from the add bonus cars installation script.
	
## Lamborghini Murcielago LP640 (Tier 3)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.2 to 3.1
	- Top Speed = 439km/h

- Suspension Max Upgraded:
	- Increased SPRING_PROGRESSION Rear from 7 to 8

- Induction Max Upgraded:
	- Reduced HIGH_BOOST from 0.25 to 0.2

- Brakes Max Upgraded:
	- Reduced front brake power from 700 to 695
	- Reduced rear brake power from 750 to 745
	
## Mercedes Benz McLaren SLR (Tier 3)  
- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.4 to 0.44
	
- Stock Supercharger:
	- Increased HIGH_BOOST from 0.05 to 0.15
	- Increased LOW_BOOST from 0.2 to 0.225
	
## Porsche Carrera GT (Tier 3)
- Transmission Max Upgraded:
	- Ported over all MW transmission data.

- Suspension Max Upgraded:
	- Increased SPRING_PROGRESSION Front from 7.5 to 8.5
	- Increased SPRING_PROGRESSION Rear from 7 to 8

# Muscle Cars

## Chevrolet Chevelle SS (Tier 1)
- Stock Engine:
	- Now uses vanilla torque values.
	
- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.3 to 0.47

## Chrysler 300c SRT-8 (Tier 1)
- Engine Max Upgraded:
	- Reduced torque values from 2.36x to 2.25x of original values.
	
- Suspension Max Upgraded:
	- Increased SHOCK_VALVING Front from 20 to 24
	- Increased SHOCK_VALVING Rear from 20 to 24

## Dodge Charger SRT-8 (2006) (Tier 2)
- Engine Max Upgraded:
	- Reduced torque values from 1.62x to 1.6x of original values.
	
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3 to 2.94
	- (Top Speed: 393km/h -> 401km/h)
	
	
## Plymouth Roadrunner (Tier 2)
- Stock Engine:
	- Now uses vanilla torque values.
	
- Stock Suspension:
	- Increased DRAG_COEFFICIENT from 0.3 to 0.44
	
	
## Chevrolet Camaro Concept (Tier 3)
- Transmission Max Upgraded:
	- Increased DIFFERENTIAL[1] from 0.5 to 0.6
	- Reduced FINAL_GEAR from 3.95 to 3.8
	- (Top speed: 363km/h -> 378km/h)

- Stock Suspension:
	- Increased ROLL_CENTER from 9.65 to 10.5 

- Suspension Max Upgraded:
	- Reduced AERO_CG from 50 to 49.9
	- Reduced TRAVEL Front from 7 to 6.75
	- Reduced TRAVEL Rear from 7 to 6.75
	
- Tires Max Upgraded:
	- Reduced GRIP_SCALE Front from 1.02 to 1
	- Reduced GRIP_SCALE Rear from 1.02 to 1
	- New YAW_CONTROL Values:
	- [0] 0
	- [1] 0.22
	- [2] 0.33
	- [3] 0.55

## Dodge Viper SRT-10 (Tier 3)
- Suspension Max Upgraded:
	- Reduced AERO_COEFFICIENT from 0.201 to 0.2

- Tires Max Upgraded:
	- Reduced DYNAMIC_GRIP Front from 1.825 to 1.7
	- Reduced DYNAMIC_GRIP Rear from 1.875 to 1.7
	- Reduced STATIC_GRIP Front from 2.1 to 2
	- Reduced STATIC_GRIP Rear from 2.15 to 2
	
## Plymouth Hemi Cuda (Tier 3)
- Stock Engine:
	- Increased torque values by 10%

- Stock Suspension:
	- Increased AERO_COEFFICIENT from 0.16 to 0.163
	- Increased DRAG_COEFFICIENT from 0.3 to 0.45
	
## Shelby GT500 2007 (Tier 3)
- Engine Max Upgraded:
	- Reduced ENGINE_BRAKING[0] from 0.75 to 0.7
	- Reduced ENGINE_BRAKING[1] from 0.82 to 0.8
	- Increased FLYWHEEL_MASS from 11 to 11.75
	
- Stock Transmission:
	>Now uses IRL individual gear ratios (except possibly reverse gear).  
	Though it makes sense to also use the IRL final drive, 
	this wasn't done for balancing reasons.

- Transmission Max Upgraded:
	- Now uses IRL gear ratios (except possibly reverse gear)
	- Reduced CLUTCH_SLIP from 0.71 to 0.701
	- Increased DIFFERENTIAL[1] from 0.75 to 0.785
	- Increased FINAL_GEAR from 3.8 to 3.95
	- (Top Speed: 382km/h -> 390km/h [Manual Transmission])
	
- Suspension Max Upgraded:
	- Increased ROLL_CENTER from 9 to 9.5 
	
- Brakes Max Upgraded:
	- Reduced front brake power from 650 to 630
	- Reduced rear brake power from 775 to 755
	
# Tuners  

## Nissan 240SX (Tier 1)	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.38 to 0.3825
	
## Mazda RX-7 (Tier 2)
- Stock Tires:
	- Increased YAW_SPEED from 0.41 to 0.44

- Suspension Max Upgraded:
	- Increased AERO_CG from 47.5 to 48.65
	- Reduced FRONT_WEIGHT_BIAS from 53.8 to 53
	
- Tires Max Upgraded:
	- Increased GRIP_SCALE Front from 1.055 to 1.1
	- Increased GRIP_SCALE Rear from 1.075 to 1.1
	- Reduced STEERING from 1.1 to 1
	
## Toyota Corolla GT-S AE86 (Tier 2)
- Suspension Max Upgraded:
	- Reduced DRAG_COEFFICIENT from 0.4225 to 0.42

## Renault Clio V6 (Tier 2)
- Stock Tires:
	- Increased YAW_SPEED from 0.3 to 0.315
	- Increased STATIC_GRIP Front from 1.8 to 1.85
	- Increased STATIC_GRIP Rear from 1.85 to 1.9

- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Rear from 1.95 to 2
	- Increased YAW_SPEED from 0.385 to 0.4

## Mitsubishi Eclipse GS-T 1999 (Tier 2):
- Engine Max Upgraded:
	- Increased torque values by 77.5% (from G35 values, up from 62%)
	
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.3 to 0.34
	
## Infiniti G35 (Tier 3):
- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.2 to 2.9
	- Top Speed = 420km/h
	
## Mitsubishi Lancer Evo 9 (Tier 3):
- Stock Suspension:
	- Reduced AERO_COEFFICIENT from 0.25 to 0.195
	- Increased DRAG_COEFFICIENT from 0.26 to 0.34
	
- Stock Tires:
	- Increased DYNAMIC_GRIP Front from 1.7 to 1.8
	- Increased DYNAMIC_GRIP Rear from 1.8 to 1.9
	- Increased STATIC_GRIP Front from 1.9 to 2
	- Increased STATIC_GRIP Rear from 2 to 2.1
	
- Stock Turbo:
	- Increased HIGH_BOOST from 0.15 to 0.175
	- Increased LOW_BOOST from 0.15 to 0.175

- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.725 to 3.475
	- Top Speed = 416km/h
		
- Turbo Max Upgraded:
	- Increased SPOOL_TIME_UP from 1.5 to 2
	
## Nissan 350z Z33 (Tier 3):
- Stock Engine:
	- Reduced FLYWHEEL_MASS from 14 to 13
	
- Stock Suspension:
	- Reduced AERO_COEFFICIENT from 0.22 to 0.1725
	- Reduced SHOCK_VALVING Front from 20.5 to 20
	- Reduced SHOCK_VALVING Rear from 20.5 to 20
	
- Stock Tires:
	- Increased DYNAMIC_GRIP Front from 1.55 to 1.7
	- Increased DYNAMIC_GRIP Rear from 1.55 to 1.7
	- Increased GRIP_SCALE Front From 1 to 1.1
	- Increased GRIP_SCALE Rear From 1 to 1.1
	- Increased STATIC_GRIP Front from 1.75 to 1.9
	- Increased STATIC_GRIP Rear from 1.9 to 2.05
	- Increased STEERING from 0.95 to 1

- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.17 to 2.84
	- Top Speed = 417km/h		

## Nissan Skyline GTR R-34 (Tier 3):
- Stock Suspension:
	- Reduced AERO_COEFFICIENT from 0.27 to 0.23
	- Increased DRAG_COEFFICIENT from 0.31 to 0.35
	- Increased ROLL_CENTER from 8.5 to 8.75
	- Increased SHOCK_DIGRESSION Front from 0.4 to 0.45
	- Increased SHOCK_DIGRESSION Rear from 0.4 to 0.45
	- Reduced SHOCK_VALVING From 19 to 18
	- Reduced SHOCK_VALVING From 19 to 18
	
- Stock Tires:
	- Increased DYNAMIC_GRIP Front from 2 to 2.15
	- Increased DYNAMIC_GRIP Rear from 2.05 to 2.15
	
- Stock Turbo:
	- Increased LOW_BOOST from 0.15 to 0.166

- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.35 to 3.1
	- Top Speed = 420km/h
	
## Subaru Impreza WRX ST-i GDB-F (Tier 3):
- Stock Suspension.
	- Reduced AERO_COEFFICIENT from 0.225 to 0.185
	- Increased DRAG_COEFFICIENT from 0.3 to 0.33
	- Reduced SHOCK_VALVING Front from 24 to 22
	- Reduced SHOCK_VALVING Rear from 24 to 22
	
- Stock Tires:
	- Increased DYNAMIC_GRIP Front from 1.6 to 1.9
	- Increased STATIC_GRIP Front from 1.8 to 2.1
	- Increased STATIC_GRIP Rear from 2.1 to 2.2
	
- Stock Turbo:
	- Increased HIGH_BOOST From 0.15 to 0.225
	- Increased LOW_BOOST From 0.15 to 0.225

- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.3 to 3
	- Top Speed = 414km/h
	
- Tires Max Upgraded:  
	- Increased GRIP_SCALE Front from 1.125 to 1.15
	- Increased GRIP_SCALE Rear from 1.175 to 1.2
	
## Toyota Supra MK-4 (Tier 3):
- Transmission Max Upgraded:  
	- Increased FINAL_GEAR from 2.5 to 2.64
	- Reduced 5th gear ratio from 1.05 to 1.025
	- Reduced 6th gear ratio from 0.9 to 0.81
	- Top Speed = 437km/h

# Improvement Mod v2 Cars

# Tuners

## Mitsubishi Lancer Evo 8 (Tier 3):
- Stock Suspension:
	- Reduced AERO_COEFFICIENT from 0.25 to 0.15
	
- Stock Turbo:
	Increased HIGH_BOOST From 0.2 to 0.225
	Increased LOW_BOOST From 0.15 to 0.175

- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.8 to 3.4
	
## Subaru Impreza WRX ST-i GDB-D (Tier 3):
- Stock Suspension:
	- Reduced AERO_COEFFICIENT from 0.23 to 0.17
	
- Stock Turbo:
	- Increased HIGH_BOOST From 0.1 to 0.2
	- Increased LOW_BOOST From 0.1 to 0.2

- Transmission Max Upgraded:  
	- Reduced FINAL_GEAR from 3.3 to 3

---
**v1.6.1 - Viper grip nerf, SLR adjustments, Eclipse GS-T 1999 transmission fix, Small adjustments to Tier 1 and 2 Cars.**  
**(dd/mm/yyyy)**  
**(12/10/2025)**


# Vanilla Cars

# Exotics

## Lotus Elise (Tier 2)
- Tires Max Upgraded:
	- Improved steering range

## Lotus Europa S (Tier 2)
- Transmission Max Upgraded:
	- Reduced FINAL_GEAR from 3.1 to 3

- Tires Max Upgraded:
	- Increased STEERING from 0.95 to 0.975

- Induction Max Upgraded:
	- Reduced SPOOL_TIME_UP from 2.5 to 2.4

## Porsche Cayman S (Tier 2)
- Tires Max Upgraded:
	- Increased YAW_SPEED from 0.3725 to 0.375


## Mercedes Benz McLaren SLR (Tier 3)  
> Suspension upgrades no-longer decrease shock valving values.
- Engine Max Upgraded:
	- Increased torque values by 25% (from original values, up from 24%)

- Suspension Max Upgraded:
	- Increased DRAG_COEFFICIENT from 0.4 to 0.44 (Vanilla value)
	- Increased SHOCK_VALVING Front from 18 to 26
	- Increased SHOCK_VALVING Rear from 18 to 26
	- Increased SPRING_PROGRESSION Front from 8 to 9 (MW value)	 
	- Increased SPRING_PROGRESSION Rear from 8.5 to 9.5 (MW value)
	- Reduced ROLL_CENTER from 9 to 8.5 (MW value)


# Muscle Cars

## Dodge Viper SRT-10 (Tier 3)
- Tires Max Upgraded:
	- Reduced DYNAMIC_GRIP Front from 1.85 to 1.825
	- Reduced DYNAMIC_GRIP Rear from 1.9 to 1.875

## Shelby GT500 1967 (Tier 3)
- Tires Max Upgraded:
	- Reduced STATIC_GRIP Front from 1.95 to 1.9
	- Reduced STATIC_GRIP Rear from 2.05 to 2


# Tuners

## Mazda Mazdaspeed 3 (Tier 1)
- Tires Max Upgraded:
	- Increased STEERING from 1 to 1.05

## Mazda RX-8 (Tier 1)
- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.3 to 0.3025
	- Increased LOW_BOOST from 0.3 to 0.3025

## Nissan 240SX (Tier 1)
- Engine Max Upgraded:
	- Increased torque values by 2.3% (from MW Cobalt SS values, up from 2%)

- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.255 to 0.2565
	
- Tires Max Upgraded:
	- Increased YAW_SPEED Rear from 0.3775 to 0.38

## Mazda RX-7 (Tier 2)
- Tires Max Upgraded:
	- Increased STEERING from 1 to 1.1

- Induction Max Upgraded:
	- Increased HIGH_BOOST from 0.225 to 0.233
	- Increased LOW_BOOST from 0.225 to 0.233
	
## Mitsubishi Eclipse GS-T 1999 (Tier 2):
- Engine Max Upgraded:
	- Increased torque values by 62% (from G35 values, up from 59%)

- Transmission Max Upgraded:
	- Fixed installation script applying the 6th gear ratio to the 5th gear.

## Mitsubishi Eclipse GT (Tier 2)
- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.26 to 0.265

## Renault Clio V6 (Tier 2)
- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Rear from 1.9 to 1.95
	- Increased YAW_SPEED Rear from 0.38 to 0.385

## Toyota Corolla GT-S AE86 (Tier 2)
> This isn't going to make the Corolla anywhere near as powerful as it was in Underground 2, but it is going to make it slightly better.
- Suspension Max Upgraded:
	- Reduced AERO_CG from 48.25 to 48
	- Reduced DRAG_COEFFICIENT from 0.425 to 0.4225

- Tires Max Upgraded:
	- Increased YAW_CONTROL[1] from 0.65 to 0.7
	- Increased YAW_CONTROL[2] from 0.85 to 1
	- Increased YAW_CONTROL[3] from 1 to 1.25

## Toyota MR2 (Tier 2)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS From 10 to 9.75

- Tires Max Upgraded:
	- Increased DYNAMIC_GRIP Front from 1.9 to 1.925
	- Increased DYNAMIC_GRIP Rear from 1.95 to 1.975
	- Increased YAW_SPEED from 0.5325 to 0.535	

# Improvement Mod v2 Cars

# Exotics

## BMW M3 CSL (Tier 3)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS From 9.5 to 9

# Tuners

## Fiat Punto (Tier 1)
- Engine Max Upgraded:
	- Reduced FLYWHEEL_MASS From 10.5 to 10

## Mazda 3 Sport (Tier 1)
- Suspension Max Upgraded:
	- Increased AERO_COEFFICIENT from 0.23 to 0.2325

## Mazda MX-5 (Tier 2)
- Tires Max Upgraded:
	- Increased YAW_SPEED From 0.305 to 0.31
