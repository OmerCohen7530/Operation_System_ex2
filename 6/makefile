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

# ./mync -e "ttt 123456789" -i UDSSD/tmp/mysocket

# ./mync -o UDSCD/tmp/mysocket

# ./mync-e "ttt 123456789" -i UDSSS/tmp/mysocket

# ./mync -o UDSCS/tmp/mysocket