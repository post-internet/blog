# ncc.hateblo.jp
NCCのはてなブログは[blogsync](https://github.com/motemen/blogsync)を用いて書かれています。基本的にはwerckerでbuild, deployされますがローカルからbuild, deployすることもできます。

## こまんど
### エントリのダウンロード(ブログ=>ローカル)
`blogsync pull ncc.hateblo.jp`

### エントリの投稿
`blogsync post ncc.hateblo.jp [投稿する記事のファイル]`

### エントリを書き始める
`blogsync post --draft --title=合宿に行きました ncc.hateblo.jp`

### エントリの更新(ローカル=>ブログ)
`blogsync push [更新する記事のファイル]`

## ToDo
- blogsyncのconfigをもうちょい使いやすくする
