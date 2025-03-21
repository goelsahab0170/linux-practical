1. Open the editing_final_lab.txt file in Vim and Nano: -> VIM- vim editing_final_lab.txt NANO- nano editing_final_lab.txt

![image](https://github.com/user-attachments/assets/e07ac686-2abf-4533-9303-33313bbce4b2)
![image](https://github.com/user-attachments/assets/ab694e8e-4742-4166-9832-9eeb7940315f)

![image](https://github.com/user-attachments/assets/eb1e97a6-215e-4f18-9b61-4f78128f5d4e)
![image](https://github.com/user-attachments/assets/92c9be50-bcb1-4e69-9925-8e1f708f09de)

2. Use the lab_file shell variable: -> lab_file="editing_final_lab.txt" vim $lab_file
![image](https://github.com/user-attachments/assets/f7a34003-3822-4f27-949a-1155312cca0c)

3. Enter visual mode in Vim: -> Open Vim. Press v to enter visual mode.
![image](https://github.com/user-attachments/assets/33b1f177-2723-459b-8e16-654ce26fa541)

4. Remove the last seven characters from the first line: -> Press ^ (caret) to go to the beginning of the line. Press v to start selecting characters. Move to the end of the line using $. Press d7 to delete the last 7 characters.
5. Preserve only the first four characters of the first column: -> Go to the beginning of the line using 0. Press v and move to the 4th character using l (right arrow). Press d to delete everything after the 4th character.
6. Save and exit: -> :wq
