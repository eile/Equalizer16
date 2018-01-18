
Plot Data Sources
--------------------

*.dat files are generated from raw log file data;
they're summing up the per-frame time of 790 frames (the first 10 frames are discarded) for each test run.
The number of nodes is stored in the first column, the time in milliseconds in the second.


Naming scheme:

LBMETHOD_PACKAGES_AFFINITY.dat

e.g.:
TE_16_random.dat = Tile Equalizer, 16 tiles (4x4), "Random" (first come first served) affinity
EQNONE2DH_X_X.dat = 2D static load balancing with horizontal stripes (H), no packaging, no affinity model
EQLOADDBU_X_X.dat = DB Load Equalizer, render node usage adjusted (U) to heterogeneous load


Folders with data:

eqPly
eVolve
eVolve_het (eVolve with heterogeneous load)
eVolve_frame_het (eVolve with heterogeneous load varying every frame)


Heterogeneous load per node:

Channel     Node    Load Power
channel_9   node01  6x   0.17
channel_1   node02  5x   0.2
channel_2   node03  1x   1.0
channel_3   node04  6x   0.17
channel_4   node05  7x   0.14
channel_5   node06  1x   1.0
channel_6   node07  4x   0.25
channel_7   node08  1x   1.0
channel_8   node09  4x   0.25
