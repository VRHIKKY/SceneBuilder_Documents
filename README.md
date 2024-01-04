# SceneBuilder_Documents
このリポジトリは、SceneBuilderのマニュアルを管理するリポジトリです。 最新のSceneBuilderマニュアル以下のURLから確認できます。 https://vrhikky.github.io/SceneBuilder_Documents/latest/

## Contribution policy
社外のSceneBuilderユーザーからのコントリビューションの参加も絶賛受付中です。
誤字脱字の修正から文言のブラッシュアップまで、どんな些細なリクエストであっても、気軽にコミットいただいて結構です。
なお、プルリクエストされた時点で、以下の規約にご同意いただいたとみなします。ご了承ください。

- プルリクエストが承認されたとしても、いかなる報酬も発生しません。
- プルリクエストは却下される場合があり、かつ将来にわたって再度修正されることがあります。
- コミット内容に関して、著作権はHIKKYに帰属します。
- 悪質なコミットや嫌がらせに関しては、法的なしかるべき処置を持って対応します。

## Issue / Pull Requestについて

- Issueを立てる際はマニュアルのバージョンとURLを併記いただくようお願いいたします。

- Pull Requestについては編集対象のバージョンを指定してブランチを切り (例：version/scenebuilder-1.0)、 Pull Requestを送る際もmasterではなくversionを指定してください。
公開されているマニュアルは基本的には週次で更新されますが、臨時的にアップデートの際に更新される場合もあります。

## 執筆環境の導入
執筆環境の構築は、以下になります。

### ①リポジトリのクローン
お手持ちのPCにgit環境を導入し、リポジトリをクローンしてください。詳しい手順・ツールなどはお好みによって異なるため、ここでは割愛します。

### ②Pythonをインストールする
ローカル環境の構築にあたり、pythonが必要です。https://www.python.org/downloads/
![image](https://github.com/VRHIKKY/VketCloudSDK_Documents/assets/50200315/d1ee286c-f0c6-4db6-a065-f3d350872ce4)

バージョンは3.11を推奨しますが、上位バージョンでもおそらく問題ありません。
ただし、python2は確実に動作の保証ができません。お手持ちのPC（特にmac）がpython2しか入っていない場合は、お手数ですが最新のpythonを手動で導入してください。

### ③simpleserve.batを起動する
リポジトリとpythonの準備が完了したら、`SceneBuilder_Documents > simpleserve.bat`を起動します。

クリック後、ブラウザが立ち上がります。ページ更新までに少しラグがあるので、しばしお待ちください。
※もしブラウザ遷移しない場合は、 http://127.0.0.1:8000/ を手動で開いてください。
ドキュメントトップが表示されたら、準備完了です。`SceneBuilder_Documents > docs`以下に配置されている.mdファイルを編集して、内容を更新してください。

## お問い合わせ
執筆環境の導入や掲載内容についてのお問い合わせは、このリポジトリにissueを立てていただくか、VketCloud/MyVketのDiscordサーバー内にて、お問い合わせください。
