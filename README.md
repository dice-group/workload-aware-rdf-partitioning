# workload-aware-rdf-partitioning

### Benchmark Datasets and Queries
We provide the datasets and queries of the benchmarmks and real-world datasets used in our evaluation.

### Benchmark Datasets and Queries
We provide the datasets and queries of the benchmarmks and real-world datasets used in our evaluation.


#### Datasets 
| [Semantic Web Dog Food (SWDF)](https://hobbitdata.informatik.uni-leipzig.de/benchmarks-data/datasets-dumps/) | [DBpedia](http://downloads.dbpedia.org/3.5.1/en/) |
|----------------------------|-----------|

#### Train Queries 
| [SWDF-BGP-only](https://drive.google.com/drive/folders/19Ig29n0NAmUfEu6nJwzchmZgRWX8w9NN?usp=sharing) | [SWDF-Fully-featured](https://drive.google.com/drive/folders/19Ig29n0NAmUfEu6nJwzchmZgRWX8w9NN?usp=sharing) |
 [DBpedia-BGP-only](https://drive.google.com/drive/folders/19Ig29n0NAmUfEu6nJwzchmZgRWX8w9NN?usp=sharing) | [DBpedia-Fully-featured](https://drive.google.com/drive/folders/19Ig29n0NAmUfEu6nJwzchmZgRWX8w9NN?usp=sharing) |
 
#### Benchmark Queries 
| [SWDF BGP-only](https://hobbitdata.informatik.uni-leipzig.de/rdf-partitioning/benchmarkQueries/) | [SWDF Fully-featured](https://hobbitdata.informatik.uni-leipzig.de/rdf-partitioning/benchmarkQueries/) |
 [DBpedia BGP-only](https://hobbitdata.informatik.uni-leipzig.de/rdf-partitioning/benchmarkQueries/) | [DBpedia Fully-featured](https://hobbitdata.informatik.uni-leipzig.de/rdf-partitioning/benchmarkQueries/) |

### Reproducing Results

 1. Download and built [Koral](https://github.com/Institute-Web-Science-and-Technologies/koral) project and follow the steps.
 2. Next, download and build existing rdf-partitioning evaluation for seven techniques from [here](https://github.com/dice-group/rdf-partitioning) and follow the steps.
 3. Source code for PCM can be found [here](https://github.com/renespeck/Cugar/blob/master/src/de/uni_leipzig/mcl/cluster/MarkovClustering.java)
 4. Source code for PartOut can be found [here](https://drive.google.com/drive/folders/11fGZ_2Rm6s38LmbIRNUl2Nd4_D4INR28)

 ```html
### Authors 
* [Adnan Akhter](http://dice.cs.uni-paderborn.de/team/profiles/akhter/) (AKSW, University of Leipzig)
* [Muhammad Saleem](https://sites.google.com/site/saleemsweb/) (AKSW, University of Leipzig)
* [Axel-Cyrille Ngonga Ngomo](http://aksw.org/AxelNgonga.html) (AKSW, University of Leipzig)
