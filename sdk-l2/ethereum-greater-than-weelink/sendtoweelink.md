# SendToWeelink

```
nodeShardInstance
    .ethAcrossChainTransfer(
        acrossChainContractAddr,
        tokenContractAddr,
        destination,
        amount
    );
```

### **parameters**

* acrossChainContractAddr\[string]  // across Chain Contract Address
* tokenContractAddr\[string] // token contract address
* destination\[string] // destination address
* amount\[string] // The number does not need to be multiplied by 1000000000000000000

### return value

msg\[Promise\<object>]（Transaction object）

### example

```
// Your account must have test tokens
nodeShardInstance
.ethAcrossChainTransfer(
    '0xxxxxx',
    '0xxxxxx',
    '0xxxxxx',
    '0.01'
)
.then(val=>{
    console.log(val);
})
```

