# Flowerly Friends Collection - Website

Flowerly Friends Collectionの公式ウェブサイトです。

## 📁 プロジェクト構造

```
.
├── content/
│   ├── txt/           # 編集用TXTファイル（セクション順）
│   └── images/        # 画像ファイル（セクション別フォルダ）
├── assets/
│   └── css/
│       └── styles.css
├── index.html         # メインHTMLファイル
└── package.json
```

## 📝 コンテンツ管理

### TXTファイル一覧（セクション順）
`content/txt/` フォルダ内のファイルを編集してコンテンツを管理：

- **01_header.txt** - ヘッダー情報（ヒーローテキスト、主催者、入場料）
- **02_past-events.txt** - これまでのフラコレ
- **03_schedule.txt** - スケジュール
- **04_venue.txt** - 開催場所
- **05_goods.txt** - グッズ販売
- **06_members.txt** - 出展メンバー
- **07_artwork-sales.txt** - 作品販売
- **08_supporters.txt** - 支援者の皆様
- **09_support-goods.txt** - フラコレ応援グッズ
- **10_staff.txt** - 運営メンバー

### 画像フォルダ一覧（セクション順）
`content/images/` フォルダ内に各セクション用の画像を格納：

- **01_header/** - ロゴ、ヒーロー画像
- **02_past-events/** - 過去のイベント写真
- **03_schedule/** - スケジュール関連画像
- **04_venue/** - 会場写真、地図
- **05_goods/** - グッズ商品画像
- **06_members/** - メンバープロフィール画像
- **07_artwork-sales/** - 販売作品画像
- **08_supporters/** - 支援者関連画像
- **09_support-goods/** - 応援グッズ画像
- **10_staff/** - スタッフプロフィール画像

### TXTファイルの記法
```
# セクション名
内容を記述

# 別のセクション
別の内容
```

## 🔄 更新フロー

1. **TXTファイル編集**: `content/txt/01_header.txt` などを編集
2. **画像追加**: 必要に応じて `content/images/01_header/` などに画像を配置
3. **変更報告**: Claude Codeに「01_header.txtを更新しました」と報告
4. **HTML反映**: 自動的に `index.html` に内容が反映される

## 🚀 ローカル確認

### ファイルを直接開く
```bash
open index.html
```

### ローカルサーバーで確認
```bash
npm run serve
# http://localhost:8080 でアクセス
```

## 💡 特徴

- ✅ シンプルな静的HTML
- ✅ TXTファイルで簡単コンテンツ管理
- ✅ Claude Codeによる自動HTML反映
- ✅ サーバー不要で動作
- ✅ 高速表示

## 📋 管理担当

**コンテンツ編集**: ユーザー（TXTファイル編集）
**HTML反映**: Claude Code（自動反映）