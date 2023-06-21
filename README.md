# Assessment

1. Download the node version from https://nodejs.org/en/download.
2. Clone this repository and Run <b>npm install</b> on terminal.
3. Run <b> npm run start</b>.
4. You can use Postman for <b>POST</b> and <b>GET</b> request.
5. You can also use cUrl command: For example,<br> 
To create the Post request: <b>curl -X POST http://localhost:3000/receipts/process  -H 'Content-Type: application/json' -d '{"retailer": "M&M Corner Market", "purchaseDate": "2022-03-20", "purchaseTime": "14:33", "items": [ { "shortDescription": "Gatorade", "price": "2.25" },{ "shortDescription": "Gatorade", "price": "2.25" },{ "shortDescription": "Gatorade", "price": "2.25" },{"shortDescription": "Gatorade", "price": "2.25"}],"total": "9.00"}'</b>
<br><br>To create the Get request: <b>curl http://localhost:3000/receipts/{id}/points</b> (An ID will be come from POST request).

