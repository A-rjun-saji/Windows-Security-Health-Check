# Windows-Security-Health-Check
 A PowerShell script for performing comprehensive security health checks on Windows systems


## Objective
This PowerShell script is designed to perform a comprehensive security health check on Windows systems. It gathers crucial security-related information and generates a detailed report that can be used for auditing and improving system security.

## Features
- **Admin Users**: Lists all users with administrative rights.
- **Running Processes**: Shows currently running processes, including their IDs, CPU usage, and start times.
- **Firewall Status**: Checks the status of firewall profiles to ensure they are properly configured.
- **Windows Update Status**: Retrieves recent Windows updates to confirm that the system is up to date.
- **Windows Defender Status**: Provides the current status of Windows Defender, including real-time protection and the last update time of antivirus signatures.
- **Recent Security Events**: Lists recent security events to help identify potential security incidents.
- **Password Policy**: Checks the system’s password policy to ensure it meets security standards.
- **Disk Encryption Status**: Verifies the encryption status of disks using BitLocker.
- **Unused Services**: Identifies services that are running but should be disabled, which could pose a security risk.

## Usage Instructions
1. **Clone or Download**: Clone the repository or download the script file to your local machine.
2. **Open PowerShell**: Open PowerShell as Administrator.
3. **Navigate to Script Directory**: Change to the directory where the script is located:
   ```powershell
   cd path\to\script\directory
Here’s a revised version of the sentence:

---

**Remember to update the file path in your script before execution. Modify the file path within the code to ensure it saves to the correct location.**

---
Requirements
PowerShell 5.1 or higher
Administrative privileges on the Windows system
