---
title: Assignments for Teams
author: lanachin
ms.author: v-lanac
manager: serdars
ms.topic: article
ms.service: msteams
audience: admin
ms.collection: 
  - M365-collaboration
search.appverid: MET150
ms.reviewer: jastark
f1.keywords: 
- CSH
ms.custom:
  - ms.teamsadmincenter.assignments.overview
  - ms.teamsadmincenter.assignments.tooltip.emaildigest
  - ms.teamsadmincenter.assignments.tooltip.makecode
  - ms.teamsadmincenter.assignments.tooltip.turnitin
description: Learn how to manage assignments in the Microsoft Teams admin center in Teams for Education.
localization_priority: Normal
appliesto: 
  - Microsoft Teams
---

# Assignments in Teams for Education

Assignments are tasks or units of work assigned to a student or team member in a class as part of their study. You can create assignments within your Teams class.

[Learn more about Assignments](https://support.office.com/article/microsoft-teams-5aa4431a-8a3c-4aa5-87a6-b6401abea114?ui=en-US&rs=en-IE&ad=IE#ID0EAABAAA=Assignments)

> [!Note]
> For details about Teams assignments on different platforms, see [Teams features by platform](https://support.microsoft.com/office/teams-features-by-platform-debe7ff4-7db4-4138-b7d0-fcc276f392d3).

## Assignments in the Microsoft Teams admin center

With the admin settings in Microsoft Teams admin center you can turn the following features on or off to be available for students and teachers within your organization. The following are settings related to Assignments:

<a name="#bkemaildigest"> </a>
### Weekly guardian email digest

The emails will contain information about assignments from the previous week and for the upcoming week, and will be sent over the weekend. Information about the email content can be found here. The emails need to be set up and updated by the admins using the [School Data Sync](https://docs.microsoft.com/schooldatasync/) feature. SDS automatically populates classes for Teams with student rosters from the school’s student information system (SIS). The steps to enable this feature are:
1.	Import parent contact information via Parent and Guardian Sync in SDS. [Click here for instructions on how to enable Parent and Guardian Sync](https://docs.microsoft.com/schooldatasync/parent-contact-sync#enabling-parent-and-guardian-sync).
2.	Turn on the Guardian Setting in the Microsoft Teams Admin Center Teams Admin Center, as the setting is turned off by default. This will enable teachers to send out a weekly digest. Note that teachers can opt-out of the digest by deselecting the setting inside their own personal class team (Assignment Settings > Parent/Guardian Emails).

To verify that Parents will get the email the following three items must be true

1.	Email address attached to the student profile in SDS and tagged as [Parent or Guardian](https://docs.microsoft.com/schooldatasync/parent-contact-sync-file-format) 
2.	Students belongs to at least one class which where e-mail is not disabled by the teacher in [assignment settings](https://support.microsoft.com/en-us/office/adjust-assignment-settings-in-your-class-team-05bb3b89-1cdf-415a-b6c7-44add0376a77)
3.	The emails will contain information about assignments that had due date in the previous week or in the upcoming week
 
This setting is off by default.


<a name="bkmakecode"> </a>
### MakeCode
Microsoft MakeCode is a block-based coding platform that brings computer science to life for all students. 

MakeCode is a Microsoft product that is subject to the Microsoft [terms of use](https://go.microsoft.com/fwlink/?LinkID=206977) and [privacy](https://go.microsoft.com/fwlink/?LinkId=521839) policies.

This setting is off by default. To enable MakeCode assignments in Teams, in the **Teams Admin Center**, navigate to the **Assignments** section and turn the MakeCode toggle option to **On**. Click **Save** and allow a few hours for these settings to take effect.

For more information on how this feature works, see this [video demonstration](https://makecode.com/blog/teams/teams-assignments).

[Learn more about MakeCode](https://aka.ms/makecode)

<a name="#turnitin"> </a>
### Turnitin

Turnitin is a plagiarism detection service. This is a third-party product or service that is subject to its own terms and privacy policy. You are responsible for your use of any third-party products and services.

This setting is off by default.

In order to successfully enable Turnitin for your organization, you will need to already have a Turnitin subscription. You will need to input the following additional information, which can be found in your Turnitin admin console:

  * _TurnitinApiKey_: This is a 32-character GUID found in the admin console under Integrations.
  * _TurnitinApiUrl_: This is the HTTPS URL of your Turnitin admin console.

Here are some instructions to help you obtain this information.

The TurnitinApiUrl is the host address of your admin console.
Example. `https://your-tenant-name.turnitin.com`

The admin console is where you can create an integration and an API key associated with the integration.

Select **Integrations** from the side menu, then select **Add Integration** and give the integration a name.
![Screenshot showing adding a new integration](./educationImages/Assignments_mopo_turnitin2.png)

The TurnitinApiKey will be given to you after you follow the prompts. 
Copy the API key and paste it into the Microsoft Teams admin center.  This is the only time you can view the key.
![Screenshot showing copying the API key](./educationImages/Assignments_mopo_turnitin3.png)

Upon clicking the **Save** button in the admin center for this setting, please allow a few hours for these settings to take effect.

Ready to start using the Turnitin integration in Teams? Sign up for the [early access program](https://www.turnitin.com/products/feedback-studio/microsoft-teams-integration).
