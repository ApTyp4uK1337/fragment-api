# getWalletBalance

Get Wallet Balance.

- **GET:** `/getWalletBalance`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                                 |
|--------------------|------------|---------------|-------------------------------------------------|
| `wallet_address`   | `string`   | ❌            | Wallet Address.                                 |
| `is_testnet`       | `boolean`  | ❌            | Is testent. Default: `false`.                   |

---

###### Response

```json
{
    "status": true,
    "message": "OK",
    "data": {
        "wallet_address": "EQCx_Ygh-MNklDp3VeGh9opQRstuv_x7yNzJrWxYZklAB",
        "balance_ton": 2.94662135,
        "balance_nano": 2946621350
    }
}
```