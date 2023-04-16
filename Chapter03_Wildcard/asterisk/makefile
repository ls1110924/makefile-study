thing_wrong := *.o
thing_right := ${wildcard *.o}

all: one two three four

one:
#one: ${thing_wrong}

two:
#two: *.o

three: ${thing_right}
	echo "three"
	echo $?

four: ${wildcard *.o}
	echo "four"
	echo $?
