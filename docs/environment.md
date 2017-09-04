## Mac

### GNU core utilities(coreutils)の例
1. ターミナルを開く
2. [Homebrew](https://brew.sh/index_ja.html)をインストールする
`$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
3. [coreutils](www.gnu.org/s/coreutils/)をインストールする
`$ brew install coreutils`
4. ターミナルで以下がエラー無く実行できればOK
`$ gls`


MacにはデフォルトでBSD系のコマンドが入っているため、区別するためにcoreutilsのコマンドは頭にgをつけた名前となっています

したがって`ls`は`gls`となります

## Win

### Gnu On Windows(Gow)の例
1. [Gow](https://github.com/bmatzelle/gow/releases)から最新バージョンのインストーラ（例：Gow-0.8.0.exe）をダウンロードし、ダブルクリックしてインストール
（こだわりがなければすべてデフォルトでOK。勝手にパスも通してくれます）
2. コマンドプロンプトを起動し、以下がエラー無く実行できればOK
`$ ls`

