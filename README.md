# interview-questions

# Task      
Make a GET request from the following  API endpoint and populate the 3 fields on a webpage  (name, height, birth_year).   
  
API Endpoint - https://swapi.dev/api/people. 
  
Read more about this API here - https://swapi.dev/    
  
***Use any programming language of your choice.***  

  
The output should look something like this -  
https://interviewtasks.fabricprojects.co.nz/ 

# Question 
  
If you have to change the web-hosting of a website and migrate it to a new server, which of the following DNS records would you change and why?

This is the snippet of the current DNS zone file pointing to the old server -

| Type of record | Name | Value/IP address     |
|----------------|------|----------------------|
| A              | @    | 44.33.22.11          |
| A              | www  | 44.33.22.11          |
| MX             | @    | mx1.someemail.co.nz  |
| MX             | @    | mx2.someemail.co.nz  |
| NS             |      | ns1.oldhosting.co.nz |
| NS             |      | ns2.oldhosting.co.nz |

These are some of the details of a new server.     

Public IP address - 11.22.33.44 

Name server records-    
ns1.newhosting.co.nz     
ns2.newhosting.co.nz   
