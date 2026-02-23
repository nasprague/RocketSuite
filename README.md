# RocketSuite
RocketSuite is a full stack rocket design, engineering, and simulation software. It is centered around the development of solid rocket motors, but will include functionality to support hybrid and liquid motor development as well.

# Goals
1. Focus on fully custom motor and rocket design - specs of commercial parts will not be included.
2. Open source.
3. Capability to conduct 3D simulations of solid rocket motor burns based on STEP file input of the motor grain. Ability to select inhibited faces on the CAD geometry natively within the GUI.
4. Capability to natively support or allow user-defined functions to iteratively design motor grains within preset constraints using genetic algorithms or other means.
5. Capability to condcut liquid/hybrid 1D performance calculations (not full CFD)
6. Parametric design of an entire rocket that can take custom motors as input. Includes mass and stability analysis
7. 6 DOF trajectory simulation, Monte Carlo dispersion, etc. 
8. Various calculation templates used when designing rockets (e.g. bolt calculations, o-ring fits, nose cone selection, fin flutter, etc.)

# Status
Planning and early development phase

# Architecture
Performance critical solvers in C/C++, basic functionality in python