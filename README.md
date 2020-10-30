# Safe remove (srm)

> Thanks @dshubenok for help. Without him this ~~great~~ script will never be finished.

### What is this:

It is a simple script which helps remove file safely. The closest analogue is 'rm' from Git system.

### How it works:

This script will compress the file and then remove it into recycle bin (if recycle directory does not exist, the script will create that directory). The recycle bin will automatically delete the files, which are stored there for 7 (seven) days. So, you have 7 (seven) days to change your mind about deleting some files.

### Installation:

0. Create new directory 'bin' on your home page (using `mkdir ~/bin`).
0. Create new file '.bash_profile' (using `touch ~/.bash_profile`) or change it if it's already exist. 
0. Complete file '.bash_profile' by the text `export PATH="${PATH}:~/bin"`.
0. Write `source ~/.bash_profile` in command line.
0. Paste 'srm' file from this repo to '~/bin'. 
0. Write `chmod +x srm` in command line.

#### OR

0. Сlone the repo.
0. `cd` into project folder.
0. Write `chmod +x install` in command line. 
0. Run `./install` script.

### Using:

You should write `srm <filename>`, where <filename> is the name of the file you want to delete.
