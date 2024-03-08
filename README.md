# flutterを使ってみた話

## 公式からダウンロードする

- まずは公式サイトからflutterを拾ってくる<br>
https://docs.flutter.dev/get-started/install/windows/web?tab=download#install-the-flutter-sdk

- 約2GBの空き容量が必要

- 10分程度は時間がかかる

- OSや環境によって必要なものが異なるので注意！

<br>

## PATHを通す

- インストール場所によってコマンドが変化するので注意

- 以下は、Windows環境でCドライブ直下にダウンロードした場合の例である

```
$ export PATH="$PATH:/c/flutter/bin"
```
<br>

## PATHが通ったか確認

- PATHをうまく通せていれば、以下コマンドが打てるはずである

- ただし、初回のみ```Hello!```的なメッセージが表示される

```
$ flutter --version
Flutter 3.19.3 • channel stable • https://github.com/flutter/flutter.git
Framework • revision ba39319843 (5 hours ago) • 2024-03-07 15:22:21 -0600
Engine • revision 2e4ba9c6fb
Tools • Dart 3.3.1 • DevTools 2.31.1
```
<br>

## doctorコマンド

- doctorコマンドを用いて、必要な環境などを確認する

- すべての項目に✓が付いていればOK

```
$ flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[√] Flutter (Channel stable, 3.19.3, on Microsoft Windows [Version 10.0.19045.4046], locale ja-JP)
[√] Windows Version (Installed version of Windows is version 10 or higher)
[X] Android toolchain - develop for Android devices
    X Unable to locate Android SDK.
      Install Android Studio from: https://developer.android.com/studio/index.html
      On first launch it will assist you in installing the Android SDK components.
      (or visit https://flutter.dev/docs/get-started/install/windows#android-setup for detailed instructions).
      If the Android SDK has been installed to a custom location, please use
      `flutter config --android-sdk` to update to that location.

[√] Chrome - develop for the web
[√] Visual Studio - develop Windows apps (Visual Studio Community 2022 17.1.3)
[!] Android Studio (not installed)
[√] IntelliJ IDEA Community Edition (version 2019.3)
[√] VS Code (version 1.80.1)
[√] Connected device (3 available)
[√] Network resources

! Doctor found issues in 2 categories.

```
<br>

## 参考

- Flutterの使いかた、環境構築から実装、ビルドまで<br>
https://future-architect.github.io/articles/20211221a/

- Flutterのインストール方法<br>
https://www.sejuku.net/blog/123973


