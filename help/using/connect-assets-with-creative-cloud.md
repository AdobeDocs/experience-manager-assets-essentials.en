---
title: Connect AEM Assets to Creative Cloud
description: Learn how to configure and connect AEM Assets to Creative Cloud. Connect to a Creative Cloud entitlement that is provisioned to a different IMS organization in order to easily use the latest Creative Cloud integrations in AEM Assets, including Express and Creative Cloud Libraries.
exl-id: 3d8d7429-ddf6-44cd-a6e7-ba2afcbaf52b
TQID: https://experienceleague.adobe.com/jNPNmqvjsK-A6LD-Mk02ffYM15aO2zudSfhJrST-gVA
product_v2:
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
    internal-label: Experience Manager
feature_v2:
  - id: ae478996-b206-4712-9b0c-dc78a2644453
    internal-label: Integrations
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
    internal-label: Leader
---
# Connect AEM Assets to Creative Cloud  {#cross-org-entitlements}

Experience Manager Assets has the ability to connect to a Creative Cloud entitlement that is provisioned to a different IMS organization in order to easily use the latest Creative Cloud integrations in AEM Assets, including Express and Creative Cloud Libraries.

If your Creative Cloud products and AEM Assets are provisioned to separate IMS organizations, you can connect to a different Creative Cloud organization to be able to execute integrated workflows between the two solutions.

## Prerequisites {#prerequisites}

* Administrator rights to Experience Manager Assets

* Active entitlement to Creative Cloud for the same user ID used across Creative Cloud and Experience Manager. Entitlements to personal and federated IDs with the same email address are treated as different user IDs.

## Connect to a new Creative Cloud organization {#connect-to-creative-cloud-org}

To connect to a new Creative Cloud organization, execute the following steps:

1. Navigate to **[!UICONTROL Settings]** > **[!UICONTROL Creative Cloud]**.

1. Select the new Creative Cloud organization using the **[!UICONTROL Select new Creative Cloud org ID]** drop-down list. The list displays all organizations that you have access to. Select the organization with active Creative Cloud entitlements.

1. Click **[!UICONTROL Switch orgs]** to switch to the new organization.

   ![Cross Org Entitlements](assets/cross-org-entitlements.png)

## Limitations {#limitations}

* You can connect AEM Assets to one Creative Cloud organization at a time. Connection to multiple Creative Cloud organizations at a time is not supported.

* The Creative Cloud organization that you connect to within AEM Assets is applicable to all users within your organization.
