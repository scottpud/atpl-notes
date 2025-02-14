## Air temperature probes

Two types of probes are used in aircraft for measuring temperature

- Expansion type:
    - Uses a bimetalic strip which can be referred to as a direct reading probe
- Electrical Wire/Resistance type
    - Relies on change of electrical resistance with change of temperature
    - Also referred to as the remote reading type 

**Light Aircraft Temperature Sensors**
- Normally use the bimetallic type
- Probe is mounted high on the windshield with indicator inside and sensor outside 
- External sensor has a sun shield over it but no anti ice protection
- Only suffenciantly accurate for low speed aircraft

## Problem of speed
- A faster aircraft creates a temperature sensing Problem
- As air flows past frictional heating will distort the result
- If the previously static air is brought up to the same speed as the rest of the aircraft as its temperature is sensed the extra energy imparted will increase the sensed temperature
- Referred to as:
    - Kinetic heating
    - Ram Rise 
    - The Ram Rise in temperature due to adiabatic compression
- Systems on faster aircraft will display the air temperature as Static Air Temperature (SAT)
    - The temperature of the undisturbed air temperature
    - Can also be referred to as Outside Air temperature (OAT)
- Will also display as True Air Temperature (TAT)
    - Air Temperature including Ram Rise
    - Can also be referred to as 'Measured impact Temperature'

- Can be calculated in a formula that depends on the aircraft's Mach number ($M$)
    - $SAT \times (1 + 0.2M^2) = TAT$
    - Temperatures are always input and output as Kelvin
    - This is based on total conversion of kinetic energy to heat, Sensing systems rarely achieve this or want to achieve this 
    - Formula needs the addition of a constant (Which value is always less than 1)
    - Values around 0.9 are typical
    - Displayed as $K$ (Not to be confused with Kelvin)
    - Formula now becomes $SAT \times (1 + 0.2KM^2) = TAT$ or the other way around $SAT = TAT ÷ (1 + 0.2KM)$

## Temperature sensors on faster aircraft
- Variety of names such as:
    - Total Head Thermometer
    - Rosemount Probe
    - Temperature Probe

![Temperature Probe Diagram](../Images/Temp_Probe.png)

- Has a heater to protect it from ice during flight 
- Once air passes heater it is accelerated through a venturi causing some air to be drawn into a sensing chamber
    - This allows dust and water to be separated by their momentum and exit back of probe
- Air in the sensor chamber has is measured by a resistive element, usually nickel and then exits the back of the chamber
- Heating element can affect air temperature reading, so It's designed that the sensing element is isolated from the effects of the de-icing heater
- Boundry layer bleeds take heated intake air away from the sensor chamber and a heat shield protects the chamber its self
- Probe will only indicate correctly when the aircraft is moving due to reliance of air being drawn into the sensing chamber



## Indications

- Flat plate temperature sensors where sensing element is flush against the aircraft surface
- Sensors of this type do not suffer from Ram Rise
- Affected by frictional Heating
    - Can be taken out by calculation