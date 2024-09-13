

# Windows-Security-Health-Check

A PowerShell script for performing comprehensive security health checks on Windows systems.

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

## **Usage Instructions**

1. **Clone or Download the Repository**

   - **Cloning the Repository**: Cloning creates a local copy of the entire repository, including all versions and history. This is useful for development or frequent updates. To clone the repository, open a terminal or Git Bash and run:
     ```bash
     git clone https://github.com/arjunsaji618/Windows-Security-Health-Check.git
     ```

   - **Downloading the Script File**: If you prefer not to use Git, you can download the script file directly from the GitHub repository. Navigate to the [repository page](https://github.com/arjunsaji618/Windows-Security-Health-Check), click on `Code`, then `Download ZIP`. Extract the ZIP file to your preferred directory.

2. **Open PowerShell as Administrator**

   - **Windows Search**: Click on the **Start** menu or press the **Windows** key, type `PowerShell`, and right-click on **Windows PowerShell** or **Windows Terminal** (if installed).
   - **Run as Administrator**: Select **Run as administrator** from the context menu to open PowerShell with elevated privileges. This is necessary because the script performs administrative tasks.

3. **Navigate to Script Directory**

   - **Change Directory**: Use the `cd` command to change to the directory where you have saved or cloned the repository. Replace `path\to\script\directory` with the actual path to the directory where the script file is located. For example:
     ```powershell
     cd C:\Users\YourUsername\Documents\Windows-Security-Health-Check
     ```

   - **Verify Script Location**: Ensure you are in the correct directory by listing the files with:
     ```powershell
     dir
     ```
     You should see `SecurityHealthCheck.ps1` among the files listed.

4. **Run the Script**

   - **Execute the Script**: Run the script by typing the following command in PowerShell:
     ```powershell
     .\SecurityHealthCheck.ps1
     ```
     The `.\` specifies the current directory, and `SecurityHealthCheck.ps1` is the name of your script file.

   - **Review Output**: The script will execute and display output directly in the PowerShell window. It will generate a security health check report based on the system’s configuration.

5. **Review the Report**

   - **Check Output File**: By default, the script generates a report file named `SecurityHealthCheckReport.txt` in the same directory where the script is run. Open this file with a text editor (e.g., Notepad) to review the results.

   - **Analyze Results**: The report will include details about administrative users, running processes, firewall status, and other security-related information. Use this report to assess the security health of your system.

6. **Troubleshooting and Additional Information**

   - **Permissions**: Ensure you have the necessary administrative privileges to run the script. Some commands in the script require elevated rights.
   - **Script Errors**: If the script encounters errors, review the error messages for clues. Common issues might include missing permissions or incorrect paths.

   - **Updating the Script**: To incorporate any updates or improvements to the script, repeat the cloning or downloading process and replace the old script with the new version.

   **Remember to update the file path in your script before execution. Modify the file path within the code to ensure it saves to the correct location.**

## Requirements

- PowerShell 5.1 or higher
- Administrative privileges on the Windows system

