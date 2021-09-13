# kyopuro

## kp

g++ による C++ のコンパイルと実行を同時に行うだけの shellscript

kp は競技プログラミング (kyougi puroguramingu) の略です。
(competitive programming だと cp と重なってしまうので kp にしました)

Linux の bash で動きます。

### 導入

適当なディレクトリにクローンします。

```sh
git clone https://github.com/card-board01/kyopuro
```

そこにパスを通します。
ここでは home directory にクローンしてきたとします。
~/.bash_profile に次のように追記します。

```sh
export PATH="$PATH:$HOME/kyopuro"
```

### 使用法

例えば a.cpp をコンパイルして実行したい時は

```sh
kp a.cpp
```

とするだけで行けるはずです。生成されるバイナリは常に a というファイル名にしています。
2 回目以降は <code>./a</code> とだけ打てばよいです。

### 更新履歴とか

- [2021/09/13] README 作成
