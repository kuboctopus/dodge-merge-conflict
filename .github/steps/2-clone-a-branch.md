<!-- このステップでは　my-resume を個人の端末にクローン(複製)する処理を書く -->

## Step 2: クローンの作成と修正

インターネット上に存在するGitHubのリポジトリデータをローカルの端末にダウンロードして修正することも可能です。
そうしておけば、新幹線や飛行機で出張している状況でもオフライン且つ高速な作業環境が実現できます。実験的な変更を加える場合やバックアップを取得したい場合にも役立ちます。
<!-- オーバービューを書く -->

### :keyboard: VSCodeのインストールとブランチの作成

今回はVSCodeを使ってローカルにリモートリポジトリのクローンを作成するため、事前に[VSCodeをインストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code)します。

1. VSCodeのインストールが完了したら、[Git](https://git-scm.com/)をインストールします。必要に応じて、[GitGraph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)や[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)もインストールします。
2. 次にGitHubの画面で「<>Code」のボタンを押下し、表示されるHTTPSのURLをコピーします(コピーアイコンを押す)。
3. VSCodeの左ペインの「リモートエクスプローラー」を押下し、リモートリポジトリの追加「+」を押します。
4. 上部の検索バーに「GitHubからリポジトリを開く」を押し、先ほどコピーしたURLを入力し実行します。VSCode上にリモートリポジトリが表示されます。
5. デフォルトでmainブランチが選択されています。「main」
my-resumeに切り替える手順に修正
<!-- 5. VSCodeの左ペインの「ソースの管理」を押下し、そのリポジトリを選択した状態で、「...」を押し、「ブランチ-ブランチの作成」を選びます。
6. 上部の検索バーにフォーカスが移動しますので、任意のブランチ名(name_yyyymmdd 等)を入力し、実行します。 -->

### :keyboard: ローカル端末へのクローンの作成

作成したブランチをローカルの端末に保存します。以下手順を記載。

