# 深層学習×音楽情報処理勉強会
（WIP）
2022年度に筑波大学 人と音の情報学研究室によって行われた深層学習による音楽情報処理の勉強会のスライドとjupyter notebookによる実装をまとめたものです．

2023年7月4日現在準備中です．一生準備中かもしれません．
もし間違い等があれば，issueにて報告お願いします．

## 本勉強会の立ち位置
本研究は，音楽・楽譜の情報処理において，Deep learningを適用する方法についてを主に解説したものです．

音楽情報処理にもDeep learningの波が来た．だから，
- 音楽情報処理特有の問題もあって，それに対応できるような知識を解説したい．
- 音処理・機械学習触ったことありますのレベルから効率的に最新知識を繋ぐためのものが欲しい．
という山本個人の想いと，
- これによってできることが増えた．Deep learningを使えば自分の叶えたいことが研究できるかもしれないから知見を持ちたい．
- ソロプレイが主の弊研究室では，これを一人で勉強しなければならないが，さすがにきつい．
というビギナーのメンバーたちのニーズにこたえてはじめました．

なお，Deep以前の音楽情報処理に関しては，
FMP Notebooks https://www.audiolabs-erlangen.de/resources/MIR/FMP/C0/C0.html
Pythonで学ぶ音楽信号処理と音楽アプリ開発 https://www.wizard-notes.com/music-analysis
などが非常に詳しいです．

また，最新のツール等に関してはこちらにまとめています．
https://github.com/yamathcy/awesome-music-informatics 

さらに，日本の音楽情報処理のレジェンドたちによる素晴らしい概説の書籍が刊行予定らしいです．
https://www.coronasha.co.jp/np/isbn/9784339013726/


## pdfおよびgoogle colab リンク
- 1. イントロダクション
  - [pdf] (/pdf/deep-people_01.pdf)
  - colab なし
- 2. 音楽ファイルについて: 
  - [pdf] (/pdf/deep-people_02.pdf)
  - colab https://colab.research.google.com/drive/1bvYDQiJaSPf4HbcCKh2ZZN6CSX0lB8Rw?usp=sharing
- 3. 音響特徴量について： （注：GTZANデータセットが利用不可になっている可能性あり）
  - [pdf] (/pdf/deep-people_03.pdf)
  - colab https://colab.research.google.com/drive/1Y0rcJZu-xFhH5eu1cmOweAg57MK0yP0V?usp=sharing
- 4. ニューラルネットワーク基礎：
  - [pdf] (/pdf/deep-people_04.pdf)
  - colab
- 5. 畳込みニューラルネットワークによる音分類：
  - [pdf] (/pdf/deep-people_05.pdf)
  - colab https://colab.research.google.com/drive/1Fl7bLZ3d0YgtbqRFkiYk3dH28y9E0SNs?usp=sharing
- 6. （畳込み）再帰型ニューラルネットワークによる系列分類：
  - [pdf] (/pdf/deep-people_06.pdf)
  - colab 
- 7. フレームレベルの分類問題 - 自動採譜を対象に：
  - [pdf] (/pdf/deep-people_07.pdf)
  - colab 
- 8. audio-to-audio：
  - [pdf] (/pdf/deep-people_08.pdf)
  - colab 
- 9. 音楽生成基礎: 
  - [pdf] (/pdf/deep-people_09.pdf)
  - colab 
- 10. variational autoencoder:
  - [pdf] (/pdf/deep-people_10.pdf)
  - colab 
- 11. GAN:
  - pdf 
  - colab 


## 更新履歴
- 2023.07.09 音楽生成（楽譜）の超基礎と，VAEについてのpdfをあっぷしました．
- 2023.07.08 NN基礎，Audio-to-Audioの基礎についてのpdfをアップしました． それぞれラボのM2松本馨輝くんとM2湯谷承将くん（ともに当時M1）が作成してくれました！
- 2023.07.04 音楽データ処理の基礎と音楽特徴量，CNNについてのpdfをアップしました．
- 2023.07.05 序章の説明（なぜ音楽情報処理に深層学習がが必要か），RNNについて，音楽情報処理の実際のタスクについてのpdfをアップしました．

## 参考資料
基本的に資料pdf内に記入していますが，ここでは全体的に参考にした資料を掲載しています．
- https://cs230.stanford.edu/
- https://www.audiolabs-erlangen.de/fau/professor/mueller/teaching/2022s_apl 
- https://www.audiolabs-erlangen.de/fau/professor/mueller/bookFMP
- https://mac.kaist.ac.kr/~juhan/gct634/ ← 特に参考にさせていただきました．


