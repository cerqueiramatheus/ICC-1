CC=gcc
INCLUDES=./include
SOURCES=./source/extractor.c ./source/metadata.c ./source/register.c ./source/index.c 
BINARY=./database
PROG=./database.c
LIBS=-lm

all:
	@ $(CC) -g -o $(BINARY) $(PROG) $(SOURCES) -I$(INCLUDES) $(LIBS)

preproc:
	$(CC) -E $(PROG) $(SOURCES) -I$(INCLUDES) $(LIBS)

run:
	$(BINARY)