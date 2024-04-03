# Password Manager

## About
PowerUp Solutions Ltd is a Power Platform consultancy that offers a variety of bespoke Power Platform development. 

Their ALM framework states that they need to set up an environment strategy within their customers tenant and carry out all bespoke development in these environments. Once a bespoke build has been deployed to production, PowerUp Solutions Ltd export the latest version and import it into their tenant for archiving purposes. 

However, in order for PowerUp Solutions Ltd to comply with their own ALM framework, they need credentials to access each customers tenant.


## Use Case
PowerUp Solutions Ltd offers Power Platform development to various customers and requires their developers to access customer tenants. 
To mitigate the customer needing to license each developer individually, the customer has shared a global service account for the developers to make use of. Unfortunately, this offers a gap when it comes to auditing logins  and assigning session ownership. 

PowerUp Solutions Ltd requires a simple solution that allows developers to access customer credentials through a user-friendly interface. This solution should allow developers to copy usernames and passwords in the app. Whenever credentials are copied, an audit needs to be logged for that developer. 

Additionally, developers need their own vault to manage their personal company passwords. This does not have to be audited. It should rather be treated as a feature that allows all personal company passwords to be kept within the organisation and not within third party systems. 


## Requirements
### User Stories
1. Developers should be able to create new customers. 
2. Developers should be able to create, edit and access customer credentials. 
3. Developers should be able to create their own passwords. 
4. Customer passwords should be audited per copy, change, or edit. 
5. Should passwords have an expiration date, the developer should be notified 2 days before the password expires. 
6. Personal passwords should be secured to the password owner. 

## Resources
•	No resources for this Use Case 😄

