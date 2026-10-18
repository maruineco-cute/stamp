# Stamp Studio（スタンプ作成アプリ）

画像から木のハンコを作り、紙に押せるブラウザアプリです。スマホ・タブレットで使えます。

## 公開方法（GitHub Pages）

1. GitHub で新しいリポジトリを作る（例：stamp-studio）
2. このフォルダの中身（index.html、.nojekyll、README.md）をアップロードする
3. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `(root)` にして Save
4. 数分後に `https://<ユーザー名>.github.io/stamp-studio/` で開けます

## 動作環境

- Android Chrome / iPad Chrome（WebGL が使える環境）
- ローカルファイルを直接開く方法では動きません。必ず公開URLで開いてください。

## 機能

- 判子プリセット：❤ ハート、よくできました、極秘、FAILED、肉球
- 画像の読み込み、2値化・トーン化（ディザ・網点）
- 枠（画像に沿う／四角いっぱい）、インクの色
- 紙は白紙、または写真・自作の絵を背景にできる
- 演出（音・インクのにじみ）は初期状態オフ
- 紙の好きなところをタップして押印（ポンボタンは廃止）
- 挑戦：5枚の用紙の枠に押していく時間計測（自己ベストはブラウザに保存）
