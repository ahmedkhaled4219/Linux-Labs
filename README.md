# Linux-Labs

# LAB 1

####   cat:         
           cat command displays the entire output once at the terminal 
       
####   more:
      more command displays the output until the end of terminal screen allowing you 
      to scroll down or viewing more by pressing enter 

### 3. What is the difference between rm and rmdir using man?
#### rm 
       rm command is used to delete a file and if we added
       -r w can delete a non empty directory
#### rmdir
         rmdir is used to delete a empty directory  

### 4. Create the following hierarchy under your home directory:
![4](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/0a613881-eefc-4faa-89b2-7ab7def261a6)


#### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?

![4a](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/694b1c70-4744-4612-9da5-42c288c8063c)

#### b. Then remove dir12 using rmdir –p command. State what happened to the

![4b](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/bf7404e6-f7b3-4cdb-a8a5-473dc7ffef9a)

#### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv

![4c](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/270a564b-750e-4118-91b1-4a9394cbb16f)

### 5. Copy the /etc/passwd file to your home directory making its name is mypasswd.

![5](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/4afb59f2-6d9f-4677-b542-d097f9170cdd)

### 6. Rename this new file to be oldpasswd.

![6](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/a2d2050e-c6ea-4859-a208-496602102463)

### 7. You are in /usr/bin, list four ways to go to your home directory

![7](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/c89c7cd6-e632-46d0-a3e6-36e2318ab938)

### 8. List Linux commands in /usr/bin that start with letter w

![8](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/943d9d8b-f849-491e-b247-b49edd438e1f)

### 9. Display the first 4 lines of /etc/passwd

![9,10](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/5252830c-b0df-469a-b752-4a82614dfd3d)

### 10.Display the last 7 lines of /etc/passwd

![9,10](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/79cdc42b-0ff6-4508-9dec-676c8bf69376)

### 11.Display the man pages of passwd the command and the file sequentially in one command.

![11](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/48641be0-aec6-4ce1-8381-1e48ac5b0427)

### 12.Display the man page of the passwd file.

![12](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/560f1db7-6fb9-4747-960a-82f26ef57e1a)


### 13.Display a list of all the commands that contain the keyword passwd in their man page.

![13](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/577d44b4-66ac-4fe0-aa21-a1dcab5819c1)

## ...........................................................................................................

# LAB 2

 ### 1. Create a user account with the following attribute
 ### username: islam
 ### Fullname/comment: Islam Askar
 ### Password: islam
![1](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/a084ec48-aa1a-47ef-b5bc-6606ee668f52)

 
### 2. Create a user account with the following attribute
 ### Username: baduser
 ### Full name/comment: Bad User
 ### Password: baduser
![2](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/e8dd30cd-a8a4-4898-9bac-fefe01e2c59a)


### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![3,4](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/7e3e498d-ef63-4ce2-bba2-b7a3ac9eb834)


### 4. Create a supplementary group called badgroup
![3,4](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/b0f8e6e0-7cb8-4fc2-9eca-1fbb14133704)

### 5. Add islam user to the pgroup group as a supplementary group
![5](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/311a5e47-c8b8-41c4-8e81-21c665bafdf8)


### 6. Modify the password of islam's account to password

![6](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/a48472e5-75a3-4763-8362-ae6bca2ee2a2)

### 7. Modify islam's account so the password expires after 30 days

![7](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/7bef7c17-0946-403a-95cf-ae1f139c152b)

### 8. Lock bad user account so he can't log in

![8](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/2fcce678-376c-4fc1-b718-d434afbfbb0c)
### 9. Delete bad user account

![9](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/aa3cf68f-d542-455d-9c71-a8294e7cc496)

### 10. Delete the supplementary group called badgroup.

![10](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/0a9babdb-02ea-489d-aa43-1dcb45c8c3cd)

### 13. Create a folder called myteam in your home directory and change its permissions to
### read only for the owner.

![13](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/7a68c7c4-a7fd-48f3-a5b3-89d65d03e08e)

### 14. Log out and log in by another user

![14](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/c6d938d3-6f32-49ec-9a43-8710879b1aad)

### 15. Try to access (by cd command) the folder (myteam)

![15](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/2b050545-cb7e-4126-848e-58b2070c3794)

### 16. Using the command Line
### Change the permissions of oldpasswd file to give owner read and write
### permissions and for group write and execute and execute only for the others
### (using chmod in 2 different ways)

![16](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/c802825c-65e1-4141-ba51-86149c3390b1)

### Change your default permissions to be as above.

![16 1](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/29cf69a7-a70c-49f9-9671-9d49c0e5b49e)

### What is the maximum permission a file can have, by default when it is just
### created? And what is that for directory.
     Max permission for file is : 666 

    Max permission for directory : 777


### Change your default permissions to be no permission to everyone then create a
### directory and a file to verify.

![16 2](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/bfef38b9-26fd-4289-89b7-c16acd20db14)

![16 3](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/fd7bd414-b185-4fed-9d15-fcaab10c8ec2)

### 17. What are the minimum permission needed for:
### Copy a directory (permission for source directory and permissions for target
### parent directory)

    The minimum permission needed for source directory is : r
    The minimum permisssion needed for target directory is : wx

### Copy a file (permission for source file and and permission for target parent
### directory)

    The minimum permission needed for source file is : r
    The minimum permisssion needed for target directory is : wx

### Delete a file

    for the soucre directory : wx
    for the file : NO need for permissions

### Change to a directory
    for the directory : x

### List a directory content (ls command)
    r

    rx for ls-l
### View a file content (more/cat command)
    for the file : r

### Modify a file content 
    w for non interactive tool
    rw for interactive tool (vi)

### 18. Create a file with permission 444. Try to edit in it and to remove it? Note what
### happened.


### 19. What is the difference between the “x” permission for a file and for a
### directory?

    x permission for file is to run the file
    x permission for a directory is to cd 

## ................................................................................................

# LAB 3

### 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,
### college, experience,...
![1 1](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/c7e8d224-6c65-467f-a089-ee339096c702)

![1](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/efff0eed-f986-4902-b4ac-90377f967706)

### 2. Open mycv file using vi command then: Without using arrows state how to:
## a. Move the cursor down one line at time.
    By pressing j in the keyboard

## b. Move the cursor up one line at time.
    By pressing k in the keyboard

 ## c. Search for word age
    Enter in the command line mode -> :/Age
 ![2 c](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/83568300-bdd3-4197-8bf6-1615b48c38b9)

### d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
    press 5G in the keyboard 
    OR Enter in the command line mode -> :5
  
### e. Delete the line you are on and line 5.
    Enter in the command line mode -> :1d

    Enter in the command line mode -> 5d

### f. How to step to the end of line and change to writing mode in one-step.
    By pressing A in the keyboard

### 3. List the available shells in your system.

![3](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/63f96c7c-defb-4e8c-8b54-f4ec45f0d593)

### 4. List the environment variables in your current shell.

![4](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/ff903231-96b4-4172-a081-fbe7709d2191)


### 5. List all of the environment variables for the bash shell.

    man bash

### 6. What are the commands that list the value of a specific variable?

    echo and printenv

![6](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/a37483a1-e0f6-4a97-b54c-a02797f7f2e7)


### 7. Display your current shell name.

![7](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/c4446efa-611c-4b15-b897-54077d15417c)

### 8. State the initialization files of: sh, ksh, bash.

### 9. Edit in your profile to display date at login and change your prompt permanently.
    To display date at login permanently I wrote this command PS1="u\@\t" in ~/bash_profile

    To change my prompt permanently I wrote this command PS1="\u@\t\W>>" in ~/bashrc

### 10.Execute the following command :
 ### echo \ then press enter
### What is the purpose of \ ?
### Notice the prompt ”>” what is that? and how can you change it from “>” to “:”.

    The prupose of \ is to open second prompt and take input 
    and > is the indicator of  PS2 and this how i changed it 

![10](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/3b497d13-f46b-44df-9a81-2d1fc5bb6bda)

### 11.Create a Bash shell alias named ls for the “ls –l” command

![11](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/18311d58-2bef-4879-8fa6-a517a11d577c)

## .....................................................................................................

# LAB4

### 1.List the user commands and redirect the output to /tmp/commands.list
![1](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/df88c557-1389-4643-988a-0ed66213b6f6)


### 2.Count the number of user commands
![2](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/622d799b-f063-4a57-9d19-2b775e442f51)


### 3.Get all the users names whose first character in their login is ‘g’.
![3](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/6e2a9d11-b55b-45bb-8c4c-95947d462381)


### 4.Get the logins name and full names (comment) of logins starts with “g”.


![4](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/8b92de41-2d9b-4a4f-8bfd-bb3581fef3a3)

### 5.Save the output of the last command sorted by their full names in a file.

![5 1](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/eb3f9a4f-3f6a-47ff-b25c-ffff1559b3cb)

 ![5](https://github.com/ahmedkhaled4219/Linux-Labs/assets/146847357/6c0884be-9a71-4304-b92a-fe4a811170c8)

### 6.Write two commands: first: to search for all files on the system that named .bash_profile. Second: sorts the output of ls command on / recursively, Saving their output and error in 2 different files and sending them to the background.

 ![Uploading 6.png…]()

### 7. Display the number of users who is logged now to the system.



#### 8. Display lines 7 to line 10 of /etc/passwd file
![UNFOUND]()

#### 9. What happens if you execute:cat filename1 | cat filename2/ls | rm/ ls /etc/passwd | wc –l
![UNFOUND]()

#### 10. Issue the command sleep 100.
![UNFOUND]()

#### 11. Stop the last command.
![UNFOUND]()

#### 12. Resume the last command in the background
![UNFOUND]()

#### 13. Issue the jobs command and see its output.
![UNFOUND]()

#### 14. Send the sleep command to the foreground and send it again to the background.
![UNFOUND]()

#### 15. Kill the sleep command.
![UNFOUND]()

#### 16. Display your processes only
![UNFOUND]()

#### 17. Display all processes except yours
![UNFOUND]()

#### 18. Use the pgrep command to list your processes only
![UNFOUND]()

#### 19. Kill your processes only.
![UNFOUND]()


### lab5
#### 1. Compress a file by compress, gzip, zip commands and decompress it again. State the differences between compress and gzip commands.
![UNFOUND]()

#### 2. What is the command used to view the content of a compressed file.
![UNFOUND]()

#### 3. Backup /etc directory using tar utility.
![UNFOUND]()

#### 4. Starting from your home directory, find all files that were modified in the last two day.
![UNFOUND]()

#### 5. Starting from /etc, find files owned by root user.
![UNFOUND]()

#### 6. Find all directories in your home directory.
![UNFOUND]()

#### 7. Write a command to search for all files on the system that, its name is “.profile”.
![UNFOUND]()

#### 8. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
![UNFOUND]()

#### 9. List the inode numbers of /, /etc, /etc/hosts.
![UNFOUND]()

#### 10. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the
file you copied, and then use these commands again, and check the output.
![UNFOUND]()

#### 11. Create a symbolic link of /etc/passwd in /boot.
![UNFOUND]() 

#### 12. Create a hard link of /etc/passwd in /boot. Could you? Why
##### 
![UNFOUND]()






