# Linux-Labs

# LAB 1

####   cat: 
#####          
#####      
#####       
####   more:
#####      
#####       

### 3. What is the difference between rm and rmdir using man?
#### rm 
##### 
##### 
##### 
#####     
#####     
#### rmdir
##### 
#####
##### 
#####     

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


### 7. Modify islam's account so the password expires after 30 days


### 8. Lock bad user account so he can't log in

### 9. Delete bad user account

### 10. Delete the supplementary group called badgroup.

### 13. Create a folder called myteam in your home directory and change its permissions to
### read only for the owner.

### 14. Log out and log in by another user

### 15. Try to access (by cd command) the folder (myteam)

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










