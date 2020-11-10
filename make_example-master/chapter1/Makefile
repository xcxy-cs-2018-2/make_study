#this is a makefile example
.PHONY:clean

main:main.o
	gcc -o main main.o

main.o:main.c
	gcc -c main.c

clean:
	-rm main *.o
	@echo hello
