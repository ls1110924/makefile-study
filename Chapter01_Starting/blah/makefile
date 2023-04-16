blah.app: blah.o
	echo "third start"
	cc blah.o -o blah.app
	echo "third end"

blah.o: blah.c
	echo "second start"
	cc -c blah.c -o blah.o
	echo "second end"

blah.c:
	echo "first start"
	echo "#include <stdio.h>\r int main(){\r printf(\"hello\");\r return 0;\r }" > blah.c
	echo "first end"
