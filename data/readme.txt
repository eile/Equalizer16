 
Plot Data Sources
--------------------

*.dat files are generated from raw log file data;
they're summing up the per-frame time of 800 frames for each test run.
The number of nodes is stored in the first column, the time in milliseconds in the second.

Naming scheme:
LBMETHOD_PACKAGES_AFFINITY.dat

e.g.:
TE_16_random.dat = Tile Equalizer, 16 tiles (4x4), "Random" (first come first served) affinity
EQNONE2DH_X_X.dat = 2D static load balancing with horizontal stripes (H), no packaging, no affinity model
