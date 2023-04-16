files = file1.tmp file2.tmp

some_file.tmp: $(files)
	echo "look at this variable: " $(files)
	touch some_file.tmp

file1.tmp:
	touch file1.tmp

file2.tmp:
	touch file2.tmp

clean:
	rm -f ${files} some_file.tmp

show:
	echo $(files)
	echo ${files}
