# MSc Thesis Maaike Trân
## TU Delft - Engineering and Policy Analysis

Three files with code:
1. Roadnetwork. Based on a shape file provided. This was a first exploration of the road network in Mali. The network was found to contain some discrapancies compared to the real world road network.
2. OpenStreetMap. As an alternative to the Roadnetwork file, OpenStreetMap was used as a source of road network data. This data turned out to be more detailed on characteristics of road edges. The road network has been downloaded and is saved in a seperate file which is also available. The file contains multiple parts. Firstly, the loading of the roadnetwork. Secondly, some general statistics of the network as a whole. Thirdly, analysing the attributes of the network. Subsequently, the population data of the Malian cities is added as a node attribute. Lastly, based on all the previous data the weight cost function is applied indicating the criticality of each road part. This criticality measure is used as input for the game theory model.
3. Game. This file contains the game on which the optimal strategies of both actors (defendent and attacker) is based. 
