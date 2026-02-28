File Integrity Monitoring (FIM)
🎯 Objective

To monitor critical system files for unauthorized changes.

🛠 What I Did

Enabled syscheck in Wazuh

Monitored sensitive files like /etc/passwd

Modified the file to trigger detection

🚨 Result

Wazuh generated an alert when the file was modified.
 
