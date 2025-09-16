# getPremiumRecipient

Get premium recipient info by username.

- **GET:** `/getPremiumRecipient`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                                 |
|--------------------|------------|---------------|-------------------------------------------------|
| `username`          | `string`  | ❌            | Recipient username.                             |
| `months`            | `int`     | ❌            | Premium subscription duration in months.        |

---

###### Response

```json
{
    "status": true,
    "message": "User @monk is already subscribed to Telegram Premium",
    "data": {
        "username": "monk",
        "exists": true,
        "can_receive_premium": false,
        "error": "already_premium"
    }
}
```