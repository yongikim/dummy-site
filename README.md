# dummy-site

GitHub Pagesの検証用リポジトリ。
docs以下が公開されている。

## 手順

### GitHub側の設定
リポジトリの設定ページでpagesの設定画面を開き、公開元をmainブランチの/docsディレクトリに設定する。

カスタムドメインをmechbiosys.me.es.osaka-u.ac.jpに設定する。

Enforce HTTPSにチェックを入れる。

### ドメイン管理側の設定

ドメインの管理ページでCNAMEレコードを作成する。

|            ホスト名            | タイプ |  TTL  |        データ         |
| :----------------------------: | :----: | :---: | :-------------------: |
| mechbiosys.me.es.osaka-u.ac.jp | CNAME  | 1時間 | aoiosakalab.github.io |

以上の手順で、mechbiosys.me.es.osaka-u.ac.jpに/docs/index.htmlが公開される。
