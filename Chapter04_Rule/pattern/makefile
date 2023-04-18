%.o: %.c
	echo "hello"
	${CC} -c ${CFLAGS} ${CPPFLAGS} $< -o $@

all: all.o foo.o

all.c:
	echo "#include <stdio.h>\r int main() {\r printf(\"hello world\");\r return 1;\r  }\r" > all.c

%.c:
	echo "generate c file"
	touch $@

clean:
	rm -f *.c *.o all
