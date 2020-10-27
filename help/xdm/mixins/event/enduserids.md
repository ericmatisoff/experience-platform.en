---
keywords: Experience Platform;home;popular topics;schema;Schema;XDM;ExperienceEvent;fields;schemas;Schemas;Schema design;mixin;mixin;enduserids;end-user;end user;ids;
solution: Experience Platform
title: ExperienceEvent EndUserIDs mixin
topic: overview
description: This document provides an overview of the ExperienceEvent EndUserIDs mixin.
---

# [!UICONTROL ExperienceEvent EndUserIDs] mixin

[!UICONTROL ExperienceEvent EndUserIDs] is a standard mixin for the [[!DNL XDM ExperienceEvent] class](../../classes/individual-profile.md), used to describe an individual's identity information across several Adobe applications. The mixin provides a root-level `endUserIDs` object, which itself contains a read-only `_experience` field whose values are automatically updated as data is ingested.

<img src='../../images/mixins/enduserids.png' width=700 /><br />

| Property | Data type | Description |
| --- | --- | --- |
| `aacustomid` | [Identity](../../data-types/identity.md)  | Custom end user IDs for Adobe Analytics Cloud. |
| `aaid` | [Identity](../../data-types/identity.md) | End user IDs for Adobe Analytics Cloud. |
| `acid` | [Identity](../../data-types/identity.md) | End user IDs for Adobe Campaign. |
| `adcloud` | [Identity](../../data-types/identity.md) | End user IDs for Adobe Advertising Cloud. |
| `emailid` | [Identity](../../data-types/identity.md) | Email address IDs. |
| `mcid` | [Identity](../../data-types/identity.md) | Adobe Marketing Cloud ID. |
| `phonenumberid` | [Identity](../../data-types/identity.md) | Phone number IDs. |
| `tntid` | [Identity](../../data-types/identity.md) | End user IDs for Adobe Target. |

For more details on the mixin, refer to the public XDM repository:

* [Populated example](https://github.com/adobe/xdm/blob/master/components/mixins/experience-event/experienceevent-enduserids.example.1.json)
* [Full schema](https://github.com/adobe/xdm/blob/master/components/mixins/experience-event/experienceevent-enduserids.schema.json)