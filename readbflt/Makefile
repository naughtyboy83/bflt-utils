CC=gcc
CFLAGS=-Wall
TARGET=readbflt

$(TARGET): readbflt.o
	$(CC) $(CFLAGS) *.o main.c -o $(TARGET)

$(TARGET).o:
	$(CC) $(CFLAGS) $(TARGET).c -c

clean:
	rm -f $(TARGET) *.o
