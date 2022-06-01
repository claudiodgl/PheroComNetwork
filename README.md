## PheroComNetwork

PheroComNetwork represents a data set of simulations that models the evolution of the communications of a swarm of robots in the surveillance task, including eventual failures.

## Network description

The "complex_network.dat" contains the graph mapped in this simulations, with:

* 12 nodes (robots)
* 63,743 edges
* 10,000 timestamps

There is a total of 20 failures: 

* 14 robot failures 
* 4 cluster failures 
* 2 swarm failures
 
The environment is composed of 40 rooms and dimensions equal to 9,600 cells.

## File description

The file format is: 

* node_origin (space) node_destiny (space) timestamp
* each line represents a edge in a timestamp
* nodes ids varies from 1 to 12 (two first columns)
* timestamps varies from 2 to 10,000

## PheroCom description

The PheroCom model is originy described in: 

* Tinoco, C. R., & Oliveira, G. M. B. (2022). PheroCom: Decentralised and asynchronous swarm robotics coordination based on virtual pheromone and vibroacoustic communication. arXiv. DOI: [https://doi.org/10.48550/arXiv.2202.13456](https://doi.org/10.48550/arXiv.2202.13456)
