# Haskell学習を始めるまで

## ターミナルでGHCの対話モードを使う
### 対話モードの始め方
ターミナルで`ghci`と入力してEnterキーを押す。

### 対話モードの終わり方
`:q`または`:quit`とタイプしてEnterキーを押す。

### 対話モード上ででスクリプトを読み込む
myfunctions.hsに関数を定義する

myfunctions.hsがあるフォルダでGHCiを起動

GHCi上で、`:l myfunctions`→GHCiに関数をロード

#### スクリプトの変更を反映
`:l myfunctions`でロードし直すか、`:r`で現在のスクリプトをリロード