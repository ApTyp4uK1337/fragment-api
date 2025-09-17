# getStarsCost

Get stars cost.

- **GET:** `/getStarsCost`

---

## 📥 Request parameters

| **Parameter** | **Type** | **Required**  | **Description**                        |
|---------------|----------|---------------|----------------------------------------|
| `username`    | `string` | ✅            | Telegram username.                     |
| `quantity`    | `int`    | ✅            | Stars amount (from `50` to `1000000`). |

---

###### Response

```json
{
    "status": true,
    "message": "Estimated cost for 50 stars: 0.2424 TON",
    "data": {
        "username": "bloody_anus",
        "quantity": "50",
        "amount_ton": 0.2424,
        "amount_nano": 242400000
    }
}
```