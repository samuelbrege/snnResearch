5/22/2022
Repository for snn research on spatial cognition

Main packages:
brian2 - Spiking Neural Net simulator
pyChrono - Physics simulator for creating behavioral data

Brain areas of focus:
PPC (Path),
SUB (Path),
RSC (Periodic - Path),
mEC (Grid Cells - Location),
CA1 (Place Cells - Location)

Papers/Literature:
Nitz 2006 - PPC,
Nitz 2017 - RSC,
Thousand Brains Theory in general

Files:

simFood.ipynb - notebook for generating behavioral data. Only has Kex arena, which is based off the arena from Nitz 2006 on the PPC. Called 'Kex' because it resembles the Scandinavian candy bar of the same name. Now with smooth turning and rotation. 'Food' title comes from having specific goals around the arena for subject to pursue.

velocity_data.csv - Velocity behavioral data from sim/simKex

cellTests.ipynb - Making various spatial related cells via brian2, mainly for practice