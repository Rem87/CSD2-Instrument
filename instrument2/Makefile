
playSound: playSound.o instrument.o string.o bass.o percussie.o
	g++ -o playSound playSound.o instrument.o string.o bass.o percussie.o

playSound.o: playSound.cpp
	g++ -c playSound.cpp

instrument.o: instrument.cpp instrument.h
	g++ -c instrument.cpp

string.o: string.cpp string.h
	g++ -c String.cpp

bass.o: bass.cpp bass.h
	g++ -c bass.cpp

percussie.o: percussie.cpp percussie.h
		g++ -c percussie.cpp

clean:
	rm -f *.o playSound
