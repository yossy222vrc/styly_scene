

# 触れるとキューブが回転するサンプルシーン(STYLY)


STYLYのPlaymakerチュートリアルのインタラクティブが上手く動かなかったので、下記問題を回避するように制作したサンプルシーンです。

* PCVRでコントローラーにコライダーがついていないっぽいのでトリガー検知ができない
    * →コントローラを追従するスフィアを用意して回避


* シーンを開いた時に何もしていないのにTRIGGER ENTERが発火してしまう
    * →シーンの最初にWaitのステートを用意することで回避

VRコントローラを追従するスフィアがキューブにに触れると、キューブがY軸に沿って回転します。VRコントローラが検知できない場合はX軸に沿って回転します。


# STYLYギャラリーのサンプル

* Cube rotates when the sphere touches the cube
    * https://gallery.styly.cc/yossy222vrc/3fef1c27-fe00-11e9-bea5-06540631ffe6


# 使い方

`styly_touch_interactive_sample.unitypackage` をインポートし、シーンをSTYLYへアップロードしてください。

あらかじめ、 Playmaker と Unity plugin for STYLY のインストールが必要です。

* [Playmaker](https://assetstore.unity.com/packages/tools/visual-scripting/playmaker-368)
* [Unity plugin for STYLY](https://styly.cc/ja/download/)


# 参考サイト

* [PlayMaker 【Unity/Playmaker】STYLYのインタラクティブ機能を作る](https://styly.cc/ja/tips/playmaker-interactive/)
* [Unofficial STYLY New feature & Bugs](https://trello.com/b/HyFmSKum/unofficial-styly-new-feature-bugs)
