# スゴロク対戦バトル 「バトすご」

## 企画概要
- 2年生向けのオブジェクト指向、設計、テスト、ネットワークの学習用プロジェクト
- コマやマス目をオブジェクトで設計。コマに多彩な動作を仕込みつつ、拡張性を確保
- マスの各種動作を単体テスト
- プレイヤーの動きをサイコロの目をテストで疑似的に出してテスト
- 多人数プレイができるようにプレイヤーやターンを導入
- NPCの実装
- ネット対戦のためのデータベース、通信プロトコルの設計、実装

## 実装環境
- プロジェクト名 BatSgo2020LTS
- Unity2020LTS
- WebGL

## 対象ユーザー
- GitHubの基本操作を理解している
- Unityの基本操作を理解している
- C#で変数、計算、分岐、繰り返しなどを理解している

## 実装フェーズ
- フェーズ１：一人用すごろくで基本設計と線形リストとテスト
- フェーズ２：ポリモーフィズムでマスに進行ルールを入れる
- フェーズ３：バトル要素追加。プレイヤーとマスに戦闘用のパラメーターを設定。戦闘の実装。管理しやすいデータ設計と実装
- 応用１：収穫物の実装でゲーム性向上。経験値、レベルアップ、アイテム入手
- 応用２：多人数プレイに拡張
- 応用３：NPCの実装
- 応用４：ネット対戦。データベースの設計とサーバサイドプログラミング

## 素材調査
- [https://assetstore.unity.com/packages/3d/props/free-little-games-asset-pack-125089](https://assetstore.unity.com/packages/3d/props/free-little-games-asset-pack-125089)
- [https://assetstore.unity.com/packages/templates/packs/dice-pack-light-165](https://assetstore.unity.com/packages/templates/packs/dice-pack-light-165)
- [https://kenney.nl/assets/boardgame-pack](https://kenney.nl/assets/boardgame-pack)

## License
MIT Licenseの予定
