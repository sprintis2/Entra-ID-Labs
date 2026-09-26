# Microsoft Entra-ID-Labs
**Entra ID Practical Labs - Users, Groups, Roles & External Collaboration Management**



# **Managing User Roles**

**Add a New User**
1. Sign in to the Microsoft Entra admin center as a **Global Administrator**.

2. In the left menu, expand **Identity**.

3. Under **Users**, select **All Users**, then choose **+ New User**.

4. Create a user using the following settings:

| Setting | Value |
| --- | --- |
| **User principal name**: | CKBam |
| **Mail nickname**: | CKBam |
| **Display name**: | Bam Alexander |
| **Password**: | (Assigned password) |

5. Select **Create** to register the user in your organization.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Creating%20a%20User%20(Entra%20ID).png?raw=true)



**Removing Users From Microsoft Entra ID**

1.	Navigate to the Microsoft Entra admin center. In the left navigation, under Identity, select **Users**

2.	In the **Users** list, select the check box for a user to delete. For example (**Tre Steward**.)

3.	With the user account selected, on the menu, select **Delete user**.

4.	Review the dialog box and then select **OK**.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Removing%20a%20User.png?raw=true)



**Restoring Deleted User**

1.	In the Users page, in the left navigation, select **Deleted users**.

2.	Review the list of deleted users and select the user you deleted.

3.	On the menu, select **Restore user**. 

4.	Review the dialog box and then select **OK**.

5.	In the left navigation, select **All users**. Verify User was restored

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Restoring%20Deleted%20User.png?raw=true)



# **Assigning Roles To Users**

1.	In Microsoft Entra ID, on the **“All users screen”**, select **Bam Alexander**.

2.	On the user’s profile page, select **Assigned roles**. The Assigned roles page appears.

3.	Select **Add assignment**s, select the role to assign to the user (for example, **Application administrator**), and then select **Add**.

4.	Select **+ Add Assignment**. The newly assigned Application administrator role appears on the user’s Assigned roles page.

 ![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Assigning%20a%20role%20to%20a%20User.png?raw=true)



# **Removing Role Assignments**

1.	In Microsoft Entra ID, select **Users** - **All User**, and then select the user getting the role assignment removed. For example, **Bam Alexander**.

2.	Select **Assigned roles**, then select the name of the role your wish to remove - **Application Administrato**r.

3.	On the far-right side of the screen, select **Remove**. Then select **Yes** option when prompted for confirmation.

# **Controlling Permissions - Add and Restrict** 

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Controlling%20Permissions.png?raw=true)



# **Exploring Available Permissions**

You can see the list of permissions in the description of each role. To open, launch Microsoft Entra ID, then open the Roles and administrators screen. Next select a role and open its description page from the ellipsis (...) menu. Depending on the role you chose, you'll see a large or small number of permissions. Two sets of permissions:

•	Role permissions

•	Guest and service principal basic read permissions

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Exploring%20Permissions.png?raw=true)



# **Configuring The External User Options**

 ![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Configure%20external%20collaboration%20settings.png?raw=true)



•	**Guest user access** – Configured Guest User access to the most restrictive setting, “restricted to properties and memberships of their own directory objects.”

•	**Guest invite settings** – Configured Guest invite settings to “Member users and users assigned to specific admin roles can invite guest users including guests with member permissions.”

•	**Guest self-service up**– Disabled guest self-service sign up via user flows.

# **Setting Tenant Wide Properties**

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Setting%20Tenant%20Wide%20Properties.png?raw=true)



1.	Select the **Show portal menu** hamburger icon and then select **Microsoft Entra ID**

2.	In the left navigation, in the Manage section, select **Properties**.

3.	In the **Name** box, the tenant name was changed from Default Directory to “CountyKids”.

4.	Select **Save** to update the tenant properties.

 # **Creating a Security Group**

1.	Browse the Microsoft Entra admin center screen.

2.	In the left navigation, under **Identity**, select **Groups** and then **All groups**.

3.	In the Groups screen, on the menu, select **New group**.

4.	Create a group using the following information:

| Setting | Value |
| --- | --- |
| **Group type:** | Security |
| **Group name:** | Marketing |
| **Membership type:** | Assigned |
| **Owners:** | Admin account |
| **Members:** | Bam Alexander |

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Creating%20a%20Security%20Group.png?raw=true)



# **Creating a Microsoft 365 group in Microsoft Entra ID**

1.	In the left navigation, under **Identity**, select **Groups**.

2.	In the Groups page, on the menu, select **New group**.

3.	Create a group using the following information:

| Setting | Value |
| --- | --- |
| Group type | Microsoft 365 |
| Group name | CountyKid Sales |
| Membership type | Assigned |
| Owners | Your admin account |
| Members | Assigned member |

4.	When complete, verify the group named CountyKid Sales is shown in the All groups list. 

 ![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Creating%20Microsoft%20365%20group.png?raw=true)



# **Assigning Group Licenses** 

1.	Go to the Microsoft 365 admin center at https://admin.microsoft.com.

2.	Select **Billing** from the menu on the left.

3.	Select **Licenses**.

4.	From the list of licenses you have available, select one.

5.	Select **Groups** from the list near the top of the screen.

6.	On the Groups page, select **+ Assign license**.

7.	Search for and select the **Marketing** group you created earlier.

8.	Select the **Assign** button at the bottom of the dialog.

9.	You should get a message that licenses were successfully assigned.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Assigning%20a%20License%20to%20a%20Security%20Group.png?raw=true)



# **Changing Group License Assignment**

1.	In the left navigation, open **Groups**.

2.	Select **All groups**, then select one of the available groups.

3.	In the left navigation, under **Manage**, select **Licenses**.

4.	Review the current assignments and then, on the menu, select **+ Assignments**.

5.	Open https://admin.microsoft.com to open the Microsoft 365 admin center.

6.	Select **Billing**. Then select **Licenses**.

7.	Select an available license from the list.

8.	Select **Groups** from the menu near the top of the page.

9.	Select the **+ Assign licenses** option.

10.	Pick the group you were looking at earlier in Microsoft Entra. Then select the **Assign** button at the bottom of the page.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Chaange%20group%20license%20assignment.png?raw=true)



# **Configuring External Collaboration Settings**

1.	Select **Identity**.

2.	Select **External Identities** - **External collaboration settings**.

3.	Under **Guest user access**, review access levels that are available and then select Guest **user access is restricted to properties and memberships of their own directory objects (most restrictive)**.

4.	Under **Guest invite settings**, mark **Only user assigned to specific admin roles can invite guest users**.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Configure%20external%20collaboration%20settings.png?raw=true)



# **Adding Guest Users to Directory**

1.	Select **Identity**.

2.	Under **Users**, select **All Users**.

3.	Select **New user** - **Invite external user**.

4.	On the New user page, select **Invite user** and then add your information as the guest user. When complete, select **Invite**.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Inviting%20an%20external%20User.png?raw=true)



![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/New%20External%20user%20invited%20as%20guest.png?raw=true)



**Inviting Guest Users (Bulk)**

1.	In the navigation pane, select **Identity**.

2.	Under **Users**, select **All Users**, then select **Bulk operations** - **Bulk invite**.

3.	In the Bulk invite users pane, select **Download** to a sample CSV template with invitation properties.

4.	Using an editor to view the CSV file, review the template.

5.	Open the .csv template and add a line for each guest user. Save the file.

6.	On the Bulk invite users page, under **Upload your csv file**, browse to the file. When you select the file, validation of the .csv file starts.

7.	After the file contents are validated, you'll see **File uploaded successfully**. If there are errors, you must fix them before you can submit the job.

8.	When your file passes validation, select **Submit** to start the Azure bulk operation that adds the invitations.

9.	To view the job status, select **view the status of each operation**. Or, you can select **Bulk operation results** in the Activity section. For details about each line item within the bulk operation, select the values under the **# Success**, **# Failure**, or **Total Requests** columns.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Invite%20Guest%20Users%20Bulk.png?raw=true)



# **Exploring Dynamic Goups**

1.	Under **Groups**, select **All Groups**, and then select **New group**.

2.	On the New Group page, under **Group type**, select **Security**.

3.	In the **Group name **box, enter **All company users dynamic group**.

4.	Select the **Membership type** menu and then select **Dynamic User**.

5.	Under **Dynamic user members**, select **Add dynamic query**.

6.	On the right above the **Rule syntax** box, select **Edit**.

7.	In the Edit rule syntax pane, enter the following expression in the **Rule syntax** box: user.objectId -ne null

8.	Select **OK**. The rule appears in the Rule syntax box.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Dynamic%20Membership%20rules.png?raw=true)



# **Configuring an Identity Provider (Google)**

Step 1: Configure a Google developer project

First, create a new project in the Google Developers Console to obtain a client ID and a client secret that you can later add to Microsoft Entra ID.

1.	Go to the Google APIs at https://console.developers.google.com, and sign in with Google account.

2.	Accept the terms of service if prompted.

3.	Create a new project: On the dashboard, select **Create Project**, give the project a name (for example, **Microsoft Entra B2B**), and then select **Create**:

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Creating%20Google%20Project%20for%20Federation.png?raw=true)



4.	On the **APIs and Services** page, select **View** under your new project. Select **Go to APIs overview** on the APIs card. Select **OAuth consent screen**. Select **External**, and then select **Create**. On the **OAuth consent screen**, enter an **Application name**

5.	 Select **Credentials**. On the **Create credentials** menu, select **OAuth client ID**

6.	Under **Application type**, select **Web application**. Give the application a suitable name, like **Microsoft Entra B2B**. Under **Authorized redirect URIs**, enter the following URIs:

•	**https://login.microsoftonline.com**

•	**https://login.microsoftonline.com/te/ tenant ID /oauth2/authresp (where tenant ID is the tenant ID in Azure)**

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/OAuth%20Client%20Created.png?raw=true)















