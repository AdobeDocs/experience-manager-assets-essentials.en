---
title: Integrate Assets Essentials with Creative Cloud applications
description: Integrate Assets Essentials with Creative Cloud applications so that you can use Adobe Asset link in-app panel to connect to [!DNL Assets Essentials] repository from within the supported [!DNL Adobe Creative Cloud] desktop applications.
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
---
# Integrate Assets Essentials with Creative Cloud applications {#integrate-assets-essentials-creative-cloud-applications}

![Preference to switch dark and light theme](assets/cce-creative-cloud.png)

## The story so far

After [configuring Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) in this tutorial, you can build on the experience to integrate the Creative Cloud applications with Assets Essentials.

## Objective

* **Audience**: Creative Cloud administrators

* **Objective**: Integrate Assets Essentials with Creative Cloud applications so that your creative users can use Adobe Asset link in-app panel to connect to [!DNL Assets Essentials] repository from within the supported [!DNL Adobe Creative Cloud] desktop applications.

## Overview

[Adobe Asset Link in-app panel](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) lets creative professionals connect to [!DNL Assets Essentials] repository from within the supported [!DNL Adobe Creative Cloud] desktop apps. The panel is available for [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], and [!DNL Adobe XD]. It streamlines access to assets, which in turn helps increase content velocity.

Creative Cloud application users can use the Adobe Asset Link in-app panel only when you integrate the Creative Cloud applications with the Experience Manager Assets Essentials repository.

Execute the following tasks to integrate Assets Essentials with Creative Cloud applications:

* [Create directory trusting between Creative Cloud and Experience Cloud Admin Console](#directory-trusting-cc-assets-essentials-consoles)

* [Add Creative Cloud users to Assets Essentials product profiles](#add-cc-users-assets-essentials-product-profiles)

* [Install Adobe Asset Link](#install-asset-link)

* [Use Adobe Asset Link](#use-asset-link)

## Create directory trusting between Creative Cloud and Experience Cloud Admin Consoles {#directory-trusting-cc-assets-essentials-consoles}

If your Creative Cloud is deployed in a separate Adobe Admin Consle from the one with Assets Essentials (Experience Cloud solution), you need to add trust relationship between the two consoles.

To integrate Creative Cloud and Assets Essentials applications, the users that are available in Admin Console for Creative Cloud must be made available in Admin Console for Experience Cloud. If Creative Cloud and Assets Essentials are deployed into separate Admin Consoles, trust relationship between them is required to enable this.

On the Experience Cloud Admin Console, click **[!UICONTROL Settings]** and use the **[!UICONTROL Directories]** tab to create a directory to establish [directory trusting](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) between the two Admin Consoles.

## Add Creative Cloud users to Assets Essentials product profiles {#add-cc-users-assets-essentials-product-profiles}

After establishing directory trusting between the Admin Console for Creative Cloud and Admin Console for Experience Cloud, assign the Creative Cloud users to the **[!DNL Assets Essentials] Users** product profile under the [!DNL Assets Essentials] product card in the Experience Cloud Admin Console. It will let Creative Cloud users to access Assets Essentials from their Adobe Asset Link plugin panel; in addition, it will give them access to the full Assets Essentials web User Interface to upload, organize, tag and find digital assets using a web browser.

Other Assets Essentials product profiles - **[!DNL Assets Essentials] Administrators** and **[!DNL Assets Essentials] Consumer Users** - are used for different user entitlements (application administrators and users accessing Assets Essentials via Experience Cloud integrations).

For more information on how to assign users to Assets Essentials product profiles, see [Assign users to Assets Essentials product profiles](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Install Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] plugin can be installed and made available to creative users in two ways:

* Creative users can install the plugin from their [!DNL Creative Cloud Desktop] application
* Creative Cloud administrator can add Asset Link plugin to a Creative Cloud package in Admin Console

The choice depends on organization IT policies. 

**Installation using [!DNL Creative Cloud Desktop] application** is described [here](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). There are two plugins available and hosted on [Adobe Exchange](https://exchange.adobe.com/) marketplace, depending on the Creative Cloud application: 

* For [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], and [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* For [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installation with a Creative Cloud package** is done by Creative Cloud administrator in Admin Console, by including the Asset Link plugin when building a deployment package, that can later be deployed to user machines. In the managed Choose Plugins screen, search for **Adobe Asset Link** in the **Featured business plugins** section. For more information, see [packaging apps via the Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Use Adobe Asset Link {#use-asset-link}

Creative users can now use Adobe Asset Link with Photoshop, Illustrator, InDesign, or XD. To open the panel in InDesign or Illustrator, go to Windows > Extensions > Adobe Asset Link. In Photoshop, go to Window > Extensions (legacy) > Adobe Asset Link.

For information on how to setup Adobe Asset Link for Adobe XD, click [here](https://helpx.adobe.com/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>When working on Apple Silicon / M1 hardware, Adobe Photoshop needs to be started using Rosetta compatibility mode to ensure creative users have access to Adobe Asset Link panel, as it is built using the CEP extension technology. For more information, see [Photoshop for Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Use Adobe Asset Link to work with and modify assets stored in Assets Essentials repository. You can perform various tasks, such as:

* Search and browse assets

* Upload assets

* Sort and filter assets

* Place, download, and drag an asset

* Check out and Check in an asset

* View version history and file details

For instructions on how to perform these tasks, see [Manage assets using Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## What's Next

Now that you have  integrated the Creative Cloud applications with Assets Essentials, [integrate Adobe Workfront with Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
