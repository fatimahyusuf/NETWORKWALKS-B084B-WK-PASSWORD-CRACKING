# NETWORKWALKS-B084B-WK3-PASSWORD-CRACKING

# Week 3 Project: Password Cracking With John The Ripper And Networkwalks Tools

## Project Overview

This project focused on practical password-cracking techniques using John the Ripper and NetworkWalks tools as part of my cybersecurity internship. I used these tools to perform password-cracking exercises, analyze password hashes, and understand how weak passwords can be identified through password security testing.

The exercise provided hands-on experience with password-cracking techniques and improved my understanding of password vulnerabilities, authentication security, and the importance of using strong passwords to prevent unauthorized access.

All activities were conducted within the authorized NetworkWalks training environment for educational purposes.

## Module 1 (WK3-PM1): Paasword Cracking With John the Ripper

### Objectives
- To understand how password cracking works and its application in cybersecurity.
- To use John the Ripper and Johnny GUI to recover the password of a protected PDF file.
- To extract the password hash from an encrypted PDF file.
- To load and analyze the extracted hash using John the Ripper.
- To understand the importance of strong passwords in protecting sensitive information.

### Tools Used
1. John the Ripper (JTR): Used to perform password cracking by analyzing the extracted PDF password hash.
2. Johnny GUI: Graphical interface for managing John the Ripper and initiating password-cracking attacks.
3. Online Hash Extractor: Used to extract the password hash from the protected PDF file.
4. Notepad: Used to save the extracted hash in a .txt file for processing.
5. Protected PDF File (My Locked PDF1.pdf): The sample file used for the password-cracking exercise.
6. Windows PC: The operating environment used to perform the exercise. 

### Workflow
1. Download and Install Tools: Downloaded John the Ripper and Johnny GUI and configured Johnny to locate the john.exe executable file.

#### Evidence
<img width="847" height="554" alt="Screenshot 2026-11-20 133504" src="https://github.com/user-attachments/assets/b0e8fbe5-73e2-471c-80e5-f55168fcb85a" />

2. Prepare the Protected PDF: Downloaded the sample password-protected PDF file (My Locked PDF1.pdf) provided for the exercise.

#### Evidence
<img width="1089" height="140" alt="Screenshot 2026-11-20 135520" src="https://github.com/user-attachments/assets/3545cbc6-fcd4-4f0a-99aa-c111eef23e2c" />

3. Extract the Password Hash: Uploaded the protected PDF to the Online Hash Extractor to retrieve its password hash.

#### Evidence
<img width="1224" height="853" alt="Screenshot 2026-11-20 093814" src="https://github.com/user-attachments/assets/f5da61c4-d585-4af1-a00c-945e19f43a9b" />

4. Save the Hash: Copied the extracted hash into Notepad and saved it as hash1.txt, ensuring the hash was in the correct format.

#### Evidence
<img width="509" height="41" alt="Screenshot 2026-11-20 094206" src="https://github.com/user-attachments/assets/a70ae480-f98a-45e7-8c08-8097f0fc5510" />

5. Load the Hash into Johnny: Opened Johnny GUI, selected Open Password File, and imported the saved hash1.txt file.

6. Perform Password Cracking: Selected Start New Attack to initiate the password-cracking process using John the Ripper.

7. Recover the Password: Allowed the tool to process the hash until the PDF password was successfully recovered.

#### Evidence
<img width="854" height="654" alt="Screenshot 2026-11-20 094412" src="https://github.com/user-attachments/assets/eaabe37d-a4e4-43b5-8fac-86232448fff3" />


8. Verify the Result: Used the recovered password to open the protected PDF file and confirmed that it was accessible.

#### Evidence
<img width="716" height="782" alt="Screenshot 2026-11-17 083726" src="https://github.com/user-attachments/assets/802b3786-a24a-4327-8126-dc5550becc60" />


###  Outcome
Successfully recovered the password of the protected PDF file using John the Ripper through Johnny GUI. The exercise provided practical experience in password-hash extraction, password cracking, and password security assessment.


## Module 2(WK3-PM2): Password Cracking With Networkwalks Tools

### Objectives
- To understand the concept of password cracking and password hashes.
- To extract password hashes from an encrypted PDF file using the NetworkWalks Hash Calculator.
- To use the NetworkWalks Password Cracker to recover the password from the extracted hash.
- To understand how dictionary attacks work in password cracking.
- To demonstrate the importance of strong passwords in protecting sensitive files.

### Tools Used
1. NetworkWalks Hash Calculator: Used to extract the password hash from the protected PDF file.
2. NetworkWalks Password Cracker: Used to perform a dictionary attack against the extracted hash and recover the password.
3. Web Browser: Used to access and operate both NetworkWalks online tools.
4. Windows Laptop: The system used to carry out the practical exercise.
5. Protected PDF File (My Locked PDF1.pdf): The sample file used for the password-cracking exercise.

### Workflow
Step 1: Download the Encrypted PDF
Downloaded the sample password-protected PDF file [My Locked PDF1 for NW Tools Lab (WK3-PM2).pdf] from the NetworkWalks project lab page.

#### Evidence
<img width="1085" height="121" alt="Screenshot 2026-11-20 142705" src="https://github.com/user-attachments/assets/302fd0fa-3a65-4597-b32f-f9163f6e97a7" />

Step 2: Open the NetworkWalks Hash Calculator
Accessed the NetworkWalks Hash Calculator through a web browser to prepare for extracting the PDF hash.

#### Evidence
<img width="1618" height="728" alt="Screenshot 2026-11-20 143108" src="https://github.com/user-attachments/assets/aad79ca0-4e1e-4743-89fd-8e604dc81b9b" />

Step 3: Upload the Protected PDF
Uploaded the encrypted PDF file to the Hash Calculator, which processed the file and generated its corresponding password hash.

#### Evidence
<img width="1259" height="618" alt="Screenshot 2026-11-20 094747" src="https://github.com/user-attachments/assets/593866a4-8bb2-4a6d-9594-5ef05198f8f1" />

Step 4: Copy the Extracted Hash
Copied the complete PDF hash generated by the Hash Calculator, ensuring that no part of the hash was missing.

Step 5: Open the NetworkWalks Password Cracker
Accessed the NetworkWalks Password Cracker through the web browser to begin the password recovery process.

#### Evidence
<img width="1479" height="779" alt="Screenshot 2026-11-20 144023" src="https://github.com/user-attachments/assets/c07c9496-9c5c-4479-a58a-4618ded875fa" />

Step 6: Initiate the Password-Cracking Attack
Pasted the extracted PDF hash into the Password Cracker and selected Start Cracking to initiate the dictionary attack.

#### Evidence
<img width="1286" height="756" alt="Screenshot 2026-11-20 094930" src="https://github.com/user-attachments/assets/ace5d9e1-0a90-4b5b-9e52-7f7560dbf09a" />

Step 7: Recover the Password
Allowed the Password Cracker to process the hash until a matching password was found and displayed on the screen.

Step 8: Verify the Recovered Password
Opened the protected PDF file and entered the recovered password to verify that the password was correct.

#### Evidence
<img width="782" height="817" alt="Screenshot 2026-11-17 234214" src="https://github.com/user-attachments/assets/10e7e668-9d58-4aaa-b9ea-56e92d73d0a9" />

Step 9: Confirm Successful Access
Successfully opened the PDF file and confirmed the completion of the password-cracking exercise.


### Outcome
Successfully recovered the password of the protected PDF file using the NetworkWalks Hash Calculator and Password Cracker. The exercise provided practical experience in hash extraction, dictionary-based password cracking, and password security assessment.


## What i Learned

Through both password-cracking modules, I gained practical knowledge and a better understanding of password security and password-cracking techniques. I learned how to extract password hashes from protected PDF files and use different tools, including John the Ripper, Johnny GUI, NetworkWalks Hash Calculator, and NetworkWalks Password Cracker, to recover passwords.

I also gained hands-on experience loading and analyzing password hashes, initiating password-cracking attacks, and performing dictionary attacks to identify matching passwords. Additionally, I developed a better understanding of how weak passwords can be vulnerable to cracking and why creating strong, complex passwords is important for protecting sensitive files.

Overall, both exercises strengthened my practical cybersecurity skills and introduced me to different approaches and tools used in password security assessment.


# Author

Name: Yusuf Fatimah Itunuoluwa

Program: Networkwalks Cybersecurity Internship

LinkedIn: https://www.linkedin.com/in/fatimah-yusuf-4b31442a9/
