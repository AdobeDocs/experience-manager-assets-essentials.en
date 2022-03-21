---
title: [!DNL Assets Essentials] user interface
description: Understand user interface of and navigation in [!DNL Assets Essentials].
role: User
---

# Integrate Assets Essentials with Creative Cloud applications {#integrate-assets-essentials-creative-cloud-applications}

![Preference to switch dark and light theme](assets/cce-next-banner-1.jpeg)

## The story so far

After [configuring Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) in the first article of this tutorial, you can build on to integrate the Creative Cloud applications with Assets Essentials.

## Objective

* **Audience**: Creative Cloud administrators

* **Objective**: Integrate Assets Essentials with Creative Cloud applications so that you can use Adobe Asset link in-app panel to connect to [!DNL Assets Essentials] repository from within the supported [!DNL Adobe Creative Cloud] desktop apps.

## Overview

[Adobe Asset Link in-app panel](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) lets creative professionals connect to [!DNL Assets Essentials] repository from within the supported [!DNL Adobe Creative Cloud] desktop apps. The panel is available for [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], and [!DNL Adobe XD]. It streamlines the access to assets that in turn increases content velocity.

Creative Cloud application users can view the Adobe Asset Link in-app panel only when you integrate the Creative Cloud applications with the AEM Assets Essentials repository.

Execute the following tasks to integrate Assets Essentials with Creative Cloud applications:

* [Create directory trusting between Creative Cloud and Experience Cloud admin console](#directory-trusting-cc-assets-essentials-consoles)

* [Add Creative Cloud users to Assets Essentials product profiles](#add-cc-users-assets-essentials-product-profiles)

* [Install Adobe Asset Link](#install-asset-link)

* [Use Adobe Asset Link](#use-asset-link)

## Create directory trusting between Creative Cloud and Experience Cloud admin consoles {#directory-trusting-cc-assets-essentials-consoles}

To integrate Creative Cloud and Assets Essentials applications, the users that are available in Admin Console for Creative Cloud must be made available in Admin Console for Experience Cloud.

On the Experience Cloud Admin Console, click **[!UICONTROL Settings]** and use the **[!UICONTROL Directories]** tab to create a new directory to establish [directory trusting](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) between the two admin consoles.

## Add Creative Cloud users to Assets Essentials product profiles {#add-cc-users-assets-essentials-product-profiles}

After establishing directory trusting between the Admin Console for Creative Cloud and Admin Console for Experience Cloud, assign the Creative Cloud users to one of the following Assets Essentials product profiles:

* **[!DNL Assets Essentials] Administrators** have administrative access to the application. In addition to all end-user capabilities, application administrators in this group can manage permissions for any folder and group/user in the whole application repository.
* **[!DNL Assets Essentials] Users** have access to the complete user interface. These users can upload, organize, tag, and find digital assets.
* **[!DNL Assets Essentials] Consumer Users**: have access to the embedded asset selection experience in [!DNL Adobe Journey Optimizer] email template editor. For more information, see [Use [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

For more information on how to assign users to Assets Essentials product pofiles, see [Assign users to Assets Essentials product profiles](adminster-aem-assets-essentials.md)

## Install Adobe Asset Link {#install-asset-link}

Greg to add the steps


## Use Adobe Asset Link {#use-asset-link}

You can now use Adobe Asset Link with Photoshop, Illustrator, or InDesign. To open the panel in InDesign or Illustrator, go to Windows > Extensions > Adobe Asset Link. In Photoshop, go to Window > Extensions (legacy) > Adobe Asset Link.

Use Adobe Asset Link to work with and modify assets stored in Assets Essentials repository. You can perform various tasks, such as:

* Search and browse assets

* Upload assets

* Sort and filter assets

* Place, download, and drag an asset

* Check out and Check in an asset

* View version history and file details

For instructions on how to perform these tasks, see [Manage assets using Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## What's Next

Now that you have  integrated the Creative Cloud applications with Assets Essentials, integrate Adobe Workfront with Experience Manager Assets Essentials as well.
