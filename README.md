
# Baisc Bash Cheat Sheet

A cheat sheet for daily used bash commands.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## Command History

Check Last Command

```bash
!!
```

## Create Files

Create Single file

```bash
touch file.txt
```

Create Multiple files

```bash
touch file1.html file2.css
```

Create Same Category's Multiple files

```bash
touch {file1, file2}.txt
```

Create file3.txt, file4.txt, file5.txt 

```bash
touch file{3..5}.txt
```

Create filea.txt, fileb.txt, filec.txt 

```bash
touch file{a..c}.txt 
```

## Open File

Open a file

```bash
start fileName.txt
```

## Move Files

Copy file content from file1 to file2

```bash
cp file1.txt file2.txt
```

Move file content from file1 to file2 and Delete file1

```bash
mv file1.txt file2.txt
```

## Delete Files

Delete Single file

```bash
rm file1.txt
```

Delete All Files

```bash
rm *
```

Delete file forcefully

```bash
rm -f | --force foo.txt
```


## Create Directories

Make Directory

```bash
mkdir folderName
```

Make Multiple Directories

```bash
mkdir folder1 folder2
```


## Navigate Directories

Print Current Directory Path

```bash
pwd
```

List directories

```bash
ls
```

List directories including hidden

```bash
ls -a | --all
```

List directories in long form

```bash
ls -l
```

Change Directory

```bash
cd
```


## Move Directories

Copy directory

```bash
cp -R | --recursive folder1 folder2
```

Move directory

```bash
mv folder1 folder2 
```



## Delete Directories

Delete empty directory

```bash
rmdir folderName 
```

Delete directory including contents

```bash
rm -r | --recursive folderName  
```

Delete directory forcefully

```bash
rm -r | --recursive -f | --force folderName
```

## Exit Terminal

Exit Terminal by code

```bash
exit 0
```


## Authors


### Shuvo Sarker [@shuvoslashn](https://www.github.com/shuvoslashn)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shuvoslashn/)

