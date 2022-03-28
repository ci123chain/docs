# RequestBatch

```
nodeShardInstance
    .requestBatch({
        nonce,
        gas,
        msg:{
            denom, 
            token_type,
            gravity_id
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string]  // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object].denom\[string] // Token contract address
  4. msg\[object].token\_type\[string] // Currency Type (ERC20 ERC721 token) enum 0-> ERC20 1-> ERC721
  5. msg\[object].gravity\_id\[string] // Cross chain instance ID

### return value

msg\[Promise\<string>]（hash）

### example

```
// Your account must have test tokens
nodeShardInstance
.requestBatch({msg:{
    denom:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6',
    token_type:'1',
    gravity_id:'xxx'
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

