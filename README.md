# About this Project

This project explore on method to create a backdoor and gain persistence on a compromised machine.

![a](Images/a.png)

There are several Pentesting phases, methodologies, or frameworks such as the Mitre and the Cyber kill Chain frameworks. This project focus on the fourth phase of engagement (Maintaining Access) or their equivalents like "Command and Control" for the cyber kill chain or "Persistence" for the Mitre framework.

To obtain this persistence, a backdoor is created using the SSH service. In short, two things need to be accomplished to succeed in this task: Create a user, and set the SSH server.

## Tools used in the project

|   |   |
| --- | --- |
| - Virtual box with an Ubuntu machine (linux-scavenger_linux) | - Nano text editor |
| - Linux file system | - SSH |
| - SSH server configuration | - sudoers file configuration |
| - John the Ripper | - usermod command and flags |
| - groupmod command and flags | - adduser command and flags |
| - sudo commands and flags | - su command and flags |
| - systemctl command and flags | - cat command |