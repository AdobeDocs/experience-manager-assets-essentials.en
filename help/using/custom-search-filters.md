---
title: Custom search filters
description: Learn about customizing search filters form
role: User, Leader, Developer
---
# Customize search filters {#customize-search-filters}

Search filters allow you to refine search results based on various parameters such as date, file type, tags, and relevance, enhancing the precision of search queries. By applying filters, you can quickly sift through the most relevant results efficiently. This not only saves time but also improves the overall search experience by tailoring results to specific preferences and needs.
See more about [search](search.md).

Custom search filters can only be mapped to entries in your Searchable Property Index. Ensure that any custom metadata is included before configuring your custom filter experience. [!DNL Assets Essentials] helps customizing search filters to streamline the search process. To customize the search filters template, execute the following steps:

1. Navigate to **[!UICONTROL Settings]** > **[!UICONTROL General Settings]**.
1. Go to the **[!UICONTROL Search]** tab. Click **[!UICONTROL Customize]** to configure your search form. 

    ![custom search filter settings](assets/custom-search-filter.png)

1. The [!UICONTROL Configure Filters] form appears. Ensure that you are in Edit mode so that you can make modifications in the template. You can switch to [!UICONTROL Preview mode] to see the preview of an existing search form.
1. Drop filter elements from the [custom filters](#available-custom-filters) on the canvas. You can drag and dropt the component to reorder if needed.

    >[!VIDEO](https://video.tv.adobe.com/v/3443080)

1. Click [!UICONTROL Preview mode] to review the changes.
1. Click [!UICONTROL Confirm] to save.

## Available custom filters {#available-custom-filters} 

Assets Essentials provides the following custom filters that are reconfigurable as per the requirement:

* [Filter elements](#filter-elements)
* [Preconfigured filters](#preconfigured-filters)

### Filter elements {#filter-elements}

You can use a collection of filter elements on your custom search filters canvas. These elements are reconfigurable based on the usability of search property attributes. The following filter elements are available in [!DNL Assets Essentials]:

<table>
    <tr>
        <th>Filter elements</th>
        <th>Value</th>
        <th>Description</th>
        <th colspan="4">Properties</th>
    </tr>
    <tr>
        <td>Text</td>
        <td>Text</td>
        <td>A text field is an input area where you can type information related to the filter.</td>
        <td>&check;</td>
        <td>&#x2717; </td>
    </tr>
</table>

* **Text:** A text field is an input area where you can type information related to the filter.
* **Options:** Options refer to the available alternatives to select a preferred item from a list.
* **Boolean:** A Boolean represents one true value. It can be used where you want to be specific to choose one option among others.
* **Number:** Use this filter element to represent a numeric value.
* **Drop down:** To choose among various options displayed in a list of options.
* **Date:** Used to specify date.
* **Path browser:** Used to navigate through files or folders in the [!DNL Experience Manager] repository.
* **Tags:** Used to select tags from the available options. Tags provide more specific information about the assets and enhance their discoverability. Tags already applied to the selected assets displays in the **Properties** panel. If you store tags on a custom metadata property and use the root path to restrict it to a hierarchy, you can leverage the same configuration in your search filters. If you can't find the relevant tags, create them and assign to the selected assets. See [Manage tags in Assets Essentials](/help/using/tagging-management.md) for details on creating and assigning tags to assets.
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

## Custom filter properties {#custom-filter-properties}

Each filter element is associated with a set of properties.

<table>
    <tr>
        <th>Properties</th>
        <th>Values</th>
        <th> Filter elements</th>
        <th>Preconfigured filters</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Label</td>
        <td>Text</td>
        <td> &check; </td>
        <td> &check; </td>
        <td>It is an identifier of the filter that you are using.</td>
    </tr>
    <tr>
        <td>Metadata</td>
        <td>Drop down</td>
        <td></td>
        <td></td>
        <td>The metadata property is used to map approved metadata from [!DNL Adobe Experience Manager Assets] repository. You can choose the metadata value from the drop-down menu that needs to be mapped with the filter element. </td>
    </tr>
    <tr>
        <td>Selection type</td> 
        <td>Single, Multiple, Exact, or Range </td>
        <td></td>
        <td></td>
        <td>
            <ul>
                <li><b>Single selection</b> allows choosing one item at a me, which is ideal for distinct choices.
                <li><b>Multiple selection</b> allows choosing several items concurrently, which is useful for selecting multiple options. 
                <li><b>Exact selection</b> allows choosing a precise single item from various options.
                <li><b>Range selection</b> allows choosing a continuous set of values within a defined range, useful for selecting a range of dates or numerical values.
            </ul>
        </td>   
    </tr>
    <tr>
        <td>Options</td>
        <td>Manual, JSON Path, or CSV Upload</td>
        <td></td>
        <td></td>
        <td>
            <ul>
                <li>Choose <b>Manual</b> if you want to add options manually. 
                <li>Choose <b>JSON Path</b> to add options from the JSON file. 
                <li>Choose <b>CSV Upload</b> to import a CSV file containing values to be added in the options.
            </ul>
        </td>
    </tr>
    <tr>
       <td>Values</td>
        <td>Add or Edit</td>
        <td></td>
        <td></td>
        <td>
        <ul>
        <li>Click <b>add</b> to add a new value. 
        <li>Click <span>&#9998;</span> to edit the label. 
        <li>Click  <img src=assets/do-not-localize/delete.svg> to delete the option value. 
        <li>Click <b>Edit</b> to modify the edit options. 
        <li>You can also change the sequence of options by holding them.
        </td>
    </tr>
    <tr>
        <td>Delimeter support</td>
        <td>Enable or disable</td>
        <td></td>
        <td></td>
        <td>A delimiter is a symbol used to separate distinct elements in text. For example commas, spaces, or semicolons.</td>
    </tr>
    <tr>
        <td>Stepper</td>
        <td>Value</td>
        <td></td>
        <td></td>
        <td>Enable the Stepper button to the number field to increment or decrement the value on each click. </td>
    </tr>
    <tr>
        <td>Stepper value </td>
        <td>Number</td>
        <td></td>
        <td></td>
        <td>It indicates the increment/decrement value when using the stepper button.</td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Text</td>
        <td></td>
        <td></td>
        <td>Add a detailed explanation to provide additional information about the filter element.</td>
    </tr>
    <tr>
        <td>Delete category</td>
        <td>Button</td>
        <td></td>
        <td></td>
        <td>Deletes filter element.</td>
    </tr>
</table>

<!--
| Properties | Values | Filter elements | Description |
|--------|--------|--------|--------|
| *Label* | Text | &#9745; &#9745; | It is an identifier of the filter that you are using. |
| *Metadata* | Drop down | Common for all filters | The metadata property is used to map the entries in your Searchable Property Index. Only properties listed in your index are available for use as filters. If the property is not visible, you can reach out to your technical team to update the index or [contact customer support](https://experienceleague.adobe.com/?support-solution=General#support). |
| *Selection type* | Single, Multiple, Exact, or Range | File Type/ Image Size/ Image Width/ Image Height/ Created Date/ Modified Date/ Expiration Date/ Dynamic Media Status/ Smart Tags/ Checkout/ Text field/ Options/ Number/ Dropdown | **Single selection** allows choosing one item at a time, which is ideal for distinct choices. **Multiple selection** allows choosing several items concurrently, which is useful for selecting multiple options. **Exact selection** allows choosing a precise single item from various options. **Range selection** allows choosing a continuous set of values within a defined range, useful for selecting a range of dates or numerical values. |
| *Options* | Manual, JSON Path, or CSV Upload | File type/ File format/ Drop down/ Checkout/ Dynamic Media status/ Options/ Dropdown | Choose **[!UICONTROL Manual]** if you want to add options manually. Choose **[!UICONTROL JSON Path]** to add options from the JSON file. Choose **[!UICONTROL CSV Upload]** to import a CSV file containing values to be added in the options. |
| *Values* | Add or Edit | File type/ File format/ Checkout/ Dynamic Media status/ Options/ Dropdown | Click add to add a new value. Click ![edit icon](assets/do-not-localize/edit.svg) to edit the label. Click ![delete icon](assets/do-not-localize/delete.svg) to delete the option value. Click **[!UICONTROL Edit]** to modify the edit options. You can also change the sequence of options by holding them. |
| *Delimeter support* | Enable or disable | Smart tags | A delimiter is a symbol used to separate distinct elements in text. For example commas, spaces, or semicolons.|
| *Tags* | Drop down | Smart Tags/ Tags field | Select relevant tags from the drop-down. Click ![tags icon](/help/using/assets/tags-icon.svg) to select tags from the available options. Tags provide more specific information about the assets and enhance their discoverability. Tags already applied to the selected assets displays in the **Properties** panel. If you can't find the relevant tags, create them and assign to the selected assets. See [Manage tags in Assets Essentials](/help/using/tagging-management.md) for details on creating and assigning tags to assets. |
| *Stepper* | Value | Image size/ Image width/ Image height/ Number field | Enable the Stepper button to the number field to increment or decrement the value on each click. |
| *Stepper value* | Number | Image size/ Image width/ Image height/ Number field | It indicates the increment/decrement value when using the stepper button. |
| *Description* | Text | Common for all filters | Add a detailed explanation to provide additional information about the filter element. |
| *Delete category* | Button | Common for all filters | Deletes filter element. |
-->
