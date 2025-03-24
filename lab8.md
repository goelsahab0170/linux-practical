1. Shell Script to Print System Information -> (a)Create a file named system_info.sh:
   ![image](https://github.com/user-attachments/assets/adc63ce2-c915-4631-95a2-7801abb40119)
   (b)Make the script executable: chmod +x system_info.sh

   (c)Run the script: ./system_info.sh

   ![image](https://github.com/user-attachments/assets/d85cf8bb-8c18-4df2-b33a-2ee07e60acbb)
2. Shell Script to Perform Basic Mathematical Calculation -> (a)Create a file named calc.sh:
   ![image](https://github.com/user-attachments/assets/4d4f43d5-7d65-40be-b887-e046aba480d3)
   (b)Make the script executable: chmod +x calc.sh

   (c)Run the script: ./calc.sh
   ![image](https://github.com/user-attachments/assets/6fa58ec9-8620-4d82-bf8a-2a4d02e083e9)
3. Use Redirection Operators to Store Output of Commands -> (a)Redirect stdout to a file: ls > output.txt
   ![image](https://github.com/user-attachments/assets/142c6013-ae7f-4f4d-bcd8-2243e8da11fc)

   (b)Append output to an existing file: date >> output.txt
   ![image](https://github.com/user-attachments/assets/3a14818d-a69b-4979-8759-db289c76f715)
   ![image](https://github.com/user-attachments/assets/71ee28f2-0ba7-477d-a5f8-23bcd1076244)

   (c)Redirect stderr to a file: ls nonexistentfile 2> error.txt
   ![image](https://github.com/user-attachments/assets/f8942322-4789-48e9-82f8-9eb1901873ae)

   (d)Redirect both stdout and stderr to a file: ls . nonexistentfile &> all_output.txt
   ![image](https://github.com/user-attachments/assets/896de55b-874f-4873-b6a0-bbe643c5f297)

   ![image](https://github.com/user-attachments/assets/951d912f-a480-4300-9b74-4d577f03afda)

   (e)Pipe output to another command: cat file.txt | grep "keyword"
   ![image](https://github.com/user-attachments/assets/2b55a76a-512f-449d-a573-c0d62c68d8c7)

