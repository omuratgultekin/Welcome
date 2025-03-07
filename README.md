Python program for calculating forces and determining appropriate lashing methods for securing cargo during transport. 
The program helps users select optimal cargo securing methods based on various parameters like weight, transport mode, and material interfaces.

Constant Definitions and Data Tables:

Predefined constants for gravity, unit conversions, and maximum weight limits
Several reference tables (TableA, TableB, TableC, TableD) containing coefficients and specifications for different transport modes, 
units, materials, and lashing equipment


User Input Functions:

get_input(): Handles option selection with validation
collect_user_inputs(): Gathers all required parameters like weight, transport mode, material type, etc.
get_takoz_inputs(): Collects wedge (takoz) specifications if needed


Calculation Functions:

calculate_forces(): Computes longitudinal, transverse, and friction forces
calculate_takoz_strength(): Determines resistance provided by wedges
net_initial_forces(): Calculates net forces in all directions
find_all_toka_halat_turu(): Identifies suitable lashing types for transport units


Main Processing Logic:

Collects all user inputs
Calculates all forces based on input parameters
Identifies suitable lashing equipment
Displays results in a formatted table
Offers option to export results to CSV
