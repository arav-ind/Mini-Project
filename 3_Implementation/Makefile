all: abc

abc:main.o phonebook.o
	gcc -Wall -o abc main.o phonebook.o

main.o:main.c
	gcc -c -Wall main.c

phonebook.o:phonebook.c
	gcc -c -Wall phonebook.c
