PWD   := $(shell pwd)
obj-m += sysfs1.o
obj-m += sysfs-poll.o

all:
	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) 
clean:
	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) clean
