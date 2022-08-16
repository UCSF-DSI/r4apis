# Summary

## Why use APIs?
- You already use it in daily internet browsing!
- Accessing data
- Analysis Services (e.g., translation api)

## How the internet works
- [YouTube playlist from Code.org](https://youtube.com/playlist?list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7)
- Protocols (http)
- An API (application programming interface) is how applications talk to each other on the internet

## Requests vs Responses
- Client (e.g., your phone, your computer, some other device) sends a request
- Server (e.g., data service, cloud service) sends a response
  - Response will contain a status code (see [list](https://moz.com/learn/seo/http-status-codes))
  
## Two Types of Requests
- GET: Get data
  - Parameters are included in URL
- POST: Modify data
  - Parameters are included in request body
  
## What's inside of a POST request
- JSON: Contains key-value pairs
- Header: Parameters that are consistent each time you send a request (e.g., authentication information)
- Body: Parameters that change based on what you need.

## Demos
- Local API
  - Postman: Great for demos. Not required for development.
  - R: httr, jsonlite, r lists
- Public APIs
  - Documentation
    - URL
    - GET vs POST
    - parameters (what goes into header vs body)
    - authentication
    - usage limits
    
## Activity
- Find a Public API and its documentation (preferably no authentication required)
  - Try to connect to it using R
  - A few demos afterwards of ones that don't require authentication
  
## Other considerations
- Authentication tokens: Don't share them and keep them safe!
- Webscraping: Not always legal. There's a reason some sites don't offer data through APIs.
- Security: If you are loading data to a service, make sure it doesn't contain PHI/PII.
