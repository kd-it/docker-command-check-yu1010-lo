# ベースイメージとしてbusyboxを使います
FROM busybox
# ルートディレクトリ上にhello.txtを作成します
# hello.txtの中身は"Hello, Docker"です
# ただしイメージ内でhello.txtは作るとします
RUN echo "Hello, Docker" > /hello.txt
CMD cat /hello.txt