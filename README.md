# Salesforce SendGrid Email Integration
## 📨 Summary:
This project integrates SendGrid with Salesforce to provide a scalable, cost-effective solution for sending high-volume emails beyond Salesforce's daily limit of 5,000 emails per day. Using SendGrid enables us to bypass Salesforce's email limits and avoid the high costs associated with purchasing additional email capacity directly from Salesforce.

By leveraging SendGrid's robust email infrastructure, this integration allows organizations to deliver timely and reliable email communication with improved cost efficiency and deliverability, making it an excellent solution for marketing campaigns, customer notifications, and more.

## 🌟 Features
* **Automated Token Management**: Refreshes access tokens every 24 hours to ensure continuous connectivity.
* **Event List Synchronization**: Automatically creates Constant Contact event lists based on Salesforce event data.
* **Registrant Management**: Adds and updates event registrants as contacts within Constant Contact, directly from Salesforce.
* **API Request Handling**: Implements secure OAuth 2.0 token handling, with dynamic refresh capability using Named Credentials.

## 💼 Using the Integration
* 🎥 Watch the video demo [Salesforce SendGrid Integration](#) on how to use the integration  
  
### 📘 **Instructions**

## ⌛️ Access Token Expiration

## ⚠️ Limitations

## 📚 Documentation
This project was developed using various documentation resources that provide essential guidance on setup, functionality, and best practices. Below are some key references:

- **Official Salesforce Documentation**: Comprehensive guide on Salesforce APIs, development best practices, and integration techniques.  
  [Salesforce Future Method](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_invoking_future_methods.htm)
  [Testing HTTP Callouts](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_classes_restful_http_testing.htm)
