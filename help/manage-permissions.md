---
title: How to manage permissions for folders in AEM Assets Essentials?
description: Assets Essentials allows the administrators to manage the access levels for folders available in the repository. Create user groups and assign permissions to those groups to manage access levels. As an administrator, you can also delegate the permission management privileges to user groups at the folder-level.
---
# Manage permissions for folders

Assets Essentials allows the administrators to manage the access levels for folders available in the repository. Create user groups and assign permissions to those groups to manage access levels. As an administrator, you can also delegate the permission management privileges to user groups at the folder-level.

The following data flow diagram illustrates the sequence of tasks that you perform to configure and manage permissions on folders available in Assets Essentials repository:

![Toolbar options when you select an asset](assets/permissions-management.png)

## Before managing permissions for folders {#before-managing-permissions}

Before you start to manage permissions for folders in your Assets Essentials repository, you must do certain tasks, such as adding administrators who can manage folder permissions for various user groups, create user groups, and create a logical folder structure.

### Add administrators {#add-admin-users}

Add administrators for the Assets Essentials application so that they can manage folder permissions for other user groups.

To add administrators:

1. Access [Admin Console](https://adminconsole.adobe.com) for your organization, click **[!UICONTROL Products]** in the top bar, click **[!UICONTROL AEM Assets Essentials]**, and then click [!DNL Assets Essentials] environment. [!DNL Assets Essentials] has three product profiles that represent access for administrators, regular and consumer users.

   ![Admin Console admin profile](assets/admin-console-admin-profile.png)
  
1. To add a user to a group, click the Assets Essentials Administrators group, select **[!UICONTROL Add User]**, provide the user details, and click **[!UICONTROL Save]**. 

   ![Add users admin profile](assets/add-users-admin-profile.png)

   When you add a user, the user receives an email invitation to get started. You can turn off the email invitations in the product profile settings in [!DNL Admin Console].

1. To remove a user from a group, click the group, select an existing user, and select **[!UICONTROL Remove User]**.

### Add user groups {#add-user-groups}

Create user groups and assign permissions to those groups to manage folder access levels in the Assets Essentials repository. You can then assign your users to the user groups.

![Add users to groups and product profiles](assets/user-groups-product-profiles.png)

You can add users to user groups (1) and [users to Assets Essentials Product Profiles (2)](#add-admin-users). However, you cannot add user groups directly to Assets Essentials Product Profiles (3).

For information on how to manage user groups, see [Manage user groups](https://helpx.adobe.com/enterprise/using/user-groups.html).

>[!NOTE]
>
>If your Admin Console is set up to leverage an external system to manage users/groups assignments, such as Azure or Google connectors, user sync tool or User Management Rest API, your groups and user assignments are configured automatically. For more information, see [Adobe Admin Console users](https://helpx.adobe.com/enterprise/using/users.html)


### Add users to groups {#add-users-to-uesr-groups}

After creating user groups, you can start adding users to user groups. 

For information on how to manage adding users to user groups, see [Manage user groups](https://helpx.adobe.com/enterprise/using/user-groups.html). 

### Create folder structure {#create-folder-structure}

You can use the following methods to create a folder structure in the Assets Essentials repository:

* Click the **[!UICONTROL Create Folder]** option available in the toolbar to create an empty folder. 

* Click **[!UICONTROL Add Assets]** option available in the toolbar to [upload a folder structure available on your local machine](add-delete.md).

Create a folder structure that works well with the business objectives for the organization. If you are uploading an existing folder structure to the Assets Essentials repository, you must review the structure. For more information, see [Best practices for effective permissions management](permission-management-best-practices.md).

## Manage permissions on folders {#manage-permissions-folders}

You can assign the following permissions to the user groups or users (not recommended):

| Permission Name | Description |
|-----|------|
| Can View |<ul><li>Read-access to view and navigate folders </li><li>Preview assets</li><li>Download assets</li><li>Copy assets</li><ul>  |
| Can Edit |<ul><li>All privileges available for Can View permissions </li><li>Create folders</li><li>Remove folders</li><li>Rename folders</li><li>Create assets</li><li>Update assets</li><li>Remove assets</li><ul>  |
| Owner |  <ul><li>All privileges available for Can Edit permissions</li><li>Manage permissions on a folder and its subfolders</li>This permission allows the administrators to delegate the admininstrator privileges to others for a folder and its subfolders.<ul>|
| Deny access | Remove Can View, Can Edit, and Owner permissions for a folder and its subfolders. |

### Assign permissions to user groups {#assign-permissions}

To assign permissions to user groups on folders:

1.


## Examples for effective permission management {#example-permission-management}