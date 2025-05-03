
# EPIC Challenge AECC round


## Technical Introduction
This document provides step-by-step instructions to connect and complete this stage of the EPIC Challenge, a CTF (Capture The Flag)-type exercise involving directory navigation, key file search, password decryption, and file decryption.

## Challenge Objectives
According to the provided information, your mission is:

1. Navigate through a directory structure
2. Find a password encrypted with Caesar cipher
3. Find a target encrypted file
4. Decrypt the target file using the found password

## Accessing the Environment
### Via browser
```
http://shortline.proxy.rlwy.net:53282/
```

```
User: epic_guest  
Password: epic_guest
```

### Local alternative
Alternatively, you can access via SSH:
```
https://drive.google.com/drive/u/0/folders/1gY8ZtA_0j8u8SzFG6WW-2v7EmTt2oMSS
```

```
ssh epic_guest@localhost -p 2222  
Password: epic_guest
```

## Environment Structure

The script sets up the following environment:

* 20 main directories (dir1 to dir20)
* Each main directory contains 5 subdirectories (maybehere1 to maybehere5)
* Each subdirectory contains 5 files (file1.txt to file5.txt)

