# Comparison with stemID 2

Reproduce the comparison with stemID 2, the successor of stemID [(Grün *et al.*, Cell. Stem Cell,
  2016)](https://doi.org/10.1016/j.stem.2016.05.010), 
by running [*RaceID3_StemID2_sample.R*](RaceID3_StemID2_sample.R).
```
time Rscript RaceID3_StemID2_sample.R
```
See [*logfile_X_krumsiek11_blobs_shifted.txt*](*logfile_X_krumsiek11_blobs_shifted.txt*) for the logging output that we produced.

We acknowledge D. Grün for providing the code via Email; parameters were chosen
by D. Grün so that stemID would produce sensible results. The code is an
improved version of the original stemID, which is available from https://github.com/dgrun/StemID/.

We note that we also tried running the code on the simpler data file *X_krumsiek11_shifted.csv* with the same parameters, but were not able to do so as this resulted in errors.