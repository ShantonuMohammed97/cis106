# Note 5
## Question 1
### a. `ls`
* **Definition:**
  * Lists files and directories.
* **Usage/Formula:**
  * ls [options] [directory].
* **Example:**
  * [directory]	ls — list the current directory’s contents.
`ls -a` — include hidden files.
`ls -lh` — show a detailed list with human-readable file sizes.

### b. `pwd`
* **Definition:**
  * Prints the absolute path of current working directory.
* **Usage/Formula:**
  * pwd
* **Example:**
  * pwd — might display /home/shanto/marstenHouse.

### c. `cd`
* **Definition:**
  * Changes your current working directory.
* **Usage/Formula:**
  * cd [directory]
* **Example:**
  * cd hallway — enter the hallway directory.
`cd ..` — move up one directory.
`cd ~` — go to your home directory.

## Question 2
**a. What is a variable?**
    A variable is a named place that stores a value, such as text or a number.

**b. How do I use a variable?**
assign a value using = sign
`name="Shanto"`
`echo "$name"`
Output: Shanto

**c. What is an environment variable?**
A variable passed to programs started from the shell. For example, HOME stores your home directory’s path. `echo "$HOME"`

**d. What is a user defined variable?**
A variable we create ourself.
`course="Linux"`
`echo "$course"`

**e. What is the root directory?**
The top directory of the Linux filesystem, written as /. All other directories are beneath it.
`cd ..`

**f. What does “Parent Directory” mean?**
The directory directly above another directory. .. refers to the parent.
`cd ..`

**g. What does “Current working directory” mean?**
The directory you are currently working in. Use `pwd` to display its path.

**h. What is an absolute path? Include an example**
A complete path starting from the root directory /.
Example: `/home/shanto/marstenHouse/hallway/.key2`

**i. What is a relative path? Include an example**
What is a relative path?
A path starting from your current working directory.
Example: `hallway/.key2` refers to that key when you are inside marstenHouse.

**j. What is the difference between “Your home directory” and “The home directory”?**
Your home directory is your personal folder, such as `/home/shanto` You can refer to it as ~ or $HOME.
The /home directory usually contains the personal home folders of regular users, such as `/home/shanto` and `/home/studen`t.

