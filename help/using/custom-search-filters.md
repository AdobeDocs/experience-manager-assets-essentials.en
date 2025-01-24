---
title: Custom search filters
description: Learn about customizing search filters form
role: User, Leader, Developer
---
# Search filters {#search-filters}

Search filters allow you to refine search results based on various parameters such as date, file type, tags, and relevance, enhancing the precision of search queries. By applying filters, you can quickly sift through the most relevant and targeted results efficiently. This not only saves time but also improves the overall search experience by tailoring results to specific preferences and needs.
See more about [search](search.md).

## Customize search filters {#customize-search-filters}

[!DNL Assets Essentials] helps customizing search filter parameters template to streamline the search process. To customize the search filters template, execute the following steps:

1. Navigate to **[!UICONTROL Settings]** > **[!UICONTROL General Settings]**.
1. Go to the **[!UICONTROL Search]** tab. Click **[!UICONTROL Customize]** to configure your search form. 

    ![custom search filter settings](assets/custom-search-filter.png)

1. The [!UICONTROL Configure Filters] form appears. Ensure that you are in Edit mode so that you can perform modifications in the template. You can switch to [!UICONTROL Preview mode] to see the preview of an existing search form.
1. Drop filter elements from the [custom filters](#available-custom-filters) on the canvas and rearrange their sequence as per the requirement.

    >[!VIDEO](https://video.tv.adobe.com/v/3443080)

1. Click [!UICONTROL Preview mode] to review the changes.
1. Click [!UICONTROL Confirm] to save.

## Available custom filters {#available-custom-filters} 

Assets Essentials provides the following custom filters that are reconfigurable as per the requirement:

* [Filter elements](#filter-elements)
* [Preconfigured filters](#preconfigured-filters)

### Filter elements {#filter-elements}

You can use a collection of filter elements on your custom search filters canvas. These elements are reconfigurable based on the usability of search property attributes. The following filter elements are available in [!DNL Assets Essentials]:

* **Text:** A text field is an input area where you can type information related to the filter.
* **Options:** Options refer to the available alternatives to select a preferred item from a list.
* **Boolean:** A Boolean represents one true value. It can be used where you want to be specific to choose one option among others.
* **Number:** Use this filter element to represent a numeric value.
* **Drop down:** To choose among various options displayed in a list of options.
* **Date:** Used to specify date.
* **Path browser:** Used to navigate through files/folders in the [!DNL Experience Manager] repository.
* **Tags:** Used to select tags from the available options. Tags provide more specific information about the assets and enhance their discoverability. Tags already applied to the selected assets displays in the **Properties** panel. If you can't find the relevant tags, create them and assign to the selected assets. See [Manage tags in Assets Essentials](/help/using/tagging-management.md) for details on creating and assigning tags to assets.
* **User:** Used to specify the type of user among administrators, regular, and consumer users.

### Preconfigured filters {#preconfigured-filters}

The preconfigured filters are preset settings that allow you to use them directly on the canvas. However, you can customize the properties as per your requirements. The following filters are preconfigured in [!DNL Assets Essentials]:

* **File type:** Filter the search results by the supported types of files that are, `Images`, `Documents`, and `Videos`.
* **File format:** [!DNL Assets Essentials] supports any binary file format with basic services, such as, storage, upload, copy, move, delete, and adding metadata.
* **Image size:** Provide one of more of the minimum and maximum dimensions to filter images. Size is provided in dimensions in pixel and is not the file size of the images.
* **Image width:** Vertical dimensions of an image.
* **Created date:** Date range when assets were created.
* **Modified date:** Date range when assets were modified.
* **Asset status:** Assets Essentials allow you to set the status on assets available in the repository. Set an asset status to better govern and manage downstream consumption of digital assets. Choose among [!UICONTROL Approved], [!UICONTROL Rejected], or [!UICONTROL No Status].
* **Smart tags:** Filter assets using smart tags added in the [!DNL Experience Manager] repository.
* **Checkout:** Choose whether the asset is checked out or checked in.
* **Dynamic Media status:** Choose the status of an asset between published or unpublished.
* **Expiration date:** Filter assets specifying a date range after which the assets are no longer valid or needed. 

<!--
    | Filter elements | Values | Description |
    |--------|--------|--------|
    | *Text* |||
    | *Options* |||
    | *Boolean* |||
    | *Number* |||
    | *Drop down* |||
    | *Date* |||
    | *Path browser* |||
    | *Tags* |||
    | *User* |||
    |**Preconfigured Filters**|||
    | *File type* |||
    | *File format* |||
    | *Image size* |||
    | *Image width* |||
    | *Created date* |||
    | *Modified date* |||
    | *Asset status* |||
    | *Smart tags* |||
    | *Checkout* |||
    | *Dynamic Media status* |||
    | *Expiration date* |||
-->

## Custom filter properties {#custom-filter-properties}

Each filter element is associated with a set of properties.

| Properties | Values | Availability (in Filter) | Description |
|--------|--------|--------|--------|
| *Label* | Text | Common for all filters | It is an identifier of the filter that you are using. |
| *Metadata* | Drop down | Common for all filters | The metadata property is used to map approved metadata from [!DNL Adobe Experience Manager Assets] repository. You can choose the metadata value from the drop-down menu that needs to be mapped with the filter element. |
| *Selection type* | Single, Multiple, Exact, or Range | File Type/ Image Size/ Image Width/ Image Height/ Created Date/ Modified Date/ Expiration Date/ Dynamic Media Status/ Smart Tags/ Checkout/ Text field/ Options/ Number/ Dropdown | **Single selection** allows choosing one item at a time, which is ideal for distinct choices. **Multiple selection** allows choosing several items concurrently, which is useful for selecting multiple options. **Exact selection** allows choosing a precise single item from various options. **Range selection** allows choosing a continuous set of values within a defined range, useful for selecting a range of dates or numerical values. |
| *Options* | Manual, JSON Path, or CSV Upload | File type/ File format/ Drop down/ Checkout/ Dynamic Media status/ Options/ Dropdown | Choose **[!UICONTROL Manual]** if you want to add options manually. Choose **[!UICONTROL JSON Path]** to add options from the JSON file. Choose **[!UICONTROL CSV Upload]** to import a CSV file containing values to be added in the options. |
| *Values* | Add or Edit | File type/ File format/ Checkout/ Dynamic Media status/ Options/ Dropdown | Click add to add a new value. Click ![edit icon](assets/do-not-localize/edit.svg) to edit the label. Click ![delete icon](assets/do-not-localize/delete.svg) to delete the option value. Click **[!UICONTROL Edit]** to modify the edit options. You can also change the sequence of options by holding them. |
| *Delimeter support* | Enable or disable | Smart tags | A delimiter is a symbol used to separate distinct elements in text. For example commas, spaces, or semicolons.|
| *Tags* | Drop down | Smart Tags/ Tags field | Select relevant tags from the drop-down. Click ![tags icon](/help/using/assets/tags-icon.svg) to select tags from the available options. Tags provide more specific information about the assets and enhance their discoverability. Tags already applied to the selected assets displays in the **Properties** panel. If you can't find the relevant tags, create them and assign to the selected assets. See [Manage tags in Assets Essentials](/help/using/tagging-management.md) for details on creating and assigning tags to assets. |
| *Stepper* | Value | Image size/ Image width/ Image height/ Number field | Enable the Stepper button to the number field to increment or decrement the value on each click. |
| *Stepper value* | Number | Image size/ Image width/ Image height/ Number field | It indicates the increment/decrement value when using the stepper button. |
| *Description* | Text | Common for all filters | Add a detailed explanation to provide additional information about the filter element. |
| *Delete category* | Button | Common for all filters | Deletes filter element. |

