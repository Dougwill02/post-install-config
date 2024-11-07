# post-install-config

<p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
<p>This guide walks you through the essential post-installation configuration of osTicket, an open-source helpdesk ticketing system.</p>

<h2>Environments & Technologies Used</h2>
<ul>
    <li>Microsoft Azure (Virtual Machines/Compute)</li>
    <li>Remote Desktop</li>
    <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems</h2>
<ul>
    <li>Windows 10 (21H2)</li>
</ul>

<h2>Post-Installation Configuration Objectives</h2>
<p>After installing osTicket, complete the following steps to ensure the system is properly set up:</p>
<ul>
    <li><strong>Configure Email Settings:</strong> Set up email integration for ticketing and notifications.</li>
    <li><strong>Set Up Ticket Templates:</strong> Customize email and ticket response templates.</li>
    <li><strong>Configure User Roles & Permissions:</strong> Define user roles and restrict access where necessary.</li>
    <li><strong>Set Up SLAs:</strong> Define service level agreements for response and resolution times.</li>
    <li><strong>Backup Configuration:</strong> Automate backups to safeguard your data.</li>
</ul>

<h2>Configuration Steps</h2>

<h3>1. Database Configuration</h3>
<p>Ensure osTicket is properly connected to your database. During the installation, you will be asked for your database server details (hostname, username, and password). This step is crucial for the system to function correctly.</p>

<h3>2. Email Integration</h3>
<p>Go to the <strong>Admin Panel > Emails</strong> section and configure your email integration. You need to specify your mail server (SMTP for outgoing, and POP3/IMAP for incoming). This allows osTicket to send and receive ticket notifications.</p>

<h3>3. Customizing Help Topics & Departments</h3>
<p>Help topics allow users to categorize their tickets when submitting them. Create and assign help topics to different departments. Go to <strong>Admin Panel > Manage > Help Topics</strong> to set them up.</p>

<h3>4. Role & Permission Setup</h3>
<p>Control who can access and modify specific areas of the system by configuring user roles and permissions. In <strong>Admin Panel > Manage > Roles</strong>, create roles such as Admin, Agent, and End-User, and set specific permissions for each role.</p>

<h3>5. Set Up SLAs (Service Level Agreements)</h3>
<p>SLAs define the response and resolution time expectations for different ticket priorities. Navigate to <strong>Admin Panel > Manage > SLAs</strong> to configure these settings based on your organization's requirements.</p>

<h3>6. Backup Configuration</h3>
<p>Set up automated backups to ensure the safety of your data. You can use tools like Azure Backup or third-party solutions to schedule regular backups of your osTicket installation and database.</p>

<h2>Security Best Practices</h2>
<ul>
    <li>Regularly update osTicket to the latest version to apply security patches and improvements.</li>
    <li>Enable SSL (HTTPS) to secure communication between users and your osTicket system.</li>
    <li>Review user roles and permissions regularly to prevent unauthorized access.</li>
    <li>Consider implementing two-factor authentication (2FA) for administrators and agents for added security.</li>
</ul>

<h2>Conclusion</h2>
<p>By following these steps, your osTicket installation will be fully configured and ready to handle support tickets. Ensure to perform regular maintenance by checking for updates and performing backups to keep the system secure and efficient.</p>
