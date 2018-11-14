## Integration with Exchange online

Microsoft Integrates with Exchange Online for:
- Sending and recieving emails
- Users can track interations with customers within dynamics 365

Emails are sent via Exchange Online using Server Side Synchronisation or CRM for outlook. 

> Server side synchronisation

Server side synchronisation allows incoming and outgoing email functionality. No additional application installation is required. Emails recieved within Exchange folders can automatically be tracked inside Dynamics 365. Server Side synchronisation is mandatory. All folders to be tracked should be inside Inbox folder. Emails can be sent to these folders using Exchange rules (create conditions based on email or domain). 

## Integrate with sharepoint online

- Dynamics 365  Integreates with sharepoint online for:
    - Document & Content management
    - Search capabilities
- Sharepoint and Dynamics 365 Permissions are exclusive 

``` 
To enable goto Document management > Enable Server Based Sharepoint Integration 
```

- With server based integration, users once signed in, do not have to sign in to both Microsoft Dynamics and Sharepoint
- No additional software is required to install on SharePoint
- Users can perform SharePoint actions from the Dynamics 365 command bar
- Sharepoint documents will be displayed in Dynamics Lists 


## Enable OneDrive for Business

- Everyont is given 1TB of Cloud Storage
- Security settings & Permissions
    - Sharepoint: Shared with all
    - OndeDrive : Private to user (sharing can be manually enabled)


``` 
To enable goto Document management > Enable OneDrive for Business  
```
By default, Microsoft Dynamics 365 does not have Documents common item for Account form. Please follow the steps to make it visible:

- PRE-REQUISITE: You must have already enabled SharePoint and OneDrive Integration.
- Open any account record and click Form as shown below:
- Click Navigation as shown below:
- Drag the Documents relationship (from the Relationship Explorer on right side) to Common Navigation Area.
- The Documents relationship is added. Click Save and then Publish.
- Now close the above window, go to the accounts record and refresh the page.
- Then click the common area explorer and then you will find Documents there.
- From here, you can change the location of the documents upload and then click Upload to start uploading documents to SharePoint from within Dynamics 365.

## Manage OneNote integration

- Onenote integration is available within Dynamics to keep notes or drawings
- Sharepoint integration is mandatory for OneNote as notebooks are stored within SharePoint
- You first need to enable OneNote Integration and then you can enalbe the OneNote feature on each entity as you require it

``` 
To enable goto Document management > Enable OneNote integration. 
```

## Managing Microsoft Social Engagement 

- Social Engagement allows companies to know what's happening on their social media
- Social Engagement subscription is required and this can be configured under Administration (within Dynamics 365)

## Yammer integration

- Yammer is a private social network for companies
- Yammer Enterprise license is required for integration
- After enabling Yammer integreation, acitvity feeds are replaced by Yammer feeds
- You can enable Yammer integration under Administration 

## Wordplace collaboration with Office 365 

- Collaboration is possible between Office 365 users (who do not  have a Dynamics 365 license) and Dynamics 365 users.
- Collaboration via conversations, meetings, sharing documents and notes (With Outlook, SharePoint and OneNote)

## Delve Integration

- Delve manages your Dynamics 365 profile and discovers/organises information thats most relevant to you.
- You can search content from Office 365 instances (providing that security is not compromised)
- Information can be displayed on Dashboards
- Delve integration can be enabled under Document Management 

!> Similar to OneNote Delve integration wont work unless you have SharePoint integration enabled 