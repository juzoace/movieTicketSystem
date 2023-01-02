# Movie Ticket System

This is a movie ticketing system that alsows users purchase tickets of their favorite movies. A code-aong course on microservices with react.js/next.js

## What's included In this repository
* A microservices application which has a (Next.js) client and several mini-services which handle various critical business workflow that determines the functionaity of the application.
* The application is setup in a kubernetes cluster and each mini-service is hosted in a pod (in that cluster)
* NATS was used a communication channel (Event bus) between the services
* Cookies was used as a medium of transfer for the JWT (used for authentication)
* For each service that requires a medium of storage, a seperate database was provisioned for it
