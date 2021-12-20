```bash
stepzen start
```

Test query

```graphql
query TEST_QUERY {
  getTest {
    Date
    DateTime
    Float
    Int
    JSON
    JSON2
    String
  }
}
```

Output:

```json
{
  "data": {
    "getTest": {
      "Date": "2020-03-30",
      "DateTime": "2029-05-09T12:14:04Z",
      "Float": 342.09990382693167,
      "Int": 275,
      "JSON": {},
      "JSON2": {
        "ihdt": "Suspendisse potenti",
        "joygwc": "469",
        "r": 578
      },
      "String": "Mauris massa"
    }
  }
}
```