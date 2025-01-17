---
title: Applying Workflows to Assets
description: Learn how to apply workflows to assets, folders, and collections in AEM Assets.
uuid: ed02fd9c-6e3a-4c66-9d6c-92dc56304767
contentOwner: AG
products: SG_EXPERIENCEMANAGER/6.5/ASSETS
discoiquuid: 099c9842-ae13-4da7-92b7-61955a8483cb
docset: aem65

---

# Applying Workflows to Assets {#applying-workflows-to-assets}

Applying workflows to digital assets is the same as for website pages. For a complete guide on how to create and use workflows in AEM, see [Starting Workflows](/help/sites-authoring/workflows-participating.md).

Use workflows in digital assets to activate the asset or create watermarks. Many of the workflows for assets are automatically turned on. For example, the workflow that automatically creates a rendition after an image is edited is automatically turned on.

If a workflow available in Classic UI is not available in Touch-enabled UI, like Request to Activate and Request to Deactivate, see [Make workflow models available in Touch UI](/help/sites-developing/workflows-models.md#classic2touchui).

## Applying a workflow to an AEM asset {#applying-a-workflow-to-an-aem-asset}

For details of applying a workflow to an AEM asset, see [Starting a Workflow on an Asset](/help/assets/managing-assets-touch-ui.md#starting-a-workflow-on-an-asset).

## Applying a workflow to multiple assets {#applying-a-workflow-to-multiple-assets}

1. From the Assets console, navigate to the location of the assets for which you want to start a workflow, and select the assets.
1. Click the GlobalNav icon, and the choose **[!UICONTROL Timeline]** from the menu to display the timeline.

   ![screen_shot_2019-03-06at123325pm](assets/screen_shot_2019-03-06at123325pm.png)

1. Click the **Actions** (arrow) icon at the bottom.

   ![chlimage_1-30](assets/chlimage_1-30.png)

1. Click **[!UICONTROL Start Workflow]**.
1. In the **[!UICONTROL Start Workflow]** dialog, select a workflow model from the list.

   ![chlimage_1-31](assets/chlimage_1-31.png)

1. (Optional) Specify a title for the workflow, which can be used to reference the workflow instance.
1. Click **[!UICONTROL Start]** and then click **[!UICONTROL Confirm]** in the dialog. The workflow runs on all the assets you selected.

## Applying a workflow to multiple folders {#applying-a-workflow-to-multiple-folders}

The procedure to apply a workflow to multiple folders is similar to the procedure to apply a workflow to multiple assets. Select the folders in the Assets console, and perform steps 2-7 of the procedure [Applying a workflow to multiple assets](/help/assets/assets-workflow.md#applying-a-workflow-to-multiple-assets).

## Applying a workflow to a collection {#applying-a-workflow-to-a-collection}

For details of applying a workflow to a collection, see [Running a workflow on a collection](/help/assets/managing-collections-touch-ui.md#running-a-workflow-on-a-collection).
