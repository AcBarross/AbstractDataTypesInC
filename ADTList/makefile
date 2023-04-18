default: arraylist

arraylist:
	gcc -Wall -o prog -g main.c listElem.c listArrayList.c
	
linkedlist:
	gcc -Wall -o prog -g main.c listElem.c listLinkedList.c

valgrind:
	leaks --atExit -- ./prog

clean:
	rm -f ./prog
