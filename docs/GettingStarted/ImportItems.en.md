# アイテムの読み込み・配置

Scene Builderにアイテムを追加するには、ローカルのプロジェクトファイルのassetフォルダ配下にある適切なフォルダに対して、モデルや画像を追加する必要があります。

| | |
| ---- | ---- |
| model | 3Dモデル（.heo、.glb）を格納するフォルダです。|
| image | プレーンとして配置する画像（.png）が格納されるフォルダです。|
| sound | サウンド（.mp3）を格納するフォルダです。|
| avatar | α版では使用できません。|
| script | スクリプト（.hs）を格納するフォルダです。 |

たとえば、モデルの追加作業を行うには下記のように行います。

SceneBuilderのProject>assets>modelに移動して、サポートしている3Dモデルを追加します。

![ImportItems_1](img/ImportItems_1.jpg)

SceneBuilderで、モデルを追加したプロジェクトを開きアセットパネルのモデルタブを見ると、追加したアセットが表示されていることが確認できます。

![ImportItems_2](img/ImportItems_2.jpg)

もしプロジェクトをブラウザで開いている状態でアセットの追加作業を行った場合、画面上で追加したアセットが反映がされない場合があります。

その際は、アセットパネルの別のタブに移動して、再度戻ると反映されます。