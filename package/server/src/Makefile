# build server executable when user executes "make"
server: server.o
	$(CC) $(LDFLAGS) server.o -o server

helloworld.o: server.c
	$(CC) $(CFLAGS) -c server.c

# remove object files and executable when user executes "make clean"
clean:
	rm *.o server

