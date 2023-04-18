default:
	gcc -Wall -o prog main.c complex.c
debug:
	gcc -Wall -o prog -g main.c complex.c
valgrind:
	leaks --atExit -- ./prog
clean:
	rm -f prog


