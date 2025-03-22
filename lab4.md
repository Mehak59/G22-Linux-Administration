Lab Number: {7-8}  
Create the /home/consultants directory. Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions. Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. Change the default umask for the operator1 user. The new umask prohibits all access for users that are not in their group. Confirm that the umask is changed.    
Solution:  
1. Create the directory using mkdir command.  
   mkdir: Creates a new directory.

   ![image](https://github.com/user-attachments/assets/1e90c5d0-96c2-4bbe-a3e0-141848c8f5ba)

   chmod: chmod stands for "change mode". It is used to control the access levels of a file or directory, determining who can read, write and execute.  
2. Now add write permission to group using symbolic method of chmod and forbid access for others.
     
   ![image](https://github.com/user-attachments/assets/ff934cf8-5f14-4a39-8660-d84e8fc406f4)
   
3. Change the default umask of operator1 user.

   ![image](https://github.com/user-attachments/assets/4a224b12-3021-4f5b-a314-377432219d5c)
   ![image](https://github.com/user-attachments/assets/0c7e9e77-3ef7-4cea-be85-4da722d9f3a2)

