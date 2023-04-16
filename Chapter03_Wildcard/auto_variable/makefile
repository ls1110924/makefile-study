one = one.tmp
two = two.tmp
hey = hey.tmp

${hey}: ${one} ${two}
	echo $@
	echo $?
	echo $^
	touch ${hey}

${one}:
	touch ${one}

${two}:
	touch ${two}

clean:
	rm -f *.tmp
