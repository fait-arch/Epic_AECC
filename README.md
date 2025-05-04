<div align="center" style="background-color: white; padding: 20px; display: inline-block;">
  <img src="https://github.com/AECCuide/AECCuide/blob/main/img/logotipoLetrasAECC.svg?raw=true" width="200">
  <img src="https://github.com/AECCuide/AECCuide/blob/main/img/logotipoLetrasAECC.svg?raw=true" width="200">
</div>
<p align="center">
  <a>
      <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/community/logos/python-logo-only.png" alt="python" width="40" height="50"/>
  </a>
  <a>
    <img src="https://d33wubrfki0l68.cloudfront.net/45825999a370278a2d392daafce3e7a95de0fff2/3bada/img/logo/svg/full_colored_light.svg" alt="Bash" width="100" height="50"/>
  </a>
</p>

---

# EPIC Challenge AECC Round

## Technical Introduction

This document provides step-by-step instructions to connect and complete this stage of the **EPIC Challenge**, a CTF (Capture The Flag)-type exercise involving directory navigation, key file search, password decryption, and file decryption.

---

## Challenge Objectives

According to the provided information, your mission is:

1. Navigate through a directory structure
2. Find a password encrypted with Caesar cipher
3. Find a target encrypted file
4. Decrypt the target file using the found password

---

## Accessing the Environment

### Via Browser

[Terminal Accesible por el navegador](http://shortline.proxy.rlwy.net:53282/)

```
User: epic_guest  
Password: epic_guest
```

### Local Alternative

Alternatively, you can access via SSH:

* [Imagen de Docker](https://drive.google.com/drive/u/0/folders/1gY8ZtA_0j8u8SzFG6WW-2v7EmTt2oMSS)

Una vez que descargaste e importaste la imagen con:

```
docker load -i epic_challenge_image.tar
```

Puedes verificar que está disponible con:

```
REPOSITORY             TAG       IMAGE ID       CREATED         SIZE
epic_challenge_image   latest    abcdef123456   x minutes ago   x MB
```

Ejecuta esto para probar:

```
docker run -it --name epic_challenge_container epic_challenge_image
docker run -it --rm epic_challenge
```

---

## Environment Structure

The script sets up the following environment:

* 20 main directories (`dir1` to `dir20`)
* Each main directory contains 5 subdirectories (`maybehere1` to `maybehere5`)
* Each subdirectory contains 5 files (`file1.txt` to `file5.txt`)

---

## Deliverable

You must submit **two files**:

* A `.sh` script to validate the process used to locate the file.
* A `.py` or `.ipynb` file to validate the result obtained.

The submission should follow this format:
[Colab Deliverable Example](https://colab.research.google.com/drive/1AG0d2z8kajN1Y8asFLcHd6FqHbgoRZf3?usp=sharing)




