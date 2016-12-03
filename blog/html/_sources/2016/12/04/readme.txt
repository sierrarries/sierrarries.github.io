README
======



.. author:: default
.. categories:: none
.. tags:: none
.. comments::


ブログ記事の作り方

//タイトルを指定して記事を作成
tinker -p "blod title"

//hogehoge.rstファイルが出来るので編集．
//編集後，記事をビルドする
tinker -b

GitHub io にて公開する
//localのソース・ファイルをローカルリポジトリに移す
cp -rf source/html/* sierrarries.github.io/html/

//コミットする
git add .
git commit -m "ここにコメントを書こう"
git push origin master



