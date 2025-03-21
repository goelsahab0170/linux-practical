1. ps Command -> (a)Display all running processes: ps aux
   ![Screenshot 2025-03-21 104545](https://github.com/user-attachments/assets/27945489-0728-4569-865d-6453e15860eb)
   
   (b)Show processes for the current terminal session: ps

    ![Screenshot 2025-03-21 104856](https://github.com/user-attachments/assets/ef112b42-9ef7-40f2-b9e7-080353f9a12a)

   (c)Display a process tree: ps -e --forest
   ![Screenshot 2025-03-21 104956](https://github.com/user-attachments/assets/6c8d81e9-4066-4f78-86ca-1b6b62c6fcd8)

   (d)Filter by process name: ps -C firefox

   ![Screenshot 2025-03-21 105050](https://github.com/user-attachments/assets/9a2e0452-4b76-4315-8aa2-bccb68129de6)

   (e)Show detailed information of a specific process: ps -p 1234 -o pid,ppid,cmd,%mem,%cpu
   ![Screenshot 2025-03-21 105248](https://github.com/user-attachments/assets/5ba535c3-8107-4888-8bc3-f0e7a8d34a85)
   
3. kill Command -> (a)Find the PID: ps aux | grep firefox
   ![Screenshot 2025-03-21 105407](https://github.com/user-attachments/assets/dc06adee-0548-461c-a65d-49ae1a5b2285)

   (b)Kill a process by PID: kill 1234

   (c)Force kill a process: kill -9 1234
   
   (d)Kill by process name: killall firefox

5. top Command -> top Sort by memory usage: Press M Sort by CPU usage: Press P Kill a process: Press k → Enter the PID Exit top: Press q
   ![Screenshot 2025-03-21 105624](https://github.com/user-attachments/assets/be55476e-8146-4012-9d9c-d71318c94c8b)

6. apt-get Command -> (a)Update package list: sudo apt-get update
   ![image](https://github.com/user-attachments/assets/e5454d12-3d99-424e-808f-6f37018afb4d)

   (b)Upgrade installed packages: sudo apt-get upgrade
   ![image](https://github.com/user-attachments/assets/db9dfeda-79fa-4e06-93f9-70b32a19e495)

   (c)Install a package: sudo apt-get install vim
   ![image](https://github.com/user-attachments/assets/0a9dfbda-5f9c-4808-9561-b646b05eab4b)

   (d)Remove a package: sudo apt-get remove vim
   ![image](https://github.com/user-attachments/assets/b265b61d-a9c8-4805-996a-21157808d74e)

   (e)Remove package along with configuration files: sudo apt-get purge vim
   ![image](https://github.com/user-attachments/assets/a05a8d0d-1380-43a9-a1cc-b355c3370fbf)

   (f)Clean up unused packages: sudo apt-get autoremove
   ![image](https://github.com/user-attachments/assets/5d3447f2-f0d9-48c4-870a-8d77b58332f6)

   (g)Clean package cache: sudo apt-get clean
   ![image](https://github.com/user-attachments/assets/64a7edb8-07ec-4bcd-9f12-d096bdf8367f)

