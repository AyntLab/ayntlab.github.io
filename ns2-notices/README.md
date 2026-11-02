# NS2 タイトル画面のお知らせ

ゲームに表示する本文は、次の2ファイルを編集してください。

- `title_jp.txt`：日本語
- `title_en.txt`：英語

UTF-8のプレーンテキストです。見出しも含め、書いた内容がそのままお知らせになります。改行・空行も使えます。
GitHubの編集画面で変更し、`main`にコミットしてください。ゲームはタイトル画面を開いたときに各言語のファイルを取得します。

取得先：

- https://raw.githubusercontent.com/AyntLab/ayntlab.github.io/main/ns2-notices/title_jp.txt
- https://raw.githubusercontent.com/AyntLab/ayntlab.github.io/main/ns2-notices/title_en.txt

ゲームはGitHubのRawファイルを直接取得するので、GitHub Pagesのビルド・デプロイ成功は必要ありません。
