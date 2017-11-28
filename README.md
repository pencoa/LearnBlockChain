reference: [Learn Blockchains by Building One](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)


```
curl -X POST -H "Content-Type: application/json" -d '{
 "sender": "d4ee26eee15148ee9226cd394edd974e",
 "recipient": "6b8b09c750e2417d34036d32c635b90e",
 "amount": 6
}' "http://localhost:5000/transactions/new"

curl -G "http://localhost:5000/chain"
```
