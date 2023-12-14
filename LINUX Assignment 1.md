# LINUX Assignment 1

## 1. How to make a directory
### mkdir:-


# Terminal input
```
manish@manish:~/linux$ mkdir directory1
manish@manish:~/linux$ ls
directory1
```
# Screenshot
![](https://lh7-us.googleusercontent.com/OOwpqHFb5QppYBIS53Cd7E8jVlpPdrqtx4Mjiq2Fd2wzKyoiL9WaLHbZPZ3C1JF5DgHpyQzHODBX2IQSMbxJDH9rHXp9sbx8ZcyQqm66AUcaRKKsZAcmR8PAHZhbRwXP5YPTwX1F7H6h58r_2Rem1yk)



## 2. Remove a directory

# Terminal input
```
manish@manish:~/linux$ ls
directory1
manish@manish:~/linux$ rmdir directory1/
manish@manish:~/linux$ ls
manish@manish:~/linux$ 
```
# Screenshot





# Terminal input
# Screenshot



3. Make a copy of a file
To copy a file we use cp command.

cp a directory_2/
cp: This is the copy command in Unix/Linux.
a: This is the source file that you want to copy.
directory_2/: This is the destination directory where you want to copy the file.


Output:-





4. Move or rename a file
To move or rename a file we use mv command.
Case 1 use mv to move
mv a folder2/
mv: This is the move command in Unix/Linux, and it is also used to rename files or directories.
a.txt : This is the source file or directory that you want to move.
folder2/: This is the destination directory where you want to move or rename the file or directory.



Case 2 use mv to move file
mv a.txt b.txt
mv: This is the move command in Unix/Linux, and it is also used to rename files or move them to a different location.
a.txt: This is the source file that you want to move or rename.
b.txt: This is the destination file or the new name for the file.





4. Create an empty file







5. Remove multiple files with a single command
manish@manish:~/linux$ touch a b c d e f g
manish@manish:~/linux$ ls
a  b  c  d  e  f  filea.txt  folder2  g
manish@manish:~/linux$ rm a b c d e f g
manish@manish:~/linux$ ls
filea.txt  folder2





6. Remove content from the folder without removing folder
manish@manish:~/linux$ cd folder2/
manish@manish:~/linux/folder2$ ls
manish@manish:~/linux/folder2$ mkdir folder1 folder2 folder3 
manish@manish:~/linux/folder2$ touch file1 file2 file3 file4
manish@manish:~/linux/folder2$ ls
file1  file2  file3  file4  folder1  folder2  folder3
manish@manish:~/linux/folder2$ cd ..
manish@manish:~/linux$ rm -rf folder2/*
manish@manish:~/linux$ ls folder2/





7. Create multiple folder(a-z) with a single command


manish@manish:~/linux$ mkdir abc
manish@manish:~/linux$ cd abc
manish@manish:~/linux/abc$ ls
manish@manish:~/linux/abc$ mkdir {a..z}
manish@manish:~/linux/abc$ ls
a  b  c  d  e  f  g  h  i  j  k  l  m  n  o  p  q  r  s  t  u  v  w  x  y  z
manish@manish:~/linux/abc$ 































	




