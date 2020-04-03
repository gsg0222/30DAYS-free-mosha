srcフォルダに開発用のコードが、distフォルダに公開用のフォルダが入っています。
開発環境はエディタにVS Codeを、sassのコンパイルや各種ファイルの圧縮にGulpを使いました。
Gitとnpmがインストールされた環境であれば、以下の手順で私の開発環境を再現できます。

・任意のフォルダに移動
$ git clone https://github.com/gsg0222/30DAYS-free-mosha.git
$ cd 30DAYS-free-mosha
$ npm install
$ gulp
