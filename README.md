# Digital-Forensics-Investigation-Report
This repository contains a comprehensive digital forensic investigation, analyzing disk images, network traffic, memory dumps, and mobile data. Key findings include user identification, financial pressures, personal conflicts, and unethical behavior, uncovered through forensic tools like Autopsy and Volatility.
## Folders and Contents
- **EvidenceA/**: Contains disk image analysis, focusing on file system recovery, partition mapping, and registry examination. Tools used include `img_stat`, `mmls`, `fsstat`, and `RegRipper`.
- **EvidenceB/**: Contains network traffic analysis using Wireshark to decode TCP streams and identify key communications and file transfers.
- **EvidenceC/**: Contains memory dump analysis using Volatility, recovering active processes, registry hives, and key session information.
- **EvidenceD/**: Contains mobile device analysis, including call logs, SMS messages, installed applications, and user web searches.
- **Reports/**: The final forensic report summarizing the investigation's findings and providing technical details.
- **Scripts/**: Custom scripts used during the analysis, such as for mounting disk images, cracking passwords, and file system extraction.
- **Presentations/**: A PowerPoint presentation summarizing the findings for an expert witness testimony, formatted for a non-technical audience.

## Key Findings
- **User Identification**: The subject was identified through registry entries, user accounts, and recovered documents from disk images and memory dumps.
- **Financial and Emotional Pressure**: Recovered files and documents revealed that the subject was experiencing significant financial difficulties and academic stress.
- **Unethical Behavior**: Network traffic analysis uncovered plans to engage in illicit activities, including the sale of academic information.
- **Personal Conflicts**: The investigation revealed conflicts between the subject and key individuals, contributing to emotional distress.

## Tools Used
- **Autopsy**: For disk image analysis, including file system recovery, partition mapping, and the retrieval of deleted files.
- **Volatility**: For memory dump analysis, focusing on process recovery, registry examination, and session data extraction.
- **Wireshark**: Used to analyze network traffic and decode TCP streams, revealing key communications and file transfers.
- **Fcrackzip**: For cracking password-protected zip files and recovering critical documents.
- **RegRipper**: For registry hive analysis, revealing installed programs, user activity, and system configuration.

## Forensic Methodology
The investigation followed industry-standard practices to ensure the integrity and reliability of the evidence:
- **Hashing**: Data integrity was ensured through hashing, with hashes generated before and after imaging.
- **Read-Only Mounting**: Disk images were mounted in read-only mode to prevent any modification of original data.
- **Comprehensive Documentation**: Each step of the forensic process was carefully documented to ensure transparency and reproducibility.

## Conclusion
This forensic investigation uncovered vital evidence related to the subject's financial and emotional pressures, unethical behavior, and personal conflicts. The findings were derived from in-depth analysis of disk images, memory dumps, network traffic captures, and mobile data, providing a clear narrative of the events leading to the incident.

---

### How to Use This Repository
To explore the findings:
1. **View the evidence analyses** in the `Evidence/` folder.
2. **Review the final forensic report** in the `Reports/` folder for a detailed summary of the investigation.
3. **Examine custom forensic scripts** in the `Scripts/` folder.
4. **Use the presentation** in the `Presentations/` folder to view a non-technical summary of the findings.

### How to Run the Analysis
1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Digital-Forensics-Investigation.git
