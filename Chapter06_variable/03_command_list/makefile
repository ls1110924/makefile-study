one = export blah="I was set!"; echo $${blah}

define two
export blah="I was set!"
echo $$blah
endef

all:
	echo "this prints 'I was set'"
	${one}
	echo "this does not print 'I was set' because each command runs in a separate shell"
	${two}

