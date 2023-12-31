## 職務経歴書

- 地方スーパーのオンライン注文、レジ決済アプリのリニューアル開発
  - 期間
    - 2022/11 ~ 現在
  - チーム編成
    - PM x 2人
    - iOSエンジニア x 5人
    - Androidエンジニア x 5人
    - KMMエンジニア x 3人
    - サーバサイドエンジニア x 4人
    - デザイナー x 1人

    iOSリードエンジニアとして参画
    
  - 言語・フレームワーク
      - iOS, Swift, KMM, SwiftUI
  - Architecture
    - MVI
  - ツール
    - Github, Jira, Confluence, Github, Bitrize, GAS, Github Action
  - プロダクト概要
    - 地方スーパーでのオンライン注文やレジでの決済、ポイント管理などを行うアプリ
    - 現行アプリが古い状態からメンテナンスができておらずブラックボックスが多く工数がかかってしまうということで古いコードを捨てて完全リニューアルを行いました。
  - 苦労した点
    - KMMの知見が少なく立ち上げ当初開発のスピードがあまり出ずにスケジュールを圧迫してしました

- 自動車ディーラー向けのiPad用カタログアプリ
  - 期間
    - 2021/9 ~ 2023/3
  - チーム編成
    - PM x 1人
    - iOSエンジニア x 5人
    - デザイナー x 1人

    iOSエンジニアとして参画
    
  - 言語・フレームワーク
      - iOS, Swift, UIKit
  - Architecture
    - MVC
  - ツール
    - Bitbucket, Jira, Github, Github Action
  - プロダクト概要
    - 大手自動車ディーラー向けの紙のカタログをデジタルに移行するために、デジタルに移行するためのiPadアプリ
  - 苦労した点
    - メンバーの口数が細切れで担当画面を割り振って開発を進めており、横の共有ができていなかったので仕様の齟齬などが発生してしまった
    - CIやAppStoreへの配布周りを一人で管理していたので属人化していたので解消するために自動化を行いました

- ゲームの記録管理を行うポータルアプリ
  - 期間
    - 2019/10 ~ 2022/10
  - チーム編成
    - PM x 3人
    - iOSエンジニア x 5人
    - Androidエンジニア x 5人
    - サーバサイドエンジニア x 4
    - デザイナー x 4人

    iOSエンジニアとして参画

  - 言語・フレームワーク
      - iOS, Swift, UIKit
  - Architecture
    - MVP
  - ツール
    - Bitbucket, Jira, Confluence, Jenkins
  - プロダクト概要
    - ユーザのゲームの記録を管理や、ゲームの情報を提供するためのアプリ
  - 苦労した点
    - アニメーションやレイアウトにおいて要求されるレベルが高く、iPadのSplitViewや画面回転なども考慮してデバッグを行いました。

- IoTアプリ開発プロジェクト
  - 期間
    - 2018/11 ~ 2019/9
  - チーム編成
    - iOSエンジニア x 2人
    - Androidエンジニア x 2人
    - デザイナー x 1人

    iOSエンジニアとして参画

  - 言語・フレームワーク
      - iOS, Bluetooth, Swift, RxSwift, UIKit
  - Architecture
    - Clean Architecture
  - ツール
    - CircleCI, Redmine, Xcode, fastlnae, cocoaPods, Github
  - プロダクト概要
    - IoTのおもちゃへのアップデートを行うアプリの作成です。アップデート対象は大きく分けて２種類存在し、Nordicのチップが搭載されているものに対してはIOS-DFU-Libraryを使用してアップデートを行います。
    - もう一つは独自通信でアップデートを行なっています。暗号化にはblake2s,crc16を用いています。
  - 苦労した点
    - テストを行う上でCoreBluetoothのPeripheral（通信対象）はインスタンスを作成することができません。その為BLE通信を行なってファームウェアのアップデートをしている部分のテストを行うことが困難でしたが、PresenterのMockを生成することでUITestが行える環境を作りました。
    - Mockを生成したおかげでBLE通信なしで遷移が可能になった為、FastlaneのSnapshot機能を使用しスクリーンショットの自動化も行えるようになりました。スクリーンショットはAppStoreのプレビュー用にも使用することを考えSimulatorStatusMagicを使いキャリアなどが表示されないように修正を行いました。
    - Peripheral側の実装でテストを行うことも試みましたが、iosもandroidもAdvertise時に公開できるデータに制限がある為mockアプリを作成することはできませんでした。

- Pepperビジュアルプログラミングアプリケーション
  - 期間
    - 2018/05 ~ 2018/10
  - チーム編成
    - PM x 1人
    - Androidエンジニア x 5人
    - デザイナー x 1人

    Androidエンジニアとして参画

  - 言語・フレームワーク
      - Java, Android
  - Architecture
    - Clean Architecture
  - ツール
    - Bitbucket, Backlog, AndroidStudio
  - プロダクト概要
    - PepperのSKDのversionアップに伴い店頭での接客をユーザが思い通りに操作できるようにするためのアプリを作成していました。
    - 古いversionアプリはPythonを使ってアプリケーションが作られていましたが、SDKがAndroidに対応した為、Andriodで開発を行いました。
  - 苦労した点
    - Pepperの開発者自体数が少ない為、公式ドキュメント以外での情報がありませんでした。SKDにもいくつかバグがあり、SKDの制作を行なっているチームと連絡を取りバグ報告やドキュメントに記載されていない不明点を聞き開発を進めました。
