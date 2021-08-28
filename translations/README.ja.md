[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
<<<<<<< HEAD
[<img align="right" src="https://firstcontributions.herokuapp.com/badge.svg">](https://firstcontributions.herokuapp.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

=======
[<img align="right" width="150" src="https://firstcontributions.github.io/assets/Readme/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/enQtNjkxNzQwNzA2MTMwLTVhMWJjNjg2ODRlNWZhNjIzYjgwNDIyZWYwZjhjYTQ4OTBjMWM0MmFhZDUxNzBiYzczMGNiYzcxNjkzZDZlMDM)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)
>>>>>>> upstream/master

# First Contributions

初めてのことは何でも大変なものです。特に他人と協力する時はそうで、間違うのは気持ちの良いことではありません。しかし、オープンソースにおける活動では協力することが全てです。私たちは初めてオープンソースへの貢献を始める人たちが簡単に貢献する方法を学べるようにしたいと考えています。

記事を読んだりチュートリアルをやってみることはためになりますが、実際にやってみる方が良いでしょう。このプロジェクトはそのガイダンスを行い、初心者が最初のオープンソースへの貢献を簡単に行えるようにするためのものです。
覚えておいてください: リラックスしているほどより良く学ぶことができます。もし初めてのオープンソースへの貢献を行いたいのなら以下の簡単なステップに従ってください。それはとても面白いものになるはずです。

<<<<<<< HEAD
#### *[他の言語](../Translations.md)で読む*

<img align="right" width="300" src="../assets/fork.png" alt="fork this repository" />
=======
#### *コマンドラインでの操作に慣れていない場合、[グラフィカルなツールでもチュートリアルを行えます。]( #その他のツールを使用したチュートリアル )*

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />
>>>>>>> upstream/master

まだGitをインストールしていない場合は、[ここ](https://help.github.com/articles/set-up-git/)からインストールしてください

## レポジトリをフォーク

Forkボタンをクリックしてこのレポジトリをフォークしてください。
この作業はあなたのアカウントにこのレポジトリのコピーを作ります。

## レポジトリをクローン

<<<<<<< HEAD
<img align="right" width="300" src="../assets/clone.png" alt="clone this repository" />
=======
<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />
>>>>>>> upstream/master

次にレポジトリをクローンします。*Clone and download*ボタンをクリックした後に*Copy to clipboard*アイコンをクリックしてください。

ターミナルを開いて以下のgitコマンドを実行してください：

```
git clone "コピーしたURL"
```
"コピーしたURL" (ダブルクオーテーションは除いてください) は先ほどコピーしたレポジトリのURLと置き換えてください。

<<<<<<< HEAD
<img align="right" width="300" src="../assets/copy-to-clipboard.png" alt="copy URL to clipboard" />
=======
<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />
>>>>>>> upstream/master

例：
```
git clone https://github.com/＜あなたのユーザー名＞/first-contributions.git
```
`あなたのユーザー名` はご自身のGitHubユーザー名に置き換えてください。この作業でGitHub のリポジトリの内容はあなたのコンピュータにコピーされました。

## ブランチを作成

もしレポジトリのディレクトリにいなければそこまで移動してください。

```
cd first-contributions
```
<<<<<<< HEAD
`git checkout command`　コマンドを使用してブランチを作成します：
=======
`git checkout` コマンドを使用してブランチを作成します：
>>>>>>> upstream/master
```
git checkout -b <add-your-name>
```

例:
```
git checkout -b add-alonzo-church
```
(ブランチの名前には必ずしも*add*が含まれていなければならないわけではありませんが、このブランチの目的があなたの名前をリストに加えることであることを考慮すれば含むのが適切です。)

## コードを変更してその変更をコミット

<<<<<<< HEAD
テキストエディタで`Contributors.md`ファイルを開いてあなたの名前を追加し、ファイルを保存します。プロジェクトディレクトリに移動して`git status`を実行すると、変更がなされたことが確認できると思います。`git add`コマンドを使ってそれらの変更を適用してください。
=======
テキストエディタで`Contributors.md`ファイルを開いてあなたの名前を追加してください。だたし、ファイルの始めや終わりにあなたの名前をつけないようにしましょう。名前リストの間のどこか好きな場所に、あなたの名前を追加するようにしましょう。あなたの名前をファイルに加えたら、ファイルを保存します。

<img align="float: right;" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

プロジェクトディレクトリに移動して`git status`を実行すると、変更がなされたことが確認できると思います。`git add`コマンドを使ってそれらの変更を適用してください。
>>>>>>> upstream/master
```
git add Contributors.md
```

<<<<<<< HEAD

=======
>>>>>>> upstream/master
次に`git commit`コマンドを使ってこれらの変更をコミットします。
```
git commit -m "Add <あなたの名前> to Contributors list"
```
<<<<<<< HEAD
`<あなたの名前>`をご自身の名前に置き換えてください

## GitHubに変更をpushする

`git push`コマンドを使って変更をpushしてください
=======
`<あなたの名前>`をご自身の名前に置き換えてください。

## GitHubに変更をpushする

`git push`コマンドを使って変更をpushしてください。
>>>>>>> upstream/master
```
git push origin <ブランチ名>
```
`<ブランチ名>`には先ほど作成したブランチ名を入れてください。

## レビューのためにプルリクエストを送る

GitHub上であなたのリポジトリに行くと、`Compare & pull request`ボタンが表示されます。そのボタンをクリックしてください。

<<<<<<< HEAD
<img style="float: right;" src="../assets/compare-and-pull.png" alt="create a pull request" />

プルリクエストを作ってください：

<img style="float: right;" src="../assets/submit-pull.png" alt="submit pull request" />
=======
<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

プルリクエストを作ってください：

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />
>>>>>>> upstream/master

すぐに私が加えられた変更をmasterブランチにマージします。マージが終了した際にはその旨のメールが送られます。

## 次に何をするべきか

<<<<<<< HEAD
初のオープンソースへの貢献を祝って友達やフォロワーにそのことを[このウェブアプリ](https://roshanjossey.github.io/first-contributions/#social-share)を使ってシェアしましょう。

もし何かしら質問があるようでしたら[私たちのSlack team](https://firstcontributions.herokuapp.com)に入ってください。

他のプロジェクトへの貢献を始めましょう。簡単なイシューが立てられているプロジェクトのリストを作りました。ウェブアプリで[プロジェクトリスト](https://roshanjossey.github.io/first-contributions/#project-list)を確認て見てください。

### [追加リソース](../additional-material/git_workflow_senarios/additional-material.md)

## その他のツールを使用したチュートリアル
|<a href="../github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="../github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://www.visualstudio.com/wp-content/uploads/2017/11/microsoft-visual-studio.svg" width="100"></a>|<a href="../gitkraken-tutorial.md"><img alt="GitKraken" src="../assets/gk-icon.png" width="100"></a>|
|---|---|---|
|[GitHub Desktop](../github-desktop-tutorial.md)|[Visual Studio 2017](../github-windows-vs2017-tutorial.md)|[GitKraken](../gitkraken-tutorial.md)|

# 宣伝
このプロジェクトがお気に召しましたら[Github](https://github.com/Roshanjossey/first-contributions)上でstarしてくださると幸いです。特にお気に召した場合には[Twitter](https://twitter.com/sudo__bangbang)上や[GitHub](https://github.com/roshanjossey)などで
[Roshan](https://roshanjossey.github.io/)をフォローしてくださると幸いです。
=======
おめでとうございます！  コントリビューターとして重要な _フォーク -> クローン -> 編集 -> プルリクエスト_　の基本的なワークフローが完了しました。

初のオープンソースへの貢献を祝って友達やフォロワーにそのことを[このウェブアプリ](https://roshanjossey.github.io/first-contributions/#social-share)を使ってシェアしましょう。

もし何かしら質問があるようでしたら[私たちのSlack team](https://firstcontributors.slack.com/join/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY)に入ってください。

他のプロジェクトへの貢献を始めましょう。簡単なイシューが立てられているプロジェクトのリストを作りました。ウェブアプリで[プロジェクトリスト](https://roshanjossey.github.io/first-contributions/#project-list)を確認て見てください。

### [追加リソース](../additional-material/git_workflow_scenarios/additional-material.md)

## その他のツールを使用したチュートリアル
|<a href="../github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="../github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a>|<a href="../gitkraken-tutorial.md"><img alt="GitKraken" src="https://firstcontributions.github.io/assets/Readme/gk-icon.png" width="100"></a>|<a href="../github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a>|<a href="../sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a>|
|---|---|---|---|---|
|[GitHub Desktop](../github-desktop-tutorial.md)|[Visual Studio 2017](../github-windows-vs2017-tutorial.md)|[GitKraken](../gitkraken-tutorial.md)|[Visual Studio Code](../github-windows-vs-code-tutorial.md)|[Atlassian Sourcetree](../sourcetree-macos-tutorial.md)|

>>>>>>> upstream/master
