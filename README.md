# web-proxy-HW

To compile:
gcc -c proxy.c && gcc -c csapp.c
gcc -pthread csapp.o proxy.o -o proxy

Or, type "make" to use the makefile