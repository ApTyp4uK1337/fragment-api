# getPremiumGiveawayChannel

Get premium giveaway channel.

- **GET:** `/getPremiumGiveawayChannel`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                 |
|--------------------|------------|---------------|---------------------------------|
| `channel`          | `string`  | ✅             | Telegram username or t.me link  |

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
        "photo": "https://cdn4.telesco.pe/file/ElscCpGdGFHB3RCbB8ZkwXJNFg_3yi5q_a5bwnBpNKiHLPLMlq2G0wf5m7RmykcT0rAvnLgEtxUz7rk4699VmIHdrKgoMbfi6g8ASJMsBx3EzLIEERCVgCo6iWTBD-8MMsb6WHgncXff_eVXcP85ZUNc7lImHo1MVthrcHMroqday8jqATZi3EzWx7tEAx0W2gO40sTEqw607U2CXz06JGj_4Do-hPMSM3l45dYoWbKN8tJjhpyd54SjoJBmjqLTtu00NhjgrGViWG1yUxrQE652uIiazmoQaQNwLYN4sFJ0Li556kRD4udMAsoxTyZZmf0NviSAQDSSXByY9ZQ4Hw.jpg",
        "exists": true,
        "can_host_premium_giveaway": true
    }
}
```