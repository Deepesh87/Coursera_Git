Other tools used to find difference between 2 files are-

1) wdiff-- words that have changed 
2) Some other tools 

vmdiff file1.txt file2.txt  - works if you have UNIX VIM editor
meld, kDiff3

To apply changes from a patch file to a python file use
patch file.py < diff_file.diff 

This will redirect the output of diff file into the py file
