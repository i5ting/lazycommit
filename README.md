# lazycommit

## Install

```
$ [sudo] npm i -g lazycommit
```

## lc

lc = git commit -am 'lazycommmit, please ignore'

## lca

lca = eval git add . && git commit -am 'lazycommmit add file, please ignore'


## ld

ld = git diff

## gs

gs = git status


## version

run in package dir
 
```
v = version

v [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
``` 


## version bump &&  publish

run in package dir
 
```
vp 

vp [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
``` 

## pull 

pull = git pull

## push

push = git push

## publish

p = eval npm publish . ----registry=https://registry.npmjs.org/

## npm alias

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