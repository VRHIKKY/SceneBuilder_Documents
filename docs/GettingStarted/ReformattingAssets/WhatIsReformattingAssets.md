# アセットの再フォーマットとは

Scene Builderでは、自分自身で用意した3Dモデルを利用することができます。
使用することができる拡張子として、glbフォーマットと、heoフォーマットの二つがあります。

## 使用できる3Dフォーマットについて
### glbフォーマット
**glb**は、glTFという3Dモデルのファイルフォーマットの一つです。

ブラウザ上での3Dコンテンツの表示に適しており、Unity、Maya、Blenderなど、様々なツールで書き出すことが可能です。
ポリゴンモデルだけでなくテクスチャやマテリアルの情報を含むことができます。

glTFには、glbフォーマットと、gltfフォーマットの二つがありますが、Scene Builderで使用できるのは、glbフォーマットのみです。

### heoフォーマット
**heo**は、Scene Builderを動かしているVket Cloudという開発エンジンに適した3Dモデルのファイルフォーマットです。

glbフォーマットでは、細かい当たり判定の調整や、UVスクロールなどの設定はできませんが、heoフォーマットであれば、3Dモデルに細かな設定を行うことが可能です。

ただし、heoフォーマットを書き出すには、VketCloudSDKというUnityを用いた、Vket Cloudのワールドを開発するツールを使用する必要があります。

## 様々なツールでの書き出し方
以下の記事では、Blender、Maya、Unityを利用した、書き出し方を解説しています。

### Blender
#### glbフォーマット
[Blenderを利用して、GLBを書き出す](GettingStarted\ReformattingAssets\ExportingGLBUsingBlender.md)

### Maya
#### glbフォーマット
[Mayaを利用して、GLBを書き出す](GettingStarted\ReformattingAssets\ExportingGLBUsingMaya.md)

### Unity
Unityでの事前準備として、以下の記事を参考に3Dモデルの準備を行ってください。

[Unityを利用する場合の準備](GettingStarted\ReformattingAssets\PreparationUnity.md)

#### glbフォーマット
[UnityでUniVRMを利用して、GLBを書き出す](GettingStarted\ReformattingAssets\ExportingGLBUsingUniVRM.md)

#### heoフォーマット
[UnityでVketCloudSDKを利用して、HEOを書き出す](GettingStarted\ReformattingAssets\ExportingHEOUsingVketCloudSDK.md)

