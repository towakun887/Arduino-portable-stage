# Arduino卓上ライブステージ with Hololens 2
[mainブランチのArduino卓上ライブステージ](https://github.com/towakun887/Arduino-portable-stage/tree/main)を、Hololens2によるARアプリケーションと連動させたもの。  
Hololens2上で、オブジェクトをステージに降ろすと、再生が始まる。ステージの周囲にはARオブジェクトが表示される。  

## デモ動画 (youtube)
[https://youtu.be/3Diwrs3YfBw?si=--2vxwpaEu3IeS5x](https://youtu.be/3Diwrs3YfBw?si=--2vxwpaEu3IeS5x)
[![](https://i.ytimg.com/vi_webp/3Diwrs3YfBw/sddefault.webp)](https://youtu.be/3Diwrs3YfBw?si=--2vxwpaEu3IeS5x)

# 以下は、mainブランチのreadme.md
電子工作(25春)中間制作及びその発展としての最終制作  を、さらに改修したもの

## 概要
#### 最終制作提出後の改修内容
PCA9685基板の導入と、それに伴うコード書き換え。ほぼ全面的に書き換えを実施。  

#### 最終制作提出レポートより抜粋
3. 作品概要  
卓上ライブステージ。1 個ずつに切り離した NeoPixel LED 4 個に対してサーボモーターを各 2 個ずつ取り付け，2 軸可動のステージライト 4 個とした上で，Arduino UNO R4 (WiFi)に接続したもの。  
フラッシュメモリ内に書き込まれた独⾃規格である 1 フレームあたり 8進数 21 桁のライティング指⽰と，同サイズの運動指⽰のデータを毎フレームごとに解釈し，LED テープとサーボモーターへ反映する。  
USB-C 経由でスマートフォンと接続し，スマートフォン側で動画を開いた状態でArduino 側のスイッチを押すと，動画の再⽣及びステージライト動作の再⽣が開始される。  
ステージライトの再⽣が終了すると，数フレーム後に動画が⾃動で再⽣停⽌する。  
筐体は樹脂製の組み⽴て式で，解体すると嵩張らなくなる。中間制作のアップデート品。  
  
#### 中間制作提出レポートより抜粋  
3. 作品概要  
4 個の LED がついた NeoPixel LED テープを，ライブステージのライトとして⽤いたArduino Uno R4 (WiFi)作品。  
フラッシュメモリ内に書き込まれた 1 フレームあたり 8 進数21 桁のライティング指⽰を毎フレームごとに解釈し，LED テープへ反映する。  
USB-C 経由でスマートフォンと接続し，スマートフォン側で動画を開いた状態で Arduino 側のスイッチを押すと，動画の再⽣及びライティングの再⽣が開始される。  
ライティングは⾃動で終了するが，動画は⼿動で再⽣停⽌する必要がある。  

https://web.sfc.keio.ac.jp/~t24789tm/utils/#Arduino-portable-stage
## デモ動画 (YouTube)
[https://youtu.be/DXe0JBAQ8Vc?si=kuB1D2xVa5uy_Kra](https://youtu.be/DXe0JBAQ8Vc?si=kuB1D2xVa5uy_Kra)
[![](https://i.ytimg.com/vi_webp/DXe0JBAQ8Vc/sddefault.webp)](https://youtu.be/DXe0JBAQ8Vc?si=kuB1D2xVa5uy_Kra)
