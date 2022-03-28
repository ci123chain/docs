# Transfer



```
nodeShardInstance
    .chainTransfer(to,amount);
```

### **parameters**

* to\[string] (The target address)
* amount\[number]（The number does not need to be multiplied by 1000000000000000000）

### return value

msg\[Promise\<object>]（Transaction object）

### example

```
// Your account must have test tokens
nodeShardInstance
.chainTransfer('0x3f43e75aaba2c2fd6e227c10c6e7dc125a93de3c', 0.01)
.then(val=>{
    console.log(val);
})
```

