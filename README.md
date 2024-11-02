# Add and manage users with Linux commands

## Objective

This lab aims to provide hands-on experience in managing user accounts on a Linux system. By using commands like `useradd`, `usermod`, `userdel`, and `chown`, users will learn how to add, modify, and delete users and groups. This knowledge is critical for maintaining system security and ensuring appropriate access controls.

## Project description

This project focuses on user management in a Linux environment. By leveraging commands like `useradd`, `usermod`, `userdel`, and `chown`, users can effectively add, modify, and delete user accounts, as well as manage file ownership and permissions. This is crucial for maintaining system security and ensuring that only authorized individuals have access to sensitive resources.

## Skills Learned

* **User Management:** Understanding how to add, modify, and delete users using commands like `useradd`, `usermod`, and `userdel`.
* **Group Management:** Assigning users to groups to control access permissions.
* **File Ownership and Permissions:** Using the `chown` command to change file ownership and permissions.
* **Linux Terminal Usage:** Effectively navigating the Linux terminal and executing commands with `sudo` for elevated privileges.
* **Security Best Practices:** Recognizing the importance of secure user management and the potential risks associated with improper user access.

## Tools Used

* **Linux Terminal:** The primary tool used to interact with the Linux system and execute commands.
* **sudo:** A command that allows users to execute commands with root privileges, necessary for user management tasks.
* **useradd:** A command used to create new user accounts on a Linux system.
* **usermod:** A command used to modify user accounts, including changing passwords, groups, and home directories.
* **userdel:** A command used to delete user accounts from the system.
* **chown:** A command used to change the owner and group of a file or directory.

## Steps
1. Add a new user

   1. A new employee has joined the Research department. In this task, you must add them to the system. The username assigned to them is researcher9.
   2. Write a command to add a user called researcher9 to the system.
   3. Next, you need to add the new user to the research_team group.
   4. Use the usermod command and -g option to add researcher9 to the research_team group as their primary group.
      
2. Assign file ownership

   1. The new employee, researcher9, will take responsibility for project_r. In this task, you must make them the owner of the project_r.txt file.
   2. The project_r.txt file is located in the /home/researcher2/projects directory, and owned by the researcher2 user.
   3. Use the chown command to make researcher9 the owner of /home/researcher2/projects/project_r.txt.
      
3. Add the user to a secondary group

   1. A couple of months later, this employee's role at the organization has changed, and they are working in both the Research and the Sales departments.
   2. In this task, you must add researcher9 to a secondary group (sales_team). Their primary group is still research_team.
   3. Use the usermod command with the -a and -G options to add researcher9 to the sales_team group as a secondary group.
      
4. Delete a user

   1. A year later, researcher9, decided to leave the company. In this task, you must remove them from the system.
   2. Run a command to delete researcher9 from the system
   3. This command will output the following message:
      * Userdel: Group researcher9 not removed because it is not the primary group of user researcher9.
   4. Run a command to delete the researcher9 group that is no longer required
  <br>

<![manage users in Linux](https://github.com/user-attachments/assets/f67cd1a5-20a0-4d18-b07a-34f59e21072b)br>

### Summary

This lab provided hands-on experience in managing user accounts on a Linux system. By using commands like `useradd`, `usermod`, `userdel`, and `chown`, users can effectively add, modify, and delete user accounts, as well as manage file permissions. These skills are crucial for system administrators and security professionals to maintain system security and control access to resources.
