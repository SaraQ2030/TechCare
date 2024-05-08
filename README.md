![Logo](https://github.com/DeemaSWE/TechCare/assets/90179257/cf227e04-3d70-4f45-b261-f62519a8dff8)

# TechCare

_Welcome to TechCare!_

TechCare is your reliable destination for all your electronic repair needs. We connect you with skilled technicians who can  restore your malfunctioning devices. Our platform caters to three users: Customers, Technicians, and Trainees.

_For Customers_

- Find skilled, trusted technicians who can fix your devices .
- Our platform makes it simple to request a repair, track progress, and leave feedback.
- Browse technician profiles and ratings to make informed decisions.

_For Technicians_

- Reach more customers and gain visibility for your repair skills.
- Accept or decline requests, setting your own hours and workload.
- Train the next generation of technicians and leave a lasting impact.

_For Trainees_

- Learn from experienced technicians and get hands-on training.
- Build your experience and reputation as a repair technician.
- Connect with technicians dedicated to sharing their knowledge.

## Tools
- Intellij
- DataGrip
- Postman
- Xampp
- Figma
- Canva

## Dependencies
- Lombok
- Validation
- Spring Web
- Spring Security
- Spring Data JPA
- MySQL Driver
- JUnit tests
## Presentation
https://www.canva.com/design/DAGEkE6e5qk/PMreR9pmtzD674fN389cjw/edit?utm_content=DAGEkE6e5qk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## API Documentation
https://documenter.getpostman.com/view/33389231/2sA3JJA441
## Figma
https://www.figma.com/file/Ifmivq19uWHkpAEAQG3IZ3/Figma-basics?type=design&node-id=1669%3A162202&mode=design&t=AVVffBJIKCgRwYn8-1

## Models
- Customer
- Product
- Request
- CustomerDTO
- RequestDTO

## Security Configuration
- AuthController
- CustomerContrller
- ProductController
- RequestController
- TrainerController
  
## Junit Test
- CategoryControllerTest
- CustomerControllerTest
- ProductControllerTest

## Endpoints

_Sara's Endpoints_
| No. | Endpoint | Description |
| --- | --- | --- |
| 1 | POST /api/v1/customer/register | Customer register |          
| 2 | GET /api/v1/customer/get-profile | Customer get their profile |
| 3 | PUT /api/v1/customer/update | Customer update their profile |
| 4 | GET /api/v1/product/get-all | Get all products |
| 5 | POST /api/v1/request/customer-send-request/{serviceId} | Customer send a request |
| 6 | PUT /api/v1/customer/rate-tech/{techID}/{reqId}/{rate} | Customer rate technician |
| 7 | GET /api/v1/order/get-order-by-status/{status} | Customer get order by status |
| 8 | GET /api/v1/order/get-order-by-date/{date} | Customer get order by date   
| 9 | GET /api/v1/request/customer-get-my-request | Customer get their requests |
| 10 |  POST /api/v1/request/trainer-send-request/{serviceId} | Trainer send a request |
| 11 |  PUT /api/v1/request/change-customer-request-status/{reqId} | Technician change customer requests status to be completed |
| 12 | PUT /api/v1/request/customer-rate-request/{reqId}/{rate} | Customer Rate Request |
| 13 |GET /api/v1/product/get-product/{productId} | Get product by id |
| 14 |GET /api/v1/product/get-product-category/{category} | Get products by category |
| 15 |GET /api/v1/product/filter-price/{minPrice}/{maxPrice} | Get products by price range |
| 16 |POST /api/v1/product/add-product/{catId} | Admin add a product |
| 17 | DELETE /api/v1/customer/delete/{customerId} | Admin delete customer |
| 18 |PUT /api/v1/product/update-product/{productId}/{catId} | Admin update a product |
| 19 | DELETE /api/v1/request/delete/{request_num} | Admin delete a request |
| 20 |DELETE /api/v1/product/delete-product/{productId} | Admin delete a product |
| 21 | GET /api/v1/customer/get-all | Get all customers |
| 22 | GET /api/v1/request/customer-request-status/{status} | Customer get Requests by status |
| 23 | GET /api/v1/request/change-trainer-request-status/{reqId} | Technician change requests status to be completed and set hours |
| 24 | GET /api/v1/request/tech-get-request | Technician get requests |
| 25 | GET /api/v1/request/trainer-get-request | Trainer get their requests |
| 26 | GET /api/v1/auth/get-all | Admin get all users |

## Class Diagram
## Use Case Diagram
![Final_use_case_Diagram drawio](https://github.com/DeemaSWE/test/assets/90179257/68ee24a9-0153-4db3-b50f-3689ca525b07)
