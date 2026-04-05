# RESTful-Booker Test Cases

| # | Method | Endpoint | Test | Expected |
|---|--------|----------|------|----------|
| 1 | POST | /auth | Create Token | 200 OK |
| 2 | POST | /booking | Create Booking | First name matches |
| 3 | GET | /booking/{{id}} | Get Booking | 200 + response < 1000ms |
| 4 | PUT | /booking/{{id}} | Update Price | Price updated to 1500 |
| 5 | DELETE | /booking/{{id}} | Delete Booking | 201 Created |
