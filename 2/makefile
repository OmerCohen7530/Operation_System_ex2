CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra

all: ttt mync

ttt: tic_tac_toe.cpp
	$(CXX) $(CXXFLAGS) -o ttt tic_tac_toe.cpp

mync: mync.cpp
	$(CXX) $(CXXFLAGS) -o mync -g mync.cpp

.PHONY: clean

clean:
	rm -f ttt mync
