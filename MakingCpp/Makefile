CC = g++ #Define Macro, here all CC means c++
CPPFLAGS = -g -Wall -I../Headers
LDFLAGS

myOut: main.cpp #here, main.run is the target and main.cpp is the dependency
	#this is the rule that will execute the cpp compiler.
	$(CC) main.cpp -o myOut
	exec ./myOut


# 	Note the following: here we are using main.run as a target. So, the make will check for
#the file main.run in order to run or not run again. Since in our rule we are not creating a main.run,
#everytime it looks for it, it won't find and will execute it the rule creating another myOut file.

# SOLUTION:
# try changin the main.run to myOut. You will see that the other times we will not have it the
# our rules to be executed again.


# Basic System Signals and Make Integration
# here we will use the exec function for POSIX systems in our rule.
# exec creates a subshell, runs the
