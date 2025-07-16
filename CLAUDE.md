# Claude Code 設定ファイル

## プロジェクト概要
- プロジェクト名: Flowerly Friends Collection 特設サイト
- 開発環境: HTML/CSS/JavaScript
- ログ管理: `/Users/endouyuuki/Projects/new-website/logs/development-log.md`

## 作業フロー設定

### 「save」トリガー処理
ユーザーが「save」というワードを使用した場合、以下の順序で自動実行：

1. **ログ更新**
   - 実行した作業内容を `/Users/endouyuuki/Projects/new-website/logs/development-log.md` に記録
   - 変更ファイル、技術詳細、実装内容を詳細に記載

2. **Git処理**
   - `git status` で変更状況確認
   - `git diff` で変更内容確認
   - `git add` で変更ファイルをステージング
   - `git commit` で適切なコミットメッセージ付きでコミット
   - `git push origin main` でリモートリポジトリにプッシュ

3. **確認**
   - 各処理の完了状況を報告

### コミットメッセージ形式
```
簡潔な変更概要

- 主要な変更点1
- 主要な変更点2
- 主要な変更点3

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude <noreply@anthropic.com>
```

## ファイル構成
```
/ワイヤーフレーム/
├── index.html                # メインファイル
├── content/
│   ├── images/              # 画像ファイル
│   └── txt/                 # コンテンツ管理用txtファイル
└── logs/                    # 開発ログ（親ディレクトリ）
    └── development-log.md
```

## 注意事項
- コミット前には必ずログ更新を行う
- txtファイルの内容変更時はHTMLに反映
- 非表示セクションも含めて全ファイル保持
- レスポンシブ対応を常に考慮