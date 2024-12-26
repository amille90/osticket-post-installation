<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation</h1>
This project tutorial explains how to configure various compartments within the osTicket VM software application to withhold a functional ticketing system. These compartments include roles, departments, teams, deskagents, admins, back-end users, SLA'S and help topics. It also gives a scope of the agent panel vs. the admin. panel within osTicket.




<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- OsTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Computer Desktop/Laptop
- Azure Account
- Remote Desktop
- OsTicket needs to already be installed

<h2>OsTicket Infrastructure Installation steps</h2>


Step 1:
<p>
<img src="https://i.imgur.com/rvVVO2J.png"/>
</p>
<p>
Go to Virtual Machines in Azure and hover over osTicket with your mouse. 
</p>
<br />
Step 2:
<p>
<img src="https://i.imgur.com/DYXlS18.png"/>
</p>
<p>
Make sure to press start to turn the osTicket Virtual Machine on. 
</p>
<br />
Step 3:
<p>
<img src="https://i.imgur.com/AzZ8XJt.png"/>
</p>
<p>
Next, log into the osTicket and connect. 
</p>
<br />
Step 4:
<p>
<img src="https://i.imgur.com/KkDjtCC.png"/>
</p>
<p>
Open up the internet from your home screen within the osTicket-vm remote desktop. 
</p>
<br />
Step 5:
<p>
<img src="https://i.imgur.com/mR1El0I.png"/>
</p>
<p>
Click on the saved osTicket admin/deskagent login page that was bookmarked during the prerequisite installation. 
</p>
<br />
Step 6:
<p>
<img src="https://i.imgur.com/1IvSAb3.png"/>
</p>
<p>
Click on the admin panel.
</p>
<br />
Step 7:
<p>
<img src="https://i.imgur.com/IgNJPys.png"/>
</p>
<p>
Click on Agents.
</p>
<br />
Step 8:
<p>
<img src="https://i.imgur.com/UigmvQU.png"/>
</p>
<p>
Go to roles.
</p>
<br />
Step 9:
<p>
<img src="https://i.imgur.com/nThLpfw.png"/>
</p>
<p>
Click on the green add new role button.
</p>
<br />
Step 10:
<p>
<img src="https://i.imgur.com/G8q74vM.png"/>
</p>
<p>
In the name box type in Supreme Admin then press add role.
</p>
<br />
Step 11:
<p>
<img src="https://i.imgur.com/cMIxucS.png"/>
</p>
<p>
Click on the permissions tab and go to tickets. Make sure all boxes are checked off.
</p>
<br />
Step 12:
<p>
<img src="https://i.imgur.com/AZ0wa8R.png"/>
</p>
<p>
Next, go to tasks and make sure all boxes are checked off.
</p>
<br />
Step 13:
<p>
<img src="https://i.imgur.com/5Oj79IJ.png"/>
</p>
<p>
In the Knowledgebase tab make sure premade is checked off and then press add role.
</p>
<br />
Step 14:
<p>
<img src="https://i.imgur.com/zeuOwM0.png"/>
</p>
<p>
The Supreme Admin role has been successfully added. Stay in the admin panel and click on agents.
</p>
<br />
Step 15:
<p>
<img src="https://i.imgur.com/rMXRFZT.png"/>
</p>
<p>
Go to departments.
</p>
<br />
Step 16:
<p>
<img src="https://i.imgur.com/5nYghVG.png"/>
</p>
<p>
Glick on the green add new department on the right hand side of the page. 
</p>
<br />
Step 17:
<p>
<img src="https://i.imgur.com/1ShoGb2.png"/>
</p>
<p>
Underneath the settings tab in the name box press type in SysAdmin..
</p>
<br />
Step 18:
<p>
<img src="https://i.imgur.com/uuNOFbd.png"/>
</p>
<p>
For parent switch from top level to support. 
</p>
<br />
Step 19:
<p>
<img src="https://i.imgur.com/IxKQWFI.png"/>
</p>
<p>
Click on the yellow create department button. 
</p>
<br />
Step 20:
<p>
<img src="https://i.imgur.com/cG3WjKh.png"/>
</p>
<p>
Stay within the Admin panel and go to settings. 
</p>
<br />
Step 21:
<p>
<img src="https://i.imgur.com/Tg4Lpm5.png"/>
</p>
<p>
Click on Users. 
</p>
<br />
Step 22:
<p>
<img src="https://i.imgur.com/qSVqksq.png"/>
</p>
<p>
Underneath the settings tab make sure the 'require registration and login to create tickets' box is left  unchecked.
</p>
<br />
Step 23:
<p>
<img src="https://i.imgur.com/Hjhpjf1.png"/>
</p>
<p>
Make sure registration method is set to public.
</p>
<br />
Step 24:
<p>
<img src="https://i.imgur.com/9Pi6x8S.png"/>
</p>
<p>
Click on save changes. 
</p>
<br />
Step 25:
<p>
<img src="https://i.imgur.com/S63TosN.png"/>
</p>
<p>
Next, stay within the admin panel and click on the agents tab.
</p>
<br />
Step 26:
<p>
<img src="https://i.imgur.com/h0Kr083.png"/>
</p>
<p>
Go to and click on the green add new agent tab.
</p>
<br />
27:
<p>
<img src="https://i.imgur.com/lqrSuYY.png"/>
</p>
<p>
Underneath the account tab, type in the information for the first desk agent that will be created. For first name type in Jane and last name Doe. Put in a fake email address. For username put in Jane.
</p>
<br />
Step 28:
<p>
<img src="https://i.imgur.com/pxwd1mc.png"/>
</p>
<p>
Under the access tab for primary department select support/sysadmin and for the role select Supreme Admin. 
</p>
<br />
Step 29:
<p>
<img src="https://i.imgur.com/kcWOkCu.png"/>
</p>
<p>
Go to the permissions tab and underneath users make sure all boxes are checked off. 
</p>
<br />
Step 30:
<p>
<img src="https://i.imgur.com/ZJK7bNO.png"/>
</p>
<p>
Under the teams tab click on add new in the drop down menu for assigned teams.
</p>
<br />
Step 31:
<p>
<img src="https://i.imgur.com/Cf2ipQZ.png"/>
</p>
<p>
Select on online banking and press create. 
</p>
<br />
Step 32:
<p>
<img src="https://i.imgur.com/HWFjbBV.png"/>
</p>
<p>
Press Create again.
</p>
<br />
Step 33:
<p>
<img src="https://i.imgur.com/AkdPYwL.png"/>
</p>
<p>
Jane Doe has been successfully added as an agent. Stay within the admin panel and click on agents. 
</p>
<br />
Step 34:
<p>
<img src="https://i.imgur.com/qSmcXlL.png"/>
</p>
<p>
Click on Add new agent again. 
</p>
<br />
Step 35:
<p>
<img src="https://i.imgur.com/a8uz7pd.png"/>
</p>
<p>
Within the account tab for first name enter in John and last name Doe. Put in a fake email address. Username is John.
</p>
<br />
Step 36:
<p>
<img src="https://i.imgur.com/dqc7pkX.png"/>
</p>
<p>
Under the access tab, for primary  department select support and for role select all access. 
</p>
<br />
Step 37:
<p>
<img src="https://i.imgur.com/wkTeNs4.png"/>
</p>
<p>
Under the permissions tab for users make sure all boxes are checked off.
</p>
<br />
Step 38:
<p>
<img src="https://i.imgur.com/uo2KRhs.png"/>
</p>
<p>
For assigned teams select level 1 support. Click on the saved changes button.
</p>
<br />
Step 39:
<p>
<img src="https://i.imgur.com/hvo4bXJ.png"/>
</p>
<p>
Stay within admin panel and click on agents.
</p>
<br />
Step 40:
<p
<img src="https://i.imgur.com/In8LCvd.png"/>
</p>
<p>
Click on Jane Doe's name. 
</p>
<br />
Step 41:
<p>
<img src="https://i.imgur.com/e1FQxoq.png"/>
</p>
<p>
Under the account tab click on the set password button to set/reset password. 
</p>
<br />
Step 42:
<p>
<img src="https://i.imgur.com/OYlaX4p.png"/>
</p>
<p>
The 'send the agent a password resert email' does not need to be checked off.
</p>
<br />
Step 43:
<p>
<img src="https://i.imgur.com/VLgihWU.png"/>
</p>
<p>
Create and insert a password for Jane. 
</p>
<br />
Step 44:
<p>
<img src="https://i.imgur.com/eZswmEe.png"/>
</p>
<p>
Uncheck require a password change and the click update. 
</p>
<br />
Step 45:
<p>
<img src="https://i.imgur.com/9UbnWPA.png"/>
</p>
<p>
Next click on John Doe underneath the agents tab within the admin panel and reset password. Follow the previous 4 steps used to set Janes password.
</p>
<br />
Step 46:
<p>
<img src="https://i.imgur.com/xqkVzyR.png"/>
</p>
<p>
Next go within the agent panel by clicking on Agent Panel in upper right hand of screen. 
</p>
<br />
Step 47:
<p>
<img src="https://i.imgur.com/2incyHs.png"/>
</p>
<p>
Notice it say 'Admin Panel in the upp right hand side instead of 'Agent Panel. This means you are now operating from the agent panel. In the next few steps back-end users will now be added to osTicket. Click on Users. 
</p>
<br />
Step 48:
<p>
<img src="https://i.imgur.com/SlgrHgZ.png"/>
</p>
<p>
Click on the green add user button. 
</p>
<br />
Step 49:
<p>
<img src="https://i.imgur.com/fPsqCDK.png"/>
</p>
<p>
For email address type in karen@(insert fake email address). Full name is Karen the press add user. 
</p>
<br />
Step 50:
<p>
<img src="https://i.imgur.com/XSfFZea.png"/>
</p>
<p>
Next go back into users and click on the gree add user button. Make sure to stay within the agent panel.
</p>
<br />
Step 51:
<p>
<img src="https://i.imgur.com/T1TD8sf.png"/>
</p>
<p>
For email type in Ken@(insert fake email address). Full name is Ken then press Add User.
</p>
<br />
Step 52:
<p>
<img src="https://i.imgur.com/lsriSnm.png"/>
</p>
<p>
Next SLA's will be created for ticket priority. Click on Admin Panel. 
</p>
<br />
Step 53:
<p>
<img src="https://i.imgur.com/qXDEev9.png"/>
</p>
<p>
Then go to Manage. 
</p>
<br />
Step 54:
<p>
<img src="https://i.imgur.com/AH9gQXL.png"/>
</p>
<p>
Then click on SLA. 
</p>
<br />
Step 55:
<p>
<img src="https://i.imgur.com/NEBptgw.png"/>
</p>
<p>
Next, click on the green add new SLA Plan button. 
</p>
<br />
Step 56:
<p>
<img src="https://i.imgur.com/N3xTXrw.png"/>
</p>
<p>
On this next screen typ in Sev-A for name, 1 hour for grace period and 24/7 for schedules. Click on add plan.
</p>
<br />
Step 57:
<p>
<img src="https://i.imgur.com/dO7aSpM.png"/>
</p>
<p>
SLA Sev-A has been successfully added. Click on Add New SLA Plan again. 
</p>
<br />
Step 58:
<p>
<img src="https://i.imgur.com/PfRlUPj.png"/>
</p>
<p>
For name typ in Sev-B, for grace period 4 hours, and for schedule 24/7. Click on add plan. 
</p>
<br />
Step 59:
<p>
<img src="https://i.imgur.com/5i4pJNI.png"/>
</p>
<p>
Sev-B SLA plan has been successfully added. Click on Add New SLA Plan one more time. 
</p>
<br />
Step 60:
<p>
<img src="https://i.imgur.com/81UDtyM.png"/>
</p>
<p>
For name type in Sev-c, for grace period 8 hours and for schedule click on business hourse which turn out to be Monday-Friday 8am-5pm with U.S. Holidays. Click Add plan. 
</p>
<br />
Step 61:
<p>
<img src="https://i.imgur.com/D23v3rW.png"/>
</p>
<p>
Next Help Topics will be created within OsTicket. Staying inside the Admin Panel, click on Manage. 
</p>
<br />
Step 62: 
<p>
<img src="https://i.imgur.com/KJ7JU14.png"/>
</p>
<p>
Then go to and click on Help Topics.
</p>
<br />
Step 63:
<p>
<img src="https://i.imgur.com/Qp9LAxy.png"/>
</p>
<p>
Click on Add New Help Topic.
</p>
<br />
Step 64:
<p>
<img src="https://i.imgur.com/1VXmdSh.png"/>
</p>
<p>
Under the Help Topic Information tab, type in Personal Computer Issues and for Parent Topic select Report a Problem. Click the add topic button. 
</p>
<br />
Step 66:
<p>
<img src="https://i.imgur.com/cfuzLR7.png"/>
</p>
<p>
Go back to the mangae tab and click on add users again.
</p>
<br />
Step 67:
<p>
<img src="https://i.imgur.com/czjK3oF.png"/>
</p>
<p>
For the next help topic type in Buisness Critical Outage and for Parent Topic select Reprt a Problem. Click Add Topic.
</p>
<br />
Step 68:
<p>
<img src="https://i.imgur.com/BSs1fFO.png"/>
</p>
<p>
Go back to manage and add another help topic by  clicking on Add New Help Topic.
</p>
<br />
Step 69:
<p>
<img src="https://i.imgur.com/y2U6yaH.png"/>
</p>
<p>
For Topc type in Equipment Request and for Parent Topic select General Inquiry. Click Add topic.
</p>
<br />
Step 70:
<p>
<img src="https://i.imgur.com/TV4tD5Z.png"/>
</p>
<p>
Go back to manage and click on Add New Help Topic.
</p>
<br />
Step 71:
<p>
<img src="https://i.imgur.com/jLUgg6A.png"/>
</p>
<p>
For name type in Password reset and for Paren Topic click on Report a Problem. Press Add Topic.
</p>
<br />
Step 72:
<p>
<img src="https://i.imgur.com/Mre5GBR.png"/>
</p>
<p>
Go back to Manage again and click on Add topic.
</p>
<br />
Step 73:
<p>
<img src="https://i.imgur.com/aPeyq1o.png"/>
</p>
<p>
For name type in Other and for Parent Topic select General Inquiry. Click on Add Topic. 
</p>
<br />
Step 74:
<p>
<img src="https://i.imgur.com/TQY9buz.png"/>
</p>
<p>
Five Help Topics have been created so far to efficiently catergorize tickets within the ticket cycle of OsTicket. 

This here concludes the configuration of the different functional compartments of osTicket ticketing system.
</p>
<br />





