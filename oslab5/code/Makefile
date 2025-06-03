head = vmrp.h
srcs = vmrp.cpp
objs = vmrp.o
opts = -w -g -c

all: vmrp

vmrp: $(objs)
    g++ $(objs) -o vmrp

vmrp.o: $(srcs) $(head)
    g++ $(opts) -o vmrp.o -c $(srcs)

clean:
    rm -f vmrp *.o