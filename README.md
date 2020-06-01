## Compile and run:

### serial_noise
Compile:
```Bash
$ g++ -std=c++11 -o serial serial_noise.cpp
```
Run:
```Bash
$ ./serial
```

### mpi_noise
Compile:
```Bash
$ mpic++ -std=c++11 -o mpi mpi_noise.cpp
```
Run:
```Bash
$ mpiexec -n <number of processes> ./mpi
```

### openmp_noise
Compile:
```Bash
$ g++ -std=c++11 -fopenmp -o openmp openmp_noise.cpp
```
Run:
```Bash
$ ./openmp <number of threads>
```
