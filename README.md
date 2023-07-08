## HOW TO USE

1. You must have a windows machine with [gcc](https://sourceforge.net/projects/mingw-w64/) installed.

2. Clone the project
```
git clone
cd ProcessInjection
```
3. Open main.c and change the shellcode and the process name.

4. Compile the file using the Makefile in the folder bin or using gcc.

Use :
```
gcc main.c -o bin/procInj
```
or
```
cd bin
mingw32-make
```
5. Execute the output file.