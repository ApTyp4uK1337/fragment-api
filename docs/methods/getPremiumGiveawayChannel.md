# getPremiumGiveawayChannel

Get premium giveaway channel.

- **GET:** `/getPremiumGiveawayChannel`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                                 |
|--------------------|------------|---------------|-------------------------------------------------|
| `channel`          | `string`  | ✅             | Telegram username or t.me link.                 |

---

###### Response

```json
{
    "status": true,
    "message": "Channel @aptyp4uk1337 can host premium giveaways",
    "data": {
        "recipient": "lPUAcov-QNqtxmaVa5vKLRk76LmWKxYk0JWUPp0x-AQ",
        "username": "aptyp4uk1337",
        "name": "@aptyp4uk1337",
        "exists": true,
        "can_host_premium_giveaway": true
    }
}
```