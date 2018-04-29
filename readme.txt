Commands


curl -X POST -H "Content-Type: application/json" -d '{
 "sender": "SINCLAIR",
 "recipient": "BEN",
 "amount": 5
}' "http://localhost:5000/transactions/new"

curl -X POST -H "Content-Type: application/json" -d '{
 "sender": "SINCLAIR",
 "recipient": "SARA",
 "amount": 5
}' "http://localhost:5000/transactions/new"




curl -X POST -H "Content-Type: application/json" -d '{
 "nodes": ["127.0.0.1:5001"]
}' "http://localhost:5000/nodes/register"
