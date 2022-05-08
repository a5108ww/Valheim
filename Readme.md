

# 一、初次設定(完整模組) 


## 1.下載模組包 (Server/Client) 

#### (1) Client端

* 下載附件連結區的附件1

#### (2) Server端

* 開啟連結 https://github.com/valheimPlus/ValheimPlus/releases/tag/0.9.9.8 

* 下載 UnixServer.tar.gz 

## 2.解壓縮模組包 (Server/Client) 

#### (1) Client端：將zip檔解壓縮到Valheim 遊戲目錄下(有valheim.exe那層目錄) 

#### (2) Server 端：將.gz檔解壓縮到serverfile目錄底下 



## 3.調整執行.sh步驟 (Server) 

說明： 

#### (1)進入編輯模式  

* /home/vhserver/lgsm/config-lgsm/vhserver/vhserver.cfg 

* 修改參數 => executable="start_server_bepinex.sh" (需將原參數註解)

#### (2)進入編輯模式_新增指令 

   /home/serverfile/start_server_bepinex.sh 

   最後一行新增 [exec ./valheim_server.x86_64 $@] 

   (不包括中括弧) 

# 二、死亡不噴裝模組 

### 下載cfg 、dll檔 ，連結參考附件連結的附件2跟附件3。

### 複製檔案

##### (1)net.mtnewton.gravekeeper.cfg

* 開啟Steam 遊戲根目錄(參考備註1)

* 複製到 \BepInEx\config\ ，此目錄底下

##### (2)Gravekeeper.dll

* 開啟Steam 遊戲根目錄(參考備註1)

* 複製到 \BepInEx\plugins\ ，此目錄底下

## 附件連結

附件1：
<a href='https://storageforshilvain.blob.core.windows.net/valheim/UnixServer.zip' target='_blank'>
ValheimPlus模組包</a>
(完整安裝包)

<br><br>

附件2：
<a href='https://storageforshilvain.blob.core.windows.net/picture/net.mtnewton.gravekeeper.cfg' target='_blank'>
死亡不噴裝設定檔.cfg</a>

<br><br>

附件3：
<a href='https://storageforshilvain.blob.core.windows.net/valheim/Gravekeeper.dll' target='_blank'>
死亡不噴裝模組.dll</a>

<br><br>

## 備註

* 備註1：Steam 遊戲根目錄開啟方式：

* => 對Steam 遊戲按右鍵 => 管理 => 瀏覽本機檔案

# 

相關設定說明文章
https://github.com/valheimPlus/ValheimPlus
https://github.com/GameServerManagers/LinuxGSM/issues/3287

設定的檔案下載連結
https://github.com/valheimPlus/ValheimPlus/releases/tag/0.9.9.8

cfg設定講解
https://www.nexusmods.com/valheim/mods/4

參數說明資源：
https://forum.gamer.com.tw/C.php?bsn=38700&snA=574
