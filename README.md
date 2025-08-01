# 🏦 Active Directory Lab — Day 3: Banner, Login Test & Password Reset

## 🛡️ I Configured the Legal Login Banner

To start Day 3, I focused on compliance by setting up a legal login banner. I logged into my domain controller (CHICAGO-DC01) as the Domain Admin and added a warning message that displays before any user logs in. The message reminds users that access is restricted to authorized personnel and that activity is monitored. After setting it, I logged out to test the change, and the banner appeared exactly as expected. ✅

<img width="1343" height="519" alt="2n8lh7p" src="https://github.com/user-attachments/assets/283a923e-ca0b-482b-bed0-057e26283b51" />

---

<img width="851" height="314" alt="fNLKIaP" src="https://github.com/user-attachments/assets/267a2ce3-7954-44d2-a5b5-511619c26850" />

## 👤 I Tested a User Login (Maria Lopez)

Once the banner was working, I verified that one of the accounts I created yesterday could successfully log in. I chose Maria Lopez from the Employees OU and signed into a domain-joined machine using her credentials.  🔐

# 🛠️ Troubleshooting: Granting RDP Access to Maria Lopez

Maria couldn’t RDP into CHICAGO-DC01. I fixed it by adding her to the Remote Desktop Users group on the server via Computer Management. Now she has RDP rights and can connect remotely as needed.

<img width="902" height="511" alt="H4iPw88" src="https://github.com/user-attachments/assets/ee66e21e-551d-4513-b174-83655498b476" />

## 🔁 I Reset Maria’s Password Through the GUI

After confirming Maria could log in, I decided to test the password reset process using the GUI. I opened Active Directory Users and Computers, found her account under the correct OU, and reset her password to a new secure value.  🔄

<img width="909" height="491" alt="milvnBn" src="https://github.com/user-attachments/assets/4542e7fb-c65d-47e0-ab62-0b05cd85a543" />

## ✅ I Completed Day 3 Goals

With the banner configured, user login tested, and password reset confirmed, I wrapped up Day 3 feeling confident in the stability and usability of the environment. Everything is running smoothly, and I'm ready to move forward with group management and account controls tomorrow. 💪
