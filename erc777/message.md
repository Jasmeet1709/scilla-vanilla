### name
```
{
    "_tag" : "name",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
       
    ]
}
```
### symbol
```
{
    "_tag" : "symbol",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
       
    ]
}
```
### granularity
```
{
    "_tag" : "granularity",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
       
    ]
}
```
### totalSupply
```
{
    "_tag" : "totalSupply",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
       
    ]
}
```

### balanceof
```
{
    "_tag" : "balanceOf",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
          {
            "vname": "tokenOwner",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234567850"
        }
    ]
}
```

### Send
```
{
    "_tag" : "Send",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
          {
            "vname": "to",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234567850"
        },
          {
            "vname": "amount",
            "type" : "Uint128",
            "value" : "3"
        },
          {
            "vname": "_userData",
            "type" : "String",
            "value" : "userdata"
        }
    ]
}
```

### authorizeOperator
```
{
    "_tag" : "authorizeOperator",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
          {
            "vname": "operator",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234563350"
        }
    ]
}
```

### isOperatorFor
```
{
    "_tag" : "isOperatorFor",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
          {
            "vname": "operator",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234567890"
        },
          {
            "vname": "tokenHolder",
            "type" : "ByStr20",
            "value" : "0x12345678901234567890123456789012345678cd"
        }
    ]
}
```
### operatorSend
```
{
    "_tag" : "operatorSend",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234563350",
    "params" : [
        {
            "vname": "from",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234567890"
        },
          {
            "vname": "to",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234567850"
        },
          {
            "vname": "amount",
            "type" : "Uint128",
            "value" : "13"
        },
          {
            "vname": "userData",
            "type" : "String",
            "value" : "userdata"
        },
          {
            "vname": "operatorData",
            "type" : "String",
            "value" : "operatordata"
        }
    ]
}
```

### revokeOperator
```
{
    "_tag" : "revokeOperator",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
          {
            "vname": "operator",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234563350"
        }
    ]
}
```

### burn
```
{
    "_tag" : "burn",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567890",
    "params" : [
       
          {
            "vname": "amount",
            "type" : "Uint128",
            "value" : "3"
        },
          {
            "vname": "data",
            "type" : "String",
            "value" : "userdata"
        }
    ]
}
```

### operatorBurn
```
{
    "_tag" : "operatorBurn",
    "_amount" : "0",
    "_sender" : "0x1234567890123456789012345678901234567870",
    "params" : [
       
          {
            "vname": "amount",
            "type" : "Uint128",
            "value" : "30"
        },
          {
            "vname": "userData",
            "type" : "String",
            "value" : "userdata"
        },
          {
            "vname": "from",
            "type" : "ByStr20",
            "value" : "0x1234567890123456789012345678901234567890"
        },
          {
            "vname": "operatorData",
            "type" : "String",
            "value" : "userdata"
        }
    ]
}
```