# コーディングルール

コーディングルールの更新は随時行う。

## プロジェクト管理について

- Git Flow に基づいて行う
- develop ブランチから feature ブランチを派生させる
- デプロイは master から行う
- ブランチの責任は単一にすること（あれこれ詰め込まない）
- ブランチ名は feature/#issue 番号 を頭につける。
- 実験的な意味合いもあるため軽微な修正であっても上記ルールを守ること

## 環境について

- Docker を利用したコンテナ管理
- CI/CD を利用
- Rubocop でコード品質向上

## テストについて

- Rspec を利用する
- 単体テストを可能な限り行うこと(特にモデル関連のテストは必須とする)
- E2E テストについては重要な部分のみ行う
