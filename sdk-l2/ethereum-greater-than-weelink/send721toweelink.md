# Send721ToWeelink

```
nodeShardInstance
    .ethAcrossChain721Transfer(
        acrossChainContractAddr,
        tokenContractAddr,
        destination,
        tokenId
    );
```

### **parameters**

* acrossChainContractAddr\[string]  // across Chain Contract Address
* tokenContractAddr\[string] // token contract address
* destination\[string] // destination address
* tokenId\[string] // ntf id

### return value

msg\[Promise\<object>]（Transaction object）

### example

```
// Your account must have test tokens
nodeShardInstance
.ethAcrossChain721Transfer(
    '0xxxxxx',
    '0xxxxxx',
    '0xxxxxx',
    '1'
)
.then(val=>{
    console.log(val);
})
```

