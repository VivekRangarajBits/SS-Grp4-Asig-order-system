
### Backend

The backend is broken up into multiple smaller fine grained size microservices.
Each business functionality is broken into their own 'domain'. A technique of context boundaries from DDD (Domain Driven Design) is used to come to this conclusion:

| Microservice     | Domain             |
|:-----------------|:-------------------|
| User Service     | User Domain        | 
| Customer Service | Customer Domain    | 
| Order Service    | Order Domain       | 
| Product Service  | Product Domain     | 

### Port Mappings

| Microservice     | Port |                  
|:-----------------|:-----|
| User Service     | 8080 | 
| Customer Service | 8081 | 
| Order Service    | 8082 | 
| Product Service  | 8083 |

