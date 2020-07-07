# Rocketseat Bootcamp Exercise

This is an simple node.js appication that manages transactions and listing them and showing current balance.


This is the resulting query.
```json
{
  "transactions": [
    {
      "id": "uuid",
      "title": "Salary",
      "value": 4000,
      "type": "income"
    },
    {
      "id": "uuid",
      "title": "Freelance Job",
      "value": 2000,
      "type": "income"
    },
    {
      "id": "uuid",
      "title": "Invoice Payment",
      "value": 4000,
      "type": "outcome"
    },
    {
      "id": "uuid",
      "title": "Office Chair",
      "value": 1200,
      "type": "outcome"
    }
  ],
  "balance": {
    "income": 6000,
    "outcome": 5200,
    "total": 800
  }
}
```
## Executing it
To reproduce it you need node.js and yarn installed:

Install needed modules
```
yarn
```

Start local server
```
yarn dev:server
```

Check routes files to know endpoints as it is a code under constant work

This code is under MIT License, following original Rocketseat work.
