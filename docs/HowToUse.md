# 使い方 / How to use

## Menu

+ [使い方の動画(日本語) / Video (Japanese)](#videos_anchor)
+ [バーチャルモーションキャプチャーと使う / Use with Virtual Motion Capture](#use_with_vmc)
+ [VMCProtocol対応アプリケーションと使う / Use with VMCProtocol Applications](#use_with_vmcprotocol)

<a name="videos_anchor"></a>

## 使い方の動画(日本語) / Video (Japanese)
### バーチャルモーションキャプチャーでの基本的な使い方 / Basic usage with Virtual Motion Capture
<iframe width="560" height="315" src="https://www.youtube.com/embed/DunqgLrUfpI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

PR: 動画内でのカメラの動きは、シネスイッチャーで実現されています。  
Camera movement within the video is accomplished with a cine switcher.  
[シネスイッチャーのダウンロードはこちらから / Download CineSwitcher here](https://booth.pm/ja/items/1654878)  

### モーションの記録 / Motion Record
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZflM7H089vM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
[テキストバージョン / Text virsion](https://note.com/afolyte/n/nc43c064fcb34)

### VMCProtocolでの基本的な使い方 / Basic usage with VMCProtocol
<iframe width="560" height="315" src="https://www.youtube.com/embed/L5dkdnk5c9A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<a name="use_with_vmc"></a>

## バーチャルモーションキャプチャーと使う / Use with Virtual Motion Capture

!!! note
    バーチャルモーションキャプチャーは、有料支援版(Fanbox版)あるいは、セルフビルド版である必要があります。 
    無償配布版にはVMCProtocol送信機能は搭載されていませんのでご注意ください。

    Virtual motion capture must be a paid support version (Fanbox version) or a self-build version.  
    Please note that the VMCProtocol transmission function is not installed in the free distribution version.

    [Fanbox](https://akira.fanbox.cc/)    
    [Patreon](https://www.patreon.com/sh_akira)    

    なお、EVMC4Uの作者はバーチャルモーションキャプチャーの製作者ではありませんので、お問い合わせを頂いても対応できません。  
    バーチャルモーションキャプチャーのFanboxおよびPatreonから参加できるDiscordサーバーにてご相談ください。

    Please note that the creator of EVMC4U is not the creator of Virtual Motion Capture, so we cannot respond to inquiries of that.  
    Please contact to the Discord server that you can join from the Virtual Motion Capture Fanbox and Patreon.


### 1. Unityを導入する / Install Unity
[トップページ](index.md) に記載のバージョン以上を使用してください。  
Please use version higher than that described in [top page](index.md).

### 2. EVMC4Uをダウンロードする / Download EVMC4U
[ダウンロードページ](Download.md) よりダウンロードしてください。  
zip圧縮されている場合は、展開してください。  

Please download from [Download page](Download.md).  
If it is zipped, unzip it.

### 3. 使用したいUnityプロジェクトを開く / Open your own Unity project
![openproject](/EasyVirtualMotionCaptureForUnity-documents/image/openproject.png)

もし、UniVRMを導入済みの場合は、削除することをおすすめします。  
If UniVRM has already been imported, it is recommended to remove it.

### 4. ExternalReceiverPack(EVMC4U)を導入する / Import ExternalReceiverPack(EVMC4U)
![dandd](/EasyVirtualMotionCaptureForUnity-documents/image/dandd.png)

インポートをクリックします。UniVRMとuOSCの推奨バージョンも同時に導入されます。  
Click Import. Recommended versions of UniVRM and uOSC will also be imported at the same time.

![](/EasyVirtualMotionCaptureForUnity-documents/image/import.png)

もしこれが出た場合、"Yes, for these and other files that might be found later"をクリック。  
If you get this, click "Yes, for these and other files that might be found later".  

![](/EasyVirtualMotionCaptureForUnity-documents/image/suc.png)

### 5. UniVRMの初期設定をする / Setup UniVRM
"Accept All"をクリック  
Click "Accept All".

![](/EasyVirtualMotionCaptureForUnity-documents/image/u1.png)  

"Close"をクリック  
Click "Close".

![](/EasyVirtualMotionCaptureForUnity-documents/image/u2.png)

### 6. EVMC4Uの初期設定をする / Setup EMV4U

閉じる  
Close  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e1.png)  

ExternalReceiverシーンを開く  
Open ExternalReceiver scene.

![](/EasyVirtualMotionCaptureForUnity-documents/image/e2.png)  

ExternalReceiverが読み込まれていることを確認する  
Check "ExternalReceiver" loaded.

![](/EasyVirtualMotionCaptureForUnity-documents/image/e3.png)  

Playボタンを押す  
Press play button.

![](/EasyVirtualMotionCaptureForUnity-documents/image/e4.png)  

### 7. バーチャルモーションキャプチャーの設定をする / Setup Virtual Motion Capture
画像に従って操作してください。  
Please follow instruction on image.

[詳細はバーチャルモーションキャプチャー公式ページを参照してください。](https://vmc.info/)  
[Please refer to the virtual motion capture official page for details.](https://vmc.info/)

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
If it works properly, VRM will be automatically loaded on the Unity side.

![](/EasyVirtualMotionCaptureForUnity-documents/image/v6.png)  


![](/EasyVirtualMotionCaptureForUnity-documents/image/v7.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v7e.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v8.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/v8e.png)  

楽しんで！  
Have a fun!  


<a name="use_with_vmcprotocol"></a>

## VMCProtocol対応アプリケーションと使う / Use with VMCProtocol Applications

!!! note
    VMCProtocol対応アプリケーションに関しては、各アプリケーションの説明を確認してください。  
    For VMCProtocol compatible applications, please check the description of each application.

### 1. Unityを導入する / Install Unity
[トップページ](index.md) に記載のバージョン以上を使用してください。  
Please use version higher than that described in [top page](index.md).

### 2. EVMC4Uをダウンロードする / Download EVMC4U
[ダウンロードページ](Download.md) よりダウンロードしてください。  
zip圧縮されている場合は、展開してください。  

Please download from [Download page](Download.md).  
If it is zipped, unzip it.

### 3. 使用したいUnityプロジェクトを開く / Open your own Unity project
![openproject](/EasyVirtualMotionCaptureForUnity-documents/image/openproject.png)

もし、UniVRMを導入済みの場合は、削除することをおすすめします。  
If UniVRM has already been imported, it is recommended to remove it.

### 4. ExternalReceiverPack(EVMC4U)を導入する / Import ExternalReceiverPack(EVMC4U)
![dandd](/EasyVirtualMotionCaptureForUnity-documents/image/dandd.png)

インポートをクリックします。UniVRMとuOSCの推奨バージョンも同時に導入されます。  
Click Import. Recommended versions of UniVRM and uOSC will also be imported at the same time.

![](/EasyVirtualMotionCaptureForUnity-documents/image/import.png)

もしこれが出た場合、"Yes, for these and other files that might be found later"をクリック。  
If you get this, click "Yes, for these and other files that might be found later".  

![](/EasyVirtualMotionCaptureForUnity-documents/image/suc.png)

### 5. UniVRMの初期設定をする / Setup UniVRM
"Accept All"をクリック  
Click "Accept All".

![](/EasyVirtualMotionCaptureForUnity-documents/image/u1.png)  

"Close"をクリック  
Click "Close".

![](/EasyVirtualMotionCaptureForUnity-documents/image/u2.png)

### 6. EVMC4Uの初期設定をする / Setup EMV4U

閉じる  
Close  

![](/EasyVirtualMotionCaptureForUnity-documents/image/e1.png)  

ExternalReceiverシーンを開く  
Open ExternalReceiver scene.

![](/EasyVirtualMotionCaptureForUnity-documents/image/e2.png)  

ExternalReceiverが読み込まれていることを確認する  
Check "ExternalReceiver" loaded.

![](/EasyVirtualMotionCaptureForUnity-documents/image/e3.png)  

### 7. EVMC4UにVRMモデルを読み込む / Load VRM model to EVMC4U

画像に従って操作してください。  
Please follow instruction on image.

![](/EasyVirtualMotionCaptureForUnity-documents/image/l1.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/l2.png)  

Click "External Reciver".

![](/EasyVirtualMotionCaptureForUnity-documents/image/l3.png)  

![](/EasyVirtualMotionCaptureForUnity-documents/image/l4.png)  
![](/EasyVirtualMotionCaptureForUnity-documents/image/l5.png)  

Playボタンを押す  
Press play button.

![](/EasyVirtualMotionCaptureForUnity-documents/image/e4.png)  

VMCProtocol対応アプリケーションから送信を有効化してください。  
Please enable transmission from the VMCProtocol compatible application.


楽しんで！  
Have a fun!  
