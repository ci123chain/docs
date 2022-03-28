# GetApproved

```
nodeShardInstance
    .erc721Approve(
        token,
        destination,
        tokenId
    );
```

### **parameters**

* token\[string] // token contract address
* destination\[string] // destination address
* tokenId\[string] // ntf id

### return value

msg\[Promise\<object>]（Transaction object）

### example

```
// Your account must have test tokens
nodeShardInstance
.erc721Approve(
    '0xxxxxx',
    '0xxxxxx',
    '1'
)
.then(val=>{
    console.log(val);
})
```

