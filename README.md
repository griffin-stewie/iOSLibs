# 気になる iOS 系ライブラリのメモ

## アニメーション系

### POP

[facebook/pop](https://github.com/facebook/pop "facebook/pop")

Facebook の Paper.app にも使われているアニメーション系ライブラリ

* [Full Length Event - Building Paper - YouTube](https://www.youtube.com/watch?v=OiY1cheLpmI "Full Length Event - Building Paper - YouTube")
* [Facebook Paper のアニメーションエンジン「pop」のソースコードを読んでみる - Over&Out その後](http://d.hatena.ne.jp/shu223/20140502/1399026349 "Facebook Paper のアニメーションエンジン「pop」のソースコードを読んでみる - Over&Out その後")

### PMTween

[poetmountain/PMTween](https://github.com/poetmountain/PMTween "poetmountain/PMTween")

### JazzHands

[IFTTT/JazzHands](https://github.com/IFTTT/JazzHands "IFTTT/JazzHands")

IFTTT が作ったアニメーションフレームワーク。Tutorial, Walk-through 画面のサンプルあり。

![ScreenShot](https://raw.github.com/IFTTT/JazzHands/screenshots/screenshots/intro.gif)

## UI

### MDCParallaxView

[modocache/MDCParallaxView](https://github.com/modocache/MDCParallaxView "modocache/MDCParallaxView")

Twitter や Path のようなスクロールに応じて画像が動く UI を作成するライブラリ

### SubjectiveCPhotoPanner

[subjc/SubjectiveCPhotoPanner](https://github.com/subjc/SubjectiveCPhotoPanner "subjc/SubjectiveCPhotoPanner")

[Facebook Paper's tilting panner · Subjective-C](http://subjc.com/facebook-paper-photo-panner/ "Facebook Paper's tilting panner · Subjective-C")

Paper.app のようにデバイスの傾きで大きな画像のpanを実現するサンプルプロジェクト

### UzysAnimatedGifPullToRefresh

[uzysjung/UzysAnimatedGifPullToRefresh](https://github.com/uzysjung/UzysAnimatedGifPullToRefresh "uzysjung/UzysAnimatedGifPullToRefresh")

Twitterrific のように PullToRefresh の Pull 動作と Loading 中の表示に任意の Gif 画像が設定できる。UIScrollView のカテゴリメソッドで追加できるようになっている。

### AFViewShaker

[ArtFeel/AFViewShaker](https://github.com/ArtFeel/AFViewShaker "ArtFeel/AFViewShaker")

OSX のログイン画面で不正な値を入力した時のように View を揺らすためのライブラリ。複数のView（例えば UITextField）を渡してアニメーションを掛けることができる。

### ECSlidingViewController

[ECSlidingViewController/ECSlidingViewController](https://github.com/ECSlidingViewController/ECSlidingViewController "ECSlidingViewController/ECSlidingViewController")

ドロワースタイルのViewController。カスタムトランジションのサンプルもある。FIFA っぽい動きもできるっぽい。

## グラフ

### TEAChart

[xhacker/TEAChart](https://github.com/xhacker/TEAChart "xhacker/TEAChart")

様々なグラフ表示に対応

* GitHub の contribution グラフ風
* アナログ時計風
* 棒グラフ

### GraphKit

[michalkonturek/GraphKit](https://github.com/michalkonturek/GraphKit "michalkonturek/GraphKit")

様々なグラフ表示に対応

* 折れ線
* 棒グラフ

## チュートリアル

### Flow

[OliverLetterer/Flow](https://github.com/OliverLetterer/Flow "OliverLetterer/Flow")

Facebook の Paper.app 風のチュートリアルライブラリ。音声あり。

## プログレス・ローディング

### ASProgressPopUpView

[alskipp/ASProgressPopUpView](https://github.com/alskipp/ASProgressPopUpView "alskipp/ASProgressPopUpView")

UIProgressView に進捗率を表示するPopOverが付いたもの。進捗率に合わせて色も変わる。

### MBProgressHUD

[jdg/MBProgressHUD](https://github.com/jdg/MBProgressHUD "jdg/MBProgressHUD")

定番 HUD ライブラリ

### HTProgressHUD

[Hardtack/HTProgressHUD](https://github.com/Hardtack/HTProgressHUD "Hardtack/HTProgressHUD")

Yet Another MBProgressHUD


## ユーティリティ

### color

[thisandagain/color](https://github.com/thisandagain/color "thisandagain/color")

* iOS 7 風のグラデ
* Hex
* HSB/HSL の調整

などの UIColor のカテゴリメソッド集

### RNCryptor

[RNCryptor/RNCryptor](https://github.com/RNCryptor/RNCryptor "RNCryptor/RNCryptor")

暗号化

### RHAddressBook

[heardrwt/RHAddressBook](https://github.com/heardrwt/RHAddressBook "heardrwt/RHAddressBook")

アドレスブック関係

### APAddressBook

[Alterplay/APAddressBook](https://github.com/Alterplay/APAddressBook "Alterplay/APAddressBook")

アドレスブック関係

### KSFileUtilities

[karelia/KSFileUtilities](https://github.com/karelia/KSFileUtilities "karelia/KSFileUtilities")

NSURL & path additions

* Query Parameters
* KSURLFormatter
* KSURLComponents
    * NSURLComponents の Backport
* etc etc    

### PSTAlertController

[steipete/PSTAlertController](https://github.com/steipete/PSTAlertController "steipete/PSTAlertController")

iOS 8 で追加された `UIAlertController` と同等のインターフェイスで iOS 7 でも利用できるラッパー


## 飛び道具系

### ReactiveCocoa

[ReactiveCocoa/ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa "ReactiveCocoa/ReactiveCocoa")

GitHub の @joshaber さんを中心に Functional Reactive Programming を実現するためのライブラリ
GitHub.app にも使われている

パラダイムが大きく変わるので利用には覚悟が必要。 

### Aspects

[steipete/Aspects](https://github.com/steipete/Aspects "steipete/Aspects")

アスペクト指向を実現するためのライブラリ
作者は PSPDFKit の @steipete さん

## Tools

### Objective-C-codegenutils

[square/objc-codegenutils](https://github.com/square/objc-codegenutils "square/objc-codegenutils")

square 製の CLI コマンド集。
特に objc-colordump コマンドは color palettes からカテゴリメソッドを生成してくれる。