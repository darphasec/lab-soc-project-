# lab-soc-project-by-adriano-ferrao
# SOC Lab Project    Using Wazuh to detect RDP brute force attacks, outdated packages, and vulnerabilities. Includes Linux basics: user management, permissions, and system hardening for SOC operations.  
# IS HUTING TIME........ 

This project demonstrates a hands-on approach to creating a Security Operations Center (SOC) lab environment using **Wazuh** with a focus on monitoring and securing **Windows systems**. It covers RDP brute force detection, outdated package and vulnerability identification, and exploring Windows Internals for system hardening and forensic analysis.  

 Features  
- RDP Brute Force Detection
  - Configure Wazuh to monitor Windows Event Logs for brute force attack patterns on Remote Desktop Protocol (RDP).  
  - Generate custom alerts to identify unauthorized access attempts.  

- Vulnerability Detection 
  - Identify outdated or vulnerable Windows software using Wazuh's CVE detection capabilities.  
  - Analyze and remediate security issues effectively.  

- Windows Internals and Administration
  - Explore Windows Internals, including processes, threads, memory management, and registry operations.  
  - Strengthen Windows system administration skills, including user account management and permissions configuration.  

Skills Developed  
- Incident detection and response in Windows environments.  
- Hands-on vulnerability management on Windows systems.  
- Deep understanding of Windows Internals for SOC and forensic analysis.  

Technologies Used  
- Wazuh: Open-source security platform for monitoring and threat detection.  
- Windows OS: For RDP attack simulations, software vulnerability testing, and administrative tasks.  
- Windows Event Viewer: To analyze logs and monitor system activities.  


soc-lab-project/  
│  
├── configs/                 # Wazuh configuration files for Windows  
├── windows-basics/          # Windows Internals and administration exercises  
├── logs/                    # Sample Windows logs for testing  
├── README.md                # Project description  
└── LICENSE                  # License details  

Getting Started  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/soc-lab-project.git  
   cd soc-lab-project  
