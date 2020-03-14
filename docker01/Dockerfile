# ベースイメージ Go言語1.9
FROM golang:1.9

# イメージビルド時のアクション
# main.go配置先のディレクトリを作る
RUN mkdir /echo

# ホストマシンからコンテナ内にコピーするファイル
COPY main.go /echo

# コンテナ実行(run)時にコンテナ内で実行するプロセス
# コマンドを配列で分割
CMD ["go", "run", "/echo/main.go"]
