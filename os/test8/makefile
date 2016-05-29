target:	dask
dask:	dask.o
		g++ dask.o -o dask
dask.o:	dask.cc dask.h
		g++ -g -c dask.cc
clean:
		rm dask*.o
