# SendtoEth

```
nodeShardInstance
    .sendtoEth({
        nonce,
        gas,
        msg:{
            eth_dest, 
            amount, 
            denom, 
            bridge_fee_amount, 
            token_type,
            gravity_id
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string]  // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object]

### return value

msg\[Promise\<string>]（hash）

### example

```
// Your account must have test tokens
nodeShardInstance
.sendtoEth({msg:{
    // xxx:xxx
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

