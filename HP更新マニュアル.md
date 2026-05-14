# つながるLab・marippe ホームページ 管理マニュアル

---

## 📍 ホームページの保存場所

```
デスクトップ → my-hp フォルダ
  ├── index.html      ← メインページ
  └── privacy.html    ← プライバシーポリシー
```

---

## 🌐 公開後のURL（GitHub Pages）

```
https://tsunagarulabmarippe414.github.io/my-hp/
```

---

## 🚀 初回公開の手順（最初の1回だけ）

### Step 1｜ターミナルを開く
- Finder →「アプリケーション」→「ユーティリティ」→「ターミナル」

### Step 2｜GitHubにログイン
ターミナルに貼り付けて Enter：
```
gh auth login
```
質問が出たら：
- `GitHub.com` → Enter
- `HTTPS` → Enter
- `Y` → Enter
- `Login with a web browser` → Enter

ブラウザが開いたらコードを入力してログイン完了。

### Step 3｜Claude Code に「公開して」と伝える
ログインできたら、このチャットに「公開して」と送るだけ！
あとはClaudeが全部やります。

---

## ✏️ ホームページを更新する手順

### 方法①｜Claude Code で更新（おすすめ）
1. Claude Code を開く
2. 「ホームページの〇〇を変えて」と伝える
3. 変更を確認したら「公開して」と伝える
4. 完了！URLは変わりません

### 方法②｜自分でファイルを直接編集する場合
1. `デスクトップ → my-hp → index.html` をVS Codeで開く
2. 編集して保存
3. ターミナルで以下を実行：
```
cd ~/Desktop/my-hp
git add .
git commit -m "更新内容のメモ"
git push
```
数分後にURLに反映されます。

---

## 📸 写真を変えたいとき
「ヒーローの写真を〇〇に変えて」とClaude Codeに伝えるだけ。

---

## 🔗 SNSのリンクを変えたいとき
「InstagramのURLを〇〇に変えて」とClaude Codeに伝えるだけ。

---

## 🆘 困ったときは
Claude Code に「ホームページを編集したい」と伝えると、
このプロジェクトのことを覚えているので続きから対応できます。

---

## 📅 更新履歴
変更するたびに自動でgitに保存されます（日時つき）。
「〇日前のバージョンに戻して」とClaude Codeに伝えると戻せます。
