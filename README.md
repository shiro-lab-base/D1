# DEVIL'S GAME 1 (D1)

96/46 ORIGINAL PLAYING DECK のブラウザゲーム開発用リポジトリ。

## 現段階

- 横画面を前提とした、一人称視点テーブルの仮レイアウトのみ。
- **配札・役判定・ターン進行・CPU・オンライン対戦は未実装**。
- `index.html` を VS Code の Live Server で開いて表示を確認できる。
- CSS は見た目、JS は機能別に分割。確定ルールを確認しながら段階的に実装する。

## ファイル構成

- `css/style.css`: 基本デザイン
- `css/layout.css`: レスポンシブ・横画面案内
- `css/animation.css`: 演出用
- `js/rules.js`: 役とルール（予定）
- `js/deck.js`: デック・配札（予定）
- `js/game.js`: ゲーム進行（予定）
- `js/cpu.js`: CPUの意思決定（予定）
- `js/online.js`: オンライン通信（予定）
- `js/ui.js`: UI表示（予定）
- `js/main.js`: 起動処理（予定）
- `assets/`, `audio/`: 後で素材を追加

初期構成を作るための雛形であり、ゲーム仕様を確定・変更するものではありません。
