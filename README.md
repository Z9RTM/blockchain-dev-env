# blockchain-dev-env
## GitHub Codespaces上での使用方法

1. **Codespacesを有効化**:
    - リポジトリの設定でGitHub Codespacesが有効になっていることを確認します。
    - 必要に応じて、GitHubの[Codespacesドキュメント](https://docs.github.com/codespaces)を参照してください。

2. **Codespaceを作成**:
    - リポジトリのページに移動し、**Code**ボタンをクリックします。
    - **Codespaces**タブを選択し、**Create codespace on main**をクリックします。

3. **環境のセットアップを待つ**:
    - Codespaceが作成され、必要な依存関係が自動的にインストールされます。数分かかる場合があります。

4. **開発を開始**:
    - Codespaceが準備完了になると、ブラウザ上またはローカルのVisual Studio Codeで開発を開始できます。

5. **Codespaceを停止または削除**:
    - 開発が終了したら、Codespaceを停止または削除することでリソースを解放できます。
    - GitHubの[Codespaces管理ページ](https://github.com/codespaces)から操作できます。

詳細については、[GitHub Codespacesのドキュメント](https://docs.github.com/codespaces)を参照してください。
## macOSでのDev Containerの使用方法

1. **事前準備をインストール**:
    - [Docker Desktop for Mac](https://www.docker.com/products/docker-desktop/)をインストールします。
    - [Visual Studio Code](https://code.visualstudio.com/)をインストールします。
    - Visual Studio Codeに[Dev Containers拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)をインストールします。

2. **リポジトリをクローン**:
    ```bash
    git clone https://github.com/Z9RTM/blockchain-dev-env.git
    cd blockchain-dev-env
    ```

3. **Dev Containerで開く**:
    - プロジェクトフォルダをVisual Studio Codeで開きます。
    - プロンプトが表示されたら、**Reopen in Container**をクリックします。表示されない場合は、コマンドパレット（`Cmd+Shift+P`）を開き、「Dev Containers: Reopen in Container」を検索して選択します。

4. **セットアップを待つ**:
    - コンテナがビルドされ、必要な依存関係がインストールされます。数分かかる場合があります。

5. **開発を開始**:
    - コンテナの準備が整ったら、事前設定された環境で開発を開始できます。

6. **コンテナを停止**:
    - コンテナを停止するには、Visual Studio Codeを閉じるか、Docker Dashboardを使用して実行中のコンテナを停止します。

詳細については、[Dev Containersのドキュメント](https://code.visualstudio.com/docs/devcontainers/containers)を参照してください。

## WindowsでのDev Containerの使用方法

1. **事前準備をインストール**:
    - [Docker Desktop for Windows](https://www.docker.com/products/docker-desktop/)をインストールします。
    - [Visual Studio Code](https://code.visualstudio.com/)をインストールします。
    - Visual Studio Codeに[Dev Containers拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)をインストールします。

2. **WSL 2を有効化**:
    - Docker DesktopでWSL 2を有効にする必要があります。詳細な手順は[公式ガイド](https://docs.microsoft.com/windows/wsl/install)を参照してください。

3. **リポジトリをクローン**:
    ```bash
    git clone https://github.com/Z9RTM/blockchain-dev-env.git
    cd blockchain-dev-env
    ```

4. **Dev Containerで開く**:
    - プロジェクトフォルダをVisual Studio Codeで開きます。
    - プロンプトが表示されたら、**Reopen in Container**をクリックします。表示されない場合は、コマンドパレット（`Ctrl+Shift+P`）を開き、「Dev Containers: Reopen in Container」を検索して選択します。

5. **セットアップを待つ**:
    - コンテナがビルドされ、必要な依存関係がインストールされます。数分かかる場合があります。

6. **開発を開始**:
    - コンテナの準備が整ったら、事前設定された環境で開発を開始できます。

7. **コンテナを停止**:
    - コンテナを停止するには、Visual Studio Codeを閉じるか、Docker Dashboardを使用して実行中のコンテナを停止します。

詳細については、[Dev Containersのドキュメント](https://code.visualstudio.com/docs/devcontainers/containers)を参照してください。