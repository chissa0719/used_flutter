# flutterを使ってみた話

# 公式からダウンロードする

- まずは公式サイトからflutterを拾ってくる
https://docs.flutter.dev/get-started/install/windows/web?tab=download#install-the-flutter-sdk

- 約2GBの空き容量が必要

- 10分程度は時間がかかる

- OSや環境によって必要なものが異なるので注意！

<br>

# PATHを通す

- インストール場所によってコマンドが変化するので注意

```
$ export PATH="$PATH:/c/flutter/bin"
```

# PATHが通ったか確認

- PATHをうまく通せていれば、以下コマンドが打てるはずである

- ただし、初回のみ```Hello!```的なメッセージが表示される

```
$ flutter --version
Flutter 3.19.3 • channel stable • https://github.com/flutter/flutter.git
Framework • revision ba39319843 (5 hours ago) • 2024-03-07 15:22:21 -0600
Engine • revision 2e4ba9c6fb
Tools • Dart 3.3.1 • DevTools 2.31.1
```

