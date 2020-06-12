「ディープラーニングと物理学2020　オンライン」とはオンラインWeb会議システムを利用したセミナーです。

登録する際のメールアドレスは、できるだけ大学もしくは研究機関のものをご使用ください。

* Cisco Webex (Zoomと類似のオンラインミーティングアプリ）のミーティングURLおよびパスワードは、先着順200名様に限り、登録されたメールアドレスに送信されます。転載・転送は控えてください。
* ご参加の際は毎回の登録をお願いします。
* URLが掲載されたメールは当日の朝までに送られます。
* 締切は前日の夜11時までとします。


* 参加時の表示名は「登録時の名前＠登録した機関名」に設定してください。
* ハウリング防止のため、原則ヘッドフォン着用をお願いします。
* ノイズを防ぐためのミュートへご協力ください。

世話人:　橋本幸士（大阪大）、富谷昭夫（理研BNL）、永井佑紀（原子力機構）、田中章詞（理研iTHEMS）（順不同)

* [第2回：　橋本幸士「深層学習と時空」](#第2回) 5/28
* [第1回：　永井佑紀「精度保証された機械学習分子動力学法：自己学習ハイブリッドモンテカルロ法」](#第1回) 5/14

# 第4回
日時: 2020年6月18日10:30-11:30(JST)<br>
発表者: 唐木田 亮 (産総研)<br>
発表題目: 深層学習の数理: 統計力学的アプローチ<br>

[登録フォーム](https://docs.google.com/forms/d/e/1FAIpQLSdJtfmkcJJ8gagNZ0_XJH7m5l1gPA4v0VsfxJUri5uxAOGSNA/viewform)

概要: 本講演では, 深層学習の数理的な理解を目的とした近年の統計力学的解析を紹介する. 具体的には, 深層学習の平均場理論, ランダム行列理論, さらにNeural Tangent Kernel (NTK)理論をとおして学習ダイナミクスの理解へとつながる一連の流れを解説する. 
深層学習では, 性能の理論的な保証や, 最適なモデルや学習手法の設定に多くの課題があり, 数理的な研究が日進月歩で進んでいる. その中で統計力学的なアプローチは, 深層学習におけるパラメータ初期値がランダム行列であること, モデルの大自由度極限(ニューラルネットワーク各層の"幅"が十分に大きいこと)に着目した枠組みで, 様々なモデルアーキテクチャに普遍的に適応できる点に特徴がある. 平均場理論は, 勾配の大きさを巨視的変数として定式化することで, 訓練が進みやすいモデルとパラメータの設定を相転移によって定量的に説明する[1]. NTK理論は, 初期値まわりの摂動の範囲で学習が進む設定があることを発見し, 学習の大域収束と汎化性能に一定の理解を与える[2]. 
本講演ではこのような統計力学的アプローチを, 歴史的な背景も含めつつ簡単に概観したい. また, このアプローチを使うことで, 再急降下法のハイパーパラメータ(学習率)の設定指針[3]やBatch NormalizationとLayer Normalizationの効果の違い[4]のようなアルゴリズムの問題に対して, 定量的な説明を与えられることも紹介する.

[1] Deep information propagation. Samuel S Schoenholz, Justin Gilmer, Surya Ganguli and Jascha Sohl-Dickstein, ICLR 2017 (arXiv:1611.01232). <br>
[2] Neural tangent kernel: Convergence and generalization in neural networks. Arthur Jacot, Franck Gabriel and Clément Hongler, NeurIPS 2018 (arXiv:1806.07572). <br>
[3] Universal Statistics of Fisher Information in Deep Neural Networks: Mean Field Approach. RK, Shotaro Akaho and Shun-ichi Amari, AISTATS 2019 (arXiv:1806.01316).<br>
[4] The Normalization Method for Alleviating Pathological Sharpness in Wide Neural Networks. RK, Shotaro Akaho and Shun-ichi Amari, NeurIPS 2019 (arXiv:1906.02926).<br>


# 第3回　

第三回(6/11)は、ライトニングトークで構成されます。<br>
日時: 2020年6月11日10:30-11:30(JST)<br>
発表者：希望者<br>

講演者: 野村悠祐 (理研CEMS)<br>
講演題目: 深層ボルツマンマシンを用いた量子多体波動関数の厳密な構築<br>
講演概要: 量子多体系の波動関数を深層ボルツマンマシンを用いて厳密に表現する方法を紹介する(Carleo, Nomura, Imada, Nature Communications 2018)。<br>

[講演スライド](./slides/Nomura_presentation_2020_06_11.pdf)

講演者: 林祐輔 (Japan Digital Design, Inc. ただし講演は個人としての活動)<br>
講演題目: 表現学習の確率熱力学的解釈<br>
講演概要: 表現学習とは，画像，音声，自然言語，時系列データといった多様な生データから，目的のタスクを解くために意味のある特徴量を生成する方法を，統計モデル自身に考えさせるアプローチのことを指す．この発表では，表現学習と確率熱力学の間にアナロジーが成り立つことを紹介し，準静的過程に対応する熱力学的操作が転移学習のようなデータのドメインを跨ぐ学習において有用であることを説明する．<br>

[講演スライド](./slides/Hayashi_DLAP2020.pdf)

講演者: 北沢正清 (大阪大学)<br>
講演題目: SU(3)非可換ゲージ理論のトポロジー分類への機械学習の適用<br>
講演概要: 4次元畳み込みニューラルネットワークを用いて、SU(3)非可換ゲージ理論の多次元データを学習し、トポロジカル電荷を推定した。99%という高い正答率を得た成果などを報告する。<br>

[講演スライド](./slides/Kitazawa_200611DLAP_NNQ.pdf)


講演者: 大塚啓(KEK)<br>
講演題目: 深層学習を用いた弦理論のランドスケープ<br>
講演概要: 本講演では、背景磁場のあるCalabi-Yau 多様体上にコンパクト化されたヘテロ型弦理論に対して、深層学習の一種であるオートエンコーダーによる次元削減とクラスタリングを適用する。 特に、フェルミオンの世代数と余剰次元空間の曲率に強い相関があることを紹介する[1]。[1] H. Otsuka and K. Takemoto, JHEP 05 (2020), 047.<br>

[講演スライド](./slides/Otsuka_20200611.pdf)

講演後には、参加者に「さらに詳しく聞きたい講演」についてのアンケートを実施し、そのアンケート結果をもとに、今後のオンラインセミナーの講演を決めていこうと考えています。<br>

[発表希望者用フォーム](https://docs.google.com/forms/d/e/1FAIpQLSfFsyop94o5mV_2ab6qB_PjpWGUN_77C_dZ44hjmXGC_MHEKg/viewform)

[参加希望者（発表なし）用フォーム](https://docs.google.com/forms/d/e/1FAIpQLSfXiD5kB106iFpglgvTa_TjvoDH03EPFRB1hkSS8N0GZNyrjQ/viewform)


ライトニングトークの構成は以下の通りです：<br>
　１）ご講演は３-10分間、その後の質疑応答は２分間、合計で５-15分間となります。<br>
　　（講演時間が終了すると座長から終了のお知らせがありますのでご協力お願いします）<br>
　２）スライドはpdf (pptもしくはkeynote)数枚です。<br>
　　　講演タイトルと所属、お名前、メールなどの連絡先を記載ください。<br>
　　　見本として[次のもの](./slidesample.pdf)をご参考に。<br>
　３）講演＋質疑時間の５分間が終了した後は、チャット機能で、参加者からの質問にお答えください。<br>
　４）ご講演タイトル（仮）を、上記登録フォームで記入ください。<br>
発表者希望者の締切は6/9の夜11時とします。<br>
発表内容は、ご自身あるいは共同研究者のオリジナルな研究に限ります。<br>

# 第2回
日時: 2020年5月28日10:30-11:30(JST)<br>
発表者: 橋本幸士(大阪大学)<br>
発表題目: 深層学習と時空

[登録フォーム](https://docs.google.com/forms/d/e/1FAIpQLSeWYyvnJC-sHLrit6d-RebOaaDeBFEFc3wsMtlASIJRniLGEg/viewform)

[講演スライド](./slides/Hashimoto20200528.pdf)

概要：
本講演では、深層ニューラルネットワークを時空とみなせるかどうかについて、議論する。特に、量子重力理論として研究が進むホログラフィー原理そのものを深層学習とみなす手法について紹介する。
学習されたニューラルネットワークの解釈可能性は、機械学習を物理学に応用する際に最も重要な観点の一つである。ニューラルネットワークの構造を対称性などにより規定することで制約を加え解釈可能にすることは学習を効率的にすることにつながっている。一方で、深層ボルツマンマシンはそもそもスピン系が原子配列しているものの一般化と考えられることから、ニューラルネットワークそのものが時空として機能している例が存在している。このような中で、量子重力理論と機械学習の融合を目指す研究が生まれた。この20年間の量子重力理論の研究において、最も重要な位置を占めているのはホログラフィー原理[1]であり、そこでは、量子重力理論と等価な、重力を含まない（時空次元の低い）量子系が存在し、重力の時空はそこから創発する。このホログラフィー原理で創発する時空を、教師つき学習の深層ニューラルネットワークと同一視し、時空のメトリックを重みと考えることで、創発時空を量子系のデータから決定する手法[2][3][4]を本講演では紹介する。

[1] The Large N limit of superconformal field theories and supergravity Juan Martin Maldacena Published in: Int.J.Theor.Phys. 38 (1999) 1113-1133, Adv.Theor.Math.Phys. 2 (1998) 231-252 • e-Print: hep-th/9711200 [hep-th]<br>
[2]Deep learning and the AdS/CFT correspondence Koji Hashimoto, Sotaro Sugishita, Akinori Tanaka, Akio Tomiya Published in: Phys.Rev.D 98 (2018) 4, 046019 • e-Print: 1802.08313 [hep-th]<br>
[3] Deep Learning and Holographic QCD Koji Hashimoto, Sotaro Sugishita, Akinori Tanaka, Akio Tomiya
Published in: Phys.Rev.D 98 (2018) 10, 106014 • e-Print: 1809.10536 [hep-th]<br>
[4] Deep Learning and AdS/QCD Tetsuya Akutagawa, Koji Hashimoto, Takayuki Sumimoto e-Print: 2005.02636 [hep-th]<br>


# 第1回
日時: 2020年5月14日10:30-11:30(JST)<br>
発表者: 永井佑紀(原子力機構)<br>
発表題目: 精度保証された機械学習分子動力学法：自己学習ハイブリッドモンテカルロ法 

[登録フォーム](https://docs.google.com/forms/d/e/1FAIpQLSedDoIH3RW6skBAzu84BkZ8yJTapYxC237BztfnPGhVdGgLLg/viewform)

[講演スライド](./slides/Nagai_SLHMC20200514.pdf)

概要：
本講演では、2008年に開発された機械学習分子動力学法について解説するとともに、学習精度に計算精度が依存しない機械学習シミュレーションである自己学習ハイブリッドモンテカルロ法について紹介する。<br>
第一原理計算で得られたポテンシャルを再現するようなニューラルネットワーク(ANN)を構築して分子動力学を実行するのが機械学習分子動力学法である。ANNを構築する際の最適なトレーニングデータは、元々の第一原理分子動力学法で生成される原子配置とそのポテンシャルである。しかしながら、第一原理分子動力学法の計算負荷が高いために機械学習分子動力学法を用いるのであるから、元々の第一原理分子動力学法でデータを集めるのは本末転倒である。そのため、通常は、様々な原子配置とそのポテンシャルデータを大量に作成することで、目的の機械学習分子動力学法と同じようなポテンシャルを生成するANNを構築している。しかしながら、構築されたANNが元々の第一原理計算のポテンシャルを再現するという保証はない。さらに、4元素以上で構成されるような系の場合には、長時間の機械学習分子動力学法では計算が不安定になることがあり、機械学習分子動力学法の計算の精度や妥当性については常に慎重な議論が必要であった。<br>
本講演では、自己学習モンテカルロ法のアイディア[1]を用いることで、得られた結果が統計的に厳密にオリジナルの第一原理計算分子動力学法の計算結果と等しい手法を開発したことを報告する[2]。
そして、その手法を用いて、4元素系でも精度よく計算ができることを示すため、フォノン誘起超伝導体YNi2B2Cのフォノン計算の結果を報告する。<br>

[1] J. Liu, Y. Qi, Z. Y. Meng, and L. Fu, Phys. Rev. B 95, 041101(R) (2017).; J. Liu, H. Shen, Y. Qi, Z. Y. Meng, and L. Fu, Phys. Rev. B 95, 241104(R) (2017).; YN, H, Shen, Y. Qi, J. Liu, and L. Fu, Phys. Rev. B 96, 161102(R) (2017)<br>
[2] YN, M. Okumura, K. Kobayashi and M. Shiga, arXiv:1909.02255<br>

# 過去のワークショップ研究会
[Deep Learning and physics2019](http://kabuto.phys.sci.osaka-u.ac.jp/~koji/workshop/DLAP2019/)<br>
[Deep Learning and physics2018](http://kabuto.phys.sci.osaka-u.ac.jp/~koji/workshop/DLAP2018/)<br>
[Deep Learning and physics](http://kabuto.phys.sci.osaka-u.ac.jp/~koji/workshop/tsrp/Deep_Lerning.html)

