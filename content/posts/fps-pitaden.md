---
title: "FPSのピタでんがひっそり受付再開してたけど、やっぱりヤバすぎる"
date: 2022-09-04T23:00:00+09:00
---

電気代は上がっているかい?  
昨今の国際情勢のさなか、旧一電でさえも自由料金も続々と燃調費の上限撤廃が進んでいる。  
欧州はおろか資源大国の米国ですら自由化が大失敗しているのに、日本で電力自由化なんてとうてい無理筋な訳だが、そうは言っても今現在、家計負担が増大しているのはやむなきことである。

そんななか、最近まで新規受付を停止していた FPS(旧:F-Power)のピタでんがヒッソリと申込み受付を再開していたのだが、やっぱり明らかに異常な価格設定で目を引く。  
私は一身上の都合により電力会社を変えられないが、実家はピタでんにするように勧めておいた。この記事はその備忘および所感である。

私は東海地方在住なので中部エリアの料金設定で書いているが、各自読み替えてほしい。  
下記の前提は、中部電力・従量電灯 B を契約容量 60A で契約しているものとする。  
なお、自由料金で「おとくプラン」だとカテエネポイント 153P または月額料金から 153 円が割引されるが、昨今の原料高を踏まえると近いうちに規制料金(従量電灯 B)のほうが安上がりになる可能性が高いため、ここでは「おとくプラン」は捨て置くものとする。

### 500kWh まで一律の料金設定

「[ピタでん使いたい放題](https://pitaden.jp/)」は、500 kWh までは一律で \11,200 (以下、ピタでん基本料金と呼称する)が課金されることとなっている。
中部電力の基本料金相当がピタでん基本料金に内包されているものと仮定し、ピタでん基本料金を分解し中部電力と比較すると、次のような表が完成する。

|                                        |         | 中部電力 | ピタでん |
| -------------------------------------- | ------- | -------- | -------- |
| 基本料金                               |         | 1716     | 1716     |
| 従量料金                               | <120kWh | 21.04    | 18.968   |
|                                        | <300kWh | 25.51    | 18.968   |
|                                        | 300kWh< | 28.46    | 18.968   |
| 2022 年 8 月燃料費調整額               | 円/kWh  | 3.66     | 0        |
| 2022 年度再エネ賦課金                  | 円/kWh  | 3.45     | 0        |
| 2022 年 8 月 500kWh 使用した場合の料金 |         | 18079    | 11200    |

中部電力従量電灯 B との比較では、実に単月で 6879 円もの差が出ることとなる。  
一般家庭で 500kWh も使用するのは意外と大変で、大所帯でも夏冬の寒暖ピークを除き到底到達するものではないだろうが、ザックリ計算すると上記のようになる。

### 燃調費・再エネ賦課金込みでの価格設定だから驚き

> Q.燃料費調整額と再エネ賦課金は発生しますか？  
> A.(中略)  
> 「ピタでん使いたい放題」は、燃料費調整額と再エネ賦課金は発生しません（料金に含んでいます。500kWh/月を超えた場合の従量料金においても料金に含んでいます）。

上記は[ピタでん HP](https://pitaden.jp/lp01/index.html#plan) より引用。

そもそもの単価設定自体もトチ狂っているが、更におかしいのは、上記のピタでん基本料金に燃調費・再エネ賦課金がすでに含まれているということ。  
上表に示したように、燃料高もあって 2022 年 8 月の燃調費は 3.66 円/kWh となっている。また再エネ賦課金も年々値上がりしており、2022 年度は 3.45 円/kWh となっている。

すなわち、2022 年単月の従量料金を燃調費・再エネ賦課金を含めて比較すると次のようになる。

|         | 中部電力 | ピタでん |
| ------- | -------- | -------- |
| <120kWh | 28.15    | 18.968   |
| <300kWh | 32.62    | 18.968   |
| 300kWh< | 35.57    | 18.968   |

一番差が小さいところでも kWh 単価で 10 円弱、最も大きいところでは倍近く単価が違うというのだから驚きだ。
ピタでんの何がヤバいかを箇条書きで表すと、

- 中部電力パワーグリッド管内における託送料金相当額は 8.12 円/kWh である
- 再エネ賦課金 3.45 円/kWh、託送料金相当額 8.12 円/kWh の**合計 11.57 円/kWh** が削減のしようが一切ない必要経費である。
- すなわち、ピタでんは上記従量料金からこれらを差し引いた **7.398 円/kWh** で電源調達および販管費のやりくりをする必要がある。
  - 便宜上、中部電力の基本料金相当額をピタでん基本料金から差し引いているため、中部電力の基本料金相当額から接続送電サービス料金 759 円を差し引いた 957 円/月も考慮に入れる必要はあるが。
- 電力を全量 JEPX (日本卸電力取引所)から調達すると仮定する。例として、記事執筆日である2022年9月4日のシステムプライスは最安で午前 0 時 30 分付近の 17.73 円/kWh、最高値が 17 時前後の 65.80 円/kWh である。

こんなのどうやったって黒字になるわけがないじゃん。まあ実際は相対取引とか自前の発電所を駆使して頑張ってるんだろう。

さて、ここまで見た数字をもとに、2022 年 8 月におけるピタでんと中部電力の価格を比較し下のようなグラフを作成してみた。

![ピタ電](https://user-images.githubusercontent.com/47537864/188321777-5d8469bb-4a5f-4481-904c-b656c3ea03a9.jpg)

電気を 1kWh も使わなかったとしても定額課金が発生する以上、ある程度の使用量が無いと損する羽目になる。  
ここでピタでん使いたい放題が中部電力より得となる損益分岐点は 306.5kWh である。(もっとも、中部電力側の燃料費調整額により上下することに注意したい)  
燃調費を一旦考慮しないものとすれば、4~5 人家族であれば余裕でプラスにすることができるのではなかろうか。

私の実家は 4 人暮らしだが、節電とは程遠い生活のため 5 月などの一番少ない時期で 360kWh、冬場で 1000kWh くらい使用しており、どう考えてもピタでんが得になるとしか考えられないのだ。

### 500kWh 超過部分も他社より圧倒的に安いじゃん

500kWh を超えてはじめて従量課金がスタートするが、この値段も 27.50 円/kWh と馬鹿げた設定となっている。

そもそも中部電力の 300kWh 超過部分の従量料金は 28.46 円/kWh だから、kWh あたり 1 円弱安いのだ。  
電力小売自由化の問題が表面化していなかった頃、安い安いともてはやされていた「Looop でんき」ですら、kWh あたり 28.5 円だからピタでんのほうが額面通りに受け取っても 1 円安い。

しかしここにもワナが存在する。  
ピタでんの従量課金 27.50 円/kWh もまた、燃調費・再エネ賦課金を含んだ価格設定だというのだ。  
「Looop でんき」はこれらを別途課金するためそれ以上に安いこととなる。  
(さらにいえば、Looop でんきは JEPX 連動の燃料費調整単価を導入しているため実際の振れ幅はもっと酷いだろうが、本筋とは関係ないため割愛する)

### 多分自殺願望がある会社なんだろう

ピタでんを運営する FPS 株式会社は、前身を F-Power といい、かつては高圧・特別高圧で確固たる地位を築き、電力販売量においては新電力 1 位となったこともある会社である。  
早い話がエネットみたいな会社である。

金融工学などを駆使した電力調達でブイブイ言わせていたみたいだが、2021 年冬の電力需要逼迫に伴い多額のインバランス債務を負い、ホープなどの新電力大手と共倒れすることとなった。

そこを、シンガポール政府系資本が入った投資会社 GLP が事業を譲り受け、FPS として再スタートさせたものが同社である。  
なお、負債は承継せず、前身の F-Power にそっくりそのまま置いてきた模様。

親会社の懐が温かいとはいえ、F-Power 時代からそっくりそのまま事業継続は大胆すぎるわ。

### 旧 F-Power として電力供給を行っていた小売電気事業者との取引も継続しているみたい

[はなカメくん電気](https://www.kamei93.co.jp/hanakame/)という、株式会社亀井組が事業を運営する新電力が存在する。  
四国の建築会社がホッソリやっている、なんともシュールなブランド名の電力会社だ。だが、電力供給は全国区である。

残念ながら現在は新規受付を停止しているが、ここもピタでんに負けず劣らず安売り勝負の会社である。  
はなカメくん電気においては、かつては F-Power が電気を供給していたが、事業承継に伴いそっくりそのまま FPS に契約が承継されたみたいだ。

本当に負債だけを切り離して再スタートということだが、F-Power の二の舞いにならないことを祈るばかりである。

### 最近の新電力は料金体系の改悪が続いている

新電力事情をチェックしていて一番ヒドいな、と思ったのは、HIS が光通信系に売却した [HTB エナジー](https://htb-energy.com/)である。  
光通信系の電力会社といえば、グランデータやハルエネ等、知る人ぞ知る会社ばかりである。

光通信系の会社は燃料費調整制度に加えて、電源調達費という独自の制度を加えて調達費用の増加に係る経営負担を軽減している。  
これは一昔前に流行った市場連動型の電気料金プランに似通ったもので、JEPX サイト内スホ゜ット市場取り引き結果のエリアプライス 1 ヵ月単純平均を電気代に転嫁するという仕組みだ。  
HP の記載もツッコミどころだらけだが、同社は自社に批判的な言論を掲載するインターネットユーザーに対し法的措置をチラつかせていたため、私はこれ以上ここで触れないことにする。

話が逸れたが、HIS は現在かなりの経営危機に陥っているため HTB や電力子会社を切り売りして立て直しを図っている状況であり、その一環として HTB エナジーは光通信の連結子会社である株式会社 HBD へと事業譲渡された。  
そして HBD 体制下で最初に行われたことといえば、HTB エナジーへの上記電源調達費制度の導入である。  
HTB エナジーは 2021 年 10 月期で 370 億円の売上に対し 100 億円の事業赤字となっているため、そのテコ入れとしては効果てきめんの方策ではあるが、利用者からしたらタマったものではない。

そのほか、先に述べた「Looop でんき」や「楽天でんき」など、新規受付一時停止のちに電気料金プラン自体を値上げするような事業者も全く珍しくはない。

こういったサービス内容の急な方針転換は自由化当初とは事業環境がかけ離れ過ぎたために起こっている。  
「エルピオでんき」のように事業継続自体を断念する会社が出ている以上、当初の自由化趣旨と照らし合わせて現状、電力自由化は最悪中の最悪で大失敗と言っていいだろう。