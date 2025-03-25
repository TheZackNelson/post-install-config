<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Post-Install Configuration</h1>

This tutorial outlines the essential post-installation configurations for the open-source help desk ticketing system, osTicket. After installation, we will configure roles, departments, teams, agents, users, SLAs, and help topics to simulate a real help desk environment.

---

<h2>🎥 Video Demonstration</h2>

- ### [YouTube: osTicket Post-Install Configuration Walkthrough](https://www.youtube.com) *(Coming Soon)*

---

<h2>🧰 Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- osTicket Admin & Agent Portals
- Web Browser (Google Chrome or Edge)

---

<h2>🖥️ Operating System Used</h2>

- Windows 10 Pro (21H2)

---

<h2>🔐 Accessing the Panels</h2>

- **Admin / Analyst Login Page:**  
  `http://localhost/osTicket/scp/login.php`

- **End Users (Customer) Ticket Page:**  
  `http://localhost/osTicket`

- osTicket separates the **Admin Panel** (for configuration and setup) and the **Agent Panel** (for ticket handling and support work). You’ll be working in both.

---

<h2>🛠️ Configuration Steps</h2>

### ✅ Step 1: Configure Roles
> Roles control what permissions agents have within osTicket.

- Navigate to:  
  `Admin Panel > Agents > Roles`
- Create a role:  
  **Name:** `Supreme Admin`  
  **Permissions:** All Access

---

### ✅ Step 2: Configure Departments
> Departments determine what tickets an agent can see.

- Navigate to:  
  `Admin Panel > Agents > Departments`
- Create departments like:
  - `Support`
  - `SysAdmins`
  - `Networking`

---

### ✅ Step 3: Configure Teams (Cross-Department Collaboration)
> Teams let you group agents from different departments to work together.

- Navigate to:  
  `Admin Panel > Agents > Teams`
- Create a team:  
  **Name:** `Online Banking`  
  **Members:** Pull agents from multiple departments

---

### ✅ Step 4: Adjust User Settings
> Control whether unregistered users can submit tickets.

- Navigate to:  
  `Admin Panel > Settings > User Settings`
- **UNCHECK**: "Require registration and login to create tickets"  
  (Allow anyone to create tickets without an account)

---

### ✅ Step 5: Add Agents (Internal Staff)
> Agents are the people who will respond to tickets.

- Navigate to:  
  `Admin Panel > Agents > Add New`
- Create agents like:
  - `Jane` – Department: `SysAdmins`
  - `John` – Department: `Support`

---

### ✅ Step 6: Add Users (External Customers)
> Users are the people submitting tickets for help.

- Navigate to:  
  `Agent Panel > Users > Add New`
- Add users like:
  - `Karen`
  - `Ken`

---

### ✅ Step 7: Configure SLA Plans
> SLA plans define response expectations based on issue severity.

- Navigate to:  
  `Admin Panel > Manage > SLA`
- Create SLA Plans:
  - **Sev-A** – Grace Period: `1 hour` | Schedule: `24/7`
  - **Sev-B** – Grace Period: `4 hours` | Schedule: `24/7`
  - **Sev-C** – Grace Period: `8 hours` | Schedule: `Business Hours`

---

### ✅ Step 8: Define Help Topics
> Help topics guide users when submitting a ticket.

- Navigate to:  
  `Admin Panel > Manage > Help Topics`
- Add topics like:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other

---

<h2>✅ Final Checklist</h2>

- [x] Admins and agents created  
- [x] Users added  
- [x] Departments, Teams, and Roles defined  
- [x] SLA and Help Topics configured  
- [x] Verified ability to submit and respond to tickets  

---

<h2>📬 Questions or Issues?</h2>

Feel free to open an issue in this repo or drop a comment under the video walkthrough. You're on your way to running a fully functional help desk!

---
