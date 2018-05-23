#Allen Yuen Assignment Makefile - Build and Launch ServerCountThrees

DIR=/home/ubuntu/ServerCountThrees

all: readInt32BitLE.c readInt32BitLE.h ServerCountThrees.c 
	gcc -o ServerCountThrees readInt32BitLE.h readInt32BitLE.c ServerCountThrees.c

test:
	mkdir $(DIR)/build 
	mv $(DIR)/src/ServerCountThrees $(DIR)/build
	cp $(DIR)/data/threesData.bin $(DIR)/build
	cd $(DIR)/build && ./ServerCountThrees

clean: 
	rm -r $(DIR)/build
     
 
