CFLAGS=-g -O3
CC=gcc

all: execTokenizer


history.o: history.c
	$(CC) $(CFLAGS) -c history.c


uimain.o: uimain.c
	$(CC) $(CFLAGS) -c uimain.c

tokenizer.o: tokenizer.c
	$(CC) $(CFLAGS) -c tokenizer.c


execTokenizer: uimain.o tokenizer.o history.o
	$(CC) $(CFLAGS) -o execTokenizer uimain.o tokenizer.o history.o

clean:
	rm -f *.o dotokenizer
