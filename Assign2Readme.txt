Documentation for Assignment 2
Pre-req - Create a field on Contact called Profile, text, 255
Task - "When an Account is updated and the Website is filled in, update the Profile field on all Contacts to:
Profile = Website + ‘/’ + First Letter of First Name + Last Name"

Step 1 - Go to Salesforce Playground
Step 2- Go to setup.
Step 3 - Click on Object Manager.
Step 4 - Click on contacts , then click on Fields and relationship.
Step 5 - Click New to create a new custom field called Profile.
Step 6 - Choose Text (255) 
Step 7- Insert the field label as Profile
Step 8 - Click next, next and save
Step 9 - Go to Developers Option.
Step10 - Go to file, Click New Apex Triggers
Step 11 - Give it a Name
Step 12 - sObject would be Account here , because we are checking the change through Account.