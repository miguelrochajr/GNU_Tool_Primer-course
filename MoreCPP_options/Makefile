CC = g++ #Define Macro, here all CC means c++
CPPFLAGS = -g -Wall -I../Headers #the -g insert debugging infromation.
																 # -Wall inserts all warnings
																 # -I<dir> adds <dir> to #include file search path
LDFLAGS = -L../lib/ -lera				 # -L<dir> adds <dir> to library search path
																 # -l<dir> Request link do library lib<name>.a
main.run: main.cpp
	$(CC) main.o $(LDFLAGS) -o main.run

main.o:
	$(CC) $(CPPFLAGS) -c main.cpp #the -c Compile a .cpp to .o (Object File), skipping the link phase
