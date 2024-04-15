# Az104-Entra-ID-and-Roles
Manage Microsoft Entra ID (AD) Identities and Role Assignments

##Job skills
•	Create and configure user accounts.
•	Create groups and add members.
•	Implement management groups.
•	Review and assign a built-in Azure role.


##Create Entra ID Tenant

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/226fac85-6228-42b5-860d-27acdc842552)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/24823a45-de71-434f-99a4-fce2df69f0ff)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/5e8bec2e-f416-4d8a-aada-316dcc76a9ac)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/7d4da1a2-39b0-4153-b6d0-91958b84ccef)


##The new Drew Test Tenant has been created.

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/101dd3bf-1d23-48d3-adca-9be332890d5f)


##Adding DrewCrouch.com as a custom domain to the new tenant (Already used in primary tenant):

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/78e95901-3217-42c5-acfd-1247d8e0db80)


![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/3b5e1750-9639-49ec-b3fe-20564da01708)

##Adding a TXT record to the domain (from above)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/4057b997-25a8-48fb-a1e1-ea0226007610)
 
##Making DrewCrouch.com the primary domain:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/81a55efb-9693-4244-86d3-5505eb2dd367)

##Creating a user:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/09292687-86ee-4b2c-946b-26932fc9fa27)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/1ee0d1de-ab01-4866-bd3f-3f9506df856a)

##New user has been successfully created:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/f687b416-f7b6-4195-9edc-27944ed55f55)

##Resetting the auto-generated user’s password:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/e4e1fe5d-9b91-4c91-b38d-4f1b902b8d8c)

##Creating student and teacher users for group creation and assignment:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/b8a692a3-808a-4f23-92b0-0edeb15bcafe)

##Creation of the student group and teacher group:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/3858aa5a-0a77-43cb-bb95-c5a3166a1e0b)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/e245a716-11c0-40e1-9af0-e779a2c93ca2)
 
##Assigning the teachers to the Helpdesk Role for the ability to reset the passwords of the students:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/dc711503-502c-44c8-900a-4cb0e1c97c3a)

##Created a password administrator role with Teacher 1 as the administrator and the Students group as the members so Teacher one can only reset the passwords of the students, not the other teachers.

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/52c10a19-5c21-4aa5-a486-6a7b1ab0c062)

##Bulk creation of student users via a CSV Import:
 
![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/50c33e7f-a6ba-421c-a485-06d61e523d10)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/a9cc6602-cd89-4bfb-936a-44c2ad6c7818)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/c4aef376-c9a7-4970-8c69-9dcbf8e3e452)

##Users successfully created:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/89eaa521-d14c-4b50-bf6e-a4b6e3d6d809)

##Disabled Access Key Access to Storage Accounts and required Entra ID roles for access. Assigning myself as a Storage Blob Data Owner so I can access containers/blob storage:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/7343e212-bc06-4c19-89bb-8322675e781a)

##Verified the security addition now allows a file to be uploaded.

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/a082ee6a-96cd-457e-9d36-d7048fcc16af)

##Assigning read-only access to only the myfirst container for the teacher group.

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/1c7f7aa5-dd8c-42ce-b32e-3531ba737a80)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/fe7f4381-3375-40a7-9b47-7c207bcf6de5)

##Created a custom role cloned from the Storage Blob Data Contributor Role and removed the Delete permissions.

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/105d590e-40a6-4065-80bc-23c8cb38f692)

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/3a4705b2-1dca-4677-807f-284736411fb4)

##Creation of a lock at the resource group level to prevent deletions:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/95503ddd-52fa-4dde-af9f-801d99ceb7d7)

##Verifying the lock was successfully deployed and prevented the deletion even though I am an owner:

![image](https://github.com/DrewCrouch1/Az104-Entra-ID-and-Roles/assets/158229796/a8f6bbc2-e815-4877-9c2f-6558cbec551f)



