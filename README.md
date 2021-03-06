# CellSignal_data
Cell Signal Quality database (test and training data)

Folder: CSQ_Training_Fetures

Contains the training features database:
alpha_1: hyperparameters for Dirichlet prior (body occupancy)
NB: alpha_0 is uniform (not included)
beta_1: hyperparameters for Dirichlet (body occupancy)
beta_1: hyperparameters for Dirichlet (empty environment)
Q: vector of quantized attenuations
v_0: CSQ deviations (excess attenuations) for empty environment
v_1: CSQ deviations (excess attenuations) for occupied environment
v_sim_1: CSQ simulated deviations for occupied environment
(xt_nom,yt_nom): nominal simulated position of the subject

Folders: Xperia_cellphone A, Xperia_cellphone B, Nexus_cellphone C, Xperia_cellphone D contains the test data for 4 cellular devices (from different vendors) 

Each folder contains measurements recorded in a given date (YYYY-MM-DD) corresponding to 4 cellular devices.

Each folder contains four files: 
CID: cell indentifier corresponding to a given sample
CSQ: received signal strength (dBm) corresponding to a given sample
DATE: date of sampling (YYYY-MM-DD)
TIME: time of sampling (HH-MM-ss)

True_occupancy_record_alldevicesABCD.csv contains the available true occupancy records for all devices (A,B,C,D)  
