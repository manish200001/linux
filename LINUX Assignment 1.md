# LINUX Assignment 1

# 1. How to make a directory
## mkdir:- 
The mkdir command is used to create directories (folders). The name "mkdir" stands for "make directory." It allows users to create one or more directories with the specified names.

```
mkdir directory1
```
**mkdir:** It's a command used to create a new directory.

**directory1:** It specifies the name of the directory you want to create. In this case, it's "directory1."


### Terminal input and output
```
manish@manish:~/linux$ mkdir directory1
manish@manish:~/linux$ ls
directory1
```
### Screenshot
![](https://lh7-us.googleusercontent.com/OOwpqHFb5QppYBIS53Cd7E8jVlpPdrqtx4Mjiq2Fd2wzKyoiL9WaLHbZPZ3C1JF5DgHpyQzHODBX2IQSMbxJDH9rHXp9sbx8ZcyQqm66AUcaRKKsZAcmR8PAHZhbRwXP5YPTwX1F7H6h58r_2Rem1yk)


## 2. Remove a directory
### rmdir:-
The rmdir command is used to remove empty directories (folders). The name "rmdir" stands for "remove directory." 


# Terminal input
```
manish@manish:~/linux$ ls
directory1
manish@manish:~/linux$ rmdir directory1/
manish@manish:~/linux$ ls
manish@manish:~/linux$ 
```
# Screenshot

![](https://lh7-us.googleusercontent.com/pH6nNe1WJ28Cikql_ENU7e3U4cfKOcAnpRBep0xX0TiUBK5TzyQpdeTqCvxExlQM7_P8dP68uk8RYTwMtuLeUZfdVZiA0Q__WOlCIhQwh8NjLRCc0-1-2URl-EL5Wew0Tqq-ZKj-moOu6iEW4ybHtZs)




3. Make a copy of a file
### cp:-

# Terminal input
```
manish@manish:~/linux$ touch file1
manish@manish:~/linux$ ls
file1
manish@manish:~/linux$ mkdir directory2
manish@manish:~/linux$ ls
directory2  file1
manish@manish:~/linux$ cp file1 directory2/
manish@manish:~/linux$ ls directory2/
file1
```
# Screenshot

![](https://lh7-us.googleusercontent.com/n5Rj2yTAN3ND3-NLIhNEkd2qhTBjsdNKXZhpU8EbakYoUwilnR7UDOAmOI4lYoz5BFOxvJ6TystcnpRKYnApmCRpH0jMEyzOw7u_At6BL-X2Hghd5p1i8kkJSlq6inZrbBRzggoZVuPmG9Ti8-8hbg0)





4. Move or rename a file
## mv:-

### Terminal input
```
manish@manish:~/linux$ ls
directory2  file1
manish@manish:~/linux$ mv file1 file2
manish@manish:~/linux$ ls
directory2  file2
```
### Screenshot
![](https://lh7-us.googleusercontent.com/a3-ShZSu744iPwS0UDTk8Za8yq_wEkTGFeSiWtlO67LoGtiVDVMiiwc8D0DRwmTeZeaRpIId5CX-NwDS88IJHXWtV7Hs4g8-cSsIhMtUh55k_yr-jKqGKE2S_Glw9aW7f610Lsr0VTbclG3fLxN5UFM)


# Terminal input
```
manish@manish:~/linux$ ls
directory2  file2
manish@manish:~/linux$ ls directory2/
file1
manish@manish:~/linux$ mv file2 directory2/
manish@manish:~/linux$ ls directory2/
file1  file2
```
# Screenshot
![](https://lh7-us.googleusercontent.com/3pHwZT-wV163zJOuxcUe_6lSrgpZjks0K3RdKteqivQjFhMpFr8yRla0w839OF5mFsR7S3xlC8YyTQjMNkk2y0DLVjfcvyII6o25grgXM8asSv7aOsVfFJxgi97lASZO9_lHlcdV8LmSbZr6wZoEf2I)

5. Create an empty file
## touch:-

### Terminal input
```
manish@manish:~/linux$ touch filea.txt
manish@manish:~/linux$ cat filea.txt 
```
![](https://lh7-us.googleusercontent.com/OB6cxU46TscbKxk4cAyF0P-lr4C5lIdlfqTh4NAngvh5A8NtuemRvwsEhmvWSzig-Rh_NOYk7Uo0MLy6nXhRADhlF0gRxKHxiAfNKKVt_U-3iAYnIXJiSJ86iCL_I5WMYu41d6RcfG_2c425flgeGC0)

6. Remove multiple files with a single command
### rm:-

# Terminal input

```
manish@manish:~/linux$ touch a b c d e f g
manish@manish:~/linux$ ls
a  b  c  d  e  f  filea.txt  folder2  g
manish@manish:~/linux$ rm a b c d e f g
manish@manish:~/linux$ ls
filea.txt  folder2
```

![](https://lh7-us.googleusercontent.com/nQr0OkS1xAeB9TJvWfYWEvoRwmmZZjYmCCQBE2TGscMaZdz4hM2jfZyOJhmiOx0ZQTD44vC8nvvWuzbs5CgqT02sp9k2iu0fm_-2zYvVzrtzriNUG2B7hPWMqvxwqcWziPItfOgjYpVmLi3WyQbrbkc)





7. Remove content from the folder without removing folder
### rm :-

# Terminal input
```
manish@manish:~/linux$ cd folder2/
manish@manish:~/linux/folder2$ ls
manish@manish:~/linux/folder2$ mkdir folder1 folder2 folder3 
manish@manish:~/linux/folder2$ touch file1 file2 file3 file4
manish@manish:~/linux/folder2$ ls
file1  file2  file3  file4  folder1  folder2  folder3
manish@manish:~/linux/folder2$ cd ..
manish@manish:~/linux$ rm -rf folder2/*
manish@manish:~/linux$ ls folder2/
```


![](https://lh7-us.googleusercontent.com/puZEGU5bO8Wi7D_nLRUuu5XChsBPVVlTvj36xdUBCJ9esrRQzq5gsu8SDsEkkdJIJ5ZEnoDjMa63_pNUzraLXYO3cVbxf5Ih50bd_d2XHdxZH2JSphswcoTqzDLdK97zPbqfP4Dd8bg0UTfxHxgxJYE)

8. Create multiple folder(a-z) with a single command
### touch:-

# Terminal input

```
manish@manish:~/linux$ mkdir abc
manish@manish:~/linux$ cd abc
manish@manish:~/linux/abc$ ls
manish@manish:~/linux/abc$ mkdir {a..z}
manish@manish:~/linux/abc$ ls
a  b  c  d  e  f  g  h  i  j  k  l  m  n  o  p  q  r  s  t  u  v  w  x  y  z
manish@manish:~/linux/abc$ 
```

![](https://lh7-us.googleusercontent.com/vKH9hSET_7_h8ZVwkBSCLXQAnoPfqJlVIuB5J5UQSAv71v18XZvA_tDrh1hS9G7rNvLS383fBdil1pmmueUYDRQGrnQl38-iF6FuJ_N8nwl97t0yofrja0v6yBSfQji5DHtfreuluMuoTRb5aRXVVVs)































	




