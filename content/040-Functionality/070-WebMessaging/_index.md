---
title: "Web Messaging"
chapter: true
weight: 70
---

![Title](/images/WebM.PNG)


Genesys Cloud web messaging provides customers with an enhanced experience when they visit your website. Unlike web chat, which provides short-lived, standalone chats, web messaging enables a visitor to enter your site, converse with a bot or agent, and return later to pick up the conversation. With Predictive Engagement, agents can view the entire customer journey as part of the web messaging interaction. Web messaging shares many of the same features and capabilities as the other Genesys Cloud messaging channels that use ACD messaging to enable agents to respond to customer interactions.

### Setup

"My Account" menu

- Choose **"Web Messenger"** in the **"Widget Type"** combobox
- Click **"Apply"** button

![One](/images/file_1644963022875_gc-web-messenger.png)

> Notes: The activation of the Web Messaging will be remebered and stay active till the moment when browser's data are cleared.

### Authentication / Passing data to the Architect - Inbound Message Flow

GSol uses [Database plugin](https://developer.genesys.cloud/commdigital/digital/webmessaging/messengersdk/SDKCommandsEvents) of Messenger JavaScript SDK to pass user data and login related information to the Architect's Inbound Message Flow.
As a result the access to some operations is closed for the users who are not logged in into GSol web site.
   
   #### User logged out:                 

![One](/images/gsol-dgt-balance-logout.png)

   #### User logged in:  

![One](/images/gsol-dgt-balance-login.png)

