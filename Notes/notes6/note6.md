# Note 6
## mkdir
* **Definition:**
  * Creates a new directory.
* **Usage:**
  * `mkdir` + `directory_name`
* **Example:**
* mkdir website
* mkdir documents pictures
* mkdir -p website/assets/images

## touch
* **Definition:**
  * Creates an empty file
* **Usage:**
  * `touch` + `file_name`
* **Example:**
* touch notes.txt
* touch index.html
* touch file1.txt file2.txt

## rm
* **Definition:**
  * Removes files or directories
* **Usage:**
  * `rm` + `file_name`
  * `rm` + `-r directory_name`
* **Example:**
* rm notes.txt
* rm image.png
* rm -r website

## cp
* **Definition:**
  * Copies files or directories to another location.
* **Usage:**
  * `cp` + `source destination`
  * `cp` + `-r source_directory destination`
* **Example:**
* cp notes.txt backup.txt
* cp image.png ~/Pictures/
* cp -r website website-backup

## mv
* **Definition:**
  * Moves a file or directory. It is also used to rename files and directories.
* **Usage:**
  * `mv` + `source destination`
* **Example:**
* Move a file:`mv old-name.txt new-name.txt`
* Rename a file:`mv old-name.txt new-name.txt`
* Move and rename at the same time: `mv recording.gif ~/lab6-challenge2/slideshow.gif`