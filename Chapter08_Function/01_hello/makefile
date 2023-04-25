bar := ${subst not,totally,"I am not superman"}

comma := ,
empty :=
space := ${empty} ${empty}
foo := a b c
foo_result = ${subst ${space},${comma},${foo}}
foo_result1 = ${subst ${space}, ${comma}, ${foo}}
foo_result2 = ${subst ${space}, ${comma},${foo}}
foo_result3 = ${subst ${space},${comma}, ${foo}}

all:
	echo ${bar}
	echo ${foo_result}
	echo --"${foo_result1}"--
	echo ${foo_result2}
	echo ${foo_result3}

