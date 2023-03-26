# mm1
C program for the M/M/1 queue simulation. We use the
ANSI-standard version of the language, as defined by Kernighan and Ritchie (1988),
and in particular use function prototyping. We have also taken advantage of C’s
facility to give variables and functions fairly long names, which thus should be self-
explanatory. (For instance, the current value of simulated time is in a variable called
sim_time.)

In order to run the mm1.c program use the following command to compile with GCC:
```
gcc lcgrand.c mm1.c -o mm1 -lm
```
Then you should be able to run the executable using:
```
./mm1
```
