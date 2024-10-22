# \<harmony/> ビルドガイド

## 必須パーツの確認
- 基板
- スイッチプレート
- バックパネル
  - 各1枚ずつ、必ず入っています。
- Waveshare RP2040-Zero
  - 1つ必要です。
- スペーサー
  - M3×7mmが4本、M3×3.5mmが4本、必ず入っています。
- ネジ
  - M3×4 極低頭が4本、M3×3 ナベが10本、M3×4 飾りが2本、必ず入っています。
  - 飾りネジは低頭、バインド、傘ネジ、ウエハ、黒染め、などのよさげなネジです。
- ダイオード
  - 1N4148シリーズ 69個必要です。
  - 表面実装型、リード型どちらでも使用できます。混合も可能です。
- スタビライザー
  - 2u用 2個必要です。
## オプションパーツの確認
- Kailh MX互換ソケット ～69個
  - スイッチを交換したい場合に必要になります。
  - North Facingでの実装になります。
  - スイッチをはんだづけする場合は不要です。
- スルーホールソケット ～138個
  - Mill-Max、Holtite等を想定しています。
  - North FacingでのHotswapに問題がある場合使用します。
  - スイッチをはんだづけする場合は不要です。

## ざっくり組み立て
基板のすべてのパーツを実装します。  
MCUは基板表側にのせ、端子やボタンは使用時下向きになる向きに実装します。  
基板の表面の六角形の表示に合わせ、3.5mmスペーサーをねじ止めします。  
スイッチプレートを乗せてスペーサーとねじ止めします。  
この状態でスイッチを実装し、基板の六角形の穴にスペーサーを挿入します。  
スイッチプレート表側からネジ止めします。このとき、使用時手前側の2本は飾りネジを使用します。
基板裏にバックパネルを乗せます。  
バックパネルの穴に合わせ、ゴム足を乗せ、極低頭ネジで固定します。