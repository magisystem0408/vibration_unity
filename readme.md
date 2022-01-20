# Unityでバイブを使用するためのモジュール(ios/android用)
## 使い方
1. vibration_module.unitypackageをインポート
2. 下記を使いたいところに記述

```javascript
Vibration.SetVibrationNumber(1003); //どのバイブ番号を使用するか

Vibration.Play(); //バイブが発動する
```

## バイブ番号参考
>> https://qiita.com/flankids/items/ae607c5fe8917f960cba