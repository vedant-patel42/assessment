# Assessment

This small projet is implemented in Node js framework. The test cases are provided in examples folder. In order to test the implementations, follow the below steps with test case.

Download the Node js of any version from https://nodejs.org/en/download.

## To run locally:
1. Clone this repository and Run <b>`npm install`</b> inside project folder.
2. Run <b> `npm run start`</b> command.
3. You can use Postman for <b>`POST`</b> and <b>`GET`</b> request.
4. You can also use cUrl command: For example,<br> 
To create the Post request: <b>`curl -X POST http://localhost:3000/receipts/process  -H 'Content-Type: application/json' -d '{"retailer": "M&M Corner Market", "purchaseDate": "2022-03-20", "purchaseTime": "14:33", "items": [ { "shortDescription": "Gatorade", "price": "2.25" },{ "shortDescription": "Gatorade", "price": "2.25" },{ "shortDescription": "Gatorade", "price": "2.25" },{"shortDescription": "Gatorade", "price": "2.25"}],"total": "9.00"}'`</b>
<br><br>To create the Get request: <b>`curl http://localhost:3000/receipts/{id}/points`</b> (An ID will be come from POST request).

