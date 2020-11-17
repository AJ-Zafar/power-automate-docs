---
title: Create a flow from a template | Microsoft Docs
description: Create a flow from any of several built-in templates.
services: ''
suite: flow
documentationcenter: na
author: MSFTMAN
manager: KVIVEK
ms.author: Deonhe
editor: ''
tags: ''
ms.service: flow
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 09/07/2020
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---
# Create a flow from a template in Power Automate

You can create a flow from one of many built-in templates in Power Automate. When you click **Templates** on the left-side navigation pane in Power Automate, you can search the many templates that are built around popular products and automation scenarios. You can browse by category, or search for templates by product name, scenario, or other keywords. The tile for each template shows a summary that includes the following:

- Icons for the products and services that are involved. 
- Template name
- Type of flow (instant/automated)
- number of flows made using this template

>[!TIP]
>[Create a flow from scratch](get-started-logic-flow.md) if you already have a process in mind and can't find a template for it.

Here, we'll follow an example that uses a template to create a flow that sends you a Slack message when your manager sends you an email in Microsoft 365.

## Prerequisites

To complete this example, you'll need accounts with access to the following:

- [Power Automate](https://flow.microsoft.com)
- Slack account
- Microsoft 365

## Choose a template

1. Sign in to [Power Automate](https://flow.microsoft.com) and select **Templates** in the left-side navigation pane.
1. Use the search bar to search for **slack manager** to find the **Send a message on Slack when my manager emails me** template, and then select it.
1. If you aren't signed into Office or Slack, select **Sign in** and then follow the prompts.
1. After you confirm your connections, select **Continue**.

    Your flow appears, showing each action with an orange title bar.

    ![Default events and actions from template](./media/get-started-logic-template/template-default.png)

## Customize your flow

1. Select the title bar for an event to expand it, and then customize it (for example, by specifying a filter on the email that interests you).
1. Actions that require input from you will automatically be expanded.
  
    For example, the **Post message** action is expanded because you need to enter a channel, such as your *\@username*. You can also customize the message content. By default, the message will contain just the subject, but you can include other information.

1. Near the top of the screen, specify a name for your flow, and then select **Create flow**.
1. Finally, if you're happy with your flow, select **Save**.

Now, when your manager sends you an email, you'll receive a Slack message that contains the information that you specified.

## Next steps

-  [Watch your flow in action](see-a-flow-run.md)
- [Publish your own template](publish-a-template.md)
- [Use a template for the Microsoft Dataverse](common-data-model-intro.md)
- [Get started with team flows](create-team-flows.md) and invite others to collaborate with you to design flows.
