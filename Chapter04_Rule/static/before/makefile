objects = foo.o bar.o all.o

all: ${objects}

foo.o: foo.c

bar.o: bar.c

all.o: all.c

%.c:
	echo $@
	touch $@

all.c:
	echo "#include <stdio.h>\r int main() {\r printf(\"hello\");\r return 0;\r }" > all.c

clean:
	rm -f *.c *.o all

