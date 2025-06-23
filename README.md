# Network Reconnaissance – Task 1

## 🎯 Objective
In this task, I learned to discover open ports on devices in my local network using Nmap.

---

## 🔧 Tools Used
- Nmap (installed using the official website)
- Kali Linux VM on VirtualBox
- GitHub for version control and documentation

---

## 🧭 Steps Followed
1. Installed Nmap on my Kali Linux VM.
2. Scanned the local network (`nmap -sS 192.168.130.0/24`) to discover live hosts and their open ports.
3. Saved the scan results to a file.
4. Encountered issues with guest additions and file sharing; solved by using the shared folder feature.
5. Uploaded the `nmap` results and screenshots to GitHub.

---

## 🖼️ Screenshots
| Screenshot | Description |
|------------|-------------|
| ![Scan Output](latha/task-1-1.jpg) | Nmap scan output showing open ports |
| ![Scan Summary](latha/task-1-2.jpg) | Nmap scan summary for 192.168.130.x network |

*(You can add more screenshots as needed)*

---

## 🐛 Errors Faced and Solutions
| Error | Solution |
|-------|------------|
| `Drag and drop failed` | Installed `virtualbox-guest-utils` and enabled shared folders |
| `Access denied for SMB client` | Configured proper credentials and enabled file and printer sharing on host Windows |
| `Authentication failed for GitHub` | Generated a Personal Access Token (PAT) and used it instead of password |

---

## ✅ Conclusion
This task gave me hands-on practice in:
- Reconnaissance and port scanning basics
- Configuring a VM properly for file sharing
- Managing a GitHub repository with version control

