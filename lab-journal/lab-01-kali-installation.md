Lab 01 - Kali Linux Installation and Initial Configuration

Objective

Install Kali Linux in VirtualBox and verify basic network connectivity.

Environment

- Host OS: Windows
- Virtualization Platform: VirtualBox
- Guest OS: Kali Linux

Commands Executed

sudo apt update
sudo apt upgrade -y
sudo apt install -y net-tools curl git
ip a


Results

The system updated successfully.

Network connectivity was confirmed.

The Kali Linux VM received the following IPv4 address:

10.0.2.15


Network mode:

NAT

Lessons Learned

- How to update Kali Linux.
- How to install packages.
- How to identify IP addresses using `ip a`.
- Understanding VirtualBox NAT networking.

Next Steps

- Create a Windows VM.
- Install Sysmon.
- Begin log analysis activities.
