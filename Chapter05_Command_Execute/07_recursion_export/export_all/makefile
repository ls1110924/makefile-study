.EXPORT_ALL_VARIABLES:

new_contents="hello:\n\techo \$$(cooly)"

cooly="the subdirectory can see me!"

all:
	mkdir -p subdir
	echo ${new_contents} | sed -e 's/^ //' > subdir/makefile
	@echo "--MAKEFILE CONTENTS--"
	@cd subdir && cat makefile
	@echo "--END MAKEFILE CONTENTS--"
	cd subdir && $(MAKE)

clean:
	rm -rf subdir

