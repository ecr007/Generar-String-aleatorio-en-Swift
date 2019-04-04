# Generar-String-aleatorio-en-Swift

```swift
public func randomString(length:Int) -> String {
		let chars:String = "0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ"
		return String((0..<length).map{ _ in chars.randomElement()! })
}
```
