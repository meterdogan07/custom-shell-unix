obj-m	:= psvis.o
 
KERNELDIR ?= /lib/modules/$(shell uname -r)/build
PWD       := $(shell pwd)
 
all: default
 
default:
	$(MAKE) -C $(KERNELDIR) M=$(PWD) modules
