# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results

![a3](https://github.com/user-attachments/assets/d5acae00-66e8-4da8-ac12-9eb6e977fe13)

![a4](https://github.com/user-attachments/assets/727e0bcb-15f8-45ea-9da3-c3b575111b71)

<img width="1048" height="675" alt="Screenshot 2025-08-29 092436" src="https://github.com/user-attachments/assets/2e9a433a-e2e8-44c9-ad12-7618275e26aa" />

![a6](https://github.com/user-attachments/assets/8407ea2d-9e92-4291-910b-f790b70270a9)

![Screenshot 2025-03-28 093408](https://github.com/user-attachments/assets/512e434e-45d1-41f2-ad37-9cf2908465e3)

![Screenshot 2025-03-28 094853](https://github.com/user-attachments/assets/1c30d0f9-174f-4ab4-b45e-03c246aa8486)


![Screenshot 2025-03-28 094903](https://github.com/user-attachments/assets/995557a3-6014-42c1-a15d-0ad1c2c5b795)


![Screenshot 2025-03-28 103946](https://github.com/user-attachments/assets/10054efb-eb5a-47ad-bea5-bd29e88ee06d)

# RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.

