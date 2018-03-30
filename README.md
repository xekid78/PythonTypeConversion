# PythonTypeConversion
文字列と数値の型変換

## 処理
`String()`クラスを使って文字列や数値の型変換をします。

## コード
```
print("** ケース1 **")
num1 = 3.15
print(num1)
print(int(num1))
print()

print("** ケース２ **")
num2 = 5
print(num2)
print(float(num2))
print()

print("** ケース３ **")
text = "123"
print(text)
print(int(text) * 100)
print(float(text))
```

## 出力結果  
```
** ケース1 **
3.15
3

** ケース２ **
5
5.0

** ケース３ **
123
12300
123.0
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Python 3.6.4 |
