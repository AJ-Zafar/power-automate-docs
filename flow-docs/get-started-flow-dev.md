---
title: Create custom connectors and embed flows| Microsoft Docs
description: Create a custom connector, share it, embed a flow, and do much more.
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
ms.date: 11/22/2017
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---
# Start to build with Microsoft Flow
[!INCLUDE [view-pending-approvals](includes/cc-rebrand.md)]

Here are some of the ways you can extend your application with Microsoft Flow:

* Create and connect to a custom connector.
* Share your custom connector with all Microsoft Flow users.
* Embed the flow experience within an app.
* Highlight all custom connectors so that users can interact with Microsoft Flow in the best way for them.

## Prerequisites

* A [Power Automate](https://flow.microsoft.com) account.

## Create a custom connector

If you have a web service to which you want to connect from Microsoft Flow, you'll first need to create a custom connector. When you register a custom connector, you teach Microsoft Flow about the characteristics of your web service, including the authentication it requires, the triggers and actions that it supports, and the parameters and outputs for each of those actions.

Follow this tutorial to learn how to [Register and use custom connectors](https://powerapps.microsoft.com/tutorials/register-custom-api/). After you register your custom connector, you can share it within your organization for testing.

## Share a custom connector with all Microsoft Flow users

After you fully test your custom connector, start the [review process](https://flow.microsoft.com/blog/calling-all-saas-apps-now-you-can-build-your-own-connector-for-flow-and-logic-apps/) to have it approved by Microsoft for sharing with all other Microsoft Flow users.

Here's what you'll need for the review process:

* An OpenAPI file that represents your API and any authentication information.
* An icon for your connector.
* A description of your connector.
* Approximately 10 ideas for how your connector could benefit other users through templates.

After you submit this information, Microsoft starts assessing your API's functionality in Microsoft Flow and Microsoft PowerApps.

## Embed the flow experience into your website or app

You can [embed](developer/embed-flow-dev.md) Microsoft Flow into your app to enable deep, in-context integration between your app and all other services that Microsoft Flow supports. For example, you can:

* Browse all templates that relate to your service and let users select a template.
* Manage the flows that users have related to your app.

## Next steps

Learn how to [embed](developer/embed-flow-dev.md) Microsoft Flow into your app.
