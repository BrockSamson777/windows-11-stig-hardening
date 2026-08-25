**[Windows 11 STIG Reference](https://stigaview.com/products/win11/latest/)**

## Remediation Workflow

1. Run a credentialed Windows 11 compliance scan using **Tenable**
2. Identify a failed STIG compliance finding
3. Record the associated **STIG ID**
4. Research the requirement using **STIG-A-View**
5. Review the:
   - Vulnerability Discussion
   - Security Requirement
   - Check Procedure
   - Fix / Remediation Guidance
6. Determine the appropriate Windows configuration and apply the remediation using:
   - PowerShell
   - Registry Editor
   - Local Group Policy
   - Local Security Policy
7. Verify the configuration manually
8. Re-run the **Tenable** compliance scan
9. Confirm the finding changes from **FAILED → PASSED**

## Initial Compliance Scan

The initial Tenable compliance scan identified multiple Windows 11 STIG findings requiring remediation.

<img width="2166" height="1261" alt="Initial Tenable Windows 11 STIG compliance scan" src="https://github.com/user-attachments/assets/8d23232d-2e96-4527-bfae-dcb1262e7f6e" />
