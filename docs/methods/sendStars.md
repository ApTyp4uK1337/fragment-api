# sendStars

Send stars to user.

- **POST:** `/sendStars`

---

## 📥 Request parameters

| **Parameter** | **Type** | **Required**  | **Description**                                    |
|---------------|----------|---------------|----------------------------------------------------|
| `username`    | `string` | ✅            | Telegram username                                  |
| `quantity`    | `int`    | ✅            | Quantity of subscriptions (from `50` to `1000000`) |
| `mnemmonics`  | `array`  | ✅            | TON wallet mnemonics                               |

---

###### Response

```json
{
    "status": true,
    "message": "Purchase of 50 stars for @monk completed",
    "data": {
    }
}
```