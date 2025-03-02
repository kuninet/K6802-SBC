# MC6802 MPUを使ったシングルボードコンピューター

## 概要
* MC6802 MPUを使ったシングルボードコンピューターです。
  * MC6850 ACIA経由でシリアルターミナル(TeraTermなど)とつながります。(SBC6800と互換)
  * 64kBのメモリー領域にRAMをわりあてるため128kB SRAMを使用しています。(半分の64kBは無駄にしています)
    * 半田ジャンパによりメモリー領域を調整可能です。(外部ボードのRAM用にディセーブル or ROM領域へ割り当て)
  * ROMは32kBタイプですが、ジャンパで2つの領域に分けて使用できます。
* SBC6800のソフトを使えることを目指しました。

## ブラウザで回路図などを確認
* Kicadcanvas
  * https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fkuninet%2FK6802-SBC%2Ftree%2Fmain%2FKiCad

## 参考
* 以下の回路を参考にさせていただきました。ありがとうございます。
  * [SBC6800 ルーズキット (電脳伝説さん)](https://vintagechips.wordpress.com/2017/12/05/sbc6800%E3%83%AB%E3%83%BC%E3%82%BA%E3%82%AD%E3%83%83%E3%83%88/)
  * [SBC-IO Rev02 (Tomi9さん)](https://sbc738827564.wordpress.com/2018/08/11/sbc-io-rev02/)
  * [SBC8080 SUBルーズキット (電脳伝説さん)](https://vintagechips.wordpress.com/2018/06/23/sbc8080-sub%E3%83%AB%E3%83%BC%E3%82%BA%E3%82%AD%E3%83%83%E3%83%88/)
  * [SBC6802 (ryu10さん)](https://github.com/ryu10/sbc6802)

