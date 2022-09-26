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

sim.ipynb - Notebook used for simulating various arenas to generate behavioral data

simKex.ipynb - notebook for generating behavioral data. Only has Kex arena, which is based off the arena from Nitz 2006 on the PPC. Called 'Kex' because it resembles the Scandinavian candy bar of the same name

simFood.ipynb - More advanced version of simKex, same arena but better movement system with smooth turning and rotation.

simFoodRL.ipynb - Test version to allow movement through reinforcement learning, goal to make movement more natural.

velocity_data.csv - Velocity behavioral data from sim/simKex

cellTests.ipynb - Making various spatial related cells via brian2, mainly for practice