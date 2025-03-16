# Changing users and groups

   <H> Knowing how to manage user groups in Active Directory as an IT admin is important for security, efficiency, and compliance. It ensures users have the right access without assigning permissions individually. Groups make it easy to update access when employees change roles, reducing security risks and human errors! </H>

   <b> Configuring users</b>
   - After opening the server manager, open tools and select active directory users and computers
     
   <img src="https://sigmawire.net/i/03/k8xCV2.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>

     
   - Open by right clicking the users folder in the organizational units to the left
  
   - Select new, then user, and enter the information of the user you would like to create

   <img src="https://sigmawire.net/i/03/JEDkl2.png" alt="VirtualBox set up wizard"/>

 
   - Here you can also select their password settings, for security you can disable their account, make them change their password on next login etc, depending on the situation required, then click next and finish
  
   <img src="https://sigmawire.net/i/03/C5MI6u.png" alt="VirtualBox set up wizard"/>

   - Verify the user is now in the group of the users folder

   <img src="https://sigmawire.net/i/03/4PJEi9.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>

   <b> Configuring groups </b>
   - Right click the users folder again, then select group
   - Name the group and leave the settings the same

   <img src="https://sigmawire.net/i/03/I5DeBd.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
     
   - Verify the group is now in the users folder same as you did with the user in the previous steps

   - Right click the group, click properties, then select members

   <img src="https://sigmawire.net/i/03/Obmdzl.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
     
   - Select add, then advanced, and check names to add users to the group and click ok and apply
 
   <img src="https://sigmawire.net/i/03/j9m3NT.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
   
   - Verify the user is added to the group, note the top highlight, it is the same group we made, confirming he is in it

   <img src="https://sigmawire.net/i/03/wOfnjL.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>

