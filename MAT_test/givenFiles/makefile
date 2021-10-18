main: main.o greeting.o
	g++ main.o greeting.o -o main

main.o: main.cpp greeting.h
	g++ -c main.cpp

greeting.o: greeting.cpp greeting.h
	g++ -c greeting.cpp


clean:
	rm *o main
