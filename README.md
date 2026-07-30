# -Project-PiSheet
Project PiSheet は、(cmでない)通常のRaspberry Pi 5をベースとした超薄型・一体型コンピュータを開発するプロジェクトです。

一般的なRaspberry Piでは、基板上にUSBポートやLANポート、HDMIコネクタなどの大型部品が実装されているため、本体の厚さはこれらのコネクタによって決まります。Project PiSheetでは、専用基盤や装置の作製をなるべくせずに、携帯性とデザイン性を両立した新しいRaspberry Piの形を目指します。

⸻
従来品との比較

例:PiBrick

!["FabSceneより引用"]("https://github.com/Akihide0517/-Project-PiSheet/blob/main/images/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202026-07-31%206.06.52.png?raw=true")

* 肉薄するほどの薄型化
    * 限界まで本体カバーを薄く、極小パーツの選定をすることで本体厚みをPiBrickと比較しても＋４mm程度のレベルまで肉薄（LANやUSBを摘出すればより薄くなります）。
    * ポケットに入るサイズ。
* Raspberry Pi 5の資産を維持
    * 超薄型化を図りながらも不必要になったらRaspberry Pi 5を取り出して資産をそのまま活用できます。余ったpi5の活用にもOK。
* 特殊部品の排除
    * 新たなpcb基盤を作製したり、産業用部品を用いずに、安価かつ比較的手軽に作製できます（その代わり一部機能を追加するには半田付けが必要）。
    * 基本モデル完成後もそこそこの空間が余るので個人で追加機能を追加可能。

 ⸻
 なお、本プロジェクトは試作段階ですので細かい配線解説などはしておりませんのでご注意ください。
 部品やケースの3Dモデルなどは共有しています。

 ⸻
使用する部品
* 基本部品
    * m5stack CardKB2
    * SupTronics Technologies X1201
    * raspberry pi 公式リテールクーラー
    * raspberry pi 5 model B+
    * 適切な電線とジャンパ線
    * GROVEケーブル
    * データ通信可能なUSB-Cケーブル
    * 薄型HDMI to micro HDMI ケーブル（フラットタイプ）
    * タクトスイッチ
    * Battery Space Liポリマーセル 3.7V 2000mAh 7.4Wh(PL-605060-2C) 2つ分
    * raspberry pi Display 4 inch 720*720 MIPI DSI TFT LCD Touch Screen with HDMI Driver Boad
    * ３Dプリンターで作成したケース
