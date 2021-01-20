# Terminal-01

## Objective

Using terminal, navigate through the file system

## Tech Requirements

* Terminal

## Activity 1

Complete the following steps in order. Write down all your answers to each question.

### Step 1
Enter the command `cd blah`

* What happens?

### Step 2
Enter the command `cd ..`

Mind the space between "cd" and ".."! Use the pwd command.

* What happens?

Check using the `pwd` command.

### Step 3
List the directory contents with the `ls` command.

* What do you see?

* What do you think these are?

### Step 4
Enter the cd command.

* What happens?

Check using the `pwd` command.

### Step 5
Repeat step 2 two times.

* What happens?

### Step 6
Display the content of this directory.

### Step 7
Try the command cd ~

-> What happens?

-> Do you know another possibility to get where you are now?

### Step 8
Repeat step 4.

-> Do you know another possibility to get where you are now?

## Activity 2


Complete the following steps in order. Write down all your answers to each question.

### Step 1
Change directory to '/' (root directory) and then to the 'etc' directory. 

Type `ls`

### Step 2

Type `man file`

* What does this do?

* What does the 'file' command do?

### Step 3

Type `ls`

### Step 4
The file 'passwd' contains the answer to the next question. Try the file command on it.

* What is the file type of 'passwd'

### Step 5
Use the command cat 'passwd' and read the file.

* What is the contents of 'passwd'

### Step 6
Return to your home directory using the cd command.

Enter the command `file .`

* Does this help to find the meaning of "."?

* Can you look at "." using the cat command?

### Step 6
Display the manual for the cat program. Use the option for numbering of output lines to count how many users are listed in the file '/etc/passwd'.

* How many users are listed in `passwd`

## Activity 3

Complete the following steps in order. Write down all your answers to each question.

### Step 1
Using your terminal, navigate to your Home directory using `cd ~`.

### Step 2
Use `ls` to view the contents of your Home directory.

### Step 3
Use cd to move into your Desktop directory.

### Step 4
In the terminal, use `mkdir` to create a folder on the Desktop called 'my_first_directory'. 

Look on your Desktop. Do you see it?

### Step 5
Use `cd my_first_directory/` to move inside that directory.

Use `pwd` to check your location.

There, make a file called 'my_first_file.txt' with `touch my_first_file.txt`.

### Step 6
Open the file with `open my_first_file.txt` and write yourself a message!

Save and close the text file

### Step 7
Back in the terminal, list the contents of your current directory from the terminal with `ls`.

### Step 8
Use the `cat` and `file` command with 'my_first_file.txt'.

What happens?

### Step 9
Make a copy of your 'my_first_file.txt' from it's current spot to directly on the Desktop with `cp my_first_file.txt ../my_first_copy.txt`.

### Step 10
Move back out to your Desktop directory from the terminal with `cd ..`.

You can verify you are in the Desktop directory with `pwd`

### Step 11
Use `ls` in the terminal to verify your 'my_first_copy.txt' on your Desktop. Open it up. 

Is it the same as your first file?

### Step 12
Move your copied file into your 'my_first_directory' with `mv my_first_copy.txt my_first_directory/`.

Use `ls` to see that the copied file is no longer on your Desktop.

### Step 13
Type `cd my_first_directory/`, followed by `ls` to confirm that your copy has been moved into 'my_first_directory'.

### Step 14
`cd ..` to get back out to your Desktop.

Type `rm my_first_directory/` to attempt to remove the folder

What happened?

### Step 15
Type `rm -r my_first_directory/` and do a visual check, as well as `ls` on your terminal, to verify that the directory has been removed.
