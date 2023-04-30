# crAPI-Walkthrough

crAPI is a API that is dilberatly vulnerable with OWASP API Top 10 security risks. Its purpose is to create a safe practice environment where different vulnerability categories can be tested and experimented on in order to understand concepts. My walkthrough is not centered around getting through this project but more on understnading the concepts behind why a certain attack vector is possible. Understanding the concept is much more valuable than passing a lession/ practical because a concept can be applied to any environment. A practical/ lesson is applicable in that context only. 



## Business Functionality

The crAPI in terms of "business" functionality, is made to allow users to manage their cars in terms of purchasing accessories, service and send any enquires regarding their car. There is a community space whereby users of the API can interact with each other. 



## Installation 

I will not go over the installation process as it is already covered by the Project Developers. crAPI can be found at : https://github.com/OWASP/crAPI 


## OWASP Vulnerabilities

The TOp 10 OWASP Vulnerabilities concerning APIs are 

    1. Broken Object Level Authorization
    2. Broken User Authentication
    3. Excessive Data Exposure
    4. Lack of Resources & Rate Limiting
    5. Broken Function Level Authorization
    6. Mass Assignment
    7. Secrutiy Misconfigurations
    8. Injections
    9. Improper Assets Management
    10. Insufficient Logging & Monitoring

For each category I will give an overview along with other resources in order to explain the general concepts and then finalize by tailoring the vulnerability to crAPI. 




## Enviornmental Awareness  

    1. Do you understand the purpose of API? 
    2  What are the assets / type of information that would be protected ? Usernames, email addresses, account information ??? 
    3. What documentation is available?
    4. Can you add any information to any documentation provided ?
    5. What actions can be taken? Email changes/ profile picture uploads / Password Resets etc




## Procedure

There is no right or wrong procedure, at least not specifically. What works for you may not work for others. Gnerally there is one foundational step that determines how smooth the road ahead is. Understand what is going on. So the first step before attacking an API is understand the 
- endpoints
- operations
- mechanism utilized
- assets that may need to be protected / that are contained. 
    
**Step 1**
Get Documentation. Either what is aviable publicly or reverse engineer the API. 

**Step 2**
Go get em tiger

## Tools utilized 

    1. Burp Suite (JWT Editor extenion, Sequncer, Repeater, Decoder)
    2. Postman
    3. mitmweb & mitmproxy2swagger
    4. Kiterunner
    5. Ffuf / Wfuzz or any other similar functionality
    6. Nmap 
    7. Online Search Engines / Shodan
    8. JWT_Tool
    9. Arjun
    10. https://jwt.io


#### Challenge Questions 

Challenges for the crAPI can be found at : https://github.com/OWASP/crAPI





## Important Notes

Pay attention to detail. Details matter


## To do
- Seperate repository for APIs and add DVWS-Node and other API walkthrough
