---
title: "[!DNL Assets Essentials] user interface"
description: Understand user interface of and navigation in [!DNL Assets Essentials].
role: User
exl-id: 534a8084-88f7-410e-b872-719e47e62b10
---
# Navigate to files and folders and view assets {#view-assets-and-details}

<!-- TBD: Give screenshots of all views with many assets. Zoom out to showcase how the thumbnails/tiles flow on the UI in different views. -->

<!-- TBD: The options in left sidebar may change. Shared with me and Shared by me are missing for now. Update this section as UI is updated. -->

## Understand the [!DNL Assets Essentials] user interface {#understand-interface-navigation}

[!DNL Assets Essentials] offers an intuitive and user-friendly user interface. The clean interface makes assets and related information easy to find and remember.

When you log into [!DNL Assets Essentials], you see the following interface.

![[!DNL Assets Essentials] user interface](assets/essentials-interface.png)

**A**: Left sidebar to browse repository and provides access to a few other options **B**: Display or collapse the left sidebar to increase asset-viewing area **C**: Filter search results **D**: Select all contents of the selected folder **E**: Options to sort assets **F**: Search box **G**: Upload or drag and drop files using `Add Assets` button **H**: Create a new folder **I**: Switch between different views

<!-- TBD: Need an embedded video here with narration. It has to be hosted on MPC to be embeddable. -->

## Browse and view assets and folders {#browse-repository}

You can browse the folders from the main user interface or from the left sidebar. Experience Manager Assets now displays visual previews of folder contents on the folder thumbnail when browsing or searching for content, which improves the discoverability of assets available within AEM Assets repository. This folder thumbnail saves your time spent on searching specific assets within a folder in AEM Assets Repository.
When browsing through assets in a folder, you can use the interface to view asset thumbnails to visually browse the repository or view asset details to quickly find the asset you want. The options available in the left sidebar are:

* [My Workspace](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/my-workspace.html?lang=en): Assets now includes a customizable workspace that provides widgets for convenient access to key areas of the Assets user interface and information that is most relevant to you. This page serves as a one-stop solution to provide an overview of your work items and to give quick access to key workflows. More convenient access to these options increases your efficiency and content velocity.
* [Tasks](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/my-workspace.html?lang=en): You can view the tasks assigned to you under **My tasks** tab. Whereas, the tasks that are created by you can be viewed under **Assigned tasks** tab. Additionally, the tasks that you complete are located under **Completed tasks** tab.
* [Assets](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-organize.html?lang=en): List of all folders in a tree view, that you have access to.
* **Recently Viewed**: List of assets that you previewed recently. [!DNL Assets Essentials] displays only the assets that you preview. It does not display the assets that you scroll past when browsing the repository files or folders.
* [Collections](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-collections.html?lang=en): A collection is a set of assets, folders, or other collections within Adobe Experience Manager Assets Essentials. Use collections to share assets between users. Unlike folders, a collection can include assets from different locations. You can share multiple collections with a user. Each collection contains references to assets. The referential integrity of assets is maintained across collections.

* [Insights](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-reports.html?lang=en#view-live-statistics): In [!DNL Assets Essentials], you can view real-time insights on your dashboard. Assets Essentials enables you to view real-time data for your Assets Essentials environment with the Insights dashboard. You can view real-time event metrics during the last 30 days or for the last 12 months. 


* **Trash**: List the assets deleted from the root **[!UICONTROL Assets]** folder. You can select an asset in the Trash folder to restore it to its original location or permanently delete it. You can specify a keyword or apply filters such as asset status, file type, mime type, image size, asset creation, modification, and expiration dates, as well as filtering by assets discarded by the current user. You can also apply custom filters to search appropriate assets within the Trash folder. For more information on using standard and custom filters, see how to [search assets in Assets Essentials](search.md).

* **Settings**: You can configure various options of Assets Essentials using **Settings**, such as, Metadata forms, Reports, and Taxonomy Management.

<!-- TBD: Not sure if we want to publish these right now. CC Libs are beta as per Greg.
* **Libraries**: Access to [!DNL Adobe Creative Cloud Team] (CCT) Libraries view. This view is visible only if the user is entitled to CCT Libraries.
-->

<!-- TBD: My Work Space shows task inbox and it is not visible on AEM Cloud Demos as of now. It is the source of truth server hence not documenting My Work Space option for now.
-->

You can open or collapse the left sidebar to increase the available asset-viewing area.

In [!DNL Assets Essentials], you can view assets, folders, and search results in four different types of layouts:

* ![list view icon](assets/do-not-localize/list-view.png) [!UICONTROL List View]
* ![grid view icon](assets/do-not-localize/grid-view.png) [!UICONTROL Grid View]
* ![gallery view icon](assets/do-not-localize/gallery-view.png) [!UICONTROL Gallery View]
* ![waterfall view icon](assets/do-not-localize/waterfall-view.png) [!UICONTROL Waterfall View]

To locate an asset, you can sort the assets in ascending or descending order of `Name`, `Relevancy`, `Size`, `Modified`, and `Created`.

To navigate in a folder, double-click on the folder's thumbnails or select the folder from the left sidebar. To view details of a folder, select it and click Details from the toolbar at the top. To navigate up and down the hierarchy, either use the left sidebar or use the breadcrumbs at the top.

![Browse folders](assets/browsing-folders.png)

*Figure: To browse the hierarchy, use the breadcrumbs at the top or the left sidebar.*

## Preview assets {#preview-assets}

Before you use, share, or download an asset, you can view it more closely. The preview feature lets you view not just the images but a few other supported asset types.

To preview an asset, select it and click [!UICONTROL Details] ![details icon](assets/do-not-localize/edit-in-icon.png) from the toolbar at the top. You can not only view the asset but also view its detailed metadata and take other actions.

![Preview an asset](assets/preview-asset-2.png)

**A**: Return to the current folder or current search result in the repository **B**: Name and format for the file you are previewing **C**: Assign tasks **D**: Advanced metadata **E**: Keywords and smart tags **F**: Comment and annotate **G**: View tasks related to the selected Asset **H**: View and manage versions **I**: View renditions of the image **J**: Edit image **K**: Basic metadata **L**: Advanced metadata **M**: Keywords and smart tags **N**: Preview more closely. Zoom, full screen, and other options **O**: Proceed to previous or next asset in the current folder without going back to the folder

You can also preview videos.

![Video preview](/help/using/assets/preview-video.png)

If you explicitly preview an asset, then [!DNL Assets Essentials] displays it as a recently viewed asset.

<!-- TBD: Describe the options.

Explicitly previewed assets are displayed as recently viewed assets. Give screenshot of this.
Other use cases after previewing.
-->

## Configure display of columns for Assets List view {#configure-columns-list-view}

You can select the columns that display in the Assets List view, such as Status, Format, Dimensions, Size, and so on:

1. Select **[!UICONTROL Assets]** from the left navigation pane, switch to the Assets List view, and click ![settings icon](assets/settings-icon.svg).

1. Select the columns that you need to display in the List view and click **[!UICONTROL Confirm]**.

   ![Configure columns](/help/using/assets/configure-columns.png)

## Next Steps {#next-steps}

* Provide product feedback using the [!UICONTROL Feedback] option available on the Assets Essentials user interface

*  Provide documentation feedback using [!UICONTROL Edit this page] ![edit the page](assets/do-not-localize/edit-page.png) or [!UICONTROL Log an issue] ![create a GitHub issue](assets/do-not-localize/github-issue.png) available on the right sidebar

* Contact [Customer Care](https://experienceleague.adobe.com/?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [View versions of an asset](/help/using/manage-organize.md#view-versions).
