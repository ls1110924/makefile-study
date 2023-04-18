objects = foo.o bar.o all.o

all: ${objects}

${objects}: %.o: %.c

%.c:
	echo $@
	touch $@

all.c:
	echo "#include <stdio.h>\r int main() {\r printf(\"hello\");\r return 1;\r }" > all.c

clean:
	rm -f *.c *.o all
