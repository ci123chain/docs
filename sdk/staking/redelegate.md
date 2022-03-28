# ReDelegate

```
nodeShardInstance
    .redelegate({
        nonce,
        gas,
        msg:{ 
            src_validator, 
            dst_validator, 
            record_id
        }
    });
```

### **parameters**

* value\[object] (parameters)
  1. ?nonce\[string] // You can pass no arguments
  2. ?gas\[string] // You can pass no arguments
  3. msg\[object].src\_validator\[string] // address of the original mortgagor
  4. msg\[object].dst\_validator\[string] // new mortgagor address
  5. msg\[object].record\_id\[string] // original mortgage ID

### return value

msg\[Promise\<string>] // hash

### example

```
// Your account must have test tokens
nodeShardInstance
.redelegate({msg:{
    src_validator:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6',
    dst_validator:'0x8Cf5002c2Ba3b72027fd9E15e48314BD770254c6',
    record_id: '1'
},gas:'',nonce:''})
.then(val=>{
    console.log(val);
})
```

