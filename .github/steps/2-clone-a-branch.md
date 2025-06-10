<!-- このステップでは　my-resume を個人の端末にクローン(複製)する処理を書く -->

## Step 2: クローンの作成と修正

インターネット上に存在するGitHubのリポジトリデータをローカルの端末にダウンロードして修正することも可能です。
そうしておけば、新幹線や飛行機で出張している状況でもオフライン且つ高速な作業環境が実現できます。実験的な変更を加える場合やバックアップを取得したい場合にも役立ちます。
<!-- オーバービューを書く -->

### :keyboard: VSCodeのインストールとブランチの作成

今回はVSCodeを使ってローカルにリモートリポジトリのクローンを作成するため、事前に[VSCodeをインストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code)します。

1. VSCodeのインストールが完了したら、[Git](https://git-scm.com/)をインストールします。VSCodeの拡張機能である[GitHub Actions](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions)、[GitGraph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)、[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)もインストールします。
1. 次にGitHubの画面で「<>Code」のボタンを押下し、表示されるHTTPSのURLをコピーします(コピーアイコンを押す)。
1. VSCodeの左ペインの「リモートエクスプローラー」を押下し、リモートリポジトリの追加「+」を押します。
1. 上部の検索バーに「GitHubからリポジトリを開く」を押し、先ほどコピーしたURLを入力し実行します。VSCode上にリモートリポジトリが表示されます。
1. デフォルトでmainブランチが選択されています。[最初の手順](https://github.com/kuboctopus/dodge-merge-conflict/blob/main/README.md)で作成した自分専用のmy-resume ブランチに切り替える必要があります。VSCodeの画面の左下に表示される「main」を押下し、「my-resume」を選択します。

<!-- 5. VSCodeの左ペインの「ソースの管理」を押下し、そのリポジトリを選択した状態で、「...」を押し、「ブランチ-ブランチの作成」を選びます。
6. 上部の検索バーにフォーカスが移動しますので、任意のブランチ名(name_yyyymmdd 等)を入力し、実行します。 -->

### :keyboard: ローカル端末へのクローンの作成

作成したブランチをローカルの端末に保存します。以下手順を記載。

1. VSCodeの画面左下にある「>< GitHub」を押下し、「新しいローカルクローンで作業を続ける」を押します。
1. 「はい、作業中の変更を使って続行します」を選択します。必要に応じてGitHubの認証を行い、ローカル端末のリポジトリの保存先を選択します。
1. 「複製したリポジトリを開きますか? または現在のワークスペースに追加しますか?」というメッセージダイアログが表示されるので、「開く」ボタンを押下します。
1. Explorerで指定した保存先にリポジトリに含まれるフォルダとファイル群(dodge-merge-conflict 以下)が保存されていることを確認します。

以上でローカル端末へのクローン作成は完了です。

