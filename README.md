This adaptar provides test data and is built for hackathon purposes

# Install
```
To Run the adaptar
1. Clone The repo
2. yarn
3. yarn start

app runs at port:8080
```
# Query
```
# To get data of a real-estate property

Send Request with following attributes

method:- POST,
body:- { "id": 0, "data": { "name": "Mannat"} }
URL:- "http://localhost:8080"

OR

# Copy this query in the terminal/postman
curl -X POST \
  http://localhost:8080/ \
  -H 'Postman-Token: ac14a2c7-7c90-4817-88c0-552044b2fb54' \
  -H 'cache-control: no-cache' \
  -H 'content-type: application/json' \
  -d '{ "id": 0, "data": { "name": "Mannat"} }'
  
```
# Example Response
```
{
    "jobRunID": 0,
    "data": [
        {
            "_id": "5f625f9008db9e00178eb21b",
            "name": "Mannat",
            "location": "Bandra, Mumbai",
            "owner": "Jon Doe",
            "type": "Penthouse",
            "country": "India",
            "surfaceArea": 3000,
            "closePrice": 29933,
            "imageUrl": "",
            "Details": "",
            "zipcode": "",
            "contact": "+911234567890",
            "__v": 0
        }
    ],
    "result": {
        "name": "Mannat",
        "surfaceArea": 3000
    },
    "statusCode": 200
}
```
