# CSET-202-Project
An Algorithmic Approach to Delhi Metro Route Optimization

This is a C program to find optimal routes between stations on the Delhi metro rail network. It allows druggies to enter a source station, destination station, and voluntarily an intermediate station. The program will cipher and display the shortest metro route along with statistics like estimated trip time and chow.

Algorithms Used

- Dijkstra's algorithm to find shortest paths between stations
- Levenshtein distance for fuzzy string matching of station names

Data Structures

- proximity matrix to represent connectivity between metro stations
- Station law struct to collude station names to numeric indicators
- Min- mound precedence line for Dijkstra's perpetration

Modules

- **route.cpp ** Functions to publish final optimal route and trip stats
- **dijkstra.cpp ** Dijkstra's algorithm perpetration
- **stations.cpp ** Station data and string matching
- **graph.cpp ** Construct metro graph from station data
- **main.cpp ** motorist law and stoner interface

operation

The program requires station data files

-node_values.txt Metro station interconnectivity graph
-stationcodes.txt Mapping of station names to canons
-stationcolorcodes.txt Line color for each station

To run


gmain.cppdijkstra.cpproute.cppstations.cppgraph.cpp
./a.out


The program will prompt for launch station, end station, and intermediate station. Enter names and it'll cipher and display the optimal metro route.

Contributing

Pull requests are welcome. For major changes, please open an issue first to bandy what you would like to change.

Please make sure to modernize tests as applicable.

License

MIT ( https//choosealicense.com/licenses/mit/)
