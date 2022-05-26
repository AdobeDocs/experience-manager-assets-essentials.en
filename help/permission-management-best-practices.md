---
title: How to effectively manage folder permissions?
description: Best practices for effective permissions management
exl-id: 06b06f0b-3806-44ce-abc4-c1449a93dd29
---
# Best practices for effective permissions management {#best-practices-permissions-management}

As an administrator, before you start managing the folder permissions for the Assets Essentials repository, there are various best practices that you can implement to make the infrastructure intuitive for administrators and end users later while managing operations.

You can  incorporate these best practices while:

* [Creating user groups in Admin Console](#admin-console-best-practices)

* [Creating folder structure in Assets Essentials repository](#folder-structure-assets-essentials)

* [Managing permissions in Assets Essentials repository](#folder-permissions)

## Admin Console {#admin-console-best-practices}

Identify access needs based on user groups in your organization. Plan and create user groups for your organization and add users to those user groups. It is easier to manage folder permissions based on user groups and not individual users.

## Folder structure for Assets Essentials repository {#folder-structure-assets-essentials}

Consider the following points when you start planning to create a folder structure in the Assets Essentials repository:

* Future governance: The folders that are governed by administrators and the folders that are [delegated for permissions to other users as owners](manage-permissions.md##manage-permissions-folders).

* Scalable: The folder structure should adhere to your organization's future needs and should be easily scalable.

* Size: A folder must not contain too many assets. It might lead to usability issues and can become difficult to manage.

* Intuitive: The folder structure should be easy to browse and intuitive for the end users. Users should be able to easily identify where to upload a new asset in the folder structure.

There are various possible folder structure types that you can use for your organization. The following are a few examples of typical folder structures: 

* Function and categorization based

   ![Function and Categorization](assets/function-categorization.png)

* Campaign based

   ![Caampaign Based](assets/campaign-based.png)

* Offer location (or channel) based

   ![Offer Location Based](assets/offer-location.png)


## Folder permissions {#folder-permissions}

After creating user groups for your organization, adding users to those user groups, and selecting and creating a folder structure in the Assets Essentials repository that suits your organization's needs, you can start managing folder permissions for your organization. Consider the following points when you start managing folder permissions:

* Apply permissions for user groups, not individual users. This results in a simpler, more efficient permissions structure.

* Keep the permission structure as simple as possible for operational efficiency.

* Use Deny access permissions carefully and prefer to apply positive permissions (Can Edit, Can View, Owner) to the folder structure.

For examples on how to achieve an efficient and simple folder structure, see [Manage permissions on folders](manage-permissions.md##manage-permissions-folders).

## Next Steps {#next-steps}

* Provide product feedback using the [!UICONTROL Feedback] option available on the Assets Essentials user interface

*  Provide documentation feedback using [!UICONTROL Edit this page] ![edit the page](assets/do-not-localize/edit-page.png) or [!UICONTROL Log an issue] ![create a GitHub issue](assets/do-not-localize/github-issue.png) available on the right sidebar

* Contact [Customer Care](https://experienceleague.adobe.com/?support-solution=General#support)
