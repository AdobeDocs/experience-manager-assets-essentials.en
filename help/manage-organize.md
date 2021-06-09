---
title: Manage your digital assets
description: Upload, download, delete, move, copy, rename, and edit your assets in [!DNL Assets Essentials].
role: Business Practitioner,Leader
contentOwner: AG
---

# Manage assets {#manage-assets}

Use [!DNL Assets Essentials] to accomplish the following asset management tasks. When you select an asset, the following options display in the toolbar at the top.

![Toolbar options when you select an asset](assets/toolbar-asset-selected.png)

* ![deselect icon](assets/do-not-localize/close-icon.png) Deselect the selection.
* ![details icon](assets/do-not-localize/edit-in-icon.png) Click to preview an asset and view the detailed metadata. When previewing, you can view the versions and edit an image.
* ![download icon](assets/do-not-localize/download-icon.png) Download the selected asset to your local file system. You do not see a download option for a folder.
* ![delete icon](assets/do-not-localize/delete-icon.png) Delete the selected asset or folder.
* ![copy icon](assets/do-not-localize/copy-icon.png) Copy the selected file or folder.
* ![move icon](assets/do-not-localize/move-icon.png) Move the selected asset or folder to a different location in the repository hierarchy.
* ![rename icon](assets/do-not-localize/rename-icon.png) Rename the selected asset or folder. Use a unique name else rename fails with a warning.

You can view the same options on assets thumbnails.

![Options on asset thumbnail to manage an asset](assets/options-on-thumbnail.png)

## Asset versioning {#create-versions}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] allows you to save multiple versions of the same asset. Having versions lets you review historical assets and revert to a previous version if needed. Asset versions are created in the following scenarios:

* Upload a new asset with the same filename as an existing asset and in the same folder as the existing asset. [!DNL Assets Essentials] prompts to either overwrite the previous asset or save the new asset as a version. See [upload duplicate assets](/help/add-delete.md#resolve-upload-fails).

  ![Create versions when uploading](assets/uploads-manage-duplicates.png)

* After editing an image, click **[!UICONTROL Save as Version]** to save the new image. See [edit images](/help/edit-images.md).

  ![Save edited image as a version](assets/edit-image2.png)

  *Figure: Save edited image as a version.*

* Open the versions of an existing asset. Click **[!UICONTROL New Version]** and upload a newer version of the asset in the repository.

  ![Option to upload a new version of an asset from the version history](assets/view-asset-versions2.png)

### View versions of an asset {#view-versions}

When uploading a duplicate copy or a modified copy of an asset, you can create its versions. Versioning lets you review historical assets and revert to a previous version if needed.

To view versions, open an asset's preview and click **[!UICONTROL Versions]** ![Versions icon](assets/do-not-localize/versions-clock-icon.png) from the right sidebar. To preview a specific version, select it. To revert to it, click **[!UICONTROL Make Latest]**.

You can also create versions from the versions timeline. Select the latest version, click **[!UICONTROL New Version]**, and upload a new copy of the asset from your local file system.

![View versions of an asset](assets/view-asset-versions1.png)

*Figure: View versions of an asset, revert to a previous version, or upload another new version.*