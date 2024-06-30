CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra

all: mync ttt

mync: mync.cpp
	$(CXX) $(CXXFLAGS) -g -o $@ $^

ttt: tic_tac_toe.cpp
	$(CXX) $(CXXFLAGS) -g -o $@ $^
	
.PHONY: clean

clean:
	rm -f mync ttt

# ./mync -i TCPS4050


# ./mync -b TCPS4050 


# ./mync -i TCPS4050 -o TCPClocalhost,4455