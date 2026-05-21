# Digital-Forensics-Investigation-Project
## Overview

This project presents a digital forensic investigation conducted on two forensic image files: E_01_Physical_Image_Christy and USB_03.E01. The investigation focused on identifying, recovering, and analysing digital artefacts related to suspected cybercrime activities. The project demonstrates the use of digital forensic methodologies, forensic tools, file system analysis, file signature analysis, and evidence handling procedures.

The investigation was performed using both Kali Linux and Windows 11 Home virtual machines to compare forensic analysis techniques and evaluate which environment provided a more efficient and user-friendly investigation process.

## Objectives

Recover deleted and hidden files from forensic images

Analyse file systems and partition structures

Identify suspicious and disguised files using file signatures

Investigate evidence related to illegal activities

Compare forensic investigation processes between Kali Linux and Windows

Maintain forensic integrity during evidence acquisition and analysis

### Tools Used

### 🐉 Kali Linux Tools

| Tool | Purpose |
|------|---------|
| Autopsy | Digital forensic analysis and file recovery |
| FTK Imager | Create and analyse forensic images |
| MediaInfo | Analyse media file metadata |
| FFmpeg | Analyse and process multimedia files |
| Strings | Extract readable text from binary files |
| Foremost | File carving and recovery |
| Volatility | Memory forensic analysis |
| ewfmount | Mount E01 forensic images |

---

### 🪟 Windows Tools

| Tool | Purpose |
|------|---------|
| Autopsy | File system and deleted file analysis |
| FTK Imager | Evidence acquisition and verification |
| VeraCrypt | Access encrypted forensic volumes |
| HxD | Hexadecimal analysis |


## Investigation Summary 
#### Task 1 – USB Investigation

A USB device with a storage size of 3.74 GB was provided for forensic investigation. A forensic image named E_01_Physical_Image_Christy was created and analysed to recover deleted images and identify hidden or suspicious files.

## Findings
Recovered deleted image files
Analysed partition structures and file systems
Verified file types using hexadecimal signatures
Identified hidden and disguised files
Task 2 – Comparative Forensic Analysis

This task focused on comparing forensic investigation procedures between Kali Linux and Windows environments.

## Objectives
Compare usability of forensic tools
Analyse compatibility and investigation speed
Evaluate ease of evidence recovery and analysis

## Observation

Windows Autopsy provided easier navigation for image and file recovery, while Kali Linux provided stronger command-line forensic capabilities and advanced analysis tools.

## Task 3 – VeraCrypt and USB_03.E01 Investigation

The forensic image USB_03.E01 was mounted and analysed using VeraCrypt, Autopsy, FTK Imager, and HxD.

## Evidence Recovered

JPG image files
Fake JPG files
Income spreadsheet files (.xlsx)
DVD cover images
Recycle Bin artefacts
WPSettings.dat file
System Volume Information folder contents
File Signature Analysis

#### Several files were analysed using hexadecimal signatures:

File Type	Signature
* JPG 	FF D8 FF

* MP3   FF FB

* ZIP 	50 4B

* GIF 	47 49 46 38

* BMP	 42 4D


## Investigation Findings

The investigation initially suggested an illegal anime movie distribution operation due to the presence of anime-related DVD covers, posters, and financial spreadsheets showing revenue from media sales.

However, further investigation identified evidence consistent with suspected drug trafficking activities. Several terms commonly associated with narcotics distribution were discovered, including:

Charlie,   
Rocks,   
Crystal,   
Fire,    
Horse,    
E,      
Mary J,     
Speed.  

These terms are widely recognised street names for illegal drugs.
The evidence suggests that the anime distribution business may have been used as a front to conceal illegal drug-related activities.



## Legal and Ethical Considerations:   
The investigation followed standard digital forensic principles and ACPO guidelines to maintain evidence integrity.

### Relevant legal frameworks include:

* UK Computer Misuse Act 1990, 

* Copyright, Designs and Patents Act 1988, 

* Data Protection Act 2018, 

* ACPO Good Practice Guide for Digital Evidence,  

## Challenges Faced

Mounting E01 forensic images in Kali Linux,  Access permission issues during image mounting,  Differences between Windows and Linux Autopsy functionality,   Difficulty identifying hidden or disguised files,  Handling corrupted or incomplete forensic image files, 

## Skills Demonstrated

Digital forensic investigation,  File recovery and carving,  File signature analysis,  Partition analysis,  Hexadecimal analysis,  Evidence preservation,  Use of forensic imaging tools, Documentation and reporting

## References

**Websites:**

https://en.wikipedia.org/wiki/BMP_file_format

https://en.wikipedia.org/wiki/GIF/

https://www.autopsy.com/

https://www.veracrypt.fr/

https://www.kali.org/tools/ 

https://www.accessdata.com/products-services/forensic-toolkit-ftk 

https://www.guidancesoftware.com/.


**YouTube Resources**

Digital Forensics Investigation: Finding Evidence with Autopsy on Kali – Ethical Explorer
https://youtu.be/EqRqCXFJ-8c?si=RdHsMcKsy-p3tAiY

Additional References: 
Google AntiGravity AI



## Conclusion

This project demonstrated the practical application of digital forensic investigation techniques using industry-standard forensic tools. The investigation successfully recovered deleted and hidden artefacts, analysed file structures and signatures, and identified suspicious evidence associated with illegal activities.

The project also highlighted the importance of maintaining forensic integrity, following structured forensic procedures, and understanding file systems, partitions, and hexadecimal analysis during digital investigations.

Through this investigation, valuable practical experience was gained in forensic imaging, evidence recovery, and cybercrime analysis using both Kali Linux and Windows forensic environments.
