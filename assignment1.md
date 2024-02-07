Exercise 1:
We Use the following command to find home directory
$echo $HOME
Output:
/c/Users/krish

To list files/folders in the home directory, we use:
$ls~
Output:
AppData/
 Apple/
'Application Data'@
 Contacts/
 Cookies@
 DATA-645_0101_Landa.ipynb
 Desktop/
 Documents/
 Downloads/
 Favorites/
'My Documents'@

Explanation:
To find my home directory, I can use the command echo $HOME. This command will display the path to my home directory, which is where my personal files are stored on the computer. Once I have the path, I can list the files and folders in my home directory using the command ls ~. This command will show me all the items located in my home directory, including directories as well as the files.

Exercise 2:
$cd ~/../../..
Solution:
The command cd ~/../../.. takes up three directories from the current location.
$cd Desktop/git/files

Explanation:
Navigating directories can be done using the cd command. For example, cd ~/../../.. takes me three directories up from my current location. This is achieved by using ../ to move up one directory level at a time, with ~ representing my home directory. Once I've moved up, I can then navigate to a specific directory like Desktop/git/files using the cd command again.


Exercise 3:
Solution:
We Use the man command or help command to read the manual page of ls:
$man ls (or) $help --ls
The -a flag shows all files, including hidden files.
The -l flag lists files in long format, providing detailed information.

Explanation:
To learn more about the ls command and its options, I can use the man or help command. For instance, man ls or help --ls will provide me with detailed information about how to use the ls command effectively. The -a flag displays all files, including hidden ones, while the -l flag shows files in a long format, giving me additional details such as permissions, size, and timestamps.

Exercise 4:
Create a new file named myfile.txt using the touch command:
$ touch myfile.txt

Use the stat command to view information about the file:
$ stat myfile.txt
  File: myfile.txt
  Size: 27              Blocks: 1          IO Block: 65536  regular file
Device: 46c8e9dch/1187572188d   Inode: 34621422135491339  Links: 1
Access: (0644/-rw-r--r--)  Uid: (197609/   krish)   Gid: (197609/ UNKNOWN)
Access: 2024-02-06 19:06:18.360387100 -0500
Modify: 2024-02-06 18:37:20.768824700 -0500
Change: 2024-02-06 18:37:20.768675500 -0500
 Birth: 2024-02-06 18:35:20.036157800 -0500


Explanation:
Creating a new file can be done with the touch command. For example, touch myfile.txt will create a new file named myfile.txt in my current directory. I can then use the stat command to view detailed information about the file, such as its size, permissions, and timestamps.


Exercise 5:
$ ls
Output:
myfile.txt
$ ls -l
Output:
$ ls -l
-rw-r--r-- 1 krish 197609 27 Feb  6 18:37 myfile.txt

Explanation:
Running ls will give me a basic list of files and directories in the current directory, while ls -l will provide more detailed information. For example, ls -l will show me details like permissions, size, and timestamps of each file. This helps me understand more about the files in the directory and when they were last modified or created.


Exercise6:
$ echo "This line is my first line" >> myfile.txt

$ cat myfile.txt
This line is my first line

Explanation:
To add content to a file, I can use the echo command followed by >> to append text to the file. For instance, echo "This line is my first line" >> myfile.txt adds a line to the file myfile.txt. I can then use the cat command to display the contents of the file, showing the line I added.

Exercise 7:
$ touch myfile.txt
$ ls -l myfile.txt

Output:
-rw-r--r-- 1 krish 197609 27 Feb  6 19:07 myfile.txt

Explanation:
Updating file timestamps can be done with the touch command. For example, touch myfile.txt updates the timestamp of the file myfile.txt to the current time. I can then use ls -l myfile.txt to view detailed information about the file, including its updated timestamp, confirming that the timestamp has been successfully updated.