# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.
## EQUIPMENT REQURIED:
● Hardware: Personal Computer (PC)

## DESIGN STEPS:
# 1. Copy Files to the Virtual Disk
Open File Explorer → Go to the new drive (D:), where the folder created in the New Virtual Disk
Create a new folder or use the entire disk and then copy images or files into it.
# 2. Delete the Files
Select any one or two images → Press Delete.
Empty the Recycle Bin to permanently delete them.
# 3. Recover Deleted Files Using Autopsy
# Open Autopsy & Create a New Case
Launch Autopsy and Run as a administrator
Click Create New Case.
![a1](https://github.com/user-attachments/assets/5b5cf129-3382-4f0e-b0ee-6c5fbfed8fc3)
Enter a Case Name 
Choose a Case Folder location.
Click Next → Click Finish.
![a2](https://github.com/user-attachments/assets/54f08e44-f85b-476e-9d22-e944896489b3)

# Add the Virtual Disk as an Evidence Source
Click Add Data Source → Select Host
![a3](https://github.com/user-attachments/assets/d5acae00-66e8-4da8-ac12-9eb6e977fe13)
Select Local Disk → next
![a4](https://github.com/user-attachments/assets/727e0bcb-15f8-45ea-9da3-c3b575111b71)
Select
 Disk → Choose the VHD drive 
<img width="1048" height="675" alt="Screenshot 2025-08-29 092436" src="https://github.com/user-attachments/assets/2e9a433a-e2e8-44c9-ad12-7618275e26aa" />
Click Next → Keep default settings → Click Finish.
Wait for Autopsy to process the disk.
# Recover Deleted Files
Go to File Views (left panel).
![a6](https://github.com/user-attachments/assets/8407ea2d-9e92-4291-910b-f790b70270a9)
Click Deleted Files → Find your deleted images.
Right-click an image → Click Extract File.
![Screenshot 2025-03-28 093408](https://github.com/user-attachments/assets/512e434e-45d1-41f2-ad37-9cf2908465e3)
Select a folder to see the recovered files 
Image is recovered successfully.

# Output :
Folder before deleting the files
![Screenshot 2025-03-28 094853](https://github.com/user-attachments/assets/1c30d0f9-174f-4ab4-b45e-03c246aa8486)

Folder after deleting the files
![Screenshot 2025-03-28 094903](https://github.com/user-attachments/assets/995557a3-6014-42c1-a15d-0ad1c2c5b795)

Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-28 103946](https://github.com/user-attachments/assets/10054efb-eb5a-47ad-bea5-bd29e88ee06d)

# RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.

