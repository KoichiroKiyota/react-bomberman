# React Bomberman Game

<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

Reactで作成されたボンバーマンゲームです。GitHub Pagesで公開されており、誰でもブラウザで遊ぶことができます。

## 🎮 ゲームをプレイ

**ライブデモ:** [https://kiyota.github.io/react-bomberman/](https://kiyota.github.io/react-bomberman/)

## 🚀 ローカルで実行

**前提条件:** Node.js

1. 依存関係をインストール:
   ```bash
   npm install
   ```

2. 環境変数を設定（必要に応じて）:
   ```bash
   # .env.localファイルを作成
   echo "GEMINI_API_KEY=your_api_key_here" > .env.local
   ```

3. 開発サーバーを起動:
   ```bash
   npm run dev
   ```

## 📦 ビルドとデプロイ

### 手動デプロイ
```bash
npm run deploy
```

### 自動デプロイ
このプロジェクトはGitHub Actionsを使用して自動的にGitHub Pagesにデプロイされます。`main`ブランチにプッシュすると、自動的にビルドとデプロイが実行されます。

## 🛠️ 技術スタック

- **React 19** - UIライブラリ
- **TypeScript** - 型安全性
- **Vite** - ビルドツール
- **GitHub Pages** - ホスティング
- **GitHub Actions** - CI/CD

## 📁 プロジェクト構造

```
react-bomberman/
├── components/          # Reactコンポーネント
│   ├── Controls.tsx     # ゲームコントロール
│   ├── GameBoard.tsx    # ゲームボード
│   ├── MessageLog.tsx   # メッセージログ
│   └── PlayerStats.tsx  # プレイヤー統計
├── .github/workflows/   # GitHub Actions
├── App.tsx             # メインアプリケーション
├── constants.ts        # 定数定義
├── types.ts           # 型定義
└── vite.config.ts     # Vite設定
```

## 🎯 ゲームの特徴

- リアルタイムゲームプレイ
- レスポンシブデザイン
- モダンなUI/UX
- ブラウザで直接プレイ可能

## 🤝 貢献

プルリクエストやイシューの報告を歓迎します！

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。
