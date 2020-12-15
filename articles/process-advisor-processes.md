---
title: Work with processes and recordings (preview)| Microsoft Docs
description: How to create and work with processes in process advisor.
services: ''
suite: flow
documentationcenter: na
author: nijemcevic 
manager: kvivek
editor: ''
tags: ''
ms.service: flow
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 12/09/2020
ms.author: tatn
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---
# Work with processes and recordings (preview)

[!INCLUDE [cc-beta-prerelease-disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

Before you can use process advisor to visualize and analyze your processes, you have to:

- Create your process in process advisor.
- Record the activities that make up the process in the process advisor recorder.
- Prepare the recording for analysis.

## Create a process

In general, processes that you think might be inefficient or repetitive are good candidates for analysis. It should also be limited to a single user, and not suited for complicated business processes that involve multiple individuals.

1. Sign in to [Power Automate](https://powerautomate.microsoft.com/).
1. Select **Process advisor (preview)** in the left-side navigation pane.
1. Select **Create** under **Process advisor (preview)**.
1. Select the **Create a new process** tile.
1. Give your process a name and description, then select **Create**.

Here's a short video on process creation: [Create a process](https://go.microsoft.com/fwlink/?linkid=2147540)

## Record your process

Create a recording in one of three ways:

- From the **Create** screen in process advisor
- Right after process creation
- From the process details page

Here's a short video on recording a process: [Record a process](https://go.microsoft.com/fwlink/?linkid=2147725)

### Create a recording from the 'Create' screen

1. From the **Process advisor (preview)** > **Create** screen, select **Add a new recording**.
1. On the **Process** screen, select the process you want to record for.
1. Select **Open recorder**.
    >[!NOTE]
    >If you are not able to see the process in the dropdown, ensure that the process has been correctly shared with you.

### Create a recording right after process creation

1. After the process is created, a creation successful modal will be shown with a few options as next steps.
1. Select **Add a recording**.

### Create a recording from the process details page

1. From the **Process advisor (preview)** > **Processes** page, select the process you want to record for from the list view.
1. Select the name of the process to go to the process details page.
1. Select **New recording** from the command bar.
1. Select **Open recorder**.

### Launching the recorder in Power Automate Desktop

1. By using any of the methods described above, you should see a message that says **Launching the recorder** in Power Automate Desktop.
    > [!NOTE]
    > You should have [downloaded Power Automate Desktop](https://go.microsoft.com/fwlink/?linkid=2102613) before you started. However, you can select **Get the app now** to install it.
1. If you have installed Power Automate Desktop, you should see a  **Open Power Automate Desktop** browser popup window.  Select it to open the app.
1. If Power Automate Desktop is installed but didn’t open correctly, select **Open again**.

## Power Automate Desktop Recorder

1. In the Desktop recorder screen, select **Start recording**.
1. Perform the actions that you want to record, and then select **Finish** on the bottom of the recorder window.
1. Once the recording has saved successfully select **Got it** to close the message.
1. Return to the web portal in your browser, and Select **View recording**.

> [!NOTE]
> Depending on the length of the recording, it may take some time before the actions will be available.

### Recorder features

- As you record your actions, the action descriptions will be listed in the recorder window. You can click the trashcan icon to delete any action from your recording.
- Select **Pause recording** at any time during the recording. 
- Select **Start recording again** to continue recording from where you left off.
- Select **Reset recording** to erase all the recorded actions and start over.

### Recording tips

- Be methodical in your actions to improve the readability of the recording. There is a slight delay so wait for the red box to focus on the item you are trying to interact with before selecting.
- If there were mis-clicks, delete the action in the recorder window.

## Prepare a recording for analysis

Once the recording has completed, you can view the recorded actions in the recording details page. More importantly, you need to prepare the recording to be ready for analysis. What does this mean?

- The actions recorded can be very granular. Group them into activities. These will be the building blocks for the process map that is created through analysis.
- Remove any sensitive information from the recording.  [More information](process-advisor-protect.md).

Here's a short video on preparing a recording for analysis: [Prepare a recording for analysis](https://go.microsoft.com/fwlink/?linkid=2147425)

### Grouping actions into activities

1. Select **Add group** to add a group header. All actions under the group header and before the next group header are considered part of the group.
1. Move the group header up and down the actions list to where you want to group to start.
1. Name your group on the right side of the screen.
1. Use the dropdown menu to find group names that already exist for the process, or create your own.
1. If you made a mistake and want to delete a group, use the trash can icon next to the group name.
1. At any time, select **Save** on the top right to save your work.
1. To analyze, you need at least two groups. Otherwise, the process map would not be very meaningful.
1. When you finish grouping, set **Ready to analyze**  next to **Save**.
1. Select **Close** to return to the process details page.

### Remove sensitive information

1. Select the step that contains information you want to remove.
1. Edit the step name or description to remove any sensitive information, such as account numbers or passwords.
1. Delete any screenshots that contain sensitive information.

### Grouping tips

- As much as possible use an existing group name, this creates a more consistent and accurate process map.
- Group names will be available in the dropdown list whenever a recording is saved. To remove group names from the dropdown list after it was removed from all recordings that used that group name, you need to analyze the recording.
