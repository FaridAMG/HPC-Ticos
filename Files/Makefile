all:
	mpicc -fopenmp -lm -o cenatMD cenatMD.c
	sbatch cenatMDesempeno.slurm
	
clean:
	rm -f cenatMD
