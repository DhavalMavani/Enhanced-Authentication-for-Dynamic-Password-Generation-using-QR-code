# EADPQR: Enhanced Authentication for Dynamic Password Generation using QR Code

## Abstract

EADPQR introduces a novel approach to authentication by combining Dynamic Password Generation and QR code technology. This project aims to enhance security and accessibility by dynamically generating One-Time Passwords (OTPs) and transmitting them through distorted QR codes.

## Problem Statement

As cybersecurity threats evolve, conventional authentication methods become vulnerable to attacks. EADPQR addresses this challenge by dynamically generating OTPs and distorting QR codes, providing an innovative solution to mitigate man-in-the-middle attacks and enhance password protection.

## Algorithm

The EADPQR algorithm follows a streamlined process:

1. **OTP Generation:** EADPQR generates an "N" digit OTP based on client input using a randomized matrix method.

2. **SKIN_OTP Superimposition:** A secondary OTP, SKIN_OTP, is generated using the same matrix method. SKIN_OTP is superimposed over the primary QR code to introduce distortion.

3. **Transmission:** The distorted QR code is transmitted over a secure connection, bypassing decryption patterns using OpenCV libraries.

4. **Decryption:** The end-user can retrieve the transmitted OTP using a decryption algorithm, ensuring secure and accessible authentication.

## Architecture

| Flow Diagram | <img width="527" alt="image" src="https://github.com/DhavalMavani/Enhanced-Authentication-for-Dynamic-Password-Generation-using-QR-code/assets/61201815/fb57d519-d59d-4139-bed8-0d436d1cfb5f"> |
|--|--|
| System Architecture Diagram | ![image](https://github.com/DhavalMavani/Enhanced-Authentication-for-Dynamic-Password-Generation-using-QR-code/assets/61201815/36724927-e69c-4301-9708-787a1c67d904) |
| Program Flow | ![image](https://github.com/DhavalMavani/Enhanced-Authentication-for-Dynamic-Password-Generation-using-QR-code/assets/61201815/75c069b7-eb37-4409-b5f0-2af3016ba6a8) |
| Sequence Diagram | ![image](https://github.com/DhavalMavani/Enhanced-Authentication-for-Dynamic-Password-Generation-using-QR-code/assets/61201815/f0e00082-fa4b-401d-9fec-786e1c262ed7) |
