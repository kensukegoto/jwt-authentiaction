# JWT

- サーバーが吐き出されるトークンに自分が誰かのユーザー情報を持つ。
- クライアントはトークンを持ってサーバーにリクエストを飛ばす。
- サーバーでトークンの検証。自分が発行したものかどうか。
- このアプリではROOTとGUESTの２つのトークンのみ発行される。