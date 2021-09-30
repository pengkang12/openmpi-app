# Matrix multiplication on MPI and OMP

*   `matrix_mult_seq.c` sequential algorithm
*   `matrix_mult_omp.c` parallel algorithm using *OMP* primitives
*   `matrix_mult_mpi.c` parallel algotithm using *MPI*

# how to run this. 
```
mpicc matrix_mult_mpi.c -o matrix
mpirun -np 4 matrix 500
```
