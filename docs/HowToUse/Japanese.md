# 使い方 / How to use

## Menu

+ [使い方の動画(日本語))](#videos_anchor)
+ [VMCProtocol対応アプリケーションと使う](#use_with_vmcprotocol)
+ [バーチャルモーションキャプチャーと使う](#use_with_vmc)

Refer: [VMCProtocolのアプリケーション組み合わせ](https://protocol.vmc.info/Combinations)

<a name="videos_anchor"></a>

## 使い方の動画(日本語)
### バーチャルモーションキャプチャーでの基本的な使い方
<iframe width="560" height="315" src="https://www.youtube.com/embed/DunqgLrUfpI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

PR: 動画内でのカメラの動きは、シネスイッチャーで実現されています。    
[シネスイッチャーのダウンロードはこちらから](https://booth.pm/ja/items/1654878)  

### モーションの記録
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZflM7H089vM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
[テキストバージョン](https://note.com/afolyte/n/nc43c064fcb34)

### VMCProtocolでの基本的な使い方
<iframe width="560" height="315" src="https://www.youtube.com/embed/L5dkdnk5c9A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### STYLY Guide
EVMC4UとEasyMotionRecorderでキャラクターのモーションを記録する方法  
[https://styly.cc/ja/tips/evmc4u_easymotionrecorder_virtualmotioncapture/](https://styly.cc/ja/tips/evmc4u_easymotionrecorder_virtualmotioncapture/)

<a name="use_with_vmcprotocol"></a>

## VMCProtocol対応アプリケーションと使う

!!! note
    VMCProtocol対応アプリケーションに関しては、各アプリケーションの説明を確認してください。  

### 1. Unityを導入する
[トップページ](/EasyVirtualMotionCaptureForUnit/index.md) に記載のバージョン以上を使用してください。  

### 2. EVMC4Uをダウンロードする
[ダウンロードページ](/EasyVirtualMotionCaptureForUnit/Download.md) よりダウンロードしてください。  
zip圧縮されている場合は、展開してください。  

### 3. 使用したいUnityプロジェクトを開く
![openproject](/EasyVirtualMotionCaptureForUnity-documents/image/openproject.png)

もし、UniVRMを導入済みの場合は、削除することをおすすめします。  

### 4. ExternalReceiverPack(EVMC4U)を導入する
![dandd](/EasyVirtualMotionCaptureForUnity-documents/image/dandd.png)

インポートをクリックします。UniVRMとuOSCの推奨バージョンも同時に導入されます。  

![](/EasyVirtualMotionCaptureForUnity-documents/image/import.png)

もしこれが出た場合、"Yes, for these and other files that might be found later"をクリック。  

![](/EasyVirtualMotionCaptureForUnity-documents/image/suc.png)

### 5. UniVRMの初期設定をする
"Accept All"をクリック  

![](/EasyVirtualMotionCaptureForUnity-documents/image/u1.png)  

"Close"をクリック  

![](/EasyVirtualMotionCaptureForUnity-documents/image/u2.png)

### 6. EVMC4Uの初期設定をする

閉じる  
Close  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e1.png)  

ExternalReceiverシーンを開く  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e2.png)  

ExternalReceiverが読み込まれていることを確認する  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e3.png)  

### 7. EVMC4UにVRMモデルを読み込む

画像に従って操作してください。  

![](/EasyVirtualMotionCaptureForUnity-documents/image/l1.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/l2.png)  

"External Reciver"をクリック

![](/EasyVirtualMotionCaptureForUnity-documents/image/l3.png)  

![](/EasyVirtualMotionCaptureForUnity-documents/image/l4.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/l5.png)  

Playボタンを押す  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e4.png)  

VMCProtocol対応アプリケーションから送信を有効化してください。  


楽しんで！  

<a name="use_with_vmc"></a>

## バーチャルモーションキャプチャーと使う

!!! note
    バーチャルモーションキャプチャーは、有料支援版(Fanbox版)あるいは、セルフビルド版である必要があります。 
    無償配布版にはVMCProtocol送信機能は搭載されていませんのでご注意ください。

    **下記サイトからダウンロードしてください(無料配布版をダウンロードしても使えません!)**

    [Fanbox](https://akira.fanbox.cc/)    
    [Patreon](https://www.patreon.com/sh_akira)    

    なお、EVMC4Uの作者はバーチャルモーションキャプチャーの製作者ではありませんので、お問い合わせを頂いても対応できません。  
    バーチャルモーションキャプチャーのFanboxおよびPatreonから参加できるDiscordサーバーにてご相談ください。

### 1. Unityを導入する
[トップページ](/EasyVirtualMotionCaptureForUnit/index.md) に記載のバージョン以上を使用してください。  

### 2. EVMC4Uをダウンロードする
[ダウンロードページ](/EasyVirtualMotionCaptureForUnit/Download.md) よりダウンロードしてください。  
zip圧縮されている場合は、展開してください。  

### 3. 使用したいUnityプロジェクトを開く
![openproject](/EasyVirtualMotionCaptureForUnity-documents/image/openproject.png)

もし、UniVRMを導入済みの場合は、削除することをおすすめします。  

### 4. ExternalReceiverPack(EVMC4U)を導入する
![dandd](/EasyVirtualMotionCaptureForUnity-documents/image/dandd.png)

インポートをクリックします。UniVRMとuOSCの推奨バージョンも同時に導入されます。  

![](/EasyVirtualMotionCaptureForUnity-documents/image/import.png)

もしこれが出た場合、"Yes, for these and other files that might be found later"をクリック。  

![](/EasyVirtualMotionCaptureForUnity-documents/image/suc.png)

### 5. UniVRMの初期設定をする
"Accept All"をクリック  

![](/EasyVirtualMotionCaptureForUnity-documents/image/u1.png)  

"Close"をクリック  

![](/EasyVirtualMotionCaptureForUnity-documents/image/u2.png)

### 6. EVMC4Uの初期設定をする

閉じる  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e1.png)  

ExternalReceiverシーンを開く  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e2.png)  

ExternalReceiverが読み込まれていることを確認する  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e3.png)  

Playボタンを押す  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e4.png)  

### 7. バーチャルモーションキャプチャーの設定をする
画像に従って操作してください。  

[詳細はバーチャルモーションキャプチャー公式ページを参照してください。](https://vmc.info/)  

![](/EasyVirtualMotionCaptureForUnity-documents/image/v1.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v1e.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v2.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v2e.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v3.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v3e.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v4.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v4e.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v5.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v5e.png)  


正常に動作していれば、Unity側にVRMが自動で読み込まれます。  

![](/EasyVirtualMotionCaptureForUnity-documents/image/v6.png)  


![](/EasyVirtualMotionCaptureForUnity-documents/image/v7.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v7e.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v8.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v8e.png)  

楽しんで！  

