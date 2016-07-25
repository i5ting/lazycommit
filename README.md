# lazycommit

## Install

```
$ [sudo] npm i -g lazycommit
```

## lc

没啥意义的提交，请忽略

```
$ lc = git commit -am 'lazycommmit, please ignore'
```

## ld

没啥意义的文档提交，请忽略

```
$ ld = git commit -am 'lazy doc, please ignore'
```

## lca

对于新增文件，git add之后再lc，懒操作

```
$ lca = eval git add . && git commit -am 'lazycommmit add file, please ignore'
```

## gd

git命令别名：查看diff

```
$ ld = git diff
```

## gs

git命令别名：查看状态

```
$ gs = git status
```

## version

版本处理

run in package dir
 
```
v = version

v [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
``` 

## version bump &&  publish

增加版本，并发布

run in package dir
 
```
vp 

vp [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
``` 

## n

快速npm init

```
$ n = npm init -y
```

## pull 

```
$ pull = git pull
```

## push

```
$ push = git push
```

## push tags

把所以tag都推上去

```
$ pt 
```

## publish

发布到npmjs

```
$ p = eval npm publish . ----registry=https://registry.npmjs.org/
```

## npm alias

npm别名

```
alias ni='npm install'
alias nis='npm install --save'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias nf='npm cache clean && rm -rf node_modules && npm install'
```