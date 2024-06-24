---
title: "Lenovo IdeaPad Pro 5i Gen 9(カスタマイズモデル)買った"
date: 2024-06-09T00:00:00+09:00
description: "lenovo"
---

\* この記事はアフィリエイトを使用していません

# 新しいノート PC が欲しい

主に実家に帰ったとき、出先、旅行先での作業に使いたい。  
今持っているノート PC が 7 年前に大学入学したときに買ったもので、i7 7600U を搭載しているのだがスペックが低すぎて厳しい。  
(Windows が重すぎて使い物にならないので基本的に Ubuntu を使ってる)

したがって、新しく新調することにした。

## Windows 12 は？

Windows 12 が出るとかなんとか、みたいな話題もあるけど、よほど型落ちのモデルを買わない限りはアプデはできると思う。  
Windows7→10、Windows10→11 みたいに無料アップデートが降ってくるかは分からないけど、まあ最悪ライセンスは consogame とかで買えばいいと思う。

## 要件

PC を買うにあたっての主な要件は次の通り

- グラボは不要（StableDiffusion を使いたいのでついていても構わない）
- バッテリー持ち重視（JEITA Ver3.0 アイドル時で最低 17,18 時間くらいは欲しい）
- メモリは 32GB 必須
- 画面解像度は WQHD 以上あるとよい
- ストレージは M.2 SSD で 1TB あるとよい(512GB でも別にいいけど)
- 給電形式は USB type-C がいい
- キーボード配列がウンコじゃないものがいい
- 本体価格は 20 万円以内(副業の作業のためだけに買う予定なので経費計上したい。一括償却資産として減価償却したい)

主にプログラムをゴリゴリ書くのと写真の RAW 現像に使うのでメモリは多ければ多いほど嬉しい。  
基本的に家のデスクトップ PC がつけっぱなしなので、スペック不足の作業はリモートデスクトップで行えば良いかなと思っている（今の激古ノート PC は全てリモートデスクトップで完結している）

32GB メモリ搭載となると一気に選択肢が減る。

## 候補にあがった PC

### Zenbook 14 OLED UX3405MA-U9321W

[https://jp.store.asus.com/store/asusjp/ja_JP/list/categoryID.5296702300](https://jp.store.asus.com/store/asusjp/ja_JP/list/categoryID.5296702300)

最初に買おうと思ったやつ。見た目がかっこいい。
価格も 199,800 円で、上限ギリギリでかなりいい。  
難点は、マジで一生在庫が無いことくらい。  
公式オンラインショップでのみ取り扱いがあるものの常に品切れ、再入荷しても 10 分くらいで売り切れるらしいので争奪戦は必至。  
また、見た目は大変かっこいいが、薄型化のトレードオフで CPU がフルパフォーマンスを発揮できない？ようで、Passmark のスコアなどは他の Core Ultra 9 185H 搭載 PC より少し低いらしい（要出典）。

主なスペック:

- CPU: Core Ultra 9 185H
- メモリ: LPDDR5X-7467 32GB
- ストレージ: M.2 SSD 1TB
- 画面: 2880x1800 / OLED / 120Hz
- バッテリー: JEITA3.0 で動画再生 11.4 時間、アイドル 20 時間（75Wh あるらしい）

### ASUS Vivobook S 15 5507QA Copilot+ PC

[https://jp.store.asus.com/store/asusjp/ja_JP/pd/productID.5889598800](https://jp.store.asus.com/store/asusjp/ja_JP/pd/productID.5889598800)

Zenbook いいなーと思って ASUS ストア見てたら見つけたやつ。6 月 18 日発売予定。  
定価は 249,800 円だが、10%オフクーポンがあるので 224,820 円で予算オーバーするが、まあ仕方ない。  
CPU 以外のスペック差はほぼなさそう。

見送り理由としては次の通り。

- CPU が Snapdragon X Elite で詳しい情報がない。多分 ARM アーキテクチャなので x64 向けのソフトがちゃんと動くのか心配（アンチチートなどカーネルレベルで動くソフトは動かない？）
- キーボード配列が糞: 無理やりテンキー搭載したせいでだいぶキーピッチが厳しそう。
- バッテリー持ちに関する情報がない: 今のところ Snapdragon X Elite に関する情報が少なすぎてどこにも掲載がない。

逆に良い点：

- microSD リーダーが標準搭載: RAW 現像するときのデータ取り込みは microSD 経由なのでこれはありがたい。
- USB 端子がクソ多い: Zenbook は Thunderbolt USB Type-C x 2、USB 3.2 Type-A x1 の計 3 ポート。対するこちらは USB 4 Type-C x 2,USB 3.2 Type-A x2 の計 4 つ。デバイスは基本無線接続で揃えているので、そこまで USB 端子を使う機会は多くないが、あるに越したことはないよね。
- メモリ帯域幅が若干（135GB/s vs 120GB/s）高性能： 誤差レベルだけど。

主なスペック:

- CPU: Snapdragon X Elite X1E-78-100
- メモリ: LPDDR5X-8448 32GB
- ストレージ: M.2 SSD 1TB
- 画面: 2880x1620 / OLED / 120Hz
- バッテリー: 謎(70Wh なので容量自体は Zenbook より小さい。最大消費電力も 90W で Zenbook の 60W よりでかいので、持ちは悪そう)

### ASUS Zenbook 14 OLED UX3405MA-U5165W

[https://jp.store.asus.com/store/asusjp/ja_JP/pd/productID.5856599100/varProductID.5859319600/categoryID.5296702300](https://jp.store.asus.com/store/asusjp/ja_JP/pd/productID.5856599100/varProductID.5859319600/categoryID.5296702300)

第一候補の Zenbook の下位モデル。スペックはしょぼい代わりに 6 万くらい安い。  
これだけ常に在庫があるので、入荷待ちに疲れたらもうこれでもいいかも。

ただし、CPU だけでなくメモリ、ストレージも半減、画面解像度も低く、リフレッシュレートは 60Hz しかない。  
安物買いの...とまでは言わないが、しょぼい。買ってしばらくは後悔しそう。

主なスペック：

- CPU: Core Ultra 5 125H
- メモリ: LPDDR5X-7467 16GB
- ストレージ: M.2 SSD 512GB
- 画面: 1920x1200 / OLED / 60Hz
- バッテリー: 上位モデルと一緒

### Macbook Pro (14 インチモデル)

[https://www.apple.com/jp/shop/buy-mac/macbook-pro](https://www.apple.com/jp/shop/buy-mac/macbook-pro)

クリエイティブ用途といえば Mac も良いよね、ということで一応検討したが、即選択肢から外れた。

- 25 万のモデルでもメモリが 8GB しかない: Windows とはメモリ使用に対する考え方が違うのかもしれないが、肌感覚的には許せない。

## 結局 Lenovo IdeaPad を買った

[https://www.lenovo.com/jp/ja/p/laptops/ideapad/ideapad-5/lenovo-ideapad-pro-5i-gen-9-(14-inch-intel)/83d2cto1wwjp2](<https://www.lenovo.com/jp/ja/p/laptops/ideapad/ideapad-5/lenovo-ideapad-pro-5i-gen-9-(14-inch-intel)/83d2cto1wwjp2>)

タイトルに戻るが、結局 Lenovo の IdeaPad Pro 5i Gen 9(カスタマイズモデル)を買った。  
Zenbook 14 OLED UX3405MA と Vivobook S 15 5507QA のいいとこ取りという感じ。  
アップグレードできる項目は Office 以外全て選択し、次のような内容で注文。

- CPU: インテル ® Core™ Ultra 9 プロセッサー 185H (E コア 最大 3.80 GHz P コア 最大 5.10 GHz) **selected upgrade**
- オンボードメモリー: 32 GB LPDDR5X-7467MHz (オンボード) **selected upgrade**
- ストレージ: 1 TB SSD M.2 2242 PCIe-NVMe Gen4 TLC **selected upgrade**
- ディスプレイ: 14" 2.8K OLED(有機 EL ディスプレイ) (2880 x 1800) 光沢あり, マルチタッチ非対応, HDR500, 100%DCI-P3, 400 nit, 120Hz **selected upgrade**

\*Office は [consogame](https://consogame.com/software/office/microsoft-office-2021-professional) で買う予定なのでいらない。

ストレージは増設スロットが 1 つ余っているようなので、別にどちらでも良いと思うが、1 万円しか変わらないので。  
上記のスペックで、¥189,498 であった。Zenbook より丁度 1 万円安い。  
それでいて、4 in 1 カードスロットも付いていて、USB 入力ポートも多い。  
注文争奪戦に参加する必要もない（納期は長いけど）。  
即決でした。

### 後悔

で、この記事をここまで書いている段階ではまだ届いていないんだが、すでに 1 つ後悔ポイント。
注文後に 2ch を見ていたら書いてあったんだが、レノボストアは[楽天リーベイツ](https://www.rebates.jp/)経由で注文すると平常時で 10%ポイント還元があるらしい。

それでいて、丁度注文に前後して上記ポイント還元が 20%に増額されていたらしいので、実質 4 万円くらいのポイントが機会損失に消えていった。  
このポイントバックの帳簿上の取り扱いがどうなるのかは分からない(雑収入になるのかな？)が、なんかすごく損した気分。

### 届くまで

ストア上における今回の PC の納期情報は「最短 1-2 週間程度(ご決済日起算)で出荷予定」であった。
時系列順でテーブルに示す。

| タイムスタンプ         | 内容                                                            |
| ---------------------- | --------------------------------------------------------------- |
| 2024/6/2(日) AM 3:10   | 注文。自動返信メール受領                                        |
| 2024/6/3(月) AM 10:23  | 領収証がメールで届いた                                          |
| 2024/6/5(水) PM 10:30  | 出荷メール受領。日通 NEC ロジの追跡番号発行                     |
| 2024/6/7(金) AM 3:52   | CEVA Logistics で荷物の追跡が可能になる                         |
| 2024/6/7(金) AM 11:51  | (CEVA) Event: Pickup CN- Cn                                     |
| 2024/6/7(金) AM 11:51  | (CEVA) Event: Documents Received HKG - Hong Kong                |
| 2024/6/9(日) AM 00:50  | (CEVA) Event: Freight Received HKG - Hong Kong                  |
| 2024/6/9(日) AM 00:50  | (CEVA) Event: Documents Received At Destination HKG - Hong Kong |
| 2024/6/9(日) PM 23:59  | (CEVA) Event: Estimated Delivery Date JPTYO - Tokyo             |
| 2024/6/10(月) AM 8:10  | (CEVA) Event: Pickup Request HKG - Hong Kong                    |
| 2024/6/10(月) AM 8:10  | (CEVA) Event: Requiested Ship Date HKG - Hong Kong              |
| 2024/6/10(月) PM 16:55 | (CEVA) Event: Estimated Delivery Date HKG - Hong Kong           |
| 2024/6/10(月) PM 23:39 | (CEVA) Event: On-Hand NRT - Tokyo Narita                        |
| 2024/6/10(月) PM 23:39 | (CEVA) Event: On-Hand NRT - Narita                              |
| 2024/6/11(火) AM 08:49 | (CEVA) Event: Cleared Customs NRT - Tokyo Narita                |
| 2024/6/11(火) AM 09:09 | (CEVA) Event: Out For Delivery NRT - Tokyo Narita               |
| 2024/6/11(火) PM 09:30 | (CEVA) Event: Docs Turned Over To Broker NRT - Tokyo Narita     |
| 2024/6/11(火) PM 15:00 | (CEVA) Event: Delivered NRT - Tokyo Narita                      |
| 2024/6/11(火) PM 16:19 | (日通 NEC) 国内配送準備                                         |
| 2024/6/12(水) -        | (日通 NEC) 配送センター出荷済み（以降、ヤマト運輸で追跡可       |
| 2024/6/13(木) AM 10:35 | (日通 NEC) お届け先配送                                         |

6/9 時点で 6/10 の予定まで書かれているので、どの便に載せられて日本に来るかなどは早い段階で確定している様子。

![chrome_20240609_182715](https://gist.github.com/assets/47537864/d8ff3f1e-658a-4b48-8ebf-3049913f7d08)

この時点での日通 NEC ロジの追跡情報は上の通りで、海外における追跡情報なし。  
到着予定日時は 6/15。NEC ロジは CEVA から受け取った荷を国内のラストワンマイル業者に中継する役割らしいが、土日は発送業務をしていないらしいので、休日を挟むと到着日が伸びるらしい（未確認）。

![image](https://gist.github.com/assets/47537864/a076620f-820d-408a-921b-85964fd4fc3a)

また、CEVA Logistics の追跡ページ下の方（Routing のところ）に「Master Waybill No.」が記載されており、この数字を航空会社に問い合わせることでより詳細のトラッキングが可能。  
今回の航空会社はチャイナエアライン(VESSEL / VOYAGE をググれば特定可能)だったので、China Airlines Cargo Services のページで問い合わせた結果がこれ。

香港から台北を経由し、台北から成田空港へ送られるみたい。予定値/実績値がそれぞれ表示されるのでわかりやすい。

今回は香港 → 台湾、台湾 → 日本で各 1 営業日。日本国内では約 3 営業日配送に要した。  
最初に日通 NEC の追跡ページに表示される到着予想日と同じか、1,2 営業日短縮される程度で届く模様。

## 機種レビュー

### 外観

#### 表面・裏面

![IMG_20240624_120516](https://gist.github.com/assets/47537864/88897b97-f7a6-47b2-b5dd-8eca7f3f42f7)

飾らないデザインなので無骨なのが好きな人にはよいかも。

#### 側面

![IMG_20240624_121307](https://gist.github.com/assets/47537864/f1f8ebd7-6a3c-4a99-8e90-4da7e2dbe44b)

左側面に USB type-C x2、HDMI ポート。右側面は USB type-A x2、SD カードリーダ、イヤホンジャック、各 LED ランプ。  
USB ポートが充実しているのがとても良い。

#### 見開き

![IMG_20240624_120509_1](https://gist.github.com/assets/47537864/9380c072-fce2-4ccc-8261-cf356117427f)

モニタの発色は有機 EL だけありとても鮮やか。120Hz 駆動にも対応（デフォルトは 60Hz）  
ベゼルは 2024 年にしては少し太め。

### スペック

#### Cinebench

![Cinebench_tRydwf6E1x](https://gist.github.com/assets/47537864/af9cf9cd-ec11-43b8-8899-b3a270d7cc89)

#### CrystalDiskMark

![DiskMark64_oP6VHw9UYG](https://gist.github.com/assets/47537864/e880bbc6-7ecf-4862-abd9-eadccd53c7b2)

使用されている SSD は MZVL81T0HELB-00BL2(SAMSUNG)

総じて処理はめちゃくちゃ早い。メインで使っている PC（Ryzen 9 5900X）と普段使いではほとんど遜色なし。

ゲームに関しては、オンボードではあるがかなり健闘している。  
原神は最高設定で 60fps 張り付き。Apex は画面解像度を FHD に下げたうえで設定を最低設定にすれば 60fps は出る。
14 インチなので画質が悪くても気にならないので、普通に許容範囲。

高負荷時にも、発熱もキーボードおよびタッチパッドとその周辺は全くない。（Fn キーより上あたりはかなり熱くなる）  
ただし PC 底面は普通に熱くなるので、高負荷時に膝置きして操作するのはちょっとツラいかも。

これから買うなら Copilot Ready の Snapdragon X Elite 搭載 PC がいいぞ！っていう YouTube Shorts が大量に流れてくるけど、よく使うソフトが ARM ネイティブで動かない場合は Core Ultra 搭載 PC で十分だと思う。
一応、当機種も Copilot ボタンついてます。
