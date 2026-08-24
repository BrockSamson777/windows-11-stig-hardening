**[Windows 11 STIG Reference](https://stigaview.com/products/win11/latest/)**

For each failed Tenable compliance finding, I used the corresponding STIG ID to review the:

Vulnerability discussion
Security requirement
Check procedure
Required configuration
Remediation / fix guidance

The STIG guidance was then used to identify the appropriate Windows configuration through Group Policy, Local Security Policy, Registry Editor, or PowerShell.

Example Workflow
Tenable Compliance Scan
        ↓
Failed STIG Finding
        ↓
Identify STIG ID
        ↓
Search STIG-A-View
        ↓
Review Check / Fix Guidance
        ↓
Apply Windows Remediation
        ↓
Verify Configuration
        ↓
Run Tenable Rescan
        ↓
PASS



<img width="2166" height="1261" alt="image" src="https://github.com/user-attachments/assets/8d23232d-2e96-4527-bfae-dcb1262e7f6e" />
