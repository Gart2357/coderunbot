# CodeRunBot
コードの実行や LaTeX の画像化ができます．

公式 Discord サーバーはこちら．（予定）

使い方は[こちら](https://coderunbot.gart.page/ja/)．

It can run codes and image LaTeX.

Here is the official discord server. (plan)

[Here](https://coderunbot.gart.page/en/) is how to use.

## 必要要件 Requirements
- Linux or macOS
- Nim
- TexLive
- Poppler (pdftoppm)
- ImageMagick (convert)

## 実行方法 How to run it
```
$ git clone git@github.com:Gart2357/coderunbot.git
$ cd coderunbot
$ nimble build -d:ssl
$ ./coderunbot
```