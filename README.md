
The Network Simulator, Version 3
================================

### Compiling

``` shell
./waf configure --build-profile=debug --enable-mpi --enable-examples --enable-tests --enable-gcov 
./waf -j4
```

### Compiling with Singularity

Wrap the command with backwards single quote.

### Running BBR example [with singularity]

``` shell
./waf --run tcp-bbr-example
```

### Running basic sim example

``` shell
./waf --run basic-sim-example-single-flows
```
