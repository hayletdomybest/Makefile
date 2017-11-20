obj := main.o fuc.o
cc  := gcc 

main.o:
	cc -c main.c
fuc.o:
	cc -c fuc.c


all: $(obj)
	cc -o  $@  $^

.PHONY=clean

clean:
	rm ${obj} all


