Z8S180-57Qは、＠Gazelle8087さんによって開発され、Z8S180が動作するSBCです。<br>
そのSBC上で動くCP/M-80 Ver2.2を公開いたします。<br>
<br>
このCP/Mのオリジナルは、@hanyazouさんが作成し、@S_Okueさんが作成したSuperMEZ80<br>
上で動いていました。その後、@hanyazouさんは独自のメザニンボードを開発しておられ、<br>
CP/M-80 Ver3.0も移植されておられます。<br>
<br>
今回公開するのは、@hanyazouさんのCP/M-80 Ver2.2をZ8S180-57Qへ移植したものです。<br>
ソースのコンパイルは、マイクロチップ社の「MPLAB® X Integrated Development Environment (IDE)」<br>
で行っております。（MPLAB X IDE v6.10）コンパイラは、XC8を使用しています。<br>
<br>
https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide<br>
<br>
Z80のアセンブラは、Macro Assembler AS V1.42を使用しています。<br>
http://john.ccac.rwth-aachen.de:8000/as/<br>
<br>
FatFsはR0.15を使用しています。<br>
＜FatFs - Generic FAT Filesystem Module＞<br>
http://elm-chan.org/fsw/ff/00index_e.html<br>
<br>
SDカード上のCP/Mイメージファイルの作成は、CpmtoolsGUIを利用しています。<br>
<br>
＜CpmtoolsGUI - neko Java Home Page＞<br>
http://star.gmobb.jp/koji/cgi/wiki.cgi?page=CpmtoolsGUI<br>
<br>
また、IPL, BOOT, BIOS等の修正で、毎回イメージファイルを作るのは面倒なので、<br>
バイナリーエディタ「xedit」を利用しています。ファイルをバイナリレベルで修正<br>
出来るので便利です。<br>
<br>
https://janus.blog.ss-blog.jp/2016-06-17<br>
<br>
（オリジナルのリンクが切れているようです）<br>
フリーソフト１００からもダウンロードできます。<br>
https://freesoft-100.com/pasokon/editor_binary.html<br>
<br>
<br>
＜＠Gazelle8087さんのソース＞<br>
https://drive.google.com/drive/folders/1XKZk0CoEiwR5hFmJEGabjisRzEqCsnz1<br>
<br>
＜＠hanyazouさんのソース＞<br>
https://github.com/hanyazou/SuperMEZ80/tree/mez80ram-cpm<br>
<br>
＜参考＞<br>
・EMUZ80<br>
EUMZ80はZ80CPUとPIC18F47Q43のDIP40ピンIC2つで構成されるシンプルなコンピュータです。<br>
<br>
＜電脳伝説 - EMUZ80が完成＞  <br>
https://vintagechips.wordpress.com/2022/03/05/emuz80_reference  <br>
＜EMUZ80専用プリント基板 - オレンジピコショップ＞  <br>
https://store.shopping.yahoo.co.jp/orangepicoshop/pico-a-051.html<br>
<br>
・SuperMEZ80<br>
SuperMEZ80は、EMUZ80にSRAMを追加し、Z80をノーウェイトで動かすことができるメザニンボードです<br>
<br>
SuperMEZ80<br>
https://github.com/satoshiokue/SuperMEZ80<br>
<br>