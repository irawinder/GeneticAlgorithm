# GeneticAlgorithm
by Ira Winder [jiw@mit.edu] as a demonstrative learning aid for Mingrui Wang [9860851159@edu.k.u-tokyo.ac.jp]

For educational purposes ONLY!

The following script will implement the following:
1. Parameterized model of a the logistics request network,  according to Mingrui's work
2. Evaluation of the network's cost
3. Genetic Algorithm to discover least cost solution
 
## Model Description:
The model assumes that 20 given sites create a net amount of refuse that needs to be collected and delivered to a set of "Stations" over a period of time. The model may implement the construction of up to 10 stations that have pre-known locations,  construction costs,  and transportation costs associated with them. 

## Optimization Goal: 
Since each potential station will have unique capital cost and operations costs,  it is not obvious which configuration will be the cheapest to build. Therefore,  we build our model to discover solution that achieves the minimum cost while providing enough capacity for all refuse to be collected.
