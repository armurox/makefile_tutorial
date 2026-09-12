blah: blah.o
	gcc blah.o -o blah # runs third

blah.o: blah.c
	gcc -c blah.c # runs second

blah.c:
	echo "int main(void) { return 0; }" > blah.c
