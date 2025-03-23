<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Post-Install Configuration</h1>

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />
After installing osTicket, it's important to perform some essential configurations to ensure your system is secure, functional, and tailored to your organization's needs.

---

<h2>🎥 Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, Post-Installation](https://www.youtube.com) 

---

<h2>🧰 Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)
- osTicket Admin Panel

---

<h2>🖥️ Operating System Used</h2>

- Windows 10 Pro (21H2)

---

<h2>🎯 Post-Install Configuration Objectives</h2>

- Rename the osTicket default admin account
- Configure support departments (e.g., IT, Billing)
- Create new help topics and assign departments
- Set up email fetching via IMAP or SMTP
- Enable and configure SLA plans and ticket filters

---

<h2>⚙️ Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/MULZ61b.png" height="80%" width="80%" alt="Rename Admin Account"/>
</p>
<p>
<strong>Step 1:</strong> Log in to the osTicket Admin Panel. Navigate to <code>Admin Panel > Agents > Staff</code>. Edit the default admin account and update the username, name, and email address to something more secure and personalized.
</p>
<br />

<p>
<img src="https://i.imgur.com/lphbLZE.png" height="80%" width="80%" alt="Configure Departments"/>
</p>
<p>
<strong>Step 2:</strong> Go to <code>Admin Panel > Staff > Departments</code>. Here, you can create new departments (such as Technical Support, Sales, or Billing) and assign department managers or team members.
</p>
<br />

<p>
<img src="https://i.imgur.com/OMtJtvw.png" height="80%" width="80%" alt="Help Topics"/>
</p>
<p>
<strong>Step 3:</strong> Navigate to <code>Admin Panel > Manage > Help Topics</code>. Create help topics such as "Password Reset" or "Hardware Request", and assign each to the appropriate department. This will help categorize incoming tickets automatically.
</p>
<br />

<p>
<img src="https://i.imgur.com/DwrEmIG.png" height="80%" width="80%" alt="Email Configuration"/>
</p>
<p>
<strong>Step 4:</strong> Set up email by going to <code>Admin Panel > Emails > Emails</code>. Add a new email and configure SMTP (for sending) and IMAP (for receiving). This allows tickets to be created by sending an email.
</p>
<br />

<p>
<img src="https://i.imgur.com/6Y09b7S.png" height="80%" width="80%" alt="SLA and Filters"/>
</p>
<p>
<strong>Step 5:</strong> Define service level agreements (SLAs) under <code>Admin Panel > Manage > SLA Plans</code> to ensure timely ticket responses. You can also use <code>Ticket Filters</code> to route and prioritize tickets automatically based on keywords or sender.
</p>

---

<h2>🔒 Security Tips</h2>

- Change the default admin username and password
- Restrict admin panel access by IP if possible
- Keep PHP, MySQL, and osTicket updated
- Back up your database regularly

---

<h2>📬 Questions or Issues?</h2>

Open an issue in this repo or comment under the YouTube video if you're stuck or have questions!

---

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
