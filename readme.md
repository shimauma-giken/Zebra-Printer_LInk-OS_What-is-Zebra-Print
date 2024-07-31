# Zebra Print とはなにか？ 要諦と注意点


<img width="100" src="https://play-lh.googleusercontent.com/8HJ6ikrUxD9PeMRma5_JW-Xkmy4LkfvJtJGyTpxoZJnTZVamvHUukW62r6uWk_-ysA=w1052-h592-rw"> <img width="100" src="https://play-lh.googleusercontent.com/z1o7ElmU09MpvelH6HtfR2CrEpTs-V_fDx1pKrOa7DcYizGaFGljz7iTh17znyr-oTQx=w1052-h592-rw"> <img width="100" src="https://play-lh.googleusercontent.com/RQXVkYGXZpY2NhuPoZYS57PX6cavl8F7QPzFoTPMCNEXfEaLsIQGSHWR_Bw5bVtLZZk=w1052-h592-rw"> <img width="100" src="https://play-lh.googleusercontent.com/mx_8UCzS-y4teNoU-4QFJ_ttYVRdpa5198jpTqr2vg4XoQcgD4WQRrF2FBy58tEsZcM=w1052-h592-rw"> 

</br>

## ■ Zebra Printとはなにか。

Androidの標準印刷サービスを用いてZebraラベルプリンタに対して印刷指示ができるサービスアプリ。Windows ドライバのような役割を果たすアプリ。

例えば下記のようなことができる。

1. PDFの印刷
1. 画像イメージの印刷
1. Word、Excel表の印刷
1. ブラウザ上のコンテンツを印刷
1. Androidの標準印刷サービスが実装された自作アプリ

基本的にはAndroid標準印刷サービスが実装されているアプリから印刷ができると考えて良い。

<img height="400" src="https://docs.zebra.com/content/dam/techpubs/media/printers/software/zebraprint/g-zprint-label.png/_jcr_content/renditions/cq5dam.web.1280.1280.jpeg">

</br>

</br>

##### # 注意

**Android標準印刷サービスが実装されているアプリからの印刷を保証しているわけでは無い。OSやアプリのバージョンによって動作しないケースがあるので、検証の上で利用すること。**


</br>

## ■ 実装されている機能

1. ペアリング機能（NFC Touch, Bluetooth, Wi-Fi)
1. 自動縮尺機能（自動的にラベルの大きさに合わせて印刷してくれる）
1. プリンタ設定機能（ラベルサイズ、印字濃度・速度など）


</br>

## ■ 入手方法
1. [Google Play](https://play.google.com/store/apps/details?id=com.zebra.channelaps&hl=ja)
1. [www.zebra.com](https://www.zebra.com/us/en/support-downloads/software/printer-software/zebra-print.html?downloadId=1cada4b7-285a-455e-9157-0a41c717f711#Ta-item-644958a420-tab)


</br>

## ■ システム要件

[システム要件](https://www.zebra.com/us/en/support-downloads/software/printer-software/zebra-print.html?downloadId=1cada4b7-285a-455e-9157-0a41c717f711#Ta-item-3ffcf4ea55-tab)


</br>

## ■ メリット・デメリット
### メリット

- 無償で利用できる。
- シンプルに使える。
- Android標準印刷サービスが実装された汎用アプリからラベル印刷ができる。
- Androidの標準機能のみで自作アプリの開発ができる。

### デメリット

- Android標準印刷サービスが実装されているアプリからの印刷を保証しているわけでは無い。また、フリーツールであるため、トラブル発生時のサポートに制限がある。
- イメージ印刷となるため、高品質な印刷には不向き。特に可読性の高い小サイズのバーコードや文字は不向き。
- イメージ印刷となるため、専用アプリと比べるとパフォーマンスが悪い。



</br>

## ■ こんなユーザに最適

1. アプリの導入・開発コストを削減したいユーザ。
    - 汎用アプリから手っ取り早くラベル印刷をしたい。
    - 自作アプリの開発コストを下げたい。
1. 汎用プリンタから印刷業務をラベルプリンタへ移植したいユーザ。
1. 販促のため、ラベル印刷デモをしたい方。


</br>

## ■ こんなユーザには不向き

1. 高パフォーマンス印刷が求められる現場
1. 小サイズラベル、文字、バーコード印刷が求められる運用
1. RFID印刷が必要な処理





