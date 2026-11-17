# Itsuki Tajima — Personal Portfolio

日本語の個人プロフィール／ポートフォリオサイトです。GitHub Pagesで公開できる静的サイトとして作成しています。

## ファイル構成

- `index.html` — ページの文章・構造
- `style.css` — 色・レイアウト・レスポンシブデザイン
- `script.js` — モバイルメニュー・フッター年号
- `assets/` — プロフィール写真や作品画像を置くフォルダ

## GitHub Pagesで公開する方法

1. GitHubで新しいPublicリポジトリを作成（例：`my-portfolio`）。
2. このフォルダ内のファイルと`assets`フォルダを、リポジトリの直下にアップロード。
3. リポジトリの **Settings → Pages** を開く。
4. **Build and deployment** のSourceを `Deploy from a branch` にする。
5. Branchを `main`、Folderを `/ (root)` にしてSave。
6. 数分後、表示されるGitHub PagesのURLでサイトを確認。

## 公開前に必ず編集する箇所

`index.html`を開き、次を自分の最新情報に合わせて修正してください。

- 名前の英語表記・表示名
- 自己紹介文
- インターンや翻訳業務の期間・正式名称・担当範囲
- 大学の在籍状況・学科名
- 語学レベル、TOEICスコア
- メールアドレス `YOUR_EMAIL@example.com`
- SNSリンクの `href="#"` を実際のURLに変更
- 作品の説明、画像、公開可能な範囲

### 写真・作品画像の追加

プロフィール写真を `assets/profile.jpg` という名前で追加し、`index.html`の`.portrait-placeholder`部分を画像表示に置き換えると使えます。作品画像も`assets`に追加して、各作品カードに表示を追加してください。

## 注意

このサイトは会話で共有された情報をもとにした初稿です。期間・役職・実績・語学力などは公開前に本人が確認してください。個人の連絡先や、許可を得ていない企業資料・顧客情報・大学課題の未公開資料は掲載しないでください。
