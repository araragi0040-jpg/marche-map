# Marche CAD Map Demo

マルシェ・イベント向けのスマホWebマップアプリのデモ版です。

## 公開方法

### Vercelで公開する場合

1. GitHubで新規リポジトリを作成
2. このフォルダ内の `index.html` をアップロード
3. Vercelで GitHub リポジトリを Import
4. Framework Preset は `Other` または未指定でOK
5. Deploy

### GitHub Pagesで公開する場合

1. GitHubで新規リポジトリを作成
2. このフォルダ内の `index.html` と `.nojekyll` をアップロード
3. Settings → Pages
4. Source を `Deploy from a branch` にする
5. Branch を `main` / `/root` にする
6. Save

## 編集権限

デモ用パスコード：

```txt
marche2026
```

URLパラメータで編集権限を付与する場合：

```txt
?adminKey=marche2026
```

本番では、この方式は簡易的なものです。ニュースサイト側のログインや管理者権限と連動させる場合は、別途認証設計を行ってください。

## 改善運用

- issueで改善要望を管理
- `main` は公開用
- 修正は別ブランチで作業
- VercelのPreview URLで確認
- 問題なければmainへ反映

## 次の拡張候補

- 出店者データをJSONファイル分離
- Googleスプレッドシート連動
- ニュースサイトログイン連動
- 管理者のみ編集画面表示
- 複数イベント対応
- アンケート集計連動
