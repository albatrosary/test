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
