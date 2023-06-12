Examples of commands used together with pipelines


ls -lt | head  :  Displays the 10 newest files in the current directory.
du | sort -nr  :  Displays a list of directories and how much space they consume, sorted from the largest to the smallest.
find . -type f -print | wc -l  :  Displays the total number of files in the current working directory and all of its subdirectories.


Filters


Common filter commands

sort  :  Sorts standard input then outputs the sorted result on standard output.
uniq  :  Given a sorted stream of data from standard input, it removes duplicate lines of data (i.e., it makes sure that every line is unique).
grep  :  Examines each line of data it receives from standard input and outputs every line that contains a specified pattern of characters.
fmt   :  Reads text from standard input, then outputs formatted text on standard output.
pr    :  Takes text input from standard input and splits the data into pages with page breaks, headers and footers in preparation for printing.
head  :  Outputs the first few lines of its input. Useful for getting the header of a file.
tail  :  Outputs the last few lines of its input. Useful for things like getting the most recent entries from a log file.
tr    :  Translates characters. Can be used to perform tasks such as upper/lowercase conversions or changing line termination characters from one type to another (for example, converting DOS text files into Unix style text files).
sed   : Stream editor. Can perform more sophisticated text translations than tr.
awk   : An entire programming language designed for constructing filters. Extremely powerful.
