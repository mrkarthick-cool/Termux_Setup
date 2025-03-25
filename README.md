# Introduction_To_Myself 

Hello visitors, I'm Karthik from Tamil Nadu 
a seasoned cybersecurity researcher with 13 years of experience in cybersecurity, ethical hacking, and cybercrime investigation

# Fresh_Termux_Setup

list of steps for a fresh Termux setup


# Step 1: Change Repository

1. Open Termux and type: `termux-change-repo`
2. Press Enter to continue.
3. Select a repository and press Enter.

# Step 2: Setup Storage

1. Type: `termux-setup-storage`
2. Press Enter to continue.
3. Grant storage permissions to Termux.

# Step 3: Update and Upgrade Packages

1. Type: `pkg update && pkg upgrade -y`
2. Press Enter to execute the command.
3. Wait for the update and upgrade process to complete.

# Step 4: Install Git

1. Type: `pkg i git`
2. Press Enter to install Git.
3. Wait for the installation to complete.

# Step 5: Install Python

1. Type: `pkg i python python2 python3`
2. Press Enter to install Python.
3. Wait for the installation to complete.

# Step 6: Install nmap whois curl php  Packages

1. Type: `pkg i nmap whois dnsutils curl wget php`
2. Press Enter to install the packages.
3. Wait for the installation to complete.

You're now ready to use Termux with Git python 

# Example use :

- Clone a repository using Git: `git clone https://github.com/user/repo.git`
- Run a Python script: `python script.py`
- Scan a network using Nmap: `nmap -sS 192.168.1.0/24`
- Perform a WHOIS lookup: `whois example.com`
- Query DNS records: `dig example.com`
- Download a file using Curl: `curl -O https://example.com/file.txt`
- Download a file using Wget: `wget https://example.com/file.txt`
- Run a PHP script: `php script.php`
