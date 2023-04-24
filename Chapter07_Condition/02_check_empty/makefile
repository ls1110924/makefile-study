nullstring =
foo = ${nullstring} #note: there is a space here

all:
ifeq (${foo},)
	echo "foo is empty"
else
	echo "foo is not empty"
endif
ifeq ($(strip ${foo}),)
	echo "foo is empty after being stripped"
else
	echo "foo is not empty with valid char"
endif
ifeq (${nullstring},)
	echo "nullstring is a zero length str"
endif

