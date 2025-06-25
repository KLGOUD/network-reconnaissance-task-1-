# 🔍 Network Reconnaissance – Task 1

## 🎯 Objective
In this task, I practiced network reconnaissance by discovering live hosts and open ports on devices in a local network.  
The goal was to gain hands-on experience with Nmap and understand basic scanning techniques.

---

## 🔧 Tools Used
- 🧰 Nmap
- 🧰 Kali Linux VM on VirtualBox
- 🧰 GitHub for version control and documentation

---

## 🧭 Steps Followed
1. Installed Nmap on my Kali Linux VM.
2. Performed a local network scan (`nmap -sS <target_subnet>`) to identify live hosts and their open ports.
3. Saved the scan results into a file.
4. Encountered file sharing issues between VM and host — fixed by setting up VirtualBox Guest Additions and shared folders.
5. Uploaded scan results and other relevant files to this GitHub repo.
---

## 🐛 Issues Faced & Solutions
| Issue | Solution |
|--------|------------|
| Drag-and-drop failed between VM and host | Installed VirtualBox Guest Additions and enabled shared folders |
| SMB client access denied | Enabled file and printer sharing on Windows and configured credentials properly |
| GitHub authentication failed | Generated a Personal Access Token and used it for commits instead of a password |

---

## ✅ What I Learned
- ✅ Basic Nmap scanning techniques (`-sS`, host discovery, etc.)
- ✅ Setting up VM environments properly for file sharing
- ✅ Creating GitHub repos and pushing files securely with a PAT
- ✅ Practicing good privacy habits like avoiding sharing IPs or other personal data

---

## 🧠 Conclusion
This hands-on task strengthened my understanding of network reconnaissance and helped me appreciate the importance of privacy and security in every phase of a project.


