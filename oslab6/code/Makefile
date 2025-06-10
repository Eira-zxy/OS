head = dask.h
srcs = dask.cpp
objs = dask.o
opts = -Wall -g -c

all: dask

dask: $(objs)
	g++ $(objs) -o dask

dask.o: $(srcs) $(head)
	g++ $(opts) $(srcs)

clean:
	rm -f dask *.o

.PHONY: all clean