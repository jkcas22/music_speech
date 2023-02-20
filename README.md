# Data 
- Gtzan dataset, 64 of 30 sec samples, for each
- Fourier transformed to 2d map of amplitudes for frequency vs time

# Aim
- Build LTSM network, where a cell predicts speech vs music
- Feed sequentially the consecutive time samples
- Study performance depending on the number of used time steps (5-32)
- Train on 80% of the data and validate on remaining 20, study the convergence