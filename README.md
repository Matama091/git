# git
I don't know how to use git, so I want to summarize it

## Versionの確認  
`$ git --version`  

##  初期設定
ユーザー名とメールアドレスを設定することでコミットした際に誰がしたかわかる    
`$ git config --global user.name "ユーザー名"`  
`$ git config --global user.email "メールアドレス"`  

## リモートリポジトリの作成
- Githubのサイト  
Githubのヘッダー右上にある「+」の「New repository」を選択し作成  

- Terminal  
`$ mkdir mysite`  
`$ cd mysite`  
`$ git init`  

- Githubのサイト  
httpsから始まる1行をコピー  

- terminal  
`$ git remote add origin <URL>`  

## Push  
プッシュするためにファイルを作成してコミットする  
`$ touch index.html`  
`$ git add index.html`  
`$ git commit -m "Create index.html"`  
`$ git push origin main`  

## Githubで確認

## Branchの作成・移動  
`$ git checkout -b <branchname>`

# 参考  
[Gitの環境構築](https://prog-8.com/docs/git-env)  
