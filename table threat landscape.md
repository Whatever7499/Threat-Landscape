# Threat Actor Summary Table

| **Threat Actor**       | **Methods**                               | **Risks**                                               |**Mitigation** 

|-------------------------|------------------------------------------|---------------------------------------------------------|-----------------------------------------------------|

| **Nation-State Actors** | Advanced Persistent Threats (APTs)       | Compromised patient records                             | Regular security updates and patch 
management
|                         | Zero-Day Exploits                        | Espionage of telehealth data                            | Network segmentation and monitoring for abnormal behavior                     
|                         |                                          | Disruption of medication tracking                       | Threat intelligence sharing to anticipate APT activities                      

|-------------------------|------------------------------------------|---------------------------------------------------------|------------------------------------------------------|

| **Cybercriminal Groups**| Ransomware Attacks                       | Loss of access to critical applications                 | Multi-factor authentication (MFA)  

|                         | Phishing Campaigns                       | Violations of HIPAA                                     | Hardened SQL queries and penetration testing     

|                         | SQL Injection                                                                                      | Secure backups stored in isolated AWS S3 buckets 


|-------------------------|------------------------------------------|---------------------------------------------------------|------------------------------------------------------|

| **Insider Threats**     | Data Breach                              | Unauthorized access to systems                          | Role-based access control (RBAC)    

|                         | Misconfigurations                        | Tampering with secure messaging                         | Regular audits of user activities using AWS CloudTrail

|                         |                                          | Disruption of medication systems                        | Employee training on data security 


|-------------------------|------------------------------------------|---------------------------------------------------------|------------------------------------------------------|

| **Hacktivists**         | Distributed Denial of Service (DDoS)     | Downtime affecting patient care                         | Use AWS WAF (Web Application Firewall)

|                         | Defacement Attacks                       | Public embarrassment                                    | Regular vulnerability scans     

|                                                                                                                              | CDN integration to absorb traffic    


|-------------------------|------------------------------------------|---------------------------------------------------------|----------------------------------------------------|

| **Low Hackers**         | Exploit                                  | Potential data breaches                                 | Enforce strong password policies and lockout mechanisms                        
|                         | Brute Force Attacks                      | Service disruption                                      | Automated vulnerability scanning and patching       

|                                                                                                                              | Rate limiting for login attempts         

