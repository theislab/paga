# PAGA - partition-based graph abstraction

*Mapping out the coarse-grained connectivity structures of complex manifolds [(bioRxiv, 2017)](https://doi.org/10.1101/208819).*

![PAGA for hematopoiesis.](http://www.falexwolf.de/img/paga_paul15.png "PAGA for hematopoiesis.")

PAGA is available within [Scanpy](https://scanpy.readthedocs.io/en/latest/examples.html#trajectory-inference) through: [`tl.paga`](https://scanpy.readthedocs.io/en/latest/api/scanpy.tl.paga.html) | [`pl.paga`](https://scanpy.readthedocs.io/en/latest/api/scanpy.pl.paga.html) | [`pl.paga_path`](https://scanpy.readthedocs.io/en/latest/api/scanpy.pl.paga_path.html) | [`pl.paga_compare`](https://scanpy.readthedocs.io/en/latest/api/scanpy.pl.paga_compare.html).

Below you find links to all central example notebooks, which also allow reproducing all main figures of the paper. If you start working with PAGA, go through [*blood/paul15*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/paul15/paul15.ipynb).

notebook       | system         | details  | reference | figure
---------------| ---------------| ---------| ----------| ------
[*blood/simulated*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/simulated/simulated.ipynb) | hematopoiesis | simulated | [Krumsiek *et al.*, Plos One (2011)](https://doi.org/10.1371/journal.pone.0022649) | 2a
[*blood/paul15*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/paul15/paul15.ipynb) | murine hematopoiesis | 2,730 cells, MARS-seq | [Paul *et al.*, Cell (2015)](https://doi.org/10.1016/j.cell.2015.11.013) | 2b
[*blood/nestorowa16*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/nestorowa16/nestorowa16.ipynb) | murine hematopoiesis | 1,654 cells, Smart-seq2 | [Nestorowa *et al.*, Blood (2016)](https://doi.org/10.1182/blood-2016-05-716480) | 2c
[*blood/dahlin18*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/dahlin18/dahlin18.ipynb) | murine hematopoiesis | 44,802 cells, 10x Genomics | [Dahlin *et al.*, Blood (2018)](https://doi.org/10.1182/blood-2017-12-821413) | 2d
[*planaria*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/planaria/planaria.ipynb) | planaria | 21,612 cells | [Plass *et al.*, Science (2018)](https://doi.org/10.1126/science.aaq1723) | 3
[*zebrafish*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/zebrafish/zebrafish.ipynb) | zebrafish embryo | 53,181 cells |  [Wagner *et al.*, Science (2018)](https://doi.org/10.1126/science.aar4362) | 4
[*1M_neurons*](https://github.com/theislab/scanpy_usage/blob/master/170522_visualizing_one_million_cells/logfile_1.3M.txt) | neurons | 1.3 million cells, 10x Genomics | [10x Genomics (2017)](https://support.10xgenomics.com/single-cell-gene-expression/datasets/1M_neurons) | S12
[*deep_learning*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/deep_learning/deep_learning.ipynb) | cycling Jurkat cells | 30,000 single-cell images |  [Eulenberg *et al.*, Nat. Commun. (2017)](https://doi.org/10.1038/s41467-017-00623-3) | S14

All supplemental figures of the paper can be reproduced based on the following table.

notebook       |  description | figure
---------------|  ----------| ------
[*connectivity_measure*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/connectivity_measure/connectivity_measure.ipynb) | connectivity measure | S1, S2, S3
[*robustness*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/robustness) | robustness and multi-resolution capacity | S4, S5
[*comparisons/simulated_data*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/comparisons/simulated_data) | comparisons for simulated data | S6, S7
[*comparisons/paul15_monocle2*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/comparisons/paul15_monocle2) | comparison Monocle 2 for Paul *et al.* (2015) | S8
[*comparisons/nestorowa16_monocle2*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/comparisons/nestorowa16_monocle2) | comparison Monocle 2 for Nestorowa *et al.* (2016) | S9
[*embedding_quality*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/embedding_quality/embedding_quality.ipynb) | quantifying embedding quality | S10
[*simulation*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/simulated/simulated.ipynb) | simulating hematopoiesis | S11
[*1M_neurons*](https://github.com/theislab/scanpy_usage/blob/master/170522_visualizing_one_million_cells/logfile_1.3M.txt) | neurons, 1.3 million cells, 10x Genomics, [10x Genomics (2017)](https://support.10xgenomics.com/single-cell-gene-expression/datasets/1M_neurons) | S12
[*blood/paul15*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/paul15/paul15.ipynb) | annotation of louvain clusters using PAGA | S13
[*deep_learning*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/deep_learning/deep_learning.ipynb) | cycling Jurkat cells, 30,000 single-cell images, [Eulenberg *et al.*, Nat. Commun. (2017)](https://doi.org/10.1038/s41467-017-00623-3) | S14
