# FundCommunityPool

```
nodeShardInstance
    .fundCommunityPool({
        nonce,
        gas,
        msg:{
            amount,
            depositor
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string] (You can pass no arguments)
  2. ?gas\[string]\(You can pass no arguments)
  3. msg\[object].amount\[string]
  4. msg\[object].depositor\[string]\(Public fund pool address)

### return value

msg\[Promise\<string>]（hash）

### example

```
// Your account must have test tokens
nodeShardInstance
.fundCommunityPool({msg:{
    amount:'1000000',
    depositor:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6'
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

