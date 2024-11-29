# Bash-Scripting-in-Linux

<h2>Description</h2>
In this Linux home lab, I created a bash script to back up the contents of "/Confidential" to a "/Backups-date" where date is the current date of backup. I've included an if, then, else statement depending on if the current date directory is already created at the time of backup. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux CLI</b> 

<h2>Environments Used </h2>

- <b>Linux Mint 22</b> 

<br />
<br />


Created a /Backup directory in root directory.
 
![1) Create Backups directory in root directory](https://github.com/user-attachments/assets/fe224393-d417-4a38-8110-6c03f7f4acfe)

<br />
<br />

Saved script, confirmed backup.sh makes date directory in Backups

![2) Make directory for current date inside backups](https://github.com/user-attachments/assets/ec3d001a-f80c-4928-a357-7d2059856b82)

<br />
<br />
Set expiring passwords for new users and switched users to set new password after expiry.

![3) saved script, confirmed script makes directory in Backups](https://github.com/user-attachments/assets/41924a94-2598-402b-b0a6-664f69996508)

<br />
<br />
Created new "Confidential" directory in root directory.

![4)located script and changed x permissions](https://github.com/user-attachments/assets/afb2a87b-7738-44df-983d-eb918ea1d155)

<br />
<br />
Created "confidential group", added elrich and bertram to confidential group, and set confidential group as group for "Confidential" directory.

![5) script command to copy Confidential folder into Backups](https://github.com/user-attachments/assets/bce126ad-29a4-4cce-aafa-5397545f58e1)

<br />
<br />
Set full permissions to root owner and group and zero permissions for other. 

![5 5) changed permissions to test file and echoed into it](https://github.com/user-attachments/assets/c6716c58-429a-440a-aae3-69855e55a9c8)

<br />
<br />
Confirmed proper permissions as elrich in Confidential directory by creating a test file. 

![6) tested script to copy Confidential contents into Backup date directory](https://github.com/user-attachments/assets/3359f45c-0a05-4166-b7cd-ed227fdffca2)

<br />
<br />
Confirmed proper permissions as elrich in Confidential directory by creating a test file. 

![7) If then state to create new directory](https://github.com/user-attachments/assets/d0de9af0-4f85-45df-87b4-4e969893780a)

<br />
<br />
Confirmed proper permissions as elrich in Confidential directory by creating a test file. 

![8) testing if script will overwrite if folder already exists](https://github.com/user-attachments/assets/dffcc14e-0d9e-4de6-aea1-0c331197be62)

<br />
<br />
Confirmed proper permissions as elrich in Confidential directory by creating a test file. 

![9) Forgot backslah in script ](https://github.com/user-attachments/assets/0f3cf490-2f83-4123-aeca-6e84b3aa4b4c)

<br />
<br />
Confirmed proper permissions as elrich in Confidential directory by creating a test file. 

![10 )Confirmation that script works](https://github.com/user-attachments/assets/a72b2804-f99b-4dbb-a3b9-0f6efe4d84fd)
