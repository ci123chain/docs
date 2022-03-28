# SetWithdrawAddress

```
nodeShardInstance
    .setWithdrawAddress({
        nonce,
        gas,
        msg:{
            withdraw_address
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string] // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object].withdraw\_address\[string] // withdrawal address

### return value

msg\[Promise\<string>] // hash

### example

```
// Your account must have test tokens
nodeShardInstance
.setWithdrawAddress({msg:{
    withdraw_address:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6'
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

