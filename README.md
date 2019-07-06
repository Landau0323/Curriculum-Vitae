# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|佐藤 大輔(さとう だいすけ)|
|HP|http://www2.yukawa.kyoto-u.ac.jp/~daisuke.satoh/Daisuke_Satow/Welcome.html|
|mail|daisuke.sato0323@gmail.com|

## スキル

### プログラミング言語
- 現在、業務で利用している
  - python
    - numpy,pandas,jupyter notebook,scikit-learn,tensorflow,keras等を用いて機械学習に使用。
    - ROSを使ってロボット制御アルゴリズムを開発。
    - OpenCVを使って画像認識関連のアルゴリズムを開発。
- 業務で使用したことのある言語
  - C++ 
    - paizaランキングS取得
    - 趣味では自律移動ロボットの制御アルゴリズムを勉強したことがある(Udacity)
    - 物理で使う数値計算用
  - C
    - 物理で使う数値計算用
  - FORTRAN
    - 物理で使う数値計算用

### 自然言語
- 日本語
  - ネイティブ
- 英語
  - TOEIC940点
  - 職務で日常的にコミュニケーションに使用した(フランス5か月・アメリカ1年・イタリア1年半・ドイツ2年)
  - 国際学会での口頭発表・海外の大学でのセミナー発表経験あり(合計17回)
  - 英語論文を読み書きできる(物理の論文を20本国際誌から出版)
- イタリア語
  - 日常会話レベル

## 強み
-  新しいものを作るうえで必要な過程である、試行錯誤しながらの開発経験が豊富（研究経験5年）。
-  学会や論文などから、必要な技術は短期間でキャッチアップできる。
-  物理の研究をした経験から、数理的な素養がある。

## やったことはないが興味を持って勉強しているもの
-  移動自律型ロボットの制御アルゴリズムの研究開発（ドローンや車の自動運転など）
-  実社会の課題への量子コンピュータのアルゴリズム適用

## 出版物
### 機械学習関係
to be updated...

### 物理関係
[論文リスト（物理）](http://inspirehep.net/search?ln=ja&p=find+a+d.+satow&of=hb&action_search=%E6%A4%9C%E7%B4%A2)

## 特許
- 

## 学会発表
### 機械学習関係
- SSII2019(ポスター発表) to be written
- ICIAM2019(口頭発表) to be written

### 物理関係
to be updated...

## エンジニアリング以外での職務上の貢献
- 人工知能学会への加入・学会誌登録を提案、実行
- 知人の物理研究者・エンジニア3名を勧誘・エンジニアとして入社させた
- セミナー講師のサーベイ・依頼（3名）

## 職務経歴
### 2013/04 - 2014/09: [理化学研究所(アメリカBrookhaven National Laboratory勤務)](http://www.riken.jp/)
### 2014/10 - 2016/02: [Fondazione Bruno Kessler(イタリア)](https://www.fbk.eu/en/)
### 2016/03 - 2018/03: [Goethe Universität(ドイツ)](http://www.goethe-university-frankfurt.de/en?locale=en)
職務:
理論物理学（主として素粒子物理）の研究　

職階:
ポスドク研究員

### 2018/04 - : [Arithmer株式会社](https://arithmer.co.jp/)
職務:
画像認識・ロボット制御・機械学習関連の研究開発

職階:
Robo Sense部門室長

- 製薬工程（震蘯）自動化ロボット開発
  - 2018年4月から2019年6月
  - 概要：製薬工程で必要となる、熟練の技術者の動きをモーションキャプチャで取得してロボットに再現させるソフトウェアを開発した。
  - 使用技術：P型軌道の編集（3次元ベクトルおよび四元数の粗視化・スプライン補間）/python
  - 開発した軌道編集技術は1件特許出願済
  
- 似顔絵ロボットデモ開発
  - 2018年5月から7月
  - 概要：人間の顔写真から似顔絵を作成し、それを6軸型ロボットに描かせるデモを開発した。
  - 使用技術:画像認識(顔検出・エッジ検出)/ROS(P型軌道によるアーム制御)/python,numpy,OpenCV

- 画像採寸AI開発(機械学習方式)
　- 2018年9月から11月
　- 概要：人間が写っている写真から機械学習を使って、体の各部位の寸法を推定するソフトウェアを開発した。
　- 使用技術:画像認識(背景除去・輪郭生成)/輪郭からの特徴量計算/特徴量からの回帰/教師データの設計・収集依頼/python,pandas,numpy,OpenCV,tensorflow,keras
　- 開発した技術は1件特許登録済
	
- 検査機パラメータ自動設定PoC
  - 2018年12月から2019年1月まで
  - 概要：ペットボトルの画像検査機のパラメータを品種に応じて自動設定できるかどうか、実証実験を行った。
  - 使用技術：画像処理（2値化、連続成分の抽出、面積計算、トリミング、left/rightmostピクセルの特定、lab色空間への変換、ピクセル値の平均の計算）/python,opencv

- 3DビジョンピッキングロボットPoC
  - 2018年12月から2019年6月まで
  - 概要：3Dセンサーつきのロボットによる、ビジョンピッキングシステムの実証実験を行った。
  - 使用技術：画像認識(semantic segmentation)、QRコード読み取り、ロボット制御（アーム制御・信号入出力・ステートマシン・順/逆運動学）。あと、3Dデータ操作開発（点群のトリミング・法線推定）のマネージメント/python,openCV,Open3D,ROS,tensorflow,keras,numpy

## 学歴

|年|学校名||
|---|-----|----|
|2004/03|広島県立尾道北高校|卒業|								
|2004/04|京都大学　理学部|入学|	
|2008/03|京都大学　理学部|卒業|						
|2008/04|京都大学大学院　理学研究科　物理学・宇宙物理学専攻　原子核理論研究室博士前期課程|入学|		
|2010/03|京都大学大学院　理学研究科　物理学・宇宙物理学専攻　原子核理論研究室博士前期課程|卒業|
|2010/04|京都大学大学院　理学研究科　物理学・宇宙物理学専攻　原子核理論研究室博士後期課程|入学|
|2013/03|京都大学大学院　理学研究科　物理学・宇宙物理学専攻　原子核理論研究室博士後期課程|卒業(博士号取得)|

## 趣味
- ハイキング
- バッティングセンター
- 読書
  - SF・歴史小説・自然科学
- 旅行
  - 特に5年間外国（フランス・アメリカ・イタリア・ドイツ）に住んでいた時は、様々な街に行きました。	

## 本経歴書の作成に参考にしたリンク
- [オープン職務経歴書を書いてみた - Qiita](https://qiita.com/Sa2Knight/items/4af2f24fac9290d26119)
- [okohs/Curriculum-Vitae-template](https://github.com/okohs/Curriculum-Vitae-template)
- [tomo3141592653/Curriculum-Vitae](https://github.com/tomo3141592653/Curriculum-Vitae)
  - リポジトリのフォーク元
																																																																																																							
