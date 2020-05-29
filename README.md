# これは何

git で merge したときにコンフリクトが起きた場合に、練習するためのサンドボックスです。

# 使い方

以下のコマンドを実行すると コンフリクトが発生した状態になります。

```
$ bin/restart
```

そのままテキストエディタでコンフリクトを修正したり、
`git mergetool` の挙動を確認するのに利用してください。

よくわからなくなってしまったら再度

```
$ bin/restart
```

を実行することでやりなおすことができるようになっています。


# 解決方法

```
git add .
```

```
git commit -m '<適当なメッセージを入力してみる>'
```

これで現在は解決していますが、途中で様々なコマンドを実行しているので上記のコマンドで解決するとは限らないと考えています。