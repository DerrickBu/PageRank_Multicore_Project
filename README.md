# PageRank_Multicore_Project
The multicore project about page rank for NYU course 'Multicore Processors: Architecture &amp; Programming' in spring 2020
## Generate data

compile program which helps us generate input data by using on Linux server:
```
g++ -std=c++11 page.cpp generate_data.cpp -o main
```

run the program:
 ```
 ./main 10 4 10 
 ```
 
 The first parameter is total pages, the second is max in links per page, and the third is page counts per chunk
 
 ## Compute page rank (serial version)
 
 compile program which calculates page ranks by using:
 ```
 g++ -std=c++11 serial_version.cpp metadata.cpp page.cpp -o serial
 ```
 
 run the program:
 ```
 ./serial
 ```
