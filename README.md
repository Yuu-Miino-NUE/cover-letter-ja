# 送付状 TeX テンプレート

## 依存環境
TeX Live が入っていれば問題なく動作するはずです．

### ドキュメントクラス
* jsclasses
    * platex
    * dvipdfmx

### パッケージ
* geometry
* latexmk

## 使い方

1. `contents.tex` を編集する
2. `latexmk cover_letter` を実行する
3. `out` ディレクトリに `cover_letter.pdf` が生成される

## コマンド・環境の説明

| コマンド | 説明 |
|:--|:--|
| `\toAddress` | 送付先の住所 |
| `\fromAddress` | 差出人の住所 |
| `\issueDate` | 日付 |
| `\subject` | 件名 |
| `\body` | 本文 |

| 環境 | 説明 |
|:--|:--|
| `encl` | 添付書類の列挙 |

