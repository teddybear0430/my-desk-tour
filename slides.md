---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# My Desk Tour

---

# まいですく
<img src="/my-desk.JPG" alt="マイデスク">

<style>
img {
  width: 500px;
  height: auto;
}
</style>
---

# おしまい

<img src="/animal-dance.png" alt="動物のイラスト">

<style>
img {
  width: 500px;
  height: auto;
}
</style>

---

# 紹介できるマイデスクがないので、今回は......

---

# 自分の開発環境について話します

<img src="/using-tools.png" alt="主な使用ツール">

<style>
img {
  width: 640px;
  height: auto;
}
</style>
---

# 開発をする際に主に使用しているツール

- Neovim（エディター）
- tmux（ターミナルマルチプレクサ）
- iTerm2（ターミナル）
- fish（シェル）
- ag (検索能力を強化するために使用)
- glow（markdownのプレビュー）
- tig（CUIでGit操作ができる）

---

# Neovim
<p>VimをフォークしてできたOSS。VimScript以外の言語（Lua、Python、Node.js、Golangなど）を使用したカスタマイズができることもあって、オリジナルのVimよりもプラグインが豊富。<br />
パフォーマンス面に関しても、Luaのランタイムを組み込むことによって、VimScriptの実行速度が遅いという問題を解決している。</p>

<img src="/nvim.png" alt="nvim">

<style>
p {
  font-size: 16px;
}
img {
  width: 500px;
  height: auto;
}
</style>
---

# tmux
<p>ターミナルマルチプレクサと呼ばれるツールの一種。<br />一つのターミナルで画面分割や切り替えなどができるという特徴がある。</p>

- ウィンドウをタブのように管理できる
- マウスを使わず端末内でコピペできる
- tmux.confと呼ばれる設定ファイルを使用することで、表示を自由にカスタマイズすることができる

<style>
p {
  font-size: 16px;
}
</style>
---

# iTerm2
<p>macでデフォルトで入っているターミナルよりもカスタマイズ性が高く、機能も豊富なターミナル。</p>

- フォント・・・Ricty Diminished, Hack Nerd Font
- テーマ・・・<a href="https://github.com/JuanKman94/tron-contrib">tron-contrib</a>

<style>
p {
  font-size: 16px;
}
</style>
---

# fish
<p>シェルの一種。bashやzshなどよく使われるシェルとの相違点は以下。</p>

- コマンドの補完が効く
- 見た目がbashやzshよりおしゃれ

<img src="/fish.png" alt="" class="img">

<style>
p {
  font-size: 16px;
}
img {
  width: 500px;
  height: auto;
}
.img {
  display: block;
  margin-top: 12px;
}
</style>
---

# ag
<p>grepのようにファイルから文字列を検索することができるツール。<br />grepよりも高速に動作するため、大量のファイルをCLIで検索する用途に向いている。</p>
<p>自分の場合はVimからagを実行できるプラグインを導入してファイルの検索を行っています。</p>

<div class="flex">
  <img src="/ag-img-1.png" alt="">
  <img src="/ag-img-2.png" alt="">
</div>

<style>
p {
  font-size: 16px;
}
.flex {
  display: flex;
  justify-content: space-between;
}
.flex img {
  width: 380px;
  height: auto;
}
</style>

---

# glow
<p>markdownをCUIでプレビューできるツール。<br />自分の場合はVimからglowを実行できる関数を自作して使用しています。</p>

<img src="/glow.png" alt="">

<style>
p {
  font-size: 16px;
}
img {
  width: 520px;
  height: auto;
}
</style>
---

# tig
<p>GitをCUI上で操作できるツールです。<br />普段Gitを使用するときは、tigとfishに設定したエイリアスを駆使してGitの操作を行っています。</p>

<img src="/tig.png" alt="">

<style>
p {
  font-size: 16px;
}
img {
  width: 520px;
  height: auto;
}
</style>
---

# その他使用しているCLI・CUIツール
- git-flow（リリース作業を行うときに使用）
- jq（JSONの整形に使用）
- tree（README.mdに載せるディレクトリ構成図を作るときに使用）

---

# 
<h1>ご静聴ありがとうございました。</h1>
