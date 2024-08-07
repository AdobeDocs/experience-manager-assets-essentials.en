---
title: Release Notes
description: Release Notes and known issues of [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
---
# Release notes of [!DNL Assets Essentials] {#release-notes}

The current release of Assets Essentials is released on July 25, 2024.

Some of the recently added features include:

**Content credentials integration**

Experience Manager Assets now supports content credentials for supported image formats. This provides information on the lineage of the asset and how it was created, including if it was modified using GenAI.

![Content credentials](/help/using/assets/content-credentials.png)

**Visual previews of folder contents**

Experience Manager Assets now displays visual previews of folder contents on the folder thumbnail when browsing or searching for content, which improves the discoverability of assets available within AEM Assets repository.

**Contextual Search**

You can now also search assets available in the repository by defining text prompts. Experience Manager Assets automatically transforms those text prompts to search filters and displays the search results. You can view and modify automatic filters using the Filters Pane to further narrow down the search results.

![storage usage insights](/help/using/assets/contextual-search-text-prompt1.png)

<!--

**Dynamic renditions**

You can now view and download dynamic renditions (including smart crops) in Experience Manager Assets. Dynamic renditions are customized versions of image assets created in real-time to meet specific needs, such as resizing images based on device resolution or cropping to fit different aspect ratios. These renditions enable organizations to deliver personalized and optimized experiences to diverse audience needs.

![storage usage insights](/help/using/assets/renditions-view-download.png)

-->

**In-place rename for assets and folders**

Experience Manager Assets now offers a simplified user experience by providing ability to rename an asset or a folder via single click.

**Express video quick actions**

Experience Manager Assets now includes easy and intuitive video editing tools powered by Adobe Express to increase content re-use and accelerate content velocity. The editing options include trimming, cropping, resizing a video, and also converting an MP4 to a GIF file.

![crop video with Adobe Express](/help/using/assets/adobe-express-crop-video.png)

>[!NOTE]
> Entitlements to access [!DNL Adobe Express] is required and at least one environment within AEM Assets. The environment can be any of the repositories within [!DNL Assets as a Cloud Service] or [!DNL Assets Essentials].

**Assign or remove metadata form to multiple folders**

A metadata form can now be assigned to or removed from multiple folders.

**Manage permissions for private collections**

You can allow administrators or non-administrators (other users) to manage access levels for private collections available in the repository. You can assign permissions such as `Can View` and `Can Edit` to the user groups or users. You can also delegate permission management privileges to user groups.


**Improvements based on customer feedback**

Enhancements and bug fixes based on customer feedback.


## Known issues {#known-issues}

The list of known issues of [!DNL Assets Essentials] offering is revised and updated on an ongoing basis.

<!--

* Assets Essentials does not support creating Private collections.

-->


<!--* Private collections are available to creator and the users with administrator privileges. As an administrator, you cannot delegate the permissions to access the collection to other users.-->

If you come across any issues or even enhancement requests, [provide feedback](#provide-feedback) to the team.

## Past releases {#past-releases}

### January 2024 release {#january-2024-release}

**Smart tags blocklist** 

Assets Essentials now enables you to define blocklist that comprises words that should not be added as Smart Tags to assets when they are uploaded to the repository. This capability helps you to maintain brand compliance and reduces effort to moderate Smart Tags.

  ![storage usage insights](/help/using/assets/block-tags.png)

**Create GenAI images with Adobe Firefly**

Create new images based on search queries with an integration of Adobe Firefly text-to-image feature (requires Adobe Firefly license).

 ![Assets Firefly integration](/help/using/assets/assets-firefly-integration.png)

**Find Similar Images**

You can now can easily find content by selecting an image and viewing similar images in the Experience Manager Assets repository.

**Embedded Adobe Express editor in AEM Assets**

 Users with access to Express now have integrated image editing and creation tools from Adobe Express and Adobe Firefly available directly within AEM Assets to improve content reuse and accelerate content velocity.

  ![assign metadata form to a folder](/help/using/assets/adobe-express-aem-assets.png)

**Storage usage reports in Insights**: 

Administrators now have the ability to view the storage usage reports available as part of Insights.

  ![storage usage insights](/help/using/assets/storage-usage-insights.png)

**Search first homepage configuration**

Assets Essentials now enables you to configure the homepage experience for your organization. If you select search first as the homepage, you can configure the search bar alignment, background image, and logo for your organization. Choosing [!UICONTROL General Settings] overrides the default landing page. For example, default landing is [!UICONTROL My Workspace] for administrators and [!UICONTROL Search First] for non-administrators, choosing any of the options under General Settings applies that to all users

  ![search first configuration](/help/using/assets/search-first-configuration.png)

### October 2023 release {#october2023-release}

**Bulk import assets from OneDrive data source**

Administrators now have the ability to [import a large number of assets from OneDrive to AEM Assets](/help/using/bulk-import-assets-view.md). The updated list for the supported data sources for bulk import includes Azure, AWS, Google Cloud, Dropbox, and OneDrive. 

  ![assign metadata form to a folder](/help/using/assets/bulk-import-source-details.png)

**Cross-Org Entitlement Support for Libraries**

Experience Manager Assets now enables you to configure access to Creative Cloud libraries in a different IMS Organization. It allows easier access to the latest cross-product workflows between Creative Cloud and Experience Manager and reduces time and effort for creatives.

### September 2023 release {#september2023-release}

**Assign metadata form to a folder**

You can now assign metadata form to a specific folder within your Assets Essentials deployment. All assets in the folder, including assets in the sub-folders, then display properties defined in the assigned metadata form.

![assign metadata form to a folder](/help/using/assets/assign-to-folder.png)

**Bulk import assets from data sources**

Administrators now have the ability to import large number of assets from a data source to AEM Assets. The administrators do not need to upload individual assets or folders to AEM Assets anymore. The supported data sources for bulk import include Azure, AWS, Google Cloud, and Dropbox.

![Bulk import assets from a data source](/help/using/assets/bulk-import.png)

**Image editing tools powered by Adobe Express**

Easy and intuitive image editing tools powered by Adobe Express available directly within AEM Assets to increase content re-use and accelerate content velocity.

![Image editing with Adobe Express](/help/using/assets/edit-adobe-express.png)

**Flexibility while pinning items for My Workspace Quick Access**

Ability to select and pin items for you, for your entire organization, or for a list of groups so that they display in the Quick Access section of My Workspace based on your selection.

![Pin items for groups](assets/pin-items-for-groups.png)


### July 2023 release {#july2023-release}

**Improved artificial intelligence framework for image Smart Tags**

Experience Manager Assets now uses an improved artificial intelligence framework for image Smart Tags. This content intelligence results in better relevancy and precision of Smart Tags available to all image assets on ingestion.

**Configure display of columns for Assets List view**

Assets Essentials now provides the ability to select the columns that display in the Assets List view, such as Status, Format, Dimensions, Size, and so on.

![Configure columns](/help/using/assets/configure-columns.png)

**Sort search results based on relevance**

Assets Essentials now sorts the search results based on Relevance, by default. You can sort the searched assets in increasing or decreasing order of `Name`, `Relevance`, `Size`, `Modified`, and `Created`.

### June 2023 release {#june2023-release}

**Hierarchical tagging of assets for faster search experience**

Flat lists of controlled vocabularies become unmanageable over time. Assets Essentials now supports hierarchical tagging structure, which facilitates applying relevant metadata, categorizing assets, supporting search, reusing tags, improving discoverability, and so on.

![Tagging Management](assets/tags-hierarchy.png)

**Pin files, folders, and collections for quick access**

You can now pin files, folders, and collections for faster access to these items when you need them later. The pinned items display in the **Quick access** section of My Workspace. You can access them using My Workspace instead of navigating to the location where they are saved within the repository.

![Tasks in Workspace](assets/quick-access.png)

**Filter assets in the Trash folder**

Assets Essentials now enables you to filter assets available in the Trash folder. You can apply standard or custom filters to search appropriate assets within the Trash folder to either restore or permanently delete them.

**Thumbnail previews for 3D assets**

Assets Essentials now generates thumbnail previews for common 3D file formats including gLB, USDz, FBX, 3DS, OBJ, and SBSAR. When these files are uploaded to Assets Essentials, thumbnails are automatically generated by the system, by default.

![Tasks in Workspace](assets/3d-preview.png)

**View top searched terms**

Assets Essentials now supports viewing top searched terms within your Assets Essentials deployment using the **Insights** section of My Workspace. You can also navigate to detailed Insights to view top searches during the last 30 days or 12 months.

![Tasks in Workspace](assets/insights-top-searches.png)

**Metadata form enhancements**

Assets Essentials now enables you to add multi-value text and drop-down list property components to the metadata forms.

### Multiple releases in 2023 {#multiple-releases-2023}

The list of recently added features include:

**Top downloaded assets**

My Workspace now displays the top ten most downloaded assets for your Assets Essentials environment in the [!UICONTROL Content] section. You can also view the format type and the number of downloads for each listed asset.

**Bulk updates to asset metadata**

Bulk metadata updates allow you to perform common metadata updates across multiple assets simultaneously. You do not need to update records individually and can quickly apply properties to assets or folders accessed through search. Additionally, bulk metadata updates overwrites any existing values, which means existing keywords are overwritten by the Bulk Metadata update.

**My Workspace with configurable widgets**

Assets now provides a customized workspace for you, which serves as a one-stop solution to provide convenient access to key areas of the Assets user interface and information that is most relevant to you. Faster access to these options increases the content velocity and efficiency of your projects.

My Workspace includes widgets for Insights, Tasks, and Content. You can configure how these widgets are displayed in your Workspace based on your preferences.

**Dedicated task management UI**

Assets Essentials now enables you to manage the list of tasks currently assigned to you, created by you, and already completed by you at a centralized location, using the new **[!UICONTROL Tasks]** option available in the left navigation pane. You can also take appropriate actions by selecting a task to approve or reject it or opening the task details to approve, reject, edit, or delete it.

![Tasks in Workspace](assets/tasks-workspace.png)

**Auto-generated links to share assets**

Assets Essentials now generates a link automatically as soon as you choose to share an asset using the Assets Essentials user interface. The generated link remains valid even if you change the expiration date.

![Tasks in Workspace](assets/share-asset.png)


**Improvements based on customer feedback**

Enhancements and bug fixes based on customer feedback.

### 2022.11.0 {#november-2022}

The November release of [!DNL Assets Essentials] is released on November 17, 2022.

This release provides:

**Preview documents using Document Cloud Viewer**

Assets Essentials now allows you to upload documents in other supported format types and preview them using the included Document Cloud viewer. The supported format types include TXT, RTF, DOC, DOCX, PPT, PPTX, XLS, and XLSX.

<!--

**View Smart Tags moderation reports**

Asset reporting now provides administrators with visibility into the Smart Tags promoted or deleted for an asset. You can specify a folder path and the report lists the Smart Tags promoted or deleted for all assets available at the folder path.

-->

<!--
**Read-only access to large number of users**

Assets Essentials allows administrators to provide read-only access to a large number of users for selected assets or folders in the repository. 
You can easily synchronize the user groups available on the external identity management of an organization with Adobe Admin Console and then manage permissions in Admin Console and Assets Essentials to provide the users with read-only access for selected assets or folders.

-->


**New Save metadata option**

A new Save metadata option is now available on the Assets Essentials user interface for better metadata governance.

**Improvements based on customer feedback**

Enhancements and bug fixes based on customer feedback.

**Adobe Asset Link version 3.3**

[Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html) version 3.3 is released on December 13, 2022, with the following features:

* Support for [Creative Cloud for teams](https://www.adobe.com/creativecloud/business/teams.html) in addition to supporting [Creative Cloud for enterprise](https://www.adobe.com/creativecloud/business/enterprise.html) before.

* Support for the latest Adobe InDesign, Photoshop, and Illustrator 2023 applications.

* Support for using the Adobe Asset Link CEP Plugin in environments with proxy servers.

### 2022.8.0 {#august-2022}

The August release of [!DNL Assets Essentials] is released on August 22, 2022. 

This release provides:

**Notifications for collections**

Assets Essentials notifications now enable you to monitor the operations performed on the collections available in the repository. You need to select and subscribe to the collections for which the notifications are sent to you. You can also configure the operations for which the notifications are sent such as delete, share link, move, rename, and update operations performed on collections.

**Edit Smart Collections**

Assets Essentials now also provides the ability to edit the search criteria used while creating a smart collection.  Save the new search criteria to update the collection contents dynamically.

**View live statistics for storage account**

Assets Essentials now also enables you to view real-time storage account data for your Assets Essentials environment with the Live Statistics dashboard. You can view real-time event metrics for the last 30 days or for the last 12 months.

**View upload reports**

Asset reporting now provides administrators with visibility into assets uploaded to the Adobe Experience Manager Assets Essentials deployment. Administrators already have the ability to generate reports for the assets downloaded from the Assets Essentials deployment. This data provides useful information about how users interact with content and the product. 

**Improvements based on customer feedback**

Enhancements and bug fixes based on customer feedback.

### 2022.6.0 {#june-2022}

The June release of [!DNL Assets Essentials] is released on July 14, 2022. 

This release provides:

**Smart Collections**

Save your search results as a Smart Collection to dynamically update the collection contents. If there are assets added to the Assets Essentials repository that fit the search criteria defined while [creating the Smart Collection](manage-collections.md#create-smart-collection), the contents of the Smart Collection get updated automatically.

**Notifications**

Assets Essentials notifications enable you to [monitor the operations performed on the assets or folders available in the repository](manage-notifications.md). You need to select and subscribe to the content for which the notifications are sent to you. You can also configure the categories for which the notifications are sent to you.

**Reporting**

Asset reporting lets administrators assess the user activity within Adobe Experience Manager Assets Essentials. The reports and live statistics dashboard provide useful information about how users interact with assets available in your deployment. [Use the information in the reports](manage-reports.md) to derive key success metrics to measure the adoption of Assets within your enterprise and by customers.

View asset download reports and live statistics dashboard module to see which assets are being downloaded and the frequency of downloads.

### 2022.5.0 {#may-2022}

The May release of [!DNL Assets Essentials] is released on June 16, 2022. 

This release provides:

**Asset Status enhancements**

* Assets Essentials now enables you to [set an expiration date for an asset](manage-organize.md#set-asset-status). In addition, you can [filter assets](search.md#refine-search-results) based on the `Expired` asset status and an expiration date range.

* You can now view the asset status indicator for all assets available in Trash. As a result, you can take a decision to restore an asset based on its status.

**Search filters enhancements**

* Assets Essentials now enables you to [filter assets](search.md#refine-search-results) using the `No Status` asset status.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Collections enhancements**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials now supports [downloading a collection](manage-collections.md).

* You can now edit the Description metadata field for a collection.

**Documentation enhancements**

* A new version of the [Assets Essentials overview documentation](introduction.md) is now available.

**Improvements based on customer feedback**

* Enhancements and bug fixes based on customer feedback.

### 2022.4.0 {#april-2022}

The current release of [!DNL Assets Essentials] is released on May 12, 2022. This release provides:

* [!DNL Assets Essentials] now supports [creating collections](manage-collections.md). A collection is a set of assets within Experience Manager Assets Essentials. Use collections to share assets between users. Unlike folders, a collection can include assets from different locations.

* Assets Essentials now also enables you to [add custom filters](search.md#custom-filters) to the user interface. You can then apply those custom filters in addition to the standard filters to refine your search results.

* Assets Essentials now allows you to [set status](manage-organize.md#set-asset-status) on assets available in the repository. Set an asset status to better govern and manage downstream consumption of digital assets.

* Enhancements and bug fixes based on customer feedback.

#### Incognito mode in Chrome {#incognito-mode}

With this release, we are optimizing performance of the UI delivery and specific features in Assets Essentials - commenting on assets and image editing - depends on browser local storage and third-party cookies being enabled. The incognito mode in the Chrome web browser blocks third-party cookies by default - users have a number of options to continue to access to all capabilities:

* Use Chrome Profiles instead of Incognito mode, when user needs to separate browser sessions

* Turn off the `Block third-party cookies` on the Incognito mode screen in Chrome

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

* Integrations with [!DNL Adobe Workfront] that lets [!DNL Workfront] users manage their digital assets in the context of managing their work.

### 2021.7.0 release {#july2021}

[!DNL Assets Essentials] 2021.7.0 is released on July 29, 2021, with the following updates:

* You can create and manage customized metadata forms to be used for displaying metadata properties to users in the asset detail screen in [!UICONTROL Metadata Forms] option under [!DNL Settings]. See [metadata forms](metadata.md#metadata-forms).
* Various bug fixes and product improvements, including better performance when uploading a nested folder with many subfolders.

### 2021.6.0 release {#june2021}

The first release of [!DNL Assets Essentials], made available on June 21, 2021, offers lightweight asset management capabilities. It supports the following major features and CRUD (Create, Read, Update, and Delete) operations:

* Upload and add assets, including nested folders. Preview the assets and versions.
* Full-text search, nuanced search filters, and saved searches for rapid asset discovery.
* Basic asset management operations like update, delete, download, and manage metadata.
* [!DNL Assets Essentials] is available to [!DNL Adobe Journey Optimizer] users to manage the assets when creating messages.
