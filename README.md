* Create a Dialogflow agent with an entity called AppointmentType that could be either
    * service
    * tune up
* 
* Enable Calendar Api in GCloud and create a service account key which would produce a json file with credentials
    * Create a calendar through a google account that does not belong to an organiztion other than google (not aucegypt.edu)
        * Get the **client-email** from this json file and share the newly craeted calendar with that email and give persmission for tis email to **Make changes to events** 
        * Take notice of the **calendarId** because it would be used in the lambda function