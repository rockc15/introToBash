# Bash 

## Topics 
1. Learning the land
2. Use the Land 


## Learning the Land 
> This lesson is the first of many to becoming a pro at bossing your computer around. In this lesson you will learn how to move around a bash shell. Trust me we get it working in a shell is intimadating at first but it is really useful to know. 

**Terms to learn** <br/>

*Command*
    : A String the user inputs into the shell that runs a program

*Directory (dir)*
    : A file that contains refences to other files. You can pretty much call this a folder

*Current Working dir*
    : The dir that you are currently working in 

*Home Dir*
    : An enviorment variable ( We will talk about envorimenal var later) that represents a user base dir

*Root Dir*
    : A dir of the highest level 

**Commands learned in this lesson**

```
pwd - prints the working directory. Tells you where are you at in the shell 

whoami - tells you what user you are

ls - list the contents of the directory 

cd - change directory 

touch - creates a new file

mkdir - created a new dir
```

Steps <br>
1. Use `pwd` and note what dir you are in 
2. Use `whoami` to see what user you are 
3. lets find the home dir use `cd` to change to the home dir
4. Use `pwd` again to see if you are in the home dir
5. Use `ls` to see what is in that dir. 
6. NOTE: You should see a combination of dir and files if not don't worry we can take care of that shortly 
7. Use `mkdir bash` to created a new dir named bash
8. Now we want to change our current working dir to bash try `cd bash` Note you can replace `bash` with any dir if you want to go somewhere else 
9. User `pwd` again to see if you are in the bash dir 
10. Notice how there is a more dir attached to bash. Something like `/Users/casey/bash` this is known as you absolute path. `/User` is the parent dir of `/casey` which is the parent dir of `/bash`. 
11. lets go back to our parent dir. Try `cd ..` to change dir to the parent
12. Again use `pwd` (last time i promise) to verify you are back to the parent. 
13. Now that you know how to move around lets go back into the bash dir 
14. Lets try making a new file type `touch newFile` to make a file called newFile
15. Use `ls` to see if the new files was created

---



## Using the Land 
> Now that you can get around your shell we are going to teach you how to use some tools in your shell. In this lesson we what to create a text file and do some fun stuff with it 


**Commands learned in this lesson**

```
echo - 

rm - 

grep - 

cat - 

clear -
```
