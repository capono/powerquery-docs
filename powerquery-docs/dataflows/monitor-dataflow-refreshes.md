---
title: Monitor your dataflow refreshes with Power BI
description: How to monitor dataflow refreshes with Power BI.
author: luitwieler


ms.reviewer: dougklo
ms.topic: conceptual
ms.date: 03/22/2022
ms.author: jeluitwi
---

# Monitor your dataflow refreshes with Power BI

When working with any kind dataflows other than Power BI dataflows, you have the ability to monitor dataflow refreshes using Power BI. This article includes step by step instructions on how to set up your own dashboard to share with everyone on your team. This dashboard provides insights into the success rate of refreshes, duration, and much more.

[![Image of the dashboard with dataflow duration, refresh count, and refresh success rate graphs.](media/refreshhistory-dashboard/dashboard-preview.PNG)](media/refreshhistory-dashboard/dashboard-preview.PNG#lightbox)

## Set up your dashboard

To set up your monitoring dashboard for dataflow refresh history:

1. Navigate to [Power Apps](https://make.powerapps.com/).
1. Select the environment you want to monitor.
1. Open ![Image of a gear.](media/refreshhistory-dashboard/gear-icon.PNG) **Settings** > **Session Details**.
1. Copy the **Instance url**, which should look something like `contoso.crm.dynamics.com`.
1. Download the [Power BI Template](https://download.microsoft.com/download/f/1/9/f195fb57-495a-4487-9317-fe00816afd88/dataflow%20refresh%20history%20metrics%20template.pbit).
1. Open the template file with Power BI Desktop and provide your instance URL.
    ![Image of a screen to input your dataverse org URL.](media/refreshhistory-dashboard/template-parameter.PNG)
1. Select **Load**.
1. If this is the first time you've used this dashboard, you might need to enter your credentials to sign in.
1. Inside the dashboard, you'll find two tabs with information about errors, duration, and the count of rows that were inserted, upserted, or failed:
    * Dataflow monitoring
    * Table monitoring
1. From this point on, you can change the dashboard however you like and publish it to a workspace of your choice.

## Power BI dataflows monitoring

When working with Power BI dataflows, you might want to check out the following pages for setting up your monitoring solution:

* [Use Dataverse to build a dataflows monitoring report](./load-dataflow-metadata-into-dataverse-table.md)
* [Use a Power BI dataset to build a dataflows monitoring report](./load-dataflow-metadata-into-power-bi-dataset.md)
* [Use Excel to build a dataflows monitoring report](./load-dataflow-metadata-into-excel-online.md)