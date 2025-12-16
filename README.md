📌Project Overview:
The Secure Online Voting System with Face Recognition is a web-based application designed to provide a secure, transparent, and reliable voting process. The system uses Machine Learning–based face recognition to authenticate voters, ensuring that only eligible voters can cast their vote and that each voter can vote only once.
This project aims to eliminate common issues in traditional voting systems such as impersonation, duplicate voting, and manual errors, while enabling remote voting in a secure manner.
🎯 Objectives:
Ensure secure voter authentication using face recognition
Prevent duplicate and fake voting
Provide remote online voting capability
Maintain data integrity and transparency
Automate vote counting and result generation
🧠 Technologies Used
Frontend
HTML5
CSS3
JavaScript
Bootstrap
Backend
Python

Database:
MySQL 
Machine Learning
Python
OpenCV
Face Recognition Library
NumPy

Tools & Libraries:
Webcam for face capture

🔐 System Features
1️⃣ Voter Registration

Voter registers with:
Name
Voter ID
Email
Face image
Face data is stored securely in the database

2️⃣ Face Recognition Authentication

Live face captured via webcam
Face compared with stored data using ML model
Access granted only if face matches

3️⃣ Secure Voting

Each authenticated voter can vote only once
Votes are encrypted and stored securely

4️⃣ Admin Panel

Add / remove candidates
View registered voters
Monitor voting status
View election results

5️⃣ Result Declaration

Automatic vote counting
Real-time result display
Eliminates manual calculation errors

🏗️ System Architecture

User accesses the voting portal
User logs in using voter credentials
Face recognition system verifies identity
Voting interface is enabled
Vote is cast and stored securely
System updates vote count
Admin views final results

🧪 Machine Learning Workflow

Image acquisition using webcam
Face detection using OpenCV
Feature extraction
Face encoding generation
Face comparison with stored encodings
Authentication decision

🗄️ Database Schema (Sample)

name
email
face_encoding
vote_status
candidate_name
party_name
vote_count
