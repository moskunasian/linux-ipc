CC = gcc
CFLAGS = -g -Wall
OBJECTS = skipList.o testDriver.o

testDriver : $(OBJECTS)
	$(CC) $(CFLAGS) $(OBJECTS) -o testDriver
	
%.o : %.c
	$(CC) $(CFLAGS) -c $<
