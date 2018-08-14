---
description: This topic contains answers to questions that are frequently asked about activity setup and using Analytics as the reporting source for Target (A4T).
keywords: faq;frequently asked questions;analytics for target;a4T;activity setup
seo-description: This topic contains answers to questions that are frequently asked about activity setup and using Analytics as the reporting source for Target (A4T).
seo-title: Activity Setup - A4T FAQ
solution: Target
title: Activity Setup - A4T FAQ
topic: Standard
uuid: c171b5e1-0dbb-48d0-90f7-1a8a4b5006f0
index: y
internal: n
snippet: y
translate: y
---

# Activity Setup - A4T FAQ

This section contains the following information: 


* [ Which activity types are support Analytics as the reporting source... ](../../../c_integrating_target_with_mac/a4t/r_a4t-faq/c_a4t-faq-activity-setup.md#section_5E4F58CD25A5424E869E6FE0803968EF)
* [ I just created an activity. Why don't I see any data coming in? ](../../../c_integrating_target_with_mac/a4t/r_a4t-faq/c_a4t-faq-activity-setup.md#section_9F8092BE4225442896F926540292F221)
* [ Why can't I can't select Analytics as my reporting source when I create a new activity? ](../../../c_integrating_target_with_mac/a4t/r_a4t-faq/c_a4t-faq-activity-setup.md#section_9F4F69C3085F4C2480AF439127EB27CD)


## Which activity types are support Analytics as the reporting source (A4T)? {#section_5E4F58CD25A5424E869E6FE0803968EF}

For a full list, see "Supported Activity Types" in [ Adobe Analytics as the Reporting Source for Adobe Target (A4T) ](../../../c_integrating_target_with_mac/a4t.md#concept_7540C8C04259434AB6EE33B09F47A1DE). 

## I just created an activity. Why don't I see any data coming in? {#section_9F8092BE4225442896F926540292F221}

When an activity is created, Target sends a classification file to Analytics. Although Analytics is capturing the and processing the data, it does not show in the reports until the classification file has been updated. This can take up to 24 hours. If after 48 hours you don't see your data, please [ contact Client Care ](https://marketing.adobe.com/resources/help/en_US/target/target/r_problem.html). Alternately, if you know you will launch an activity, you can create the activity a few days beforehand and the classifications will be sent when the activity is saved. That way, data appears in the reports upon launch. Please note that it takes 45-90 minutes for data to be processed in Analytics. 

## Why can't I can't select Analytics as my reporting source when I create a new activity? {#section_9F4F69C3085F4C2480AF439127EB27CD}

You can change your Reporting Settings options in Setup. 


1. In Adobe Target, click **[!UICONTROL  Setup]**.
1. In the **[!UICONTROL  Experience Cloud solution used for reporting]** drop-down list, click **[!UICONTROL  Select per Activity]**.


![](assets/select-per-activity.png) 

The **[!UICONTROL  Reporting Source]** drop-down list is enabled in the **[!UICONTROL  Goal &amp;amp; Settings]** screen for creating and editing activities. 

To always use Analytics as the reporting source, select **[!UICONTROL  Adobe Analytics]** from the drop-down list in Setup. 