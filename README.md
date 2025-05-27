# ORACLE VIRTUAL BOX & ACTIVE DIRECTORY 

![image](https://github.com/user-attachments/assets/d341aa27-38e2-4010-a238-9fbbd122516b)


## LAB OVERVIEW

This lab simulates a basic Windows domain environment using Oracle VirtualBox on macOS. It includes the setup of a Widows Server 2019 Domain Controller and a Windows 10 client, and demonstrates essential network services such as Active Directory, DNS, DHCP, and NAT configuration.

## TOPOLOGY

![image](https://github.com/user-attachments/assets/b08d431a-8764-43bd-aec9-0df5c69c96bc)


<h2>SOFTWARE</h2>

- Oracle VirtualBox (hosted on macOS)
- Oracle VirtualBox Essentials
- Windows Server 2019 ISO
- Windows 10 ISO

<h2>OBJECTIVES</h2>

1. Install and configure Oracle VirtualBox on MacOS to host virtual machines.
2. Create a Windows Server 2019 VM as a domain controller.
3. Create a Windows 10 VM as a domain-joined client.
4. Configure internal networking, NAT, DHCP, and DNS to simulate an enterprise environment
5. Use a PowerShell scripting to automate the creation of 1,000 in Active Directory user accounts
6. Verify client connectivity using "ipconfig" and "ping" from the Windows 10 Command Line
7. Confirm domain functionality by logging into the client VM with a domain user account created via script
