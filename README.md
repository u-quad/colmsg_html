**ENGLISH ===================**

This program creates HTML files for viewing colmsg files in a chat-style interface.

## Features

- Chat-style UI with avatar images
- Month selector to switch between different months
- Support for text messages, images (jpg), and videos (mp4)
- Lazy loading for videos to improve performance
- Responsive design with embedded CSS styling

## Usage

For example, if you save the colmsg files in below folders:

  **C:\Prog\colmsg\data\日木坂26\白石七瀬**
  
  **C:\Prog\colmsg\data\日木坂26\加藤京子**

and you want to create HTML files in below folder

  **C:\Prog\colmsg\html\日木坂26**

Then you will run the program in the command line:  

  **colmsg_html "C:\Prog\colmsg\data\日木坂26" "C:\Prog\colmsg\html\日木坂26" "your_nickname" "icon.jpeg"**

Then you will find the HTML files (one per member) in the output folder:

**C:\Prog\colmsg\html\日木坂26\日木坂26-白石七瀬.html**

**C:\Prog\colmsg\html\日木坂26\日木坂26-加藤京子.html**

Each HTML file contains all messages from all months, with a month selector at the top to switch between different months.

## Parameters

1. **INPUT PATH** (required): The folder where the source colmsg files are located by group level
2. **OUTPUT PATH** (required): The folder where you want to store the generated HTML files
3. **NICK NAME** (optional): Your nick name, or how you want the member to call you. Default: **としくん**
4. **AVATAR IMAGE PATH** (optional): Path to the member's icon image file. Default: **icon.jpeg**

## Note

- CSS styles are embedded directly in the HTML files, so the generated HTML files are self-contained and can be placed anywhere.
- If you want to run the program in a script, remember to add **chcp 65001** to recognize unicode characters.  (see **run_demo.cmd**)


**日本語 ===================**

このプログラムは、colmsgファイルをチャット風のインターフェースで表示するHTMLファイルを作成します。

## 機能

- アバター画像付きのチャット風UI
- 月別セレクターで異なる月のメッセージを切り替え可能
- テキストメッセージ、画像（jpg）、動画（mp4）に対応
- 動画のLazy loading機能でパフォーマンスを向上
- 埋め込みCSSスタイルによるレスポンシブデザイン

## 使用方法

例えば、colmsgファイルを以下のフォルダーに保存した場合：

**C:\Prog\colmsg\data\日木坂26\白石七瀬**

**C:\Prog\colmsg\data\日木坂26\加藤京子**

そして、HTMLファイルを以下のフォルダーに作成したい場合：

**C:\Prog\colmsg\html\日木坂26**

次に、コマンドラインでプログラムを実行します：

**colmsg_html "C:\Prog\colmsg\data\日木坂26" "C:\Prog\colmsg\html\日木坂26" "あなたのニックネーム" "icon.jpeg"**

その後、出力フォルダーにメンバーごとのHTMLファイルが作成されます：

**C:\Prog\colmsg\html\日木坂26\日木坂26-白石七瀬.html**

**C:\Prog\colmsg\html\日木坂26\日木坂26-加藤京子.html**

各HTMLファイルには全ての月のメッセージが含まれており、上部の月別セレクターで異なる月を切り替えることができます。

## パラメータ

1. **INPUT PATH**（必須）：colmsgのソースファイルが保存されているフォルダー（グループレベル）
2. **OUTPUT PATH**（必須）：生成されたHTMLファイルを保存するフォルダー
3. **NICK NAME**（任意）：あなたのニックネーム、またはメンバーにあなたをどう呼んでほしいか。デフォルト：**としくん**
4. **AVATAR IMAGE PATH**（任意）：メンバーアイコン画像ファイルへのパス。デフォルト：**icon.jpeg**

## 注意事項

- スクリプトでプログラムを実行したい場合は、Unicode文字を認識するために **chcp 65001** を追加することを忘れないでください。（**run_demo.cmd**を参照）


