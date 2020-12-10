Documentation of Assginment 1
Prereq - Create a field on Account called “is_gold”, checkbox, default off
Task - When Amount field on Opportunity  is greater than $20k, mark is_gold to TRUE.
Step 1- Open Salesforce
step 2- Go to setup, open Object Manager, as we have to create a checkbox in Account.
Step 3 - Open Account and then click fields and relation (for creating new custom field) and make a field with checkbox .
Name it is_gold. Default Value of Checkbox is Unchecked.
click save
Step 4 - Go to developers console or use VS code, CLick new File and chhose Apex Triggers.
Step 5 - Enter Name
Step 6 - sObject as Opportunity because we are using Opportunity to find the change.