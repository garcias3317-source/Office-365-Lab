
# ☁️ Microsoft 365 Administration & Data Recovery Lab
### [Sergio Garcia | IT Portfolio](github.com/garcias3317-source)

## 📝 Description
This project demonstrates my proficiency in  using the **Microsoft 365 Admin Center**. I performed end-to-end administrative tasks including user lifecycle management, Shared Mailboxes/Distribution Lists, and critical data recovery via OneDrive for Business administration.

---

## 🛠️ Project Walk-through

### 1. User Provisioning & Role-Based Access Control
I created new users  and implemented **Role-Based Access Control**. Instead of granting full Global Admin rights, I assigned the **Helpdesk Administrator** role to follow the "Principle of Least Privilege," allowing for password resets and service ticket management without compromising security

<p align="center">
<img src="https://imgur.com/aLyoLW2.png" height="80%" width="80%" alt="User Creation and Role Assignment"/>
</p>

<p align="center">
<img src="https://imgur.com/kX2yHMF.png" height="80%" width="80%" alt="User Creation and Role Assignment"/>
</p>

### 2. IT Support Shared Mailbox & Delegation
To streamline department communications, I configured a **Shared Mailbox** for the "IT Support" team.
* **Configuration:** Created the mailbox `itsupport@company5255.onmicrosoft.com` and assigned `Full Access` and `Send As` permissions to team members.
* **Testing:** Verified members could successfully add the shared mailbox to their Outlook Web App and send/receive emails on behalf of the IT department.

<p align="center">
<img src="https://imgur.com/oC8V6iW.png" height="80%" width="80%" alt="Shared Mailbox Setup and Outlook Integration"/>
</p>

<p align="center">
<img src="https://imgur.com/Yvi4Rnw.png" height="80%" width="80%" alt="Shared Mailbox Setup and Outlook Integration"/>
</p>

<p align="center">
<img src="https://imgur.com/muQfL1x.png" height="80%" width="80%" alt="Shared Mailbox Setup and Outlook Integration"/>
</p>

### 3. Distribution Group Deployment
I created an organization-wide **Distribution List** for the HR department. This enables broadcast "one-to-many" communication. I managed the membership list (Alex, Sally, Sarah, and Sergio) and finalized the group settings within the Exchange Admin Center.

<p align="center">
<img src="https://imgur.com/krUkK1s.png" height="80%" width="80%" alt="Distribution List Configuration"/>
</p>

### 4. Critical Data Recovery Scenario 
I simulated a  support scenario where a user (`bob hardy`) deleted a critical file and accidentally emptied their Recycle Bin.

* **The Problem:** The file was removed from the standard user-facing Recycle Bin, appearing "permanently" deleted to the end-user.
* **The Admin Solution:** I accessed the **M365 Admin Center**, navigated to Bob's user profile, and generated a management link for his OneDrive files.
* **The Recovery:** I accessed the **Second-stage recycle bin**.I then successfully restored the file to its original location.

<p align="center"
<img src="https://imgur.com/mYUWuqm.png" height="70%" width="70%" alt="File Deletion Simulation"/>
<br />
<img src="https://imgur.com/wc5eGa6.png" height="70%" width="70%" alt="Admin OneDrive Access"/>
<br />
<img src="https://imgur.com/xsGOHXE.png" height="70%" width="70%" alt="Second Stage Recovery"/>
</p>

---

