# NMJ_ephys_analysis
Matlab code used to analyze intracellular NMJ recordings

mEJP_analysis.m takes .mat files from Chart software and displays recordings, allowing you to select the region of recording
you would like to analyze. After analyzing a batch of files, it outputs mini frequency, amplitude, and average membrane
potential. The code requires also requires Getspikes.m, Getoptions.m, Derivfilter.m, RealUnderscores.m, NamedFigure.m, PlotGetSpikes.m from Marder lab https://github.com/marderlab/Spike_analysis
The following miniOptions settings in Getspikes.m were used for analysis:
'bracketWidth', 100.0, ... 'minCutoffDiff', 0.0005, ... 'minSpikeAspect', 0.005, ... 'minSpikeHeight', .2, ... 'pFalseSpike', 0.01, ... 'discountNegativeDeriv', true, ... 'recursive', true ...

Comments/concerns can be addressed to griffith@brandeis.edu. Note: We cannot provide advice/assistance with configuring your system.
