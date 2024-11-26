CC = gcc
CFLAGS = -g -m32 -Wall

all: base

base: base.o
	$(CC) $(CFLAGS) -o base base.o

base.o: base.c
	$(CC) $(CFLAGS) -c base.c

clean:
	rm -f base base.o