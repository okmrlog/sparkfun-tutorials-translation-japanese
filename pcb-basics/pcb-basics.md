# PCBの基本

## 翻訳について(About this translation)

これはsparkfunにて公開されている記事「PCB Basics」の日本語訳です。
この翻訳を元記事のライセンスと同じライセンス(CC BY-SA 4.0)で配布します。

This is a Japanese translation of the sparkfun released article "PCB Basics". We distribute this translation under the same license as the original (CC BY-SA 4.0).

翻訳元(The Source)：[PCB Basics](https://learn.sparkfun.com/tutorials/pcb-basics)

翻訳元(ミラー)(The Source(Mirror))：[PCB Basics](https://web.archive.org/web/20200927114029/https://learn.sparkfun.com/tutorials/pcb-basics)

ライセンス(License)：[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

------

## 概観(Overview)

One of the key concepts in electronics is the printed circuit board or PCB. It's so fundamental that people often forget to explain what a PCB is. This tutorial will breakdown what makes up a PCB and some of the common terms used in the PCB world.

電子工学において鍵となる概念の1つは、the printed circuit board もしくはPCBです。それはとても基本的なものです。人々はしばしば忘れます。PCBとはなんであるかという説明をすることを。このチュートリアルは説明します。何がPCBを作り上げるか、そしてPCBの世界で使われている共通用語のうちのいくつかを。

![PCBの例](https://cdn.sparkfun.com/assets/9/b/4/6/1/520a9c35757b7ff0062f49b5.jpg)

Over the next few pages, we'll discuss the composition of a printed circuit board, cover some terminology, a look at methods of assembly, and discuss briefly the design process behind creating a new PCB.

次の数ページにわたって私たちは議論します。printed circuit boardの構造を。そこでは網羅します。いくつかの専門用語を。ちょっと見ます。部品の組み立ての方法を。そして簡単に議論します。新しいPCBを作る際のデザインの過程を。

### おすすめの読書(Suggested Reading)

Before you get started you may want to read up on some concepts we build upon in this tutorial:

あなたが読み始める状態にする前に、あなたは十分に知りたいと思うかもしれません。我々がこのチュートリアルで前提としている以下のようないくつかの概念について。

* [電気って何?(What is Electricity?)](https://learn.sparkfun.com/tutorials/what-is-electricity)
* [回路って何?(What is a Circuit?)](https://learn.sparkfun.com/tutorials/what-is-a-circuit)
* [電圧、電流、抵抗、そしてオームの法則(Voltage, Current, Resistance, and Ohm's Law)](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law)
* [接続端子の基本(Connector Basics)](https://learn.sparkfun.com/tutorials/connector-basics)
* [はんだ 101 - PTH](https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering)
* 信号(Signals)

### 翻訳(Translations)

Minh Tuấn was kind enough to translate this tutorial to Vietnamese. You can view the translation here.

Minh Tuấnは親切にもこのチュートリアルをベトナム語に翻訳してくれました。あなたは[ここ(リンク切れ)](http://vidieukhien.net/threads/23/)から翻訳を見ることができます。

## PCBとは何か？(What's a PCB?)

Printed circuit board is the most common name but may also be called "printed wiring boards" or "printed wiring cards". Before the advent of the PCB circuits were constructed through a laborious process of point-to-point wiring. This led to frequent failures at wire junctions and short circuits when wire insulation began to age and crack.

プリント回路板(printed circuit board)は最もよく使われる名前です。しかしまた呼ばれています。"プリント配線板(printed wiring boards)"または"プリント配線カード(printed wiring cards)"と。PCBの出現の前、回路は構築されていました。空中配線(point-to-point wiring)という骨の折れる過程を通して。このことは頻繁な失敗につながりました。配線の交差とショートした回路の部分で。配線の絶縁体が劣化と崩壊を始めたとき。

(訳者注: 以下は空中配線の例)

![空中配線の例](https://cdn.sparkfun.com/assets/1/3/b/5/8/50cba0dcce395fb716000000.jpg)

courtesy Wikipedia user Wikinaut <-

Wikipedia user Wikinaut のご厚意による。
