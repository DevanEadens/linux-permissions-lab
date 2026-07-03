Linux File Permissions Lab
Objective
Practice Linux file permission management using the command line while reinforcing the cybersecurity principle of least privilege.

Environment
Ubuntu Linux
Bash Terminal
Skills Practiced
Creating directories and files
Navigating the Linux filesystem
Viewing file permissions
Modifying permissions with chmod
Understanding numeric permission values
Applying the Principle of Least Privilege
Commands Used
mkdir permission_lab
cd permission_lab
touch secret.txt
echo "Top Secret" > secret.txt
ls -l
chmod 600 secret.txt
ls -l
chmod 400 secret.txt
ls -l
chmod 600 secret.txt
Permission Values
Permission

Meaning

600

Owner can read and write. Group and others have no access.

400

Owner can read only. Group and others have no access.

What I Learned
Linux permissions are an important security control that limits who can access or modify files. Using chmod allows administrators to implement the principle of least privilege by granting only the permissions required for a user to perform their job.

This lab reinforced how Linux protects sensitive files and demonstrated how permission changes directly affect a user’s ability to access or modify data.

Security Concepts
Least Privilege
Access Control
File Permissions
Linux Administration
Next Steps
Practice directory permissions
Explore user and group ownership with chown
Create multiple users to test access restrictions
Learn special permissions such as SUID, SGID, and Sticky Bit
