# Graph abstraction reconciles clustering with trajectory inference through a topology preserving map of single cells

Our preprint will soon be updated but contains the essential ideas: [Wolf *et al.*, bioRxiv (2017)](https://doi.org/10.1101/208819).

Note the former repository https://github.com/theislab/graph_abstraction, which for now still contains some of the material presented in the preprint; we will move this material here, soon.

*Partition-based graph abstraction* (PAGA) is available within
[Scanpy](https://scanpy.readthedocs.io). Central toplevel functions are:
* [`scanpy.api.tools.paga`](https://scanpy.readthedocs.io/en/latest/api/scanpy.api.tl.paga.html)
* [`scanpy.api.plotting.paga`](https://scanpy.readthedocs.io/en/latest/api/scanpy.api.pl.paga.html)
* [`scanpy.api.plotting.paga_path`](https://scanpy.readthedocs.io/en/latest/api/scanpy.api.pl.paga_path.html)
* [`scanpy.api.plotting.paga_compare`](https://scanpy.readthedocs.io/en/latest/api/scanpy.api.pl.paga_compare.html)

Central example notebooks are:

* [*blood/paul15*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/paul15/paul15.ipynb): hematopoiesis - if you start working with PAGA, start with this
* [*blood/nestorowa16*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/nestorowa16/nestorowa16.ipynb): hematopoiesis
* [*blood/dahlin18*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/dahlin18/dahlin18.ipynb): hematopoiesis
* [*blood/simulated*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/blood/simulated/simulated.ipynb): simulated hematopoiesis
* [*planaria*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/planaria/planaria.ipynb): planarian lineages (Plass *et al.*, 2018)
* [*zebrafish*](https://nbviewer.jupyter.org/github/theislab/paga/blob/master/zebrafish/zebrafish.ipynb): lineages of zebrafish embryo (Wagner *et al.*, 2018)


