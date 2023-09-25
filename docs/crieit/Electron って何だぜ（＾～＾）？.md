# 📅 (2023-09-24 sun)

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　電子だろ」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　👇　フレームワークだぜ」  

📖　[Build cross-platform desktop apps with JavaScript, HTML, and CSS](https://www.electronjs.org/)  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　Web のスキルで　デスクトップ・アプリを作れんの？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　興味は引かないが　とりあえずインストールしてみるかだぜ」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　うーん？　環境が分からん、これ　Node.JS　なのかだぜ？  
また今度にしようぜ」

## Node.JS を入れろだぜ

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👇　ノード・ジェイエスってまだ生き残ってるんだな。人気が根強いんだな」  

📖　[Node.JS](https://nodejs.org/ja)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　どうせ遊びだから　ＬＴＳは気にせず　最新版で行こう」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　Chocolatey をインストールするためにパソコンを再起動しろと出てきたが、  
嫌だぜ」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　Node.JS はインストールできたのか？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👇　Visual Studio Code のウィンドウを全て閉じて開き直し、ターミナルへ打鍵」  

```shell
# Command Prompt

node --version
v20.7.0
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👆　インストールできてるぜ」  

## Electron を入れろだぜ

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　👇　じゃあ Electron を入れろだぜ」  

```shell
npm install --save-dev electron@latest
```

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　なんか　19 パッケージ　インストールされたし、インストールできたんじゃないか？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　次何したらいいか分からん」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　Electron のホームページに　でかでかと書いてある　`Electron Fiddle`　をインストールしたらいいんじゃないの？」  

## Fiddle をインストールしろだぜ

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　👇　じゃあ Fiddle を入れろだぜ」  

📖　[fiddle](https://www.electronjs.org/fiddle)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　インストールは要らないのか、ダウンロードしたら  
デスクトップ・アプリケーションが出てきたぜ」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　Fiddle は Electron で　できてんじゃないの？　知らんけど」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　適当に　Run　ボタン押したら　デスクトップ・アプリケーションのようなものが  
出てきたぜ」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　じゃあ　デスクトップ・アプリケーションなんだろ」

# 📅 (2023-09-25 mon) Electron を調べろだぜ

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　昨日ダウンロードした Fiddle 、どうやって起動すんの？」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　Windows のいつものランチャーから起動できないのかだぜ？」  

![202309__electron__25-1646--start.png](https://crieit.now.sh/upload_images/4af95115a6a9b24e06b958e63c665bc865113b0f0ecb7.png)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👆　おー、あるな」  

![202309_shogi_24-1648--fiddle.png](https://crieit.now.sh/upload_images/acf8b0b71eed51c6d5205c36a087bf0865113b957d2d7.png)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👆　しかし　Fiddle　の画面見ても何にも分かんないな」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　`Run` ボタンを押してみなさいよ」  

![202309_shogi_24-1651--desktop.png](https://crieit.now.sh/upload_images/89228092d4eaca8519fdca32e51d4ff365113c12caec4.png)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👆　デスクトップ・アプリのようなものが出てきたぜ」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　その　**デスクトップ・アプリのようなもの**　は何ができんの？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　`Hello World!` と書いてるだけで、別に」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　何ができるのか分からないのでは、なんともなあ？」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　マイクロ・ゲームでも作ったらどうなの？」

# 挑戦No.1 画像の表示

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　👇　32 x 32 pixel で、アットマークの画像を作ったから、これを画面に表示しなさい？」

![202309_shogi_24-1658--atmark.png](https://crieit.now.sh/upload_images/37b98f7ae181fbdc3381c02aa9911a9465113e2e68213.png)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　ローグをやろうってのか。著作権は大丈夫か……」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　画像の背景を透過しなくていいのかだぜ？」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　細かいことは　全部抜きで」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　しかし　どうやって　画像を表示するのか……。  
Web 系なら　サーバーにファイルを置かないといけないだろ？」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　Fiddle は Electron で作られてるんだろ。  
Electron は Node.JS でインストールしたな。  
じゃあ　Node.JS が Web サーバーとして起動するんだろ。  
Node.JS の作法を調べろだぜ」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　ググると　Qiita の低スキルレベルのクソ記事が　うじゃうじゃ出てきてしまって　わたしの思考の邪魔をする……、  
👇　公式のドキュメントを読むか」  

📖　[Electron とは何ですか?](https://www.electronjs.org/ja/docs/latest/)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👆　恐ろしいほど　知りたいことが見つからないな」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　この　`Hello World!`　の `index.html` ファイルは　Windows のどのディレクトリーに置いてあんの？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　何も分からないぜ」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　Windows のいつものメニューから辿れだぜ」  

![202309_shogi_25-1715--AppData-o2o0.png](https://crieit.now.sh/upload_images/186b832dc46d6d9d686bb1491f5b5190651141f7c6515.png)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　👆　アプリケーション・データのフォルダーに入ってるぜ」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　じゃあ　ディレクトリーなんか触んな、っつーこと？」  

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　フォルダ―は作れないのかだぜ？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　このチンケな開発環境の意味が分からない……」  

![ohkina-hiyoko-futsu2.png](https://crieit.now.sh/upload_images/96fb09724c3ce40ee0861a0fd1da563d61daf8a09d9bc.png)  
「　サンプル・プログラムのソースを探してみたらどうかしら？」  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　分からん。何もできん」

## PNG ではなく BASE64 を使う

![kifuwarabe-futsu.png](https://crieit.now.sh/upload_images/beaf94b260ae2602ca8cf7f5bbc769c261daf8686dbda.png)  
「　👇　PNG ではなく BASE64 を使うそうだぜ」  

📖　[Select and display an image from the filesystem with electron](https://stackoverflow.com/questions/50781741/select-and-display-an-image-from-the-filesystem-with-electron)  

![ramen-tabero-futsu2.png](https://crieit.now.sh/upload_images/d27ea8dcfad541918d9094b9aed83e7d61daf8532bbbe.png)  
「　エレクトロンで画像処理する気が起きないな。別のフレームワークを探そうぜ？」