# Casha-Api-Suite
A repo for both the json collection and environments 

Document for API Automation 

Install Node 
Install Newman  “npm install -g newman ”
npm install -g newman-reporter-htmlextra
Newman run collection-json/URL -e environment.json –bail -r htmlextra –reporter-htmlextra-export path/to/store/report
Where collection.json/URL is the collection to be runned
Environment.json is the environment variables 
--bail flag telling newman to fail the build if any test case fails 
-r htmlextra is the reporter to be used 
–reporter-htmlextra-export followed by the path to store the report

The command to be executed looks like the below  :
newman run /Users/benjaminamuzu/Downloads/Devops.postman_collection1.json -e /Users/benjaminamuzu/Downloads/CashaStaging.postman_environment.json -r htmlextra --reporter-htmlextra-export /Users/benjaminamuzu/Downloads

