# 更新履歴

### バージョン 5.1.0
<hr/>
リリース日: 2023/12/05

* 廃止予定のAPIを取り除く
* バグを修正

### バージョン 5.0.0
<hr/>
リリース日: 2023/11/02

* Android 14 のサポート
* SDK Core ライブラリを取り除く
* SDKポータルを改善
* SDKポータルポータルでのメッセージを更新する

### バージョン 4.1.0
<hr/>
リリース日: 2023/09/12

* Android SDK の最小バージョンを24 (Android 7.0) にアップデート
* RaクッキーをセットするAPIを提供
* Android Gradle Plugin 7.3.1 にアップデート
* Kotlin 1.6.21 にアップデート

### バージョン 4.0.0
<hr/>
リリース日: 2023/07/28

* ユーザーの承諾をリクエストする機能の追加

### バージョン 3.7.0
<hr/>
リリース日: 2023/07/14

* SDKポータルの UI を改善
    * 未獲得ミッションリストのソート機能を追加
    * ミッションをタップして情報を詳しく示す
* `RakutenReward.openAdPortal()` API を廃止予定になります
* [FAQページ](../../faq/README.md) を改善

### バージョン 3.6.0
<hr/>
リリース日: 2023/04/12

* JAVA 11 にアップデート
* Android Gradle Plugin 7.1.0 にアップデート

### バージョン 3.5.1
<hr/>
リリース日: 2023/03/22

* バグを修正

### バージョン 3.5.0
<hr/>
リリース日: 2023/02/10

* SDKポータルにポイ活タブを追加
* Claim UIを改善
* SDK Core ライブラリのアップデート
* バグを修正

### バージョン 3.4.2
<hr/>
リリース日: 2022/12/02

* ミニブラウザーを改善
* 新しい`RakutenReward.startSession` APIを提供する
* `Activity.onActivityResult`で結果を得るの代わりに、Activity Result Callbackを使って新しいAPIを提供する
    * `RakutenAuth.openLoginPage`
    * `RakutenReward.openSDKPortal`
    * `RakutenReward.openAdPortal`

### バージョン 3.4.1
<hr/>
リリース日: 2022/10/25

* コンパイル Android SDK バージョンを API 33にアップデート
* 楽天市場アプリのサポート
* 台湾版のサポートを取り除く
* バグを修正

### バージョン 3.4.0
<hr/>
リリース日: 2022/09/28

* コンパイル Android SDK バージョンを API 31にアップデート
* 新しいミッション達成のノーティフィケーションをサポート
* `onBackPressed()` と `KeyEvent.KEYCODE_BACK` APIを使った部分を削除する
* バグを修正

### バージョン 3.3.0
<hr/>
リリース日: 2022/08/26

* 手動初期化は必要ないようになりました。アプリケーションのAndroidManifest.xmlに`App Code`を設定してください。[ここ](../basic/README.md#バージョン-330-から手動初期化は必要ないようになりました)に参照してください。
* コルーチン サポート。[ここ](../basic/README.md#コルーチン-サポート)に参照してください。
* 楽天市場アプリのサポート
* MissionList APIの検証を改善
* LogAction と Claim API を改善

### バージョン 3.2.2
<hr/>
リリース日: 2022/07/07

* ヘルプページURLを修正
* SDKポータル内のclaim UIのフローを改善
* SDK Core ライブラリのアップデート
* マイナーなバグを修正

### バージョン 3.2.1
<hr/>
リリース日: 2022/06/16

* SDK Core ライブラリのアップデート
* 楽天市場アプリのサポート

### バージョン 3.2.0
<hr/>
リリース日: 2022/05/31

* グローバル広告を改善
* マイナーなUIの問題を修正
* LogAction APIの検証を改善
* データベースへの非同期アクセスに関わる問題を修正

### バージョン 3.1.2
<hr/>
リリース日: 2022/05/04

* Claim UIにローディングアイコンを示す
* クッキーの設定を改善
* 楽天市場アプリのサポート

### バージョン 3.1.1
<hr/>
リリース日: 2022/04/08

* LogAction API を改善
* SDK デバッグログ機能の追加
* UIの問題を修正
* ログアウトAPIを改善
    * ID SDKかUser SDKのログインオプションを使っている方はユーザーがログアウト度にログアウトAPIを呼ぶ必要があります

### バージョン 3.1.0
<hr/>
リリース日: 2022/03/07

* kotlin のアップデート
* Event Ananlytics 機能を追加
* 楽天市場アプリのサポート
* 広告を外部ブラウザで開くの機能を追加
* `RakutenReward.addRakutenRewardListener`と`RakutenReward.removeRakutenRewardListener` APIを追加

### バージョン 3.0.0
<hr/>
リリース日: 2022/01/27

* SDKポータルのUIを改善
* SDK Core ライブラリのアップデート
* Android SDK の最小バージョンを21にアップデート
* `RakutenRewardBaseActivity`クラスを`FragmentActivity`クラスから拡張するように変更

### バージョン 1.1.4
<hr/>
リリース日: 2022/01/19

* コンパイル Android SDK バージョンを API 30にアップデート
* SDK Core ライブラリのアップデート

### バージョン 2.4.1
<hr/>
リリース日: 2022/01/14

* SDKポータル内のミッションのアイコンのメモリ管理を改善
* SDKポータル内の未獲得ミッション最大15個を表示するように変更
* 新しい openLoginPage APIを追加

### バージョン 2.4.0
<hr/>
リリース日: 2021/12/29

* コンパイル Android SDK バージョンを API 30にアップデート
* 広告ポータル機能の追加
* 廃止予定のPreferenceManagerクラスから AndroidX の PreferenceManagerにアップデート
* openSdkPortal APIに関するロジックの修正
* いくつのバグを修正

### バージョン 2.3.3
<hr/>
リリース日: 2021/12/02

* リージョンが台湾の場合のロゴを変更
* SDKポータル内のミッション達成のトグルを取り除く

### バージョン 2.3.2
<hr/>
リリース日: 2021/11/12

* UIの問題を修正

### バージョン 2.3.1
<hr/>
リリース日 : 2021/10/11

* Androidのライフサイクルに関する問題を修正(新しいAPIを追加)
* openPortal APIに関するロジックの修正
* Javaアクセスに関するコールバックの修正

### バージョン 2.3.0
<hr/>
リリース日 : 2021/09/21

* ウォール広告の問題を修正
* Android 開発環境のアップデート(gradleなど)
* SDKポータル上でミッション達成通知を表示させないようにする

### バージョン 1.1.3
<hr/>
リリース日 : 2021/08/31

* Android 開発環境のアップデート(gradleなど)
* SDK Core ライブラリのアップデート

### バージョン 2.2.2
<hr/>
リリース日 : 2021/07/26

* Android 5 でログインが維持できない問題を修正

### バージョン 2.2.1
<hr/>
リリース日 : 2021/06/08

* Wall広告の表示/非表示ロジックの問題の修正

### バージョン 2.2.0
<hr/>
リリース日 : 2021/05/27

* Rp, RzクッキーをセットするAPIを提供
* ポイントをクレイムするUIを閉じるためのAPIを提供
* クーポン広告のサポート
* デフォルトログインの場合にユーザーデータが正しくシンクされない問題を解消

### バージョン 2.1.0
<hr/>
リリース日 : 2021/03/01

* 台湾版のサポート

### バージョン 2.0.0
<hr/>
リリース日 : 2020/09/28

* サードパーティ向けのログインオプションを提供

### バージョン 1.1.2
<hr/>
リリース日 : 2020/11/23

* 広告にローディングアイコンを追加
* UI の修正

### バージョン 1.1.1
<hr/>
リリース日 : 2020/10/20  

* コンパイル Android SDK バージョンを API 29にアップデート

### バージョン 1.1.0
<hr/>
リリース日 : 2020/06/18  

* User SDKをサポート(現 ID SDK RAE)

### バージョン 1.0.0
<hr/>
リリース日 : 2020/02/20  

* 初期リリース

---
言語 :
> [![ja](../../lang/en.png)](../../history/README.md)