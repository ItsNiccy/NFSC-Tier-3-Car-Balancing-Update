# NFSC - Tier 3 Car Balancing Update
### Changelog/Patch Notes:  
*Note: Changes to Tier 1 and 2 Cars only apply to the 'MW Style Upgrades' installation options.

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
	- Reduced AERO_CG from 0.201 to 0.2

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
