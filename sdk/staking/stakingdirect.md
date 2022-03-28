# StakingDirect

```
nodeShardInstance
    .stakingDirect({
        nonce,
        gas,
        msg:{ 
            amount, 
            validator, 
            delegate_time 
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string] // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object].validator\[string] // validator address
  4. msg\[object].amount\[string]&#x20;
  5. msg\[object].delegate\_time\[string] // time range (ms)

### return value

msg\[Promise\<string>] // hash

### example

```
// Your account must have test tokens
nodeShardInstance
.stakingDirect({msg:{
    validator:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6',
    amount:'1000000',
    delegate_time: '86400000'
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

