<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

<h1 align="center">osTicket - Post-Install Configuration</h1>

<p align="center">This guide outlines the post-installation configuration of osTicket, including setting up roles, users, departments, teams, and help topics for an efficient help desk system.</p>

<h2>🌐Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>💻Operating Systems Used</h2>
<ul>
  <li>Windows 10 Pro (21H2)</li>
</ul>

<h2>📝Post-Install Configuration Objectives</h2>
<ul>
  <li>Login to the osTicket Admin Panel</li>
  <li>Configure Roles</li>
  <li>Configure Departments</li>
  <li>Configure Teams</li>
  <li>Configure Help Topics</li>
</ul>

<h2>🚀Configuration Steps</h2>

<details>
  <summary><b>Roles</b></summary>
  <p>Roles define the permissions and privileges assigned to staff members. Each role determines the actions a staff member can perform within a department.</p>
  <ol>
    <li>Navigate to <b>Admin Panel -> Agents -> Roles</b>.</li>
    <li>Create a new role named <b>Supreme Admin</b> and assign it full permissions.</li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/1fea4e97-e38a-4135-82b0-1f1b7808513a" alt="Roles Configuration" width="70%" />
  </p>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/7176787e-1a2f-45d6-89b0-996e8cee1d69" alt="Add New Role" width="70%" />
  </p>
</details>

<hr>

<details>
  <summary><b>Departments</b></summary>
  <p>Departments are essential for routing tickets within the help desk. Each department can have customized settings.</p>
  <ol>
    <li>Navigate to <b>Admin Panel -> Agents -> Departments</b>.</li>
    <li>Create a department named <b>SysAdmins</b>.</li>
    <li>Leave default settings as-is and review available options.</li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/d00cb26a-8ec8-4a8e-aae6-b23dd232dfc6" alt="Departments" width="70%" />
  </p>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/315b3184-22e2-46e2-bc42-87c2b979167f" alt="Departments Settings" width="70%" />
  </p>
</details>

<hr>

<details>
  <summary><b>Teams</b></summary>
  <p>Teams allow grouping agents from different departments to handle specific issues or user requests.</p>
  <ol>
    <li>Navigate to <b>Admin Panel -> Agents -> Teams</b>.</li>
    <li>Create a team named <b>Online Banking</b>.</li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/ab806c99-0aac-4e8f-9222-8659e4df2399" alt="Teams Configuration" width="70%" />
  </p>
</details>

<hr>

<details>
  <summary><b>Agents</b></summary>
  <p>Agents are responsible for resolving tickets. Assign them a primary department and role, with extended access to other departments if needed.</p>
  <ol>
    <li>Navigate to <b>Admin Panel -> Agents -> Add New</b>.</li>
    <li>Add agents <b>Jane</b> and <b>John</b>.</li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/ab806c99-0aac-4e8f-9222-8659e4df2399" alt="Add Agent" width="70%" />
  </p>
</details>

<hr>

<details>
  <summary><b>Users</b></summary>
  <p>Users (customers) can create accounts to log in, submit tickets, and check ticket statuses.</p>
  <ol>
    <li>Navigate to <b>Agent Panel -> Users -> Add New</b>.</li>
    <li>Add a user named <b>Karen</b>.</li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/d6c37642-cc49-4b58-a80a-138ddf161b4d" alt="Add User" width="70%" />
  </p>
</details>

<hr>

<details>
  <summary><b>SLA (Service Level Agreements)</b></summary>
  <p>SLA Plans define the expected time frame for resolving tickets based on their severity.</p>
  <ol>
    <li>Navigate to <b>Admin Panel -> Manage -> SLA</b>.</li>
    <li>Create SLA plans:
      <ul>
        <li><b>Sev-A:</b> 1 hour, 24/7</li>
        <li><b>Sev-B:</b> 4 hours, 24/7</li>
        <li><b>Sev-C:</b> 8 hours, business hours</li>
      </ul>
    </li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/023f2d47-8b40-4b2c-aa7d-e76b2a3a3e58" alt="SLA Configuration" width="70%" />
  </p>
</details>

<hr>

<details>
  <summary><b>Help Topics</b></summary>
  <p>Help Topics organize ticket submissions for quicker assignment and resolution.</p>
  <ol>
    <li>Navigate to <b>Admin Panel -> Manage -> Help Topics</b>.</li>
    <li>Create topics:
      <ul>
        <li>Business Critical Outage</li>
        <li>Personal Computer Issues</li>
        <li>Equipment Request</li>
        <li>Password Reset</li>
        <li>Other</li>
      </ul>
    </li>
  </ol>
  <p align="center">
    <img src="https://github.com/user-attachments/assets/de44dc0c-17a1-4102-9947-1b855a11efa6" alt="Help Topics" width="70%" />
  </p>
</details>

<hr>

<h2>Summary</h2>
<p>osTicket’s post-install configuration is a straightforward process that transforms a basic installation into a fully functional help desk system. By setting up roles, departments, teams, and help topics, your organization can efficiently manage tickets, prioritize tasks, and enhance customer satisfaction.</p>
