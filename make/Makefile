hello: Main.o Hello.o
	g++ -o hello Main.o Hello.o
Main.o: Main.cpp Hello.h
	g++ -I. -c Main.cpp
Hello.o: Hello.cpp Hello.h
	g++ -I. -c Hello.cpp
