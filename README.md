# Casha-Api-Suite
A repo for both the json collection and environments 

Document for API Automation 

1.Install Node 

2.Install Newman  “npm install -g newman ”

3.npm install -g newman-reporter-htmlextra

4. Newman run collection-json/URL -e environment.json –bail -r htmlextra –reporter-htmlextra-export path/to/store/report
      a. Where collection.json/URL is the collection to be runned
      b. Environment.json is the environment variables 
      c. --bail flag telling newman to fail the build if any test case fails 
      d. -r htmlextra is the reporter to be used 
      e. –reporter-htmlextra-export followed by the path to store the report

The command to be executed looks like the below  :
newman run /Users/benjaminamuzu/Downloads/Devops.postman_collection1.json -e /Users/benjaminamuzu/Downloads/CashaStaging.postman_environment.json -r htmlextra --reporter-htmlextra-export /Users/benjaminamuzu/Downloads

