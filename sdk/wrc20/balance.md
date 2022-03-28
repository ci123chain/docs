# Balance

```
nodeShardInstance
    .erc20getBalanceof(
        contractAddr,
        account
    );
```

### **parameters**

* contractAddr\[string] // erc20 token contract address
* ?account\[string] // destination address

### return value

msg\[Promise\<object>]（Transaction object）

### example

```
// 
nodeShardInstance
.erc20getBalanceof(
    '0xxxxxx'
)
.then(val=>{
    console.log(val);
})
```

