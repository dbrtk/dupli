
This module finds duplicated files in a given directory. Binary files with
duplicates can be created using the out_create_files.sh script.

A directory that will contain the generated files, needs to be created.


The command generating files with duplicates:
bash out_create_files.sh /path/to/files/ 100

The commands to run the script that looks for duplicates:
python3 duplicates_async.py /path/to/files/
or
python3 duplicates.py /path/to/files/
