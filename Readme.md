﻿
## Caption2Ass_PCR_pf

tsファイルから字幕を抽出します。



------------------------------------------------------------------
### 使い方
ファイル  
Caption2Ass_PCR_pf.exe  -i "C:\video.ts"  -o "C:\video.ts"  -format srt

パイプ  
Caption2Ass_PCR_pf.exe  -pipe  -o "C:\video.ts"  -format srt



------------------------------------------------------------------
### 追加引数

    -pipe
パイプからデータを受けとる


    -limit 10.0
ファイル読込み速度を10.0 MiB/secに制限


    -NonCapTag
tsファイルに字幕が含まれてない場合に空のファイルvideo.noncapを出力。
Caption2Ass_PCR_pfの動作確認用です。



------------------------------------------------------------------
### 引数

    -format srt
    -format ass
    -format dual
字幕ファイルの形式。  
dualを指定すると srt, assを出力します。


    -detect_length 300
300×10000パケットを探索して字幕が見つからなければプロセスを終了します。  
およそ３～５分間のデータ量に相当します。  
初期値は300  


その他の引数は  
"Caption2Ass_PCR_pf\readme history\Caption2Ass_PCR.exe の Readme.txt"  
に記載されています。


------------------------------------------------------------------
### 謝辞
maki/maki_rxrzさん公開のCaption2Ass_PCR_20131011_Experimentalを元に作成しました。
オリジナル及び改良版の開発に関わった方々にお礼申し上げます。


------------------------------------------------------------------
### ライセンス
以下Caption2Ass_PCR.exe の Readme.txtより、

●EpgDataCap_Bon、TSEpgView_Sample、NetworkRemocon、Caption、TSEpgViewServerの
ソースの取り扱いについて
　特にGPLとかにはしないので自由に改変してもらって構わないです。
　改変して公開する場合は改変部分のソースぐらいは一緒に公開してください。
　（強制ではないので別に公開しなくてもいいです）
　EpgDataCap.dllの使い方の参考にしてもらうといいかも。

●EpgDataCap.dll、Caption.dllの取り扱いについて
　フリーソフトに組み込む場合は特に制限は設けません。ただし、dllはオリジナルのまま
　組み込んでください。
　このdllを使用したことによって発生した問題について保証は一切行いません。
　商用、シェアウェアなどに組み込むのは不可です。


