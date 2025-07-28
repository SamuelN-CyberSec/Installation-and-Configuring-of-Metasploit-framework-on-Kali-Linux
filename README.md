# Installation-and-Configuring-of-Metasploit-framework-on-Kali-Linux
Metasploit is a framework used for penetration testing, vulnerability validation and exploit development. In this project I will demonstrate installation and configuring of Metasploit framework on Kali Linux 

# Objectives
-Install Metasploit framework  
-Start Metasploit
-Check if PostgreSQL is connected ( Metasploit database) 
-Start Metasploit database 
-Start Metasploit console

# Tools Used
-Kali Linux 
-VMware 


# Steps
- apt install Metasploit-framework(to install Metasploit framework Kali Linux)
- systemctl status PostgreSQL
- msfconsole (to start Metasploit framework)
- msfdb init (to start Metasploit framework database)
- db_connect -y/usr/share/metasploit-famework/config/databse.yml)( to connected the database manually to the console if not connected)
- db_status (to check the status of database if connected)


## Key Findings
- Can be seen in the screenshot attached
- <img width="554" height="283" alt="Installaing  Metasploit" src="https://github.com/user-attachments/assets/94089507-0574-425f-a219-35768c158aec" />
<img width="548" height="335" alt="Starting Metasploit Framwork Database" src="https://github.com/user-attachments/assets/0dcd0734-23fd-4a3e-81b2-03fbeeba3428" />
<img width="541" height="341" alt="Starting Metasploit Framework Console" src="https://github.com/user-attachments/assets/9e1e68be-7dc9-4345-9431-71a7572dc226" />
<img width="533" height="243" alt="Database Status on Metasploit framework console" src="https://github.com/user-attachments/assets/7db3e3a9-196f-4988-a58c-24109e682031" />


 

