---
layout: default
title: git(コマンド)の設定
---

___
## ■ git環境の初期設定

```
git config --global user.name [GitアカウントID]
git config --global user.email [GitアカウントMailアドレス]
```


gitコマンドの基本ブランチ(git initで作成されるブランチ名)を設定する。  
```
git config --global init.defaultBranch [ブランチ名]
```

>mainもしくはmasterが推奨。  
>初期の頃はmasterだったが徐々にmainに移行しつつあるらしい。 



___
## ■ 