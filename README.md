# ☁️🔍 Displaying Metadata Information (ExifTool)

![Badge](https://img.shields.io/badge/Cloud%20Security-Metadata%20Analysis%20%7C%20ExifTool-red?style=for-the-badge)

📄 **Full Lab Report:**  
👉 [Click here to open the complete lab report](https://github.com/Pelumi-Johnson/-Creating-a-Virtual-Machine-and-Installing-Ubuntu-Using-Hyper-V/blob/main/Creating%20a%20Virtual%20Machine%20and%20Installing%20Ubuntu%20Using%20Hyper-V%20%20.pdf)

## 📌 Project Overview
UMGC cloud security lab focused on displaying, analyzing, and modifying metadata within image files using ExifTool. The lab emphasizes command-line analysis, metadata attribution, and verification techniques relevant to cloud security and digital forensics.

---

## 🧠 Course Information
- **Institution:** University of Maryland Global Campus (UMGC)
- **Course:** CMIT 436 – Cloud Security
- **Lab Title:** Displaying Metadata Information
- **Date:** January 14, 2026

---

## 🎯 Objective
Learn how to display, analyze, and modify metadata stored within image files using ExifTool, and verify metadata changes through command-line analysis.

---

## 🧰 Tools & Environment
- uCertify Virtual Lab (Linux Environment)
- Ubuntu Linux
- Terminal
- ExifTool
- Image file: `ubuntu-default-greyscale-wallpaper.png`

---

## ✅ Lab Walkthrough

### Step 1: Open the Terminal
- Opened the Terminal from the Ubuntu desktop sidebar
- Used the terminal for all installation and analysis commands

### Step 2: Install ExifTool
- Navigated to the Downloads directory
- Extracted the Image-ExifTool package
- Generated the Makefile using Perl
- Installed required dependencies
- Compiled and installed ExifTool
- Verified successful installation

### Step 3: Display Metadata
- Executed ExifTool on the image file located at:  
  `/usr/share/backgrounds/ubuntu-default-greyscale-wallpaper.png`
- Observed metadata including:
  - File name and directory
  - File size and permissions
  - Image dimensions and format
  - Modification and access timestamps

### Step 4: Add Metadata
- Added a new metadata attribute to the image file using ExifTool
- Set the attribution name to identify **uCertify** as the source
- Overwrote the original file as instructed

### Step 5: Verify Metadata Changes
- Re-ran ExifTool on the same image file
- Confirmed the new attribution metadata was present and correctly recorded

---

## 📊 Results Summary
- ExifTool successfully installed and executed
- Image metadata displayed without errors
- New metadata attribute added successfully
- Metadata changes verified using ExifTool

---

## 🧾 Conclusion
This lab demonstrated how file metadata can be accessed and modified using command-line tools. Working with ExifTool provided hands-on experience in metadata analysis, a critical skill in cloud security, digital forensics, and incident response. Understanding metadata helps identify file origins, changes, and potential indicators of compromise.

---

## 🔑 Key Takeaways
- Metadata contains valuable hidden information about files
- ExifTool is a powerful utility for reading and editing metadata
- Command-line analysis is essential for forensic investigations
- Metadata analysis supports cloud security and incident response workflows

---

## 📎 Documentation
- 📄 Full UMGC Lab Report (PDF): `Displaying Metadata Information.pdf`
