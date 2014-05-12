CC=g++
CFLAGS=-c -Wall
LDFLAGS=
SOURCES=HelloWorld.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=helloworld

all: $(SOURCES) $(EXECUTABLE)
	
clean: 
	rm -f *o $(EXECUTABLE)

$(EXECUTABLE): $(OBJECTS)
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@

