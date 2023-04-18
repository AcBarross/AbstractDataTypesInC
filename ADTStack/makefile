default: arraylist

arraylist:
	gcc -Wall -o prog -g main.c stackElem.c stackArrayList.c

linkedlist:
	gcc -Wall -o prog -g main.c stackElem.c stackLinkedList.c

valgrind:
	leaks --atExit -- ./prog
	
clean:
	rm -f prog

