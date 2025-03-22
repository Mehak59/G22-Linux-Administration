Lab Number : {10-11}  
Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.  
Solution:  
1. Create operator1 user using useradd command.

   
   ![image](https://github.com/user-attachments/assets/273420c7-5045-4e4c-b05d-19be64f20d3a)

2. Verify if operator1 exists.
   
   ![image](https://github.com/user-attachments/assets/0738b8f3-4df2-4761-a9d0-50e64ed91617)

3. Set password for operator1 using passwd command.

   ![image](https://github.com/user-attachments/assets/fe031225-114d-4263-877e-2c2635904416)

4. Create operator2 and operator3 user while also setting their password.

   ![image](https://github.com/user-attachments/assets/60fc8dfa-b971-4f76-947a-515452231538)
   ![image](https://github.com/user-attachments/assets/4837b0ca-6a81-4e21-befe-8a2e719e624f)

5. Add comments to operator1 user using usermod -c command.

   ![image](https://github.com/user-attachments/assets/a2e2ad93-dbf2-4339-a932-b738e065df45)

6. Use userdel command to delete operator3 user.

   ![image](https://github.com/user-attachments/assets/512b60c0-9b41-483e-8e9f-4c5ee44e73b9)





