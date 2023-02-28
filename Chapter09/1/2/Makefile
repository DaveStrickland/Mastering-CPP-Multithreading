EXECS=hellohybrid
MPICC?=gcc

all: ${EXECS}

hellohybrid: hellohybrid.c
	gcc -c -I/opt/local/include/libomp -I/opt/local/include/mpich-mp/ -fopenmp hellohybrid.c
	gcc -o hellohybrid -L/opt/local/lib/libomp/ -L/opt/local/lib/mpich-mp/ -lmpi -fopenmp hellohybrid.o

clean:
	rm ${EXECS}
