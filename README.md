# ICADlancher_NR
## 概要
Node-REDによるiCADランチャーフロー（json）の導入方法について
## はじめに
- 前提としてNode-REDはインストール済み 
- iCAD用ツール(exe)の格納場所はC:\ICADSX\USER\BINとする
## 導入方法-NodeREDフロー
1. 本レポジトリ内の「flows.json」をダウンロード
2. Node-REDフロー編集画面の 右上三本線メニュー→読み込み からダウンロードしたフローを読み込み
## 編集方法-NodeRED
### command実行
下図橙枠のボタンノードをダブルクリックし、編集画面へ  
![image](https://github.com/user-attachments/assets/d1209206-d032-452b-b241-7bd050be5bc8)  
赤枠payload内にiCADコマンドを入力する  
![image](https://github.com/user-attachments/assets/d091237f-36ef-4615-ac06-703d2ccbc681)  
### macro実行
commandと同様にボタンノードを編集する  
Payload内をiCADにて登録したマクロ名を入力  
### EXE起動
commandと同様にボタンノードを編集する  
Payload内にexeの名称を入力  
![image](https://github.com/user-attachments/assets/f569f68d-c2cf-4219-8d98-ba5412ae7cc3)

