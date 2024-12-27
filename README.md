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


Step 1: Go to Virtual Machines in Azure and hover over osTicket with your mouse. 
</p>
<p>
<img src="https://i.imgur.com/rvVVO2J.png"/>
</p>
<p>

</p>
<br />
Step 2: Make sure to press start to turn the osTicket Virtual Machine on. 
</p>
<p>
<img src="https://i.imgur.com/DYXlS18.png"/>
</p>
<p>

</p>
<br />
Step 3: Next, log into the osTicket and connect. 
</p>
<p>
<img src="https://i.imgur.com/AzZ8XJt.png"/>
</p>
<p>

</p>
<br />
Step 4: Open up the internet from your home screen within the osTicket-vm remote desktop. 
</p>
<p>
<img src="https://i.imgur.com/KkDjtCC.png"/>
</p>
<p>
 
</p>
<br />
Step 5: Click on the saved osTicket admin/deskagent login page that was bookmarked during the prerequisite installation and login as the administrator. 
</p>
<p>
<img src="https://i.imgur.com/mR1El0I.png"/>
</p>
<p>

</p>
<br />
Step 6: Click on the admin panel.
</p>
<p>
<img src="https://i.imgur.com/1IvSAb3.png"/>
</p>
<p>

</p>
<br />
Step 7: Click on Agents.
</p>
<p>
<img src="https://i.imgur.com/IgNJPys.png"/>
</p>
<p>

</p>
<br />
Step 8: Go to roles.
</p>
<p>
<img src="https://i.imgur.com/UigmvQU.png"/>
</p>
<p>

</p>
<br />
Step 9: Click on the green add new role button.
</p>
<p>
<img src="https://i.imgur.com/nThLpfw.png"/>
</p>
<p>
.
</p>
<br />
Step 10: In the name box type in Supreme Admin then press add role.
</p>
<p>
<img src="https://i.imgur.com/G8q74vM.png"/>
</p>
<p>

</p>
<br />
Step 11: Click on the permissions tab and go to tickets. Make sure all boxes are checked off.
</p>
<p>
<img src="https://i.imgur.com/cMIxucS.png"/>
</p>
<p>

</p>
<br />
Step 12: Next, go to tasks and make sure all boxes are checked off.
</p>
<p>
<img src="https://i.imgur.com/AZ0wa8R.png"/>
</p>
<p>

</p>
<br />
Step 13: In the Knowledgebase tab make sure premade is checked off and then press add role.
</p>
<p>
<img src="https://i.imgur.com/5Oj79IJ.png"/>
</p>
<p>

</p>
<br />
Step 14: The Supreme Admin role has been successfully added. Stay in the admin panel and click on agents.
</p>
<p>
<img src="https://i.imgur.com/zeuOwM0.png"/>
</p>
<p>

</p>
<br />
Step 15: Go to departments.
</p>
<p>
<img src="https://i.imgur.com/rMXRFZT.png"/>
</p>
<p>

</p>
<br />
Step 16: Click on the green add new department on the right hand side of the page. 
</p>
<p>
<img src="https://i.imgur.com/5nYghVG.png"/>
</p>
<p>

</p>
<br />
Step 17: Underneath the settings tab in the name box press type in SysAdmin.
</p>
<p>
<img src="https://i.imgur.com/1ShoGb2.png"/>
</p>
<p>

</p>
<br />
Step 18: For parent switch from top level to support. 
</p>
<p>
<img src="https://i.imgur.com/uuNOFbd.png"/>
</p>
<p>

</p>
<br />
Step 19: Click on the yellow create department button. 
</p>
<p>
<img src="https://i.imgur.com/IxKQWFI.png"/>
</p>
<p>

</p>
<br />
Step 20: Stay within the Admin panel and go to settings. 
</p>
<p>
<img src="https://i.imgur.com/cG3WjKh.png"/>
</p>
<p>

</p>
<br />
Step 21: Click on Users. 
</p>
<p>
<img src="https://i.imgur.com/Tg4Lpm5.png"/>
</p>
<p>

</p>
<br />
Step 22: Underneath the settings tab make sure the 'require registration and login to create tickets' box is left  unchecked.
</p>
<p>
<img src="https://i.imgur.com/qSVqksq.png"/>
</p>
<p>

</p>
<br />
Step 23: Make sure registration method is set to public.
</p>
<p>
<img src="https://i.imgur.com/Hjhpjf1.png"/>
</p>
<p>

</p>
<br />
Step 24: Click on save changes. 
</p>
<p>
<img src="https://i.imgur.com/9Pi6x8S.png"/>
</p>
<p>

</p>
<br />
Step 25: Next, stay within the admin panel and click on the agents tab.
</p>
<p>
<img src="https://i.imgur.com/S63TosN.png"/>
</p>
<p>

</p>
<br />
Step 26: Go to and click on the green add new agent tab.
</p>
<p>
<img src="https://i.imgur.com/h0Kr083.png"/>
</p>
<p>

</p>
<br />
Step 27: Underneath the account tab, type in the information for the first desk agent that will be created. For first name type in Jane and last name Doe. Put in a fake email address. For username put in Jane.
</p>
<p>
<img src="https://i.imgur.com/lqrSuYY.png"/>
</p>
<p>

</p>
<br />
Step 28: Under the access tab for primary department select support/sysadmin and for the role select Supreme Admin. 
</p>
<p>
<img src="https://i.imgur.com/pxwd1mc.png"/>
</p>
<p>

</p>
<br />
Step 29: Go to the permissions tab and underneath users make sure all boxes are checked off. 
</p>
<p>
<img src="https://i.imgur.com/kcWOkCu.png"/>
</p>
<p>

</p>
<br />
Step 30: Under the teams tab click on add new in the drop down menu for assigned teams.
</p>
<p>
<img src="https://i.imgur.com/ZJK7bNO.png"/>
</p>
<p>

</p>
<br />
Step 31: Select on online banking and press create. 
</p>
p>
<img src="https://i.imgur.com/Cf2ipQZ.png"/>
</p>
<p>

</p>
<br />
Step 32: Press Create again.
</p>
<p>
<img src="https://i.imgur.com/HWFjbBV.png"/>
</p>
<p>

</p>
<br />
Step 33: Jane Doe has been successfully added as an agent. Stay within the admin panel and click on agents. 
</p>
<p>
<img src="https://i.imgur.com/AkdPYwL.png"/>
</p>
<p>

</p>
<br />
Step 34: Click on Add new agent again.
</p>
<p>
<img src="https://i.imgur.com/qSmcXlL.png"/>
</p>
<p>

</p>
<br />
Step 35: Within the account tab for first name enter in John and last name Doe. Put in a fake email address. Username is John.
</p>
<p>
<img src="https://i.imgur.com/a8uz7pd.png"/>
</p>
<p>

</p>
<br />
Step 36: Under the access tab, for primary  department select support and for role select all access. 
</p>
<p>
<img src="https://i.imgur.com/dqc7pkX.png"/>
</p>
<p>

</p>
<br />
Step 37: Under the permissions tab for users make sure all boxes are checked off.
</p>
<p>
<img src="https://i.imgur.com/wkTeNs4.png"/>
</p>
<p>

</p>
<br />
Step 38: For assigned teams select level 1 support. Click on the saved changes button.
</p>
<p>
<img src="https://i.imgur.com/uo2KRhs.png"/>
</p>
<p>

</p>
<br />
Step 39: Stay within admin panel and click on agents.
</p>
<p>
<img src="https://i.imgur.com/hvo4bXJ.png"/>
</p>
<p>

</p>
<br />
Step 40: Click on Jane Doe's name.
</p>
<p
<img src="https://i.imgur.com/In8LCvd.png"/>
</p>
<p>

</p>
<br />
Step 41: Under the account tab click on the set password button to set/reset password.
</p>
<p>
<img src="https://i.imgur.com/e1FQxoq.png"/>
</p>
<p>

</p>
<br />
Step 42: The 'send the agent a password resert email' does not need to be checked off.
</p>
<p>
<img src="https://i.imgur.com/OYlaX4p.png"/>
</p>
<p>

</p>
<br />
Step 43: Create and insert a password for Jane. 
</p>
<p>
<img src="https://i.imgur.com/VLgihWU.png"/>
</p>
<p>

</p>
<br />
Step 44: Uncheck require a password change and the click update. 
</p>
<p>
<img src="https://i.imgur.com/eZswmEe.png"/>
</p>
<p>

</p>
<br />
Step 45: Next click on John Doe underneath the agents tab within the admin panel and reset password. Follow the previous 4 steps used to set Janes password.
</p>
<p>
<img src="https://i.imgur.com/9UbnWPA.png"/>
</p>
<p>

</p>
<br />
Step 46: Next go within the agent panel by clicking on Agent Panel in upper right hand of screen. 
</p>
<p>
<img src="https://i.imgur.com/xqkVzyR.png"/>
</p>
<p>

</p>
<br />
Step 47: Notice it say 'Admin Panel in the upp right hand side instead of 'Agent Panel. This means you are now operating from the agent panel. In the next few steps back-end users will now be added to osTicket. Click on Users. 
</p>
<p>
<img src="https://i.imgur.com/2incyHs.png"/>
</p>
<p>
 
</p>
<br />
Step 48: Click on the green add user button. 
</p>
<p>
<img src="https://i.imgur.com/SlgrHgZ.png"/>
</p>
<p>

</p>
<br />
Step 49: For email address type in karen@(insert fake email address). Full name is Karen the press add user. 
</p>
<p>
<img src="https://i.imgur.com/fPsqCDK.png"/>
</p>
<p>
 
</p>
<br />
Step 50: Next go back into users and click on the gree add user button. Make sure to stay within the agent panel.
</p>
<p>
<img src="https://i.imgur.com/XSfFZea.png"/>
</p>
<p>

</p>
<br />
Step 51: For email type in Ken@(insert fake email address). Full name is Ken then press Add User.
</p>
<p>
<img src="https://i.imgur.com/T1TD8sf.png"/>
</p>
<p>

</p>
<br />
Step 52: Next SLA's will be created for ticket priority. Click on Admin Panel. 
</p>
<p>
<img src="https://i.imgur.com/lsriSnm.png"/>
</p>
<p>

</p>
<br />
Step 53: Then go to Manage. 
</p>
<p>
<img src="https://i.imgur.com/qXDEev9.png"/>
</p>
<p>

</p>
<br />
Step 54: Then click on SLA. 
</p>
<p>
<img src="https://i.imgur.com/AH9gQXL.png"/>
</p>
<p>

</p>
<br />
Step 55: Next, click on the green add new SLA Plan button.
</p>
<p>
<img src="https://i.imgur.com/NEBptgw.png"/>
</p>
<p>
</p>
<br />
Step 56: On this next screen type in Sev-A for name, 1 hour for grace period and 24/7 for schedules. Click on add plan.
</p>
<p>
<img src="https://i.imgur.com/N3xTXrw.png"/>
</p>
<p>

</p>
<br />
Step 57: SLA Sev-A has been successfully added. Click on Add New SLA Plan again. 
</p>
<p>
<img src="https://i.imgur.com/dO7aSpM.png"/>
</p>
<p>

</p>
<br />
Step 58: For name type in Sev-B, for grace period 4 hours, and for schedule 24/7. Click on add plan. 
</p>
<p>
<img src="https://i.imgur.com/PfRlUPj.png"/>
</p>
<p>

</p>
<br />
Step 59: Sev-B SLA plan has been successfully added. Click on Add New SLA Plan one more time. 
</p>
<p>
<img src="https://i.imgur.com/5i4pJNI.png"/>
</p>
<p>

</p>
<br />
Step 60: For name type in Sev-C, for grace period 8 hours and for schedule click on business hourse which turn out to be Monday-Friday 8am-5pm with U.S. Holidays. Click Add plan. 
</p>
<p>
<img src="https://i.imgur.com/81UDtyM.png"/>
</p>
<p>

</p>
<br />
Step 61: Next Help Topics will be created within OsTicket. Staying inside the Admin Panel, click on Manage. 
</p>
<p>
<img src="https://i.imgur.com/D23v3rW.png"/>
</p>
<p>

</p>
<br />
Step 62: Then go to and click on Help Topics.
</p>
<p>
<img src="https://i.imgur.com/KJ7JU14.png"/>
</p>
<p>

</p>
<br />
Step 63: Click on Add New Help Topic.
</p>
<p>
<img src="https://i.imgur.com/Qp9LAxy.png"/>
</p>
<p>

</p>
<br />
Step 64: Under the Help Topic Information tab, type in Personal Computer Issues and for Parent Topic select Report a Problem. Click the add topic button. 
</p>
<p>
<img src="https://i.imgur.com/1VXmdSh.png"/>
</p>
<p>

</p>
<br />
Step 65: Go back to the mangae tab and click on add users again
</p>
<p>
<img src="https://i.imgur.com/cfuzLR7.png"/>
</p>
<p>

</p>
<br />
Step 66: For the next help topic type in Buisness Critical Outage and for Parent Topic select Reprt a Problem. Click Add Topic.
</p>
<p>
<img src="https://i.imgur.com/czjK3oF.png"/>
</p>
<p>

</p>
<br />
Step 67: Go back to manage and add another help topic by clicking on Add New Help Topic.
</p>
<p>
<img src="https://i.imgur.com/BSs1fFO.png"/>
</p>
<p>

</p>
<br />
Step 68: For Topc type in Equipment Request and for Parent Topic select General Inquiry. Click Add topic.
</p>
<p>
<img src="https://i.imgur.com/y2U6yaH.png"/>
</p>
<p>

</p>
<br />
Step 69: Go back to manage and click on Add New Help Topic.
</p>
<p>
<img src="https://i.imgur.com/TV4tD5Z.png"/>
</p>
<p>

</p>
<br />
Step 70: For name type in Password reset and for Paren Topic click on Report a Problem. Press Add Topic.
</p>
<p>
<img src="https://i.imgur.com/jLUgg6A.png"/>
</p>
<p>

</p>
<br />
Step 71: Go back to Manage again and click on Add topic.
</p>
<p>
<img src="https://i.imgur.com/Mre5GBR.png"/>
</p>
<p>

</p>
<br />
Step 72: For name type in Other and for Parent Topic select General Inquiry. Click on Add Topic. 
</p>
<p>
<img src="https://i.imgur.com/aPeyq1o.png"/>
</p>
<p>

</p>
<br />
Step 73: Five Help Topics have been created so far to efficiently catergorize tickets within the ticket cycle of OsTicket. 

This here concludes the configuration of the different functional compartments of osTicket ticketing system.
</p>
<p>
<img src="https://i.imgur.com/TQY9buz.png"/>
</p>
<p>

</p>
<br />





