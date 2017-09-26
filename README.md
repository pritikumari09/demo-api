# demo-api

Repository for consumer and producer API for Customers and associated resources.

### API Resources

  - [GET /api/v1/customers](#get- list of customers)
  - [POST /api/v1/customers/customer](#post-create a customer)
  - [GET /api/v1/customers/customer/{customerid}](#get- a customer)
  - [PUT /api/v1/customers/customer/{customerid}](#put- Update customer )
  - [DELETE /api/v1/customers/customer/{customerid}](#delete- remove a customer)

### Set Up and Run the provider API for Customers.

** Note : It assumed that you are familiar with Mulesoft ESB and Anypoint Studio.Also familiar with REST client like POSTMAN etc.

** Note : Provider API is currently mocked with static data.Hence extensive testing or error handling cannot be verified at this stage.
 
Follow the below steps to test the provider API - 

1. Import the "customers" project using pom.xml into anypoint studio.
2. Once imported, run the customers project.
3. Import rest-client/Deloitte - Technical Task.postman_collection into POSTMAN.
4. Run the test collection to verify the API request and responses.

