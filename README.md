# gambarry-colab


Here is what i did for task 0

created a main.h file and included all the prototypes
created a README.md file
created all the functions by yanking them from other directories in the alx-low_level_programming repository
started creating the static library by using gcc -c *.c [please note i used other options with gcc such as -pedantic etc]
to archive i used ar -rc libmy.a as is the file we are suppose to push to the repository
to index i used ranlib libmy.a
then i did ar -t libmy.a to confirm that all the 20 files are present
then i git add . to all the remaining files, git commit and push

for task 1
i created a script in a file called create_static_lib.sh with the commands embedded
the script inside are:
#!/bin/bash
gcc -c *.o
ar -rc liball.a
git add, commit and push
