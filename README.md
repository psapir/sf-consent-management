
# Consent Management Starter Kit

Welcome to the complex world of consent and preference management in Salesforce! 

This guide is intended to provide a good starting point to manage user consent and preferences utilizing the Consent Data Model in Salesforce and give you a foundation for your solution.

**Important Considerations**

 - Because managing consent in Salesforce is not a "plug and play" solution and there are many ways to solve this complex scenario, don't treat this document as your "silver bullet" but a place to get inspired and get started. 
 - This guide assumes that you are utilizing Salesforce Sales or Service Cloud and Salesforce Marketing Cloud Engagement. If you utilize a different product such as Salesforce Data Cloud or Pardot this guide might not serve you as well but still could be useful.

Finally, this is a living guide. As I develop more components for the starter kit I will continue to upload them in this repository. Enjoy!

## Useful Links

To write this guide I based myself in several articles that you should read to get acclimated with the concepts of Consent Management:

 - [Consent Management Concepts by Elliot Harper](https://www.cloudkettle.com/blog/martech-in-the-era-of-consent/) 
 - [Consent Data Model Diagram](https://architect.salesforce.com/diagrams/template-gallery/platform-privacy-consent-data-model)
 - [Consent Capture Flow Template](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000FMiVQUA1)
 - [Consent Management Guide in Salesforce Marketing Cloud](https://help.salesforce.com/s/articleView?id=sf.consent_data_model_mc_about.htm&type=5)
 - [Consent Write API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_consent_write.htm)
 - [Cookie Consent Plugin](https://github.com/orestbida/cookieconsent)

## Prerequisites 

To implement this quick start guide you will need:

1. Access to a Salesforce Org
2. Access to a Salesforce Marketing Cloud Org
3. Implemented the [integration between Salesforce and Marketing Cloud](https://help.salesforce.com/s/articleView?id=sf.mc_co_marketing_cloud_connect.htm&language=en_US&type=5) 

### Part I - Setting up the Consent Data Model in Salesforce

**Step 1 - Enable Data Protection and Privacy Settings**

 1. Open Setup
2. Enter _Data Protection and Privacy_ in the Quick Find box, and select **Data Protection and Privacy**.  
3. Click **Edit**.  
4. Select the  **Make data protection details available in records**  checkbox.  
5. Click **Save**.  

**Step 2 - Add the Individual field to your Lead, Contact or Person Account page layouts**

**Step 3 - Install the Consent Capture Flow Template**
 Install the [Consent Capture Flow Template](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000FMiVQUA1) from the AppExchange. This is an open source project, you can access the code here: https://github.com/schandlergarcia/consent-capture
 
**Step 4 - Configure Consent Objects**
Create records for your consent data model objects for Data Use Legal Basis and Data Use Purpose.

**Step 5 - Create a Lightning Component Action to Launch the Consent Flow**
Depending on where you want the Screen Flow template to be launched (at the Contact level, at the Lead level, etc) you will need to setup a Lightning Action to trigger the installed Screen Flow, [follow these instructions to set this up.](https://help.salesforce.com/s/articleView?id=sf.lightning_component_actions_create.htm&type=5)

**Mission Accomplished!** you are already setup and ready to start storing consent in Salesforce! Now let's take a look at capturing consent.
 
### Part II - Capturing Consent 
Coming Soon!

### Part III - Storing Consent in Salesforce
Coming Soon!

### Part IV - Sending Consent information to Salesforce Marketing Cloud
Coming Soon!

### Part V - Managing Preferences and Consent 
Coming Soon!

### Part VI - Unsubscribe feedback loop 
Coming Soon!
