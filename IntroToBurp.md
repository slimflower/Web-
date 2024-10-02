# Describe
- Try here to find the flag
# Solution
- The question shows you a link and asks you to find the flag hidden in that link
- **Step 1**
   - When accessing the link, you will see the interface "Registration". This means that you must log in to an account to find the encryption behind it.
   - <img width="629" alt="Ảnh màn hình 2024-09-28 lúc 14 58 06" src="https://github.com/user-attachments/assets/601703de-a9cb-444a-8cc3-f268cb20c3a6">
   - If you try to log in to an account, you will see an interface with an otp code. <img width="541" alt="Ảnh màn hình 2024-09-28 lúc 14 54 13" src="https://github.com/user-attachments/assets/edbb1d27-5e87-4719-aad7-468891c2ebff">
- **Step 2**
   - As you can see, to find the hidden flag we must have the otp code. To decode this we need to use a tool called Burp suite.
   - To be able to get the flag you must be an admin accessing the website for the flag to appear.
   - When you enter a certain otp code, the request section will display the otp code you entered. What you need to do now is change to admin
   - <img width="657" alt="Ảnh màn hình 2024-09-28 lúc 15 53 09" src="https://github.com/user-attachments/assets/d2f71431-a846-455e-9bf4-f04f77dd8fc3">
   - When you change to admin, the flag will appear
   - <img width="738" alt="Ảnh màn hình 2024-09-28 lúc 15 56 00" src="https://github.com/user-attachments/assets/8914d48f-1b24-43dd-a1d1-7e6395a8d95d">
   - Flag:picoCTF{#0TP_Bypvss_SuCc3$S_9090d63c}
