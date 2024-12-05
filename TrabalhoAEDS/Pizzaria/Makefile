all: main

main: pizza.o ingrediente.o main.o
	gcc pizza.o ingrediente.o main.o -o main

pizza.o: pizza.c pizza.h
	gcc -c pizza.c

ingrediente.o: ingrediente.c ingrediente.h
	gcc -c ingrediente.c

main.o: main.c
	gcc -c main.c

clean:
	rm -rf *.o main

run:
	./main

