<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (Supreme Admin), and roles with varying access
- Configure Departments (System Administrators, Support)
- Configure Teams (Level I Support, Level II Support)
- Allow anyone to create tickets without requiring registration
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA (Service Level Agreements)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/pvc5U7M.png" height="80%" width="80%" alt="Create Roles"/>
  <img src="https://i.imgur.com/rr101kB.png" height="80%" width="80%" alt="Create Roles"/>
</p>
<p>
Create roles with varying permissions for different job titles such as System Administrators, Ticketing Queue Manager, and Help Desk Analysts. 
</p>
<br />
<br />
<br />
<br />

<p>
<img src="https://i.imgur.com/gVdRlkx.png" height="80%" width="80%" alt="Create Departments"/>
</p>
<p>
Configure the different departments for which the different IT personnel would belong to. 
</p>
<br />
<br />
<br />
<br />

<p>
<img src="https://imgur.com/2MR5KGr.png" height="80%" width="80%" alt="Teams"/>
</p>
<p>
Created different teams such as Level I, and Level II support for tickets that require escalation and higher level attention.
</p>
<br />
<br />
<br />
<br />

<p>
<img src="https://imgur.com/EeiRYor.png" height="80%" width="80%" alt="Settings"/>
</p>
<p>
Change administration settings to allow users to create tickets without going through registration or login. 
</p>
<br />
<br />
<br />
<br />

<p>
<img src="https://imgur.com/eqUBOSU.png" height="80%" width="80%" alt="Agents"/>
  <img src="https://imgur.com/VLrqTe2.png" height="80%" width="80%" alt="Agents"/>
  <img src="https://imgur.com/DBMAXzJ.png" height="80%" width="80%" alt="Agents"/>
</p>
<p>
Configure Agents (workers) with different roles. Also add Users (customers). 
</p>
<br />
<br />
<br />
<br />

<p>
<img src="https://imgur.com/D5Hnp4A.png" height="80%" width="80%" alt="SLA"/>
</p>
<p>
Configure Service Level Agreements. Sev-A (business critical events) with 1hr grace period with 24/7 support availability. Sev-B (moderate impact events) with 4hr grace period also 24/7. Sev-C (general support inquries) 8hr grace period with support available only during normal business hours Mon-Fri 9am-5pm. 
</p>
<br />
<br />
<br />
<br />

<p>
<img src="https://imgur.com/I6TSQYr.png" height="80%" width="80%" alt="Help Topics"/>
</p>
<p>
Configure different Help Topics which users can initially categorize for support. This along with SLA can later be modified by a Queue Manager for proper ticket prioritization for Help Desk Analysts. 
</p>
<br />
<br />
<br />
<br />
