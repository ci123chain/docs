# WithdrawValidatorCommission

```
nodeShardInstance
    .withdrawValidatorCommission({
        nonce,
        gas,
        msg:{
            validator_address
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string] // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object].validator\_address\[string] // verifier address

### return value

msg\[Promise\<string>] // hash

### example

```
// Your account must have test tokens
nodeShardInstance
.withdrawValidatorCommission({msg:{
    validator_address:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6'
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

