# Project Details
This is the **holy-grail** for a contributor to learn about the entire project in-depth.

# Contents

1. [MVC Diagram](#mvc-diagram)
2. [Database Design](#database-design)
3. [Usecase Diagram](#usecase-diagram)
4. [Activity Diagram](#activity-diagram)
5. [Screenshots of the Project](#screenshots-of-the-project)
   1. [Customer Database (MongoDB) Schema](#customer-database-mongodb-schema)
   2. [Product Database (MongoDB) Schema](#product-database-mongodb-schema)
   3. [Order Database (MongoDB) Schema](#order-database-mongodb-schema)
   4. [Customer Routes](#customer-routes)
   5. [Product Routes](#product-routes)
   6. [Order Routes](#order-routes)
   7. [Middleware for Customer Authentication](#middleware-for-customer-authentication)
   8. [Middleware for Error Handler](#middleware-for-error-handler)
   9. [Implementation of JWT Token](#implementation-of-jwt-token)
   10. [New Customer Registration Route/API](#new-customer-registration-route-api)
     - [POST Request for Customer Registration](#post-request-for-customer-registration)
   11. [Customer Login Route/API](#customer-login-route-api)
     - [POST Request for Custom Login](#post-request-for-custom-login)
   12. [Get Customer Details Route/API](#get-customer-details-route-api)
   13. [Update Customer Profile Route/API](#update-customer-profile-route-api)
     - [Customer Details Update Route](#customer-details-update-route)
   14. [Update Customer Password Route/APl](#update-customer-password-route-api)
   15. [Product Creation Route/API](#product-creation-route-api)
     - [POST Request for Production Creation Route](#post-request-for-production-creation-route)
   16. [Get all Products (Admin) Route/API](#get-all-products-admin-route-api)
     - [GET Request for Get All Products Route](#get-request-for-get-all-products-route)
   17. [Get Product Details Route/API](#get-product-details-route-api)
     - [GET Request Get Product Details Route](#get-request-get-product-details-route)
   18. [Update Product (Admin) Route/API](#update-product-admin-route-api)
     - [PUT Request for Update Product Route](#put-request-for-update-product-route)
   19. [Delete Product Route/API](#delete-product-route-api)
     - [DELETE Request for Delete Product Route](#delete-request-for-delete-product-route)
   20. [New Order Creation Route/API](#new-order-creation-route-api)
     - [POST Request for New Order Creation Route](#post-request-for-new-order-creation-route)
   21. [Get Single Order Route/API](#get-single-order-route-api)
     - [GET Request for Get Single Order Route](#get-request-for-get-single-order-route)
   22. [Get Logged in Customer Order Route/API](#get-logged-in-customer-order-route-api)
     - [GET Request for Get Logged in Customer Order Route](#get-request-for-get-logged-in-customer-order-route)
   23. [Update Order Status (Admin) Route/API](#update-order-status-admin-route-api)
     - [PUT Request for Update Order Status Route](#put-request-for-update-order-status-route)
   24. [Delete Order(Admin) Route/API](#delete-orderadmin-route-api)
     - [DELETE Request for Delete Order Route](#delete-request-for-delete-order-route)





### MVC Diagram

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/da372c9a-edd8-4816-ab09-436dd0b00195)



### Database Design


**1.	Customer Collections in MongoDB**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/27cde241-a5b7-4ece-a441-0f2040faa926)



**2.	Product Collections in MongoDB**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/ffb30092-5a78-400c-8671-9df6c74381d6)


**3.	Order Collections in MongoDB**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/368691d1-da9b-422e-b722-80da7a835c53)


### Usecase Diagram

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/1ec30aa8-08f7-44ee-9fdd-51f1dcf94ea9)

### Activity Diagram


**1.	Login Activity Diagram**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/190db9a2-6813-4021-82c4-e791ea8f7246)


**2.	Registration Activity Diagram**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/bdbe4903-f32e-42c9-8c3a-222f455705d3)


**3.	Admin Registration Activity Diagram**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/0f8c9339-362d-44f4-af7b-743e8041bb68)


**4.	Admin Login Activity Diagram**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/697ea02c-1cf2-4bc3-a324-808cc0a7e3fd)


**5.	User Activity Diagram**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/8e446cf0-ec52-4e5e-9517-68533c2c6b92)


### Screenshots Of The Project

**1.	Customer Database (MongoDB) Schema**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/1a649afc-4c4a-44d3-b606-98e5e23288d9)


**2.	Product Database (MongoDB) Schema**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/3b7fee5c-3bee-4c6b-b0b8-649bcd94ea44)


**3.	Order Database (MongoDB) Schema**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/59635387-41bf-4d34-a6d2-70026f4fb6b4)


**4.	Customer Routes**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/209aec36-3c63-42e7-b755-3919f08c9782)


**5.	Product Routes**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/be245f6b-a87e-4c30-863b-3bf7471ac4dc)


**6.	Order Routes**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/04955d4c-c5fa-4430-9e8e-d33069119bc6)


**7.	Middleware for Customer Authentication**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/867e73c6-c5de-4b60-8e0b-edcd7b5e090b)


**8.	Middleware for Error Handler**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/ba54d54b-f9b1-4c28-834c-4863527bce8e)


**9.	Implementation of JWT Token**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/31797131-8dcf-4f5e-ade5-9740bd4169c5)


**10.	New Customer Registration Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/6f778757-018c-4517-9da3-09b9b18c2781)

**POST Request for Customer Registration**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/bfcb8d0f-1e98-4b9c-a912-ff0c582f8acc)


**11.	Customer Login Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/5130f8cf-7808-4a4d-9795-c6ee0cd9637c)

**POST request from Customer Login**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/ff4f579b-9f3c-40ec-8def-4fea8ff37a3b)


**12.	Get Customer Details Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/64cf87be-e96f-46b4-9e00-d6d4b5bf4444)


**13.	Update Customer Profile Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/50d41af0-e126-4c33-b7eb-abc41a4dbf29)

**Customer Details Update Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/843b84a4-a58e-4f18-92c1-8119877bf022)


**14.	Update Customer Password Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/201e986d-4dca-4d54-bff1-8f7261765c1c)


**15.	Product Creation Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/396063c1-9460-4b4f-80b0-7f70f51d7191)

**POST request for Product Creation Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/10ad824f-4749-40d2-96fd-44d309f5e8f4)


**16.	Get All Products (Admin) Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/fe63562d-1fa9-433a-847e-6430c92fd429)

**GET request for Get All Products Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/5da96418-fb08-4638-9d3e-b706ad735562)


**17.	Get Product Details Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/1572497a-bffb-4505-b7b9-7bf00f7c5fdb)

**GET request for Get Product Details Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/6e4adb2a-b396-4b59-8847-8845257b40c9)


**18.	Update Product (Admin)  Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/5d2cc194-d637-458f-9b4f-4bbab39fee74)

**PUT request for Update Product Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/7cb11583-26bd-4ff4-bad5-797d3e0adba6)


**19.	Delete Product Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/f1198ec6-bc8d-4cf4-a2d0-578b56f3cda3)

**DELETE request for Delete Product Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/28e79a8e-1cc0-4c44-955c-432eb88e2aa3)


**20.	New Order Creation Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/60143c79-c44d-4ec8-8250-117f7d77a22f)

**POST request for New Order Creation Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/d48a7b22-1ed2-4c89-a67b-eb7b5cc8a557)


**21.	Get Single Order Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/1c4c7ab6-c599-4ccd-969f-cbc58e6272ba)

**GET Request for Get Single OrderRoute**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/c585e1dd-9cbc-4f4b-9520-608adcca5aa0)


**22.	Get Logged in Customer Orders Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/61124e33-cdaa-4e1c-a293-ee1d4e7becf6)

**GET request for Get Logged In Customer Orders Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/ff691f36-2730-4121-a707-73a961d4e33c)


**23.	Update Order Status (Admin) Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/4c896590-de51-42b1-bc4e-bfef98720320)

**PUT request for Update Order Staus Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/6811e967-8236-4a4e-bdeb-043d9918ba5f)


**24.	Delete Order (Admin) Route/API**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/034ae168-0a90-4225-b759-370b7667e4eb)

**DELETE request for Delete Order Route**

![image](https://github.com/Trisha-tech/OnlineBookSales-Backend/assets/55338588/c715d391-5a08-434e-bd81-63f44839c5de)

**With that we hope you have a clear understading of the entire project now you can start contributing :)**
