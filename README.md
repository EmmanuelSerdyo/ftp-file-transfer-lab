#  FTP File Transfer Lab

## Objective
- Upload a file to an FTP server
- Download a file from an FTP server

## Tools
- FTP client (CLI)
- FTP server (lab environment)
- FTP Packet tracer

## Scenario
File Transfer Protocol (FTP) is used to transfer files between clients and servers.  
- Port 21: commands  
- Port 20: data transfer  

## Steps
1. Connect to FTP server: `ftp 209.165.200.226`
2. Upload a file: `put sampleFile_FTP.txt`
3. Verify files on server: `dir`
4. Download a file: `get sampleFile_FTP.txt`
5. Close connection: `quit`

## Screenshots
<img width="1892" height="928" alt="Screenshot 2026-03-23 222017" src="https://github.com/user-attachments/assets/edf19bee-c421-404d-b65b-7fd2565e1fec" />
<img width="1914" height="968" alt="Screenshot 2026-03-23 222649" src="https://github.com/user-attachments/assets/66bf72cf-83dd-442d-b8cd-cac99525ce4b" />

## Lessons Learned
- FTP transmits data in plaintext → security risk
- Learned basic file transfer commands

## ⚠️ Disclaimer
Performed in a controlled lab environment for educational purposes.
