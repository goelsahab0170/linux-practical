1. chown Command -> (a)Change the owner of a file: sudo chown user1 file.txt
   ![image](https://github.com/user-attachments/assets/744fc99e-070f-4273-b605-e741d36d9ab8)

   (b)Change the owner and group of a file: sudo chown user1:usergroup file.txt
   ![image](https://github.com/user-attachments/assets/3e7b8edd-9764-4275-92e7-944b47e81a2b)

   (c)Change only the group: sudo chown :usergroup file.txt
   ![image](https://github.com/user-attachments/assets/e84680bb-e180-4307-9d6f-aa5c3af03bc1)

   (d)Change ownership recursively (for directories): sudo chown -R user1:usergroup /path/to/directory
   ![image](https://github.com/user-attachments/assets/fed70d7f-1d3a-4ba6-a3ba-a86131329af1)

   (e)Transfer ownership to root: sudo chown root file.txt
   ![image](https://github.com/user-attachments/assets/cb75e2d0-4bd9-4895-8622-52743ab3eec6)

   (f)Use --from to change from a specific owner: sudo chown --from=current_owner new_owner file.txt
   ![image](https://github.com/user-attachments/assets/aeab59ec-5c8d-4016-9921-1f4080720721)

3. chmod Command -> (a)Give execute permission to the user: chmod u+x file.txt
   ![image](https://github.com/user-attachments/assets/0db83867-0217-449b-9749-ebe51cacf5f8)

   (b)Remove write permission for others: chmod o-w file.txt
   ![image](https://github.com/user-attachments/assets/0a8ac6ea-d677-4250-81cd-bdcb9cbd0985)

   (c)Give read and execute permission to the group: chmod g+rx file.txt
   ![image](https://github.com/user-attachments/assets/c70ce724-be6b-4434-b3ba-bedfa8830841)

   (d)Set specific permissions: chmod u=rwx,g=rx,o=r file.txt
   ![image](https://github.com/user-attachments/assets/91713542-4274-4d64-b588-5c01fdf8b410)

   (e)Set permissions to rwxr-xr-- using octal mode: chmod 754 file.txt
   ![image](https://github.com/user-attachments/assets/457fca54-1d39-4839-977a-104b2c6a7dcb)

   (f)Recursive Change of Permissions: chmod -R 755 /path/to/directory
   ![image](https://github.com/user-attachments/assets/bdc57d54-c529-477a-8b43-ad25b9b5b52d)

   (g)Change permissions based on existing files: chmod --reference=ref_file.txt target_file.txt
   ![image](https://github.com/user-attachments/assets/02c92eb1-b5d5-4275-b4df-c5709f471471)
