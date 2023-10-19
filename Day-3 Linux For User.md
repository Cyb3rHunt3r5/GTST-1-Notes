# kali linux
***What is command
“Small programs that do one task well”***

# ls / List Directory
 List  information  about  the FILEs (the current directory by default).
 
# cd / Change Directory
 It is used to change current working directory. 

# Pwd / print working directory
   It prints the path of the working directory, starting from the root.


# echo
  echo command in linux is used to display line of text/string that are passed as an argument 


● You can write texts into ﬁles.
**○ echo text > ﬁle.txt** 
**● You can add texts(append)** 
**○ echo text >> ﬁle.txt**


# cat / head / tail / less
 Used to show the content of a ﬁle


# touch
Creates any kind of Files with the name you gave it. With empty inside.



# Mkdir / make directory 
Creates Folder with the name u gave it.


# rm / remove
SYNOPSIS
-rm  [FILE1] [FILE2] [FILE3]
DESCRIPTION
-Remove ﬁle.

# cont…
● rm -r   => recursive(4 folders) 
● rm -i    => for prompt(ask) 
● rm -f    => force delete


# Cp| mv  / copy,move
SYNOPSIS
       cp [oldFILEplace] [newﬁlePlace]
       Mv  [oldFILEplace] [newﬁlePlace]
DESCRIPTION
       Copy/move  ﬁles & folders.


# grep - global search for regular expression
● grep -i “search” ﬁle     
○ - case insensitive 
● grep -c “search” ﬁle    
○ - count numbers 
● grep -l “search” *   
○ -  displays ﬁlename 
● grep -R “search” foldername 
○ - search text in folders 
● grep -v ‘term’ ﬁlename 
○ To display without this term 
● grep -n “term” ﬁle 
○ To display the term ﬁnd number 



# Wc - word count
   It is used to find out number of lines, word count, byte and characters count in the files specified in the file arguments.
**Line(-l)      word(-w)      byte(-c) 


# Piping ( | )
On pipe, will help you run commands by using the output of the 1st command as the input for the next one


