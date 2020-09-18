This adaptar provides test data and is built for hackathon purposes

# Install
```
To Run the adaptar
1. Clone The repo
2. yarn
3. yarn start
```

```
# To get data of a real-estate property

Copy this query
curl -X POST \
  http://localhost:8080/ \
  -H 'Postman-Token: ac14a2c7-7c90-4817-88c0-552044b2fb54' \
  -H 'cache-control: no-cache' \
  -H 'content-type: application/json' \
  -d '{ "id": 0, "data": { "name": "Mannat"} }'
  
```
