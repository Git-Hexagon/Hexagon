---
tags: hexagon/equipment
type: 
aliases: 
date: 29-10-2022
share: true
category: hidden
---

# Equipment Naming Conventions

> As the development of new gear began to exponentially increase, the Neo-Hexagon and the Apeirogon Regime have adopted a naming system to better classify and list the ever growing arsenal of the Regime and the Empire.
> 
> More obscure or unrecognised equipment are not subject to this naming convention, and are instead named something else by their inventors.
---

### Production Code
> A weapon or gear's production code is a collection of abbreviations that describe the general usage and function of said equipment.

| Usage | Meaning              |
| ----- | -------------------- |
| CD    | Chronodynamic        |
| CS    | Chronostatic         |
| EX    | External             |
| IN    | Internal             |
| C     | Coil-Operated        |
| Ch    | Chemical-Operated    |
| BW    | Ballistic Weapon     |
| EW    | Exotic Energy Weapon |
| VW    | Void Weapon          |

| Function | Meaning               |
| -------- | --------------------- |
| SD       | Standard              |
| SA       | Semi-Automatic        |
| AT       | Automatic             |
| LS       | Life Support          |
| PA       | Physical Armour       |
| CD       | Combat Device         |
| TA       | Thaumic Armour        |
| PB       | Physical Barrier      |
| TB       | Thaumic Barrier       |
| EA       | Exotic Energy Armour  |
| EB       | Exotic Energy Barrier |
| E-       | External              |
| P-       | Personal              |
| A-       | Area-based            |

###  Mould
> Mould refers to the model of said equipment.

### Iteration
> Iteration refers to the version of a mould.
> 
> Variations of an iteration are added to a weapon or an equipment's short form.

### Short Form
> An equipment's short form contains both its mould, iteration, and variation.
> 
> It allows agents to quickly identify the equipment's classification for quick searches in the database.

> [!abstract]- Examples
> > (CBW)SDSA_PDW-Md.1 In.13 Expeditionary [2S(B)]
> > Mould 1/Iteration 13
> > C1.13-02S(B)
> 
> C = Coilgun
> S = Semi
> (B) = Binary
> 
> > (CDEX)PLS_RBTR-Str 1.3 — Md. 4 In.57 Standard Rebreather
> > Mould 4/Iteration 57
> > RB4.57-00
> 
> RB = Rebreather
> 
> > (CDEX)PPA_UDR-St.1(1.2,1.3),2X,3X,4X — Md.9 In.6 Standard Protective Suit
> > Mould 9/Iteration 6
> > BA9.6-00
> 
> BA = Body Armour

### Structure
> Structure refers to the areas of the body where said equipment is worn.
> 
> Structures enclosed in parentheses are known as reductions, while those with Rs are known as reversals.

> [!abstract]- Examples
> > ... EPA_VST-***St.2X*** — Md.2 ...
> > External Physical Armour, Body Vest
> 
> Covers the entire torso.
> 
> > ... PPA_UDR-**St.1X(1.2,1.3)** — Md.16 ...
> > Personal Physical Armour, Underwear
> 
> Covers the entire head except for the face.
> 
> > ... EPA_GDS-**St.3A,3B(3.2,3AR)** — Md.1 ...
> > External Physical Armour, Protective Guards
> 
> Covers the front part of the upper arm and the entire forearm, but leaves the elbows unprotected.
> 
> > ... ECD_ECE-**St.3CR** — Md.3 ...
> > External Combat Device, Electric Charge Emitter
> 
> Covers the palms.

| Structure | Area  |
| --------- | ----- |
| St.1      | Head  |
| St.2      | Torso |
| St.3      | Arms  |
| St.4      | Legs  |

#### Head (St.1)
| Structure | Area          |
| --------- | ------------- |
| St.1X     | Whole Head    |
| St.1.1    | Scalp         |
| St.1.2    | Eyes          |
| St.1.3    | Mouth         |
| St.1.4    | Ears and Nape |
| St.1.5    | Neck          |

#### Torso (St.2)
| Structure                 | Area                           |
| ------------------------- | ------------------------------ |
| St.2X                     | Whole Torso                    |
| St.2.1                    | Chest                          |
| St.2.2                    | Core                           |
| St.2.3                    | Waist                          |

#### Arms (St.3)
| Structure | Area              |
| --------- | ----------------- |
| St.3X     | Whole Arm + Hands |
| St.3A     | Upper Arm         |
| St.3B     | Forearm           |
| St.3C     | Hands             |
| St.3.1    | Shoulders         |
| St.3.2    | Elbows            |
| St.3.3    | Wrists            |

#### Legs (St.4)
| Structure | Area              |
| --------- | ----------------- |
| St.4X     | Whole Legs + Feet |
| St.4A     | Thighs            |
| St.4B     | Calves            |
| St.4C     | Feet              |
| St.4.1    | Hips              |
| St.4.2    | Groin             |
| St.4.3    | Knees             |
| St.4.4    | Ankles            |

### Production Arrays

Akadht-type and Rukht-type Vessels are always equipped with at least one array. Arrays are large, onboard containment and fabrication units designed to dock and/or create vessels for use in combat. Each array has a different purpose, and thus, there are several types of arrays that are currently in use.

An Akadht-type or a Rukht-type Vessel listed in an Order of Battle are always accompanied by the vessel it is designed to dock, as well as its type, followed by a designation code below it.

These designation codes are also used by other things, such as fabrication limitations or cloning arrays.

Some examples are listed below.

> **Gehenna's First Expeditionary Microtangent, First Void Division**
> - *Specialised Voidbound Command and Control Akadht* [01-24]
> 	- Autonomous Voidbound Giwyn Interceptor, Chrono-divergent Auto-fabricator Array [1-4]
> 		- 512.00-64-105(V)

The type `Chrono-divergent Auto-fabricator Array [1-4]`, as well as the designation code `512.00-64-105B(V)` gives the following information:
- It is chrono-divergent, meaning that it can still produce ships at the same rate, despite chronological interference.
- It is capable of producing vessels automatically even if there are already existing ships assigned to the docks.
- There are four arrays present in the Akadht.
- The arrays hold enough raw materials to produce 512 ships.
- The array has 64 docks, allowing for production, fabrication, resupply, and repair.
- It is capable of producing 105 ships a minute.
- It is currently designed for instantaneous Void deployment.

> Gehenna's First Expeditionary Microtangent, First Parsec Division
> - *Ceryn-class, Rukht-type Central Supply and Production Vessel, 'Genesis'* [1]
> 	- Autonomous Multi-vessel Fabricator, Chrono-divergent Auto-fabricator Array [1-24]
> 		- 86400.00-384-2880(RV)
> - *Ceryn-class, Rukht-type Specialised Carrier Vessel'* [1-6]
> 	- Multi-vessel Docking Unit, Maintenance and Resupply Array [1-200]
> 		- 120000.00-200-000(D)

For the first one, the type `Autonomous Multi-vessel Fabricator, Chrono-divergent Auto-fabricator`, as well as the designation code `86400.00-384-2880(RV)` gives the following information:
- It is autonomous, meaning additional vessels may be automatically produced depending on the status of the combat scenario, as examined by on-board sensors.
- It is a multi-vessel fabricator, meaning it is capable of fabricating and producing multiple types of Sanckht-class vessels.
- It is chrono-divergent, meaning that it can still produce ships at the same rate, despite chronological interference.
- It is an auto-fabricator, which means that it is capable of producing vessels automatically even if there are already existing ships assigned to the docks.
- There are twenty-four arrays present in the Rukht.
- The arrays hold enough raw materials to repair or fabricate 86 thousand vessels.
- The arrays have 384 docks all in all, which count 16 for each array.
- The arrays can produce 2880 ships a minute, or 120 ships per array.
- It is designed for both instantaneous real-space and void deployment.

For the second one, the type `Multi-vessel Docking Unit, Maintenance and Resupply Array`, designation code `120000.00(IT)-200-000(D)`, gives the following information:
- It is a multi-vessel docking unit, meaning it is capable of docking and maintaining multiple types of vessels as long as it fits.
- It is a maintenance and resupply array, meaning that its main purpose is to repair and resupply vessels.
- It can repair a hundred and twenty thousand ships before its raw materials are depleted.
- It, however, can continuously replenish its materials through the Interlink, and it is capable of transmitting material-based Interlink signals to other vessels, allowing for a very quick and efficient remote method of resupplying.
- It is only designed for normal docking, and is not specialised for in-combat rapid deployment.