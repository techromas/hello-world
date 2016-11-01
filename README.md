# hello-world
just another repository


## cheet sheet

### what is my name & what is my e-mail address

    $git config --get user.name
    $git config --get user.email

### change my name & change my e-mail address

    $git config --global user.name "romas"
    $git config --global user.email foo.bar@hoge.hoge

### init repository and network

    $git init
    $git remote add origin git@github.com:techromas/hello-world.git
    

### pull repository

    $git fetch
    $git merge --allow-unrelated-histories origin/master

### add to repository

    $git add -A
    $git commit -m "comment"
    $git push origin master

### what is the address of the remote now

    $git remote -v
    
or

    $git config --get remote.origin.url

### change the remote url

    $git remote set-url origin https://github.com/techromas/hello-world.git

### make branch

    $git branch hoge
    
### what branch now I am in

    $git branch

### change branch

    $git checkout hoge

### make and chage branch

    $git checkout -b hoge

## WebGL

study note about webgl. [WebGL_memo](WebGL/memo.md)
