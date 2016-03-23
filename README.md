# どうかく拡大版用Dickerfile

## 入ってるもの

- ruby
- haskell
- jdk
- rust

(elixirは上手く入らなかった)

## OSX

```sh
$ brew cask install dockertools
$ brew tap codekitchen/dinghy
$ brew install dinghy
$ dinghy create --provider=virtualbox
$ eval $(dinghy shellinit)
$ docker run -v #{codedir}:/doukaku -ti hidenba/doukaku-extention
```
