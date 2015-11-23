# python001
Githubまとめ
##Githubにアカウントを作成
https://github.com/
  
##ローカルへGitをインストール
http://git-scm.com/book/ja/v2/使い始める-Gitのインストール
  
##ローカルで公開鍵を作成する
```Bash:sample
$ ssh-keygen
```
  
SSH鍵がローカルの$HOME/.ssh/にできる。
 
##Githubに公開鍵を登録
GitHubの「AccountSetting」にある「SSH Keys」から登録
  
##Githubにリポジトリを作成する
「create a new repo」のボタンからリポジトリを作成

##ローカルでファイルを作成、リポジトリーにpush
https://github.com/oosawak/python001
```Bash:sample
$ echo "# python001" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/oosawak/python001.git
$ git push -u origin master
```

##github for mac
https://desktop.github.com/
