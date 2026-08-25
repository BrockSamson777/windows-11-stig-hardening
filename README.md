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


## STIG Remediation Progress

After implementing several Windows 11 STIG remediations, I performed another credentialed compliance scan using Tenable Vulnerability Management.

The rescan confirmed that multiple previously failed STIG controls were successfully remediated and now report a **Passed** status.

### Current Scan Results
- **109 Passed**
- **142 Failed**
- **12 Warnings**
- **263 Total Compliance Checks**

Examples of successfully remediated controls visible in the scan include:

- WN11-CC-000315 — Always Install with Elevated Privileges disabled
- WN11-CC-000110 — Printing over HTTP prevented
- WN11-CC-000197 — Microsoft Consumer Experiences disabled
- WN11-CC-000326 — PowerShell Script Block Logging enabled
- WN11-CC-000185 — Autorun commands prevented
- WN11-CC-000327 — PowerShell Transcription enabled
- WN11-CC-000305 — Indexing of encrypted files disabled
- WN11-CC-000252 — Windows Game Recording and Broadcasting disabled

This validation step demonstrates the remediation workflow:

**Identify Finding → Research STIG → Implement Remediation → Rescan → Verify Compliance**

<img width="1593" height="854" alt="image" src="https://github.com/user-attachments/assets/6cc88194-83cd-4ecf-bb9a-5ad8b31f18e3" />

