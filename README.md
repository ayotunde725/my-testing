-------------------------------------------------------------------------------------------------------------------------------------
[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQ1Gu)  (Book APi)

[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQ1MR)    (Student API)

--------------------------------------------------------------------------------------------------------------------------------------



Book_API — Postman Collection

 About
A complete Book Store REST API test suite built 
with Postman. All requests are chained together 
using environment variables, allowing the entire 
workflow to run seamlessly through the 
Collection Runner.

 📖 Postman Documentation
[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQ1Gu)

 
[Book API Base URL](https://simple-books-api.click)

Key Features
- ✅ Dynamic token generation
- ✅ Dynamic order ID chaining
- ✅ Full CRUD order management
- ✅ Data-driven testing
- ✅ Automated test assertions

 API Workflow
POST Generate_Token → saves token
        ↓
GET Get_List_of_Books → browse available books
        ↓
GET Get_non_fiction_books → filter by type
        ↓
POST Submit_Order → uses token → saves order ID
        ↓
GET Get_List_of_Orders → uses token
        ↓
GET Get_Specific_Order → uses order ID
        ↓
PATCH Edit_Order → uses order ID
        ↓
DELETE Delete_Order → uses order ID

Requests Overview

| Method | Request | Description |
|--------|---------|-------------|
| GET | To_Get_Status | Check API health |
| GET | Get_List_of_Books | Get all books |
| GET | Get_non_fiction_books | Filter non-fiction |
| GET | Get_specific_limit | Get books with limit |
| POST | Create_book_to_generate_Token | Generate auth token |
| POST | Submit_order | Create new order |
| GET | Get_List_of_Orders | Get all orders |
| GET | Get_Specific_orders | Get one order by ID |
| PATCH | Edit_an_order | Update order |
| DEL | Delete_Orders | Delete order |

 Test Coverage
- ✅ Status code validation (200, 201, 204)
- ✅ Response body validation
- ✅ Data type validation
- ✅ Response time validation
- ✅ Authentication token chaining
- ✅ Order ID chaining
- ✅ Schema validation

 Environment Variables

| Variable | Description | Set By |
|----------|-------------|--------|
| baseUrl | API base URL | Manual |
| token | Auth token | POST Generate_Token |
| id | Order ID | POST Submit_Order |

 How to Run
1. Import collection into Postman
2. Set environment variables
3. Open Collection Runner
4. Run in order shown above
5. All requests execute automatically

_______________________________________________________________________________________________________________________________________________________________

My_Student_API — Postman Collection

ABOUT 
A complete Student REST API test suite built 
with Postman. This collection demonstrates 
comprehensive API testing skills including 
response validation, schema validation, 
data type testing, and array property testing.

POSTMAN DOCUMENTATION
[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQ1MR)

 Live Student API
[Student API Base URL](https://my-json-server.typicode.com/ayotunde725/student-api/student)

 Key Features
- ✅ Status code validation
- ✅ Response body validation
- ✅ Schema validation 
- ✅ Data type validation
- ✅ Array property testing
- ✅ JSON field validation
- ✅ Response time validation
- ✅ Header validation






Dr. Yusuf Ayodeji
(QA Automation Engineer)
