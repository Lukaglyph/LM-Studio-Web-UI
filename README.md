🌌LM Studio Web UI
<img width="1246" height="680" alt="スクリーンショット 2026-02-17 201256" src="https://github.com/user-attachments/assets/958abfce-2dd9-4948-8ab7-69b53daf8ac1" />

LM Studioで稼働するローカルLLMを、ブラウザから操作するためのWEBインターフェースです。
アイコンや背景のカスタマイズ、会話履歴のローカル保存に対応しています。

🚀 主な機能

    ローカルLLM連携: LM StudioのAPIサーバーを利用したプライベートなチャット環境。

    コンテキスト保持: 直近の会話履歴（最大10件）をAIに送信し、文脈に沿った対話が可能。

    カスタマイズ: サイドパネルからAIのアイコン、ユーザーのアイコン、カード型背景画像を即座に変更可能。

🛠️ セットアップ
1. LM Studio の準備

    LM Studioを起動し、使用したいモデルをロードします。

    左メニューの 「Local Server」 アイコンをクリック。

    「Start Server」 をクリックしてサーバーを起動します（デフォルト：localhost:1234）。

    重要: 設定パネルの 「Cross-Origin Resource Sharing (CORS)」 を必ず ON にしてください。

2. インストール

    このリポジトリをクローンするか、index.html をダウンロードします。
    Bash

    git clone https://github.com/Lukaglyph/LM-Studio-Web-UI.git

    index.html をブラウザで開くだけで準備完了です（サーバーやビルド作業は不要です）。

⚙️ カスタマイズ項目

サイドパネル（CONFIGURATION）から以下の設定が可能です：
項目	説明
BOT ICON URL	AIのアイコン画像URL
USER ICON URL	あなたのアイコン画像URL
BOT CARD IMAGE	AIメッセージの背面に薄く表示される背景画像URL

⚠️ 注意事項

    このプロジェクトはブラウザの LocalStorage を使用してデータを保存します。ブラウザのキャッシュをクリアすると、履歴や設定も削除されます。

    LM Studioが起動していない場合、メッセージの送信に失敗します。

📝 ライセンス

MIT License

Author: Lukaglyph
