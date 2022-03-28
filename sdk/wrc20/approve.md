# Approve

```
nodeShardInstance
    .erc20Approve(
        token,
        destination,
        amount
    );
```

### **parameters**

* token\[string] // token contract address
* destination\[string] // destination address
* amount\[string] //

### return value

msg\[Promise\<object>]（Transaction object）

### example

```
// Your account must have test tokens
nodeShardInstance
.erc20Approve(
    '0xxxxxx',
    '0xxxxxx',
    '0.01'
)
.then(val=>{
    console.log(val);
})
```

