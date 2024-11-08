# ENPM634 - Penetration Testing Project

## Overview

This repository contains a penetration test report conducted on the ENPM634 Pumpkins web application, a Capture-the-Flag (CTF) style midterm project. The objective was to uncover the full name of the web app's creator by exploiting vulnerabilities and following a series of clues within the application.

## Objectives

The primary objectives of this assessment were:

1. Discover the full name of the web app creator by exploring hidden clues and files.
2. Document the steps taken, including tools and techniques used to gain access to sensitive information.
3. Provide a concise walkthrough highlighting significant findings and artifacts encountered.

## Methodology

The assessment was performed using standard penetration testing methods:

1. **Reconnaissance**: Captured packets with Wireshark to locate potential login credentials.
2. **Access**: Gained SSH access using discovered credentials.
3. **Exploration**: Searched directories and examined files to find relevant information.
4. **Final Exploit**: Entered the creator’s full name into the web app, successfully capturing the final flag.

## Key Findings

- **Weak Credentials**: Easily guessable credentials allowed SSH access to user accounts.
- **Sensitive Files**: Located hidden files containing critical information.
- **Flag Capture**: Entered the discovered full name into the web app, unlocking the final message and flag.

## Tools Used

- **Wireshark**: To capture packets and identify credentials.
- **Kali Linux**: For SSH login and command execution.
- **Hydra**: To brute-force passwords.
- **Secure Copy (SCP)**: For transferring files from the VM to the local machine.

## Challenges

1. **Credential Discovery**: Analyzing packets for login credentials required thorough inspection.
2. **Password Brute-Forcing**: Multiple attempts were needed to crack certain passwords.

## Conclusion

This penetration test illustrated the importance of securing login credentials, monitoring network activity, and limiting access to sensitive information. The walkthrough provided in this report offers a step-by-step guide to reaching the final flag, demonstrating effective methods for reconnaissance and exploitation.

For a detailed guide, please refer to the full walkthrough report in this repository.
