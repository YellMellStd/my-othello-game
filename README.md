# 🎯 オセロゲーム / Othello Game

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="MIT License">
</p>

<p align="center">
  <strong>シンプルで美しいブラウザベースのオセロゲーム</strong><br>
  A simple and beautiful browser-based Othello (Reversi) game
</p>

---

## 🎮 デモ / Demo

[こちらでプレイできます / Play it here](https://yellmellstd.github.io/my-othello-game/)

## 📷 スクリーンショット / Screenshot

<p align="center">
  <img src="https://github.com/user-attachments/assets/d698eeff-0d2e-40f1-b3b7-fb1b5d8926a8" alt="Othello Game Screenshot" width="600">
</p>

## ✨ 特徴 / Features

- 🎨 **美しいUI** - ダークテーマでモダンなデザイン
- 🎯 **有効手のヒント表示** - オレンジ色のドットで次に置ける場所を表示
- 📊 **リアルタイムスコア** - 黒と白の石の数を常に表示
- 🔄 **スムーズなアニメーション** - 石の配置と反転が滑らかに動作
- 📱 **レスポンシブデザイン** - どのデバイスでも快適にプレイ可能
- 🚀 **軽量** - 外部ライブラリ不使用、純粋なHTML/CSS/JavaScript

## 🎯 遊び方 / How to Play

1. **ゲームの目的**
   - 盤面により多くの自分の色の石を置くことが目的です

2. **基本ルール**
   - 黒が先手です
   - 相手の石を挟むように石を置きます
   - 挟まれた相手の石は自分の色に変わります
   - 置ける場所がない場合はパスとなります

3. **操作方法**
   - オレンジ色の点が表示されている場所をクリックして石を置きます
   - 「ゲームをリセット」ボタンで新しいゲームを開始できます

## 🚀 使い方 / Getting Started

### オンラインでプレイ

GitHub Pagesで公開されているバージョンをプレイできます：
[https://yellmellstd.github.io/my-othello-game/](https://yellmellstd.github.io/my-othello-game/)

### ローカルでプレイ

1. リポジトリをクローン
```bash
git clone https://github.com/YellMellStd/my-othello-game.git
cd my-othello-game
```

2. ブラウザで開く
```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

または、ファイルをブラウザにドラッグ＆ドロップしてください。

## 🛠️ 技術仕様 / Technical Details

- **純粋なWeb技術**: HTMLとCSS、JavaScriptのみで実装
- **グリッドレイアウト**: CSS Gridを使用した8×8のゲームボード
- **イベント駆動**: クリックイベントによる対話的なゲームプレイ
- **アルゴリズム**: 
  - 有効手の判定
  - 石の反転処理
  - ゲーム終了判定

## 📁 プロジェクト構成 / Project Structure

```
othello-game/
├── index.html      # メインのHTMLファイル（ゲーム本体）
├── README.md       # このファイル
├── LICENSE         # MITライセンス
└── .gitignore      # Git除外設定
```

## 🤝 貢献 / Contributing

プルリクエストを歓迎します！大きな変更の場合は、まずissueを作成して変更内容を議論してください。

1. フォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/AmazingFeature`)
3. 変更をコミット (`git commit -m 'Add some AmazingFeature'`)
4. ブランチにプッシュ (`git push origin feature/AmazingFeature`)
5. プルリクエストを作成

## 📝 ライセンス / License

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルをご覧ください。

## 🙏 謝辞 / Acknowledgments

- オセロ（リバーシ）は長谷川五郎氏によって考案されたボードゲームです
- このプロジェクトは教育目的で作成されました

---

<p align="center">
  Made with by [YellowMellowStudio]
</p>
