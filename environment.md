## Instances

> Sandbox Instances

Used for the following:
- Development & Customisation 
- User Acceptance Testing (UAT)
- Testing 
- Training 
- Various Demos 
You can reset the sanbox instance and this deletes all of the data and refreshes the instance. 

> Production Instances

- Used for day-to-day live business transactions.
- No R&D or Development is done on production instance.
- Only authorized users are allowed to use production instance.
- Production instance cannot be reset.

> How to get instances

Within the trial subscription
- Only get one instance
- Cannot purchase new instances as Add-Ons

Within Paid subscriptions
- You get two instances
- Additional instances can be purchased as add-ons
- Its reccomended that you have 1 production instance and two sandbox ones. 

## Managing Instances

Its possible to swtich an instance from Production to Sandbox OP Sandbox to Production. Its also possile to reset a Sandbox instance but not the production one. Its also possible to delete a sandbox instance, but again, not the Production instance. It's possible to copy the Dynamics 365 application and all data from any instance to a Sandbox instance.

There are two copy types, Full(without production data), and Minimal (without production data.) This is only available for paid Dynamics subscriptions. You must jabe at least one Sandbox instance in addition to the Production instance. All instances are available within a tenant (Office 365 account). A tenant can have maximum 50 production instances and 75 sandbox instances. When setting up instances, you must specify the region which they belong to. For paid subscriptions all instances are created in the same region. 

### Available Regions
```
North America (crm.dynamics.com)
South America (crm2.dynamics.com)
Canada (crm3.dynamics.com)
EMEA (crm4.dynamics.com)
APAC (crm5.dynamics.com)
Australia (crm6.dynamics.com)
Japan (crm7.dynamics.com)
India (crm8.dynamics.com)
United Kingdom (crm9.dynamics.com)
Microsoft Could Germany (crm.microsoftdynamics.de)
```

Storage is allocated to Subscriptions not instances. This includes production as well as sandbox. And buying new instances does not add more storage to the account. A notification will be sent to the Administrator on consuming 80% pf the storage available. Additional storage can be purchased if need be. 


> Notifications

- Emails are sent to Administrators by default
- New recipiants can be added to instance level 

## Updates

Microsoft delivers new features and updates to the Dynamics environment twice per year. Its mandatory to apply one update per year. You should always apply the updates to the sandbox instance first. After the update is successful, schedule the update for production. Updates are applicable to individual instances. Once the update is released notifications are sent to administrators. You can view all the available updates from the Dynamics Admin center. Updates need to be approved before they take place. 

!> Instances are not available to users when the update is in progress.

The chosen time and dates for the updates and provided by Microsoft. To avoid rush and last moment errors, plan updates in advance with your implementation partner. 

!> If you miss two updates in a row, then you are forced to do a mandatory update. 