# latex-docker-vscode

1. dockerをインストールする
2. vscodeのLaTeX Workshopをインストールする
3. 以下のコマンドを実行
```
git clone git@github.com:2ndr9/latex-docker-vscode.git [project_name] && \
cd [project_name] && \
code .
```
4. texファイルを編集
5. texファイルを保存
6. 自動でビルドされ，pdfが作成される
7. "command + option + v"でpdfのリアルタイムプレビューが表示される



### 備考
docker image(paperist/texlive-ja:latest)がダウンロードされていない初回ビルド時などは，ビルドに少し時間がかかる．

vscodeのRemote - Containersを用いる必要はない．

現時点では，texファイルと.latexmkrcファイルを同じディレクトリに置く必要がある