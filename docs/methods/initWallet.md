# initWallet

Initialize TON walet.

- **POST:** `/initWallet`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                                 |
|--------------------|------------|---------------|-------------------------------------------------|
| `mnemonics`        | `array`   | ❌            | Wallet mnemonics.                |

---

###### Response

```json
{
    "status": true,
    "message": "Wallet initialized successfully",
    "data": {}
}
```