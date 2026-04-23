# Group-Policy-and-Managing-Accounts
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

This project will showcase group policy mangement within Active Directory.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2025
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Project 1-Working with Account Lockouts
- Project 2-Enabling and Disabling Accounts with Password Reset
- Project 3-Observing Logs
- Project 4-Implmenting a Welcome Message when Users Login

<h2>Project 1</h2>

<p>
<img width="1915" height="500" alt="image" src="https://github.com/user-attachments/assets/d68c1c88-c511-4205-9a52-9a841a727fc3" /> 
</p>
<p>
Configured group policy on DC-1 to where the duration of the lockout was 30 minutes, the account lockout threshold was after 5 invaild login attempts, and the reset counter for account lockout was 10 minutes.
</p>
<br />

<p>
<img width="563" height="155" alt="image" src="https://github.com/user-attachments/assets/0b5bdb92-5ed4-407a-894e-b58744b17a26" /> <img width="411" height="538" alt="image" src="https://github.com/user-attachments/assets/c74b2b68-f2c3-4c7a-9c1c-5f1510f103f9" />
</p>
<p>
Failed to login in to Client-1 VM with account "cox.fij" after five failed attempts and account was locked out.
</p>
<br />

<p>
<img width="865" height="740" alt="image" src="https://github.com/user-attachments/assets/7cc2ab55-3e1e-4c2d-8ef9-27099727c67b" />
</p>
<p>
Unlocked the account "cox.fij" on DC-1 and was able to log back into Client-1 using the cox.fij account.
</p>
<br />

<h2>Project 2</h2>

<p>
<img width="757" height="531" alt="image" src="https://github.com/user-attachments/assets/bf0b6946-1669-4fdb-886f-6afe068cc198" /> <img width="561" height="135" alt="image" src="https://github.com/user-attachments/assets/50f5b39b-bf5a-4bb1-8b01-66cda8db73a3" />
</p>
<p>
Disabled the account "cox.fij" on DC-1.
</p>
<br />

<p>
<img width="755" height="526" alt="image" src="https://github.com/user-attachments/assets/1a6f14a7-9a8e-4055-b699-ab106c40b721" /> <img width="758" height="533" alt="image" src="https://github.com/user-attachments/assets/5c0c4889-472a-46ab-bf5c-1f9335bc7163" />
</p>
<p>
Enabled the account "cox.fij" on DC-1 and was able to log back into Client-1 using the cox.fij account with a new password.
</p>
<br />

<h2>Project 3</h2>

<p>

</p>
<p>
Enabled the account "cox.fij" on DC-1 and was able to log back into Client-1 using the cox.fij account with a new password.
</p>
<br />


