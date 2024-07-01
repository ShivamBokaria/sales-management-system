# Makefile 

# Variables
CC = g++
JOSH = -g
EJECUTABLE = main

# Program Principal
all: lista.h nodo.h
	$(CC) $(JOSH) nodo.h lista.h main.cpp -o $(EJECUTABLE)

# Libraries



lista.h: lista.h 
	$(CC) $(JOSH) -c lista.h
nodo.h: nodo.h 
	$(CC) $(JOSH) -c nodo.h
	

clean:
	rm -rf *.o $(EJECUTABLE) 
