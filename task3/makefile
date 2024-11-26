CC = gcc
CFLAGS = -g -m32 -Wall

all: menu

menu: menu.o
	$(CC) $(CFLAGS) -o menu menu.o
	
menu.o: menu.c
	$(CC) $(CFLAGS) -c menu.c

clean:
	rm -f menu menu.o