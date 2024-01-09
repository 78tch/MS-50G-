# MS-50G+
[戻る](./README.md)
## パッチメモリー(100個)の設定例
  
Factory Preset は、必ずしもそのまま使うものばかりでもない。  
エフェクターがたくさん内蔵されているので、単体でどういう音なのか試したいが、設定で呼び出すのは手間や時間がかかる。  
そこで、Factory Preset は削除してしまって、  
1. パッチメモリーの001から昇順：「各エフェクター１つ」というパッチでプリセットを上書き。
2. パッチメモリーの100から降順：実際に音作りしたパッチを保存。
  
とすれば、「単体の音を試す」のと、「音作りしたユーザープリセットを呼び出す」のを、両立できる。  
ios のアプリがあれば、この状態をバックアップして、１パッチ１ファイルで書き出せる。  
中身は単なるテキストファイルであり、拡張子は「.zptc」。  
  
以下の表のように設定した設定ファイルを、[リンク先](https://drive.google.com/drive/folders/1qUogeVSghd8oD4pVegNLOcD8s_Ive20_?usp=drive_link)に置いています。  
iOS 版のアプリから、インポートできます。  
  
|No|Name|type|Memo|
|---|---|---|---|
|1|ROOM REVERB|REVERB|部屋の残響をシミュレートしたリバーブです。|
|2|BRGHT ROOM REVERB|REVERB|明るい残響が得られるルームリバーブのシミュレーションです。|
|3|SPRING REVERB|REVERB|スプリングリバーブのシミュレーションです。|
|4|HALL REVERB|REVERB|コンサートホールの残響をシミュレートしたリバーブです。|
|5|BRGHT HALL REVERB|REVERB|明るい残響が得られるホールリバーブのシミュレーションです。|
|6|AIR REVERB|REVERB|部屋鳴りの空気感を再現し、空間的な奥行きを与えます。|
|7|EARLY REFLECTION REVERB|REVERB|リバーブに含まれる初期反射音のみを取り出したエフェクトです。|
|8|DELAY|DELAY|最長4000msのロングディレイに対応したディレイです。|
|9|ANALOG DELAY|DELAY|最長4000msのロングディレイに対応した、暖かみのあるアナログディレイのシミュレーションです。|
|10|TAPE ECHO|DELAY|テープエコーの効果をシミュレートしたエフェクトです。"Time" パラメーターを変化させると、エコー音のピッチが変化します。|
|11|TAPE ECHO 3|DELAY|MAESTRO ECHOPLEX EP-3をモデリングしたテープエコーサウンドです。|
|12|DUAL DELAY|DELAY|2つの独立したディレイを組み合わせることができるエフェクトです。|
|13|SOFT ECHO|DELAY|ソフトな音質のエコーです。エコー音にモジュレーションの効果がかかるエフェクトです。|
|14|SLAPBACK DELAY|DELAY|カッティングやロカビリーに適した短いタイムに特化したディレイです。|
|15|PING-PONG DELAY|DELAY|ディレイ音が左右交互に出力されるディレイです。|
|16|REVERSE DELAY|DELAY|最長2000msのロングディレイに対応した、リバースディレイです。|
|17|MODULATION DELAY|DELAY|ディレイ音にモジュレーションの効果がかかるエフェクトです。|
|18|FILTER DELAY|DELAY|ディレイ音にフィルターの効果がかかるエフェクトです。|
|19|PITCH DELAY|DELAY|ディレイ音にピッチシフターの効果がかかるエフェクトです。|
|20|HOLD DELAY|DELAY|フットスイッチの操作で制御する、ホールド・ディレイです。フットスイッチを踏み込むとエフェクトON、離すとエフェクト音がホールドされます。|
|21|CLONE CHORUS|MODULATION|Electro-Harmonix SmallCloneをモデリングしたアナログコーラスサウンドです。|
|22|CHORUS ONE|MODULATION||
|23|TRI CHORUS|MODULATION|BOSS SUPER CHORUS CH-1のモデリングです。|
|24|ANALOG CHORUS|MODULATION|アナログコーラスのシミュレーションです。|
|25|STEREO CHORUS|MODULATION|クリアな音質のステレオコーラスです。|
|26|DETUNE|MODULATION|わずかにピッチシフトさせたエフェクト音と原音をミックスさせることで、変調感の少ないコーラス効果が得られるエフェクトタイプです。|
|27|ORANGE TREMOLO|MODULATION|音量を周期的に上下させるエフェクトです。|
|28|PHASER|MODULATION|音にシュワシュワした揺らぎを加えるエフェクトです。|
|29|STONE PHASER|MODULATION|Electro-Harmonix SmallStoneをモデリングしたフェイザーサウンドです。|
|30|WARP PHASER|MODULATION|一方向に効果がかかるフェイザーです。|
|31|THE VIBE|MODULATION|独特のうねりが特徴的なヴァイブサウンドです。|
|32|VINTAGE FLANGER|MODULATION|MXR M-117Rのようなアナログフランジャーのサウンドです。|
|33|KICK FLANGER|MODULATION|フットスイッチの操作で制御するフランジャーです。|
|34|VIBRATO|MODULATION|自動的にビブラートのかかるエフェクトです。|
|35|SWELL VIBRATO|MODULATION|ピッキング後に音程を揺らすエフェクトです。|
|36|OCTAVER|MODULATION|原音に1オクターブ下と2オクターブ下の音を加えるエフェクトです。|
|37|POLYPHONIC OCTAVER|MODULATION|和音に対応したオクターバーです。|
|38|HARMONY PITCH SHIFTER|MODULATION|設定されたキーやスケールに応じてピッチをシフトしたエフェクト音を出力する、インテリジェントなピッチシフターです。|
|39|POLYPHONIC PITCH SHIFTER|MODULATION|和音に対応したピッチシフターです。|
|40|GEMINOS DOUBLER|MODULATION|ダブルトラッキングをリアルタイムに得ることができるエフェクトです。|
|41|RING MODULATOR|MODULATION|金属的なサウンドを作り出すエフェクトです。"FREQ" パラメーターの設定で音色がガラリと変わります。|
|42|SLICER|MODULATION|音を連続的に刻んでリズミカルなサウンドを作り出すエフェクトです。|
|43|COMPRESSOR|DYNAMICS|MXR Dyna Comp風のコンプレッサーです。|
|44|RACK COMPRESSOR|DYNAMICS|細かい調節の可能なコンプレッサーです。|
|45|GRAY COMPRESSOR|DYNAMICS|ROSS Compressorのモデリングです。音質を調節することができるパラメーターを追加しました。|
|46|BLACK OPTICAL COMPRESSOR|DYNAMICS|Demeter COMP-1 Compulatorのモデリングです。音質を調節することができるパラメーターを追加しました。|
|47|1176 LIMITER|DYNAMICS|UREI 1176LNのモデリングです。|
|48|ZOOM NOISE REDUCTION|DYNAMICS|音色を損なわずに無演奏時のノイズを抑えるノイズリダクションです。|
|49|NOISE GATE|DYNAMICS|無演奏時に信号をカットするノイズゲートです。|
|50|SLOW ATTACK|DYNAMICS|バイオリン奏法のように、1音1音の立ち上がりをゆるやかにするエフェクトです。|
|51|AUTO WAH|FILTER|ピッキングの強弱に応じてワウ効果がかかるエフェクトです。|
|52|LOW-PASS FILTER|FILTER|ピッキングの強弱に応じてローパスフィルターの周波数が動くエフェクトです。|
|53|ENVELOPE GENERATOR FILTER|FILTER|フットスイッチの操作で制御するフィルターエフェクトです。|
|54|SEQUENCE FILTER|FILTER|Z.Vex Seek Wah風のシーケンスフィルターです。|
|55|STEP FILTER|FILTER|音色が階段状に変化するエフェクトです。|
|56|GUITAR GRAPHIC EQ7|FILTER|モノラル仕様の7バンドのイコライザーです。|
|57|PARAMETRIC EQ|FILTER|モノラル仕様の1バンドのパラメトリック・イコライザーです。|
|58|EP DRIVE|DRIVE|Maestro Echoplexのプリアンプをモデリングしたエフェクトです。|
|59|RC DRIVE|DRIVE|クリーン・ブーストから軽いドライブサウンドまでカバーするブースターです。|
|60|TS DRIVE|DRIVE|Ibanez TS808をモデリングしたエフェクトです。|
|61|GOLD DRIVE|DRIVE|ブティックペダルを代表する金色のオーバードライブをモデリングしたエフェクトです。|
|62|SWEET DRIVE|DRIVE|甘いサウンドのオーバードライブをモデリングしたエフェクトです。|
|63|ZEN O.DRIVE|DRIVE|Hermida Audio Zendriveのモデリングです。|
|64|DYNAMIC DRIVE|DRIVE|簡単に真空管アンプの暖かいドライブトーンが得られるエフェクトです。|
|65|PLUS DISTORTION|DRIVE|MXR DISTORTION+のモデリングです。|
|66|DISTORTION ONE|DRIVE|BOSS DISTORTION DS-1のモデリングです。|
|67|SQUEAK DISTORTION|DRIVE|ProCo RATのモデリングです。原音のミックスレベルが調節できるパラメーターを追加しました。|
|68|RED CRUNCH DRIVE|DRIVE|ブラウンサウンドの得られるエフェクトです。|
|69|VIOLET DISTORTION|DRIVE|SUHR Riot Reloadedのモデリングです。|
|70|TB MK1.5 FUZZ|DRIVE|伝統的なファズ・エフェクトです。|
|71|OCTAVE FUZZ|DRIVE|アッパー・オクターブを加えたファズ・エフェクトです。|
|72|NEW YORK MUFF FUZZ|DRIVE|Electro-Harmonix Big Muff Piのモデリングです。原音と歪みの音量バランスを調節することができるパラメーターを追加しました。|
|73|WAVE SHAPER DRIVE|DRIVE|新しいディストーションアルゴリズムにより波形を成形し、ユニークなサウンドが得られるディストーションエフェクトです。|
|74|RAZOR DRIVE|DRIVE|コムフィルターを使って歪みをコントロールする新感覚のディストーションエフェクトです。|
|75|HG THROTTLE DRIVE|DRIVE|Mesa Boogie THROTTLE BOX(GAIN SWITCH:HI / BOOST:ON)のモデリングサウンドです。|
|76|ACOUSTIC SIMULATOR|DRIVE|エレクトリックギターの音色をアコースティックギター風に変えるエフェクトです。|
|77||||
|78||||
|79||||
|80||||
|81||||
|82||||
|83||||
|84||||
|85||||
|86||||
|87||||
|88||||
|89||||
|90||||
|91||||
|92||||
|93||||
|94||||
|95||||
|96||||
|97||||
|98||||
|99||||
|100|||
  
  
[戻る](./README.md)
