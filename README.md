# WeChat Mini Program

## ドキュメント

### 英語
https://github.com/apelegri/wechat-mini-program-wiki

### 中国語
https://developers.weixin.qq.com/miniprogram/dev/

## 概要
WeChat上に載せられる簡易的なアプリのこと。JSとHTML、CSSで作成できる。JSといってもほとんどVue.jsに近い。独自のVue.jsの機能である。

## ICPライセンス
中国大陸でウェブサービスを提供するためには、[ICPライセンス](https://www.clara.jp/consulting/icp/lp/#section07)が必要になる。ウェブサービスとはいえ、APIサーバを大陸内に置く場合も同様である。このライセンスには経営性と非経営性があり、前者は取得に一年とかかかることもあり、後者は数日からせいぜい数週間で取れる。

ミニプログラムは海外の法人も作成可能だが、事業内容によってはICPライセンスの取得が必要になるので注意が必要だ。

## データの保持

### 永続化
公式でおすすめされているサービス。ただし、 __中国大陸の電話番号が必要__ 。

https://leancloud.cn/

### キャッシュ
WeChat側のAPIでキャッシュの仕組みが提供されている。KVSで、iOSでいうところのUserDefaultsに近い。

## WeChat API

以下の機能がWeChatのミニプログラムで提供されており、 `wx.getUserInfo` のように `wx` オブジェクト内に入っている。

- ユーザ情報取得機能
- データのキャッシュ機能
- QRコード読み取り機能
- 位置情報取得機能
- 画像の取扱（保存等）機能


## TODO

海外法人アカウントで作成する場合の制約について、WeChat Payが使えない？とかの調査をする。