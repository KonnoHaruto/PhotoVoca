# PhotoVoca

[English](README.md) | 日本語

<p align="center">
  <img src="assets/images/photovoca.png" alt="PhotoVoca Logo" width="200"/>
</p>

カメラで撮影した物体を自動認識し、英語の語彙学習に変換するFlutterアプリケーションです。

**🏆 [RSS Hackathon 2025 Beyond "あたりまえ"の、その先へ](https://www.craftstadium.com/hackathon/rss-hackathon-2025-beyond) 優秀賞受賞作品（2025年9月7日）**

## 概要

PhotoVocaは、日常生活の中で目にする物体を撮影するだけで、その英語名と説明文を自動生成し、フラッシュカード形式で語彙学習ができるモバイルアプリです。Google ML Kitによる物体検出とGemini AIによる説明文生成を組み合わせることで、実用的で記憶に残りやすい学習体験を提供します。

## 主な機能

### カメラ撮影と物体認識
- リアルタイムの物体検出（Google ML Kit Object Detection）
- 撮影した物体の自動切り抜き
- 複数の物体から学習したいものを選択可能

### AI による説明文生成
- Gemini AIが物体の英語名と説明文を自動生成
- 文脈に応じた実用的な例文の提供
- 視覚的なイメージと言葉を結びつけた効果的な学習

### フラッシュカード学習
- 撮影した物体がフラッシュカードとして保存
- カードをタップして答えを確認
- スワイプで次のカードへ移動
- 学習履歴の管理

### データ管理
- SQLiteによるローカルデータベース管理
- 学習履歴の永続化
- オフラインでの学習が可能

## 技術スタック

- **フレームワーク**: Flutter
- **状態管理**: Riverpod
- **ルーティング**: go_router
- **AI/ML**:
  - Google Generative AI (Gemini)
  - Google ML Kit Object Detection
- **カメラ**: camera
- **データベース**: Drift (SQLite)
- **画像処理**: image


## 今後の開発予定

- 音声読み上げ機能の追加
- 学習進捗の可視化
- カテゴリー別の語彙管理
- 複数言語対応
- クラウド同期機能

## 貢献

プルリクエストは歓迎します。大きな変更を行う場合は、まずissueを開いて変更内容について議論してください。

## お問い合わせ

ご質問や提案がある場合は、GitHubのissueページからお気軽にお問い合わせください。