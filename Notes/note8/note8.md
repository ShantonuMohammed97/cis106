# Note 8
## cat
* **Definition:**
  * `cat` displays all the contents from the beginning of file.
* **Usage:**
  * `cat` + `file_name`
* **Example:**
* `cat` access.log

## tac
* **Definition:**
* `tac` displays a file in reverse line order. The last line appears first.
* **Usage:**
  * `tac` + `file_name`
* **Example:**
* `tac` access.log
* 
## head
* **Definition:**
  * `head` displays the first 10 lines.
* **Usage:**
  * `head` + `file_name`
* **Example:**
* `head` access.log
* `head` -n 5 access.log (to display specific number of lines)

## tail
* **Definition:**
  * `tail` displays the last 10 lines of file.
* **Usage:**
  * `tail` + `file_name`
* **Example:**
* `tail` access.log
* `tail` -n 8 access.log (to display specific number of lines)

## cut
* **Definition:**
* `cut` extracts specific fields, characters, or sections from each line of a file..
* **Usage:**
  * `cut` -d 'delimiter' -f field_number filename
* **Example:**
* `cut` -d ' ' -f3 access.log.
* `cut` -d ' ' -f3,4 --output-delimiter=' accessed: ' access.log.

## short
* **Definition:**
  * sort arranges the lines of a file alphabetically or numerically. It displays the result without changing the original file unless use -o.
* **Usage:**
  * `short` + `file_name`
  * `sort` `-k field,field filename`
* **Example:**
* `sort -k3,3 -o sorted_access_log_by_uname.log access.log` (Sort access.log by the username in field 3 and save it)
* `sort -k4,4 -o sorted_access_log_by_endpoint.log access.log` (Sort by the endpoint in field 4 and save it)

## wc
* **Definition:**
* `wc` means “word count.” It counts the lines, words, characters, or bytes in a file.
* 
* **Usage:**
- `wc -l  file` counts lines.
- `wc -w  file` counts words.
- `wc -m  file` counts characters.
- `wc -c file` counts bytes.
* **Example:**
* `wc -l access.log`
* `wc -w access.log`
* `wc access.log` (Display lines, words, and bytes together)