-------------------------------------------------------------------------------------------------------------------------------------
[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQ1Gu)  (Book API)

[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQ1MR)    (Student API)

[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PR1eK)    
 Download CVS and JSON link: Link : (https://raw.githubusercontent.com/ayotunde725/api-automation/refs/heads/main/book.json)     
                            https://raw.githubusercontent.com/ayotunde725/api-automation/refs/heads/main/books.csv      (Data Driven Book API)

                            
[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4Mu1n6)   (PetStore-API-With-JSON-Model)

[View Full API Documentation Here](https://documenter.getpostman.com/view/54261214/2sBY4PQfwE)    (PetStore-API-With-XML-Model)

--------------------------------------------------------------------------------------------------------------------------------------



Book_API — Postman Collection

 About
A complete Book Store REST API test suite built 
with Postman. All requests are chained together 
using environment variables, allowing the entire 
workflow to run seamlessly through the 
Collection Runner.

 Postman Documentation
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


_______________________________________________________________________________________________________________________________________________________


BOOK API DATA DRIVEN 

The Book_API_DataDriven collection is an advanced API test suite built with Postman that demonstrates professional-level Data Driven Testing techniques. Rather than testing a single fixed scenario, this collection automatically executes the same workflow multiple times using different test data loaded from a CSV file or json simulating real-world testing environments used in enterprise software companies.


What makes this collection special is that, every test iteration runs with a complete different customer name, book ID and quantity, all sourced automatically from a CVS file or a Json. This proves that the API works correctly multiple data scenarios, not just one fixed example 

Data Driven Testing (DDT) is an advanced automation approach where test inputs and expected results are stored separately in an external file (such as a CSV or Excel file or JSON) and fed into the test automatically during execution

Data Driven Validation
✓	Each CSV row executes independently
✓	Different customer names tested per iteration
✓	Different book IDs tested per iteration
✓	All iterations pass consistently


Follow these steps to execute the Data Driven Book API collection using Postman Collection Runner:

Download the file book.csv or book.json from the GitHub repository link provided in the documentation.
           Link : (https://raw.githubusercontent.com/ayotunde725/api-automation/refs/heads/main/book.json)
Click the collection name in the left sidebar, then click the Run button to open Collection Runner.
In Collection Runner, click Select File under the Data section and choose book.csv from your computer.
Set the number of Iterations to match the number of rows in your CSV file (e.g. 5 iterations for 5 rows).
Click Run ZEE_Book_API_DataDriven and watch all iterations execute automatically with different data.
After completion, review the results panel. Each iteration shows pass/fail for all 6 test assertions.






_______________________________________________________________________________________________________________________________________________________


Dr. Yusuf Ayodeji
(QA Automation Engineer)
