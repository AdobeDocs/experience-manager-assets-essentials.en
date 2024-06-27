---
title: Edit images
description: Edit images using [!DNL Adobe Express] powered options and save updated images as versions.
role: User
exl-id: fc21a6ee-bf23-4dbf-86b0-74695a315b2a
---
# Edit images in [!DNL Assets Essentials] {#edit-images-in-asset-essentials}

The Asset Essentials UI enables basic image editing, including resizing, background removal, cropping, and converting between JPEG and PNG formats. Additionally, it allows advanced editing through integration with Adobe Express. After editing an image, you can save the new image as a new version. Versioning helps you to revert to the original asset later if needed. To edit an image, [open its preview](https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/navigate-view#preview-assets) and click **Edit Image**. 

>[!NOTE]
>
>You can edit images of PNG and JPEG file types using Adobe Express.

<!--The editing actions that are available are Spot healing, Crop and straighten, Resize image, and Adjust image.-->

## Edit Image {#edit-images}

Land on Asset Essentials UI, using the link - [Asset Essentials UI](https://experience.adobe.com/#/assets) and selecting the right repository. To receive access, contact your organization's administrator.
For any additional reference information refer - [Get started using Adobe Experience Manager Assets Essentials](https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/get-started), [understanding of the user interface](https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/navigate-view), [Asset essentials use cases](https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/get-started#use-cases) and [known issues](https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/release-notes).
<!--
>[!CONTEXTUALHELP]
>id="assets_express_integration"
>title="Adobe Express Integration"
>abstract="Easy and intuitive image-editing tools powered by Adobe Express available directly within AEM Assets to increase content reuse and accelerate content velocity."-->

### Edit Image on Essentials UI using Adobe Express {#edit-image-on-essentials-ui-using-adobe-express}

After landing on Essentials UI, click **Assets**, select an image, and then click **Edit** from the top rail. The new screen displays the available editing options including resizing, background removal, cropping, and converting between JPEG and PNG formats. 

#### Resize image {#resize-image-using-express}

Resizing an image to a specific size is a popular use case. Assets Essentials lets you quickly resize images to fit the common photo sizes by providing pre-calculated new resolutions for specific photo sizes. To resize the image using Assets Essentials, follow the steps below: 

1. Click **Resize Image** from the left pane. 
2. Select the appropriate social media platform from the Resize drop-down list and select the image size from the options that display. 
3. Scale the image, if required, using the **Image Scale** field. 
4. Click **Apply** to apply your changes. 
   ![Image editing with Adobe Express](/help/using/assets/adobe-express-resize-image.png)

   Your edited image is available for download. You can either save the edited asset as a new version of the same asset or save it as a new asset.
   ![Save image with Adobe Express](/help/using/assets/adobe-express-resize-save.png)

#### Remove background {#remove-background-using-express}

You can remove background from an image by following the steps mentioned below: 

1. Click **Remove Background** from the left pane. Experience Manager Assets displays the image with no background. 
2. Click **[!UICONTROL Apply]** to apply your changes.
![Save image with Adobe Express](/help/using/assets/adobe-express-remove-background.png)

   Your edited image is available for download. You can either save the edited asset as a new version of the same asset or save it as a new asset.

#### Crop image {#crop-image-using-express}

Transforming an image into a perfect size is simple using embedded [!DNL Adobe Express] quick actions.

1. Click **[!UICONTROL Crop Image]** from the left pane.
2. Drag the handles on the corners of the image to create your desired crop.
3. Click **[!UICONTROL Apply]**.
   ![Save image with Adobe Express](/help/using/assets/adobe-express-crop-image.png)
   The cropped image is available for download. You can either save the edited asset as a new version of the same asset or save it as a new asset.

#### Convert between Image file types {#convert-image-types-using-express}

You can quickly convert between JPEG and PNG image formats using Adobe Express. Execute the following steps: 

1. Click **JPEG to PNG** or **PNG to JPEG** from the left pane.
   ![Convert to PNG with Adobe Express](/help/using/assets/adobe-express-convert-image.png)
2. Click **[!UICONTROL Download]**.

#### Limitations {#limitations-adobe-express}

* Supported image resolution: Minimum - 50 pixels, Maximum - 6000 pixels per dimension.
* Maximum file size supported: 17 MB.

### Edit images in Adobe Express embedded editor {#edit-images-in-adobe-express-embedded-editor}

Users with Express entitlement can use the embedded Express editor from within the Assets Essentials UI to easily edit content and create new content with GenAI from Adobe Firefly. This improves content reuse and accelerates content velocity. You can also use pre-defined elements to make your asset look stunning or perform quick actions to edit your image with just a few clicks. 
![express in essentials UI](/help/using/assets/express-in-essentials-ui.jpg)
To edit images using Adobe Express embedded editor, follow the steps below: 

1. Land on to AEM Asset Essentials UI using the link - [AEM Asset Essentials UI](https://experience.adobe.com/#/assets) and select the right repository. 
1. Click **Assets**, enter a folder, and select an image. 
1. Click **Open in Adobe Express**. The image opens on an express canvas.
1. Make the required edits to the image. 
1. If your project requires you to add more pages, click **Add**, select Assets, enter a folder, select an image to bring onto the canvas page, and then perform the required edits to the image. 
1. To save the image(s), click **Save**. The save dialog box displays. 

   >[!NOTE]
   >
   > **1. For Single Page**  
   >
   > **Save as Version:** This feature supports saving a single asset only. Select this option to export the image as a new version(retaining the original format), and save it in the same folder. 
   > **Save as New Asset:** Select this option to export the asset in a different format than the original and save it to any folder as a new asset.
   >  
   > **2. For Multi Page**  
   >
   > **Save as Version:** This feature supports saving a single asset only. If you want to save a single page from multiple pages, select this option to save the asset in its original format and location.  
   > **Save as New Asset:** With this option, you export either multiple assets or a single asset to any folder and save them as new asset(s) with their file format as original or different. 

1. In the Save dialog box:  
   1. Enter a name for the file in the **Save As** field. 
   1. Select a destination folder. 
   1. Optional: Provide details such as Project or Campaign name, Keywords, Channels, Time frame, and Region. 
1. Click **Save as version** or **Save as new asset** to save the asset(s).  

#### Limitations of editing images in the Express Editor {#limitations-of-editing-images-in-the-express-editor}

 * Supported file type: JPEG or PNG. 
 * Maximum file size supported: 40 MB. 
 * Supported width and height range: Between 50 to 8000 pixels.
 * Reload the page to see the latest saved new asset in the source folder. 

### Create new assets using Adobe Express {#create-new-assets-using-embedded-editor}

Assets Essentials enables you to create a new template from scratch using Adobe Express embedded editor. To create a new asset using Adobe Express, execute the below steps: 

1. Navigate to **My Workspace** and click **Create** within the Adobe Express banner that displays within the Adobe Express at the top. Adobe Express blank canvas displays within the Assets Essentials user interface. 
1. Create your content using [Templates](https://helpx.adobe.com/in/express/using/work-with-templates.html). Otherwise, navigate to Your Stuff to modify existing content. 
1. Once you complete editing, click **Save**. 
1. Specify the destination path for the created asset and click **Save as new asset**.

#### Limitations {#limitations}

* You can only modify images of `JPEG` and `PNG` format types.
* The asset size must be less than 40 MB.
* You can save an image in `PDF`, `JPEG`, or `PNG` formats.

<!--
## Edit images using [!DNL Adobe Photoshop Express] {#edit-using-photoshop-express}

<!--
After editing an image, you can save the new image as a new version. Versioning helps you to revert to the original asset later, if needed. To edit an image, [open its preview](/help/using/navigate-view.md#preview-assets) and click **[!UICONTROL Edit Image]** ![edit icon](assets/do-not-localize/edit-icon.png) from the rail on the right.

![Options to edit an image](assets/edit-image2.png)

*Figure: The options to edit images are powered by [!DNL Adobe Photoshop Express].*
-->
<!--
### Spot heal images {#spot-heal-images-using-photoshop-express}

If there are minor spots or small objects on an image, you can edit and remove the spots using the spot healing feature provided by Adobe Photoshop.

The brush samples the retouched area and makes the repaired pixels blend seamlessly into the rest of the image. Use a brush size that is only slightly larger than the spot you want to fix.

![Spot healing edit option](assets/edit-spot-healing.png)

<!-- 
TBD: See if we should give backlinks to PS docs for these concepts.
For more information about how Spot Healing works in Photoshop, see [retouching and repairing photos](https://helpx.adobe.com/photoshop/using/retouching-repairing-images.html). 
-->
<!--
### Crop and straighten images {#crop-straighten-images-using-photoshop-express}

Using the crop and straighten option that you can do basic cropping, rotate image, flip it horizontally or vertically, and crop it to dimensions suitable for popular social media websites.

To save your edits, click **[!UICONTROL Crop Image]**. After editing, you can save the new image as a version.

![Option to crop and straighten](assets/edit-crop-straighten.png)

Many default options let you crop your image to the best proportions that fit various social media profiles and posts.

### Resize image {#resize-image-using-photoshop-express}

You can view the common photo sizes in centimeters or inches to know the dimensions. By default, the resizing method retains the aspect ratio. To manually override the aspect ratio, click ![](assets/do-not-localize/lock-closed-icon.png).

Enter the dimensions and click **[!UICONTROL Resize Image]** to resize the image. Before you save the changes as a version, you can either undo all the changes done before saving by clicking [!UICONTROL Undo] or you can change the specific step in the editing process by clicking [!UICONTROL Revert].

![Options when resizing an image](assets/resize-image.png)

### Adjust image {#adjust-image-using-photoshop-express}

[!DNL Assets Essentials] lets you adjust the color, tone, contrast, and more, with just a few clicks. Click **[!UICONTROL Adjust image]** in the edit window. The following options are available in the right sidebar:

* **Popular**: [!UICONTROL High Contrast & Detail], [!UICONTROL Desaturated Contrast], [!UICONTROL Aged Photo], [!UICONTROL B&W Soft], and [!UICONTROL B&W Sepia Tone].
* **Color**: [!UICONTROL Natural], [!UICONTROL Bright], [!UICONTROL High Contrast], [!UICONTROL High Contrast & Detail], [!UICONTROL Vivid], and [!UICONTROL Matte].
* **Creative**: [!UICONTROL Desaturated Contrast], [!UICONTROL Cool Light], [!UICONTROL Turquoise & Red], [!UICONTROL Soft Mist], [!UICONTROL Vintage Instant], [!UICONTROL Warm Contrast], [!UICONTROL Flat & Green], [!UICONTROL Red Lift Matte], [!UICONTROL Warm Shadows], and [!UICONTROL Aged Photo].
* **B&W**: [!UICONTROL B&W Landscape], [!UICONTROL B&W High Contrast], [!UICONTROL B&W Punch], [!UICONTROL B&W Low Contrast], [!UICONTROL B&W Flat], [!UICONTROL B&W Soft], [!UICONTROL B&W Infrared], [!UICONTROL B&W Selenium Tone], [!UICONTROL B&W Sepia Tone], and [!UICONTROL B&W Split Tone].
* **Vignetting**: [!UICONTROL None], [!UICONTROL Light], [!UICONTROL Medium], and [!UICONTROL Heavy].

![Adjust image by editing](assets/adjust-image.png)

<!--
TBD: Insert a video of the available social media options.
-->

### Next Steps {#next-steps}

* Provide product feedback using the [!UICONTROL Feedback] option available on the Assets Essentials user interface.

* Provide documentation feedback using [!UICONTROL Edit this page] ![edit the page](assets/do-not-localize/edit-page.png) or [!UICONTROL Log an issue] ![create a GitHub issue](assets/do-not-localize/github-issue.png) available on the right sidebar

* Contact [Customer Care](https://experienceleague.adobe.com/?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [View version history of an asset](/help/using/navigate-view.md)
