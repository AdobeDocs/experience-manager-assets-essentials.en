---
title: Release Notes
description: Release Notes and known issues of [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
---
# Release notes of [!DNL Assets Essentials] {#release-notes}

The current release of [!DNL Assets Essentials] is released on May 05, 2022. This release provides:

* [!DNL Assets Essentials] now supports [creating collections](manage-collections.md). A collection is a set of assets within Experience Manager Assets Essentials. Use collections to share assets between users.

  Unlike folders, a collection can include assets from different locations. You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.

* Assets Essentials now also enables you to [add custom filters](search.md#custom-filters) to the user interface. You can then apply those custom filters in addition to the standard filters to refine your search results.

* Assets Essentials now allows you to [set status and expiration date](manage-organize.md#set-asset-status) on assets available in the repository. Set an asset status to better govern and manage downstream consumption of digital assets.

* Enhancements and bug fixes based on customer feedback.



## Known issues {#known-issues}

The list of known issues of [!DNL Assets Essentials] offering is revised and updated on an ongoing basis:

* None

If you come across any issues or even enhancement requests, [provide feedback](#provide-feedback) to the team.

## Past releases {#past-release}

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] is released on March 09, 2022, with the following updates:

* [!DNL Assets Essentials] now enables you to [generate a link and share assets with external stakeholders](share-links-for-assets.md), who do not have access to the [!DNL Assets Essentials] application. You can define an expiration date for the link and then share it with others using your preferred communication method like email or messaging services. Recipients of the link can preview assets and download them.

* The [!DNL Assets Essentials] now comprises [an administrator product profile](deploy-administer.md#add-users-to-essentials) on Admin Console in addition to the existing regular and consumer user product profiles. An administrator can now assign other users to the administrator product profile.

* Assets Essentials now allows the administrators to [manage the access levels for folders available in the repository](manage-permissions.md). As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the folder-level.

* Enhancements and bug fixes based on customer feedback.

In addition, [!DNL Adobe Asset Link] extension for Creative Cloud (Photoshop, Illustrator, and InDesign) released a [new version 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html), with performance improvements in the panel startup time and in download speed.


### 2022.1.0 release {#january-2022}

[!DNL Assets Essentials] is released on February 03, 2022, with the following updates:

* Performance improvements for the [!UICONTROL Create Folder] operation. <!-- CQ-4338818 -->

### 2021.11.0 release {#november-2021}

[!DNL Assets Essentials] is released on December 16, 2021, with the following updates:

* Adobe deploys Assets Essentials automatically after completing the provisioning process. The administrators do not need to perform additional steps to deploy Assets Essentials using [!DNL Cloud Manager] user interface. This automatic deployment will be available for environments provisioned after 6 January 2022.
* New versions of Creative Cloud plugins working with Assets Essentials are available on Adobe Exchange - [Adobe Asset Link for Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) and [Adobe Asset Link for Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Various bugfixes and product enhancements, including previous known issues (folders now display correctly in the left navigation tree after upload<!-- CQ-4337638 -->, drag and drop upload allows user to select either current folder or any subfolder when dropping for upload<!-- CQ-4327753 -->).

### 2021.8.0 release {#august2021}

[!DNL Assets Essentials] 2021.8.0 is released on August 30, 2021, with the following updates:

* Integrations with [!DNL Adobe Workfront] that lets [!DNL Workfront] users manage their digital assets in the context of managing their work. For more information, see [integrations with other Adobe solutions](/help/integration.md).

### 2021.7.0 release {#july2021}

[!DNL Assets Essentials] 2021.7.0 is released on July 29, 2021, with the following updates:

* You can create and manage customized metadata forms to be used for displaying metadata properties to users in the asset detail screen in [!UICONTROL Metadata Forms] option under [!DNL Settings]. See [metadata forms](metadata.md#metadata-forms).
* Various bug fixes and product improvements, including better performance when uploading a nested folder with many subfolders.

### 2021.6.0 release {#june2021}

The first release of [!DNL Assets Essentials], made available on June 21, 2021, offers lightweight asset management capabilities. It supports the following major features and CRUD (create, read, update, and delete) operations:

* Upload and add assets, including nested folders. Preview the assets and versions.
* Full-text search, nuanced search filters, and saved searches for rapid asset discovery.
* Basic asset management operations like update, delete, download, and manage metadata.
* [!DNL Assets Essentials] is available to [!DNL Adobe Journey Optimizer] users to manage the assets when creating messages. For more information, see [integrations with other Adobe solutions](/help/integration.md).
