thing_wrong := *.o
thing_right := $(wildcard *.o)

all: one two three four

one: $(thing_wrong)

two: *.o

three: $(thing_right)

four: $(wildcard *.o)

print: $(wildcard *.c) # passes through when no matches
	ls -la $?
printw: *.c # specifically breaks when it finds no matches
	ls -la $?



