## If I'm in the work directory, what do I need to type to get to to_do?

cd ..

## If I'm in the projects_to_delegate directory, what two commands do I need to type to get to to_do?(We'll learn how to combine these momentarily)

cd  ..
cd ..
## I'm in the home directory. What three commands do I need to type to get to projects_to_delegate?(We'll learn how to combine these momentarily)

cd  cd  work/projects-delegate
## I'm in the projects_to_delegate directory. What three commands do I need to type to get to home?(We'll learn how to combine these momentarily)

cd ..
cd ..
cd ..

### I'm in to_do. What do I type to remove random.txt?

rm random.txt

### I'm in to_do. What do I type to remove the home directory?

rm -rf  home


### I'm in the work directory. What two commands do I type to remove the home directory?

cd  ..  rm -rf  home

### I'm in the projects_to_delegate directory. What two commands do I type to remove the directory I'm currently in?

cd .. rm -rf  project-to-delegate

### I'm in projects_to_delegate. What four commands do I need to type to remove the cleaning.txt file?

cd  .. cd ..  cd  home/rm  cleaning.txt
