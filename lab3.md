```
grep -i "we" stringsearch-data/technical/911report/chapter-1.txt
```
```
grep -i "inside" stringsearch-data/technical/911report/chapter-1.txt
```

This command looks for the string but ignores any of the casing. This is useful if you are not sure whether a word is uppercase or lowercase.

```
grep -r "2001" technical/
```
```
grep -r "American" technical/
```

This command looks for the strings in all the files and subdirectories. This is useful to look for things in multiple files and directories at once.

```
grep -v "The" stringsearch-data/technical/911report/chapter-1.txt
```
```
grep -v "All" stringsearch-data/technical/911report/chapter-1.txt
'''
This command looks for all the lines in the file that do not contain the string. This is useful in order to filter out lines.

'''
grep -w "Washington" stringsearch-data/technical/911report/chapter-1.txt
```
```
grep -w "Shehhi" stringsearch-data/technical/911report/chapter-1.txt
```
This command looks for the whole word that is given. This is useufl to filter out false positives and only get what you want.


This was all found by using ChatGPT. I typed in the command grep and asked it for four options of how to use it and what the outputs would be.
