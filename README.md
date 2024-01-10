# MS-50G+
  
## 1.画面は3種類
1. ホーム画面：起動直後の画面。100あるパッチメモリーを、フットスイッチの上下（上段のほう）で切り替える、通常使用する画面。パッチのなかに複数のエフェクターがある場合は、フットスイッチの左右（下段のほう）で横移動する。表示されているエフェクターのパラメーターを、画面下に４つあるノブで操作できる。  
2. LIBRARY画面：パッチにエフェクターを追加する際に、エフェクターを選択する画面。エフェクターのカテゴリーごとに、同一ジャンルのものが縦に並んでいる。カテゴリーを変える時はフットスイッチの左右（下段のほう）で横移動する。  
3. MENU画面：初期化など、各種設定をする画面。画面下に４つあるノブで操作する。  
  
## 2. 内蔵エフェクト（１０３）の一覧
詳細は[こちら](./FXlist.md)
  
|No|ジャンル|数|
|--|--|--|
|1|DYNAMICS|8|
|2|FILTER|7|
|3|DRIVE|19|
|4|PREAMP|22|
|5|MODULATION|22|
|6|DELAY|13|
|7|REVERB|7|
|8|SFX|5|
||合計|103|
  
## 3.Factory Presets（プリセット・パッチメモリー）（８５）の一覧
詳細は[こちら](./FactoryPreset.md)  
起動時に表示される「ホーム画面」は、パッチメモリーを切り替える画面。  
本体を初期化すれば復元できるので、削除したり上書きしてもよい。  
Factory Prestes の85個中60個が、有名な曲をイメージした設定になっており、パッチ名も曲名ズバリになっている。  
かなり網羅されているので、知らない曲があれば、聴いてみるとよい。  
  
|No|ジャンル|数|
|--|--|--|
|1|Preset|85|
|2|Empty|15|
  
## 4.使いやすくするコツ
Factory Preset は、必ずしもそのまま使うものばかりでもない。  
エフェクターがたくさん内蔵されているので、単体でどういう音なのか試したいが、設定で呼び出すのは手間や時間がかかる。  
そこで、Factory Preset は削除してしまって、  
1. パッチメモリーの001から昇順：「各エフェクター１つ」というパッチでプリセットを上書き。
2. パッチメモリーの100から降順：実際に音作りしたパッチを保存。
  
とすれば、「フットスイッチでパッチメモリーを切り替えて」、「単体の音を試す」のと、「音作りしたユーザープリセットを呼び出す」のを、両立できる。  
iOS のアプリがあれば、この状態をバックアップして、１パッチ１ファイルで書き出せる。  
設定やrenameの作業も、本体でやるよりもアプリでやったほうが効率がいい。  
作業はなかなか骨が折れるが、バックアップ・リカバリ・共有ができるので、いちど、頑張って作業してしまえば、次からはファイルからリカバリできる。
くわしくは[こちら](./UserPreset.md)
  
## 5.工場出荷時の設定に戻す
iOSアプリを使えば、現状の設定を「１パッチ１ファイル」で書き出せるので、初期化する前には、バックアップするとよい。  
  
1. MENU画面で「FACTORY RESET」を選択する
2. ノブを回して「YES」を選択する
3. ノブを押し込んで「ENTER」する
4. 初期化が実行され工場出荷時の設定に書き換えられます
  
## 6.使い方あれこれ
- シーン１：単体で「マルチエフェクター」として使う
- シーン２：エフェクターボードの前方に組み込み、「歪み系単体ペダル」的に使う
- シーン３：エフェクターボードの後方に組み込み、「空間系単体ペダル」的に使う
  
「シーン３」を想定して、パッチメモリーのプリセットを消し、001から昇順に「空間系のFXを１つだけ置いたユーザープリセット」、100から降順に「空間系のFXを複数置いたユーザープリセット」に置き換える。  
くわしくは[こちら](./UserPreset.md)
  
1. パッチメモリーの１から７までを昇順で「REVERB」から１つだけ置いたプリセットにする。
2. パッチメモリーの８から２０までを昇順で「DELAYから１つだけ置いたプリセットにする。
3. パッチメモリーの２１から４２までを昇順で「MODULATION」から１つだけ置いたプリセットにする。
4. パッチメモリーの４３から５０までを昇順で「DYNAMICS」から１つだけ置いたプリセットにする。
5. パッチメモリーの５１から５７までを昇順で「FILTER」から１つだけ置いたプリセットにする。
6. パッチメモリーの５８から７６までを昇順で「DRIVE」から１つだけ置いたプリセットにする。
7. パッチメモリーの１００から降順で、「MODULATION」「DELAY」「REVERB」などを置いたユーザープリセットにする。