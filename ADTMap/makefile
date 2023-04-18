default: arraylist

arraylist:
	gcc -Wall -o prog -g mapElem.c mapArrayList.c main.c 

linkedlist:
	gcc -Wall -o prog -g mapElem.c mapLinkedList.c main.c

valgrind:
	leaks --atExit -- ./prog

clean:
	rm -f ./prog

