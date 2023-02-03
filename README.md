# latex-docker-vscode

1. docker をインストールする
2. vscode の LaTeX Workshop をインストールする
3. 以下のコマンドを実行

```
git clone git@github.com:2ndr9/latex-docker-vscode.git [project_name] && \
cd [project_name] && \
code .
```

4. tex ファイルを編集
5. tex ファイルを保存
6. 自動でビルド&フォーマットされ，pdf が作成される
7. "command + option + v"で pdf のリアルタイムプレビューが表示される

### 備考

docker image がダウンロードされていない初回ビルド時などは，ビルドに少し時間がかかる．

vscode の Remote - Containers を用いる必要はない．

現時点では，tex ファイルと.latexmkrc ファイルを同じディレクトリに置く必要がある
