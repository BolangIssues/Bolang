```
extension Data {
    
    var hexString: String {
        return map { String(format: "%02hhx", $0) }.joined()
    }
    
    var decimalString: String {
        return map { String(format: "%d", $0) }.joined()
    }
    
}
```

```
let hexString = string.data(using: .ascii)!.hexString
```

```
let decimalString = string.data(using: .ascii)!.decimalString
```
