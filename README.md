# latex-docker-vscode

1. vscodeのLaTeX Workshopをインストールする
2. 以下のコマンドを実行
```
git clone git@github.com:2ndr9/latex-docker-vscode.git [project_name] && \
cd [project_name] && \
code .
```
3. texファイルを編集
4. texファイルを保存
5. 自動でビルドされ，pdfが作成される
6. "command + option + v"でpdfのリアルタイムプレビューが表示される



### 備考
docker image(paperist/texlive-ja:latest)がダウンロードされていない初回ビルド時などは，ビルドに少し時間がかかる．

vscodeのRemote - Containersを用いる必要はない．
