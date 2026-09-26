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
| User principal name | CKBam |
| Mail nickname | CKBam |
| Display name | Bam Alexander |
| Password | (your assigned password) |

5. Select **Create** to register the user in your organization.

![image alt](https://github.com/sprintis2/Entra-ID-Labs/blob/main/Creating%20a%20User%20(Entra%20ID).png?raw=true)



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



















