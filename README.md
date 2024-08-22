# M2PI_2024_Awesense_Team

Phase imbalances in an electric grid can lead to significant inefficiencies and power losses, underscoring the need for an effective method to reassign loads across phases. This notebook presents an Integer Programming (IP) model designed to address these imbalances by optimizing load distribution across three phases within a synthetic grid environment provided by Awesense. The model identifies the optimal clusters to reassign, minimizing phase imbalances while limiting the number of phase changes. The IP model is efficiently solved using Gurobi, a state-of-the-art optimization solver.

**Important remarks:**
 - The data used for the experiments are taken from a Awesense database.
 - In order to run the program the following are necessary:
       - Access to sandpit platform (granted by Awesense)
       - Gurobi's license

Authors: Emily Au, Marco Caoduro, Boaz Elazar, Syeda Atika Batool Naqvi, Varun Neelamana
