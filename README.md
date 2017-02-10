# hello-world

githubへのHello World!!  
メモ書きのようなもの

## cheet sheet

### 現在の自分の名前とメールアドレスを確認
    
    $git config --get user.name
    $git config --get user.email

### 自分の名前とメールアドレスをromasとfoo.bar@hoge.hogeとして設定

    $git config --global user.name "romas"
    $git config --global user.email foo.bar@hoge.hoge

### リポジトリを作成してリモートを設定する
    
    $git init
    $git remote add origin git@github.com:techromas/hello-world.git
    
### リポジトリをpullする
    
    $git fetch
    $git merge --allow-unrelated-histories origin/master

``--allow-unrelated-histories``は必要に応じて書く

### リポジトリにファイルを追加する

    $git add -A
    $git commit -m "comment"
    $git push origin master

### 今のリモートリポジトリの場所を表示する

    $git remote -v
    
or

    $git config --get remote.origin.url

### リモートリポジトリのURLを変更する
    
    $git remote set-url origin https://github.com/techromas/hello-world.git

### hogeと言う名前のブランチを作る
    
    $git branch hoge
    
### 自分が現在居るブランチを表示
    
    $git branch

### ブランチをhogeブランチに移る

    $git checkout hoge

### 新規ブランチとしてhogeブランチを作成し移る

    $git checkout -b hoge

### hogeブランチを消す

    $git branch -d hoge

### 存在する全てのブランチを表示

    $git branch -a

## WebGL

study note about webgl. [WebGL_memo](WebGL/memo.md)
