# Balance

```
nodeShardInstance
    .erc721getBalanceof(
        contractAddr,
        account
    );
```

### **parameters**

* contractAddr\[string] // 721 token contract address
* ?account\[string] // destination address

### return value

msg\[Promise\<string>]

### example

```
// 
nodeShardInstance
.erc721getBalanceof(
    '0xxxxxx'
)
.then(val=>{
    console.log(val);
})
```

