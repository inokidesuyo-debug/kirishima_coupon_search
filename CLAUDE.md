# よっちゃん検索 — Claude 作業ルール

## デプロイフロー

このプロジェクトは GitHub Pages（main ブランチ）で公開している。

修正依頼を受けたときの手順：

1. `index.html` を編集
2. `git add index.html` → `git commit` を自動実行
3. push する前にユーザーに確認を求める
4. 承認されたら `git push origin main` を実行
5. GitHub Pages が自動で再デプロイされる（数十秒〜1分）

## コミットメッセージの形式

```
修正: <何を変えたかを一言で>
```

例: `修正: 国分エリアのカフェ数件を追加`

## 注意

- push は必ずユーザー確認後に行うこと
- 店舗データは `index.html` 内の `const shops = [...]` に直接埋め込まれている
