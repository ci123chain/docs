# CreateValidator

```
nodeShardInstance
      .prestakingCreateValidatorDirect({
            nonce,
            gas,
            msg:{ 
                  public_key,
                  amount,
                  min_self_delegation,
                  rate,
                  max_rate,
                  max_change_rate,
                  moniker,
                  identity,
                  website,
                  security_contact,
                  details,
                  delegate_time,
            }
      });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string] // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object].public\_key\[string] // public key nodes
  4. msg\[object].amount\[string] &#x20;
  5. msg\[object].min\_self\_delegation\[string] // minimum mortgage
  6. msg\[object].rate\[string] // commission rate; 0-100.
  7. msg\[object].max\_rate\[string] // maximum rate of commission
  8. msg\[object].max\_change\_rate\[string] // maximum daily percentage change
  9. msg\[object].moniker\[string] // the name of the node
  10. msg\[object].identity\[string] //&#x20;
  11. msg\[object].website\[string] // website
  12. msg\[object].security\_contact\[string] //&#x20;
  13. msg\[object].details\[string] // validator address
  14. msg\[object].delegate\_time\[string] // ms

### return value

msg\[Promise\<string>] // hash

### example

```
// Your account must have test tokens
nodeShardInstance
.stakingDirect({msg:{
    xxx:xxx
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

