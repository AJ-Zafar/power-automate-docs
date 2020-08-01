---
title: Get started | Microsoft Docs
description: Quick ways to start automating your work and life with Power Automate
services: ''
suite: flow
documentationcenter: na
author: stepsic-microsoft-com
manager: kvivek
editor: ''
tags: ''
ms.service: flow
ms.devlang: na
ms.topic: conceptual
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 7/29/2020
ms.author: stepsic
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---

# Get started with Power Automate 

Welcome! What can you expect from Power Automate? Here are a few examples of what you can do:

* Automate business processes
* Send automatic reminders for past due tasks
* Move business data between systems on a schedule
* Connect to almost 300 data sources or any publicly available API
* You can even automate tasks on your local computer like computing data in Excel. 

Just think about time saved once you automate repetitive manual tasks simply by recording mouse clicks, keystrokes and copy paste steps from your desktop! Power Automate is all about automation. 

<br/>

> [!VIDEO https://www.youtube.com/embed/hCuxuUaGC6Y]


## Who is Power Automate for? 

*What skills do you need to have?* 
Anyone from a basic business user to an IT professional can create automated processes using Power Automate's no-code/low-code platform.

*What industries can benefit from Power Automate?* 
Check out how some companies implemented Power Platform solutions using Power Automate in: 

  * [Banking](https://customers.microsoft.com/en-us/story/821782-illimity-bank-banking-power-automate)
  * [Retail](https://customers.microsoft.com/en-us/story/drivetime-retail-consumer-goods-azure)
  * [Manufacturing](https://customers.microsoft.com/en-us/story/810656-hexion-manufacturing-power-platform)
  * [Insurance](https://customers.microsoft.com/en-us/story/811345-aioi-nissay-dowa-insurance-microsoft-power-platform)
  * [Healthcare](https://customers.microsoft.com/en-us/story/vnshs-health-provider-microsoft-flow) 

Find [examples from your industry](https://customers.microsoft.com/en-us/search?sq=%22Power%20Automate%22&ff=story_product_categories%26%3EPower%20Automate&p=0&so=story_publish_date%20desc)


The first step in creating an automation is to [sign up](sign-up-sign-in.md), or, if you already have an account with Power Automate, [sign in](https://flow.microsoft.com/signin).

## Types of flows

See the following table to learn more about the types of flow that you can build to help address your use cases.

| **Flow type**                                                                       | **Use case**                                                                                  | **Automation target**                                                                             |
|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| [Automated flows](get-started-logic-flow.md)                 | Create an automation that is triggered by an event such as arrival of an email from a specific person, or a mention of your company in social media.| [Connectors](https://docs.microsoft.com/connectors/) for cloud or on-premises services connect your accounts and enable them to talk to eachother. |
| [Instant flows](introduction-to-button-flows.md)              | Start an automation with a click of a button. You can automate for repetitive tasks from your Desktop or Mobile devices. For example, instantly send a reminder to the team with a push of a button from your mobile device.                      |     Wide range of tasks such as requesting an approval, an action in Teams or SharePoint.                                                                                |
| [Scheduled flows](run-scheduled-tasks.md)                    | Schedule an automation such as daily data upload to SharePoint or a database.             |Tasks that need to be automated on a schedule.                                                                            |
| [Business process flows](business-process-flows-overview.md) | Ensure that  everyone in your company follows the same process by defining a set of steps for people to follow.                 | Human processes such as customer service requests, approvals, IT development,...                                                                        |
| [UI flows](ui-flows/overview.md)                                                | Record  clicks and keyboard strokes from your Desktop and Web applications and automate the playback of manual steps on legacy software.                    | Desktop and Web applications that do not have APIs available for automation.    |



## Check out the start page 

[On the start page](https://flow.microsoft.com) for Power Automate, you can [explore a diverse set of templates](https://flow.microsoft.com/templates) and learn about the key features for Power Automate. You can get a quick sense of what's possible and how Power Automate could help your business and your life.

Each template is designed for a specific purpose. For example, there are templates for sending you a text message when your boss emails you, adding Twitter leads to Dynamics 365, or backing up your files. These templates are just the tip of the iceberg. They're intended to inspire you to create customized flows for the exact processes you need.

## Create your first flow 

1. Select a template that's useful for you. A simple template is [**Get daily reminders in Email**](https://flow.microsoft.com/galleries/public/templates/45a3399aa29345308f08b6db0a9c85b9/):

    ![daily reminder template](./media/getting-started/template-details.png)

1. Select **Continue**.

    ![Create connection](./media/getting-started/create-connection.png)

1. Enter the email addresses to which the daily reminder will be sent. Next, enter the reminder message. Finally, select **Create flow**, and then verify that your flow is running as expected.

    ![Provide credentials for the connection](./media/getting-started/configure-email-details.png)

    > [!NOTE]
    > You can explore the conditions that trigger the flow and the action that results from that event. Play around with the settings to make the flow your own. You can even add or delete actions.

1. Select **Done**.

[Follow this tutorial](get-started-logic-template.md) to learn more about creating flows from templates.

## Get creative

Now that you've created your first flow from a template, use any of the more than [380 data sources](https://flow.microsoft.com/connectors/) that Power Automate supports to [create your own flows from scratch](get-started-logic-flow.md).

![Building a flow](./media/getting-started/build-a-flow.png)

When you create a flow from scratch, you control the entire workflow. Here are a few ideas to get your started:

- [Flows with many steps](multi-step-logic-flow.md).
- [Run tasks on a schedule](run-scheduled-tasks.md).
- [Create an approval flow](wait-for-approvals.md).
- [Watch a flow in action](see-a-flow-run.md).
- [Publish a template](publish-a-template.md).
- [Create flows from a Microsoft Teams template](https://flow.microsoft.com/connectors/shared_teams/microsoft-teams/).


## Peek at the code

You don't need to be a developer to create flows; however, Power Automate does provide a **Peek code** feature that allows anyone to take a closer look at the code that's generated for all actions and triggers in a flow. Peeking at the code could give you a clearer understanding of the data that's being used by triggers and actions. Follow these steps to peek at the code that's generated for your flows from within the Power Automate designer: 

1. Select the **...** menu item at the top right corner of any **action** or **trigger**. 
1. Select **Peek code**.

    ![Peek code](media/getting-started/peek-code.png)

1. Notice the full JSON representation of the actions and triggers. This includes all inputs, such as the text you enter directly, and expressions used. You can select expressions here and then paste them into the **Dynamic Content** expression editor. This can also give you a way to verify the data you expect is present in the flow.

    ![Peek code](media/getting-started/peek-code-details.png)
   

## Find your flows easily

When your creative juices start *flowing*, you might create many flows. Don't worry, finding your flows is easy - just use the search box on the **My flows**, **Team flows**, **Connections**, or **Solutions** screen to display only flows that match the search terms you enter.

![Filter or search flows](media/getting-started/filter-search-box.png)
 
> [!NOTE]
> The search filter only finds flows that have been loaded into the page. If you don't find your flow, try selecting **Load more** at the bottom of the page.

## Get notifications when something's wrong

Use the Power Automate notification center (located at the top right of the designer) to quickly see a list of flows have failed recently. The notification center displays a number that indicates the number of flows that failed recently.

From the notification center, you can navigate to the **Activity** page of Power Automate to see all your flows that recently ran, sent notifications, or failed.

![Notification center](media/getting-started/notification-center.png)

## Use the mobile app 

Download the Power Automate mobile app for [Android](https://aka.ms/flowmobiledocsandroid), [iOS](https://aka.ms/flowmobiledocsios), or [Windows Phone](https://aka.ms/flowmobilewindows). With this app, you can [monitor flow activity](mobile-monitor-activity.md), [manage your flows](mobile-manage-flows.md) and [create flows from templates](mobile-create-flow.md).

## We're here to help 

We're excited to see what you do with Power Automate, and we want to ensure you have a great experience. Be sure to check out our [guided learning](https://flow.microsoft.com/guided-learning/) tutorials and [join our community](https://go.microsoft.com/fwlink/?LinkID=787467) to ask questions and share your ideas. [Contact support](https://go.microsoft.com/fwlink/?LinkID=787479) if you run into any issues.
