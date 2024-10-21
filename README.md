# Embedded-Systems-Security
This repository contains projects and resources focused on embedded systems security, developed in the context of the Embedded Capture the Flag (eCTF) competition run by MITRE Engenuity. The eCTF is a semester-long challenge designed to test participants' ability to secure embedded systems, highlighting various security methods.


## Documentation
 Medical Device Security Notes

 These are the notes we took during the training and development phase. They include a variety of topics, such as loading firmware onto the microcontroller, the development environment, and the weaknesses in the insecure eCTF example code. We learned how to successfully deploy firmware using Linux, and Mac OS. We also learned how to use the cortex-debug plugin in Visual Studio Code. 

Attack Phase Group Assignment

This document outlines the steps we took to complete the attack phase of the eCTF competition. We were tasked with exploiting the vulnerabilities in the insecure eCTF example code. We successfully exploited the vulnerabilities and gained control of the device. We found that CA had a secure bootloader but UTArlington had leaking information exposing the flag. We also found that the UTArlington device had a buffer overflow vulnerability.

## Team Members
- [Luciano] (Architect and Lead-Developer)
- [Hadise] (Team Lead)
- [Merve] (Co-Developer and Investigator)
- [Maryam] (Documenter)
