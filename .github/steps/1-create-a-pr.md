<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

#出だしの文言を適当に入れる

この学習に必要なGitとGitHubに関連する用語は以下のとおりです。先ずはこの用語と意味を理解してください。

## GitとGitHubの基本用語説明

| 用語           | 説明                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Git** | 主にコードが書かれたテキストファイルの変更を追跡するためのプログラム。                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **GitHub** | テキストファイルのバージョン管理がを行うためのプラットフォーム。                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **リポジトリ** | プロジェクトのすべてのファイルと変更履歴を格納する場所。                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **リモートリポジトリ**  | ネットワーク上(通常はGitHubやGitLabなど)に存在するリポジトリ。チームでコードを共有したり、バックアップを取ったりするために使用される。                                                                                                                                                                                                                                                                                                                                     |
| **ローカルリポジトリ**  | 自分のコンピュータ上に作成されたリポジトリ。リモートリポジトリからクローンすることで作成できます。ローカルで作業を行い、変更をコミットしてリモートリポジトリにプッシュすることで、他の人と共有できる。                                                                                                                                                                                                                                                                     |
| **ブランチ**     | リポジトリ内の開発ラインを分岐させたもの。新しい機能の開発やバグ修正などを行う際に、メインのコードベース(通常は`main`ブランチ)から分岐させて作業することで、品質が安定したコードを維持しながら開発を進めることができるす。                                                                                                                                                                                                                                                                   |
| **コミット**     | ファイルの変更履歴をリポジトリに記録すること。コミットメッセージには、どのような変更を行ったかを記述する。コミットは、Gitにおけるバージョン管理の基本単位となる。                                                                                                                                                                                                                                                                                                                         |
| **プル**       | リモートリポジトリの変更をローカルリポジトリに取り込むこと。他の人がリモートリポジトリに変更をプッシュした場合、自分のローカルリポジトリを最新の状態に保つためにプルを実行する。                                                                                                                                                                                                                                                                                                                         |
| **マージ**     | 複数のブランチの変更内容を1つのブランチ(大抵は`main`ブランチ)に統合すること。通常、機能開発ブランチでの作業が完了したら、そのブランチを`main`ブランチにマージする。                                                                                                                                                                                                                                                                                                                                 |
| **マージコンフリクト** | 異なるブランチで同じファイルの同じ箇所が変更された場合に発生する競合(コンフリクト)。Gitは不測のコード変更を防ぐために自動的にマージできず、手動で競合箇所を修正する必要がある。VSCodeのようなツールは、マージコンフリクトの解決を支援する機能を提供する。                                                                                                                                                                                                                                                                   |
| **プッシュ**     | ローカルリポジトリの変更をリモートリポジトリに反映させること。ローカルでコミットした変更を、他の人と共有したり、バックアップとしてリモートリポジトリに保存したりするためにプッシュを実行しする。                                                                                                                                                                                                                                                                                                                         |


## VSCodeとGit連携で開発効率UP！

なぜ、世の中の開発者はVSCodeとGitを使うのか?
1. **変更管理が楽々**: ソース管理ビューで、ファイル変更が一目瞭然。差分表示で修正箇所もすぐ把握。コミット履歴も追えて安心。
2. **ブランチ操作が直感的**: ブランチ作成/切替がGUIで簡単。ブランチ比較で変更点を把握し、マージもスムーズ。
3. **コンフリクト解決も支援**: コンフリクト箇所を明示し、コンフリクトエディタで視覚的に解決。どちらの変更を残すか迷わない！
4. **チーム開発を加速**: GitHub等と連携し、コード共有が容易。プルリク作成/レビューもVSCode内で完結。
5. **生産性UP**: コマンド操作減で開発集中！Git初心者もGUIで直感的に操作可能。

VSCodeとGit連携で、より快適な開発ライフを！



## Step 1: Create a pull request

_Welcome to "Managing Merge Conflicts"! :wave:_

**What is a _merge conflict_?**: A **merge conflict** occurs when changes are made to the same part of the same file on two different branches. You usually find out about conflicts in a pull request so let's start by creating one.

### :keyboard: Activity: Create a pull request

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. We made a small change to a file in the repository in the `my-resume` branch.
1. [Create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) setting `my-resume` as the head branch and `main` as the base branch. You can enter `Resolving merge conflicts` for the pull request title and body.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
