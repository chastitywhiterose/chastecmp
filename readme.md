# Chastity's Hex Compare Tool

Welcome to Chastity's Hex Compare program also known as "chastecmp".

Enter two filenames as command line arguments such as:

`./chastecmp file1.txt file2.txt`

It works for any binary files too, not just text. In fact for text comparison you want entirely different tools.

This tool can be used to find the tiny differences between files in hexadecimal. It shows only those bytes which are different. I wrote it as a solution to a reddit user who asked how to compare two files in hexadecimal.

It is an improvement over the Linux "cmp" tool which displays the offsets in decimal and the bytes in octal. Aside from using two different bases in the data, it falls short of usefulness because there are more hex editors than octal editors.

Here are also some graphical tools I can recommend if you are looking for a GUI instead of my command line program.

vbindiff  
wxHexeditor

