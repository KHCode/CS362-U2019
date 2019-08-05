CFLAGS = -Wall -fpic -coverage -lm -std=c99

testresults:
	gcc -o testme testme.c $(CFLAGS)
	-testme >> prints.out
	-gcov testme.c -b -f >> testresults.out

clean: 
	-rm testme *.gcov *.out *.gcda *.gcno

