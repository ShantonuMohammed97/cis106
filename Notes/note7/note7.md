# Note 7

## Wildcards

### The * (Asterisk)

* To get list of every .txt file: **`ls *.txt`**
* To move every .jpg file into images: **`mv *.jpg images/`**
* To remove every file beginning with temp: **`rm temp*`**

### The Question mark (?)

* List all the files that have 3 letter file extension: **`ls *.???`**
* List all the files that start with letter b and have two characters following: **`ls b??*.*`**
* List all the files that are hidden and have a two letter file extension: **`ls .??*.??`**

### The Square brackets []

* List all the files that start with a lowercase letter and have 3 letter file extension: **`ls [a-z]*.???`**
* List all the files that start with an uppercase letter and have a number in the name: **`ls [A-Z]*[0-9]*`**
* List all the files that start with a year in the format yyyy: **`[0-9][0-9][0-9][0-9]*`**

## Brace Expansion
Brace expansion generates several names from one pattern. It is useful for creating an entire directory structure with one mkdir command.
### Example 1
* To create a tree of music folder: **`mkdir -pv music/{jazz,rock}/{mp3files,videos,oggfiles}/new`**
### Example 2
* To create a tree of website folder: **`mkdir -p website/{assets/{css,images,js},pages/{about,contact},documents}`**