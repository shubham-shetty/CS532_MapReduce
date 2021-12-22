# MapReduce Framework

This library recreates the working of the MapReduce processing framework, designed for multiple processes running on a single server.

* MapReduce paper: https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf  
* Project Description: https://docs.google.com/document/d/1UkbhEz8FCfKOIBlBW26WUGD78yTh7I_qqGOerHABjd0/edit?usp=sharing

## Instructions
The project uses `conda` for package, environment, and dependency management via the `environment.yml` file, which tracks the project dependencies, including the python version against which our system is stable. Please make sure you have [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed before proceeding. 

The script we provide will install the necessary dependencies and execute the test scripts.
```
sh run_tests.sh
```
Each test script generates intermediate and final output files in the `test_scripts/` directory.
