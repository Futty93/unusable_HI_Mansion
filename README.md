# -使いにくいHIの館-

# Node.jsを使用した簡易的なWebサーバーのセットアップ

この手順では、Node.jsのhttp-serverパッケージを使用して、ローカルマシン上で簡易的なWebサーバーをセットアップします。

## 前提条件

- [Node.js](https://nodejs.org/)がインストールされていること

## 手順

1. **http-serverパッケージのインストール**

    Node.jsのnpm（Node Package Manager）を使用して、http-serverパッケージをグローバルにインストールします。

    ```bash
    npm install http-server -g
    ```

2. **http-serverの起動**

    インストールが完了したら、次のコマンドを実行して、http-serverを起動します。

    ```bash
    http-server
    ```

    これにより、ローカルマシンのポート8080でhttp-serverが起動します。任意のディレクトリにHTMLファイルを配置すると、そのディレクトリのHTMLファイルは、`http://localhost:8080/`でアクセスできるようになります。

## 注意事項

- http-serverを実行する際には、利用するポートが既に使用されていないことを確認してください。
