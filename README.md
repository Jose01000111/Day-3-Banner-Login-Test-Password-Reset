# 🏦 Active Directory Lab — Day 3: Banner, Login Test & Password Reset

## 🛡️ I Configured the Legal Login Banner

To start Day 3, I focused on compliance by setting up a legal login banner. I logged into my domain controller (CHICAGO-DC01) as the Domain Admin and added a warning message that displays before any user logs in. The message reminds users that access is restricted to authorized personnel and that activity is monitored. After setting it, I logged out to test the change, and the banner appeared exactly as expected. ✅

## 👤 I Tested a User Login (Maria Lopez)

Once the banner was working, I verified that one of the accounts I created yesterday could successfully log in. I chose Maria Lopez from the Employees OU and signed into a domain-joined machine using her credentials.  🔐

# 🛠️ Troubleshooting: Granting RDP Access to Maria Lopez

Maria couldn’t RDP into CHICAGO-DC01. I fixed it by adding her to the Remote Desktop Users group on the server via Computer Management. Now she has RDP rights and can connect remotely as needed.


## 🔁 I Reset Maria’s Password Through the GUI

After confirming Maria could log in, I decided to test the password reset process using the GUI. I opened Active Directory Users and Computers, found her account under the correct OU, and reset her password to a new secure value.  🔄

## ✅ I Completed Day 3 Goals

With the banner configured, user login tested, and password reset confirmed, I wrapped up Day 3 feeling confident in the stability and usability of the environment. Everything is running smoothly, and I'm ready to move forward with group management and account controls tomorrow. 💪
