FLAGS = -O3 -lm -lfftw3 -lpthread

all:  mrserver.o
	g++ -o out mrserver.o $(FLAGS)

mrserver.o: mrserver.cc
	g++ -c mrserver.cc $(FLAGS)

clean:
	rm -f *.o out