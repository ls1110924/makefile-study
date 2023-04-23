one = one ${later_variable}

two := two   ${later_variable}

two := ${two} three

one ?= this is one

three ?= three

later_variable = later

four = four   # test

five = ${four} five

null =
space = $(null) 

seven:=start
seven+=end

all:
	echo --${one}--
	echo --${two}--
	echo --${three}--
	echo "$(five)"
	echo "${five}"
	echo start"$(space)"end
	echo "${six}"
	echo "seven-->${seven}"
