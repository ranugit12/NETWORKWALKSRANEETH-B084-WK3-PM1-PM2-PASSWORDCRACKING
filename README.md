# NETWORKWALKSRANEETH-B084-WK3-PM1-PM2-PASSWORDCRACKING
Password cracking with John the ripper and hash cracking tools

## 📌Project overview: 

### WK3-PM1: Password cracking with JTR(John The Ripper)
This project focuses on cracking the password of a locked PDF (`My Locked PDF1.pdf`) using JTR(John The Ripper) and JTR Johnny.

#### 🔨Steps:

1. Open the below website to extract the hash from the locked PDF.

<img width="1916" height="1077" alt="Hash extraction from locked PDF" src="https://github.com/user-attachments/assets/55125946-44d1-46cb-840b-c3480b38ca5c" />


2. Copy the given hash and save it into a text file and name it as `hash1.txt`.

<img width="1917" height="1077" alt="Paste the copied hash into notepad" src="https://github.com/user-attachments/assets/d563530e-0b7c-417b-bd36-d128c84d1653" />
<img width="947" height="187" alt="Save the txt file as hash1" src="https://github.com/user-attachments/assets/3430528b-459c-4a4f-b9de-4f64a732f298" />


3.  Download John the Ripper from the official site and click on the link shown below in red.
   
   <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/bbc7c062-d622-46f8-94a8-5d6150fa2b87" />
   <img width="1917" height="1077" alt="John the Ripper" src="https://github.com/user-attachments/assets/03d6d946-8d34-4f7b-a940-11a1e098a85c" />

4. Download the current version of Johnny GUI.
   
   <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/bfe4c38b-f8fd-4bfd-9d2b-61d6523aa50a" />

5. Open JTR and select **settings** and import the executable file named `john.exe`. (It's in the **run** folder).
   
   <img width="867" height="687" alt="image" src="https://github.com/user-attachments/assets/61fc3dae-3277-4509-90f1-9ceb9059d929" />
   
6. Click on passwords and select **Open password file** then select the `hash1.txt` file which you saved previously and import it here.

   <img width="873" height="690" alt="Click on open password file" src="https://github.com/user-attachments/assets/f86d5290-6ae9-42cb-882e-ae0c3e6ccecc" />

7. Finally, click on start attack and the password shows just as it is shown in the red box.

   <img width="1862" height="1077" alt="Click on Start attack and password shows" src="https://github.com/user-attachments/assets/ecedd4a0-d263-4a10-88a4-911ee66d86ba" />


8. Use the password to unlock the PDF and reveal the flag.

<img width="575" height="802" alt="image" src="https://github.com/user-attachments/assets/9e71d99b-1993-4706-bebc-7003f1d81c68" />




### WK3-PM2: Password cracking with NETWORKWALKS tools

#### 🔨Steps:

1. Open the Hash calculator in your web browser.

  <img width="1897" height="1077" alt="image" src="https://github.com/user-attachments/assets/e7af87b0-45dc-4227-b933-010c4b1d00f5" />


2. Go to the file section highlighted in red and upload the file (`My-Locked-PDF1.pdf`). The hash will be revealed.

   <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/128ad98e-be68-45b7-87e5-b0bbc1e2b014" />
   <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/d1c81101-1d45-44f6-a345-2b60815a68cd" />

3. Copy and save the hash into a text file. (`My-Locked-PDF1_hash.txt`)

   <img width="877" height="290" alt="Hash save in txt file" src="https://github.com/user-attachments/assets/29b0bb80-657b-4b66-bd73-77a99881f320" />

4. Open the Password cracker in your web browser and Copy and paste the hash from the text file into the field below.

   <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/f0195e4e-0d7c-434f-a94e-43b446751361" />


5. Click on **Start Cracking**. The tool will start the attack and find the matching passwords. The password will be revealed as shown below.

   <img width="1917" height="1077" alt="Password cracked" src="https://github.com/user-attachments/assets/8798322b-dbca-412c-a7bd-a8ac740a040f" />



6. Copy the password paste it to unlock the PDF.

   <img width="657" height="855" alt="image" src="https://github.com/user-attachments/assets/aea14d26-3da1-4ed8-86a6-160b47353fc1" />



### ⚠️Warning:

This is to be used only for educational purposes. Any misuse will result in legal action taken against you.

### 🔗Resources:

- https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php
- https://www.openwall.com/john/
- https://openwall.info/wiki/john/johnny

### Author:

Raneeth Jayaratne

### Project Information
Instructor: Waqas Karim CCIE | Batch: B084 | Program name: Cybersecurity intern @NETWORKWALKS.

