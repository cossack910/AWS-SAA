# mac から cli でコマンドを叩けるようにする

## CLI のインストール

- [ ] ファイルをダウンロード。

```
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
```

- [ ] Rosetta のインストール

Appel シリコン に対応していないっぽい？<br>
https://support.apple.com/ja-jp/HT211861

以下のコマンドを叩いて、A を入力してインストール

```
sudo softwareupdate --install-rosetta
```

- [ ] インストーラー実行

```
sudo installer -pkg ./AWSCLIV2.pkg -target /
```

- [ ] パス確認

```
which aws
```

- [ ] コマンド確認

```
aws --version
```
