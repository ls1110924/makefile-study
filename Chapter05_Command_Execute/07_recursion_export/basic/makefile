new_contents = "hello:\n\techo \$$(cooly)"

all:
	mkdir -p subdir
	echo ${new_contents} | sed -e 's/^ //' > subdir/makefile
	@echo "--MAKEFILE CONTENTS--"
	@cd subdir && cat makefile
	@echo "--END MAKEFILE CONTENTS--"
	cd subdir && $(MAKE)

cooly = "The subdirectory can see me!"
export cooly

clean:
	rm -rf subdir
