# getStarsRecipient

Get stars recipient info by username.

- **GET:** `/getStarsRecipient`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                                 |
|--------------------|------------|---------------|-------------------------------------------------|
| `username`          | `string`  | ✅            | Telegram username.                              |

---

###### Response

```json
{
    "status": true,
    "message": "User @monk can receive stars",
    "data": {
        "recipient_id": "aJhB_03EnR6SUXAX8vrT46HiyWVhOkSyhMhvqlPk2ljPo6okLBc1RQuMvpJSx9qm",
        "username": "monk",
        "exists": true,
        "can_receive_stars": true,
    }
}
```