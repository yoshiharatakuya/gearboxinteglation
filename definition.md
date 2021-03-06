 ## 下ギアを設計する上で守るべき制約
　これはインフレームという仕様上駆動単独で考えると危険となるため
　注意しなければならない点について述べていくところである。ほとんど引き継ぎ資料を
　見てもらうとそれ以上のことが書いてある可能性が高いのでそちらをメインで考えて欲しいかも
* ### フレームの全断面上にフランジが存在していること
どういうことかというと下図のようなこと
![フレームとフランジ](https://raw.githubusercontent.com/yoshiharatakuya/gearboxinteglation/master/sharephoto/%E3%83%95%E3%83%AC%E3%83%BC%E3%83%A0%E3%81%A8%E3%83%95%E3%83%A9%E3%83%B3%E3%82%B8.png)


インフレームという構造上、絶対守らなければならないことだと思う。
機体が着地時もろに軸方向に荷重が伝達されるのでフレームの断面がフランジの形に内包されて
いないと軸方向に力をかけた時にまっすぐ伝達されない。また横滑りで着地した時に、そこを基点に
破損する恐れもあるので、そこは必ず守って欲しい。
* ### 上下フランジはこれ以上薄くしない
暁月の設計では厚みが4mm（実際は製作上の誤差で-）だがこれ以上薄くすると六角穴付きボルト(1175)
もしくは低頭のボルトで締めた所がTF等で運用していくと凹んだり変形した箇所が見られた（麗月時)ので
そこでの軽量化はやめといた方が良い。麗月はギアボの位置が高かったということもあり、横滑りでドン着する
ことがギアボに対して一番負荷がかかるので薄くするならギアボの位置を下げて計算時にフランジにかかる負荷と
ボルトの剪断荷重を計算して大丈夫なのかを確認した上での変更をお願いいたします。特にボルトの径の変更
とかは特に危険なので。
