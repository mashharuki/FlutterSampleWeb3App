# FlutterSampleWeb3App

Flutter + WalletConnect で作成するサンプル用 Web3 モバイルアプリです。

## 動かし方

```bash
cd sample_web3_app && flutter run --dart-define=PROJECT_ID={YOUR_PROJECT_ID}
```

以下で WalletConnect 用のライブラリをインストール

```bash
flutter pub add web3modal_flutter
```

## Flutter と Dart のバージョン上げ方

```bash
flutter upgrade
```

以下で確認

```bash
dart --version
```

### 参考文献

1. [GitHub - WalletConnect Example](https://github.com/WalletConnect/Web3ModalFlutter/tree/master/example)
2. [WalletConnect Docs](https://docs.walletconnect.com/web3modal/flutter/installation?platform=ios)
3. [Build a Web3 Flutter App with Web3Modal](https://www.youtube.com/watch?v=v_M2buHCpc4&t=16s)
