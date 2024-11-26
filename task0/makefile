CC = gcc
CFLAGS = -g -m32 -Wall

all: count-words

count-words: count-words.o
	$(CC) $(CFLAGS) -o count-words count-words.o

count-words.o: count-words.c
	$(CC) $(CFLAGS) -c count-words.c

clean:
	rm -f count-words count-words.o