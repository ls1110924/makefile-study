some_file: other_file.tmp
	echo "this line will run second"
	touch some_file.tmp

other_file.tmp:
	echo "this will run first"
	touch other_file.tmp

clean2:
	rm -f other_file.tmp

clean1:
	rm -f some_file.tmp

clean:
	rm -f some_file.tmp other_file.tmp
