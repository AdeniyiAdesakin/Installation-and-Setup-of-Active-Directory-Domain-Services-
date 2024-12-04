<h1>Installation and Setup of Active Directory Domain Services</h1>
<p>Active Directory Domain Services is a directory service used in Windows-based networks to manage and organize resources such as computers, users, groups, and services</p>
<p>1. To install Active Directory Domain Services(ADDS) in Windows server 2019, from the server manager dashboard, click on Manage and on Add roles and Features</p>
<p align="center"><img src="https://i.imgur.com/BFw3fUz.png" height="50%" width="50%"/>

<p>2. On the before you begin screen, just click <b>NEXT</b></p>
<p align="center"><img src="https://i.imgur.com/gaMZiFi.png" height="50%" width="50%"/>

<p>3. On the Installation Type screen, make sure the Role-based or feature-based installation is selected, then click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/ZvY3YRt.png" height="50%" width="50%"/>

<p>4. On the Select destination server screen, make sure the select a server from the server pool is selected and select the server you are trying to install Adds from the server pool, then click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/Xq8ggfi.png" height="50%" width="50%"/>

<p>5. On the select server roles screen, select the second option(Active Directory Domain Services) and click on add features from the pop-up screen, then click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/FJXu3HC.png" height="50%" width="50%"/>

<p>6. On the select features screen, just click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/6Ri1r9H.png" height="50%" width="50%"/>

<p>7. On confirm installation selections, just click on INSTALL and wait for the installation to complete. </p>
<p align="center"><img src="https://i.imgur.com/qgNK3C5.png" height="50%" width="50%"/>

<p>8. After the installation is complete, from the notification, click on promote the server to a domain controller</p>
<p align="center"><img src="https://i.imgur.com/QxcyWQO.png" height="50%" width="50%"/>

<p>9. On the Deployment configuration screen, select add a new forest and enter your desired domain name(for this I am using my last name) in the Root domain name box, then click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/IYX8EZ7.png" height="50%" width="50%"/>

<p>10. On the Domain Controller Options screen, Input password and confirm password, then click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/W7ujg6C.png" height="50%" width="50%"/>

<p>11. On the Additional options screen, leave your domain name in the NetBIOS domain name and click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/19JkJZ0.png" height="50%" width="50%"/>

<p>12. On the Paths screen, leave it at default and click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/VvvvYWw.png" height="50%" width="50%"/>

<p>13. On the Review Options, click <b>NEXT</b>.</p>
<p align="center"><img src="https://i.imgur.com/FrXmctQ.png" height="50%" width="50%"/>

<p>14. On the Prerequisites Check, click <b>INSTALL</b>.</p>
<p align="center"><img src="https://i.imgur.com/3Lto4nb.png" height="50%" width="50%"/>

<p>15. On the Installation page, just wait for the installation to complete.</p>
<p align="center"><img src="https://i.imgur.com/l82jh6v.png" height="50%" width="50%"/>

<br>
<br>

<h1>Creating Organizational units, Users, and Groups in Active Directory</h1>
<p>The purpose of creating OUs, Groups, and Users in Active Directory is to organize and manage network resources, assign appropriate permissions, and streamline user and group administration for security and access control.</p>
<h3>*To create OU</h3>
<p>1. Go to Server manager-dashboard > Tools >Active Directory Users and Computers</p>
<p align="center"><img src="https://i.imgur.com/VJnRNxO.png" height="50%" width="50%"/>

<p>2. On the dashboard, right click on the domain name, go to New, then click Organizational Unit</p>
<p align="center"><img src="https://i.imgur.com/ReaN2rI.png" height="50%" width="50%"/>

<p>3. On the New object -Organizational Unit screen, in the name space, type in the OU name you intend to create and click OK</p>
<p align="center"><img src="https://i.imgur.com/tJp70AG.png" height="50%" width="50%"/>

<p>4. Repeated steps 2 and 3 above to create another OU</p>
<p align="center"><img src="https://i.imgur.com/wtTranz.png" height="50%" width="50%"/>

<p>5. The two OUs created are displayed when I expanded the domain</p>
<p align="center"><img src="https://i.imgur.com/uNzL8J2.png" height="50%" width="50%"/>

<h3>*To Create Users</h3>
<p>1. While on Active Directory Users and Computers, Right-click on the User, go to New, then click User</p>
<p align="center"><img src="https://i.imgur.com/7jmEy3f.png" height="50%" width="50%"/>

<p>2. On the New Object - User, input the first name, last name, a user logon name and click NEXT</p>
<p align="center"><img src="https://i.imgur.com/nqDwXeK.png" height="50%" width="50%"/>

<p>3. On the next page, input the password, leave the “User must change password at next logon” checked, then click NEXT</p>
<p align="center"><img src="https://i.imgur.com/n8lAysh.png" height="50%" width="50%"/>

<p>4. On the next page, review the information and click FINISH</p>
<p align="center"><img src="https://i.imgur.com/JYLmC0I.png" height="50%" width="50%"/>

<p>5. The user and couple other users I created are now displays under the User tab</p>
<p align="center"><img src="https://i.imgur.com/VGIxG1e.png" height="50%" width="50%"/>

<h3>*To Create Groups</h3>
<p>1. While on Active Directory Users and Computers, Right-click on an OU, go to New, then click Group</p>
<p align="center"><img src="https://i.imgur.com/gDAfcJL.png" height="50%" width="50%"/>

<p>2. On the New Object - Group, type in the Group name in the space provided and click OK</p>
<p align="center"><img src="https://i.imgur.com/o1dDx7K.png" height="50%" width="50%"/>

<p>3. The seurity group I created in the EdmontonOU is now displayed</p>
<p align="center"><img src="https://i.imgur.com/hHupEMt.png" height="50%" width="50%"/>

<br>



