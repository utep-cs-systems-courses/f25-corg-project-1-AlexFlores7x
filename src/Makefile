OBJS = tokenizer.o history.o uimain.o
CFLAGS = -g -O3

all: execTokenizer

execTokenizer: $(OBJS)
	cc -o execTokenizer $(CFLAGS) $(OBJS)



$(OBJS): tokenizer.h history.h


clean:
	rm -f *.c# *.c~ *.o execTokenizer


run:execTokenizer

	./execTokenizer
