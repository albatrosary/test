# test

## testSub をサブモジュールとして定義する

```
git submodule add git@github.com:albatrosary/testSub.git
```

## test をクローンしたとき

```
git clone git@github.com:albatrosary/test.git
git submodule update -i
```

## test で testSub を更新するとき

```
git submodule foreach git pull origin master
```

サブモジュールは`git submodule update -i`を実行したときの状態のモジュールを github から落としてくる  
最新のものが必要な場合はこのコマンドを発行する
