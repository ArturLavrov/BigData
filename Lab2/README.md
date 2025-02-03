# Flight Network Analysis using Spark GraphX / GraphFrame

## Data Description  
[OpenFlights Data](https://openflights.org/data.html)

## Datasets Used  
- **airports-extended.dat**: [Dataset link](https://github.com/fcerbell/sampledata/tree/master/OpenFlights.org) (includes airport coordinates)  
- **airlines.dat**  
- **routes.dat**  

## Tasks to Solve  
1. **Find the airline with the largest total flight distance. Do the same for the smallest total flight distance.**  
2. **Find all possible flights between Poland and Belgium (with no more than 2 stopovers).**  
   - Use **motif search** and other approaches.  
   - Compare their performance and implementation complexity.  
3. **Find airports with the fewest and most flights.**  
4. **Find the shortest and longest route between two given airports, using flight distance as the path length.**  
   - Consider routes with stopovers (**no more than 4**).  
5. **Find the airline with the largest total flight distance.**  
6. **Identify large airport clusters (at least 5 airports) based on flight connections.**  
   - Analyze the results of cluster formation.  
7. **Find subgraphs with at least 2 nodes that are connected but have no links to other airports.**  
