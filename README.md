This is a scenario exercise done in a recent Cybersecurity Experiential Workshop. It is hosted on Cyberium arena which is a cyber simulator with real-world data. It also has a wicked interface.

![Screenshot 2025-06-05 at 11 17 02 AM](https://github.com/user-attachments/assets/14bc2f48-70f8-44af-a478-92038f66f5b5)

There are 6 questions, focusing on the auth.log.2 file

# Key Takeaways and Learning 
* Chaining commands in text manipulation is very useful, caution must be given to the sequence of the chaining (left to right)
* It is key to read the objectives clearly. One small deviation or misinterpretation can lead to different results.
* In this sandbox environment, it's okay to try and submit the answers without being 100% sure of the answer
* In Q2, the correct answer was 1 number away from my previous answer. What happened? That single extra entry that should be removed had a username "rootftp", not the "root" user that  the question was looking for

# Skills showcased: Basic Linux commands, Text manipulation
Scenario Questions:
1. Log into 18.194.139.143 via SSH, entering 'admin?' as the user and 'Capitalb' as your password. In the /var/log folder, access auth.log.2 and calculate how many minutes the log has been recording events.
![Screenshot 2025-06-05 at 11 38 15 AM](https://github.com/user-attachments/assets/7c58e34e-9163-42d5-9705-c6f346c0793b)
**Answer: 540** (using the time listed in "head" and "tail" and finding the difference)

2. Assist the Security team in analyzing the auth.log.2 file and identify the number of unsuccessful access attempts made with the 'root' username.
![Screenshot 2025-06-04 at 3 30 34 PM](https://github.com/user-attachments/assets/b0ec8d74-fd8c-45fb-b359-0946b242b966)
**Answer: 3562** (previous answer 3563 was wrong) ![Screenshot 2025-06-05 at 12 03 25 PM](https://github.com/user-attachments/assets/9f52ed1e-9a52-4347-aa32-cff2ceadc82b)



3. Calculate how many unique IPs were responsible for these unsuccessful entries.
![Screenshot 2025-06-04 at 3 34 54 PM](https://github.com/user-attachments/assets/7e0d153f-bc4c-4dc2-a02b-3f939a81d124)
**Answer: 69**


4. Assist the investigators in identifying which IP address made the highest number of unauthorized access attempts to the system.
![Screenshot 2025-06-04 at 3 36 25 PM](https://github.com/user-attachments/assets/f4515bf0-7bee-4fb2-a56f-4bce894985cb)
**Answer: 14.181.8.32**

5. Assist the security team in identifying how many different usernames were used by the IP address 119.45.184.52 in its failed password attempts to access the system.
![Screenshot 2025-06-04 at 3 43 50 PM](https://github.com/user-attachments/assets/a957b87a-0b19-4dfa-bcd4-6920f3f83668)
**Answer: 91**

6. The hacking attempts have led the organization to question the identity of the interested parties. Assist the investigators in determining the country associated with the IP address 64.227.72.109.
![Screenshot 2025-06-04 at 3 52 07 PM](https://github.com/user-attachments/assets/8370cd03-6c03-4e4b-a0a8-c85f7f21fc0e)
**Answer: Netherlands** (previous answer NL was not accepted, guess they wanted the full name)

![Screenshot 2025-06-05 at 11 19 57 AM](https://github.com/user-attachments/assets/a8c68e6e-6f2e-416a-a4a7-be3f2a46defc)

