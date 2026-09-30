# 社内ナレッジサイト テンプレート

研修で使うフォルダです。このフォルダの中で、Claude Codeを使って社内マニュアルの検索サイトを作ります。

## 中に入っているもの

| 名前 | 何に使うか | 使うコマ |
| --- | --- | --- |
| docs | マニュアルの原本を入れるフォルダ。最初はダミーが4本入っています | 1日目1限から |
| prompts | Claude Codeに送る指示文。番号の順に使います | 各コマ |
| design-sheet.md | サイトの設計を考えるためのシート | 1日目2限 |
| memo-template.md | 自分の業務手順を書き出すためのひな形 | 2日目2限 |
| automation-sheet.md | 自動化できる作業を整理するシート | 2日目4限 |

## ファイルの一覧

ファイル名が読めない記号になっていたら、Claude Codeに「このフォルダのファイル名が文字化けしています。README.md に書かれている名前を参考に、正しい名前に直してください」と送ってください。中身は壊れていません。

- README.md
- design-sheet.md
- memo-template.md
- automation-sheet.md
- docs/経費精算の手順.md
- docs/有給休暇の申請方法.md
- docs/慶弔休暇の申請方法.md
- docs/社内Wi-Fiがつながらないときの対処.md
- prompts/01_動作確認.md
- prompts/02_サイト生成.md
- prompts/03_公開準備.md
- prompts/04_add-doc作成.md
- prompts/05_update-doc作成.md

## 大事な約束

- 研修中は、社外秘の情報を入れないでください。迷ったら入れない
- docs フォルダの中が原本です。サイトの見た目のファイルは、Claude Codeが docs をもとに作り直します
- 困ったら、そのままClaude Codeに「専門用語を使わずに教えて」と聞いて大丈夫です
