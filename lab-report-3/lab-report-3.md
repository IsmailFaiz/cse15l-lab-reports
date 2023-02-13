# Four ways to use the `less` command

In this lab report, I will be exploring the `less` command in bash. In addition to using the `man` command to access bash's reference manual, I have used the following two links: [[1]](https://www.geeksforgeeks.org/less-command-linux-examples/) and [[2]](https://www.thegeekstuff.com/2010/02/unix-less-command-10-tips-for-effective-navigation/).

## 1. `less *` and `:n`, `:p`

The first functionality we explore is the multiple file navigation. This could be useful when we wnat to have a look at more than one file in a directory without having to write a command for each of them. Following is a sample code snippet that helps achieve this:

```
less written_2/non-fiction/OUP/Abernathy/*
```

Now, `less` command allows us to enter `:n` to go to the next file and `:p` to go to the previous file. The first example shows the bash interface for the former while the second example shows the bash interface for the latter.

| ![Image](a1.jpg) | 
|:--:| 
| *First example*

| ![Image](a2.jpg) | 
|:--:| 
| *Second example*

## `less -p <pattern>`

| ![Image](b1.jpg) | 
|:--:| 
| *First example*

| ![Image](b2.jpg) | 
|:--:| 
| *Second example*
## 3. `less -N`

| ![Image](c1.jpg) | 
|:--:| 
| *First example*

| ![Image](c2.jpg) | 
|:--:| 
| *Second example*

## 4. `less -F`

| ![Image](d1.jpg) | 
|:--:| 
| *First example*

| ![Image](d2.jpg) | 
|:--:| 
| *Second example*
