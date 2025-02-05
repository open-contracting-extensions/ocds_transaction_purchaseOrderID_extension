# Transaction Purchase Order Identifier

This extension adds a purchaseOrderID field to the Transaction object, enabling each transaction to reference a specific purchase order.

## Example

```json
{
  "contracts": [
    {
      "id": "12",
      "awardID": "34",
      "implementation": {
        "transactions": [
          {
            "id": "56",
            "purchaseOrderID": "78"
          }
        ]
      }
    }
  ]
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.
