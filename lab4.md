1. Create the /home/consultants directory: -> sudo mkdir /home/consultants
   ![image](https://github.com/user-attachments/assets/e15c76e1-a605-4775-9d10-eb6cbbe5daff)
2. Add write permission to the consultants group (symbolic method): -> sudo chmod g+w /home/consultants
   ![image](https://github.com/user-attachments/assets/9670f6a3-9744-41ff-9c17-fbfa5ed0283c)
3. Forbid others from accessing the /home/consultants directory (octal method): -> sudo chmod 750 /home/consultants
   ![image](https://github.com/user-attachments/assets/0a416e62-dd7d-418b-a414-2e1d620827e9)
   ![image](https://github.com/user-attachments/assets/2d34d12f-2c2b-4ebd-98eb-d35771aeec10)

4. Change the default umask for the operator1 user: -> (a)Open the user’s .bashrc or .profile file: sudo nano /home/ubuntu/.bashrc

(b)Add the following line to set the umask: umask 0074
   ![image](https://github.com/user-attachments/assets/9c7b460c-6818-4d1c-b2ae-415d9b457185)
   ![image](https://github.com/user-attachments/assets/7fdbbae5-80db-461b-ac60-1727d6a50582)
   ![image](https://github.com/user-attachments/assets/7d644448-2662-40d6-95b6-957142eefb35)
5. Confirm the umask: -> su - ubuntu umask
   ![image](https://github.com/user-attachments/assets/17345836-8482-4512-9623-cdee8e9161b2)
