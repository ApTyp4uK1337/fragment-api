# createWallet

Create TON wallet.

- **POST:** `/createWallet`

---

## 📥 Request parameters

| **Parameter**      | **Type**   | **Required**  | **Description**                                 |
|--------------------|------------|---------------|-------------------------------------------------|
| `version`          | `string`   | ❌            | Wallet version. Default: `v4r2`.                |

---

###### Response

```json
{
    "status": true,
    "message": "Wallet successfully created",
    "data": {
        "wallet_address": "EQBpLkkFD-CT8AVz78z6vxL9UMUvN4ugl1_23TAVVQONZSiB",
        "wallet_address_testnet": "kQBpLkkFD-CT8AVz78z6vxL9UMUvN4ugl1_23TAVVQONZZML",
        "public_key": "c462fb3cb1b6c0ab7935fbb4f4a8dcbfaaaca44616962102d86777285ec32fbb",
        "mnemonics": [
            "trick",
            "chase",
            "envelope",
            "prosper",
            "ancient",
            "patient",
            "humble",
            "toilet",
            "search",
            "calm",
            "zero",
            "athlete",
            "hurdle",
            "cream",
            "secret",
            "scout",
            "rural",
            "rug",
            "unable",
            "tube",
            "duty",
            "awful",
            "useless",
            "error"
        ]
    }
}
```