# Mô tả
- Can you get the flag?
- Go to this website and see what you can discover.
# Cách Giải
- ***When you access the linked page in the topic, you will see a website asking to log in. If you log in to a certain account, the website will display a failed login.***
   - <img width="665" alt="Ảnh màn hình 2024-09-30 lúc 08 15 10" src="https://github.com/user-attachments/assets/d862f902-1173-4a40-b20c-c8bde7a24e4d">
 
- ***You must find the administrator to log in successfully. Please see the page source to find the admin account. We will see two files ending in .css and .js. Let's check those two files.***
 - <img width="860" alt="Ảnh màn hình 2024-09-30 lúc 08 15 27" src="https://github.com/user-attachments/assets/d307849a-8b98-4f72-8887-43c5b2ffab52">
 
- ***Going into the .css file we will see that there are no flags or encodings hidden inside.***
 - <img width="424" alt="Ảnh màn hình 2024-09-30 lúc 08 15 40" src="https://github.com/user-attachments/assets/2cce286d-5d62-4568-b88c-3e010801ff37">

 - ***So the flag will be hidden inside the .js file. Login under the admin account and you will find the flag.***
 - <img width="734" alt="Ảnh màn hình 2024-09-30 lúc 08 15 34" src="https://github.com/user-attachments/assets/8ae19e81-c061-423b-83df-199918364ba6">
- Flag: picoCTF{j5_15_7r4n5p4r3n7_05df90c8}
