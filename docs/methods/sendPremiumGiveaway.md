# sendPremiumGiveaway

Send premium giveaway to channel.

- **POST:** `/sendPremiumGiveaway`

---

## 📥 Request parameters

| **Parameter** | **Type** | **Required**  | **Description**                                      |
|---------------|----------|---------------|------------------------------------------------------|
| `channel`     | `string` | ✅            | Telegram username or t.me link                       |
| `quantity`    | `int`    | ✅            | Quantity of subscriptions (from `1` to `24000`)      |
| `months`      | `int`    | ✅            | Subscription duration in months (available: `3`, `6`, `12`) |
| `mnemmonics`  | `array`  | ✅            | TON Wallet mnemonics                                 |

---

###### Response

```json
{
    "status": true,
    "message": "@aptyp4uk1337 premium giveaway completed: 1×3 months",
    "data": {
        "amount": 4860000000,
        "from": "EQBs_Xdf-LSbjBk0VeKd1clGBltpqu_k4rMzIqwfMSjqZlIR",
        "status_code": 200,
        "success": true,
        "to": "UQBAjaOyi2wGWlk-EDkSabqqnF-MrrwMadnwqrurKpkla4QB"
    }
}
```