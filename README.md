# Chemical Reactor Network Modelling for Iron Particle Combustion

## Bachelor Thesis Project -- 1

**Submitted by:** Mudavath Simhachal (22MF3IM12)\
**Supervisor:** Prof. Mani Kalyani Ambatipudi\
**Department:** Mechanical Engineering\
**Institution:** IIT Kharagpur\
**Date:** March 2026

------------------------------------------------------------------------

## 1. Introduction

Metal fuels such as iron powder are promising alternatives for clean
energy. When iron reacts with oxygen, it releases significant heat
energy. Iron combustion can therefore be used for carbon-free energy
systems.

Iron powder is especially promising because of its practicality.

------------------------------------------------------------------------

## 2. Challenges in Modelling Iron Combustion

Iron combustion is difficult to model because it involves:

-   A multi-phase system consisting of solid and gas phases.

-   Multiple processes such as heating, melting, oxidation, and
    evaporation.

-   A complex oxidation pathway:

    **Fe → FeO → Fe₃O₄ → Fe₂O₃**

-   Strong coupling between heat transfer, mass transfer, and chemical
    reactions.

Therefore, direct simulation can be complex and computationally
expensive.

------------------------------------------------------------------------

## 3. Why Iron Is a Good Fuel

Iron has several advantages as a fuel:

-   Non-toxic
-   High energy density
-   Already produced in large quantities
-   Can be recycled

### Iron Cycle

**Iron → Burn → Iron Oxide → Recycle using Hydrogen → Iron again**

This creates a circular energy system.

------------------------------------------------------------------------

## 4. Experimental Setup

The study uses a laboratory-scale combustion chamber with:

-   Methane-assisted iron dust flame
-   Swirling air flow for mixing

### Purpose of the Study

The experimental setup is used to investigate:

-   Flame structure
-   Oxygen distribution
-   Pollutant formation

The results are compared with **CFD simulations and LES data**.

------------------------------------------------------------------------

## 5. Models Used in the Study

Two oxidation models are considered.

### 5.1 FOSK Model

**FOSK -- First Order Surface Kinetics**

Key features:

-   Oxidation occurs at the particle surface.
-   The reaction depends on oxygen diffusion.

### 5.2 Reactive Cooling Model

This model:

-   Considers a layered oxide structure.
-   Includes evaporation effects.
-   Captures detailed particle physics.

These models simulate iron particle conversion during combustion.

------------------------------------------------------------------------

## 6. Chemical Reactor Network (CRN)

A **Chemical Reactor Network (CRN)** is a combination of simple reactors
used to represent a complex combustion system.

### Reactor Types

#### Perfectly Stirred Reactor (PSR)

-   Complete mixing
-   Used for recirculation zones

#### Plug Flow Reactor (PFR)

-   One-directional plug flow
-   No axial mixing

A combination of **PSR + PFR** can be used to simulate real combustion
chamber behaviour.

CRNs have been successfully applied to iron particle combustion in
literature.

------------------------------------------------------------------------

## 7. Objective of the Work

The main objective is to:

> **Develop CRN models for iron combustion.**

### Advantage

CRN modelling has a lower computational cost than CFD.

However, iron combustion remains highly complex because of its
multi-phase interactions.

------------------------------------------------------------------------

## 8. 0D Reactor as a Starting Point

A **0D Ideal Gas Reactor** is used as the starting point.

Characteristics:

-   Perfect mixing
-   No spatial variation
-   Only time-dependent changes

A 0D reactor is basically similar to a **PSR concept**, because it
assumes perfect mixing.

It is the simplest reactor model and can be used as the simplest CRN
element for understanding combustion behaviour.

------------------------------------------------------------------------

## 9. Conclusions from the Literature

The study highlights the following conclusions:

-   CRN models can effectively represent iron combustion.
-   Oxygen controls the reaction.
-   Temperature affects NOx formation and evaporation.
-   Particle size affects evaporation.

------------------------------------------------------------------------

## 10. Project Summary

This project focuses on modelling iron particle combustion using
Chemical Reactor Networks. The approach aims to capture important
combustion behaviour while reducing the computational cost associated
with direct CFD simulations.

The initial modelling approach uses a 0D ideal gas reactor as a simple
CRN element, with the broader goal of developing CRN models for iron
combustion.

------------------------------------------------------------------------

## 11. Keywords

`Iron combustion` `Iron powder` `Chemical Reactor Network` `CRN` `PSR`
`PFR` `0D reactor` `FOSK` `Reactive Cooling Model` `CFD` `LES`
`Iron fuel` `Combustion modelling`
