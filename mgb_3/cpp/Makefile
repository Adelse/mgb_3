TARGET = program
DEBTARGET = debprogram
CXX = g++

build:
	$(CXX) -c ./src/main.cpp -o ./obj/main.o
	$(CXX) -c ./src/math.cpp -o ./obj/math.o
	$(CXX) ./obj/main.o ./obj/math.o -o $(TARGET)

debug: build
	$(CXX) -g -o debprogram ./src/main.cpp ./src/math.cpp

clean:
	rm ./obj/*.o $(TARGET) $(DEBTARGET)