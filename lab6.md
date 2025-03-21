1. Create the operator1 user: -> sudo useradd -m operator1
   ![image](https://github.com/user-attachments/assets/ae77bb49-063d-41bc-9628-586e79671cf5)
2. Confirm that operator1 exists: -> cat /etc/passwd | grep operator1
   ![image](https://github.com/user-attachments/assets/f96588c9-970c-4480-967f-bd596c847e25)
3. Set the password for operator1: -> sudo passwd operator1
   ![image](https://github.com/user-attachments/assets/3a419ec4-e5d9-41d8-89c2-a6bf8f57a81a)
4. Create operator2 and operator3 users: -> sudo useradd -m operator2 sudo passwd operator2 sudo useradd -m operator3 sudo passwd operator3
   ![image](https://github.com/user-attachments/assets/757b82eb-47dd-43c1-a938-18c1c6f558db)
5. Update the comment for operator1 using usermod -c: -> sudo usermod -c "System Operator 1" operator1
   ![image](https://github.com/user-attachments/assets/250f8978-1ebd-45b4-bf67-0443367664ec)
6. Remove the operator3 user: -> (a)To delete operator3 without removing the home directory: sudo userdel operator3
   ![image](https://github.com/user-attachments/assets/f71927b8-56bb-4210-9035-cc38ec1ee087)
   (b)To delete operator3 and its home directory: sudo userdel -r operator3
   ![image](https://github.com/user-attachments/assets/3957ca21-4183-48c7-8428-3e3de2c1b32d)

