# Lab Assignment 3

## Overview

To get you a grasp of how PKI works, this lab simulates the issuance, revocation, and installation process of digital certificates. Specifically, you will do some experiments in the GENI environment, and go through them using OpenSSL, a widely used cryptographic toolkit. The tasks in this assignment are divided into two lab modules. The first module focuses on certificate issuance and revocation, while the second module focuses on the chain of trust. Since there are quite a few overlaps between these two modules, getting familiar with the first module will dramatically speed up your pace in the second one. It is recommended that you complete the first module before you move on to the second one.

**Note: You only need to complete Module 1 and Two Additional Tasks as below.**

## Environment Setup

For each lab module, you have to create a seperate **slice** in GENI, and reserve resources as decribed in lab manuals. After the resources are available, connect to those VMs through ssh and do the correspondent tasks. If you have difficulty setting up the environment, please refer to the [beginner's guide](http://groups.geni.net/geni/wiki/GENIExperimenter/Tutorials) for GENI.

### GENI 101

Set up your GENI Account

1. Go to https://portal.geni.net and log in with your JHU ID. You may need to search for "Johns Hopkins" the first time.
2. After you are logged into the GENI Portal, find _Join the Project_ button and request to join the class project named **InfoSec2020Lab**.
3. Once you are approved to join the project, you can create your own experimental _slices_.

For Windows users, please refer to these getting started series of [win-1](http://mountrouidoux.people.cofc.edu/CyberPaths/GettingStartedWindows.html), [win-2](http://mountrouidoux.people.cofc.edu/CyberPaths/GettingStartedWindowsHelloGENI.html).
For Mac users, please refer to these guides of [mac-1](http://mountrouidoux.people.cofc.edu/CyberPaths/GettingStartedMac.html), [mac-2](http://mountrouidoux.people.cofc.edu/CyberPaths/GettingStartedMacHelloGENI.html).

## Module 1: Certificate Issuance and Revocation (40 points)

Complete tasks in the [lab manual](module1/README.md) and answer all questions. Use your team name(initials of your team members) instead of "jhuws" in the instructions. Since you are required to include screenshots in your report, it is suggested that you capture screenshots periodically.

## Module 2: Certificate Authority Hierarchy

Follow the instructions in the [lab manual](module2/README.md) and answer all questions. Use your team name(initials of your team members) instead of "jhuws" in the instructions. Still, you have to include screenshots for this module in the report. Please capture them periodically.

## Additional Tasks (10 points)

Please complete (1) and (2) in the Additional Tasks section in Module 1, as listed at the end of the lab manual.

## Submission Details

- Each group only needs to submit one report in PDF format. Please list group members in your report explicitly.
- **_Use your team name (initials of your team members) instead of "jhuws" in the assignment and include screeshots for each sections in your report._**
- Only typed reports are accepted.

## Grading

- Completeness (30 points): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
- Presentation (20 points): The report must be clear and correct in organization and writing with adequate explanation.
