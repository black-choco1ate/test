# keyball44

以下のファームの改良版

https://github.com/takashicompany/qmk_firmware/tree/keyball

上のkeyballブランチをチェックアウトして、以下のディレクトリのソースを置き換え
qmk_firmware/keyboards/keyball/keyball44/keymaps/takashicompany/



|キー|Code(hex)|説明|
|:--|:--|:--|
|マウスボタン1|0x5DAF|主に左クリックが設定されていることが多い。|
|マウスボタン2|0x5DB0|主に右クリックが設定されていることが多い。|
|マウスボタン3|0x5DB1|OSやPCの設定に依存。|
|スクロールボタン|0x5DB2|このキーを押している際はトラックボールの入力はスクロールとして扱われる。|
|レイヤー変更しきい値増加|0x5DB2|トラックボールレイヤーを有効にするためのトラックボール必要移動量のしきい値を下げる。最小は5。|
|レイヤー変更しきい値増加|0x5DB3|トラックボールレイヤーを有効にするためのトラックボール必要移動量のしきい値を上げる。|
|マウスレイヤ解除時間増加|0x5DB4|マウスレイヤを解除する時間を増加させる|
|マウスレイヤ解除時間減少|0x5DB5|マウスレイヤを解除する時間を減少させる|


## 追加変更してある機能

1. マウスレイヤ中のLED点灯
1. マウスレイヤの解除までの時間調整キーの設定
1. マウスレイヤを解除しないキーの規定
1. スクロール方向の反転
1. レイヤ5枚化

## 注意点

残りメモリが少ないので気をつけること
