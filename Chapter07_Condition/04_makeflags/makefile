bar =
foo = ${bar}

all:
ifneq (,$(findstring i, $(MAKEFLAGS)))
	echo "i was passed to MAKEFLAGS"
else
	echo "i wasn't passed to MAKEFLAGS"
endif




