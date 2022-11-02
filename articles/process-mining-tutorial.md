---
title: Get started with process mining in process advisor (preview)
description: This topic is a tutorial with sample data in process mining using the process advisor feature in Power Automate.
author: nijemcevic
contributors:
  - nijemcevic
  - v-aangie 
ms.subservice: process-advisor
ms.topic: conceptual
ms.custom: intro-internal
ms.date: 10/31/2022
ms.author: tatn
ms.reviewer: angieandrews
search.app: 
  - Flow[https://preview.flow.microsoft.com/en-us/?processinsights-core.tabularData=true](https://preview.flow.microsoft.com/en-us/?processinsights-core.tabularData=true)
search.audienceType: 
  - flowmaker
  - enduser
---

# Tutorial: Get started with process mining (preview)

[!INCLUDE[cc-beta-prerelease-disclaimer](./includes/cc-beta-prerelease-disclaimer.md)]

This tutorial allows you to experience process mining with sample data. In this tutorial, you'll create a process, import data, and then analyze it.

## Download the sample data

For the process mining tutorial, download the sample event log CSV file:  

- [English version](https://go.microsoft.com/fwlink/?linkid=2181220)<br/>
- [French version](https://go.microsoft.com/fwlink/?linkid=2181117)

The sample data in this tutorial is for illustration only and is fictitious. No real association is intended or inferred.

## Create a process

1. Sign in to [Power Automate](https://flow.microsoft.com/).

1. Select your environment.

1. On the navigation pane to the left, select **Process advisor**.

    :::image type="content" source="media/process-mining-tutorial/process-adv-menu.png" alt-text="Screenshot of the process advisor menu selection.":::

1. In the **Create new process** section, select **Start here**.

    :::image type="content" source="media/process-mining-tutorial/start-here.png" alt-text="Screenshot of the 'Start here' message.":::

1. Enter a process name, and then select **Data (preview)**.

    :::image type="content" source="media/process-mining-tutorial/process-name-data.png" alt-text="Screenshot of the process name and Data (preview) button.":::

1. Select **Create**.

## Import data and analyze

1. In your process, select **Setup** in the toolbar.

1. Select **Blank table**.

    :::image type="content" source="media/process-mining-tutorial/blank-table.png" alt-text="Screenshot of blank table selection.":::


1. Use Notepad or any other text editor to open the sample event log CSV file that you downloaded.

1. Select all contents of the CSV file by pressing **Ctrl** + **A**.

1. Copy the selection by pressing **Ctrl** + **C**.

1. Paste the selection you copied into the blank table in process advisor by pressing **Ctrl** + **V**.

1. Select **Use first row as headers**.

    :::image type="content" source="media/process-mining-tutorial/headers.png" alt-text="Screenshot of first row as headers selection.":::

1. Upload your event log, select your file from the list, and choose **Select** to continue.

1. Select **Next** twice to open the Power Query editor.

1. Validate that your fields are correct in the table view.

1. On the toolbar, select **Map to entity**.

    :::image type="content" source="media/process-mining-tutorial/map-to-entity.png" alt-text="Screenshot of Map to entity button.":::

1. On the left pane, select the **Event log** entity.

1. On the right pane, map the three required columns by selecting **Auto map**.

1. Return to the Power Query editor by selecting **OK**.

    :::image type="content" source="media/process-mining-tutorial/auto-map.png" alt-text="Screenshot of auto mapping.":::

1. Return to the process details page by selecting **Save**.

1. On the toolbar, select **Analyze**, and then select **Confirm** when the dialog opens.

1. Wait for the analysis to complete. After the process is analyzed, select **Analytics** in the toolbar to view the process map.

    :::image type="content" source="media/process-mining-tutorial/analytics.png" alt-text="Screenshot of an analyzed process.":::

For a description of how to analyze the process map and a short video, go to [Visualize and gain insights from processes in process advisor (preview)](process-mining-visualize.md).
