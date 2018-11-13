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
