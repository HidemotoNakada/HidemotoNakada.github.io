---
layout: default
---
# その他(日本語) 

- **ROS準拠ロボット及びエッジを活用したIoTシステムの性能評価**    
佐々木 怜名, 竹房 あつ子, 中田 秀基, 小口 正人
, *xSIG2023*    , 2023 



- **JuliaとActorを用いた強化学習フレームワークの提案** [[Paper](dataDir/xsig23nakada_poster.pdf)]  <span onmouseover="document.getElementById('xsig23nakada_poster').style.display = 'block'"  onmouseout="document.getElementById('xsig23nakada_poster').style.display = 'none'">[abst]</span>   
中田 秀基
, *xSIG2023*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig23nakada_poster"> 並列強化学習には複雑な並行制御が必要となり、単純なFork-Join型の並列計算にはそぐわない。本発表ではJulia言語を対象としてActorを導入し、その上に汎用性の高い教科学習フレームワークを構築する。</div> </blockquote>



- **5G SA 環境における IoT システムのためのモバイル通信性能評価**  <span onmouseover="document.getElementById('xsig23ito').style.display = 'block'"  onmouseout="document.getElementById('xsig23ito').style.display = 'none'">[abst]</span>   
伊藤 千紗, 竹房 あつ子, 中田 秀基, 小口 正人
, *xSIG2023*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig23ito"> IoT機器から収集された様々なセンサデータをクラウドで蓄積,解析し,活用することが期待されている. しかし,モバイル環境にあるIoTデータの収集では,各種サービスで要求される通信スループットや通信遅延を維持することができるかが課題となる. 高性能なモバイル通信技術として, 5Gの活用が期待されているが,小規模データが大量に送信されるような, IoT通信で利用する際の性能特性は明らかではない. 本研究では, IoT用通信ライブラリを提供するSINETStreamを用いて, 5G SA (Standalone)環境におけるIoTデータ通信性能を調査する. 5G SAとは, 4G用のコア装置を流用するNSA (Non-SA)に対して, 5G専用のコア装置を導入して5G専用の基地局装置を使用するものである. 実験結果から,モバイル通信における5G SAのスループットが従来のLTEよりも高くなること,通信スループットを高めるにはマルチスレッド通信が有効であることを確認した. 一方で, IoT通信のように小規模のメッセージを大量にクラウドに送信するような通信パターンではアップロード帯域で律速され,広いダウンロード帯域を持つ5Gモバイル通信を有効利用するのが難しいことも示唆された.</div> </blockquote>



- **5G 環境での IoT システムのためのモバイル通信性能の評価**  <span onmouseover="document.getElementById('dicomo23ito').style.display = 'block'"  onmouseout="document.getElementById('dicomo23ito').style.display = 'none'">[abst]</span>   
伊藤 千紗, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2023)シンポジウム*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo23ito"> IoT 機器から収集された様々なセンサデータをクラウドで蓄積, 解析し, 活用することが期待されている. しかし, モバイル環境にある IoT データの収集では, 各種サービスで要求される通信スループットや通信遅延を維持することができるかが課題となる. また, 高性能なモバイル通信技術として5G の活用が期待されているが, 小規模データが大量に送信されるようなIoT 通信で利用する際の性能特性は明らかではない. 本研究では, IoT 用通信ライブラリを提供する SINETStream を用いて, 5G環境における IoT データ通信性能を調査する. 5GとはLTEをさらに進化させた通信規格であり, 高速大容量, 低遅延, 多数同時接続の特徴を持つ. また, 5G SA(Standalone)は, 4G 用のコア装置を流用する NSA (Non-SA) に対して, 5G 専用のコア装置と基地局装置を使用するものである. 実験から, 5G SAではIoT通信スループットが従来のLTEよりも高くなる多いこと, 通信スループットを高めるにはマルチスレッド通信やデータ圧縮が有効であることを確認した. 一方で, IoT通信のように小規模のメッセージを大量にクラウドに送信するような通信パターンではアップロード帯域で律速され, 広いダウンロード帯域を持つ5Gモバイル通信を有効利用するのが難しいことも示唆された.</div> </blockquote>



- **ROS準拠ロボット及びエッジを活用したストリーム処理を行うIoTシステムの構築と評価**  <span onmouseover="document.getElementById('dicomo23sasaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo23sasaki').style.display = 'none'">[abst]</span>   
佐々木 怜名, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2023)シンポジウム*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo23sasaki"> IoT機器に装備されたセンサによって収集したデータを活用して，お年寄りやペットの見守り，室内環境監視などを目的とした，スマートホームのためのサービスが実現されている．個々の家庭のデータをクラウドに収集するIoTシステムを構築するには，通信遅延の低減，転送データ量の削減，プライバシの保護への対策も必要となる．室内環境で多様なデータを収集する場合，一般家庭に多数のセンサを設置するとコストが高くなるだけでなく，必要な情報を得るためのセンサの再配置も容易ではない．よって，我々はROSで実装した車輪型移動ロボット，エッジ，クラウドを活用したIoTシステムを実装し，有用性を確認した．しかし，ROSの通信性能についてはより詳細な調査が必要である．本研究では，ROSとROSの後継バージョンであるROS2の性能特性を調査するため，異なる通信環境におけるセンサロボットとエッジ間の通信時間とスループットを測定し，センサロボットを活用したスマートホームにおける技術的課題を明らかにする．</div> </blockquote>



- **報酬最大化を目的とする行動計画・実行・対話・推論の統一的制御機構**  <span onmouseover="document.getElementById('jsai23ichisugi').style.display = 'block'"  onmouseout="document.getElementById('jsai23ichisugi').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 竹内 泉, 佐野崇
, *人工知能学会全国大会（第37回）*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai23ichisugi"> 我々は将来の汎用人工知能の実現に向けて、再帰的強化学習を用いて思考や行動を制御するAIアーキテクチャを開発している。エージェントは統一的な制御のもと、環境に対して行動し、他者と対話し、環境の状態を推論して、報酬の最大化を目指す。本稿では、まず全体アーキテクチャを説明したあと、その上で動作する行動計画の機構を提案する。我々はプロトタイプシステムを実装し提案機構の動作を確認した。</div> </blockquote>



- **Improving symbolic music pre-training using bar-level variational inference**  <span onmouseover="document.getElementById('jsai23fu').style.display = 'block'"  onmouseout="document.getElementById('jsai23fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *人工知能学会全国大会（第37回）*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai23fu"> Pre-training has been a significant trend in NLP nowadays. BERT-liked models showed power in solving downstream tasks. Inspired by the masked language model pre-training strategy, context could be learned by recovering the masked musical tokens. In our previous work, we tested the ability of MusicBERT and improved the model structure. The models worked well on the melody extraction task (a token-level classification task). But when facing sequential tasks like composer and emotion classification, our previous models&#x27; performance still needs improvement. The possible reason is that, the previous pre-training method cannot learn the general information of the sequence from the context. We proposed the bar-level recovery pre-training task using variational inference to solve this problem. Our proposed method aims to better learn general sequential information from context. In our in-progress work, we compared our method with the previous works.</div> </blockquote>



- **Attention機構を用いた物体中心表現学習** [[Paper](dataDir/prmu2305.pdf)] [[Slides](dataDir/prmu2305-slides.pdf)]  <span onmouseover="document.getElementById('prmu2305').style.display = 'block'"  onmouseout="document.getElementById('prmu2305').style.display = 'none'">[abst]</span>   
中田秀基, 麻生 英樹
, *信学技報, vol. 123, no. 30, PRMU2023-13*   , pp. 68-73  , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="prmu2305"> 動画像を用いた表現学習では、個々の物体をマスクで分離した上で個別に物体表現を教師なしで学習する手法が広く用いられている。これらの表現学習手法の性能は高く、多くのダウンストリームタスクで高い性能を示しているが、計算量が膨大であるという問題点がある。われわれは、従来の動画表現学習手法であるViMONをベースとし、これにAttention機構を導入することで、性能を維持しつつ計算量を低減することを試みた。Attention機構を導入する位置によって2つの手法を提案し、それぞれ実装を行い、再構成誤差、実行時間、ダウンストリームタスクの性能で評価を行った。その結果、ベースとなる手法と比較して、より高い性能を示しながら大幅な計算量の低減できることを確認した。</div> </blockquote>



- **Julia言語を用いた高性能並列実行環境の構築** [[Paper](dataDir/pro2303nakada.pdf)] [[Slides](dataDir/pro2303nakada-slide.pdf)]  <span onmouseover="document.getElementById('pro2303nakada').style.display = 'block'"  onmouseout="document.getElementById('pro2303nakada').style.display = 'none'">[abst]</span>   
中田秀基
, *情報処理学会プログラミング研究会*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pro2303nakada"> Julia言語は科学技術計算向けに設計されたインタラクティブ言語として広く注目を集めている。Juliaはネイティブで分散計算をサポートしており、Remote Procedure Callに類した通信が可能である。また、JuliaはMPIをサポートしており、高性能計算環境の高速なノード間通信を利用できる。われわれはすでに、Juliaネイティブな通信機構を用いて、JuliaにActorを導入する手法について発表しているが、高性能計算環境での評価はいまだされていない。本発表では、高性能計算環境でのActorの評価を行う。また、Julia言語に適した並列分散言語のコンストラクトについて議論する。</div> </blockquote>



- **ROS 準拠ロボット及びエッジを用いた 環境情報収集・ストリーム処理を行う IoT システムの構築と評価**  <span onmouseover="document.getElementById('deim23sasaki').style.display = 'block'"  onmouseout="document.getElementById('deim23sasaki').style.display = 'none'">[abst]</span>   
佐々木 怜名, 竹房 あつ子, 中田 秀基, 小口 正人
, *第15回データ工学と情報マネジメントに関するフォーラム (DEIM)*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim23sasaki"> IoT 機器に装備されたセンサによって収集したデータを活用して，お年寄りやペットの見守り，コロナ禍 における室内環境監視などを目的とした，スマートホームのためのサービスを実現している.個々の家庭のデータを クラウドに収集する IoT システムを構築するには，通信遅延の低減，転送データ量の削減，プライバシの保護への対 策も必要となる.本研究では，ROS で実装された車輪型移動ロボットを用いて室内環境情報を収集し，エッジを介し てクラウド上での解析処理を行う，スマートホームのための IoT システムの構築と評価を行う.また，構築したシス テムを活用し，室内二酸化炭素濃度監視アプリケーションを試作した.</div> </blockquote>



- **5G SA 環境における IoT システムの通信性能調査**  <span onmouseover="document.getElementById('deim23ito').style.display = 'block'"  onmouseout="document.getElementById('deim23ito').style.display = 'none'">[abst]</span>   
伊藤 千紗, 竹房 あつ子, 中田 秀基, 小口 正人
, *第15回データ工学と情報マネジメントに関するフォーラム (DEIM)*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim23ito"> IoT 機器から収集された様々なセンサデータをクラウドで収集, 解析し, 活用することが期待されている. しかし, モバイル環境にある IoT データの収集では, 各種サービスで要求される通信スループットや通信遅延を維持 することができるかが課題となる. 高性能なモバイル通信技術として, 5G の活用が期待されているが, その性能も明 らかでない. 本研究では, 5G SA (Standalone) 環境における IoT データ通信性能を調査する. 5G SA とは, 4G 用のコ ア装置を流用する NSA (Non-SA) に対して, 5G 専用のコア装置を導入して 5G 専用の基地局装置を使用するものであ る. 5G SA 環境で, IoT 用通信ライブラリを提供する SINETStream を用いて基本性能を調査する.</div> </blockquote>



- **ROS 準拠ロボット及びエッジを用いた環境情報収集・ストリーム処理を行う IoT システムの構築**  <span onmouseover="document.getElementById('ipsj23sasaki').style.display = 'block'"  onmouseout="document.getElementById('ipsj23sasaki').style.display = 'none'">[abst]</span>   
佐々木 怜名, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第85回全国大会*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj23sasaki"> スマートホームでは，IoT 機器に装備されたセンサ で収集したデータを，お年寄りやペットの見守り，コ ロナ禍における室内二酸化炭素濃度監視などを目的 とした様々なサービスに活用している.個々の家庭の データをクラウドに収集する IoT システムを構築する には，通信遅延の低減，転送データ量の削減，プライ バシの保護への対策も必要となる.本研究では，ROS(Robot Operating System)で実装された車輪型移 動ロボットを用いて室内環境情報を収集し，エッジを 介してクラウド上での解析処理を行う，スマートホー ムのための IoT システムの構築を目指す.我々は，提 案システムのセンサロボットとエッジ間における処理 方法の検討を行った.本稿では，センサロボット とクラウド間において，エッジを介したセンサデータ 処理方法の検討を行い，CO2 濃度リアルタイム監視シ ステムを試作する.</div> </blockquote>



- **5G SA環境でのIoTシステムのための通信性能の調査**  <span onmouseover="document.getElementById('ipsj23ito').style.display = 'block'"  onmouseout="document.getElementById('ipsj23ito').style.display = 'none'">[abst]</span>   
伊藤 千紗, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第85回全国大会*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj23ito"> IoT (Internet of Things) 機器から収集された様々な センサデータをクラウドで収集，解析し，活用すること が期待されている.しかし，モバイル環境にある IoT データの収集では，自動運転車や倉庫内自走ロボット などの各種サービスで要求される通信スループットや 通信遅延を維持することが必要である. これらの通信 スループットや通信遅延の性能要求を満たすには, 現在 のモバイル通信技術である LTE では難しく, 性能向上 が課題となる. 高性能なモバイル通信技術として，5G の活用が期待されているが, 新しい通信であるため IoT への実用化は十分にされておらず, IoT に利用するため の性能特性については明らかではない.本研究では，5G SA (Stand Alone) 環境での IoT データ通信性能を調査する.5G SA とは，4G 用のコ ア装置を流用する NSA (Non Stand Alone) に対して， 5G 専用のコア装置と基地局装置を使用するものである [1]. 国立情報学研究所内に設置された 5G SA 環境で， IoT 用通信ライブラリを提供する SINETStream を用 いて基本性能を調査する.</div> </blockquote>



- **ネットワークエッジを活用したデータ収集システムに向けたMQTTの性能計測**  <span onmouseover="document.getElementById('os2302tou').style.display = 'block'"  onmouseout="document.getElementById('os2302tou').style.display = 'none'">[abst]</span>   
董 允治, 中田秀基, 谷村勇輔
, *情報処理学会システムソフトウェアとオペレーティング・システム研究会*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os2302tou"> 近年、IoT（Internet of Things）技術の発展に伴い、エッジとクラウドを適切に使い分けるアーキテクチャの設計やそれを実現する技術が必要となっている。本研究では、データソースにできるだけ近い場所で不要データの削減、複数データの集約、各種処理を行うことで、エッジからクラウドにまたがるデータ収集システムを効率的に実現する手法を明らかにすることを目指している。その最初の取り組みとして、IoT向けの軽量な通信プロトコルであるMQTTに着目し、MQTTを用いた中継サーバが介在するシステムを提案し、予備評価実験を行った。ローカル環境、およびクラウドと繋がる環境においてMQTT Brokerに対するストレステストを実施し、送信データのサイズや頻度を変えてBrokerを動かすサーバの負荷状況やデータの転送遅延を検証した。本実験により、Brokerによるサーバ資源消費が十分に小さいことを確認し、ネットワークエッジに配置するサーバで各種データ処理を行える見込みを立てることができた。また、中継サーバを追加しても、遅延が極端に大きくなることはなく、データ量が多い場合にも許容遅延内で転送できることを確認できた。</div> </blockquote>



- **Pythonで学ぶ機械学習モデルと画像分類への応用**    
中田秀基
, *日本テクノセンター講習*    , 2023 



- **プログラム合成対象言語 Pro5Lang のための行動価値関数圧縮アルゴリズム**  <span onmouseover="document.getElementById('sigagi2211').style.display = 'block'"  onmouseout="document.getElementById('sigagi2211').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 竹内泉
, *第22回人工知能学会 汎用人工知能研究会 SIG-AGI*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2211"> プログラム合成対象言語 Pro5Lang の行動価値関数圧縮アルゴリズムを提案する。将来は AGIエージェントの経験履歴を圧縮することにより、 Pro5Lang プログラムを自律的に獲得させる計画である。アルゴリズムは K-means 法に似ているが、距離やクラスタ中心の計算方法が、入力データの特徴と我々の用途に特化しており、強力な汎化能力をもたらす。経験履歴を模した人工データを用いて、プロトタイプ実装の動作を確認した。</div> </blockquote>



- **Pre-training music transformer with masked-language model**  <span onmouseover="document.getElementById('isbisml2022fu').style.display = 'block'"  onmouseout="document.getElementById('isbisml2022fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *第25回情報論的学習理論ワークショップ (IBIS2022)*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="isbisml2022fu"> Pre-training driven by vast data has shown great power in natural language understanding. The idea has also been applied to symbolic music. However, many existing works using pre-training for symbolic music are not general enough to tackle all the tasks in musical information retrieval, and there is still space to improve the model structure. To make up for the insufficiency and compare it with the existing works, we employed a BERT-like masked language pre-training approach to train a stacked MusicTransformer on MAESTRO dataset. Then we fine-tuned our pre-trained model on several symbolic music understanding tasks. In the work, our contribution is 1)we improved MusicBERT by modifying the model structure. 2)be- sides the existing evaluation downstream tasks, we complemented several downstream tasks, including melody extraction, emotion classification, and composer classification. We pre-trained the modified model and existing works under the same condition. We make a comparison of our pre-trained model with the previous works. The result shows that the modified model is more powerful than the previous models with the same pre-training setting.</div> </blockquote>



- **AutoformerとBayes by Backpropを用いた信頼度つき時系列予測**  <span onmouseover="document.getElementById('ibislml2022nakada').style.display = 'block'"  onmouseout="document.getElementById('ibislml2022nakada').style.display = 'none'">[abst]</span>   
中田秀基, 麻生 英樹
, *第25回情報論的学習理論ワークショップ (IBIS2022)*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibislml2022nakada"> AutoformerなどのTransformerをベースとした時系列予測技術が提案されているが、これらの信頼度推定については明らかになっていない。本発表では、Autoformerに対してBayes by Backpropを適用することで信頼度推定を行ったので報告する。</div> </blockquote>



- **セキュアなAI/HPCクラウドバースティング実現に向けた検討**  <span onmouseover="document.getElementById('swopp2022takizawa').style.display = 'block'"  onmouseout="document.getElementById('swopp2022takizawa').style.display = 'none'">[abst]</span>   
滝澤真一朗, 清水 正明, 中田 秀基, 松葉 浩也, 高野 了成
, *情報処理学会ハイパフォーマンス・コンピューティング研究会*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp2022takizawa"> 機密性の高い情報の安全な処理を担保しつつ計算資源への投資を最適化する手法として、オンプレミス環境を保持したうえで、必要に応じてクラウド環境を追加的に使用する{\bf クラウドバースティング}が普及しつつある。われわれはクラウドストレージをジョブサブミッション機構として使用してユーザレベルでのクラウドバースティングを実現するCloudQを提案し、バースト先としてHPC環境であるABCIをターゲットとした実装についてすでに報告している。本稿では、CloudQシステムの対象としてパブリッククラウド環境を使用するシステムについて報告する。パブリッククラウドを用いる際には、ABCIのようなHPC環境とは異なるセキュリティおよび利便性に関する配慮が必要である。われわれは2つの方針を立案し、それぞれ実装を行った。2つの方針の得失を議論するとともに、この2つの実装について詳述する。</div> </blockquote>



- **ROS準拠ロボット及びエッジサーバを活用した環境情報収集・処理を行うIoTシステムの検討**  <span onmouseover="document.getElementById('dicomo2022sasaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo2022sasaki').style.display = 'none'">[abst]</span>   
佐々木 怜名, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2022)シンポジウム*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo2022sasaki"> 防犯サービスやペット・お年寄りの見守りサービスなどを行うスマートホームでは，IoT機器に装備されたセンサから収集したデータを活用して，利便性が高い快適で安全な生活を実現するサービスを提供している． このようなサービスの実現には，屋内外の様々な場所に適切にIoT機器を設置し，センサデータを収集する必要があり，個別の間取りなどを考慮したり，必要に応じてIoT機器を再配置しなければならないといった課題がある．また，個々の家庭のデータをクラウドに収集するIoTシステムを構築するには，転送データ量の削減，プライバシの保護，サイバー攻撃への対策も必要となる． 本研究では，車輪型移動ロボットを用いて室内環境情報を収集し，エッジサーバを介してクラウド上での解析処理を可能にする，スマートホームのためのIoTシステムを検討する．ROS（Robot Operating System）で実装された車輪型移動ロボットは遠隔操作が可能なIoT機器の1つであり，ロボットに搭載されたセンシング機能と駆動機能を用いて室内の多様な環境情報の収集が可能となる．本稿では，車輪型移動ロボット群，エッジサーバ，クラウドで構成されるスマートホームのためのIoTシステムを設計し，予備実験を行うとともに室内二酸化炭素濃度監視システムを試作した．</div> </blockquote>



- **報酬最大化ＡＧＩのための意思疎通機構の設計とプロトタイプ実装**  <span onmouseover="document.getElementById('sigagi2207').style.display = 'block'"  onmouseout="document.getElementById('sigagi2207').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 竹内泉, 佐野 崇
, *第21回人工知能学会 汎用人工知能研究会 SIG-AGI*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2207"> 報酬最大化を目的として動作するエージェントどうしが、お互いに意思疎通するための機構を設計し、プロトタイプ実装を行った。エージェントは POMDP を近似的に解いていると解釈でき、合目的的に行動・推論・対話を使い分けるよう設計されている。プロトタイプ実装の上で動作するテストプログラムを書くことにより、設計の妥当性を検討した。この機構はヒトの意思疎通の計算論的モデルの候補でもある。</div> </blockquote>



- **Symbolic piano music understanding from large-scale pre-training**  <span onmouseover="document.getElementById('jsai22fu').style.display = 'block'"  onmouseout="document.getElementById('jsai22fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *人工知能学会全国大会（第36回）*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai22fu"> Pre-training driven by a vast amount of data has shown great power in natural language understanding. The existing works using pretraining for symbolic music are not general enough to tackle all the tasks in musical information retrieval. To make up for the insufficiency and compare it with the existing works, we employed a BERT-like masked language pre-training approach to train a stacked Music Transformer on polyphonic piano MIDI files from the MAESTRO dataset. Then we finetuned our pre-trained model on several symbolic music understanding tasks. In our current work in progress, we complemented several note-level tasks, including next token prediction, melody extraction, velocity prediction, and chord recognition. And we compared our model with the previous works.</div> </blockquote>



- **画像内オブジェクトの切り出しと質問応答タスクの同時学習**  <span onmouseover="document.getElementById('jsai22nakada').style.display = 'block'"  onmouseout="document.getElementById('jsai22nakada').style.display = 'none'">[abst]</span>   
中田秀基, 麻生 英樹
, *人工知能学会全国大会（第36回）*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai22nakada"> 視野内の複数のオブジェクトの関係などを含む複雑な VQAタスクにおいて、画像から個々のオブジェクトを切り出した結果を入力として質問応答を学習させることで性能が向上することが知られている。本発表では、それぞれ独立に行われていたオブジェクトの切り出しとVQAタスクを同時に学習させる方法について検討した結果について報告する。</div> </blockquote>



- **汎用人工知能のためのプログラム合成対象言語 Pro5Lang のエピソード記憶機構**  <span onmouseover="document.getElementById('sigagi2203').style.display = 'block'"  onmouseout="document.getElementById('sigagi2203').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 竹内泉, 佐野 崇
, *第20回人工知能学会 汎用人工知能研究会 SIG-AGI*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2203"> 連想記憶の機構を持った汎用人工知能のためのプログラム合成対象言語 Pro5Lang について述べる。この言語は論理型言語と機械語の特徴を合わせ持っている。連想記憶装置は証明探索の過程で得られる証明済み命題をのみを記憶する。この提案機構は脳におけるエピソード記憶の主要な役割の１つを明解に説明する計算論的モデルでもある。テストプログラムをいくつか書くことにより、Pro5Lang の表現力と合成対象言語としての適性を予備的に検討した。</div> </blockquote>



- **ROS準拠ロボットからの環境情報収集を可能にするIoTシステムの検討**  <span onmouseover="document.getElementById('zen22sasaki').style.display = 'block'"  onmouseout="document.getElementById('zen22sasaki').style.display = 'none'">[abst]</span>   
佐々木 怜名, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第84回全国大会*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen22sasaki"> 本研究では，センサ端末として多種センサを搭載した車輪型移動ロボットを用いることで，少ないセンサで多様なデータを必要に応じて収集可能となるIoTシステムの構築を目指す．移動ロボットにより，センシング機能と駆動機能によって室内全体を移動しながら，室内位置情報と多様なセンサデータを収集することが可能になる．また，ロボットで収集した室内環境情報をエッジサーバを介してクラウドに蓄積し，その解析処理を行うIoTシステムの検討を行う.</div> </blockquote>



- **合成データを用いた教師なしドメイン適応による室内動作認識手法の比較**  <span onmouseover="document.getElementById('zen22isoi').style.display = 'block'"  onmouseout="document.getElementById('zen22isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第84回全国大会*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen22isoi"> 我々は,合成動画像データを活用した教師なし学習による高精度な実動画像データ解析の実現のため,写実的な合成動画像データを作成して実験したが,合成データのみでの学習でもドメイン適応を用いた学習でも十分な解析精度が得られず,改善の余地があることがわかった.本研究では,より時間的モデリングに優れたドメイン適応を行うモデルであるTRN, TA3Nを用いた手法で改善を図り,高精度な動画像分類を実現した.</div> </blockquote>



- **合成データを用いた教師なしドメイン適応による室内動作認識手法の検討**  <span onmouseover="document.getElementById('deim22isoi').style.display = 'block'"  onmouseout="document.getElementById('deim22isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *第14回データ工学と情報マネジメントに関するフォーラム (DEIM)*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim22isoi"> ディープニューラルネットワークの利用に伴う実データ収集のコストやプライバシーの問題に対応するため,人工的に作成される合成データを学習に活用することが期待される.我々は,実データ動作認識のための写実的な合成動画像データを作成し,ドメイン適応ネットワークDANNを2つの基本的な動画像識別ネットワーク3D ResNet,TSNで拡張した動画像ドメイン適応手法の効果を調査したが,十分な精度で実データの動作分類を行うことができなかった.本研究では, DANNモデルのバックボーンの比較, Attentionの導入,敵対的学習の追加を行い,さらに詳細に動画像ドメイン適応手法を検討する.実験から,合成データをソースデータとするドメイン適応によって高精度なラベルなし実データの動作分類ができるようになることを示す.</div> </blockquote>



- **合成動画データを用いた学習でのドメイン適応による動作認識精度の比較**  <span onmouseover="document.getElementById('miru2107isoi').style.display = 'block'"  onmouseout="document.getElementById('miru2107isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *第24回画像の認識・理解シンポジウム*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="miru2107isoi"> ディープニューラルネットワークの進歩に伴う学習データ不足の問題について様々な議論が行われており, その解決策の1 つに合成データを利用した学習がある. 合成データには生成が比較的容易であるという利点があるが, 合成データを用いて学習したモデルには, 実データ解析時にデータの分布の違いから解析精度が低下するドメインシフトが起こるという課題がある. 本研究では, 合成動画像データを活用した高精度な実動画像データ解析の実現を目的とし,写実的な合成動画像データを作成して学習し, その解析精度を調査した.</div> </blockquote>



- **ABCI 2.0: Advances in Open AI Computing Infrastructure at AIST**  <span onmouseover="document.getElementById('hpc2107takizawa').style.display = 'block'"  onmouseout="document.getElementById('hpc2107takizawa').style.display = 'none'">[abst]</span>   
Takizawa Shinichiro, Yusuke Tanimura, Hidemoto Nakada, Ryousei Takano, Hirotaka Ogawa
, *情報処理学会ハイパフォーマンス・コンピューティング研究会*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc2107takizawa"> ABCI is the world’s first large-scale Open AI Computing Infrastructure for both developing AI technologies and bridging them into the industry, operated by AIST, Japan since August 2018. It delivers 19.88 petaflops of HPL performance and achieves 70 seconds for training ResNet-50 model in MLPerf Training v0.6. Last November we achieved world’s fastest records for CosmoFlow and DeepCAM in MLPerf HPC benchmarks. ABCI was the fastest supercomputer in Japan until Fugaku made a spectacular debut, however, it soon became short of computing capacity and I/O performance due to the rapid expansion of its usage. This forced us to make a major upgrade to ABCI. With this upgrade, we have added 120 compute nodes and a stroage system with a capacity of 11 PBytes. We named the whole system which includes both existing ABCI and the newly added equipments as ABCI 2.0. ABCI 2.0 provides the same software environment that ABCI provided. It enables that existing ABCI users can easily use the newly equipments in a similar way they used ABCI. We compared the performance of existing and new compute nodes and found that new nodes had 4.1 times higher performance than existing nodes in training ResNet-50 model using PyTorch. We expect that the new nodes largely contributes to increase the system throughput.</div> </blockquote>



- **オンライン動画動作識別のための分散ストリーム処理基盤の検討**  <span onmouseover="document.getElementById('xsig2107takasaki').style.display = 'block'"  onmouseout="document.getElementById('xsig2107takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *The 5th cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig2107takasaki"> 子供やお年寄りの見守りサービスや防犯を目的として家庭のセンサで取得した動画像をリアルタイムに機械学習で解析するには，データ量と解析計算量が課題となる．我々は，センサ側で姿勢推定ライブラリOpenPoseを使用して動画像から関節の特徴量データを抽出してクラウドへ転送し，クラウドでその特徴量データのみを用いて機械学習による動作識別を行うことで，処理遅延やプライバシの問題に対処するセンサとクラウドでの分散処理手法を提案している．しかし，複数家庭のセンサから連続的に送られる大量のデータをクラウドで処理するには，急激なデータの増加によるシステム負荷上昇に耐えうる処理基盤が必要である．本研究では，大量のデータを効率よく処理可能な分散ストリーム処理基盤の構築を目指して，エッジで抽出した関節の特徴量データをApache Kafkaを用いて収集し，クラウドにおいてApache Flinkの分散ストリーム処理機能を用いて機械学習を行うシステムを構築し，その性能特性を調査した．実験結果から，Flinkの並列処理機能を用いることでスケーラブルに機械学習の推論を行えることが分かった．また，データ転送時のバッファリング待ち時間を制御するFlinkのBufferTimeoutパラメータを調節することで，解析効率が改善することが分かった．</div> </blockquote>



- **Julia言語へのActorの導入**  <span onmouseover="document.getElementById('pro2107nakada').style.display = 'block'"  onmouseout="document.getElementById('pro2107nakada').style.display = 'none'">[abst]</span>   
中田秀基
, *情報処理学会プログラミング研究会*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pro2107nakada"> Julia言語はインタラクティブな言語でありながら、LLVMを利用したJITにより高速な実行が可能なことから科学技術計算向け言語として注目を集めている。Juliaは分散環境での実行をデフォルトでサポートしており、リモートノードでの関数実行、リモートチャンネルへの書き込み、Futureによる同期などが利用できる。しかし、リモート変数への参照を持つことができないため、リモートノードに状態を保持しておき、その状態を利用した計算を行うことが難しい。本稿ではJulia言語にActorを導入することで、分散並列計算の実行を容易にすることを試みた。Actorは1980年代に提唱された並列計算モデルに基づく実行モデルで1990年代に広く研究されたが、近年Akkaが採用するなど再評価されている。Actorは状態を保持したシングルスレッドでメッセージを処理するオブジェクトとして捉えることができ、粗粒度の並列実行モデルとして適している。本稿ではユーザに提供するActor APIのモデルに付いて議論し、Julia既存の言語機能を利用することで効率的にActorを実現できることを示す。また、本実装のマイクロベンチマークでの性能評価結果を示す。</div> </blockquote>



- **動作認識のための合成データ活用に向けたドメイン適応手法の比較**  <span onmouseover="document.getElementById('dicomo2107isoi').style.display = 'block'"  onmouseout="document.getElementById('dicomo2107isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *「マルチメディア、分散、協調とモバイル(DICOMO2021)シンポジウム」*   , pp. 1289 - 1297  , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo2107isoi"> ディープニューラルネットワークの進歩に伴う学習データ不足の問題について様々な議論が行われており,その解決策の1つに合成データを利用した学習がある.合成データには生成が比較的容易であるという利点があるが,合成データを用いて学習したモデルには,実データ解析時にドメインシフトによって解析精度が低下するという課題がある.本研究では,合成動画像データを活用した高精度な実動画像データ識別の実現を目的とし,写実的な合成動画像データを用いて3D ResNetとTSNをベースとするモデルでそれぞれ学習し,その動作識別精度を比較した.実験の結果,合成データと実データの特徴の違いはモーションよりも色や形状,質感にあること,オプティカルフローを用いるTSNベースのモデルの方が高精度に実データの動作識別が可能であることがわかった</div> </blockquote>



- **MIDI note embedding with fasttext model**  <span onmouseover="document.getElementById('jsai21fu').style.display = 'block'"  onmouseout="document.getElementById('jsai21fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *2021年度 人工知能学会全国大会 (第35回)*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai21fu"> Distributed word representation greatly promoted research in natural language processing. Word embedding models like word2vec, GloVe, fasttext and BERT could help saving a lot of time training in the downstream tasks. Same as languages, MIDI music is constructed in the way of sequence, with a determined alphabet of notes and events. We proposed a way of training MIDI note embedding with adaption of Facebook’s fasttext model. We trained model in both supervised and unsupervised way. Same as fasttext, we then evaluate the model by word similarity, word analogy, and a classification task. The result shows that the adopted fasttext model generalize well in MIDI data and it’s promising to be used on future tasks.</div> </blockquote>



- **A study on the effect of regularization for weight imprinting**  <span onmouseover="document.getElementById('jsai21paulino').style.display = 'block'"  onmouseout="document.getElementById('jsai21paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Hidemoto Nakada, Yusuke Tanimura, Hideki Asoh
, *2021年度 人工知能学会全国大会 (第35回)*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai21paulino"> We investigate the Few Shot Learning based on the weight imprinting technique.  The performance of imprinted weights deeply depends on the quality of the representation the encoder creates.  However, it is known that the extracted representation quality affects the performance of the imprinted model, it is not known what characteristics are required for weight imprinting. The representation leads to the highest classification accuracy for base classes might not be the best one for downstream imprinting tasks. We are investigating how we can get a `better&#x27; representation in terms of WIP. Currently, we are focusing on regularization, model architecture, data augmentation,  auxiliary dataset, and auxiliary tasks.</div> </blockquote>



- **動作認識のための合成データ活用に向けたドメイン適応手法の検討**  <span onmouseover="document.getElementById('prmu2105isoi').style.display = 'block'"  onmouseout="document.getElementById('prmu2105isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *信学技報
 
PRMU2021-5(2021-05)*   , pp. 25-30  , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="prmu2105isoi"> ディープニューラルネットワークの進歩に伴う学習データ不足の問題について様々な議論が行われており,
その解決策の1 つに合成データを利用した学習がある. 合成データには生成が比較的容易であるという利点があるが,
合成データを用いて学習したモデルには, 実データ解析時にドメインシフトによって解析精度が低下するという課題が
ある. 本研究では, 合成動画像データを活用した高精度な実動画像データ識別の実現を目的とし, 写実的な合成動画像
データを作成して学習し, その動作識別精度を調査した. 実験の結果, 合成動画像データにデータ拡張を行い, ラベルな
し実動画像データと併せてドメイン適応を用いた学習を行うことで, 実データ動作識別精度の向上が可能であることが
わかった.</div> </blockquote>



- **ドメイン適応を用いた動作認識のための合成動画像の活用の検討**  <span onmouseover="document.getElementById('zen2021isoi').style.display = 'block'"  onmouseout="document.getElementById('zen2021isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第83回全国大会*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen2021isoi"> 本研究では,合成動画像データを活用した高精度な実動画像データ解析の実現を目的とし,写実的な合成動画像データを作成して学習し,その解析精度を調査した.実データを用いた解析実験の結果,合成データのみでの学習でもドメイン適応を用いた学習でも現時点では十分な解析精度が得られず,改善の余地があることがわかった。</div> </blockquote>



- **分散ストリーム処理フレームワークを用いた動作識別処理性能の調査**  <span onmouseover="document.getElementById('zen2021takasaki').style.display = 'block'"  onmouseout="document.getElementById('zen2021takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第83回全国大会*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen2021takasaki"> 本研究では，クラウドにおいて，分散メッセージングシステムApache Kafka(以降，Kafkaと呼ぶ)と分散ストリーム処理フレームワークApache Flink(以降，Flinkと呼ぶ)を用いて機械学習処理を行うシステムを構築し，分散ストリーム機械学習処理の性能特性を調査した．</div> </blockquote>



- **リアルタイム動画動作識別の実現に向けた分散ストリーム処理基盤の検討**  <span onmouseover="document.getElementById('dicomo2021takasaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo2021takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *DEIM 第13回データ工学と情報マネジメントに関するフォーラム*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo2021takasaki"> 子供やお年寄りの見守りサービスや防犯を目的として家庭のセンサで取得した動画像をリアルタイムに機械学習で解析するには，データ量と解析計算量が課題となる．我々は，センサ側で姿勢推定ライブラリOpenPoseを使用して動画像から関節の特徴量データを抽出してクラウドへ転送し，クラウドでその特徴量データのみを用いて機械学習による動作識別を行うことで，処理遅延やプライバシの問題に対処するセンサとクラウドでの分散処理手法を提案している．しかし，複数家庭のセンサから連続的に送られる大量のデータをクラウドで処理するには，急激なデータの増加によるシステム負荷上昇に耐えうる処理基盤が必要である．本研究では，大量のデータを効率よく処理可能な分散ストリーム処理基盤の構築を目指して，エッジで抽出した関節の特徴量データをApache Kafkaを用いて収集し，クラウドにおいてApache Flinkの分散ストリーム処理機能を用いて機械学習を行うシステムを構築し，その性能特性を調査した．実験結果から，Flinkの並列処理機能を用いることでスケーラブルに機械学習の推論を行えることが分かった．また，データ転送時のバッファリング待ち時間を制御するFlinkのBufferTimeoutパラメータを調節することで，解析効率が改善することが分かった．</div> </blockquote>



- **室内動作認識のためのドメイン適応による合成データ活用の検討**  <span onmouseover="document.getElementById('dicomo2021isoi').style.display = 'block'"  onmouseout="document.getElementById('dicomo2021isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *DEIM 第13回データ工学と情報マネジメントに関するフォーラム*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo2021isoi"> ディープニューラルネットワークの進歩に伴う学習データ不足の問題について様々な議論が行われており,その解決策の 1 つに合成データを利用した学習がある. 合成データには生成が比較的容易であるという利点があるが,合成データを用いて学習したモデルには, 実データ解析時にデータの分布の違いから解析精度が低下するドメインシフトが起こるという課題がある. 本研究では, 合成動画像データを活用した高精度な実動画像データ解析の実現を目的とし, 写実的な合成動画像データを作成して学習し, その解析精度を調査した. 実験では, 作成したラベル付き合成データのみを用いて学習したネットワークと, ラベル付き合成データとラベルなし実データの両方を用いてドメイン適応して学習したネットワークを用いて実データの解析を行った. 実験の結果, 合成データのみでの学習でもドメイン適応を用いた学習でも現時点では十分な解析精度が得られず, 改善の余地があることがわかった.</div> </blockquote>



- **クラウドオブジェクトストレージを活用したメタスケジューラ**  <span onmouseover="document.getElementById('hpc2012takizawa').style.display = 'block'"  onmouseout="document.getElementById('hpc2012takizawa').style.display = 'none'">[abst]</span>   
滝澤 真一朗, 高野 了成, 清水 正明, 松葉 浩也, 中田 秀基, 小川 宏高
, *第177回ハイパフォーマンスコンピューティング研究発表会, 	2020-HPC-177*   , pp. 1-8  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc2012takizawa"> 計算能力の増強を理由にオンプレミスシステムに加えてクラウドを利用することや，処理対象とするデータの機密性に応じてオンプレミスシステムとクラウドを使い分ける利用形態がある．この時，複数計算機資源間での実行環境の共通化と，計算内容とデータのセキュアな共有，これら 2 点を実現するシステムの管理コスト最小化が課題となる．この課題を解決することを目的に，計算実行環境にコンテナイメージを活用し，クラウドオブジェクトストレージに計算内容とデータを格納するメタスケジューリングシステムを提案する．システムを統一認証基盤を必要としない，利用者権限で実行できる設計とすることで管理コストの課題も解決する．本システムのプロトタイプを実装し，クラウドに ABCI を，クラウドオブジェクトストレージとして ABCI クラウドストレージを用いる試験環境を構築し，利用者端末での同時ジョブ投入時の応答性能，連続ジョブ投入時のクラウドでの受付までの待ち時間の評価を行った．</div> </blockquote>



- **Auxiliar Dataset on Few Shot Learning with Weight Imprinting**  <span onmouseover="document.getElementById('ibisml2020paulino').style.display = 'block'"  onmouseout="document.getElementById('ibisml2020paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Yusuke Tanimura, Hidemoto Nakada, Hideki Asoh
, *IBIS2020 第23回情報論的学習理論ワークショップ*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml2020paulino"> How to train models with few or single examples? Few Shot Learning techniques address this question by learning from limited samples and rapidly adapt to novel samples. In this work, we review a prominent approach categorized as weight imprinting. We apply an auxiliary dataset to improve the feature representations for the task. This approach enables the feature extractor to learn richer representation. This technique can be naturally extended since a similar dataset can be gathered. We also review Few Shot Learning performances on a small network with two layers in contrast with the commonly used ResNet18.</div> </blockquote>



- **Piano score vectorization using fasttext**  <span onmouseover="document.getElementById('ibisml2020fu').style.display = 'block'"  onmouseout="document.getElementById('ibisml2020fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *IBIS2020 第23回情報論的学習理論ワークショップ*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml2020fu"> As representation learning techniques in natural language processing become more and more mature, we could utilize this advantage in sentiment analysis, natural language generation/ understanding, and so on. A well-trained word vector representation could save you a lot of effort in solving downstream tasks. Same as language, music could also be understood as a kind of sequence data with a determined alphabet and tokens. In this work, we want to further discover the possibility of adapting Facebook’s fasttext model on pianoroll. We train the model in both supervised and unsupervised settings. And then we evaluate the word vector by word similarity, word analogy, and a classification task. The result shows the power of the word-vector model in pianoroll representation and gives us the hope to apply it to future tasks.</div> </blockquote>



- **物体操作に適したワーキングメモリを持つ汎用人工知能アーキテクチャの検討**  <span onmouseover="document.getElementById('sigagi2011ichisugi').style.display = 'block'"  onmouseout="document.getElementById('sigagi2011ichisugi').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 佐野 崇
, *第16回SIG-AGI*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2011ichisugi"> 認知科学におけるオブジェクトファイル理論を参考
にしたワーキングメモリのモデルを提案する。このモ
デルはベイジアンネットを用いた生成モデルとして表
現される。我々はこのワーキングメモリを持った認知
アーキテクチャのプロトタイプシステムを実装し、行
動ルールの記述が簡潔で汎用性の高いものになる見込
みを得た。</div> </blockquote>



- **動画像予測と対比学習による表現学習**  <span onmouseover="document.getElementById('prmu2009nakada').style.display = 'block'"  onmouseout="document.getElementById('prmu2009nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 麻生 英樹
, *信学技報 IEICE-120 no.154*   , pp. 59-64  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="prmu2009nakada"> 近年ラベルを用いない教師なし学習手法が発展し、わずかな量のラベルを用いた下流タスクへの転移学習
によって、ラベルを用いた事前学習に匹敵するほどの精度が得られるようになっている。これらの教師なし学習手法
の多くは画像データを対象としており、ランダムクロッピングなどの経験的に有効であることが知られているデータ
水増し手法によって、帰納バイアスをモデルに与えている。これに対してわれわれは、動画像のフレームの連続性を
帰納バイアスとして用いることを試みた。具体的には、動画中の別フレームを用いる方法、動画中のフレームを他の
フレームから予測したものを用いる方法を試行した。下流タスクとして画像識別を用いて評価を行った結果、前者の
手法では従来手法よりもやや性能が落ちるものの一定の効果があることを確認した。また、後者の商法では従来手法
に匹敵する性能が得られることを確認した</div> </blockquote>



- **脳の自律的プログラム合成機構のモデルに向けて：２層ベイジアンネットによる記号処理命令の獲得・実行機構**  <span onmouseover="document.getElementById('sigagi2008ichisugi').style.display = 'block'"  onmouseout="document.getElementById('sigagi2008ichisugi').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 佐野 崇
, *第15回SIG-AGI*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2008ichisugi"> 本稿ではまず経験から知識を獲得する知的エージェ ントのアーキテクチャの構想を述べる。次にそのアー キテクチャの重要な要素技術の１つとして、２層ベイ ジアンネットを用いてパターン獲得・パターンマッチ を行う手法を提案する。本手法は特別に設計された条 件付確率モデルを用いる。</div> </blockquote>



- **Julia言語を用いた大規模計算機上での分散並列実行環境の構築**  <span onmouseover="document.getElementById('cpsy202007').style.display = 'block'"  onmouseout="document.getElementById('cpsy202007').style.display = 'none'">[abst]</span>   
中田 秀基
, *信学技報, vol. 120, no. 121, CPSY2020-2*   , pp. 9-14  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy202007"> Julia言語はスクリプト言語でありながら、LLVMを用いた強力なJITコンパイラによって高速な科学技術計算が可能であり、次世代の機械学習向け言語として期待されている。われわれはJulia言語の大規模分散並列実行環境への適正を調査するために、2つの並列化手法に関して性能評価を行った。その結果MPIによる並列化ではネイティブに近い通信速度が得られるものの、Julia独自の分散技術による並列化では十分な通信速度が得られないことがわかった。</div> </blockquote>



- **エッジ，クラウド間分散処理に向けたNNを用いた動作識別手法の検討**  <span onmouseover="document.getElementById('xsig2020takasaki').style.display = 'block'"  onmouseout="document.getElementById('xsig2020takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *xsig2020*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig2020takasaki"> センサ機器やクラウドコンピューティングの普及により，一般家庭で取得，蓄積した動画像が子供 やお年寄りの見守りサービスや防犯対策，セキュリティに活用されるようになってきた.しかし，家庭の センサで取得した動画像をリアルタイムに機械学習を用いて解析するには，データ転送量と解析計算量が 課題となる.我々は，センサ側で姿勢推定ライブラリ OpenPose を使用して動画像から関節の特徴量デー タを抽出して転送し，クラウドでその特徴量データのみを用いて機械学習による動作識別を行うことで， 処理遅延やプライバシの問題に対処する分散処理手法を提案している.実験では，STAIR Actions データ セットの 3 カテゴリの動作識別が 80%以上の精度で行えること，センサからクラウドへのデータ転送量を 大幅に削減できることを確認した.しかし，3 カテゴリの識別では汎用性が低く，過学習の改善も課題と なっていた.本研究では，より多様な動作識別を活用する実アプリケーションへの応用を目指し，同デー タセットの全 100 カテゴリを用いた識別を行った. 実験から，LSTM を用いることで最も高い精度を得る ことができることを確認した.</div> </blockquote>



- **分散ストリーム処理フレームワークを用いた動作識別手法の検討**  <span onmouseover="document.getElementById('dicomo2020takasaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo2020takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2020)シンポジウム*   , pp. 1245 - 1250  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo2020takasaki"> センサ機器やクラウドコンピューティングの普及により，一般家庭で取得，蓄積した動画像が子供やお年寄りの見守りサービスや防犯対策，セキュリティに活用されるようになってきた．家庭のセンサで取得した動画像をリアルタイムに機械学習を用いて解析するには，データ転送量と解析計算量が課題とる．我々は，センサ側で姿勢推定ライブラリ OpenPose を使用して動画像から関節の特徴量データを抽出して転送し，クラウドでその特徴量データのみを用いて機械学習による動作識別を行うことで，処理遅延やプライバシの問題に対処するセンサとクラウドでの分散処理手法を提案している．しかし，複数家庭のセンサから連続的に送られる大量のデータをクラウドで処理するには，急激なデータの増加によるシステム負荷上昇に耐えうる処理基盤が必要である.本研究では，大量のデータを効率よく処理可能な分散ストリーム処理基盤の構築を目指して，エッジで抽出した関節の特徴量データをApache Kafkaを用いて収集し，クラウドにおいてApache Flinkの分散ストリーム処理機能を用いて機械学習処理を行うシステムを構築し，解析スループットを調査した．実験から，解析スループットはFlinkの並列度に比例して増加することが確認できた．</div> </blockquote>



- **室内における動作識別のための合成動画像データセット構築の検討**  <span onmouseover="document.getElementById('dicomo2020isoi').style.display = 'block'"  onmouseout="document.getElementById('dicomo2020isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2020)シンポジウム*   , pp. 832 - 837  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo2020isoi"> 近年ディープニューラルネットワーク (DNN) により動画像から人間の行動を分析することが可能になり, 一般家庭で老人や子供の見守りなどに応用することが期待されている. しかし, 室内における人間の行動解析のためのデータセットは現状不十分であり, またそのようなデータセットを現実の動画像で作成するには多大な手間やコスト・プライバシといった課題がある. 我々は，既発表研究で人間の室内行動解析のためのデータセットの構築, および現実の動作解析のための合成動画像の生成方法を確立することを目指し, Unity を用いて合成動画像データセットを試作・評価した. 本研究では, 試作したデータに追跡カメラでの撮影・学習時のクラス数の均一化という改良を行い,実写動画像STAIR Actionsを用いて評価した. その結果,作成した合成動画像の改良により, 本合成動画像における動作分類の精度が改善したこと, さらに動作などのバリエーションを増やすことが必要であることがわかった.</div> </blockquote>



- **Few-shot Learning with Data Augmentation with Generative Model**  <span onmouseover="document.getElementById('jsai2020zhou').style.display = 'block'"  onmouseout="document.getElementById('jsai2020zhou').style.display = 'none'">[abst]</span>   
Mu Zhou, Yusuke Tanimura, Hidemoto Nakada
, *2020年度人工知能学会全国大会*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai2020zhou"> While deep learning, in general, requires a large amount of labeled data,
there are situations where only a few samples are available for some classes. 
In theory, if we can predict the probabilistic distribution of the classes 
based on the samples for other classes, we can leverage the distribution to train the model. 
We augment the data for the class with few samples using the generative model trained on the other classes for a classification task. We applied this method on MNIST dataset and 
evaluate it.</div> </blockquote>



- **Sparsity enforcement on latent variables for better disentanglement in VAE**  <span onmouseover="document.getElementById('jsai2020paulino').style.display = 'block'"  onmouseout="document.getElementById('jsai2020paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Yusuke Tanimura, Hidemoto Nakada, Hideki Asoh
, *2020年度人工知能学会全国大会*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai2020paulino"> We address the problem of unsupervised latent factorization and reconstruction accuracy. The related work on unsupervised representations focuses on constraining the second term of Variational Autoencoders loss function: The Kullback-Leibler component (Beta-VAE, FactorVAE Beta-TCVAE). Despite promising results, this comes with a trade-off between disentanglement and reconstruction. Besides, it is not clear why minimizing the KL divergence leads to disentanglement. In this paper, we propose to achieve disentangled representations by sampling from a sparse distribution. To give a visual appealing reconstruction for humans, we replace the conventional pixel-wise quadratic by perceptual loss. We demonstrate the reconstruction quality and disentangled on synthetic datasets.</div> </blockquote>



- **Transfer symbolic music style from latent representation**  <span onmouseover="document.getElementById('jsai2020fu').style.display = 'block'"  onmouseout="document.getElementById('jsai2020fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *2020年度人工知能学会全国大会*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai2020fu"> Generative models has been widely applied in many computer vision scenarios. Two series of models, Generative Adversarial Network(GAN) and Variational Autoencoder(VAE), are getting more and more popular in representation learning. 
Training these model on discrete sequence data generation is still challenging. We want to take advantage of both kind of models. In this work, we first improved a CycleGAN based model to transfer MIDI music genre. Then we want to find to combine the CycleGAN model together with a disentangled latent representation from VAE to have better understanding of music style.</div> </blockquote>



- **大規模計算クラスタにおけるユーザ利便性向上**  <span onmouseover="document.getElementById('hpc2005nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc2005nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 滝澤真一朗, 小川宏高
, *174回HPC研究会*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc2005nakada"> 大規模な計算クラスタの多くでは、計算ノードがバッチスケジューリングシステムで管理されているため、事前にアドレスを確定する事ができない、計算ノードに直接外部からネットワーク接続できない、計算ノードから外部ネットワークへの接続が制限される、といった制約がある。このため、ネットワーク接続を前提とするJupyter Notebookなどの近代的なプログラム実行環境の利用が難しい。われわれは、これらの制約を回避して、ユーザの手元の計算機から大規模クラスタの計算ノード上のJupyter Notebookを簡便に利用する方法を確立した。ユーザの計算機環境に小規模なプログラムをインストールすることが許されるケースと、ユーザ計算機には全く依存しない代わりにクラウド上のサービスが利用できるケースの、2つのシナリオを対象として検討を行い、いずれの場合においても容易に利用できる環境を実現した。</div> </blockquote>



- **動画像予測を用いた挙動分類タスクの事前学習**  <span onmouseover="document.getElementById('ibis2003nakada').style.display = 'block'"  onmouseout="document.getElementById('ibis2003nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 麻生 英樹
, *電子情報通信学会情報論的学習理論と機械学習研究会(IBISML) 信学技報, vol. 119, no. 476*   , pp. 85-90  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibis2003nakada"> 動画像は強い相関を持つ画像の集合であり、明示的なラベルなしでも利用できる有用な情報を含んでいる。 われわれは動画像挙動分類タスクを下流タスクとし、動画像予測を事前学習タスクとして用いることを試みた。事前 学習の効果は見られたものの、教師あり同画像データセットからの転移学習と比較すると十分な性能向上は見られな かった。</div> </blockquote>



- **機械学習向け生活空間動画像データセット構築の検討**  <span onmouseover="document.getElementById('zen20isoi').style.display = 'block'"  onmouseout="document.getElementById('zen20isoi').style.display = 'none'">[abst]</span>   
磯井葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第82回全国大会*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen20isoi"> ディープニューラルネットワーク (DNN) により動画 像から人間の行動を分析することが可能になり, 一般家 庭で老人や子供の見守りなどへの応用が期待されてい る [1]. DNN を用いた学習では, 大量かつバリエーショ ン豊富なラベル付き学習データが必要となるが [2], 室 内における人間の行動解析のためのデータセットは現 状存在しない. また, そのようなデータセットを実写画 像で作成するには, 多大な手間やコストを要する.本研究では，人間の室内行動解析のデータセット構 築を目指し, 3D ゲームエンジンの Unity を用いた合成 動画像データセットを試作した. 作成したデータセッ トでは 室内で人が歩く・立ち止まる・座る・座ってい る・立ち上がるの 5 つの動作をランダムに行う. また, 動画像を実写画像に似せるため, 照明条件のランダム化 とノイズ・ぼかし処理を施した. 予備実験では, 作成し たデータで上記の動作分類ができることを確認した.</div> </blockquote>



- **ポーズデータと NN を用いた動作識別手法の調査**  <span onmouseover="document.getElementById('zen20takasaki').style.display = 'block'"  onmouseout="document.getElementById('zen20takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第82回全国大会*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen20takasaki"> センサ機器やクラウドコンピューティングの普及により， 一般家庭で取得，蓄積した動画像が子供やお年寄りの見守 りサービスや防犯対策，セキュリティに活用されるように なってきた.しかし，家庭のセンサで取得した動画像をリ アルタイムに機械学習を用いて解析するにはデータサイズ と解析計算量が大きいため，サーバやストレージを用いて データの分析や蓄積を行う必要がある.我々は，姿勢推定ライブラリ OpenPose[1][2][3][4] を使っ てセンサ側で動画像から特徴量を抽出し，クラウドでその 特徴量データのみを用いて機械学習による動作識別を行う ことで，処理遅延やプライバシーの問題に対処する分散処 理手法を提案している [5].また，STAIR Actions[6] デー タセットのうち，3 カテゴリを用いた識別を行い，80%以 上の精度で識別可能であること，センサからクラウドへの データ転送量を大幅に削減できることを確認した.しかし， 3 カテゴリの識別では汎用性が低く，過学習の改善も課題 となっていた.本研究では，より多様な動作識別を活用し た実アプリケーションへ応用を目指し，同データセットの 全 100 カテゴリを用いた識別を行う.</div> </blockquote>



- **室内における日常動作解析のための合成動画像データセット構築に向けて**  <span onmouseover="document.getElementById('deim20isoi').style.display = 'block'"  onmouseout="document.getElementById('deim20isoi').style.display = 'none'">[abst]</span>   
磯井葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *第12回データ工学と情報マネジメントに関するフォーラム*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim20isoi"> ディープニューラルネットワーク (DNN) により動画像から人間の行動を分析することが可能になり, 一般 家庭で老人や子供の見守りなどに応用することが期待されている. DNN を用いた学習では大量かつバリエーション豊 富なラベル付き学習データが必要となるが, 室内における人間の行動解析のためのデータセットは現状存在しない. ま たそのようなデータセットを実写画像で作成するには, 多大な手間やコストを要する.本研究では，人間の室内行動解 析のためのデータセット構築を目指し, 3D ゲームエンジンの Unity を用いた合成動画像データセットを試作した. 作 成したデータセットでは, 室内で人が歩く・立ち止まる・座る・座っている・立ち上がるの 5 つの動作がランダムに行 われるようにした. また, 動画像を実写画像に似せるため, 照明条件のランダム化とノイズ・ぼかし処理を施した. 予 備実験では, 作成したデータを用いて上記の動作分類ができることを確認した.</div> </blockquote>



- **エッジ，クラウド間分散処理に向けた動作識別手法の検討**  <span onmouseover="document.getElementById('deim20takasaki').style.display = 'block'"  onmouseout="document.getElementById('deim20takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *第12回データ工学と情報マネジメントに関するフォーラム*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim20takasaki"> センサ機器やクラウドコンピューティングの普及により，一般家庭で取得，蓄積した動画像が子供やお年 寄りの見守りサービスや防犯対策，セキュリティに活用されるようになってきた.しかし，家庭のセンサで取得した 動画像をリアルタイムに機械学習を用いて解析するには，データ転送量と解析計算量が課題となる.我々は，センサ 側で姿勢推定ライブラリ OpenPose を使用して動画像から関節の特徴量データを抽出して転送し，クラウドでその特 徴量データのみを用いて機械学習による動作識別を行うことで，処理遅延やプライバシーの問題に対処する分散処理 手法を提案している.実験では，STAIR Actions データセットの 3 カテゴリの動作識別が 80%以上の精度で行えるこ と，センサからクラウドへのデータ転送量を大幅に削減できることを確認した.しかし，3 カテゴリの識別では汎用 性が低く，過学習の改善も課題となっていた.本研究では，より多様な動作識別を活用する実アプリケーションへの 応用を目指し，同データセットの全 100 カテゴリを用いた識別を行った. 実験から，LSTM を用いることで最も高い 精度を得ることができることを確認した.</div> </blockquote>



- **推論規則の価値を階層型強化学習 RGoal を用いて学習する手法の提案**  <span onmouseover="document.getElementById('sigagi2002chisugi').style.display = 'block'"  onmouseout="document.getElementById('sigagi2002chisugi').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 佐野 崇
, *第14回SIG-AGI*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2002chisugi"> 環境の中で動く知的エージェントが正しい推論規則
を経験から獲得するための手法を提案する。提案手法
は、推論規則の「正しさ」を「正解に到達するまでのコ
ストの低さ」で代用し、それを階層型強化学習RGoal
によって学習する。全体のアーキテクチャは神経科学
的にも妥当である。提案手法は汎用人工知能の自律的
な知識獲得の基本原理の１つになると考えている</div> </blockquote>



- **Image synthesis for One-shot Classification with Triplet Network** [[Paper](dataDir/ibisml19zhou.pdf)]  <span onmouseover="document.getElementById('ibisml19zhou').style.display = 'block'"  onmouseout="document.getElementById('ibisml19zhou').style.display = 'none'">[abst]</span>   
Mu Zhou, Yusuke Tanimura, Hidemoto Nakada
, *第22回情報論的学習理論ワークショップ (IBIS 2019)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml19zhou"> Humans can learn visual concepts quickly at a glance, whereas it is a challenge for machine to solve one-shot classification. We try to synthesize more instances from new concept to augment the scarce dataset with different augmenting methods. Then we fed our support set into Triplet Networks and the kNN classifier. We found that the synthesized images perform well on one-shot classification.</div> </blockquote>



- **Few-Shot Style Transfer for Handwriting Chinese Synthesis Using Conditional GAN** [[Paper](dataDir/ibisml19liu.pdf)]  <span onmouseover="document.getElementById('ibisml19liu').style.display = 'block'"  onmouseout="document.getElementById('ibisml19liu').style.display = 'none'">[abst]</span>   
Liangyu Liu, Yusuke Tanimura, Hidemoto Nakada
, *第22回情報論的学習理論ワークショップ (IBIS 2019)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml19liu"> Creating a handwritten Chinese font shows a great challenge due to the large amount of characters. We create handwritten fonts using few samples and synthesize other characters. We train a model with large amounts of characters in various handwritten style at the same time, and evaluate performance on synthesized characters. We find that cGAN perform better with a few examples.</div> </blockquote>



- **An improvement on CycleGAN based symbolic music genre transfer** [[Paper](dataDir/ibisml19fu.pdf)]  <span onmouseover="document.getElementById('ibisml19fu').style.display = 'block'"  onmouseout="document.getElementById('ibisml19fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *第22回情報論的学習理論ワークショップ (IBIS 2019)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml19fu"> In this work, we optimize a CycleGAN based symbolic music generation system, which could do a symmetric genre transfer of music between two domains. We applied various kinds of encoders and decoders, and some of them could drastically reduces training time and keep the quality. We also provide a novel data representation and compression which how good performance in this scenario.</div> </blockquote>



- **A study on the latent space of VAE** [[Paper](dataDir/ibisml19paulino.pdf)]  <span onmouseover="document.getElementById('ibisml19paulino').style.display = 'block'"  onmouseout="document.getElementById('ibisml19paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Yusuke Tanimura, Hidemoto Nakada, Hideki Asoh
, *第22回情報論的学習理論ワークショップ (IBIS 2019)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml19paulino"> We study the role of latent space dimensionality and latent structure using sparse autoencoder. The assumption is that, inducing sparsity in the encoder will lead to better latent space representation. We extend our analysis to find the correlation between latent dimensionality and latent interpolation result. We tested our assumption on dSprites dataset.</div> </blockquote>



- **少数のサンプル画像からの任意人物姿勢画像の生成** [[Paper](dataDir/ibisml19nakada.pdf)]  <span onmouseover="document.getElementById('ibisml19nakada').style.display = 'block'"  onmouseout="document.getElementById('ibisml19nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 麻生 英樹
, *第22回情報論的学習理論ワークショップ (IBIS 2019)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml19nakada"> 少数の異なる姿勢をとった人物画像から、任意の姿勢の人物画像を生成する試みについて紹介する。人物画像をエンコードした表現を、指定姿勢を入力として変換し、変換後の表現から人物画像にデコードすることで指定姿勢の人物画像を得る。3D モデルから生成した学習データに対して、提案手法を評価した結果、比較的良好な画像が得られることが確認できた。</div> </blockquote>



- **エッジ、クラウド間の分散処理に向けたポーズデータを用いた動作識別手法の調査**  <span onmouseover="document.getElementById('cpsy1911takasaki').style.display = 'block'"  onmouseout="document.getElementById('cpsy1911takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *電子情報通信学会 CPSY研究会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1911takasaki"> センサの発達やクラウドコンピューティングの普及により，一般家庭で取得，蓄積した動画像が子 供やお年寄りの見守りサービスや防犯対策，セキュリティに活用されるようになってきた.しかし，家庭のセン サで取得した動画像をリアルタイムに機械学習を用いて解析するにはデータサイズと解析計算量が大きいため， サーバやストレージを用いてデータの分析や蓄積を行う必要がある.本研究では，センサ側で姿勢推定ライブラ リ OpenPose を使って前処理を行い，動画像から特徴量を抽出してデータ量を削減した後，クラウドでその特徴 量データを収集して機械学習を用いて動作の識別を行うことで処理遅延，プライバシ，通信コストの問題に対処 する.前処理によりもとの動画像に含まれていた情報量が大幅に失われてしまうため，特徴量のみでどの程度の 精度で学習や推論ができるのかについて調査した。複数の手法において 80% 以上の精度で動作を識別すること が可能であり、LSTM を用いた動作識別の精度が最もよくなることがわかった.</div> </blockquote>



- **階層型強化学習 RGoal を用いた記号推論の実現手法の検討**  <span onmouseover="document.getElementById('sigagi1908ichisugi').style.display = 'block'"  onmouseout="document.getElementById('sigagi1908ichisugi').style.display = 'none'">[abst]</span>   
一杉裕志, 高橋直人, 中田秀基, 佐野崇
, *第12回汎用人工知能研究会 (SIG-AGI)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi1908ichisugi"> 我々はヒト前頭前野周辺の計算論的モデルの構築を目指しており、それに向けて再帰的にサブルーチン呼び出しが可能な階層型強化学習アーキテクチャ RGoal を提案している。本論文では RGoal にわずかな拡張を加えることで、記号推論の一例である定理証明ができることを示す。また、知的エージェントが経験により環境から記号的知識を獲得する機構について考察する。これらの機構は、ヒトの脳における記号推論と記号的知識の獲得の機構の候補である。</div> </blockquote>



- **姿勢推定と RNN を用いた動画動作識別手法の調査**  <span onmouseover="document.getElementById('dicomo19takasaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo19takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *DICOMO 2019 シンポジウム*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo19takasaki"> 防犯カメラなどの動画像データが活用されるようになってきたが，動画像解析に要する通信量や計 算量，プライバシーに関する問題が介在している.また，ディープラーニング技術が画像認識や音声認識 を始めとする様々な分野に応用されているが，正確な認識処理を行うためには大量のデータの収集，処理 が必要となるため，リアルタイムに解析するのは非常に困難である.本研究では，動画像をリアルタイム に解析し，動作の識別を行うことを目標として，姿勢推定ライブラリ OpenPose とディープラーニングフ レームワーク Keras を用いた機械学習手法について考察した.画像 1 枚から抽出した特徴量のみを使用し た学習では，約 80%の精度で動作を識別することが可能であることがわかった.次に，同じ動画から取得 した 10 枚の画像の時系列を考慮した特徴量データを使用して動作の識別精度を測定したところ，画像 1 枚 の識別と比較して識別精度は低下した.また，より長い時系列を考慮した学習を行うために LSTM によ る学習を行い，時間ステップ数や LSTM のノード数，dropout の導入有無を変化させて動作識別精度を比 較したところ，ノード数 50，時間ステップ数 30，入力の線形変換における dropout を設定して学習を行 なった際の精度が最も良く約 83%となった.</div> </blockquote>



- **A Sub-policy Pruning Method for Meta Learning Shared Hierarchies** [[Slides](dataDir/jsai19hong_slides.pdf)]  <span onmouseover="document.getElementById('jsai19hong').style.display = 'block'"  onmouseout="document.getElementById('jsai19hong').style.display = 'none'">[abst]</span>   
Qing Hong, Yusuke Tanimura, Hidemoto Nakada
, *人工知能学会全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai19hong"> 階層化強化学習の一つであるMLSHは、タスク集合があるタスク分散からサンプルされることを前提にサブポリシという形で過去のタスクに対する知識を保持することで、新しいタスクに対する学習を高速化する。この際、サブポリシの数はタスクに内在するサブゴールの数と一致していることが望ましいが、タスクのサブゴールの数は一般に事前に知ることはできない。本稿はこの問題を解決するために、十分な数のサブポリシ数でスタートし、徐々に枝刈りを行うことで適切なサブポリシ数に至ることを目指す手法を提案する。2D-bandid 問題を用いて本手法を評価したところ、多くの場合に適切な数のサブポリシ数を見出すことができた。</div> </blockquote>



- **階層型強化学習 RGoal アーキテクチャへの再帰呼び出し用スタックの導入**  <span onmouseover="document.getElementById('jsai19ichisugi').style.display = 'block'"  onmouseout="document.getElementById('jsai19ichisugi').style.display = 'none'">[abst]</span>   
一杉裕志, 高橋直人, 中田秀基, 佐野崇
, *人工知能学会全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai19ichisugi"> 人間は何か目的を達成するために適切なサブゴールを設定できる。さらに必要に応じてそのサブゴールを再帰的に設定することができ、その再帰の深さには制約がないように見える。我々はこれまでに、この振る舞いにヒントを得た階層型強化学習の新しいアーキテクチャとして、RGoal アーキテクチャを提案した。本稿では、サブルーチンの再利用性を高めるために、アーキテクチャに呼び出し用スタックを導入する方法を提案する。そして、マルチタスク環境での迷路タスクにより性能を評価した。その結果、スタックの深さの最大値が大きいほど、収束が早くなる傾向がみられた。今後このアーキテクチャを拡張し、脳の前頭前野周辺の情報処理機構のモデルを構築することを目指す。</div> </blockquote>



- **One-shot Learning using Triplet Network with kNN classifier** [[Slides](dataDir/jsai19zhou-slides.pdf)]  <span onmouseover="document.getElementById('jsai19zhou').style.display = 'block'"  onmouseout="document.getElementById('jsai19zhou').style.display = 'none'">[abst]</span>   
Mu Zhou, Yusuke Tanimura, Hidemoto Nakada
, *人工知能学会全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai19zhou"> 本稿では、Triplet NetworkとK近傍クラス分類器を用いたワンショット学習技術を提案する。ワンショット学習では、クラスごとに正例を1つだけあたえて訓練した学習機で対象画像のクラス分類を行う。この手法では、Tripletネットワークを用いて画像をユークリッド空間にマップし、その空間でK近傍クラス分類を行う。この際に、正例画像をデータ拡張することでワンショット学習を可能にする。MNISTデータセットを用いて実験を行い、提案手法の有効性を確認した。</div> </blockquote>



- **Design a Loss Function which Generates a Spatial configuration of Image In-betweening** [[Slides](dataDir/jsai19paulino-slides.pdf)]  <span onmouseover="document.getElementById('jsai19paulino').style.display = 'block'"  onmouseout="document.getElementById('jsai19paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Yusuke Tanimura, Hidemoto Nakada, Hideki Asoh
, *人工知能学会全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai19paulino"> Instead of generating image inbetween directly from adjacent frames, we propose a method based on inbetweening in latent space. We design a simple loss function which generates a latent space that represent the spatial configu- ration of image inbetween. Contrary to the frame based methods, this model can make plausible assumption about the moving objects in the image and can capture what is not seen in the images. Our model has three networks, all based on variational autoencoder, sharing same weights. We validate this model on different synthetic datasets. We show the details of our network architecture and the evaluation results.</div> </blockquote>



- **Wasserstein Autoencoderを用いた画像スタイル変換** [[Slides](dataDir/jsai19nakada-slides.pdf)]  <span onmouseover="document.getElementById('jsai19nakada').style.display = 'block'"  onmouseout="document.getElementById('jsai19nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 麻生 英樹
, *人工知能学会全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai19nakada"> 本稿ではWasserstein Autoencoderを用いた画像スタイル変換を提案する。画像スタイル変換とは、コンテント画像に対してスタイル画像から抽出したスタイルを適用することで、任意のコンテントを任意のスタイルで描画する技術である。スタイル変換はこれまでも広く研究されてきたが、その多くにはスタイルに対して学習が必要なため実行に時間がかかるという問題がある。 本稿で提案する手法は、スタイルとコンテントが分離した形で隠れ変数として表現されるようにネットワークを構成することで、スタイル変換を実現する。特定のスタイルに対してネットワークを訓練する必要がないため、任意の画像に対して任意のスタイルを即座に適用できる。CerebAの画像に対していくつかのスタイルを適用したところ、良好な画像が得られることを確認できた。</div> </blockquote>



- **ニューラルネットワークを用いた任意人物・姿勢画像の生成**    
中田 秀基, 麻生 英樹
, *電子情報通信学会 パターン認識・メディア理解研究会 信学技法 Vol. 118, No.513*   , pp. 73-78  , 2019 



- **姿勢推定ライブラリOpenPoseを用いた機械学習による動作識別手法の比較**  <span onmouseover="document.getElementById('zen19takasaki').style.display = 'block'"  onmouseout="document.getElementById('zen19takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第81回全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen19takasaki"> 近年、カメラやセンサ等の発達によって一般家庭でライフログを取得することが可能になり，活用されるようになってきた。しかし、取得した動画像はデータサイズと解析計算量が大きく、サーバやストレージを一般家庭に設置して処理するのは難しい。リアルタイムに機械学習を用いて動画像を解析するためには、センサ側での前処理により特徴量を維持したままデータ量を削減した後、クラウド側に集約しで処理することが望ましい。本研究では、深層学習を用いて人の関節情報を抽出するライブラリOpenPoseを使用し、動画像から取得した関節の特徴量データから複数の機械学習手法を用いて動作識別を行った際の認識精度を比較する。</div> </blockquote>



- **スケーラブルな分散ストリーム処理基盤の検討と構築**  <span onmouseover="document.getElementById('zen19kato').style.display = 'block'"  onmouseout="document.getElementById('zen19kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第81回全国大会*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen19kato"> 近年、カメラやセンサ等の普及とクラウド技術の発達により、一般家庭でのライフログの蓄積と利用が拡大している。また、ディープラーニングを用いた画像や音声の認識処理が非常に注目されている。しかし、その処理の重さから一般家庭で収集した動画像データをリアルタイムに識別するのは困難である。そこで本研究では、分散プラットフォームとディープラーニングフレームワークを用いた動画像の分散識別処理をストリーミング環境に適応させ、スケーラブルな分散ストリーム処理基盤の構築について検討する。</div> </blockquote>



- **姿勢推定ライブラリOpenPoseを用いた機械学習による動作識別手法の検討**  <span onmouseover="document.getElementById('deim19takasaki').style.display = 'block'"  onmouseout="document.getElementById('deim19takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *第11回データ工学と情報マネジメントに関するフォーラム*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim19takasaki"> 防犯カメラなどの動画像データが活用されるようになってきたが，動画像解析に要する通信量や計算量， プライバシーに関する問題が介在している.また，ディープラーニング技術が画像認識や音声認識を始めとする様々 な分野に応用されているが，正確な認識処理を行うためには大量のデータの収集，処理が必要となるため，リアルタ イムに解析するのは非常に困難である.本研究では，動画像をリアルタイムに解析し，動作の識別を行うことを目標 として，姿勢推定ライブラリ OpenPose とディープラーニングフレームワーク Keras を用いた機械学習手法について 考察した.画像 1 枚から抽出した特徴量のみを使用した学習では，約 80%の精度で動作を識別することが可能である ことがわかった.次に，同じ動画から取得した 10 枚の画像の時系列を考慮した特徴量データを使用して動作の識別精 度を測定したところ，画像 1 枚の識別と比較して識別精度は低下した.実験結果をもとに，その原因と識別精度を向 上させる手法について考察する.</div> </blockquote>



- **スケーラブルな分散ストリーム処理基盤の構築と評価**  <span onmouseover="document.getElementById('deim19kato').style.display = 'block'"  onmouseout="document.getElementById('deim19kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *第11回データ工学と情報マネジメントに関するフォーラム*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim19kato"> カメラやセンサ等の普及とクラウド技術の発達により，一般家庭でのライフログの蓄積と利用が拡大して いる.また，ディープラーニングを用いた画像や音声の認識処理が非常に注目されている.しかし，その処理の重さ から一般家庭で収集した動画像データをリアルタイムに識別するのは困難である.我々は，分散プラットフォームと ディープラーニングフレームワークを用いた動画像の分散識別処理をストリーミング環境に適応させ，スケーラブル な分散ストリーム処理基盤を構築している.予備実験として，大規模分散プラットフォームの Apache Spark と分散実 行フレームワーク Ray の分散性能を調査し，Ray による高速かつスケーラブルな分散処理が可能であることを示す. 次に，分散メッセージングシステム Apache Kafka と Ray を用いた分散ストリーム処理基盤を構築し，その性能を評 価する.実験から，スケーラブルな分散ストリーム処理基盤が構築可能であることを示す.</div> </blockquote>



- **A Hybrid Simulator to Analyze Gradient Staleness Effect**  <span onmouseover="document.getElementById('os19duo').style.display = 'block'"  onmouseout="document.getElementById('os19duo').style.display = 'none'">[abst]</span>   
Duo Zhang, Yusuke Tanimura, Hidemoto Nakada
, *情報処理学会 システムソフトウェアとオペレーティング・システム研究会 研究報告 Vol.2019-OS-145 No.8*   , pp. 1-6  , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os19duo"> One of the obstacles for parallel execution of Deep Learning is the Gradient exchange overhead, and there are numerous exchange methods are proposed to mitigate the overhead. Investigating these methods with real machines requires a lot of resources. Furthermore, it is impossible to investigate the behavior under other circumstances, such as different network latency. We propose a hybrid simulator that combines gradient computation on real machine and virtual time management using discrete event simulator, that enables to accurately reproduce the behavior under arbitrary gradient exchange methods and arbitrary setup. We implemented this simulator using Python coroutine. We confirmed that we can reproduce the behavior of asynchronous gradient exchange, and it can handle 64 nodes with single node.</div> </blockquote>



- **Designing Loss Function which Generate Latent Space for image in-betweening.**  <span onmouseover="document.getElementById('isaj18paulino').style.display = 'block'"  onmouseout="document.getElementById('isaj18paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Hidemoto Nakada, Yusuke Tanimura, Hideki Asoh
, *9th Annual Symosium of Indian Scientists association in japan*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="isaj18paulino"> Learning interpretable latent representation of independent data is an important task of intelligence machines. We design a loss function which generate a latent space that represent the spatial configuration of the object in the images. The resulting latent space could be used for image in-betweening or image prediction. Our network architecture is based on the variational autoencoders.</div> </blockquote>



- **単一化の機構を利用した階層型強化学習のテーブル圧縮手法の検討**  <span onmouseover="document.getElementById('wba18ichisugi-2').style.display = 'block'"  onmouseout="document.getElementById('wba18ichisugi-2').style.display = 'none'">[abst]</span>   
一杉裕志, 高橋直人, 中田秀基, 佐野崇
, *第10回 人工知能学会 汎用人工知能研究会(SIG-AGI)*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="wba18ichisugi-2"> We propose a method of compressing the size of the table of the action value function for the hierarchical reinforcement learning architecture RGoal, using a mechanism of unification. Moreover, we study the characteristics of RGoal as a program synthesis system.</div> </blockquote>



- **One-shot Learning using Triplet Networks with KNN**  <span onmouseover="document.getElementById('ibisml18zhou').style.display = 'block'"  onmouseout="document.getElementById('ibisml18zhou').style.display = 'none'">[abst]</span>   
Mu Zhou, Hidemoto Nakada, Yusuke Tanimura
, *第21回情報論的学習理論ワークショップ（IBIS2018）ディスカッショントラック*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml18zhou"> We propose triplet networks with KNN for the problem of one-shot learning, in which we predict the query images correctly by given only single example of each class where we do the data augmentation. Our triplet network learns a mapping from sample images to the Euclidean space. Then we apply KNN classifier on the embeddings generated by the triplet network to classify the query sample.</div> </blockquote>



- **Designing Loss Function which Generate Latent Space for image in-betweening.**  <span onmouseover="document.getElementById('ibisml18paulino').style.display = 'block'"  onmouseout="document.getElementById('ibisml18paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Hidemoto Nakada, Yusuke Tanimura, Hideki Asoh
, *第21回情報論的学習理論ワークショップ（IBIS2018）ディスカッショントラック*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisml18paulino"> Learning interpretable latent representation of independent data is an important task of intelligence machines. We design a loss function which generate a latent space that represent the spatial configuration of the object in the images. The resulting latent space could be used for image in-betweening or image prediction. Our network architecture is based on the variational autoencoders.</div> </blockquote>



- **RGoal Architecture:再帰的にサブゴールを設定できる階層型強化学習アーキテクチャ**  <span onmouseover="document.getElementById('wba18ichisugi').style.display = 'block'"  onmouseout="document.getElementById('wba18ichisugi').style.display = 'none'">[abst]</span>   
一杉裕志, 高橋直人, 中田秀基, 佐野崇
, *第9回 人工知能学会 汎用人工知能研究会(SIG-AGI)*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="wba18ichisugi"> Humans can set suitable subgoals in order to achieve some purposes, and furthermore, can set sub-subgoals recursively if needed. It seems that the depth of the recursion is unlimited. Inspired by this behavior, we have designed a new hierarchical reinforcement learning architecture, the RGoal architecture. The algorithm is designed to solve the MDP on the augmented stateaction space. The action-value function becomes shareable among multi-tasks due to the value function decomposition. The sharing accelerates learning in multi-task setting. The mechanism named “think-mode” is a kind of model-based reinforcement learning. It combines learned simple tasks in order to solve inexperienced complicated tasks quickly, or in zero-shot in some cases. The algorithm is realized by a flat table and repetition of simple operations, without a stack. Hereafter, we will extend this architecture, and will build the model of the information processing mechanism of the prefrontal cortex in the brain.</div> </blockquote>



- **Adaptation of Ray, a distributed framework for machine learning, to MPI-based environment**  <span onmouseover="document.getElementById('swopp18ou').style.display = 'block'"  onmouseout="document.getElementById('swopp18ou').style.display = 'none'">[abst]</span>   
Tianlun WANG, Yusuke Tanimura, Hidemoto Nakada
, *信学技法  vol. 118, no. 165 IEICE-CPSY*   , pp.  205-210  , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp18ou"> Ray is a distributed framework for machine learning that targets reinforcement learning using multiple nodes. While it works well on loosely coupled nodes, it does not take into account the“high-performance computing environment ”based on MPI. We modified Ray so that, 1) it works well with the MPI launch mechanism, and 2) it use MPI communication for large data transfer. We evaluated the modified version of Ray on a cluster and confirmed the preliminary performance.</div> </blockquote>



- **Asynchronous Deep Learning Test-bed to Analyze Gradient Staleness Effect**  <span onmouseover="document.getElementById('swopp18duo').style.display = 'block'"  onmouseout="document.getElementById('swopp18duo').style.display = 'none'">[abst]</span>   
Duo Zhang, Yusuke Tanimura, Hidemoto Nakada
, *信学技法  vol. 118, no. 165 IEICE-CPSY*   , pp. 199-204  , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp18duo"> For modern machine learning systems, including deep learning systems, parallelization is inevitable since they are required to process massive amount of training data. One of the hot topic of this area is the data parallel learning where multiple nodes cooperate each other exchanging parameter / gradient periodically. In order to efficiently implement data-parallel machine learning in a collection of computers with a relatively sparse network, it is indispensable to asynchronously update model parameters through gradients, but the effect of the learning model through asynchronous analysis has not yet been fully understood. In this paper, we propose a software test-bed for analyzing gradient staleness effect on prediction performance, using deep learning framework TensorFlow and distributed computing framework Ray. We report the architecture of the test-bed and initial evaluation results.</div> </blockquote>



- **大規模データ分散処理基盤におけるパラメータ制御の一検討**  <span onmouseover="document.getElementById('dicomo18kato').style.display = 'block'"  onmouseout="document.getElementById('dicomo18kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2018)シンポジウム*   , pp. 987 - 991
  , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo18kato"> 近年カメラやセンサ等の発達やクラウドコンピューティングの普及により，一般家庭でのライフロ グの取得とそのデータの蓄積が可能になった.これらの技術は，遠隔地から家庭にいるお年寄りや子供， ペットを見守ることができる安全サービスや，防犯対策・セキュリティといった用途に応用されている. しかし，サーバやストレージを一般家庭に設置して取得・蓄積した動画像データの解析をするのは困難で あるため，センサから取得した動画像データはクラウドに送信して解析する必要がある.ここで，動画像 はデータサイズが大きいため，クラウドでの機械学習処理による動画像データ解析に要する計算量は大き くなる.また，クラウドには非常に多くの家庭からデータが送信されることが想定されるため，クラウド での並列機械学習処理が必要不可欠である.我々は，大規模データ分散処理プラットフォーム Apache Spark(以降，Spark と呼ぶ) を用いて，ディープ ラーニングフレームワーク Chainer による機械学習処理を並列化させ，そのパラメータを調整することで 動画像データ解析処理の効率化を検討してきた.本稿では，Spark を用いた Chainer の並列処理と，分散処 理フレームワーク Ray を用いた Chainer の並列処理について比較しつつ，処理の効率化について検討する.</div> </blockquote>



- **Sub-policy pruning in Meta Learning Shared Hierarchies**  <span onmouseover="document.getElementById('sigagi1803hon').style.display = 'block'"  onmouseout="document.getElementById('sigagi1803hon').style.display = 'none'">[abst]</span>   
Ging Hong, Yusuke Tanimura, Hidemoto Nakada
, *人工知能学会汎用人工知能研究会*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi1803hon"> MLSH (Meta Learning Shared Hierarchies) is a meta learning method that divide a policy into multiple sub-policies and a master-policy that picks one of the sub-policies to be actually used. By training sub-policies in advance, master policy can rapidly adjust to given environments. However, MLSH is not suitable for complicated environments. In complicated environments, a number of sub-policies are required,  and it is very difficult to train them properly. We propose a method to effectively prune excessive sub-policies to give better chance the other sub-policies to be trained.</div> </blockquote>



- **Toward image inbetweening using Latent Model**  <span onmouseover="document.getElementById('prmu1803paulino').style.display = 'block'"  onmouseout="document.getElementById('prmu1803paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Yusuke Tanimura, Hidemoto Nakada, Hideki Asoh
, *信学技法 IEICE-PRMU2017-185, vol. IEICE-117, no.514*   , pp. 79-84  , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="prmu1803paulino"> Image interpolation is a well known problem in computer vision. Many approaches are restricted to optical flow and convolutional neural network. In this work, we present an alternative approach based on generative models to generate in between images (interpolation) using variational autoencoders (VAE). The goals are: Generate in between images using hidden structures (latent variables), and yield latent features that generalize well. Our architecture composed of three networks (VAE) that share weights. We train the network feeding three continous frames so that the second latent variables become close to the average of the first and third latent variables. To get interporated image from two images, we can just reconstract the image from the avarage of the two images&#x27; latent variables. We evaluate the result by comparing the ground truth image and the generated one to evaluate the in between image. In addition we show the reconstructed images using the same network.</div> </blockquote>



- **Variational Autoencoderを用いた画像スタイル変換**  <span onmouseover="document.getElementById('prmu1803nakada').style.display = 'block'"  onmouseout="document.getElementById('prmu1803nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 麻生 英樹
, *信学技法 IEICE-PRMU2017-185, vol. IEICE-117, no.514*   , pp. 121-126  , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="prmu1803nakada"> 画像スタイル変換は、コンテント画像に対してスタイル画像から抽出したスタイルを適用することで、任意のコンテントを任意のスタイルで描画することを実現する技術である。 従来手法の多くは、スタイルに対して学習が必要なため実行に時間がかかるという  問題があった。本稿ではVariational Autoencoderを用い、隠れ変数にスタイルとコンテントを分離して学習させることによって、スタイル変換を行う手法を提案する。本手法は、スタイルに対する学習の必要がなく、任意の画像に対して任意のスタイルを即座に適用できるという特徴を持つ。スタイルを表す隠れ変数とコンテントを表す隠れ変数の間の相互情報量が小さくなるようにすることで、比較的良好なスタイル変換が実現できた。</div> </blockquote>



- **ビックデータ分散処理基盤を用いたタスク並列化におけるパラメータ制御の考察**  <span onmouseover="document.getElementById('zen18kato').style.display = 'block'"  onmouseout="document.getElementById('zen18kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第80回全国大会*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen18kato"> カメラやセンサ等の発達により，一般家庭でのライフロ グの取得が可能になり，活用されるようになった.サーバ やストレージを一般家庭に設置して解析するのは困難でる ため，取得した動画像データはクラウドで解析する必要が ある.しかし，動画像はデータサイズが大きく，その解析 に要する計算量も膨大になるので，クラウドにおける負荷 も大きくなる.本研究では，大規模データ分散処理プラッ トフォーム Apache Spark(以降，Spark と呼ぶ)[1] を用い てディープラーニングフレームワーク Chainer[2] による機 械学習処理を並列化させることで，動画像データ解析処理 の効率化を検討してきた [4].本稿では特に，Spark のパ ラメータ制御を行うことによるタスク並列化について考察する.</div> </blockquote>



- **Kafka と Spark Streaming を利用した リアルタイム動画像解析フレームワークの評価**  <span onmouseover="document.getElementById('zen18ichinose').style.display = 'block'"  onmouseout="document.getElementById('zen18ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第80回全国大会*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen18ichinose"> 近年各種センサの普及やクラウドコンピューティング技 術の習熟に伴い，お年寄りや子供のための安全サービスな どを目的としたライフログが活用されている.しかし，動 画像解析のようなデータ量，計算量の多い処理をクラウド でリアルタイムに行うことは困難である. 本研究では，Kafka と Spark Streaming を用いた，複数カ メラからの動画収集とその解析処理を効率よく行う動画像 解析フレームワークを構築している [1].本稿では，デー タの収集を行う Kafka のレプリケーションの設定による性 能の変化に注目し，提案フレームワークのスループットを 計測した.実験から，レプリケーション数を増やすことに よりネットワークの輻輳が起き，データ転送のスループッ トが低下することが確認できた.また，データ転送のス ループット低下により，ストリーム処理における 1 マイク ロバッチあたりの処理数が小さくなり，システム全体のス ループットが低下することが確認できた.</div> </blockquote>



- **ビックデータ分散処理基盤におけるパラメータ制御の一検討**  <span onmouseover="document.getElementById('deim18kato').style.display = 'block'"  onmouseout="document.getElementById('deim18kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *DEIM 2018 (第10回データ工学と情報マネジメントに関するフォーラム)*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim18kato"> 近年，お年寄りや子供を見守るサービスや防犯カメラなどによるライフログの利用が普及し，多様に活用 されるようになってきている.また，ディープラーニング技術が非常に発達してきており，画像認識や音声認識を始 めとする様々な分野に応用されている.しかし正確な認識処理を行うためには大量のデータ処理が必要となるため， 処理の並列化が求められる.本研究では，ディープラーニングフレームワークである Chainer をクラスタコンピュー ティングプラットフォーム Apache Spark 上で動作させ，分散並列機械学習処理を行う.実験から，Spark のパラメー タ調整による処理の効率化について検討する.</div> </blockquote>



- **Kafka を利用したリアルタイム動画像解析フレームワークの レプリケーションによる性能変化の調査**  <span onmouseover="document.getElementById('deim18ichinose').style.display = 'block'"  onmouseout="document.getElementById('deim18ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *DEIM 2018 (第10回データ工学と情報マネジメントに関するフォーラム)*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim18ichinose"> 近年各種センサの普及やクラウドコンピューティング技術の習熟に伴い，お年寄りや子供のための安全サー ビスなどを目的としたライフログが活用されている.しかし，動画像解析のようなデータ量，計算量の多い処理をク ラウドでリアルタイムに行うことは困難である.我々は，Kafka と Spark Streaming を用いた，複数カメラからの動画像収集とその解析処理を効率よく行う動画像解 析フレームワークを構築している.本稿では，データ収集を行う Kafka のレプリケーションの設定による性能の変化 に注目し，提案フレームワークのスループットを計測した.実験から，レプリケーション数を増やすことによりネッ トワークの輻輳が起き，データ転送のスループットが低下し，システム全体のスループットが低下することがわかっ た.また，ネットワーク帯域を十分に増やすことにより性能劣化を軽減でき，レプリケーション数を増やした場合に も Worker の処理能力に応じたスループットで解析処理できることが確認できた.</div> </blockquote>



- **Storage-Side Processing for Spark with Tiered Storage**  <span onmouseover="document.getElementById('hpc1802chou').style.display = 'block'"  onmouseout="document.getElementById('hpc1802chou').style.display = 'none'">[abst]</span>   
Kaihui Zhang, Yusuke Tanimura, Hidemoto Nakada, Hirotaka Ogawa
, *研究報告ハイパフォーマンス・コンピューティング（HPC）2017-HPC-163(7)*   , pp. 1--6  , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1802chou"> Apache Spark is a parallel data processing framework that executes fast for iterative calculations and interactive processing, by caching intermediate data in memory with a lineage-based data recovery from faults. However, Spark still needs to load input data from a persistent storage at the beginning of main analytics and store the final result on the storage at the end of the analytics. In this study, we use a memory-based, tiered storage called Alluxio for the persistent storage of Spark and implement the active storage concept, which utilizes processing resources on the storage side and reduces the amount of I/O between Spark and Alluxio. As our first step, we implemented filtering on the Alluxio worker and examined performance improvement of reading data. The results showed that the performance was worse than we expected, due to inefficiency of storage-side filtering in our implementation.</div> </blockquote>



- **大規模データ分散プラットフォームApache Sparkにおけるタスク並列化に関する検討**    
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *信学技報, vol. 117, no. 371, MoNA2017-39*    , 2017 



- **KafkaとSpark Streamingを利用したリアルタイム動画像解析フレームワークの構成検討**    
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *信学技報, vol. 117, no. 371, MoNA2017-39*    , 2017 



- **人工知能・機械学習の応用・研究に適したパブリッククラウドサービス**  <span onmouseover="document.getElementById('ai-resource-cloud').style.display = 'block'"  onmouseout="document.getElementById('ai-resource-cloud').style.display = 'none'">[abst]</span>   
中田 秀基
, *人工知能 Vol.33 No.1*   , pp. 15-22  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ai-resource-cloud"> 昨今の大容量データを利した機械学習や人工知能の研究、応用は膨大な計算を必要とする。このような計算を実行する方法の一つとして、クラウド事業者が提供するパブリッククラウドを用いる方法が考えられる。パブリッククラウドサービスを用いると、計算機資源の初期コストを低減させることができるだけでなく、計算機管理にかかるコストを省くことができる。さらにクラウド事業者が持つ高度な技術を利用する事が可能になる。本稿では、さまざまなパブリッククラウドサービスを、サービス形態を軸にIaaS、PaaS、SaaSの3つに整理した上で、それぞれに対して、現在利用可能な機械学習・人工知能の研究・応用に適したパブリッククラウドサービスを紹介する。</div> </blockquote>



- **特集「AI 計算資源」にあたって**  <span onmouseover="document.getElementById('ai-resource').style.display = 'block'"  onmouseout="document.getElementById('ai-resource').style.display = 'none'">[abst]</span>   
上野聡, 高橋恒一, 中田 秀基
, *人工知能 Vol.33 No.1*   , pp. 5--7  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ai-resource"> 現在のAIブームは、1960年代の第一期、1980年代の第二期に続く、第三期であると言われている。第三期のAIブームを特徴づけているのは、インターネットの発展によって蓄積された大量の計算機可読データと、計算処理能力の著しい向上によって初めて可能になった、機械学習手法である。人工知能研究における計算機資源の重要性はこれまでになく大きくなっている。今後の人工知能の研究・応用には、十分な計算機資源を調達し、活用していくことが不可欠である。本特集は、読者が人工知能研究・応用を行う上で必要となる計算機資源を調達する際の指針となるべく構成されている。長期的な計画立案の補助として、今現在利用可能なものだけでなく、近い将来利用可能となることが予想される技術に関しても言及する。</div> </blockquote>



- **A study on the performance of DDPG (Deep Deterministic Policy Grandient)**  <span onmouseover="document.getElementById('ibisws1711hong').style.display = 'block'"  onmouseout="document.getElementById('ibisws1711hong').style.display = 'none'">[abst]</span>   
Ging Hong, Yusuke Tanimura, Hidemoto Nakada
, *第20回情報論的学習理論ワークショップ ディスカッショントラック*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisws1711hong"> 強化学習とニューラルネットワークを結合した学習モジュールは、比較的単純な環境であるビデオゲームなどにおいては人間よりも高い性能を示すことが知られているが、より複雑な環境における性能は明らかではない。本稿ではActorとCritic双方にDDPを用いるアルゴリズムDDPGを高度に複雑なシミュレーション環境における学習に適用し、その有用性を確認する。</div> </blockquote>



- **VAEを用いた画像スタイル変換に向けて**  <span onmouseover="document.getElementById('ibisws1711nakada').style.display = 'block'"  onmouseout="document.getElementById('ibisws1711nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 麻生 英樹
, *第20回情報論的学習理論ワークショップ ディスカッショントラック*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibisws1711nakada"> 画像スタイル変換は、対象画像をそのコンテントを維持しながら、他の画像のスタイルに従うように変換する操作である。従来のスタイル変換ネットワークを学習する手法では、スタイルごとにネットワークを学習したり、スタイルを独立したネットワークで学習する必要があった。本稿ではVAEを用いて、スタイル情報を隠れ変数の一部として抽出し、隠れ変数の一部を変更することでスタイル変換を行うネットワークを提案する。</div> </blockquote>



- **A Performance Evaluation of Distributed TensorFlow**  <span onmouseover="document.getElementById('hpc1709ou').style.display = 'block'"  onmouseout="document.getElementById('hpc1709ou').style.display = 'none'">[abst]</span>   
Tianlun Wang, Yusuke Tanimura, Hirotaka Ogawa, Hidemoto Nakada
, *研究報告ハイパフォーマンス・コンピューティング（HPC）2017-HPC-161*   , pp. 1--6  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1709ou"> TensorFlow is a deep learning framework which is developed by Google. The computations in TensorFlow are implemented and expressed as data flow graphs of multidimensional array data which is referred to as “Tensor.” We know that, with TensorFlow we can implement parallel execution in a multi-GPU configuration and distributed execution in a multi-node configuration, but it is not clear how effective it is in the real environment. In this paper, we measured these performances for several mini batch sizes and network settings. From the experimental results, we confirmed that we can accelerate the execution in all the environment we have tested. We also found that the mini batch size has a big influence in the distributed environment of 1Gbps network. However, in the environment of 10Gbps network or the intra-node multipl-GPU configuration, we could achieve the linear speed up regardless of mini batch size.</div> </blockquote>



- **A study on Network Structure and Parameter Exchange Method in large-scale Cluster for Machine Learning**  <span onmouseover="document.getElementById('swopp17duo').style.display = 'block'"  onmouseout="document.getElementById('swopp17duo').style.display = 'none'">[abst]</span>   
Dou Zhang, Rei Mingxi, Yusuke Tanimura, Hidemoto Nakada
, *信学技報, vol. 117, no. 153, CPSY2017-29*   , pp. 145-150  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp17duo"> For modern machine learning systems, including deep learning systems, parallelization is inevitable since they are required to process massive amount of training data. One of the hot area of this area is the data parallel learning where multiple nodes cooperate each other exchanging parameter / gradient periodically. In this paper, we focus on the network resource requirement for this kind of application. We investigate 3-layered Clos network and omega-network adding to the 2-layered fat tree network which we have already reported. As parameter exchange method, we tested direct parameter exchange method and centralized server method. We evaluated these three types of network with SimGrid, a simulator for distributed environment, and confirmed that with suitable parameter exchange methods, we can maintain performance with higher over subscription factor.</div> </blockquote>



- **ビッグデータ処理基盤Apache Sparkのストリーミング機能を利用したセンサデータ解析フレームワークの検討**  <span onmouseover="document.getElementById('dicomo17ichinose').style.display = 'block'"  onmouseout="document.getElementById('dicomo17ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2017)シンポジウム*   , pp. 1583 - 1587  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo17ichinose"> 各種センサの普及やクラウドコンピューティング技術の習熟に伴い，お年寄りや子供のための安全 サービスなどを目的としたライフログの利用が普及してきている．しかし，動画像解析のようなデータ量， 計算量の多い処理をクラウドでリアルタイムに行うことは困難である．また，近年ディープラーニング技 術の発達で，その高い精度から画像や音声の認識などに広く用いられているが，計算負荷が高いことが課 題の一つとなっている． 本研究では，複数カメラからの動画収集とその解析処理を，効率よく高速に行う解析フレームワークの構 築を目指し，Apache Kafka によるデータ収集と Apache Spark のストリーミング機能と Chainer を用い た機械学習を行う．本稿では，提案フレームワークの性能向上に向け，まずはデータ転送を行う Apache Kafka の性能調査を行った．</div> </blockquote>



- **ビッグデータ分散処理基盤を用いた機械学習処理並列化に関する一考察**  <span onmouseover="document.getElementById('dicomo17kato').style.display = 'block'"  onmouseout="document.getElementById('dicomo17kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2017)シンポジウム*   , pp. 796 - 802  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo17kato"> 各種センサーや防犯カメラなどによるライフログの収集，利用が可能となり，お年寄りや子供を見守るサービスなど多様に活用されるようになってきているが，動画像の収集・解析に要する通信量や計算量が課題となる.また，近年ディープラーニングの技術が非常に発達してきており，画像認識や音声認識を始めとする様々な分野に応用されている.しかし複数カメラから送信される大量の動画像の解析を高速に行うには，処理の並列化が求められる.そこで本研究では，ディープラーニングフレームワークである Chainer を，クラスタコンピューティングプラットフォームである Apache Spark 上で動作させることによる，分散並列機械学習処理において分散の挙動を調査する実験を行い，その実態と高速化について考察する.</div> </blockquote>



- **人間とAIの共働**    
中田秀基
, *佐倉市国際文化大学*    , 2017 



- **大規模機械学習向けクラスタにおけるネットワーク構造とパラメータ交換手法** [[Paper](dataDir/xsig17rei.pdf)] [[Slides](dataDir/xsig17rei-slides.pdf)]  <span onmouseover="document.getElementById('xsig17rei').style.display = 'block'"  onmouseout="document.getElementById('xsig17rei').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 中田 秀基
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17rei"> 大規模なデータを対象とする機械学習システムの高速化には並列化が必須である。データ並列機械学習システムにおいては、何らかの方法で機械学習機内のパラメータの値を交換する必要があるが、パラメータ交換手法とネットワーク構造の関係は知られていない。本研究では、ネットワークシミュレータSimGridを用いて、さまざまなネットワークと、パラメータ交換手法を組み合わせて評価を行った。その結果、パラメータ交換手法によっては、ネットワークバイセクションバンド幅の影響をほとんど受けず、比較的貧弱なネットワークでも遜色のない性能で実行できることがわかった。</div> </blockquote>



- **Spark におけるディスクを用いた RDD キャッシングの高速化と 効果的な利用に関する検討** [[Paper](dataDir/xsig17chou.pdf)] [[Slides](dataDir/xsig17chou-slides.pdf)]  <span onmouseover="document.getElementById('xsig17chou').style.display = 'block'"  onmouseout="document.getElementById('xsig17chou').style.display = 'none'">[abst]</span>   
張 凱輝, 谷村 勇輔, 中田 秀基, 小川 宏高
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17chou"> Spark は機械学習やデータマイニングなどの反復計算を高速に実行できる並列データ処理フレームワークである.RDD(Resilient Distributed Dataset)と呼ばれる仕組みを利用してインメモリでの並列処理や中間データのキャッシング，耐障害性の確保を実現している点に特徴がある.扱うデータが大きくメモリ容量が 不足する場合には，一部または全部のデータを処理ノードのディスクに置いて処理を行うことも可能である.しかし，ディスクを用いることにより，Spark アプリケーションの実行性能が低下する可能性がある上，このディスク利用の有無をユーザが指示しないといけない問題がある.そこで本研究では，ディスク利用時の RDD キャッシングの効果と性能を調査し，ディスクを効果的に利用するために，メモリとディスクを併用する方式において明らかになった性能低下の問題の解決を試みた.また，ディスクを利用したキャッシング操作自体の高速化を検討するため，性能の異なるディスクを用いた場合の性能比較を行った.これらの結果により，ディスクを用いた RDD キャッシングを利用する際の問題点や注意点を明らかにした.</div> </blockquote>



- **大規模機械学習向けクラスタにおけるネットワークバンド幅とパラメータ交換手法に関する考察** [[Paper](dataDir/xsig17rei-poster.pdf)]  <span onmouseover="document.getElementById('xsig17rei-poster').style.display = 'block'"  onmouseout="document.getElementById('xsig17rei-poster').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 中田 秀基
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming, (poster)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17rei-poster"> 大規模なデータを対象とする機械学習システムの高速化には並列化が必須である。データ並列機械学習システムにおいては、何らかの方法で機械学習機内のパラメータの値を交換する必要があるが、パラメータ交換手法とネットワーク構造の関係は知られていない。本研究では、ネットワークシミュレータSimGridを用いて、さまざまなネットワークと、パラメータ交換手法を組み合わせて評価を行った。その結果、パラメータ交換手法によっては、ネットワークバイセクションバンド幅の影響をほとんど受けず、比較的貧弱なネットワークでも遜色のない性能で実行できることがわかった。</div> </blockquote>



- **Spark におけるディスクを用いた RDD キャッシングの高速化と効果的な利用に関する検討** [[Paper](dataDir/xsig17chou-poster.pdf)]  <span onmouseover="document.getElementById('xsig17chou-poster').style.display = 'block'"  onmouseout="document.getElementById('xsig17chou-poster').style.display = 'none'">[abst]</span>   
張 凱輝, 谷村 勇輔, 中田 秀基, 小川 宏高
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming ,(poster)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17chou-poster"> Spark は機械学習やデータマイニングなどの反復計算を高速に実行できる並列データ処理フレームワークである.RDD(Resilient Distributed Dataset)と呼ばれる仕組みを利用してインメモリの並列処理や耐障害性の確保を実現したり，中間データをキャッシングして再利用可能にしている点に特徴がある.扱うデータが大きくメモリ容量が 不足する場合には，一部または全部のデータを処理ノードのディスクに置いて処理を行うことも可能である.しかし，ディスクを用いることにより，Spark アプリケーションの実行性能が低下する可能性がある上，このディスク利用の有無をユーザが指示しないといけない問題がある.そこで本研究では，ディスク利用時にアプリケーション(Hibenchベンチマーク)の実行性能を調査し，RDDキャッシングのストレージレベルや性能の異なるディスクを用いた場合について実行性能を比較した.その結果をもとに，ディスク利用時の RDDキャッシングの高速化について検討を行い、ディスクを利用する際を注意すべきいくつかの点を明らかにする。更に提案手法により、ベンチマークの実行性能を向上した。</div> </blockquote>



- **ディープラーニングフレームワーク Caffe の分散処理における多種クライアントを用いた比較** [[Paper](dataDir/xsig17ichinose.pdf)]  <span onmouseover="document.getElementById('xsig17ichinose').style.display = 'block'"  onmouseout="document.getElementById('xsig17ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17ichinose"> 近年各種センサの普及とクラウドコンピューティング技術の習熟により，各種センサデータの取得や蓄積が容易になった．その結果監視カメラなどのデータをクラウドで収集して解析するアプリケーションも普及してきている．ここで，センサデータをそのまま送信してクラウドで処理する場合，プライバシや各種センサとクラウド間のネットワーク帯域の問題が生じてしまう．我々は，クラウドへ送るデータのデータ量の削減とプライバシの保護を目的とし，機械学習フレームワークCaffeの処理をクライアント側とクラウド側でパイプライン的に分散処理を行う手法を提案している．その評価として，ニューラルネットワークの分割箇所やパラメータを変化させ処理時間を比較してきた．本稿では，クライアント側として性能の異なる3種類の端末を用いて実験を行い，処理時間を比較した．結果から，端末の性能により全体の処理時間に影響する処理過程が異なり，効率のよい分散方法も異なることも確認できた．</div> </blockquote>



- **Apache Spark のストリーミング機能を利用した機械学習処理の検討**  <span onmouseover="document.getElementById('xsig17ichinose-poster').style.display = 'block'"  onmouseout="document.getElementById('xsig17ichinose-poster').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming ,(poster)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17ichinose-poster"> 各種センサの普及やクラウドコンピューティング技術の習熟に伴い一般家庭におけるライフログの利用が普及しているが、動画像解析のようなデータ量，計算量の多い処理をクラウドでリアルタイムに行うことは困難である。また、近年ディープラーニング技術の発達で、その高い精度から画像や音声の認識などに広く用いられているが、計算負荷の高さが問題の一つとなっている。本研究では、大規模データ処理のための高速かつ汎用性の高いエンジンApache Sparkのストリーミング機能を利用 して、ディープラーニングフレームワークの一つであるChainerの機械学習処理を行い、動画像データ解析処理の高速化を図る。</div> </blockquote>



- **ビッグデータ分散処理基盤を用いた機械学習処理並列化の一検討**  <span onmouseover="document.getElementById('xsig17kato-poster').style.display = 'block'"  onmouseout="document.getElementById('xsig17kato-poster').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming ,(poster)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17kato-poster"> 近年、お年寄りや子供を見守るサービスや防犯カメラなどによるライフログの利用が普及し、多様に活用されるようになってきているが、動画像解析に要する通信量や計算量、プライバシーに関する問題が介在している。また、近年ディープラーニングの技術が非常に発達してきており、画像認識や音声認識を始めとする様々な分野に応用されている。しかし正確な認識処理を行うためには大量のデータ処理が必要となるため、処理の並列化が求められる。そこで本研究では、ディープラーニングフレームワークであるChainerを、クラスタコンピューティングプラットフォームであるApache Spark上で動作させることによる、分散並列機械学習処理に関して検討する。</div> </blockquote>



- **大規模データ分散処理プラットフォーム Apache Spark を用いた分散並列機械学習の検討**  <span onmouseover="document.getElementById('zen17kato').style.display = 'block'"  onmouseout="document.getElementById('zen17kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第79回全国大会*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen17kato"> 近年カメラやセンサ等の発達により，一般家庭でのライ フログの取得が可能になり，お年寄りや子供のための安全 サービスや，防犯対策・セキュリティといった用途に応用 されている.しかし，サーバやストレージを一般家庭に設 置して解析するのは困難であり，取得した動画像データは クラウドで解析する必要がある.ただし，動画像はデータ サイズが大きいため通信量が膨大になってしまい，その解 析に要する計算量も膨大になるので，クラウドでの負荷も 大きくなる.本研究では，大規模データ分散処理プラット フォーム Apache Spark(以降，Spark と呼ぶ)[1] を用いて ディープラーニングフレームワーク Chainer[2] による機械 学習処理を並列化させることで，動画像データ解析処理の 効率化を図る.</div> </blockquote>



- **大規模データ処理フレームワークのストリーミング機能を利用した機械学習処理の検討**  <span onmouseover="document.getElementById('zen17ichinose').style.display = 'block'"  onmouseout="document.getElementById('zen17ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第79回全国大会*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen17ichinose"> 近年各種センサの普及やクラウドコンピューティング技 術の習熟に伴い，お年寄りや子供のための安全サービスな どを目的としたライフログの利用が普及してきている.し かし，動画像解析のようなデータ量，計算量の多い処理を クラウドでリアルタイムに行うことは困難である.また， 近年ディープラーニング技術の発達で，その高い精度から 画像や音声の認識などに広く用いられているが，計算負荷 が高いことが問題の一つとなっている. 本研究では，大規模データ処理のための高速かつ汎用性 の高いエンジン Apache Spark(以降，Spark と呼ぶ) [1] の ストリーミング機能を利用して，ディープラーニングフ レームワークの一つである Chainer [2] の機械学習処理を 行い，動画像データ解析処理の高速化を図る.本稿ではク ライアント側，クラウド側として 2 つの端末間で Apache Kafka [3] を用いてストリーミング処理を行い，クラウド 側で機械学習の識別処理を行った.2 つの端末間のネット ワーク帯域を変化させ，1 秒あたりに識別処理を行える画 像数を計測し，性能を調査した.実験から，低帯域環境に おいてリアルタイムに識別を行うことが可能であることが 示された.</div> </blockquote>



- **大規模データ分散処理プラットフォーム Apache Spark を用いた分散並列機械学習に関する考察**  <span onmouseover="document.getElementById('deim17kato').style.display = 'block'"  onmouseout="document.getElementById('deim17kato').style.display = 'none'">[abst]</span>   
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *第9回データ工学と情報マネジメントに関するフォーラム (DEIM 2017)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim17kato"> 近年各種センサの普及やクラウドコンピューティング技術の習熟に伴い，お年寄りや子供のための安全サー ビスなどを目的としたライフログの利用が普及してきている.しかし，動画像解析のようなデータ量，計算量の多い 処理をクラウドでリアルタイムに行うことは困難である.また，近年ディープラーニング技術の発達で，その高い精 度から画像や音声の認識などに広く用いられているが，計算負荷が高いことが問題の一つとなっている. 本研究では，大規模データ処理のための高速かつ汎用性の高いエンジン Apache Spark のストリーミング機能を利用 して，ディープラーニングフレームワークの一つである Chainer の機械学習処理を行い，動画像データ解析処理の高 速化を図る.本稿ではクライアント側，クラウド側として 2 つの端末間で Apache Kafka を用いてストリーミング処 理を行い，クラウド側で機械学習の識別処理を行った.2 つの端末間のネットワーク帯域を変化させ，1 秒あたりに識 別処理を行える画像数を計測し，性能を調査した.実験から，低帯域環境においてリアルタイムに識別を行うことが 可能であることが示された.</div> </blockquote>



- **大規模データ処理フレームワークのストリーミング機能を利用した機械学習処理の評価**  <span onmouseover="document.getElementById('diem17ichinose').style.display = 'block'"  onmouseout="document.getElementById('diem17ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *第9回データ工学と情報マネジメントに関するフォーラム  (DEIM 2017)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="diem17ichinose"> 近年各種センサの普及やクラウドコンピューティング技術の習熟に伴い，お年寄りや子供のための安全サー ビスなどを目的としたライフログの利用が普及してきている.しかし，動画像解析のようなデータ量，計算量の多い 処理をクラウドでリアルタイムに行うことは困難である.また，近年ディープラーニング技術の発達で，その高い精 度から画像や音声の認識などに広く用いられているが，計算負荷が高いことが問題の一つとなっている. 本研究では，大規模データ処理のための高速かつ汎用性の高いエンジン Apache Spark のストリーミング機能を利用 して，ディープラーニングフレームワークの一つである Chainer の機械学習処理を行い，動画像データ解析処理の高 速化を図る.本稿ではクライアント側，クラウド側として 2 つの端末間で Apache Kafka を用いてストリーミング処 理を行い，クラウド側で機械学習の識別処理を行った.2 つの端末間のネットワーク帯域を変化させ，1 秒あたりに識 別処理を行える画像数を計測し，性能を調査した.実験から，低帯域環境においてリアルタイムに識別を行うことが 可能であることが示された.</div> </blockquote>



- **ネットワーク検索エンジン及びディープニューラルネットワークの高速化**  <span onmouseover="document.getElementById('ieice17nakahara').style.display = 'block'"  onmouseout="document.getElementById('ieice17nakahara').style.display = 'none'">[abst]</span>   
中原啓貴, 井上一成, 中田秀基
, *電子情報通信学会誌 vol.100 No.2*   , pp. 87-91  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice17nakahara"> FPGA の応用分野としてネットワーク向けパケット検索エンジンやディープニューラルネットワークが挙げられる. どちらも用途に応じて仕様の変更が頻繁に生じ,かつ短期間開発が求められているため,専用 LSI を起こすことはコス トの面で問題がある.また,汎用 CPU では遅く,GPU では消費電力が問題となる.したがって,コスト・性能・消費電 力のバランスという点で FPGA が有利である.本稿では,それぞれの応用における研究動向を紹介する. キーワード:パケット分類,ディープニューラルネットワーク,FPGA,低消費電力</div> </blockquote>



- **大規模制限付きベイジアンネットワークを用いた文脈に依存したロバストな文字認識に向けて**  <span onmouseover="document.getElementById('nc1701nakada').style.display = 'block'"  onmouseout="document.getElementById('nc1701nakada').style.display = 'none'">[abst]</span>   
中田秀基, 一杉裕志
, *信学技報 NC vol 116 No.424*   , pp. 65-70  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="nc1701nakada"> われわれは制限付きベイジアンネットワークを用いた大脳皮質モデルBESOMを開発している。BESOMはベイジアンネットワークを用いているため、抽象度の低い情報からの情報抽出と、抽象度の高い事前知識を自然な形で組み合わせた推論が可能である。このようなタスクの一例として本稿では、コンテクスト情報を用いたロバストなテキスト認識タスクについて報告する。BESOMを用いた文字認識タスクでは、単語情報、単語n-gram情報を自然な形で与える事ができ、その結果ノイズを大きく加えた画像においても文字認識精度を大きく向上させることができた。一方計算コストにおいては、文字数、単語数に線形な範囲であることを確認した。</div> </blockquote>



- **Spark MLlibの利用を可能にするSpark SQLの拡張**  <span onmouseover="document.getElementById('de16nakada').style.display = 'block'"  onmouseout="document.getElementById('de16nakada').style.display = 'none'">[abst]</span>   
中田秀基, 小川宏高
, *信学技報 DE Vol.116 No.340*   , pp. 51-56  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="de16nakada"> 大規模データ処理のデファクトスタンダードであるApache Sparkには、機械学習ライブラリMLlibとSQLインターフェイスが用意されている。しかし、これらを組み合わせて利用する方法は限定的である。われわれは、Spark SQLを拡張しOPERATIONAL JOINと呼ぶ操作を導入し、MLlibによる学習結果をテーブルから参照できるようにすることで、Spark SQLからSpark MLlibを呼び出すことを可能にした。提案手法を既存の方法と比較した結果、速度向上を確認することができた。</div> </blockquote>



- **パラメータサーバを用いた並列機械学習システムにおける耐故障性のシミュレーション** [[Paper](dataDir/swopp16rei.pdf)] [[Slides](dataDir/swopp16rei-slides.pdf)]  <span onmouseover="document.getElementById('swopp16rei').style.display = 'block'"  onmouseout="document.getElementById('swopp16rei').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 中田 秀基
, *信学技報, vol.116, no.177*   , pp. 125-130  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp16rei"> 機械学習システムを高速化させるためには、並列化は必要である。並列化には2つの方法があるが、本稿ではパラメータサーバと計算サーバからなる大規模な計算システム、いわゆるモデル並列を扱う。一般に大規模な計算システムに於いては耐故障性が問題になるが、並列機械学習システムにおける耐故障性の議論は進んでいない。本稿ではパラメータサーバを用いた並列機械学習システムにおける耐故障性に関して議論し、また、シミュレーションを用いて検証を行う。</div> </blockquote>



- **Spark RDDの入出力性能の高速化に関する検討** [[Paper](dataDir/swopp16chou.pdf)] [[Slides](dataDir/swopp16chou-slides.pdf)]  <span onmouseover="document.getElementById('swopp16chou').style.display = 'block'"  onmouseout="document.getElementById('swopp16chou').style.display = 'none'">[abst]</span>   
張 凱輝, 谷村 勇輔, 中田 秀基, 小川 宏高
, *信学技報, vol.116, no.177*   , pp. 77-82  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp16chou"> Sparkの中間データである RDD のストレージシステムへの入出力性能をプロファイラーなどを用いて評価して、ボトルネックを特定し、高速化を検討した結果について報告する。</div> </blockquote>



- **ディープラーニングフレームワークCaffeの分散処理の評価**  <span onmouseover="document.getElementById('dicomo16ichinose').style.display = 'block'"  onmouseout="document.getElementById('dicomo16ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2016)シンポジウム*    , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo16ichinose"> 近年各種センサの普及とクラウドコンピューティング技術の習熟により,ライフログの取得やその データの蓄積が容易になった.その結果監視カメラなどのセンサを用いたライフログデータをクラウドで 収集して解析するアプリケーションも普及してきている.ここで,センサデータをそのまま送信してクラ ウドで処理する場合,プライバシや各種センサとクラウド間のネットワーク帯域の問題が生じてしまう. 本研究では,クラウドへ送るデータのデータ量の削減とプライバシの保護を目的とし,フレームワーク Caffe の機械学習処理をセンサ側とクラウド側でパイプライン的に分散処理を行う.その評価として,分 割箇所やパラメータを変化させ処理時間を比較する.本稿では ImageNet を用いて実験を行い,大規模な データセットにおいても分散処理を行うことで生データをクラウドに送ることなく遜色ない学習が可能で あり,また低帯域環境ではより高速に処理できることを示す.</div> </blockquote>



- **ディープラーニングフレームワークCaffeの分散処理に向けた一検討**  <span onmouseover="document.getElementById('zen16ichinose').style.display = 'block'"  onmouseout="document.getElementById('zen16ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *第78回情報処理学会全国大会4P-05*   , pp. 1-2  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen16ichinose"> 我々は，データ量の削減とプライバシの保護を目的として，ディープラーニングフレームワークCaffeをセンサーとクラウドで分散して実行することを目指している．本研究では，センサ・クラウド間で分散実行した場合の送受信データ量と識別率の相関を調査した．</div> </blockquote>



- **Apache Stormを用いたリアルタイムストリームデータ解析フレームワークにおけるセンサ・クラウド間負荷分散の性能評価**  <span onmouseover="document.getElementById('zen16kurosaki').style.display = 'block'"  onmouseout="document.getElementById('zen16kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第78回全国大会論文集4T-07*   , pp. 1-2  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen16kurosaki"> 我々は，動画像解析における前処理をセンサ側とクラウド側で負荷分散させる動画像解析フレームワークをApache Stormで開発している．本研究では，提案フレームワークの性能評価を行い，スレッドのポーリング間隔を調整することで性能向上することを示した</div> </blockquote>



- **Apache Stormを用いたリアルタイム動画像データ解析フレームワークの性能解析**  <span onmouseover="document.getElementById('DEIM16kurosaki').style.display = 'block'"  onmouseout="document.getElementById('DEIM16kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *DEIM予稿集 G8-2*   , pp. 1-5  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="DEIM16kurosaki"> カメラやセンサ等が手軽に利用できるようになり，一般家庭やオフィスビルでもデータを取得して，防犯対策，お年寄りや子供のための安全サービスを目的とした動画像解析アプリケーションが数多く開発されている．それらのアプリケーションは一般的にクラウドで全ての処理が行われている．しかし，動画像を含む多数のセンサデータをクラウドに送信して画像の特徴抽出等の前処理から解析まで，全ての工程をクラウド側で行うと，各センサとクラウド間のネットワーク帯域やクラウド側の資源の制限により，リアルタイムに処理できない可能性がある．我々は，動画像解析処理全体の高速化を目的として，負荷分散機能をもつ分散型リアルタイム計算基盤であるApache Stormを導入し，前処理をセンサ側とクラウド側で負荷分散させた．本研究では，提案フレームワークの性能について，より詳しく解析する．解析結果より，処理スレッド数が多い環境において，スレッドのポーリング間隔を調整することで，性能が向上することがわかった．</div> </blockquote>



- **ディープラーニングフレームワークCaffeの分散環境への適用**  <span onmouseover="document.getElementById('DEIM16ichinose').style.display = 'block'"  onmouseout="document.getElementById('DEIM16ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *DEIM2016予稿集 D1-3*   , pp. 1-5  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="DEIM16ichinose"> 近年インターネット上の情報量の増大やクラウドコンピューティングの普及により，ライフログの取得やそのデータの蓄積が容易になった．その結果監視カメラなどのセンサを用いたライフログの利用も普及してきている．ここで，一般家庭にサーバやストレージを設置して解析までの処理を行うことは困難であるが，映像のようなセンサデータをそのまま送信してクラウドで処理する場合，プライバシや各種センサとクラウド間のネットワーク帯域の問題が生じてしまう．本研究では，クラウドへ送るデータのデータ量の削減とプライバシの保護を目的とし，ディープラーニングのフレームワークであるCaffeを分散環境へ適用させることを考える．本稿ではディープラーニング処理シーケンスを分割してクライアント側とクラウド側でパイプライン的に分散処理を行い，分割箇所やパラメータを変化させ処理時間を比較した．</div> </blockquote>



- **大脳皮質モデルBESOMのGPGPUによる並列化** [[Paper](dataDir/cpsy1601nakada.pdf)]  <span onmouseover="document.getElementById('cpsy1601nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1601nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 井上辰彦, 一杉 裕志
, *信学技報, vol. 115, no. 398, VLDI*   , pp. 31-36  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1601nakada"> 大脳皮質モデルBESOM は、最新の神経科学的な知見に基づき、大脳皮質をベイジアンネットによってモデル化したものである。BESOM における学習、認識には確率伝搬法の反復計算が必要なため計算量が大きく、並列化による実行速度向上が必須である。一般に機械学習機の並列化手法としてはモデル間並列とモデル内並列が考えられるが、本稿ではモデル内並列化をGPGPUで実現した技法について報告する。データ構造の見直しによるGPGPUによるモデル内並列化と、ミニバッチ学習化による並列化を併用することで約50倍の速度向上を得た。</div> </blockquote>



- **大脳皮質モデルBESOMのクラスタ分散化とGPGPU並列化** [[Paper](dataDir/ibis15nakada-poster.pdf)]  <span onmouseover="document.getElementById('ibis15nakada-poster').style.display = 'block'"  onmouseout="document.getElementById('ibis15nakada-poster').style.display = 'none'">[abst]</span>   
中田 秀基, 黎 明曦, 井上辰彦, 一杉 裕志
, *第18回情報論的学習理論ワークショップ (IBIS2015) ポスター*    , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ibis15nakada-poster"> 大脳皮質をベイジアンネットで模したモデルBESOMは、ニューラルネットワークと比較すると計算が複雑であり、並列化が一般に困難である。本発表では、モデル単位で複製し計算機クラスタに分散して実装する手法と、GPGPUによるモデル内部の並列化について述べる。</div> </blockquote>



- **リアルタイム動画像解析アプリケーションフレームワークにおけるセンサ・クラウド間負荷分散の性能評価**  <span onmouseover="document.getElementById('de15kurosaki').style.display = 'block'"  onmouseout="document.getElementById('de15kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *信学技報, vol. 115, no. 230*   , pp. 23-28  , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="de15kurosaki"> 一般家庭やオフィスビルでカメラや各種センサの情報を取得してクラウドに転送し、解析処理を行うライフログ解析アプリケーションが数多く開発されている．しかし，センサとクラウド間のネットワーク帯域やクラウド側の資源の制限により，動画像解析のようなデータ量、計算量の多い処理をクラウドでリアルタイムに行うことは困難である．我々は，センサ・クラウド間で分散処理を行う動画像解析アプリケーションフレームワークを提案しているが，センサからクラウドまでの実行環境を考慮しつつ，特徴量抽出等の前処理から解析までの各処理に対して適切な並列度を設定する必要がある．本研究では，センサとクラウドを模擬したクラスタ環境を構築し，動画像解析アプリケーションの性能を調査する．実験から，処理スレッド数を増やすと処理性能が向上すること，センサ・クラウド間が低帯域の場合はセンサ・クラウド間の分散処理が有効であることが示された．</div> </blockquote>



- **マスタ・ワーカ型パラメータサーバの実装とBESOM への適用** [[Paper](dataDir/swopp15rei.pdf)]  <span onmouseover="document.getElementById('swopp15rei').style.display = 'block'"  onmouseout="document.getElementById('swopp15rei').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 一杉 裕志, 中田 秀基
, *信学技報, vol. 115, no. 174, CPSY2015-33*   , pp. 179-184  , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp15rei"> 大脳皮質の計算論的モデルとして\BESOM を提案している。BESOM は最新の神経科学的な知見に基づいてベイジアンネットで大脳皮質をモデル化したもので、人間の脳の比較的忠実なモデルとなっていることから、科学的に興味深いだけではなく、工学的にも広い応用が期待できる。その一方、BESOM における学習には、近年注目を集めているニューラルネットによるディープラーニングよりもさらに計算量が大きいことから、並列化による実行速度向上が要請される。本稿では、汎用のマスタ・ワーカ型タスク実行フレームワークを用いて、学習パラメータを交換するパラメータサーバを構築し、複数の\BESOM モデルが協調して並列に学習する環境を実現した。これに、計算機内でのスレッド並列を組み合わせることで、16台4スレッドを用いた場合で、最大40倍程度の高速化が可能であること、また、高速化の度合いは並列実行時のバッチサイズに依存することを確認した。</div> </blockquote>



- **ファットクライアント型リアルタイム動画像解析アプリケーションフレームワークの提案**  <span onmouseover="document.getElementById('dicomo15kurosaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo15kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2015)シンポジウム*   , pp. 1019 - 1023  , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo15kurosaki"> 一般家庭でカメラやセンサ等によりライフログを取得して， 防犯対策やセキュリティ，お年寄りや子供のための安全サービスを目的としたライフログ解析アプリケーションが数多く開発されている． それらのアプリケーションを一般家庭で採用する場合，サーバやストレージを設置して解析までを行うことは難しいため，クラウドでの処理が必要となる． しかし，センサとクラウド間のネットワーク帯域やクラウド側の資源の制限により，クラウドに動画像を含む多数のセンサデータを送信し， 特徴量抽出等の前処理から解析までの全ての工程をクラウド側でリアルタイムに行うことは困難である． 我々は，ファットクライアントの概念を取り入れ，センサ側で画像から特徴量抽出し， 前処理済みの小さいデータをクラウドに収集して解析する動画像データ解析アプリケーションフレームワークを提案しているが， 動画像解析ではセンサ側での前処理により多くの時間がかかってしまうことが明らかになった． 本研究では，前処理をセンサ側とクラウド側で負荷分散させることで，動画像解析処理全体の高速化を図る． 提案するアプリケーションフレームワークはリアルタイム分散処理システムのApache Stormを用いて実装し， 実際に画像データをセンサ側とクラウド側で分散処理した場合の画像1枚あたりの処理時間と一定時間内に処理できるジョブ数を調査した． 実験結果より，処理スレッド数を増やすことによって画像1枚当たりの処理時間は増加するが， 一定経過時間に処理できる総画像数が増加し，ファットクライアントとクラウドを連携させた分散処理の有用性が示された．</div> </blockquote>



- **マルチラック環境におけるHDFSの効率的なレプリカ再配置手法の提案**  <span onmouseover="document.getElementById('zen77higai').style.display = 'block'"  onmouseout="document.getElementById('zen77higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第77回全国大会*    , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen77higai"> 我々はこれまで，分散ファイルシステムの一つであるHadoop Distributed File Systemにおいて，ノード故障時などに発生する，不足レプリカを補うレプリカ再配置処理に着目し評価を行ってきた．２ラックからなるクラスタにおいて，ディスクやネットワーク負荷、耐障害性に着目し，生成元・生成先選択アルゴリズム，転送スケジューリング及び転送ストリーム数を適切に行う制御手法を提案し，その有効性を示している．本稿では，３つ以上のラックからなるクラスタにおけるレプリカ再配置処理を評価する．ラック間転送が行われる際，生成先のラックを複数ラックの中から選択可能になるため，生成元・生成先選択アルゴリズムを拡張し，その拡張した制御手法が有効であるか検討する．</div> </blockquote>



- **ファットクライアントとクラウドを用いたカメラ画像データ解析フレームワークの提案**  <span onmouseover="document.getElementById('zen77kurosaki').style.display = 'block'"  onmouseout="document.getElementById('zen77kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第77回全国大会*    , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen77kurosaki"> 近年ではカメラやセンサ等を手軽に利用できるようになり，一般家庭でもライフログの取得が容易になった．防犯対策やセキュリティ，お年寄りや子供のための安全サービスを目的として，ライフログ解析アプリケーションが数多く開発されてきたが，実際に一般家庭で採用する場合は，サーバやストレージを設置して解析までを行うことは難しいため，クラウドでのライフログ解析が必要となる．
今回は動画像をセンサデータとして実験を行う．動画像データはデータ量が大きく，連続的であるため，Apache Stormを用いて画像の特徴抽出を分散処理させ，前処理済みのデータ量の小さいデータをクラウドに収集して解析するフレームワークを提案、実装する．</div> </blockquote>



- **マルチラック環境におけるHDFSの効率的なレプリカ再配置手法の提案と評価**  <span onmouseover="document.getElementById('deim15higai').style.display = 'block'"  onmouseout="document.getElementById('deim15higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *第7回データ工学と情報マネジメントに関するフォーラム DEIM2015*    , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim15higai"> Hadoop Distributed File System (HDFS) では，ノードが故障するとデータノード間でレプリカ再配置処理を行いデータの可用性を維持する．しかしながら，HDFSのレプリカ再配置では，レプリカ生成元・生成先をランダムに選択するため，データ移動に偏りが生じ非効率な再配置処理が行われている．この問題を解消するために，我々は指向性リング構造に基づいたデータ転送により各ノードの負荷を均衡化するレプリカ生成元・生成先の選出と，可用性とネットワーク負荷を考慮してスケジューリングを行う手法を提案し，2ラックからなるHDFSクラスタにおいて，その特性及び性能が向上することをシミュレーションを用いて示してきた．2ラック時には，ラック間転送の生成先のラックが一意に決定するのに対して，3ラック以上の場合には生成先のラックを任意に選択することができ新たな制御が考えられる．本稿では既提案手法を拡張して，3つ以上のラックからなるHDFSクラスタにおける効率的なレプリカ再配置手法を提案し，シミュレーションで評価する．評価実験より，提案手法により再配置の性能が向上し，最大で再配置の実行時間が20%削減できることを示す</div> </blockquote>



- **ファットクライアントを利用した動画像データ解析アプリケーションフレームワークの提案**  <span onmouseover="document.getElementById('deim15kurosaki').style.display = 'block'"  onmouseout="document.getElementById('deim15kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *第7回データ工学と情報マネジメントに関するフォーラム DEIM2015*    , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim15kurosaki"> カメラやセンサ等が手軽に利用できるようになり，一般家庭でライフログを取得して，防犯対策やセキュ リティ，お年寄りや子供のための安全サービスを目的としたライフログ解析アプリケーションが数多く開発されている．それらのアプリケーションを一般家庭で採用する場合は，サーバやストレージを設置して解析までを行うことは難しいため，クラウドでの処理が必要となる．しかし，動画像を含む多数のセンサデータをクラウドに送信して画像の特徴抽出等の前処理から解析まで，全ての工程をクラウド側で行うと，各センサとクラウド間のネットワーク帯域やクラウド側の資源の制限により，リアルタイムに処理できない可能性がある．また，動画像はデータ量が大きく，連続的であるため，大容量ストリームデータに対する解析処理が必要となる．本研究では，ファットクライアントの概念を取り入れ，クライアント側で画像から特徴抽出し，前処理済みの小さいデータをクラウドに収集して解析する動画像データ解析アプリケーションフレームワークを提案する．また，提案するフレームワークをApache Stormを用いて実装する</div> </blockquote>



- **クラウドのこれまでとこれから**    
中田秀基
, *MMSフォーラム*    , 2014 



- **耐障害性ミドルウェアfalanxへの高可用分散協調スケジューラの実装**  <span onmouseover="document.getElementById('swopp14takefusa').style.display = 'block'"  onmouseout="document.getElementById('swopp14takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 中田 秀基, 池上努, 戸澤貴之, 田中良夫
, *HPC研究会(SWoPP)*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp14takefusa"> 我々は，エクサスケール計算機環境において耐障害性を有した階層型タスク並列アプリケーションプログラムの開発を支援するFalanxミドルウェアを開発している．Falanxは，データストア機構と資源管理機構からなり，アプリケーションプログラムを単一MPIジョブとして実行させるとともに，実行障害発生時には選択的にタスクを再実行／破棄させることができる．しかしながら，Falanxの既存実装では資源管理機構をMPIプロセスの1ランクで処理しているため，耐障害性およびスケーラビリティに課題が残っている．本稿では，Falanxシステムの耐障害性およびスケーラビリティを高めることを目指し，既発表研究で提案した高可用分散協調スケジューラをZooKeeperを用いてFalanxミドルウェアに実装した．予備実験を行った結果，細粒度のタスクを大量に処理する場合には高可用分散協調スケジューラのオーバヘッドが非常に大きくなることが分かり，タスク取得処理の効率化が必要不可欠であることが示された．</div> </blockquote>



- **シミュレーションを用いたHDFSのレプリカ再配置手法の性能評価**  <span onmouseover="document.getElementById('dicomo14higai').style.display = 'block'"  onmouseout="document.getElementById('dicomo14higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *DICOMO2014シンポジウム*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo14higai"> 大規模データに対応した処理システムとして，汎用ハードウェアを用いて高度な集約処理を行う分散ファイルシステムに注目が集まっている．オープンソースのHadoop Distributed File System(HDFS)は広く使用されている分散ファイルシステムの一つである．HDFSは耐障害性を維持するためにデータのレプリカを複数のノードに分散配置し，ノード故障時には不足レプリカを残りのノード間で補うレプリカ再配置処理を行う．我々はこれまで，シングルラックからなる小規模実クラスタ環境において，HDFSではレプリカ再配置時のデータ移動に偏りが発生し非効率な処理が行われていることを明らかにし，この問題を解消するためにリング構造に基づく一方向のデータ転送よって負荷分散を行うレプリカ再配置の制御手法を提案し，その有効性を示してきた．本稿では，シングルラック及びマルチラックで構成したより大規模な環境を想定し，シミュレーションを用いてレプリカ再配置に関する提案手法の有効性を評価する．評価実験より，シングルラック環境ではノード数が増加するにつれて再配置のスループットが向上し，提案手法が有効であることが示された．マルチラック環境では，拡張した制御手法を用いた評価を行った．実験からラック間帯域幅が小さい場合はラック間リンク部分が転送のボトルネックとなり，提案手法の顕著な優位性はみられなかった．一方，ラック間帯域幅が十分大きい場合は，提案手法によりレプリカ再配置のスループットが大幅に改善され，提案手法の有効性が示された．</div> </blockquote>



- **クラウド上でのライフログ解析のためのオンラインフレームワークJubatusを用いたアプリケーション実装**  <span onmouseover="document.getElementById('dicomo14kurosaki').style.display = 'block'"  onmouseout="document.getElementById('dicomo14kurosaki').style.display = 'none'">[abst]</span>   
黒崎裕子, 竹房 あつ子, 中田 秀基, 小口 正人
, *DICOMO2014シンポジウム*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo14kurosaki"> 近年ではカメラやセンサ等を手軽に利用できるようになり，一般家庭でもライフログの取得が容易になった．防犯対策やセキュリティ，お年寄りや子供のための安全サービスを目的として，ライフログ解析アプリケーションが数多く開発されてきたが，実際に一般家庭で採用する場合は，サーバやストレージを設置して解析までを行うことは難しいため，クラウドでのライフログ解析が必要となる．しかしながら，動画のようなセンサデータはデータ量が大きいため，特徴量抽出等の前処理は各センサ側で行い，特徴量のみをクラウド側で収集して解析する手法も考えられる．本研究では，ライフログ解析の前処理をセンサ側で行う場合とクラウド側で行う場合での性能比較を行うことを目的として，評価対象となるオンライン学習アプリケーションを実装した．実装したアプリケーションでは，カメラが動体検知すると前処理として撮影した画像の特徴量抽出をOpenCVを用いて行い，その特徴量をもとにBag-of-Features手法を用いてベクトル化したデータに変換する．そのデータを入力値として，オンライン機械学習フレームワークJubatusを用いて学習し，人の行動の判別を行う．実験から，カメラ画像を前処理したデータを入力値として，Jubatusを用いて行動判別が行えることが確認され，実装したアプリケーションの動作確認ができた．</div> </blockquote>



- **大規模環境におけるHDFSのレプリカ再配置処理のシミュレーションによる評価**  <span onmouseover="document.getElementById('ipsj14shigai').style.display = 'block'"  onmouseout="document.getElementById('ipsj14shigai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *掲載誌名 情報処理学会第76回全国大会講演論文集 1巻*   , pp. 127-128  , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj14shigai"> 分散ファイルシステムHadoop Distributed File Systemでは，ノード故障時に不足レプリカを補うレプリカ再配置処理の際，処理に偏りがあり非効率なデータ転送が行われている．本研究では，指向性リング構造に基づきデータ転送を行うヒューリスティック手法と最適化手法を提案し，提案手法により負荷が分散し効率的なレプリカ再配置処理を行えることを示す．</div> </blockquote>



- **大規模環境におけるHDFSの効率的なレプリカ再配置制御に向けた評価**  <span onmouseover="document.getElementById('deim14higai').style.display = 'block'"  onmouseout="document.getElementById('deim14higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *第6回データ工学と情報マネジメントに関するフォーラム(DEIM2014)，D1-4*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim14higai"> 大規模データに対応した処理システムとして，汎用なハードウェアを用いて高度な集約処理を行う分散ファイルシステムに注目が集まっている．分散ファイルシステムでは従来よりも大規模なシステムが構成されるようになり，複数のレプリカを分散配置することで可用性や耐故障性を維持している．ノードが故障すると，そのノードが管理していたレプリカが一時的に不足し，そのデータを保持している他のノードへのアクセス負荷が増加してシステム全体の性能が低下するため，不足レプリカの再配置の高速化が重要である．しかしながら，一般に広く利用されているHadoop Distributed File System(HDFS)のレプリカ再配置では，データ移動に偏りが生じており，効率良く処理されていない．この問題を解消するために，我々はリング構造に基づく一方向のデータ転送を行い負荷分散を行う制御手法を提案した．本稿では，この制御手法を0-1整数計画問題として定式化した最適化手法を提案し，7台からなる実クラスタを用いた小規模環境での評価とシミュレーションによる大規模環境での評価を行った．評価実験より，いずれの環境においても提案手法が有効であり，小規模実環境ではスループットが最大で45%向上することを確認した．</div> </blockquote>



- **Hadoop CassandraとCassandraを用いた並列分散処理機構の性能比較**  <span onmouseover="document.getElementById('deim14hishinuma').style.display = 'block'"  onmouseout="document.getElementById('deim14hishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *第6回データ工学と情報マネジメントに関するフォーラム(DEIM2014)，D1-4*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim14hishinuma"> クラウドコンピューティングの発展に伴い，大量に生成されるデータを蓄積し，高速に処理することが求められている．このような処理は従来のRDBMSでは難しいことから，大量に生成されるデータの蓄積には分散KVSが，高速な処理にはMapReduce処理系と分散ファイルシステムが用いられている．しかし，蓄積した大容量データを処理するためには分散KVSから分散ファイルシステムにデータを転送しなければならず，そのコストが問題となる．Apache Cassandraには，Apache Hadoop連携機能がある．この連携機能を使用すると転送コストの発生を防ぐことが予想されるが，その性能は明らかでない．我々は，既発表研究において，データを蓄積した分散KVS上で直接高速データ処理を行う手法を提案し，分散KVSのApache Cassandraを拡張した並列データ処理機構を実装した．本稿では，Hadoop Cassandraと本実装との比較を行い，これらの特性を明らかにする．比較実験より並列データ処理機構では，データサイズによらず高速に処理することができ，本提案手法の有効性が示された．</div> </blockquote>



- **インタークラウド仮想インフラ構築システムIrisのプロトタイプシステムの開発**  <span onmouseover="document.getElementById('service14takefusa').style.display = 'block'"  onmouseout="document.getElementById('service14takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 高野 了成, 中田 秀基, 柳田誠也, 工藤 知宏 
, *信学技報 SC2013-21 (2014-03)*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="service14takefusa"> クラウドOSソフトウェアの普及により，IaaSクラウドの構築が容易に行えるようになってきた．しかしながら，IaaSサービスの需要は大きく変動するため，設備投資や運用コストを削減するにはクラウド間で資源を融通する必要がある．インタークラウドを実現する手法として，我々はIaaS事業者が別の拠点の物理資源を借りてIaaS環境を拡張することを可能にするHaaSモデルを提案している．本稿では，HaaSを提供するインタークラウド仮想インフラ構築システムIrisのプロトタイプシステムの開発を行った．プロトタイプシステムでは，HaaSの簡素なRESTインタフェースを定義し，RESTインタフェースからHaaSテナントの構築，状態取得，破棄が行えるようにし，Nested KVMとOpen vSwitchとGREトンネルを用いたオーバレイ型ネットワーク仮想化を実現した．本プロトタイプシステムを用いることにより，既存クラウドOSよりHaaSテナントの構築・破棄が高速にできることを確認した．</div> </blockquote>



- **NSIコネクションサービスプロトコルver. 2の参照実装の開発**  <span onmouseover="document.getElementById('ns14takefusa').style.display = 'block'"  onmouseout="document.getElementById('ns14takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 工藤 知宏 , 高野 了成, 中田 秀基, 大久保克彦, 岡崎史裕
, *信学技報 NS2013-202 (2014-3)*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns14takefusa"> 研究・教育ネットワークでは，異なる管理ドメインが提供する複数ネットワークを跨ったパスを動的に構築・提供する試みが複数行われており，実運用サービスが開始されようとしている．OGFのNSIワーキンググループでは，そのためのインタフェースとしてConnection Service (CS)プロトコルの標準化を進めている．CSプロトコルの検証には，ネットワークサービスのプロバイダ，アグリゲータ，リクエスタ用のソフトウェアやモニタリングツールが必要となる．本研究では，GridARSフレームワークとしてCS v. 2.0プロトコルに準拠したこれらのソフトウェアモジュール群を開発した．我々は，CS v. 2.0プロトコルの相互運用実験に開発したモジュール群を提供し，国際的な実証実験に貢献した．また，本フレームワークはオープンソースとして公開されており，本フレームワークを用いたアプリケーション，プロバイダ，モニタリングツールが第三者により開発されていることを示す．</div> </blockquote>



- **伸縮自在なデータセンターを実現するインタークラウド資源管理システム**  <span onmouseover="document.getElementById('it14takano').style.display = 'block'"  onmouseout="document.getElementById('it14takano').style.display = 'none'">[abst]</span>   
高野 了成, 竹房 あつ子, 中田 秀基, 柳田誠也, 工藤 知宏 
, *インターネット技術第163委員会第34回研究会*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="it14takano"> 我々はデータセンター（IaaS）事業者からの要求に対して、ネットワーク越しに資源を提供するHaaSサービスモデルを提案している。本モデルに基づいて実装したシステムIrisを用いて、Apache CloudStackに変更を加えることなく、要求に応じた計算資源提供が可能であることを紹介する。また、その応用として、日欧のネットワークテストベッドを活用した実証的共同研究の取り組みについても紹介する。</div> </blockquote>



- **FELIX大規模情報通信基盤を活用した日欧実証実験に向けて**  <span onmouseover="document.getElementById('ag13takefusa').style.display = 'block'"  onmouseout="document.getElementById('ag13takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 工藤 知宏 , 高野 了成, 中田 秀基
, *アカデミッククラウドシンポジウム2013*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ag13takefusa"> 日欧のネットワークテストベッドを利用した日欧実証実験を目的としたFELIXプロジェクトについて紹介するとともに、その実現に向けた産総研の取り組みについて紹介する。</div> </blockquote>



- **パーシステントストレージを利用した高可用分散協調スケジューラの実装**  <span onmouseover="document.getElementById('swopp13takefusa').style.display = 'block'"  onmouseout="document.getElementById('swopp13takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 中田 秀基, 池上 努, 田中 良夫 
, *研究報告ハイパフォーマンスコンピューティング 2013-HPC-140*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp13takefusa"> 階層型タスク並列処理は，タスクの再実行や冗長実行により耐障害性を備えたプログラムが設計できるため，ポストペタスケール高性能計算における有望なプログラミングモデルの 1 つと考えられている．我々は，耐障害性を備えたアプリケーションプログラムの開発を支援にする耐障害アプリケーションフレームワーク Falanx を提案している．このようなアプリケーションフレームワークは，計算に必要となるデータを障害から保全するデータストア機構と計算ノードの健全性を監視しつつ適切に計算を実行する資源管理機構からなる．これらを，ポストペタスケール計算機環境においてスケーラブルでかつ，それら自身が耐故障性を持つように設計・実装する必要がある．本研究では，耐障害アプリケーションフレームワークのポストペタスケール計算機環境での性能特性を検証して技術的課題を明らかにすることを目的とし，試験実装となるパーシステントストレージを利用した高可用分散協調スケジューラを設計・開発する．本スケジューラは既に実装を進めている資源管理機構と新たに追加したデータストア機構で構成され，Apache ZooKeeper と Apache Cassandra を用いて実装することで耐障害性を実現する．本スケジューラを用いた予備実験から，処理中に計算ノードが落ちてしまった場合も，自動的にタスクが再実行されアプリケーションプログラムが継続実行できることを確認した．</div> </blockquote>



- **ポストペタスケール高性能計算のためのオンメモリストレージの設計**  <span onmouseover="document.getElementById('swopp13nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp13nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 池上 努, 竹房 あつ子, 高野 了成, 田中 良夫 
, *研究報告ハイパフォーマンスコンピューティング 2013-HPC-140*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp13nakada"> ポストペタスケールの計算機ではノード数が極端に大きくなることから、ユーザに対して故障を完全に隠蔽する Fault Tolerance は現実的ではなく、ユーザプログラムに故障を提示し対処を委譲する Fault Resilience を持つ計算機構が必要となる。しかし故障への対処は非常に複雑な処理であり、適切な抽象界面を設定することでユーザへの負荷が過大にならないよう工夫する必要がある。われわれは、問題を多数の副問題に分割し、副問題単位での Fault Resilience ポリシを設定することが可能な計算機構 Falanx を提案している。本稿では Falanx の主要構成要素の一つであるオンメモリストレージの設計について述べる。提案オンメモリストレージはハッシュによってノード間分散を行なうキーバリューストレージで、レプリケーションによる耐故障性を持つ。このストレージのプロトタイプを既存のキーバリューストレージである Kyoto Cabinet と ULFM (User Level Fault Mitigation) 機能を持つ MPI 実装をを用いて実装し、仮想環境において予備的評価を行った。その結果、書き出しスループットはプライマリ Ack 時で 140MByte/s 程度、読み込みスループットは最大 120MByte/s 程度であること、単体ノードの障害に対して頑健であることを確認した。</div> </blockquote>



- **異種クラスタを跨がる仮想マシンマイグレーション機構**  <span onmouseover="document.getElementById('swopp13takano').style.display = 'block'"  onmouseout="document.getElementById('swopp13takano').style.display = 'none'">[abst]</span>   
高野 了成, 中田 秀基, 広渕 崇宏, 田中 良夫, 工藤 知宏 
, *研究報告システムソフトウェアとオペレーティング・システム（OS）2013-OS-126*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp13takano"> 災害復旧 (DR) や事業継続計画 (BCP) の観点から、クラウド間を跨がった仮想計算機マイグレーションの重要性が高まっている。しかし、ヘテロなクラウド環境におけるマイグレーション技術に関して、今まで十分に議論されていない。本論文では、プライベートクラウドとパブリッククラウドなど、通信デバイスが異なるヘテロなクラウド環境間で仮想クラスタをマイグレーションする際の問題点を明らかにし、解決策を提案する。本提案の特長は、仮想クラスタを構成するノード VM に対して、実行環境の変化に応じて、最良の通信性能を達成する通信デバイスをアプリケーションから透過的に選択し、利用できることである。インターコネクト透過型マイグレーションである Ninja migration、OpenFlow を用いたエッジオーバレイネットワーク、ストレージマイグレーションなどの要素技術から成るプロトタイプシステムを実装した。このシステムを用いて、産総研の Infiniband クラスタと商用パブリッククラウド間で仮想クラスタをマイグレーションできることを確認した。</div> </blockquote>



- **Cassandraによるデータアフィニティを考慮した並列分散処理の実装**  <span onmouseover="document.getElementById('dicomo13hishinuma').style.display = 'block'"  onmouseout="document.getElementById('dicomo13hishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2013)シンポジウム*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo13hishinuma"> クラウドコンピューティングの発展に伴い，大量に生成されるデータを蓄積し，高速に処理することが求められている．このような処理は従来のRDBMSでは難しいことから，大量に生成されるデータの蓄積には分散KVSが，高速な処理にはHDFSなどの分散ファイルシステムが用いられている．しかし，蓄積した大容量データを処理するためには分散KVSから分散ファイルシステムにデータを転送しなければならず，そのコストが問題となる．この問題の解決に向けて，データを蓄積した分散KVS上で直接高速データ処理を行う手法を提案し，実装する．我々は既発表研究において大容量データを扱う分散KVSであるApache Cassandraを拡張し，データアフィニティを考慮した並列データ処理機構を組み込んでいる．本稿では，並列データ処理機構の特性を明らかにするため，データの蓄積を行いつつ，高速データ処理を行った場合の性能と，処理の偏りと性能の相関を調査した．評価より，本実装はWrite中の影響を受けることが確認でき，影響を少なくするためには処理の偏りを小さくし，処理を担当しないノードの発生を防ぐことがより重要であることが分かった．</div> </blockquote>



- **Hadoopのノード削除時のレプリカ生成の高速化手法の提案**  <span onmouseover="document.getElementById('dicomo13higai').style.display = 'block'"  onmouseout="document.getElementById('dicomo13higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2013)シンポジウム*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo13higai"> 大規模データに対応した処理システムとして，汎用なハードウェアを用いて高度な集約処理を行う分散ファイルシステムに注目が集まっている．本研究では，Apache Hadoopの基盤技術であるHadoop Distributed File System (HDFS)に着目した．Hadoopはスケールアウトするシステムであり，システム規模に応じた運用や故障の発生などにより，ノードを脱退および削除することが想定される．HDFSでは通常複数のDataNode上に複数のレプリカを保持し，ノード脱退時および削除時には他のノードにレプリカを自動的に生成する．この過程が長くなると一部のDataNodeに負荷が掛かりスループットが低下してしまうため，その高速化が重要である．本稿では，ノード削除時に注目して不足分を補うレプリカ生成処理を高速化する制御手法を提案する．予備調査から，レプリカ生成時のデータ移動には偏りが生じ，効率の良い処理が行われていないことが分かった．そこでレプリカ生成先および生成元を制御することでその偏りを解消し，処理を高速化する制御手法を提案する．制御手法により偏りが解消され，スループットが最大59\%向上することを示す．</div> </blockquote>



- **多数の動画像を対象とするリアルタイム異常値検出の検討**  <span onmouseover="document.getElementById('hpc1305ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1305ogawa').style.display = 'none'">[abst]</span>   
小川 宏高, 中田 秀基, 工藤 知宏
, *研究報告ハイパフォーマンスコンピューティング 2013-HPC-139*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1305ogawa"> 我々は，オンライン機械学習向け分散処理フレームワーク Jubatus を基盤として用いた，大量センサデータに対するリアルタイムかつ複雑な解析を実現する処理エンジンの構築を目指している．特にさまざまな応用分野へのシステムの適用を想定した場合，多種多様なリアルタイムデータを処理対象として取り扱えることが重要である．そのなかでも映像や音声に代表されるメディアデータは，汎用性が高く，実世界へのセンサー装置の浸透が顕著に進んでおり，内包している情報量の多さから高い利用価値が期待される．本稿では，Jubatus を基盤として実際に多数の動画像を対象としたリアルタイム異常値検出を行うシステムを構築し，その構成概要を示した．また，性能特性の調査を行い，その結果を示した．その結果，学習データに基づいた異常値検知はリアルタイムに実現できたが，学習フェーズは学習データの増加とともにリアルタイムに処理することが困難になった．レスポンス時間についてより詳細な調査を行い，LSH から取得した擬似近傍点の個数が多い場合に著しい性能劣化が見られることが判明した．</div> </blockquote>



- **Hadoop のノード脱退時および削除時のレプリカ生成の高速化**  <span onmouseover="document.getElementById('sacsis13higai').style.display = 'block'"  onmouseout="document.getElementById('sacsis13higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *SACSIS2013 - 先進的計算基盤システムシンポジウム(萌芽論文)*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis13higai"> 大規模データに対応した処理システムとして，汎用的なハードウェアを用いて高度な集約処理を行う分散ファイルシステムに注目が集まっている．本研究では，Apache Hadoopの基盤技術であるHadoop Distributed File System(HDFS)に着目した．Hadoopはスケールアウトするシステムであり，システム規模に応じた運用や故障の発生などにより，ノードの脱退もしくは削除が想定される．HDFSでは通常複数のDataNode上に複数のレプリカを保持し，ノード脱退時および削除時には他のノードにレプリカを自動的に生成する.
この過程が長くなると一部のDataNodeに負荷がかかり性能が低下してしまうため，その高速化が重要である．本稿では,ノード削除時に注目して，不足分を補うレプリカ生成処理に関するスループットを評価する．予備実験からレプリカ生成時のデータ移動には偏りが生じ，効率の良い処理が行われていないことが分かった．そこでレプリカ生成先を制御することでその偏りを解消し，処理の高速化を目指す制御手法を提案する．制御手法によりスループットが最大で18%向上すること，およびデータ移動の偏りが若干解消することを示す．</div> </blockquote>



- **データアフィニティを考慮したCassandraによる並列分散処理の実装と評価**  <span onmouseover="document.getElementById('sacsis13hishinuma').style.display = 'block'"  onmouseout="document.getElementById('sacsis13hishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *SACSIS2013 - 先進的計算基盤システムシンポジウム(萌芽論文)*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis13hishinuma"> クラウドコンピューティングの発展に伴い，大量に生成されるデータを蓄積し，高速に処理することが求められている．このような処理は従来のRDBMSでは難しいことから，大量に生成されるデータの蓄積には分散KVSが，高速な処理にはHDFSなどの分散ファイルシステムが用いられている．しかし，蓄積した大容量データを処理するためには分散KVSから分散ファイルシステムにデータを転送しなければならず，そのコストが問題となる．我々はこの問題に着目し，問題解決に向けて，データを蓄積した分散KVS上で直接高速データ処理を行う手法を提案し，実装する．本稿では，大容量データを扱う分散KVSであるApache Cassandraを拡張し，データアフィニティを考慮した並列データ処理機構を組み込んだ．評価結果から，本提案手法はCassnadraを通常使用した際よりも処理が高速に行えることが示された．</div> </blockquote>



- **多数の動画像を対象とするリアルタイム異常値検出にむけて**  <span onmouseover="document.getElementById('sacsis13ogawa-poster').style.display = 'block'"  onmouseout="document.getElementById('sacsis13ogawa-poster').style.display = 'none'">[abst]</span>   
小川 宏高, 中田 秀基, 工藤 知宏
, *SACSIS2013 - 先進的計算基盤システムシンポジウム(poster)*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis13ogawa-poster"> 我々は，オンライン機械学習向け分散処理フレームワークJubatusを基盤として用いた，大量センサデータに対するリアルタイムかつ複雑な解析を実現する処理エンジンの構築を目指している．特にさまざまな応用分野へのシステムの適用を想定した場合，多種多様なリアルタイムデータを処理対象として取り扱えることが重要である．そのなかでも映像や音声に代表されるメディアデータは，汎用性が高く，実世界へのセンサー装置の浸透が顕著に進んでおり，内包している情報量の多さから高い利用価値が期待される．本稿では，Jubatusを基盤として実際に多数の動画像を対象としたリアルタイム異常値検出を行うシステムを構築し，その構成概要を示した．また，性能特性の調査を行い，その結果を示した．その結果，学習データに基づいた異常値検知はリアルタイムに実現できたが，学習フェーズは学習データの増加とともにリアルタイムに処理することが困難になった．レスポンス時間についてより詳細な調査を行い，LSHから取得した擬似近傍点の個数が多い場合に著しい性能劣化が見られることが判明した．</div> </blockquote>



- **Cassandraを用いた並列分散処理機構の開発とHadoop Cassandraとの比較**  <span onmouseover="document.getElementById('ipsj14shishinuma').style.display = 'block'"  onmouseout="document.getElementById('ipsj14shishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *掲載誌名 情報処理学会第76回全国大会講演論文集 3巻*   , pp. 421-422  , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj14shishinuma"> 大容量データをリアルタイムの高速処理するため、Apache Cassandraを拡張した並列分散処理機構を開発している。本研究では、提案手法とHadoop Cassandraとの比較を行い、提案手法の有効性を示す。</div> </blockquote>



- **Hadoop のノード脱退時、ノード削除時のレプリカ生成挙動に関する
評価**    
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第75回全国大会*    , 2013 



- **Cassandraによる局所性を考慮した分散並列処理機能の拡張と評価**    
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会第75回全国大会*    , 2013 



- **Hadoopのノード脱退時および削除時のレプリカ生成に関する一考察**  <span onmouseover="document.getElementById('deim13higai').style.display = 'block'"  onmouseout="document.getElementById('deim13higai').style.display = 'none'">[abst]</span>   
日開 朝美, 竹房 あつ子, 中田 秀基, 小口 正人
, *第5回データ工学と情報マネジメントに関するフォーラム*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim13higai"> 大規模データに対応した処理システムとして，汎用的なハードウェアを用いて高度な集約処理を行う分散大規模データに対応した処理システムとして，汎用的なハードウェアを用いて高度な集約処理を行う分散ファイルシステムに注目が集まっている．本研究では，Apache Hadoop の基盤技術である Hadoop Distributed FileSystem(HDFS) に着目した．Hadoop はスケールアウトするシステムであり，システム規模に応じた運用や故障の発生などにより，ノードを脱退もしくは削除することが想定される．HDFS は通常複数の DataNode 上に複数のレプリカを保持し，ノード脱退時および削除時にはレプリカを自動的に生成する．この過程が長くなると一部の DataNodeに負荷がかかり性能が低下してしまうため，その高速化が重要である．本稿では，ノード脱退時および削除時の不足分を補うレプリカ生成処理に関するスループットを評価する．また，レプリカ生成を高速化するために，レプリカ生成先を制御する手法を提案する．制御手法により約 10MB/sec 程スループットが向上したこと，およびレプリカ生成処理が若干効率化したことを示す．</div> </blockquote>



- **Cassandraによるデータアフィニティを考慮した分散並列処理の提案と実装**  <span onmouseover="document.getElementById('deim13hishinuma').style.display = 'block'"  onmouseout="document.getElementById('deim13hishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *第5回データ工学と情報マネジメントに関するフォーラム*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim13hishinuma"> クラウド技術の普及により，個人が生み出す情報が大量にネットワーク上に保存されるようになり，大量のデータを高速に処理することが必要となっている．そこで，分散環境で一貫性の制限を緩和して処理性能を重視する分散KVS (Key Value Store) と呼ばれる NoSQL型データベース管理システムが注目され始めた．分散KVSを用いると，RDBMSでは管理が困難な規模の大容量データを分散環境で管理することができる．管理されている大容量データを効率よく活用するためには，対象となるデータに対して複数計算機を利用して並列処理を行う必要がある．しかしながら，分散KVSからデータを取り出した後に再度データを複数計算機に分散させて並列処理を行うと，データの転送オーバヘッドが非常に大きくなってしまう．本研究では分散KVSの実装のひとつであるApache Cassandraに着目し，データアフィニティを考慮して大容量データをより高速に処理するための手法を提案する．本稿では，Cassandra上に分散して保存された異なる値に対し，事前に指定された処理を値が格納されている計算機上で並列に実行できる機能を実装した．性能評価を行い，本提案手法はCassandraを通常使用した際よりも処理が高速に行えることを示す．効率よく活用するためには，対象となるデータに対して複数計算機を利用して並列処理を行う必要がある．しかしながら，分散  からデータを取り出した後に再度データを複数計算機に分散させて並列処理を行うと，データの転送オーバヘッドが非常に大きくなってしまう．本研究では分散 の実装のひとつである  !&quot;&quot;#$ に着目し，データアフィニティを考慮して大容量データをより高速に処理するための手法を提案する．本稿では，!&quot;&quot;#$上に分散して保存された異なる値に対し，事前に指定された処理を値が格納されている計算機上で並列に実行できる機能を実装した．性能評価を行い，本提案手法は !&quot;&quot;#$ を通常使用した際よりも処理が高速に行えることを示す．</div> </blockquote>



- **インタークラウドにおける仮想インフラ構築システムの提案**  <span onmouseover="document.getElementById('os1302takano').style.display = 'block'"  onmouseout="document.getElementById('os1302takano').style.display = 'none'">[abst]</span>   
高野 了成, 中田 秀基, 竹房 あつ子, 柳田 誠也, 工藤 知宏
, *研究報告システムソフトウェアとオペレーティング・システム（OS）2013-OS-124*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os1302takano"> クラウド間で柔軟に資源を融通したり、複数クラウドの資源を組み合わせてサービスを提供するための仮想インフラ構築技術の開発が求められている。本論文では、そのような事例の一つとして、インタークラウド環境において、IaaS事業者に対して、計算機、ネットワーク、ストレージ資源を提供するHaaSサービスモデルおよびHaaS資源管理システムIris（Inter-cloud Resource Integration System）を提案する。Irisはデータセンタ内部の各種資源の管理および仮想化と、データセンタ間ネットワークの制御を行う。Irisのプロトタイプ実装を用いた実証実験では、Apache CloudStackで管理されたIaaSシステムに変更を加えることなく、HaaSの資源を透過的に提供できることを示す。実験結果から、HaaSシステム上へのユーザVMのデプロイ時間は、IaaSシステム上と遜色ないことが分かった。さらに、各要素技術に対する機能または性能上の課題について議論する。</div> </blockquote>



- **SSS-MapReduceのグラフ処理アプリケーションによる評価**  <span onmouseover="document.getElementById('hpc1302nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc1302nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川 宏高, 工藤 知宏
, *研究報告ハイパフォーマンスコンピューティング 2013-HPC-138*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1302nakada"> SSS はキーバリューストアを基盤として採用することで、通常のファイルシステムベースの MapReduce システムと比較して、より柔軟なワークフローを構築することが可能となっている。本稿ではこのような SSS の特性のメリットを確認するために、複雑なワークフロー処理を伴うグラフ処理システム PEGASUS による評価を行った。PEGASUS は Hadoop 向けに記述されている。この PEGASUS の提供するアプリケーションの一部を SSS 固有の機能を用いて SSS 上に再実装し、オリジナルの Hadoop 版と比較した。評価の結果、PEGASUS の移植において、SSS を用いることでワークフロー構造を単純化するとともに、データ構造をバイナリ化することが可能であることがわかった。この結果多くの場合において高速化に成功し、特にブロック化した場合においては最大で約 2.1 倍の高速化を実現できることを確認した。</div> </blockquote>



- **Cassandraによる局所性を考慮した分散並列処理の提案**  <span onmouseover="document.getElementById('dbs12hishinuma').style.display = 'block'"  onmouseout="document.getElementById('dbs12hishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会研究報告. データベース・システム研究会報告*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dbs12hishinuma"> 近年，データの爆発的な増加により，大量のデータを高速に処理することが必要な場面が増え，分散KVS (Key Value Store)と呼ばれるNoSQL型データベース管理システムが注目され始めた．分散KVSに格納された大容量データを効率よく活用するには，データの並列処理が必要となるが，分散KVSから対象データを取り出した後，再度データを分散させて並列処理を行うと，処理効率が悪くなってしまう．そこで本研究では，大規模データを扱う分散KVSであるApache Cassandraに着目し，大規模データをより高速に処理するための手法を提案する．Cassandraに保存されたデータに対して任意の処理を行いたい状況では，Cassandraから処理を行いたい値を取得し，その後処理を行うのが通常の流れである．しかし，Cassandraの読み出し処理性能があまり高くない上に，取得しようとする値が大きくなると通信量が多くなり処理が遅くなってしまうことが予想される．そこで本研究では，Cassandraに保存された値に対し任意の処理を効率よく行えるようにするために，まず，UDFと呼ばれる機能と類似した機能をCassandraに追加する．追加した機能を利用し，ユーザが実行したい処理をプラグインとして定義し，各データノード上で処理を行い結果のみをクライアントに返す手法を提案する．これにより通信が必要なデータ量を抑えることができ，また，処理を行う対象の値をrangeで複数指定すると，異なる値に対して並列に処理を実行可能になり，より高速化できる．本稿では手案手法の実装第一段階として，ユーザが指定した1つの値に対し，任意の処理を行い結果のみを取得する機能を実装し，その特性を評価した．その結果，本提案手法は処理対象の値のサイズが比較的大規模な場合には有効な手法であることが示せたと同時に，その一貫性レベルを調整することで処理の高速化が可能であることを確認した.</div> </blockquote>



- **VMware ESXi 5 の I/O 性能評価**  <span onmouseover="document.getElementById('comsys12saito_poster').style.display = 'block'"  onmouseout="document.getElementById('comsys12saito_poster').style.display = 'none'">[abst]</span>   
斎藤 大輔, 芳澤 伸介, 山崎 輝幸, 高野 了成, 池上 努, 中田 秀基, 竹房 あつ子, 田中 良夫 
, *コンピュータシステムシンポジウム2012論文集*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys12saito_poster"> 仮想マシンモニタVMWare ESXi 5における、ファイバチャネルストレージおよび10ギガビットイーサネットの性能を評価したので報告する。ゲストOSにはWindows server 2008 R2およびRed Hat Enterprise Linux 6.2を用いた。実験では物理マシン、仮想マシン(仮想化I/O、またはPCIパススルー)の3つの設定での性能を比較した。その結果、概ね仮想化I/Oの性能がもっともよく、仮想化環境においても十分なI/O性能を得られることが確認できた。</div> </blockquote>



- **省電力化のためのマッチングに基づく仮想計算機パッキングアルゴリズム**  <span onmouseover="document.getElementById('acs5-5takahashi').style.display = 'block'"  onmouseout="document.getElementById('acs5-5takahashi').style.display = 'none'">[abst]</span>   
高橋 里司, 竹房 あつ子, 繁野 麻衣子, 中田 秀基, 工藤 知宏, 吉瀬 章子
, *情報処理学会論文誌 コンピューティングシステム Vol.5 No.5*   , pp. 33-42  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs5-5takahashi"> データータセンタでの消費電力低減の手法として，低負荷の仮想計算機(VM)を高速にマイグレーションして集約し，使用していない物理計算機を省消費電力モードで運用する方法がある．これを実現するには，消費電力を抑えつつユーザ体験の劣化を防ぐ，負荷が変動するVM群を現実的な時間で再配置する，再配置時のマイグレーションによる通信衝突を考慮する，という課題がある．本研究では，ユーザ体験を劣化させることなく省電力化を図る仮想計算機パッキング問題に対するマッチングべースアルゴリズムを提案，評価する．提案手法では，再配置時に1つの物理計算機が送受信できるVM数を制限し，VMを送受信する物理計算機の組合せをグラフのマッチングで表すことで，多項式時間で適切な再配置プランニングを可能にする．評価実験では，マッチングを用いた提案手法，仮想計算機パッキング問題を0-1整数計画問題として定式化して最適化ソルバを用いる手法とグリーディな手法に対して，消費電力削減効果，計算時間，ユーザ体験の劣化を比較する．この評価実験から，1)パッキングをしない場合より18%から50%の消費電力が削減できる，2)マッチングべースアルゴリズムにより，現実的な計算時間で適切な再配置を行うことができる，3)ユーザ体験は消費電力の削減効果に反比例する傾向があるが，再配置によりほぼ改善できる，ことが示される．</div> </blockquote>



- **PrefixSpan法のMapReduce実装の改良** [[Paper](dataDir/cpsy1210nakada.pdf)]  <span onmouseover="document.getElementById('cpsy1210nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1210nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 井上 辰彦, 小川 宏高, 工藤 知宏
, *信学技報, vol. 112, no. 237, CPSY2012-40.*   , pp. 55-60  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1210nakada"> 分散キーバリューストアをベースとし、Owner Computeルールで計算を実行することで、高速な繰り返し処理を可能とするMapReduce処理系SSSを開発している。このSSSの評価の一つとして、PrefixSpan法による系列パターン抽出を実世界アプリケーションとして利用して来た。しかし、既存の手法では大規模なデータに対しては十分な絶対性能が得られていなかった。本稿ではPrefixSpanをMapReduceで実装するための新たな手法を提案する。提案手法ではデータの流れを見直すことによって、これまでReduceで行なっていた処理を、Mapに移すことによって大幅な速度の向上を得た。具体的には4Mのソースコードのデータに対してSSSで約60倍、Hadoopで約3倍の高速化を実現した。</div> </blockquote>



- **ポストペタスケール計算機環境に向けた高可用分散協調セルフスケジューリング機構の提案** [[Slides](dataDir/hpc1210takefusa_slide.pdf)]  <span onmouseover="document.getElementById('hpc1210takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc1210takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 中田 秀基, 池上 努, 田中 良夫
, *情報処理学会研究報告2011-HPC-136*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1210takefusa"> ポストペタスケール計算機環境では，階層型タスク並列が有望なプログラミングモデルの 1 つであると考えられている．タスク並列型アプリケーションでは，タスクの再実行や冗長実行により，耐障害性を備えるように設計することは比較的容易であるが，その実装は容易ではない．よって，我々はそのようなアプリケーションの開発を容易にする耐障害アプリケーションフレームワークの開発を目指している．アプリケーションフレームワークでは，故障箇所を避けながら適切な計算ノード上でタスクを実行する資源管理機構が必要となるが，ポストペタスケール計算機環境でのスケーラビリティや，資源管理機構そのものの耐障害性，資源管理情報の永続化が課題となる．本稿では，スケーラブルかつ可用性の高い分散協調セルフスケジューリング機構を提案・設計する．提案する資源管理機構では，複数資源管理プロセスを分散協調させてタスクキューを管理し，タスクキュー内のタスクを各計算ノード上の実行デーモンプロセスが自律的に取得して実行する．また，各計算ノードの死活監視を行い，実行中に故障が発生した場合は選択的に再実行または削除する仕組みを提供する．資源管理プロセスの耐障害性と資源管理情報の永続化の実現方法を検討するため， Apache ZooKeeper を用いてこれらの機能を試験実装し，提案資源管理機構の妥当性と課題の明確化を行う</div> </blockquote>



- **MapReduce処理系SSSにおけるContinuous MapReduceの実装** [[Paper](dataDir/hpc1210nakada.pdf)]  <span onmouseover="document.getElementById('hpc1210nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc1210nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川 宏高, 工藤 知宏
, *情報処理学会研究報告2011-HPC-136*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1210nakada"> 継続的に生成されるストリームデータを、大容量データと付きあわせて処理するためのシステムを提案する。従来のストリーム計算システムは、オンメモリの比較的少量のデータしか参照できない。一方Hadoopに代表されるファイルベースのMapReduceシステムを拡張し、ストリームデータに対応させる研究も存在するが、ストリームデータとストレージ上のデータをうまく組み合わせて処理することのできる処理系はない。我々の提案するSSSは、間欠的に起動するMapper / Reducer プロセスでストリームデータの処理を行う。この際にストレージ上の既存データとのマージ操作を行うことで、ストレージ上の大容量データとストリームデータを付きあわせて処理することが可能になる。本稿ではSSSのストリームデータ処理機構の概要と、ストリームデータ処理の予備的評価の結果を示す。予備評価の結果、提案システムは1ノードあたりおよそ秒間0.14Miレコードを処理できることが確認できたが、読み出しスレッドとの干渉により間欠的に書き込みスループットが大幅に低下し、平均としては秒間0.095Miレコード程度となることがわかった。</div> </blockquote>



- **パブリック・クラウドの現在**    
中田秀基
, *IDG Cloud Computing World 2012 Tokyo*    , 2012 



- **MapReduce処理系SSSにおけるKey Value Store アクセス手法の改良** [[Paper](dataDir/cpsy1208nakada.pdf)] [[Slides](dataDir/cpsy1208nakada-slides.pdf)]  <span onmouseover="document.getElementById('cpsy1208nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1208nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川 宏高, 工藤 知宏
, *信学技報, Vol.112, No.173 CPSY2012-9 - CPSY2012-30*   , pp. 103-108  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1208nakada"> われわれが開発中のMapReduce処理系SSSは、既存のKey Value Store（KVS）であるTokyoCabinetを要素KVSとする分散KVS上に構築されている。既存のSSS実装ではTokyoCabinetをネットワークサーバ化するレイヤであるTokyoTyrantを改変し、利用してきた。しかし、性能上の問題点が確認されたため、TokyoTyrant を廃し、独自のネットワーク・サーバレイヤを導入した。この導入により、１）ネットワーク通信時のデータコピー削減によるアクセス高速化、２）タプルグループごとにデータベースファイルを持つことによるグループ削除の高速化、３）キーに対するプレフィックス、ポストフィックスを廃することによる転送データ量の削減、を実現することができた。</div> </blockquote>



- **MapReduce処理系SSSのアプリケーションによる消費電力測定** [[Paper](dataDir/hpc1208ogawa.pdf)]  <span onmouseover="document.getElementById('hpc1208ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1208ogawa').style.display = 'none'">[abst]</span>   
小川 宏高, 中田 秀基, 高野 了成, 工藤 知宏
, *情報処理学会研究報告2011-HPC-135*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1208ogawa"> MapReduce は,大規模なデータインテンシブ計算の実装手段として広範に用いられている.その単 純なプログラミングモデルゆえ,MapReduce はデータインテンシブ計算のみならず,より一般的な HPC 分野の並列分散アプリケーションのためのプログラミングツールとしても利用されつつある.われわれは イタレーションが高速で柔軟なワークフローの構成が可能な大規模データ処理システムの実現を目的とし て,MapReduce 処理系 SSS を開発している.Hadoop が HDFS と呼ばれる一種の分散ファイルシステム を基盤としているのに対して,SSS は分散キーバリューストアを基盤としている点が大きく異なる.一方 で,こうした処理系の利活用によってますます大規模な計算リソースを必要とするようになると,ランニ ングコスト,とりわけ電力コストの問題は避けられない問題となる.われわれは消費電力に対して処理系 をチューニングする必要があると考え,そのために実験用クラスタの消費電力を秒単位で計測・報告する システムを構築した.その上で,本稿では English Wikipedia の全テキストデータを対象に Word Count を実行するベンチマーク実験を実施したので本稿ではその結果を示す.</div> </blockquote>



- **様々なシステム構成におけるCassandraの処理能力に関する考察**  <span onmouseover="document.getElementById('dicomo1207hisinuma').style.display = 'block'"  onmouseout="document.getElementById('dicomo1207hisinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2012)シンポジウム予稿集*   , pp. 396-402  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo1207hisinuma"> 近年,クラウドコンピューティングの普及や,分散環境における一貫性の制限を緩和 して処理性能を重視するアプリケーションが多く開発されている事に伴い,個人が生み 出す情報が大量にネットワーク上に保存されるようになり,そのデータ量が爆発的に 増加している.それに伴い従来のデータベース管理システムである ではデー タ格納や処理の柔軟性に不満が出る場面も見られるようになり, と呼ばれる 新しいデータベース管理システムが注目され始めた.そこで,本研究では の 実装のひとつであり, 型データベースでありながら,複雑なデータ管理が可能なCassandraと呼ばれる分散データベースに着目する. に対しベンチマー クツール を用いて書き込みや読み出しにかかる実行時間やスループット等を測 定し性能評価を行い,その結果をもとに の傾向を明確にするための考察を 行う.これまでに小規模なクラスタを用いた性能測定は実行済みなので,本研究では より詳細な の傾向把握のためにより大きなクラスタを用いて の傾向を調査し,特に一貫性レベルとレプリケーション数の変化に伴う Cassandraの 振る舞いの変化等を調べる.調査の結果, はある一定の負荷までは効率良 く処理が行えていることが分かり,本実験環境では ノードあたり スレッド程度は 無駄なく処理することができていた.また,読み出処理は実行結果が一貫性レベルや レプリケーション数といった設定条件に大きく依存し,書き込み処理はあまり依存し ていないことが確認できた.</div> </blockquote>



- **MapReduce処理系SSSの実装と評価** [[Paper](dataDir/sacsis12ogawa_poster.pdf)]    
小川宏高, 中田 秀基, 高野 了成, 工藤知宏
, *SACSIS2012予稿集（ポスタ）*   , pp. 44  , 2012 



- **一貫性を考慮したCassandraの処理性能に関する考察** [[Paper](dataDir/sacsis12hishinuma_poster.pdf)]    
菱沼 直子, 竹房 あつ子, 中田秀基, 小口 正人
, *SACSIS2012予稿集（ポスタ）*   , pp. 49-50  , 2012 



- **仮想マシンの超広域ライブマイグレーションにむけたベストエフォート型状態同期機構の試作**  <span onmouseover="document.getElementById('os1205hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('os1205hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, マウリシオツガワ, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2012-OS-121*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os1205hirofuchi"> 仮想マシンの遠隔ライブマイグレーションを用いれば、災害発生時にサーバを安全な遠隔拠点に待 避できる。しかし、ライブマイグレーションは大量のデータ転送を伴うため、ネットワーク帯域が限られる WAN 環境において、災害発生直後の限られた猶予時間内に再配置を完了することが難しい。本稿では、広域ライブマイグレーション時間を短縮するため、仮想マシンの実行状態をベストエフォートで事前に同期する手法を提案する。平時から仮想ディスクの状態を待避先拠点とできる限り同期しておき、ライブマイグレーションを実行する際にはその差分のみを転送する。マイグレーションに伴うデータ転送量およびマイグレーション時間を大幅に削減できる。同期データに対して世代管理を行うことで、可用帯域が許す範囲での部分的な同期を可能にし、一時的な通信の断絶に対しても再び途中から同期を再開可能にしている。提案機構のプロトタイプを実装し、日米間のネットワークを用いて基礎的な評価実験を行った。仮想マシンの実行状態全体を約30秒で再配置できた。提案機構を用いない場合(約1時間)よりも大幅に待避時間を短縮できた。</div> </blockquote>



- **MapReduce処理系SSSに向けたKVSの改良** [[Paper](dataDir/cpsy1204nakada.pdf)]  <span onmouseover="document.getElementById('cpsy1204nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1204nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *信学技報, Vol.112, No.2 CPSY2012-1 - CPSY2012-8*   , pp. 19-24  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1204nakada"> 広く用いられている Hadoop と比較して、より広い範囲に適用可能な MapReduce 処理系 SSS を開発して いる。SSS はオープンソースのキーバリューストア(KVS)である Tokyo Cabinet とそのネットワークインターフェ イスである Tokyo Tyrant をストレージとして用いる。しかし、SSS のアクセスパターンはバルクでの読み出し、書き 込み、削除が主で、Tokyo Tyrant が本来想定している細粒度のアクセスとはかけ離れており、Tokyo Tyrant が用意 する API を利用するだけでは、Tokyo Cabinet/Tokyo Tyrant 本来の性能を引き出すことが出来なかった。本稿では われわれが行った、Tokyo Cabinet に対する改変について報告する。SSS が行う範囲指定処理を Tokyo Cabinet およ び Tokyo Tyrant に追加し、さらに内部でのロックを最適化した。その結果、Tokyo Cabinet を直接用いるマイクロ ベンチマークで、読み込み時 5 倍書き込み時 2 倍の速度向上を確認した。また、SSS 全体としてのマクロベンチマー クでも読み込み時 3 倍、書き込み時で 1.3 倍の速度向上を確認した。</div> </blockquote>



- **ポストぺタスケール高性能計算に向けた階層的プログラミングモデルの提案** [[Paper](dataDir/hpc1203ikegami.pdf)]  <span onmouseover="document.getElementById('hpc1203ikegami').style.display = 'block'"  onmouseout="document.getElementById('hpc1203ikegami').style.display = 'none'">[abst]</span>   
池上 努, 田中 良夫, 中田 秀基, 高野 了成, 関口 智嗣
, *情報処理学会研究報告2011-HPC-133*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1203ikegami"> 次世代スパコンで想定される百万コア越の大並列環境を対象に、高効率かつ頑健な アプリケーションを実装する上で必要となるアルゴリズムとプログラミング手法につ いて考察する。まず、マスタ・ワーカ型の実装が可能であり、かつワーカの障害に対 して寛容なアルゴリズムを紹介する。次いでワーカの動的な増減を可能にするプログ ラミング手法として、グリッド環境で実績のある、遠隔手続き呼出し (RPC) と MPI を組合せたハイブリッド型の手法を提案する。グリッド環境での経験を元に、従来型 RPC に対する改善案を検討する。</div> </blockquote>



- **MapReduce 処理系 SSS の PrefixSpan 法による評価** [[Paper](dataDir/hpc1203nakada.pdf)]  <span onmouseover="document.getElementById('hpc1203nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc1203nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *情報処理学会研究報告2011-HPC-133*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1203nakada"> MapReduceプログラミングモデルの幅広いアプリケーションへの適用をめざし、より柔軟で複雑なワークフロー実行を可能にするMapReduce処理系SSSを開発している。SSSは代表的なMapReduce処理系であるHadoopとは大きく構成が異なり、したがって性能的特性も大きく異なる。われわれはSSSの有効なアプリケーション領域を知るべく、合成的ベンチマークでの評価とともに実アプリケーションでの評価を行っている。本稿では、先行研究で述べたPrefixSPan法による系列パターン抽出の改良と、疎行列ベクトル積について述べる。評価の結果、いずれのアプリケーションにおいてもSSSはHadoopよりも高性能であることが確認できた。</div> </blockquote>



- **クラウドの現状**    
中田秀基
, *電子情報通信学会総合大会*    , 2012 



- **NSI相互運用試験のためのGridARSによるネットワーク資源管理**  <span onmouseover="document.getElementById('ns1203takefusa').style.display = 'block'"  onmouseout="document.getElementById('ns1203takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 工藤知宏, 中田 秀基, 高野 了成, 大久保克彦, 岡崎 史裕, 柳田誠也
, *電子情報通信学会技術研究報NS2011-224*   , pp. 249-254  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns1203takefusa"> NSI(Network Service Interface)はOGFで標準化が進められているネットワーク上のコネクションを要求するためのインタフェースであり、そのドラフト第一版が2011年3月にリリースされた。NSIの実現可能性を示すため、我々を含む欧米亜の複数機関によりウェブサービスベースの参照実装が開発され、国際的なネットワークテストベッド上で相互運用試験を行っている。
我々は、複数クラウド環境で多種資源を管理するフレームワークとしてGridARSを開発している。本研究では、GridARSにJAX-WS 2.0の非同期モデルを新たに実装して手続きの高速化を図るとともに、GridARSに対するNSIプロキシを開発し、プロキシを介して複数参照実装との相互運用を実証した。</div> </blockquote>



- **CassandraによるKVSデータ処理におけるデータ容量と処理性能に関する考察**  <span onmouseover="document.getElementById('deim1203hishinuma').style.display = 'block'"  onmouseout="document.getElementById('deim1203hishinuma').style.display = 'none'">[abst]</span>   
菱沼 直子, 竹房 あつ子, 中田秀基, 小口 正人
, *第4回データ工学と情報マネジメントに関するフォーラム deim2012*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim1203hishinuma"> 近年,クラウドコンピューティングの普及に伴い,個人が生み出す情報が大量にネットワーク上に保存され,ネットワーク上に存在するデータ量の爆発的な増加が生じている. それに伴い従来のデータベース管理システム であるRDBMS ではデータ格納や処理の柔軟性に不満が出るようになり, NoSQLと呼ばれる新しいデータベース管理システムが注目され始めた.そこで,本研究では NoSQLの実装のひとつであり,KVS 型データベースでありなが ら,複雑なデータ管理が可能な Cassandraと呼ばれる分散データベースに着目する. Cassandraに対しベンチマーク ツール YCSBを用いて書き込みや読み出しにかかる実行時間やスループット等を測定し性能評価を行い,その結果を もとに Cassandraの傾向を明確にするための考察を行う.特に処理データ量に対するスケーラビリティなどの特性を 明らかにする.測定から, Cassandraが書き込み性能重視な NoSQLで,一貫性と処理性にトレードオフの関係があ ることが分かった.また,ノード数を増加させるとCassandraのスループットが向上していくことも確認できた.</div> </blockquote>



- **クラウドを利用した電力可視化システムの構築**  <span onmouseover="document.getElementById('os1111takano').style.display = 'block'"  onmouseout="document.getElementById('os1111takano').style.display = 'none'">[abst]</span>   
高野 了成, 中田秀基, 清水 敏行, 工藤知宏
, *情報処理学会研究報告2011-OS-119*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os1111takano"> きめ細やかな節電計画の立案には、事業所内の分電盤ごと、さらにはブレーカごとの細分化した単位でリアルタイムに使用電力を可視化する必要がある。しかし、必要な電力計測点が多くなるため、システム全体のコスト削減やスケーラビリティの向上が重大な問題になる。我々は、安価な電力計測ユニット （計測点あたり 2500 円） とクラウドコンピューティング技術を用いることで、安価かつスケーラブルなシステムを短期間に開発することに成功した。そして、産総研のサーバ室および実験室に 290 計測点を有するシステムを導入し、個別機器毎の電力使用量を可視化したので報告する。</div> </blockquote>



- **ゲスト透過なMobile IPv6トンネリング機構(Kagemusha)を用いた仮想マシンの広域ライブマイグレーション** [[Paper](dataDir/ic11hirofuchi-demo.pdf)]    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *インターネットコンファレンス 2011 (IC2011) デモ*   , pp. 139-140  , 2011 



- **分散KVSに基づくMapReduce 処理系SSS** [[Paper](dataDir/ic11nakada-poster.pdf)]    
中田 秀基, 小川宏高, 工藤知宏
, *インターネットコンファレンス 2011 ポスタ*    , 2011 



- **MapReduce処理系SSSの実アプリケーションによる評価** [[Paper](dataDir/cpsy1110nakada.pdf)] [[Slides](dataDir/cpsy1110nakada_slides.pdf)]  <span onmouseover="document.getElementById('cpsy1110nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1110nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *信学技報, Vol.111, No.255, CPSY2011-25-CPSY2011-41*   , pp. 55-60  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1110nakada"> 高速で高機能なMapReduce処理系の実装を目指し、分散キーバリューストアを用いてOwner Computes ルールに基づいた計算を行う軽量なMapReduce処理系SSSの開発を行なった。これまで、合成ベンチマークや簡単なアプリケーションのコアを用いたベンチマークによる評価の結果、Hadoopに対して大幅な高速化を確認したが、実世界のアプリケーションでの性能の検証は行われていなかった。本稿ではPrefixSpan法による系列パターン抽出を対象としてSSSの評価を行った。この結果、SSSは全般にHadoopと比較して高速であり、さらにノード数増大による速度向上の余地があることが確認できた。</div> </blockquote>



- **高速で高機能なMapReduceシステムSSS** [[Paper](dataDir/openlab11nakada.pdf)]    
中田 秀基, 小川宏高
, *産総研オープンラボ11展示*    , 2011 



- **MapReduce処理系SSS上のSawzall処理系の実装** [[Paper](dataDir/cpsy1107-nakada.pdf)] [[Slides](dataDir/cpsy1107-nakada_slide.pdf)]  <span onmouseover="document.getElementById('cpsy1107-nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1107-nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 井上辰彦, 小川宏高, 工藤知宏
, *信学技報, Vol.111, No.163, CPSY2011-9-CPSY2011-24*   , pp. 89-94  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1107-nakada"> Sawzallは、Google が2006年に発表した大容量データの並列バッチ処理に適した言語である。Sawzallの計算モデルはMapReduce型の分散演算であるが、リダクション操作を組み込みのAggregatorに限定することで、エンドユーザによる容易な記述を可能にしている。われわれはHadoopおよびわれわれが現在開発中のMapReduce 処理システム SSSを対象として、Scala言語によるSawzall言語処理系SawzallClone を、Javaをターゲットコードとするコンパイラとして実装した。SSSのNative APIで直接プログラムを記述した場合と比較を行い、言語オーバヘッドを見積もった。また、Googleによる逐次処理系Szlとの比較を行った。その結果、一定の言語オーバヘッドはあるもののメリットを考えれば許容範囲であること、Szlと比較して遜色ない逐次性能を示すことを確認した。</div> </blockquote>



- **省電力化にむけた仮想計算機パッキングアルゴリズムの提案**  <span onmouseover="document.getElementById('cpsy1107-takefusa').style.display = 'block'"  onmouseout="document.getElementById('cpsy1107-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 広渕崇宏, 伊藤智, 関口智嗣
, *信学技報, Vol.111, No.163, CPSY2011-9-CPSY2011-24*   , pp. 73-78  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1107-takefusa"> データセンターでの消費電力削減手法の一つとして、仮想計算機（VM）を適宜マイグレーションして使用していない物理計算機を低消費電力状態でスタンバイさせる方法が考えられる．これを実現するには，マイグレーション時の通信衝突を考慮しつつ負荷に応じてVMの配置を決定（仮想計算機パッキング）する手法が必要である．本研究では，通信衝突を考慮したVMパッキングアルゴリズムとして，0-1整数計画法を応用した手法（IP）とグリーディな手法（Greedy）を提案する．評価では，総消費電力量，ユーザ体験の劣化，スケジューリングに要する時間を比較し，シミュレーションから以下が示された．1) GreedyとIPにより消費電力の大幅な削減が可能である．2) ユーザ体験の劣化は消費電力削減効果に反比例するが，再配置により解消できる．3) Greedyは高速かつリーズナブルな再配置が可能であり，IPはリアルタイム性を確保しつつより消費電力削減効果の高い再配置が可能である．</div> </blockquote>



- **合成ベンチマークによるMapReduce 処理系SSS の性能評価** [[Paper](dataDir/hpc1107ogawa.pdf)] [[Slides](dataDir/hpc1107ogawa_slide.pdf)]  <span onmouseover="document.getElementById('hpc1107ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1107ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 工藤知宏
, *情報処理学会研究報告2011-HPC-130*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1107ogawa"> MapReduce プログラムで大容量データを処理する際の実行速度は、Mapへの入力されるデータ、Reduceから出力されるデータ、さらにMap 処理とReduce処理の間でやりとりされる中間データの量と性質によって大きく変化する。特に中間データを蓄積する方法は、処理系によって大きく異なり、システム全体の特性を決定する要因となりうる。われわれは開発中のMapReduce 処理系SSSの特性を確認するために、 先行研究で開発した合成ベンチマークプログラムを用いて、SSSの評価を行い、Hadoopと比較した。合成ベンチマークプログラムは、MapReduceプログラムのデータ入出力部分のみを抽出したもので、パラメータを変更することでさまざまなプログラムの入出力パターンを再現することが可能となっている。評価の結果、以下を確認した。1) SSSはHadoopと比較して一般に高速に動作する、2) SSSのMap後のCombine処理は非常に有用である、3) ベンチマークの設定には改善が必要である。</div> </blockquote>



- **Hadoop上で動作するSawzallサブセット** [[Paper](dataDir/sacsis11nakada-poster.pdf)]  <span onmouseover="document.getElementById('sacsis11nakada-poster').style.display = 'block'"  onmouseout="document.getElementById('sacsis11nakada-poster').style.display = 'none'">[abst]</span>   
中田秀基, 井上辰彦, 小川宏高, 高野了成, 工藤知宏
, *先進的計算基盤システムシンポジウムSACSIS2011 (ポスター発表)*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis11nakada-poster"> GoogleによるMapReduce 向け言語であるSawzallのサブセット(以下SawzallClone)を実装しHadoop上で実行できる環境を実装した。SawzallClone はJavaを中間言語として用いるコンパイラとして実装した。構文解析にScalaのParser Combinatorを用いることで、処理系の記述量が削減できた。</div> </blockquote>



- **合成ベンチマークによるMapReduceのI/O性能評価手法** [[Paper](dataDir/hpc1103ogawa.pdf)]  <span onmouseover="document.getElementById('hpc1103ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1103ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 工藤知宏
, *情報処理学会研究報告2011-HPC-129*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1103ogawa"> MapReduceは，大規模なデータインテンシブ計算の実装手段として広範に用いられている．その単純なプログラミングモデルゆえ，MapReduceはデータインテンシブ計算のみならず，より一般的なHPC分野の並列分散アプリケーションを実装するためのプログラミングツール，謂わば``High-Performance MapReduce&#x27;&#x27;処
理系，としても利用されつつある．こうしたMapReduce処理系の高性能計算への適用を考えたとき，定量的な性能評価基準は必須であるが、MapReduceに関してはそのような基準が存在しない．我々はこうした問題を解決するために，合成ベンチマークによるMapReduceのI/O性能の評価を行うことを提案する．具体的
には，MapReduceアプリケーションのデータ入出力をモデル化するとともに，各パラメータを任意に設定して実行できるベンチマークソフトウェアを実現する．本稿ではモデル化ならびに合成ベンチマークの実装の概要を示すとともに，SSDとSAS HDDを用いた小規模なクラスタでの実行結果を示す．</div> </blockquote>



- **多種資源を対象とするオンラインコアロケーション手法の提案**  <span onmouseover="document.getElementById('hpc1103-takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc1103-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 工藤知宏, 田中良夫
, *情報処理学会研究報告2011-HPC-129*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1103-takefusa"> 分散環境におけるデータインテンシブ計算の重要性が多分野において高まっているが，データインテンシブ計算で安定した実効性能を得るには，ネットワーク，計算機，ストレージを含めた資源とそれらの属性情報を考慮したコアロケーション手法が必要となる．
本研究では，多種資源とその属性情報を考慮したオンラインコアロケーション手法を提案する．提案手法では，既発表手法を拡張して整数計画モデルに新たな制約を加えることで，多種資源のコアロケーションを可能にする．
また，整数計画法のソルバに対するJavaインタフェースを提供するJavaILPを用いて提案手法に対して複数整数計画ソルバを適用できるように実装するとともに，シミュレーションによりその基本性能を調査した．その結果，資源の一部をユーザが指定する場合は31.7msecと高速に処理できることと，属性指定がある場合は通常と同程度で処理することが分かり，提案手法の実用性が示された．</div> </blockquote>



- **マルチドメインクラウド資源管理フレームワークの実証実験**  <span onmouseover="document.getElementById('ns1103-takefusa').style.display = 'block'"  onmouseout="document.getElementById('ns1103-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 高野了成, 柳田誠也, 大久保克彦, 工藤知宏, 田中良夫
, *信学技報 NS2010-249*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns1103-takefusa"> マルチドメインクラウドの資源管理フレームワークとして，資源管
理システム，アプリケーション実行管理システム，分散モニタリングシステムからなるGridARSを開発している．本研究では，既存システムを拡張し，相互運用性，機能性の高いGridARSシステムを開発し，大規模環境でその有用性を評価した．また，GLIF2010およびSC10において実証実験を行い，GridARSを用い
てマルチドメインクラウド上に自動的にユーザの要求を満たす仮想インフラを構築し，そのモニタリングを行うことに成功した．</div> </blockquote>



- **Condor VM ユニバースを利用した HPC Cloud の試作**  <span onmouseover="document.getElementById('zen73futatsuki').style.display = 'block'"  onmouseout="document.getElementById('zen73futatsuki').style.display = 'none'">[abst]</span>   
二木邦尚, 田中良夫, 池上努, 中田秀基, 竹房あつ子
, *情報処理学会 第73回全国大会予稿集*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen73futatsuki"> スーパーコンピュータの性能向上は目覚ましく,近い将 来数百 TFlops から数十 PFlops 規模のスパコンが HPC インフラとして大学,研究所やデータセンターなど複数 組織に次々と導入されていく事が予想される.多組織の スパコンを有効活用して科学技術や産業の発展を促進す るためには,ネットワークを介してこれらのスパコンを 容易に利用する環境の構築が必要である.グリッドコン ピューティング [1] はそのための要素技術を提供するが, アプリケーション配備の際に組織毎に異なる計算環境へ の対応に手間がかかるといった問題がある.</div> </blockquote>



- **Hadoop上で動作するSawzallサブセットの実装** [[Paper](dataDir/pro1101nakada.pdf)]  <span onmouseover="document.getElementById('pro1101nakada').style.display = 'block'"  onmouseout="document.getElementById('pro1101nakada').style.display = 'none'">[abst]</span>   
中田秀基, 井上辰彦, 工藤知宏
, *情報処理学会PRO研究会 2010-4-(1)*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pro1101nakada"> Sawzall は、Google が 2006 年に発表した大容量データの並列バッチ処理に適し た言語である。Sawzall の計算モデルは MapReduce 型の分散演算であるが、リダ クション操作を組み込みの Aggregator に限定することで、エンドユーザによる容易 な記述を可能にしている。われわれは現在開発中の並列データ処理機構上の言語処 理系を開発するための 1 ステップとして、Hadoop 上で動作する Scala 言語による Sawzall 言語のサブセット処理系を実装した。文法やセマンティクスに関しては明確 な定義がなかったため、2006 年の論文をベースに推測した。Scala は Java VM 上 で動作するため、Java で記述される Hadoop 上での実行は容易である。構文解析に Scala 言語の Parser Combinator を用いることで、処理系の記述量を削減した。言 語インタプリタは、Hadoop の Mapper 上で動作する。Reducer 上では処理系の提 供する Aggregater が動作する。Hadoop で直接記述した場合と、プログラム量およ び実行速度の点で比較を行った。比較の結果、プログラム量は大幅に小さくなる一方、 実行速度の面でも一定のオーバヘッドがあることが確認された。</div> </blockquote>



- **クラウドの展望と課題**    
中田秀基
, *電子情報通信学会北陸支部講演会*    , 2010 



- **マルチドメインクラウド環境のための資源管理フレームワーク**  <span onmouseover="document.getElementById('comsys10-takefusa-poster').style.display = 'block'"  onmouseout="document.getElementById('comsys10-takefusa-poster').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 高野了成, 柳田誠也, 大久保克彦, 工藤知宏, 田中良夫
, *第22回コンピュータシステム・シンポジウム(ComSys2010)*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys10-takefusa-poster"> クラウドは，大規模データインテンシブ科学技術計算の計算基盤としても注目されているが，分散する複数組織から提供される資源を統合して計算基盤を構築する技術は成熟していない．我々は，マルチドメインクラウド環境で仮想計算基盤を提供する資源管理フレームワークGridARSを提案している．GridARSは，資源管理サービス，プロビジョニングサービス，モニタリングサービスを提供し，予約ベースでマルチドメインクラウド上の資源の選択と確保，仮想計算基盤の構築とユーザアプリケーションの実行，モニタリング情報の提供を自動的に行う．デモンストレーションでは，クラスタ上に構築した仮想マルチドメインクラウド環境を用いて，本フレームワークが実際に動作する様子を示す．</div> </blockquote>



- **大規模資源の管理・制御に関する技術の実証実験 －新世代ネットワークプラットフォームの実現に向けて－**  <span onmouseover="document.getElementById('ns-miyamoto-2010').style.display = 'block'"  onmouseout="document.getElementById('ns-miyamoto-2010').style.display = 'none'">[abst]</span>   
林 通秋, 竹房 あつ子, 池永全志, 宮本 崇弘, 小島 功, 嶋村昌義, 松本延孝, 中田 秀基, 小出洋, 高野 了成, ジルセウ・ガベンディッシュ, 工藤 知宏, 田中 良夫, 西村公佐
, *電子情報通信学会技術研究報告ネットワークシステム*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns-miyamoto-2010"> クラウドコンピューティングの更なる普及や新世代ネットワークに向けた新たなインフラの実現に向けて，計算機やネットワークなどのICT資源を大規模に管理制御して，ユーザの用途に適したICT環境を柔軟に作る技術への期待が高まっている．そこで，複数のネットワークからなる規模のICT資源の存在を把握し，用途に応じて適した資源を割り当てる資源提供プラットフォームを開発した．また，データを適応的に圧縮するなどの機能を持つ高機能中継ノードを開発し，資源提供プラットフォームを通じて用途に応じて割り当てることで，ネットワーク内での輻輳下でも通信品質を維持することに成功した．</div> </blockquote>



- **クラウド上のNoSQLデータベースの実際**  <span onmouseover="document.getElementById('ipsj-seminor2010').style.display = 'block'"  onmouseout="document.getElementById('ipsj-seminor2010').style.display = 'none'">[abst]</span>   
中田秀基
, *情報処理学会連続セミナー 2010 第4回 クラウドコンピューティング技術の肝（要素技術）*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj-seminor2010"> クラウド上のデータベースとしては、従来のリレーショナルデータベースに比べてスケールアウト性に優れるNoSQLデータベースが適していると言われる。しかし、一般に、NoSQLデータベースの機能は、リレーショナルデータベースに遠く及ばず、アプリケーションプログラマの負担は増加する。本講演では、PaaS型のクラウドであるGoogle App Engine のNoSQLデータベース、データストアを例に取り、プログラマへのインパクトについて議論する。</div> </blockquote>



- **仮想計算機パッキングへの最適化手法の適用**  <span onmouseover="document.getElementById('cpsy1008nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1008nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 広渕崇宏, 伊藤智, 関口智嗣
, *電子情報通信学会技術研究報告 Vol.110, No.167, CPSY2010-8 ~ 2010-24*   , pp. 55-60  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1008nakada"> 実行ホストの切り替えを可能とするポストコピー型ライブマイグレーション技術を, 仮想マシン集約システムに対して適用することを新たに提案する.約一秒程度で仮想 マシンの実行ホストを切り替えられるため,迅速に配置状態を最適化できる.突発的 な負荷上昇が発生しても,仮想マシンの性能低下を短時間にとどめられる.評価実験 を通して,提案機構のプロトタイプシステムが正しく動作することを確認した.ポス トコピー型マイグレーションを利用したシステムは,プレコピー型を利用したシステ ムよりも,過負荷状態を迅速に解消し性能低下を軽減できた.</div> </blockquote>



- **高速マイグレーションを利用した仮想マシン配置最適化システムの検討**  <span onmouseover="document.getElementById('os1008hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('os1008hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2010-OS-115*   , pp. 1-13  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os1008hirofuchi"> データセンタの資源利用効率を高めるため,資源消費量に応じた動的な仮想マシン (VM)再配置に関心が高まっている.仮想マシンに対して一定量の計算資源を割り当 てつつも,資源消費量が少ないときには仮想マシンを集約して配置し運用効率を高め る.しかし,これまで研究されてきた仮想マシン集約システムは,仮想マシンの移動 に時間を要するプレコピー型ライブマイグレーション技術を使用している.仮想マシ ンの突発的な負荷上昇が発生すると,過負荷状態を素速く解消することが難しく,長 時間にわたる仮想マシンの性能低下を招いてしまっていた.そこで,我々は,迅速な</div> </blockquote>



- **仮想マシン技術とサーバ一時停止技術を利用した 省エネデータセンタシステムの開発**    
広渕崇宏, 中田秀基, 小川宏高, 伊藤智, 関口智嗣
, *先進的計算基盤システムシンポジウムSACSIS2010*    , 2010 



- **クラウドの現状と展望**    
中田秀基
, *SACSIS 2010 チュートリアル*    , 2010 



- **動的ネットワークパスプロビジョニングの相互運用技術 ーG-lambdaシステムとGLIF Feniusの連携ー**  <span onmouseover="document.getElementById('ns1003-takano').style.display = 'block'"  onmouseout="document.getElementById('ns1003-takano').style.display = 'none'">[abst]</span>   
高野了成, 工藤知宏, 岡崎史裕, 竹房あつ子, 中田 秀基
, *信学技報, NS2009-205*   , pp. 345-350  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns1003-takano"> G-lambdaプロジェクトでは、グリッド・クラウドミドルウェアがネットワークパス、計算機、ストレージといった分散資源を動的に確保、予約するためのインタフェースを確立することを目指している。GLIF（Global Lambda IntegratedFacility）によって開発が進められているFeniusは、動的ネットワークパスプロビジョニングシステム間での相互運用性を実現するために、共通インタフェースを備えたユニバーサルプロキシである。本稿ではFeniusの概要、およびG-lambdaシステムにおけるネットワーク資源マネージャとFeniusを連携した動的ネットワークパスプロビジョニングについて述べる。また、GLIFワークショップ2009および国際会議SC2009においてFeniusを用いた相互運用性実験を行ったので報告する。</div> </blockquote>



- **ネットワーク帯域予約を用いた分散アプリケーション実行環境の構築**  <span onmouseover="document.getElementById('ns1003-nakada').style.display = 'block'"  onmouseout="document.getElementById('ns1003-nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 高野了成, 竹房あつ子, 工藤知宏
, *信学技報, NS2009-205*   , pp. 253-258  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns1003-nakada"> 我々は，予約ベースで計算資源とネットワーク資源を確保し，その上に一般的なクラスタ内の環境と類似した環境を構築するグリッドミドルウェアの構築を行っている．構築された環境内では，一般的なクラスタ向けに記述された並列アプリケーションをそのまま実行することができる．本稿では，ミドルウェアのうち，アプリケーション実行環境の構築部分に焦点を当てて詳述する．われわれのミドルウェアは，Linuxの仮想OS機能LXC(Linux Containers)とスタッカブルファイルシステムを利用することで，通常のユーザ環境をベースとしたサンドボックスを高速に作成することができる．</div> </blockquote>



- **複数ドメイン環境でQoSを保証するクラウドのための資源管理フレームワーク**  <span onmouseover="document.getElementById('ns1003-takefusa').style.display = 'block'"  onmouseout="document.getElementById('ns1003-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 高野了成, 柳田誠也, 大久保克彦, 工藤知宏, 田中良夫
, *信学技報, NS2009-205*   , pp. 247-252  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns1003-takefusa"> クラウド環境でQoSを保証した環境を提供するには，計算資源と計算資源間のネットワークの両方を同時に確保・提供する必要がある．また，これらの資源群は広域に分散し，複数ドメインから提供されるため，その資源のモニタリング情報の収集も課題となる．我々は，資源管理フレームワークGridARSを開発しており，GridARS RMSにより複数ドメインから提供される資源を選択・確保し，GridARS DMSでそのモニタリングを行う．本研究では，多様な資源のために規定された予約インタフェースGNS-WSI3を採用したRMSおよびDMSを，Globus Toolkit 4.2およびApache CXFを用いて開発した．システムの有効性を示すため，エミュレーション環境を構築してRMSおよびDMSの基本性能を調査し，各システムが非常に高速に処理できることを示す．また，RMSとDMSの連携実験をSC09国際会議で行ったので報告する．</div> </blockquote>



- **高速フラッシュメモリに適したキーバリューストアの予備的評価** [[Paper](dataDir/hpc1002-ogawa.pdf)]  <span onmouseover="document.getElementById('hpc1002-ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1002-ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 美田晃伸, 広渕崇宏, 高野了成, 工藤知宏
, *情報処理学会研究報告2010-HPC-124*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1002-ogawa"> 大規模なデータインテンシブアプリケーションの高性能実行の必要性から，大規模データ処理に特化された分散処理を実現する，Data-Intensive Scalable Computing(DISC) が注目されている．MapReduce は，そうした DISC を実現するシステムのひとつであるが，近年利用可能になってきた，10Gbit/sec クラスの読み書き性能を持つ高速な SSD (Solid State Drive) との組み合わせでは，ソフトウェアオーバヘッドが課題となり，十分な性能が得られない危惧がある．そこで我々は，10Gbit/sec クラスの読み書き性能を持つフラッシュメモリストレージに適した，MapReduce システムの実現を目指し，分散キーバリューストアを基盤とする MapReduce システムのプロトタイプ実装を行った．本稿では，我々のプロトタイプ実装の概要を示すとともに，その基盤となるキーバリューストアの既存実装の性能評価を行う．</div> </blockquote>



- **仮想マシンの瞬間的な実行ホスト切り替えを可能とする ポストコピー型ライブマイグレーション機構**    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *第21回コンピュータシステム・シンポジウム(ComSys2009)*    , 2009 



- **Googleのクラウド技術**    
中田秀基
, *情報処理 Vol.50 No.11*   , pp. 1062-1067  , 2009 



- **瞬間的な実行ホスト切り替えを可能とする仮想マシンの高速ライブマイグレーション機構**    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *日本ソフトウェア科学会研究会資料シリーズNo.62, 日本ソフトウェア科学会, インターネットカンファレンス2009*   , pp. 122  , 2009 



- **クラウドコンピューティング：動向と課題**    
中田秀基
, *第８回ネットワークソフトウェア研究会招待講演*    , 2009 



- **大規模環境における資源情報連携アーキテクチャ**  <span onmouseover="document.getElementById('ngnworkshop2009').style.display = 'block'"  onmouseout="document.getElementById('ngnworkshop2009').style.display = 'none'">[abst]</span>   
宮本 崇弘, 小島 功, 池永全志, 林 通秋, 田中 良夫, ジルセウ・ガベンディッシュ, 松本延孝, 工藤 知宏, 小出洋, 田中 英明, 児玉 祐悦, 嶋村昌義, 中田 秀基, 竹房 あつ子, 高野 了成
, *電子情報通信学会 新世代ネットワークワークショップ 2009*   , pp. 7-12  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ngnworkshop2009"> けて，計算機やネットワークなどのICT資源を大規模に管理制御して，ユーザの用途に適したICT環境を柔軟に作る技術への期待が高まっている．そこで，複数のネットワークからなる規模のICT資源の存在を把握し，用途に応じて適した資源を割り当てる資源提供プラットフォームを開発した．また，データを適応的に圧縮するなどの機能を持つ高機能中継ノードを開発し，資源提供プラットフォームを通じて用途に応じて割り当てることで，ネットワーク内での輻輳下でも通信品質を維持することに成功した．</div> </blockquote>



- **高速フラッシュメモリ向けMapReduceフレームワークの実現に向けて** [[Paper](dataDir/swopp09-ogawa.pdf)]  <span onmouseover="document.getElementById('swopp09-ogawa').style.display = 'block'"  onmouseout="document.getElementById('swopp09-ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 広渕崇宏, 高野了成, 工藤知宏
, *情報処理学会研究報告2009-HPC-121*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-ogawa"> 大規模なデータインテンシブアプリケーションの高性能実行の必要性から，大規模データ処理に特化された分散処理を実現する，Data-Intensive Scalable Computing(DISC) が注目されている．DISC は，安価なハードディスクと Gigabit Ethernet を用いたクラスタシステムを用いて，大容量データをストリーム的に扱うワークロードを実行するシステムとして非常に有効である．一方で近年利用可能になってきた，10Gbit/sec クラスの読み書き性能を持つ高速な SSD (Solid State Drive) との組み合わせでは，ソフトウェアオーバヘッドが課題となり，十分な性能が得られない危惧がある．そこで我々は，10Gbit/sec クラスの読み書き性能を持つ高速なフラッシュメモリを利用したストレージクラスタに適した，DISC システム SSS を設計・実装することを目指している．本稿では，既存の DISC システムの問題点を考察した上で，我々がプロトタイプ設計している SSS フレームワークのアーキテクチャを説明する．</div> </blockquote>



- **性能を保証する計算・ネットワーク資源のコアロケーション手法の評価**  <span onmouseover="document.getElementById('swopp09-takefusa').style.display = 'block'"  onmouseout="document.getElementById('swopp09-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *情報処理学会研究報告2009-HPC-121*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-takefusa"> 利用者の要求する性能を保証しつつ計算機・ネットワークなどの資源を組合わせて提供する場合，それらの資源のスケジューリングが重要な課題となる．我々は既発表研究において，このようなスケジューリングを最適化問題としてモデル化し，必要な計算・ネットワーク資源を同時に確保するためのオンラインコアロケーション手法を提案した．一方，最適化問題として解くと，変数の数に依存して指数的に求解時間が長くなるため，実用化に向けた課題が残る．本研究では， (1) 制約条件を追加することにより既発表研究の手法を改良し，求解時間の短縮を図るとともに，(2) 制約条件とソルバの違いによるに求解時間を比較し，実用化に向けて議論する．また，既発表研究に対して追加の実験を行い，(3) 重み付けすることにより管理者の要求を反映した資源の割り当てが可能であり，我々の手法が機能面でも有効であることを示す．</div> </blockquote>



- **仮想計算機メモリの遅延再配置による高速ライブマイグレーション**  <span onmouseover="document.getElementById('swopp09-hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('swopp09-hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2009-OS-112*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-hirofuchi"> 仮想計算機 （VM）のライブマイグレーション機能は有用であるものの，負荷バランスのため広く利用されているとは言い難い．一般的なライブマイグレーション手法は，VM のメモリをすべて転送してから実行ホストを切り替えるので時間がかかる．結果，負荷バランスにも長時間を要してしまい，過負荷状態をすぐに解消できない．そこで，我々は，迅速な実行ホストの切り替えを可能とする，新たなライブマイグレーション機構を提案する．VM メモリを実行ホスト切り替え後からオンデマンドに転送することで，約 1 秒程度で稼動ホストの変更を実現できる．既存の実装と比較して，仮想計算機モニタへの変更が少なくゲスト OS への改変が不要である点に優位性がある．プロトタイプを実装してオンデマンドなメモリアクセスが正しく動作することを確認した．</div> </blockquote>



- **グリッドRPCシステムのクラウド環境への適用**  <span onmouseover="document.getElementById('swopp09-nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp09-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2009-HPC-121*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-nakada"> Amazon EC2 に代表される HaaS 型のクラウドサービスは，ハードウェアそのものをネットワーク越しに従量課金で提供するもので，主にベンチャー企業の IT サービス基盤として広く普及しつつある．しかし，科学技術計算の分野では，現在のところあまり普及していない．この理由の一つとして，アプリケーションやミドルウェアのデプロイと設定が容易でないことが挙げられる．本稿では，クラウド側での設定をまったく行わずに，マスターワーカ型の科学技術計算を実現する機構を提案する．これまでに開発した GridRPC システム Ninf-G5 のジョブ起動機構を改良し，クラウド上のリソース制御機構を組み込んだ．この機能を用いることで，既存のマスタワーカ型の並列プログラムをまったく変更せずにクラウドを用いて大規模並列実行を行うことができる．クラウド側でのデプロイ，設定作業はまったく必要ない．このシステムを用いて簡単な評価実験を行った結果，計算量の大きいマスタワーカ型計算の HaaS 型クラウド上での実行にメリットがあることを確認した．</div> </blockquote>



- **異機種大規模クラスタ対応型ホンダグリッドシステム**  <span onmouseover="document.getElementById('auto09maekawa').style.display = 'block'"  onmouseout="document.getElementById('auto09maekawa').style.display = 'none'">[abst]</span>   
前川史人, 中田秀基
, *自動車技術 vol.63 no.6*   , pp. 58−62  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="auto09maekawa"> CAE計算環境の充実を図るべく，異機種大規模クラスタ対応型ホンダグリッドシステムを開発した．CAE計算環境が，ハイパフォーマンスCPUを積んだスーパーコンピュータからラック内にPCを何台も換装したPCクラスタへ移行しており，それに伴って急増したリソース（CPU）稼働率を向上し有効活用するために，このようなシステムの構築が望まれていた．高品質なスケジューラを基盤とし，独自の機能を開発しつつ，環境に合わせたチューニングを施すことで，CPU稼働率を向上でき，これにより，リソース補強の効果と相まって，JOB数やJOB規模が増加したにも関わらず，待ち時間を含めた平均計算時間を約1/10に短縮できた．また，同様の手法を使い，CAD用のデスクトップPCの有効活用も可能となり，PC上でのCAE計算環境も充実させた．</div> </blockquote>



- **仮想計算機遠隔マイグレーションに対応するストレージ提供手法の比較検討**  <span onmouseover="document.getElementById('hokke09-hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('hokke09-hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 小川宏高, 伊藤智, 関口智嗣
, *情報処理学会研究報告2008-HPC-119*   , pp. 73−78  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke09-hirofuchi"> 我々は，計算機センタやデータセンタにおける資源運用効率を飛躍的に向上させるため，計算資源利用を拠点横断的に最適化することを目指している．各拠点の物理資源が常に最も効率的な稼動状態となるように，仮想計算機のライブマイグレーション機能を利用して，稼動サービスを動的に拠点間で再配置する． しかし，仮想計算機の拠点間再配置においてはストレージの取り扱いが大きな課題であり，さまざまなストレージ提供技術を適切に組み合わせる必要がある． そこで本稿では，仮想計算機の動的再配置に対応したストレージ技術を比較し，それぞれの特徴を概観する． 仮想計算機移動に対応するストレージ提供手法には，大別するとストレージ共有，ミラーリングおよびストレージ再配置が存在する． 予備実験において，ミラーリングおよび先行型のストレージ再配置手法が仮想計算機のライブマイグレーションと連係動作することを確認した． またその基本的な I/O 性能を計測した． ミラーリングおよび先行型のストレージ再配置とも仮想マシンモニタと正しく連係動作することが確認できた． 書き込み処理については，ミラーリングにおいては性能低下が見られるものの，先行型のストレージ再配置においては限定的な低下にとどまった． 読み込み処理については，両者とも通常のディスクアクセスと同等の I/O 性能であった．</div> </blockquote>



- **ネットワーク帯域予約とOS仮想化機構を用いた分散アプリケーション実行環境に向けて** [[Slides](dataDir/hokke09-nakada_slides.pdf)]  <span onmouseover="document.getElementById('hokke09-nakada').style.display = 'block'"  onmouseout="document.getElementById('hokke09-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高野了成, 竹房あつ子, 工藤知宏
, *情報処理学会研究報告2008-HPC-119*   , pp. 61-66  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke09-nakada"> 複数のサイトにまたがって計算資源，ネットワーク資源を動的に確保し，アプリケーションを実行することは以下の理由により困難である．1) ネットワークの非対称性、2) サイト間の非均質性，3) 必要情報の実行時確定，4) アプリケーションのマルチホームネットワーク非対応．このため，現在のグリッド環境では既存のアプリケーションをそのまま実行することは難しい．我々は，予約ベースで計算資源とネットワーク資源を確保し，その上にごく一般的なクラスタ内の環境と類似した環境を構築するグリッドミドルウェアの構築を行っている．このグリッドミドルウェアを用いると，既存のアプリケーションを修正すること無く実行することが可能となる．本稿ではこのグリッドミドルウェアのアプリケーション実行フレームワークの設計とプロトタイプ実装について述べる．プロトタイプを用いた実行の結果，フレームワークの設計の妥当性を確認した．</div> </blockquote>



- **高品質分散実行環境のための計算・ネットワーク資源のグローバルスケジューリング手法**  <span onmouseover="document.getElementById('hokke09-takefusa').style.display = 'block'"  onmouseout="document.getElementById('hokke09-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *情報処理学会研究報告2008-HPC-119*   , pp. 55-60  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke09-takefusa"> 高品質分散実行環境の構築に際し，ユーザの要求を満たす高品質資源群を適切に確保し，かつ，グリッド上の資源群を有効活用するためには，グローバルスケジューリングが重要な課題となる．本稿では，高品質分散実行環境の構築を目的とした計算・ネットワーク資源のグローバルスケジューリング手法を提案し，シミュレーションでの評価により，その有効性を示す．提案するグローバルスケジューリング手法は，ユーザの計算機及びネットワークに関する資源要求に対して，複数資源マネージャから利用可能な資源情報を入手し，組合せ最適化問題に帰着して事前予約プランを作成する．シミュレーションによる評価により，提案手法が有効であることを示す．</div> </blockquote>



- **ライブ・ストレージマイグレーション機構の開発とその評価,**    
広渕崇宏, 中田秀基, 小川宏高, 伊藤智, 関口智嗣
, *先進的計算基盤システムシンポジウムSACSIS2009 論文集*    , 2009 



- **資源予約と連携した階層型分散資源モニタリングシステムの設計**  <span onmouseover="document.getElementById('hpc0810-takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0810-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 岡崎史裕, 工藤知宏, 田中良夫
, *情報処理学会研究報告 2008-HPC-117*   , pp. 13-18  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0810-takefusa"> グリッドとネットワークプロビジョニング技術を用いることで，複数管理組織を跨る高品質の仮想計算基盤を動的に構築・提供することが可能になった．しかしながら，分散する多様な資源で構成される仮想計算基盤の利用者が，確保した資源群の状況を把握するのは困難である．本研究では，資源予約により複数管理組織を跨る資源群を利用するユーザに対し，利用資源のモニタリング情報を収集し，各管理者の開示ポリシに基づき資源情報を提供する，階層型分散資源モニタリングシステムを提案する．提案システムでは，GridARSコアロケーションフレームワークを用いて資源予約との連携を実現する．本稿では，提案システムの設計について述べるとともに，本システムによる計算機およびネットワーク資源のモニタリング情報の収集・提供方針を述べる．</div> </blockquote>



- **異機種大規模クラスタ対応型ホンダグリッドシステム**  <span onmouseover="document.getElementById('honda08nakada').style.display = 'block'"  onmouseout="document.getElementById('honda08nakada').style.display = 'none'">[abst]</span>   
前川史人, 山本義弘, 中田秀基
, *Honda R&amp;D Technical Review Vol.20 No.2*   , pp. 61-65  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="honda08nakada"> CAE計算環境の充実を図るべく異機種大規模クラスタ対応型ホンダグリッドシステムを開発した。CAE計算環境が、ハイパフォーマンスCPUを積んだスーパーコンピュータから、ラック内にPCを何台も換装したPCクラスタへ移行しており、それに伴って急増したリソース（CPU)稼働率を向上し有効活用するために、このようなシステムの構築が望まれていた。高品質なスケジューラを基盤とし、独自の機能を開発しつつ、環境に合わせたチューニングを施すことで、CPU稼働率を向上でき、これにより、リソース補強の効果と相まって、JOB数やJOB規模が増加したにもかかわらず、待ち時間を含めたた計算時間を約1/10に短縮できた。また、同様の手法を使い、CAD用のデスクトップPCの有効活用も可能となり、PC上でのCAE計算環境も充実させた。</div> </blockquote>



- **仮想クラスタのステートレス化のためのRocks 5ディスクレス化機構** [[Paper](dataDir/swopp08ogawa.pdf)] [[Slides](dataDir/swopp08ogawa_slides.pdf)]  <span onmouseover="document.getElementById('swopp08ogawa').style.display = 'block'"  onmouseout="document.getElementById('swopp08ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 広渕崇宏, 伊藤智, 関口智嗣
, *情報処理学会研究報告2008−HPC-116*   , pp. 31-36  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp08ogawa"> 計算機資源の効率的な運用の方法として仮想化が注目されており，仮想的なクラスタを管理するさまざまなシステムが提案されている．我々も 2005 年度よりユーザからの依頼に応じて予約ベースで仮想クラスタを構築・提供するサービスを実現する仮想クラスタ管理システムGriVonを研究・開発している．このような仮想クラスタ構築技術でとりわけ重要なのは，仮想クラスタで利用するストレージに求められるさまざまな性質（性能，スケールアウトの容易さ，管理の容易さ，計算機資源の集約を動的に行うためのライブマイグレーション，耐故障性など）をいかに実現するか，である．我々はこうした課題を解決することを目的として，本年 5 月にリリースされた NPACI Rocks version 5 にディスクレスブート化機構を実現した．本稿ではその詳細を述べる．GriVon の次期バージョンでは，この機構を用いてより柔軟な仮想ストレージ管理を実現する予定である．</div> </blockquote>



- **仮想クラスタ遠隔ライブマイグレーションにおけるストレージアクセス最適化機構** [[Paper](dataDir/swopp08hirofuchi.pdf)] [[Slides](dataDir/swopp08hirofuchi_slides.pdf)]  <span onmouseover="document.getElementById('swopp08hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('swopp08hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 小川宏高, 中田 秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2008−HPC-116*   , pp. 19-24  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp08hirofuchi"> 計算機センタやデータセンタの計算機資源の運用効率を高めるために, 仮想計算機とそのライブマイグレーション技術が注目されている. 仮想計算機を遠隔拠点に対して動的に再配置できれば, 資源運用の柔軟性向上や省電力化に寄与すると考えられる. しかし既存のライブマイグレーション技術のみでは, 複数拠点にまたがる動的な再配置を効率的・実用的に行うことができない. 本研究では仮想クラスタの遠隔マイグレーションを可能とするためにそのストレージアクセスの最適化機構を提案する. ライブマイグレーションにともなって仮想計算機のストレージも透過的に再配置することで, 周辺機器を含めた仮想計算機の実行環境全体の移動を可能にする. そして移動前後の性能低下を最小限に抑えることを目指す. プロトタイプ実装を用いて予備的な評価実験を行い, 提案手法の基本的な有効性を確認した.</div> </blockquote>



- **オーバーレイスケジューラJojo3 のグリッドRPC への適用** [[Paper](dataDir/swopp08nakada.pdf)]  <span onmouseover="document.getElementById('swopp08nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp08nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2008−HPC-116*   , pp. 91-96  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp08nakada"> 複数サイトにまたがる大量の計算資源を用いた計算が, 一般ユーザにとっても現実のものとなりつつある.我々は, このような環境で稼働するアプリケーションレベルスケジューラを容易に記述できる環境として, オーバーレイスケジューラJojo3を提案している. Jojo3はさまざまな環境上にオーバレイするレイヤとして機能し, プロセスの起動, およびプロセス間の通信機能を提供する.我々は, Jojo3の有用性を検証するため, GridRPC 実装の一つであるNinf-G5への適用を行った. Ninf-G5はリモート実行モジュールの起動モジュールと, クライアントとリモート実行モジュール間の通信プロキシモジュールを独立したプロセスとしてコアモジュールの外部に持つ設計となっている. 既存のモジュールをベースにJojo3を用いるように修正した結果, 数十行から数百行程度の比較的軽微な修正によって, Jojo3への適用が可能であることが確認できた. これによって, Jojo3の提供するAPIの機能と記述力が十分であることが確認できた.本稿では, この過程で実装した, Python言語によるJojo3クライアントライブラリを合わせて紹介する.</div> </blockquote>



- **オーバレイスケジューラ Jojo3 の提案** [[Paper](dataDir/hpc0803nakada.pdf)] [[Slides](dataDir/hpc0803nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0803nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0803nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-114*   , pp. 169-174  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0803nakada"> グリッド技術およびクラスタ技術の発展によって， 個々のユーザがアクセスできる計算機の 総量は爆発的に増大した．しかしこれらの計算機を同時に利用する アプリケーションプログラムを記述することは困難であり， 膨大な計算資源を有効に活用できているアプリケーションは限定されている．アプリケーションプログラムの記述が困難な理由の一つは， 環境の不均質性および非対称性にある． 計算機資源は，それぞれ異なるバッチスケジューリングシステム およびグリッドミドルウェアで管理されており不均質 ネットワークの接続性には非対称性があり，ノード間通信も必ず 可能なわけではない．本稿では，この不均質性と非対称性をアプリケーションプログラマから隠蔽する オーバレイスケジューラを提案し， その1実装であるJojo3の設計と実装について述べる． オーバレイスケジューラは，グリッドミドルウェアおよび バッチスケジューリングシステムで起動され， 均質なインターフェイスをアプリケーションプログラムに 対して提供する． アプリケーションプログラマは，オーバレイスケジューラを 利用することで，比較的容易にアプリケーションを記述することができる．</div> </blockquote>



- **複数サイトにまたがる仮想クラスタの管理機構** [[Paper](dataDir/hpcs08poster_nakada.pdf)] [[Slides](dataDir/hpcs08poster_nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpcs08poster_nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcs08poster_nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 広渕崇宏, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *HPCS 2007*   , pp. 64  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs08poster_nakada"> 計算機サービスを提供する基盤システムの管理コストを低減する目的で仮想化技術を用いることが一般的となりつつある．われわれは，VMware Serverを用いた計算機の仮想化のみならず，VLANを用いたネットワークの仮想化，iSCSIとLVMを用いたストレージの仮想化を行うことで，クラスタ全体を仮想化した．さらにクラスタデプロイツールRocksを用いて，クラスタ管理ソフトウェアや，運用ソフトウェアを自動的にインストール，設定する仮想クラスタ管理システムを構築した．このような仮想クラスタは管理コストの低減に大きく寄与することが期待できるが，単一サイトの資源のみを用いるシステムでは運用の自由度に限界がある．この限界を取り除くためには，複数の物理的に隔絶したサイトの資源を集合的にもちいて，その上に仮想クラスタを構築する技術が必要となる．我々は，ソフトウェアによるイーサネットVPNをVLANと併用することで，仮想的にフラットな構造を持つネットワークを仮想クラスタに提供し，Rocksを用いたインストールが可能であることを確認した．さらに，仮想クラスタ管理システムを拡張し，複数のサイトからなる仮想クラスタの管理を行うことを可能にしたので報告する．</div> </blockquote>



- **SlothLib/EaRDB : マイサーチエンジン開発環境支援**    
大島裕明, 中村聡史, 赤星祐平, 中田秀基, 喜連川優, 田中克己
, *情報処理 Vol.49 No.8*   , pp. 927-930  , 2008 



- **PluS予約機構のCondorへの適用** [[Paper](dataDir/hpc0712nakada.pdf)] [[Slides](dataDir/hpc0712nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0712nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0712nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-113*   , pp. 43-48  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0712nakada"> 複数資源の同時確保には，各資源が事前予約機構を備えていなければならない．我々は既存のローカルスケジューラに対して事前予約機構を付加するPluS事前予約機構を開発している．PluS事前予約機構は，2つの動作モードを持つが，そのうちの1つであるキュー制御 動作モードは，ローカルスケジューラが特定の機能を持つことを前提に， モジュール構成を改変すること無く予約機構を付加することができる． このキュー制御動作モードは，特定のローカルスケジューラに依存しないよう 注意深く設計されているが，これまでの実際の適用例は，Sun Grid Engineのみで キュー制御動作モードの汎用性は立証されていなかった．本稿では，キュー制御動作モードの汎用性を立証するべく，Sun Grid Engineとは全く異なる基本設計に基づくローカルスケジューラ Condorに対してPluSの適用を行った．その結果，わずかなコード量でCondorへの適応が可能なことを確認した.</div> </blockquote>



- **グリッドRPCシステムNinf-Gの可搬性および適応性の改善** [[Paper](dataDir/hpc0709nakada.pdf)] [[Slides](dataDir/hpc0709nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0709nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0709nakada').style.display = 'none'">[abst]</span>   
中田秀基, 朝生正人, 谷村勇輔, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-112*   , pp. 37-42  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0709nakada"> Ninf-Gはグリッド上でRPC(Remote Procedure Call) を実現するシステムである．従来のNinf-Gは，さまざまなジョブ起動機構に対応することができるが，通信機構にGlobus Toolkit のGlobus-IOを用いるため，常にGlobus Toolkit とリンクする必要がある．このため，1)Globus Toolkit のインストールがユーザに対する導入障壁となる，2)Globus Toolkit に依存するため可搬性が限定される，3)Globus-IO 以外の通信レイヤを利用することができない，といった問題がある．現在実装中のNinf-G Ver.5 では，これらの問題点を解決するために，リモート通信部を通信プロキシと呼ぶ独立した別プロセスとすることで，コア部分を外部ライブラリ非依存とした．これによって，ユーザに対する導入障壁が解消し，可搬性が向上すると同時に，他の通信レイヤの利用が可能となる．さらに，通信プロキシを利用することで，クライアントとリモート実行ノードが直接通信できない環境においても利用することが可能になる．本稿ではこのNinf-G Ver.5 の設計について詳述する．さらに，通信プロキシを導入することで予想されるオーバヘッドを見積もるための予備的評価を行う．評価の結果，別プロセス化によるオーバヘッドは無視できないものの，得られるメリットを勘案すれば受け入
れることができる範囲であることがわかった．</div> </blockquote>



- **ステートレス仮想クラスタの構想**    
小川宏高, 中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 関口智嗣
, *情報処理学会研究報告2007-HPC-112*   , pp. 43-48  , 2007 



- **SOAの新しい標準技術としてのSCAの登場**    
丸山不二夫, 中田秀基
, *情報処理 Vol.48 No.9*   , pp. 1033-1037  , 2007 



- **Globus Toolkit 4におけるWSRFサービス記述のアノテーションによる補助** [[Paper](dataDir/hpc0708nakada.pdf)] [[Slides](dataDir/hpc0708nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0708nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0708nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 岸本誠, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-111*   , pp. 291-296  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0708nakada"> グリッド上のサービスを記述するための枠組として、Web サービス規格の一つである Web Services Resource Framework (ＷSRF) がある。Globus Toolkit 4 は、ＷSRF を用いてサービスを記述するためのツールの一つで、多くのプロジェクトで用いられているが、記述は煩雑で十分に容易であるとは言いがたい。我々は、 Globus Toolkit 4 による WSRＦ 記述を補助するツールを作成した。この補助ツールを用いると、ユーザは通常のオブジェクト記述にアノテーションを適切に付加するだけで、煩雑な Web Services Description Language (WSDL) によるインターフェイス記述をすることなく、WSRF に基づくサービスを記述することができる。さらに、通信対象となるデータのスキーマが独立に規定されている場合にも、対処することができる。簡単なサービ スをこの補助ツールを用いて記述した結果、大幅に記述量を削減できることを確認した。</div> </blockquote>



- **WSRFに基づく情報サービスのXACMLによるアクセス制御** [[Paper](dataDir/hpc0708takefusa.pdf)]  <span onmouseover="document.getElementById('hpc0708takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0708takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-111*   , pp. 285-290  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0708takefusa"> グリッドでは資源やジョブに関する情報の提供は重要な機能のひとつであり、クラスタ監視ツールの Ganglia や Globus Toolkit 4 の MDS4 などの情報サービスが実現されている。しかしながら、複数の仮想組織に属するユーザが資源を共有する場合、全情報をすべてのユーザに開示することは好ましくない。本研究では、認可モデルとポリシ記述言語の標準として提案されている XACML を用い、サイト毎に情報開示ポリシを定義して、各ユーザからの細粒度の情報アクセス制御を可能にする、WSRF に基づく情報サービスシステムを提案する。本研究で開発したプロトタイプでの予備実験から、(1) 情報収集に関するオーバヘッドは WSRF/GSI によるもので占められ、認可決定の時間は無視できる、(2) 複数サイトから情報収集する場合も、手続きを並行して行うとその所要時間は許容できる、(3) XACML のポリシ数が多い場合も、判定に要する時間は全体の処理時間に対して十分小さいことが確認できた。</div> </blockquote>



- **GEO Gridの構築に向けたストレージシステムの予備評価** [[Paper](dataDir/hpc0708tanimura.pdf)]  <span onmouseover="document.getElementById('hpc0708tanimura').style.display = 'block'"  onmouseout="document.getElementById('hpc0708tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 山本直孝, 石橋拓也, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-111*   , pp. 279-284  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0708tanimura"> 衛星観測した数百 TB のデータをオンラインのハードディスクに保管し、必要に応じていつでも参照できる環境の整備が求められている。そのバックエンドとなるストレージは、大規模データの保存とそれらの高速処理を実現するシステムでなくてはならない。そのようなシステムを検討するために、ASTER 衛星データとそのアプリケーションを例に、Ｇfarm と Lustre を用いて同等のシステムを構築した場合のデータアクセスの性能と運用方法を比較した。性能面では ASTER アプリケーションのデータ処理を解析した上で、各ストレージシステムでのアプリケーションの実行性能を比較した。運用面では故障に対する備え方、メンテナンスの作業内容や課題を比較した。これらの調査により、より大規模な衛星観測データの保存システム、あるいは類似アプリケーションのためのストレージを構築するための指針を得た。</div> </blockquote>



- **経路が動的に接続/解放されるネットワークにおけるユーザ単位の経路切替手法** [[Paper](dataDir/hpc0708okazaki.pdf)]  <span onmouseover="document.getElementById('hpc0708okazaki').style.display = 'block'"  onmouseout="document.getElementById('hpc0708okazaki').style.display = 'none'">[abst]</span>   
岡崎 史裕, 工藤知宏, 中田秀基, 竹房あつ子
, *情報処理学会研究報告2007-HPC-111*   , pp. 255-260  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0708okazaki"> 同一宛先との通信に複数の経路がある IP ネットワークでは、実際に通信に使用する経路を選択する仕組みが必要である。例えば、遠隔の計算機間の帯域を動的に確保して並列処理を行う場合や､ VLAN を用いてレイヤ 2 ネットワーク上に複数の経路を実現する VLAN ルーティング法では、ユーザごとに経路を切替えることが有効であると考えられる。そこで本稿では、これを実現する手法として、Linux の netfilter と iproute2 を用いる方法と、ロードバランサ装置である BIG-IP を用いる方法を比較検討する。また、これらの切替手法が並列計算アプリケーションの性能面に与える影響を調べるため、NPB3.2 による性能評価を行う。</div> </blockquote>



- **複数サイトにまたがる仮想クラスタの構築** [[Paper](dataDir/hpc0708hirofuchi.pdf)]  <span onmouseover="document.getElementById('hpc0708hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('hpc0708hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 谷村勇輔, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-111*   , pp. 231-236  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0708hirofuchi"> 計算機資源の効率的かつ柔軟な運用を実現する手法として、仮想クラスタ技術が注目されている。しかし既存システムは単一サイトの計算機資源のみを仮想クラ スタの対象とする。構築可能な仮想クラスタは単一サイト内に存在する計算機資源によって制限され運用の柔軟性に乏しい。そこで、我々は複数サイトをまたい で横断的に仮想クラスタを構築可能な管理システムの実現に取り組んでいる。複数サイトにわたって構築された仮想クラスタにおいても、単一実行環境としての 透過性やシステムの導入や運用における容易性が実現されなければならない。本論文では、インターネットを介したイーサネット VPN によって単一のネットワークセグメントを仮想クラスタに対して提供することを提案する。予備的な評価実験においては、イーサネット VPN で結ばれたサイト間において仮想クラスタの構築が可能であることを確認した。</div> </blockquote>



- **事前予約機構のポリシ記述による制御** [[Paper](dataDir/hpc0706nakada.pdf)]  <span onmouseover="document.getElementById('hpc0706nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0706nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-110*   , pp. 19-24  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0706nakada"> グリッド上の複数サイトにまたがるジョブの実行を実現する方法として，事前予約による同時確保がある．事前予約を実現するローカルスケジューラは，いくつか提案されているものの，事前予約ジョブと通常のジョブを共存させるための適切なポリシは明らかになっていない．われわれは，事前予約ジョブと通常ジョブ間のポリシは，各サイトのローカルスケジューラに内蔵されるべきではなく，管理者が設定するべき事項であると考え，実装中の{\plus}事前予約機構に，管理者によるポリシ記述機能を組み込んだ．ポリシ記述には，Condor プロジェクトで用いられているClassAdを用いた．我々は，1)ClassAd による記述力は管理ポリシを記述するのに十分であること，2)PluSの提供する情報により有効な管理ポリシが記述できること，3)ClassAd によるポリシ解釈のオーバヘッドは十分小さいことを確認した．</div> </blockquote>



- **NAREGIミドルウェアβ-gLite 間における相互ジョブ起動実験** [[Paper](dataDir/hpc0703nakada.pdf)] [[Slides](dataDir/hpc0703nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0703nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0703nakada').style.display = 'none'">[abst]</span>   
中田秀基, 佐藤仁, 佐賀一繁, 畑中正行, 佐伯裕治, 松岡聡
, *情報処理学会研究報告2007-HPC-109*   , pp. 269-274  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0703nakada"> グリッド標準化団体OGFでは， グリッドミドルウェア間の相互運用技術を確立するために． GIN(Grid Interoperation Now) と呼ばれるコミュニティグループの活動が行われている． この活動の一環として， NAREGI のNAREGI ミドルウェアβ とEGEE (Enabling Grids for E-Science in Europe)のミドルウェアgLite の間でジョブ起動およびデータ転送に関する相互運用実験を行い， NAREGIミドルウェアβ からgLite， およびgLite からNAREGI ミドルウェアβ へのジョブ起動を実現した．前者はgLite の個々の計算資源(Compute Element) を擬似的にNAREGI ミドルウェアβ の資源として取り込み， NAREGI ミドルウェアβ のスケジューラの配下に置くことで実現した． 後者は，NAREGI ミドルウェアβ 全体をひとつの計算資源としてgLite に対して公開し， gLite 側で明示的にNAREGI ミドルウェアβ を選択する方式で実現した． 実験の結果， 以下を確認することができた．1) 証明書や仮想組織管理のレイヤでは相互運用性に問題はない， 2) 情報サービスのレイヤでも相違が吸収できる， 3) その情報を用いて相互のジョブ起動が可能である，</div> </blockquote>



- **ミドルウェア連携による計算・ネットワーク資源の日米間グリッドコアロケーション実験**  <span onmouseover="document.getElementById('hpc0703takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0703takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 林通秋, 築島幸男, 岡本修一, 柳田誠也, 宮本崇弘, 平野章, 鮫島康則, 中田秀基, 谷口篤, 工藤知宏
, *情報処理学会研究報告2007-HPC-109*   , pp. 281-286  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0703takefusa"> グリッドでは，計算資源に関する管理・利用技術は成熟しつつあるものの，ネットワークの帯域を資源として管理する技術は実験段階にあり，特に異なるネットワークドメインに属する拠点間の帯域を自動的に提供するのは非常に困難である．また，グリッドコアロケーションシステムは複数開発されているが，異なるシステム間で連携し，それぞれの管理ドメインの計算・ネットワーク資源を横断的に利用する試みはこれまでない．我々は，ネットワークの帯域を予約するためのインタフェースGNS-WSI を規定することを目的としたG-lambda  プロジェクトを推進しており，複数ドメインに跨るネットワーク資源を確保することを考慮し，新たにGNS-WSI2を規定した．G-lambda が前提とするアーキテクチャでは，グリッド資源スケジューラが複数のネットワークドメインおよび計算資源の資源管理マネージャと連携することにより，ドメインを超えた資源のコアロケーションが可能になる．また，本報告では，米国の Enlightened Computing プロジェクトと共同で行った，ネットワークと計算機資源の同時事前予約実験について述べる．本実験では，日米の複数ドメインに跨る計算資源およびネットワーク資源をミドルウェア連携により事前予約で確保し，動的に構築したグリッド環境上でアプリケーションを実行することに成功した．</div> </blockquote>



- **仮想クラスタに対するIPストレージの提供方法の比較**  <span onmouseover="document.getElementById('hpc0703tanimura').style.display = 'block'"  onmouseout="document.getElementById('hpc0703tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 小川宏高, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-109*   , pp. 109-114  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0703tanimura"> ユーティリティ・コンピューティングの1 つとして，事前予約に基づいて仮想クラスタを貸し出すシステムの提案が行われている．貸し出す仮想クラスタでは計算機資源だけでなく，ストレージやネットワークを含めた仮想環境を提供することを目指しており，ストレージの仮想化とそれを仮想クラスタの各ノードへ提供する方法を検討する必要がある．本論文では，Xen によって構築した仮想計算機への仮想ストレージとして，仮想計算機をサービスする実計算機のローカルディスクを提供する方法に加え，NFS やiSCSI を用いて遠隔で管理されたディスクスペースを提供する方法を検討した．そして，データインテンシブなアクセスとメタデータインテンシブなアクセスに対するそれらの性能の違いを明らかにし，仮想クラスタでの利用に向けた課題を明らかにした．</div> </blockquote>



- **クラスタ構築システムRocksを用いた仮想クラスタの構築** [[Paper](dataDir/hpcs07poster_nakada.pdf)] [[Slides](dataDir/hpcs07poster_nakada_slide.pdf)]    
中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *HPCS 2007 2007年ハイパフォーマンスコンピューティングと計算科学シンポジウム論文集*   , pp. 72  , 2007 



- **クラスタ構築システムRocksを用いた仮想クラスタの構築** [[Paper](dataDir/comsys06poster_nakada.pdf)] [[Slides](dataDir/comsys06poster_nakada_slide.pdf)]    
中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *コンピュータシステムシンポジウム, ポスター*    , 2006 



- **グリッドRPCシステムNinf-Gのリモート起動手法の改良** [[Paper](dataDir/hpc0610nakada.pdf)]  <span onmouseover="document.getElementById('hpc0610nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0610nakada').style.display = 'none'">[abst]</span>   
中田秀基, 朝生正人, 谷村勇輔, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-10８*   , pp. 43-47  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0610nakada"> グリッド上でRPC(Remote Procedure Call) を実現するGridRPCは，グリッド上のプログラミングモデルとして有望なマスタ・ワーカ計算をサポートするのに適した計算機構である．われわれはGridRPC APIを実装したプログラミング機構としてNinf-Gを設計，実装している．Ninf-Gは基本的にGlobus Toolkitを用いて実装されているが，ジョブの起動機構をInvoke Serverと呼ぶ外部モジュールとしてプラグインすることで，多様な実行環境に柔軟に適応することができる．Invoke Server機構の設計に関しては，すでに別稿で報告している．われわれは，Globus Toolkit 4 WS GRAM, Unicore, Condor，ssh，NAREGI ミドルウェアβに対してそれぞれInvoke Serverを実装した．また，Invoke Server機構のオーバヘッドを評価するためにジョブ起動時間を測定した．その結果，Invoke Serverによって導入されるオーバヘッドはジョブ起動機構自身のオーバヘッドと比較すると十分小さいことがわかった．本稿では，より適応範囲を広げるために計画されている，より高度なモジュール化に関しても議論する．</div> </blockquote>



- **グリッドとSOAからみるWebサービス標準技術 : グリッドとSOAの意外な関係**    
丸山不二夫, 中田秀基
, *情報処理 Vol.47 No.9*    , 2006 



- **グローバルスケジューリングのためのローカル計算資源管理機構**  <span onmouseover="document.getElementById('swopp0608nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp0608nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 岸本誠, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-107*   , pp. 55-60  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp0608nakada"> グリッド上で資源の同時確保を実現する方法のひとつとして事前予約を行う方法がある．複数資源の同時予約操作は本質的に分散トランザクションであり，操作失敗時の挙動を保障するためには，スケジューラとローカル資源管理機構の間で適切なプロトコルを用いる必要があり，ローカル資源管理機構がそのプロトコルに対応していなければならない．また，ローカル資源管理機構内部の予約管理機構もプロトコルに対応する必要がある．われわれは，プロトコルとして分散トランザクションで一般に用いられる2相コミットプロトコルを採用し，これを可能にするべく，計算資源上のローカル資源管理機構の予約インターフェイスを設計・実装した．予約インターフェイスはWSRF(Web Services Resource Framework)を基盤プロトコルとし，Globus Toolkit 4 を用いて実装されている．さらにローカル資源管理機構内部で使用する予約管理機構として，TORQUE および GridEngineと協調動作することのできるPluS予約管理機構を改良し，2相コミットの機構を組み込んだ．</div> </blockquote>



- **Rocksを用いた仮想クラスタ構築システム** [[Paper](dataDir/hpc0606nakada.pdf)] [[Slides](dataDir/hpc0606nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0606nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0606nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 横井 威, 関口 智嗣
, *情報処理学会研究報告2006-HPC-106*   , pp. 49-54  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0606nakada"> アプリケーションの動的配備を実現するための一手法として，実行環境であるOSも含めて配備を行う方法がある．この機能を実現する方法としては専用のハードウェアと管理ソフトウェアを使用する方法があるが，高価であり一般的ではない．われわれは，仮想計算機と，OSインストールシステムNPACI Rocksを用いて，安価な通常のPC上でOSとアプリケーションを一体として動的に配備するシステムを構築している．ユーザは，Rocks のRollパッケージの形で使用するアプリケーションを指定する．システムは計算機クラスタを一体として管理し，ユーザからのリクエストに応じて実計算機をユーザに割り当て，実計算機上の仮想計算機にOSとアプリケーションを配備してユーザに提供する．本稿では本システムの構想と設計，現在までに実装されたプロトタイプに関して述べる．</div> </blockquote>



- **グリッドにおける計算資源 と光パスネットワーク資源のコアロケーション実験**    
竹房あつ子, 林通秋, 長津尚英, 中田秀基, 工藤知宏, 宮本崇弘, 大谷朋広, 田中英明, 鮫島康則, 今宿亙, 神野正彦, 滝川好比郎, 岡本修一, 田中良夫, 関口智嗣
, *先進的計算基盤システムシンポジウムSACSIS2006 論文集（ポスター）*   , pp. 234-235  , 2006 



- **グリッドアプリケーション のためのGMPLSネットワーク資源の管理制御**    
林通秋, 宮本崇弘, 大谷朋広, 田中英明, 竹房あつ子, 中田秀基, 工藤知宏, 鮫島康則, 岡本修一
, *電子通信処理学会 2006総合大会講演論文集*    , 2006 



- **グリッド上における仮想計算機を用いた高速なジョブ実行環境構築システム** [[Paper](dataDir/hpc0603yamagata.pdf)] [[Slides](dataDir/hpc0603yamagata_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603yamagata').style.display = 'block'"  onmouseout="document.getElementById('hpc0603yamagata').style.display = 'none'">[abst]</span>   
山形育平, 高宮安仁, 中田秀基, 松岡聡
, *情報処理学会研究報告2006-HPC-105*   , pp. 127-132  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603yamagata"> グリッド上で実行されるジョブの多様化に伴い、ジョブが要求する実行環境も多様化しつつある．そこで我々は仮想計算機と自動設定・インストールツールを用いて投入されるジョブごとに専用の仮想実行環境を動的に提供するシステムORE Grid を開発している．このシステムを使用することにより約173 秒で16 台のBLAST 実行環境を動的に構築することが可能であるが，今後のグリッドの応用領域の広がりを考慮すると構築時間を短縮することも必要である．この構築時間短縮のため一度構築した仮想計算機環境を保存，再利用するキャッシュサーバーを作成し，ORE Grid に組み込むことを提案する．このキャッシュを使用することによりパッケージインストール時に起こるパッケージサーバーへの負荷集中を回避できる．このシステムを実装し，従来のシステムとの比較を行ったところ約12%の構築時間削減効果が見られた．</div> </blockquote>



- **光ネットワーク環境におけるMPI集団通信** [[Paper](dataDir/hpc0603takizawa.pdf)] [[Slides](dataDir/hpc0603takizawa_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603takizawa').style.display = 'block'"  onmouseout="document.getElementById('hpc0603takizawa').style.display = 'none'">[abst]</span>   
滝澤真一朗, 松岡　聡, 中田秀基
, *情報処理学会研究報告2006-HPC-105*   , pp. 193-198  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603takizawa"> 光バーストスイッチングネットワークでは、通信を行う前に光パスコネクションを確立し、通信終了後にはコネクションを解放しなければならない。コネクション確立・解放コストは合計して平均10msほど要する。そのため、MPI アプリケーション等、コンピュートインテンシブなアプリケーションで集団通信を実行する際にはコネクション確立・解放のオーバーヘッドが顕著になる。そこで、MPI集団通信において通信発生とは独立してコネクション確立・解放を行うことにより、オーバーヘッドを削減する手法を提案する。本手法ではノードの持つポート数に応じてコネクション確立・解放方法を変え、同時コネクション確立を行い高速実行を実現する。本手法と単純に通信のたびにコネクションを張る方法とで、数値解析によるアルゴリズム単体の比較、およびシミュレータを用いて仮想的に実アプリケーションを実行した場合の比較を行い、本手法の優位性を示した。</div> </blockquote>



- **事前予約機能を持つローカルスケジューリングシステムの設計と実装** [[Paper](dataDir/hpc0603nakada.pdf)] [[Slides](dataDir/hpc0603nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0603nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 岸本誠, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-105*   , pp. 217-222  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603nakada"> グリッド上で複数の資源を同時に確保(コアロケーション) するには，各サイトにおける事前予約が不可欠である．現在計算資源の多くでは，プライオリティとFirst Come First Served を組み合わせたスケジューリングポリシが用いられているが，このスケジューリングポリシと事前予約をどのように組み合わせるべきかに関しては，明らかになっていない．われわれは，この問題を検討する研究環境を整備することを目的とし，1) OpenPBS の亜種であるTORQUE のスケジューラモジュールを記述するためのAPI を整備し，2) これを用いて事前予約機能を持つスケジューラモジュールを実装した．さらにWSRF を用いた外部インターフェイスを実装し，Globus Toolkit Ver.4 のGRAMと連動したグリッド環境での予約と実行を実現した．</div> </blockquote>



- **大規模環境向け情報共有手法を用いた分散ジョブスケジューリングシステム** [[Paper](dataDir/hpc0603umeda.pdf)] [[Slides](dataDir/hpc0603umeda_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603umeda').style.display = 'block'"  onmouseout="document.getElementById('hpc0603umeda').style.display = 'none'">[abst]</span>   
梅田典宏, 中田秀基, 松岡　聡
, *情報処理学会研究報告2006-HPC-105*   , pp. 223-228  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603umeda"> グリッド環境では、ジョブスケジューリングシステムによって分散した計算機を統合した資源として扱うことを可能にしている。しかし既存のシステムは、スケジューリングに必要な資源情報収集および実行ジョブと資源のマッチングを少数の計算機で行うことによる単一故障点の存在と資源・投入ジョブ数の増加に対するスケーラビリティの欠如という問題を抱えている。我々は、大規模環境向けの通信手法を用いて資源情報を共有し、耐故障性と資源数の増加に対しスケーラブルな分散ジョブスケジューリングシステムを提案する。シミュレータを用いた従来システムとの比較評価によって、本提案手法が大規模環境下でより効率的なスケジューリングを可能にすることを示す。</div> </blockquote>



- **レプリカ管理システムを利用したデータインテンシブアプリケーション向けスケジューリングシステム** [[Paper](dataDir/hpc0603machida.pdf)] [[Slides](dataDir/hpc0603machida_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603machida').style.display = 'block'"  onmouseout="document.getElementById('hpc0603machida').style.display = 'none'">[abst]</span>   
町田悠哉, 滝澤真一朗, 中田秀基, 松岡　聡
, *情報処理学会研究報告2006-HPC-105*   , pp. 229-234  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603machida"> グリッド環境において既存のスケジューリングシステムはデータ入出力を共有ファイルシステムや単純なステージング機構を利用して行っている。しかしこれらの手法ではデータ保持ノードはアクセス集中によりパフォーマンスが低下、そして最悪の場合にはハングアップしてしまう。またユーザが同一のデータセットを利用する多数のタスクからなるジョブを実行した場合、スケジューリング後に毎回同じデータをステージングするのは非効率である。そこで本研究ではレプリカ管理とジョブスケジューリングをタイトに結合し、データを効率的に再利用する。プロトタイプシステムとして複数ノードへO(1) の転送時間でデータを複製できるスケーラブルなレプリカ管理システムを利用し、効率的なファイル転送を提供するとともにデータ転送と計算を同時実行するような効率的なスケジューリングを可能にした。評価実験によりプロトタイプシステム上で従来手法よりも効率的なジョブ実行、スループット向上が達成されたことを確認した。</div> </blockquote>



- **グリッドにおける計算資源と光パスネットワーク資源のコアロケーション実験** [[Paper](dataDir/hpc0603takefusa.pdf)] [[Slides](dataDir/hpc0603takefusa_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0603takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 林通秋, 長津尚英, 中田秀基, 工藤知宏, 宮本崇弘, 大谷朋広, 田中英明, 鮫島康則, 今宿亙, 神野正彦, 滝川好比郎, 岡本修一, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-105*   , pp. 121-126  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603takefusa"> 産業技術総合研究所，KDDI 研究所，日本電信電話は共同で，ネットワーク資源の事前予約を行うための標準ウェブサービスインタフェースを定めるG-lambda プロジェクトを推進している．このインタフェースの有効性を確認するために，計算資源と光パスネットワーク資源を事前予約によりコアロケーションする実験を，情報通信研究機構の協力を得て行った．本稿では，前提とするコアロケーションシステムモデル，G-lambda プロジェクトにおけるグリッドでのネットワークサービスインタフェースの規定，産総研が開発した計算・ネットワーク資源を同時予約するスケジューラの概要，KDDI 研が開発したGMPLS で制御される光パスネットワークの提供機構の概要と，これらにより実現されたコアロケーションシステムプロトタイプのiGrid2005 での実証実験について報告する．</div> </blockquote>



- **カスタマイズ可能な仮想計算機上におけるグリッドでのジョブ実行** [[Paper](dataDir/swopp05yamagata.pdf)]  <span onmouseover="document.getElementById('swopp05yamagata').style.display = 'block'"  onmouseout="document.getElementById('swopp05yamagata').style.display = 'none'">[abst]</span>   
山形育平, 青木孝文, 高宮安仁, 中田秀基, 松岡聡
, *電子情報通信学会 CPSY 研究会報告*    , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp05yamagata"> 近年グリッドでは、ユーザーが投入するジョブが多様化しており、それに伴いユーザーの求める実行環境 も多様化している。しかし、すべてのサイトでユーザーの求める実行環境が提供されているとは限らない。そこで我々は仮想計算機とユーザーがカスタマイズ可 能なインストレーション機構を組み合わせ、ユーザーがジョブ実行環境を容易に構築できるシステムを提案する。本システムではGRAM 経由で、カスタマイズ可能なインストレーション機構であるLucie [5] を呼び出し、これを用いて仮想計算機の構築を行い、その計算機上でジョブを実行することができる。このシステムを評価した結果、既存の計算機環境に影響を 与えないジョブの実行が可能であった。環境構築時間も一般的なグリッドジョブの実行時間と比べて許容範囲であることを確認し、本研究の有効性を確認した。</div> </blockquote>



- **レプリカ管理システムを利用したデータインテンシブアプリケーション向けスケジューリングシステム** [[Paper](dataDir/swopp05machida.pdf)]  <span onmouseover="document.getElementById('swopp05machida').style.display = 'block'"  onmouseout="document.getElementById('swopp05machida').style.display = 'none'">[abst]</span>   
町田悠哉, 滝澤真一朗, 松岡聡, 中田秀基
, *電子情報通信学会 CPSY 研究会報告*    , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp05machida"> グリッド環境において既存のスケジューリングシステムはデータ入出力を共有ファイルシステムや単純なステージング機構を利用して行っている。しかしこれらの手法ではデータ保持ノードはアクセス集中によりパフォーマンスが低下、そして最悪の場合にはハングアップしてしまう。またユーザが同一のデータセットを利用する多数のタスクからなるジョブを実行した場合、スケジューリング後に毎回同じデータをステージングするのは非効率である。そこで本研究では複数ノードへO(1) の転送時間でデータを複製できるスケーラブルなレプリカ管理システムをステージング機構として利用し、レプリカを再利用するような効率的なスケジューリングを可能とするシステムを提案する。プロトタイプシステム上でサンプルアプリケーションを実行したところ従来の共有ファイルシステムやステージング機構を利用したものより高い性能が確認できた。</div> </blockquote>



- **仮想計算機を用いて負荷分散を行うMPI実行環境** [[Paper](dataDir/swopp05tatezono.pdf)]  <span onmouseover="document.getElementById('swopp05tatezono').style.display = 'block'"  onmouseout="document.getElementById('swopp05tatezono').style.display = 'none'">[abst]</span>   
立薗真樹, 松岡聡, 中田秀基
, *電子情報通信学会 CPSY 研究会報告*    , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp05tatezono"> 長時間に及ぶ実行や遊休計算機上での実行などにおいては、各計算機間の負荷分散が重要である。我々は 仮想計算機を用いた負荷分散可能なMPI 実行環境を提案する。これはMPI 実行環境を仮想計算機ごとマイグレーションさせることにより、MPI プロセスに透過的なマイグレーションを実現する。仮想計算機としてXen [8] を用い、同計算機が持つマイグレーション機能を用いたプロトタイプを実装した。さらに、VPN を用いたネットワークの仮想化によって、異なるサブネットへのマイグレーションを実現した。同プロトタイプを評価した結果、MPI 実行時マイグレーションが可能かつ、仮想化によるオーバーヘッドは10%から、通信の頻繁なものでは50%超えることが分かった。また、同プロトタイプに 負荷分散アルゴリズムを実装し、長時間実行されるジョブにおいて実行効率の向上を確認し、本提案の有効性を確認した。</div> </blockquote>



- **GridRPC を用いたタスクファーミングAPIの設計と実装** [[Paper](dataDir/swopp05tanimura.pdf)]  <span onmouseover="document.getElementById('swopp05tanimura').style.display = 'block'"  onmouseout="document.getElementById('swopp05tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2005-HPC-103*   , pp. 67-72  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp05tanimura"> 本研究では，グリッド上でタスク並列を行うアプリケーションを開発する手間を削減することを目指して，GridRPC の上位にタスクファーミングAPI を提供するミドルウェアを設計した．実アプリケーションの事例研究から得られた要求仕様をもとにAPI を提案し，タスクの自動割り当てや耐障害に関する機能をミドルウェア内部に実装した．そのような上位ミドルウェアを実装するために，Argument Array API に引数データのコピー機能が求められること，ノンブロッキング呼び出しにおけるデータ通信のタイミングとRPC の実行情報を取得する方法がGridRPC で標準化される必要があることを明らかにした．</div> </blockquote>



- **GridRPCシステムNinf-GにおけるUNICOREおよびGT4によるジョブ起動** [[Paper](dataDir/hpc0506nakada.pdf)]  <span onmouseover="document.getElementById('hpc0506nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0506nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2005-HPC-102*   , pp. 45-50  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0506nakada"> GridRPCシステムNinf-GにおけるUNICOREおよびGrobus Toolkit 4を用いたジョブ起動機構に関して報告する。Ninf-GはGrobus Toolkit２および３を用いたジョブ起動機構をクライアントライブラリに内臓している。しかしUNICOREやGrobus Toolkit 4ではC言語でのクライアントAPIが提供されていないため、ジョブ起動機構をクライアントライブラリに内臓することはできない。我々は、ジョブ起動機構 を外部モジュールとしてクライアントライブラリから切り離すための汎用プロトコルを設計した。このプロトコルを使用することで、Ninf-Gクライアント ライブラリ本体に手を加えることなく、新たなジョブ起動機構を追加することができる。</div> </blockquote>



- **ユーザーのステアリングを許すインタラクティブなジョブ゛スケジューリングシステム** [[Paper](dataDir/hpc0506iino.pdf)]  <span onmouseover="document.getElementById('hpc0506iino').style.display = 'block'"  onmouseout="document.getElementById('hpc0506iino').style.display = 'none'">[abst]</span>   
飯野　彰子, 中田秀基, 下平英寿, 松岡聡
, *情報処理学会研究報告 2005-HPC-102*   , pp. 39-44  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0506iino"> 複数のジョブから構成されるワークフローを、グリッド上でパッチ的に実行する研究は多くなされている。しかし、アプリケーションユーザの持つジョ ブの中には、基本的にはワークフロー的な構造を持つものの、各ジョブの実行においてユーザからの操作が不可欠なものも少なくない。このようなジョブは既存 のワークフロー機構で実行することは難しい。我々は基本的にはワークフローに従った処理をしつつも、ユーザからの入力が不可欠な場面ではユーザに操作の要 求を行う。ワークフロージョブスケジューリングシステムを開発した。ワークフローシステムのベースとしては、CondorのDAGManを用いた。この DAGManの機構を利用して、ユーザからのステアリングを受け付ける機構を実装した、また、本システムを系統樹推定問題に適用し、有効性を確認した。</div> </blockquote>



- **OGSA アーキテクチャに基づく NAREGI スーパースケジューラの設計と実装** [[Paper](dataDir/hpc0506hatanaka.pdf)]  <span onmouseover="document.getElementById('hpc0506hatanaka').style.display = 'block'"  onmouseout="document.getElementById('hpc0506hatanaka').style.display = 'none'">[abst]</span>   
畑中正行, 中野恭成, 井口裕次, 大野利男, 秋岡明香, 佐賀一繁, 中田秀基, 松岡　聡
, *情報処理学会研究報告 2005-HPC-102*   , pp. 33-38  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0506hatanaka"> 本稿では、OGSA-EMS のサービス・アーキテクチャに沿った NAREGI スーパースケジューラ の設計と実装について述べる。NAREGI スーパースケジューラの実装をとおして OGSA-EMS アーキテクチャの実現可能性を確認すると同時に、ヘテロかつ多数台の計算資源を要求する MPI並列ジョブの自動資源割当における OGSA-EMS 仕様の問題点を明確化するとともに それを解決する OGSA-EMS 構成要素への拡張を提案する。</div> </blockquote>



- **インタラクティブなジョブスケジューリングシステム**    
飯野　彰子, 中田秀基, 下平英寿, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **ファイルへのアクセスの自動分散を行うグリッド用分散ファイルシステム**    
佐藤 仁, 松岡聡, 中田秀基
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **チェックポイント時のdiskI/O負荷を軽減する投機チェックポイント**    
山形育平, 松岡聡, 實本英之, 中田秀基
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **仮想計算機を用いたマイグレーション可能なMPI実行環境**    
立薗真樹, 中田秀基, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **スケジューリングシステムとレプリカ管理システムによるデータインテンシブアプリケーション実行環境**    
町田悠哉, 滝澤真一朗, 中田秀基, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **カスタマイズ可能な仮想計算機上による安全なジョブ実行環境**    
青木孝文, 高宮安仁, 中田秀基, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **大規模グリッド環境下での Jojo の評価**    
青木仁志, 中田秀基, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **グリッド環境におけるスーパースケジューラ連携手法の検討** [[Paper](dataDir/hokke05akioka.pdf)]  <span onmouseover="document.getElementById('hokke05akioka').style.display = 'block'"  onmouseout="document.getElementById('hokke05akioka').style.display = 'none'">[abst]</span>   
秋岡明香, 竹房あつ子, 中田秀基, 松岡聡, 三浦謙一
, *情報処理学会研究報告 2004-HPC-101*   , pp. 55-60  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke05akioka"> グリッド環境において効果的な負荷分散を実現するために、従来からスーパースケジューラの利用が提案されてきた。しかし、グリッド環境にスーパースケジューラが複数存在する場合の挙動は充分な検討がされていない。本稿では、スーパースケジューラの連携手法とその効果について、グリッドシミュレータを用いて検討した。その結果、複数のスーパースケジューラが単独で機能するよりも、階層構造や分散ネットワークを構成して協調することで、アプリケーションの実行待ち時間を短縮し、グリッド計算資源の利用効率を高めることを確認した。さらに、スーパースケジューラが階層構造を構成する場合と分散ネットワークを構成する場合について、利点と欠点を確認した。</div> </blockquote>



- **GridRPCシステムの比較 --アプリケーション開発における違い** [[Paper](dataDir/hokke05tanimura.pdf)]  <span onmouseover="document.getElementById('hokke05tanimura').style.display = 'block'"  onmouseout="document.getElementById('hokke05tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2004-HPC-101*   , pp. 91-96  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke05tanimura"> 本研究では，代表的なGridRPCシステムである Ninf-G, NetSolveおよびOmniRPCに注目し，それぞれのシステムを使ってアプリケーションを開発する上での違いを調査した．システムが想定している用途の違いを踏まえて，プログラミングや遠隔実行プログラムの起動方法，利用できる環境，実行をサポートする機能の違いについて明らかにし，単一RPC実行時の性能比較を行った．また，将来的にサポートが進むであろう機能や発展的なRPCについても言及した．こうした調査結果は，どのシステムを利用してアプリケーションを開発するかを決める上で有用な情報になると考える．</div> </blockquote>



- **ファイルへのアクセスの自動分散を行うグリッド用分散ファイルシステム** [[Paper](dataDir/hokke05sato.pdf)]  <span onmouseover="document.getElementById('hokke05sato').style.display = 'block'"  onmouseout="document.getElementById('hokke05sato').style.display = 'none'">[abst]</span>   
佐藤仁, 松岡聡, 中田秀基
, *情報処理学会研究報告 2004-HPC-101(HOKKE2005)*   , pp. 7-11  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke05sato"> HPCクラスタやグリッドなどの並列計算環境では アプリケーションによっては ファイルを保持するノードへのアクセス集中が発生し 実行性能の低下が問題となる 既存の分散ファイルシステム上でこのようなアクセス集中を避けるためには ユーザがアプリケーションの作成時や実行時に明示的にファイルアクセスの分散を行うことが必要となるが 環境が不均質であるグリッドではこのような対応は困難であり負担が大きい 我々は ファイルシステム側でアクセスの集中を検知し ファイル複製を積極的に利用して ファイルへアクセスを分散する手法を提案する 本稿では グリッドファイルシステムであるGfarmを用いてファイルへのアクセスが集中する例 理想的なアクセスパターンの例について検証を行った また 提案手法をGfarmに実装したプロトタイプを用いて ファイルへのアクセスの自動分散の有効性を確認した．</div> </blockquote>



- **非対称ネットワークを隠蔽する高速通信インフラストラクチャの設計と実装** [[Paper](dataDir/hokke05hamano.pdf)]  <span onmouseover="document.getElementById('hokke05hamano').style.display = 'block'"  onmouseout="document.getElementById('hokke05hamano').style.display = 'none'">[abst]</span>   
濱野智行, 中田秀基, 松岡聡
, *情報処理学会研究報告 2004-HPC-101(HOKKE2005)*   , pp. 85-90  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke05hamano"> グリッド環境で問題となっている非対称ネットワークを扱う研究は数多く存在するが、十分な接続性とグリッド環境に適したセキュリティ・サイトポリ シ非依存性・高通信性能を達成するものは存在しない。そこで、非対称ネットワークを隠蔽し、それを意識せず通信可能であり、グリッド環境に適した通信イン フラストラクチャを提案する。また、そのプロトタイプJRouter を実装し、それを用いて実際のグリッド環境でその性能評価を行った。その結果、接続性・セキュリティ・サイトポリシ非依存性において十分な性能であるが、 通信性能において十分とは言えないという結論に至ったため、更なる性能向上のための施策について議論を行う。</div> </blockquote>



- **グリッド環境におけるモニタリングシステムの自律的構成** [[Paper](dataDir/hokke05shirose.pdf)]  <span onmouseover="document.getElementById('hokke05shirose').style.display = 'block'"  onmouseout="document.getElementById('hokke05shirose').style.display = 'none'">[abst]</span>   
白勢健一郎, 松岡聡, 中田秀基
, *情報処理学会研究報告 2004-HPC-101(HOKKE2005)*   , pp. 1-6  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke05shirose"> グリッド環境での計算機資源のモニタリングは、効率の良い自動的な資源配分やグリッド環境の把握などに必要である。しかし、依存関係を持つ多数の 構成要素から成り立っているため、その運用を人間の作業のみで行うのは限界がある。本研究では標準化団体の提案するモニタリングシステムのアーキテクチャ に基づき、個々の構成要素が分散アルゴリズムなどを用いて自律的に設定やその更新を行うモデルを提案する。提案に基づいて既存のモニタリングシステムを対 象にした管理機構を試作した。テストベッド環境の14 個のPC クラスタのログインノードへの初期設定を10 分程度で行い、障害修復の機能が動作することを確認した。</div> </blockquote>



- **耐障害性を考慮したNinf-Gアプリケーションの実装と評価** [[Paper](dataDir/hpcs05tanimura.pdf)]  <span onmouseover="document.getElementById('hpcs05tanimura').style.display = 'block'"  onmouseout="document.getElementById('hpcs05tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 池上努, 中田秀基, 田中良夫, 関口智嗣
, *ハイパフォーマンスコンピューティングと計算科学シンポジウム, HPCS2005*   , pp. 99-106  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs05tanimura"> 我々はグリッドのアプリケーションにとって耐障害性が重要課題であることをふまえて，タスク並列アプリケーションをGridRPC システムの1 つであるNinf-G を用いて実装し，アジア太平洋地域のグリッドのテストベッド上で長時間にわたり実行した．その中で障害パターンを集めて，障害の検知や復旧にかかるコストを測定しながら耐障害性の機構を検討した．本研究により，グリッドが持つ不安定さに対応したアプリケーションやミドルウェアでは，障害検知や復旧の操作におけるタスク実行の性能低下に留意する必要があるとともに，性能低下を防ぐために，障害検知のためのタイムアウト値の最小化や復旧のバックグラウンド処理，障害を考慮したタスク割当てが必要であることが分かった．こうして，グリッドのアプリケーション開発者に対して開発や実行時の留意点を示すとともに，GridRPC の枠組みの上位に求められる耐障害に関する機構の設計への指針を示した．</div> </blockquote>



- **ポータビリティの高いジョブスケジューリングシステムの設計と実装** [[Paper](dataDir/swopp04machida.pdf)]  <span onmouseover="document.getElementById('swopp04machida').style.display = 'block'"  onmouseout="document.getElementById('swopp04machida').style.display = 'none'">[abst]</span>   
町田悠哉, 中田秀基, 松岡聡
, *情報処理学会研究報告 2004-HPC-99*   , pp. 217-222  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp04machida"> グリッド環境に存在する不安定性と非均質性という２つの特徴に対応したジョブスケジューリングシステムJay について述べる．Jay はウィスコンシン大学で開発されたスケジューリングシステムCondor の構造をベースとし，ポータビリティを高めるためJava で実装を行った．ここでJava にはプロセスのユーザID を安全に変更する手法がないという問題が生じたが，JNI をサポートしていないJava 環境においても稼働するようなポータブルなC++デーモンを開発することでこの問題に対処した．小規模環境における評価実験により，本システムが耐故障性 と高いポータビリティを備えていることが示された．</div> </blockquote>



- **グリッド上のスケーラブルな並列レプリケーションフレームワーク** [[Paper](dataDir/swopp04takizawa.pdf)]  <span onmouseover="document.getElementById('swopp04takizawa').style.display = 'block'"  onmouseout="document.getElementById('swopp04takizawa').style.display = 'none'">[abst]</span>   
滝澤真一朗, 高宮安仁, 中田秀基, 松岡聡
, *情報処理学会研究報告 2004-HPC-99*   , pp. 247-252  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp04takizawa"> グリッド環境におけるデータレプリケーション手法として，レプリカ管理とデータ転送の集約およびマルチキャスト転送を利用し，複数サイト間の巨大 データの効率的なレプリケートを可能とする，並列レプリケーションフレームワークを提案する．レプリカ情報を集中管理するレプリカ管理サービス，および データ要求元に応じて複数レプリカの中から最適なレプリカを選択し，同時並列ファイル転送ツールであるDolly+による高速ファイル転送を行うレプリ ケーションサービスからなるプロトタイプを実装した．遠隔データサイトに複数クラスタが接続された実際のデータグリッド環境においてプロトタイプの評価を 行った結果，ノード数の増加によらずほぼ一定時間内にレプリケーションを完了し，クラスタ内でキャッシュを管理する単純な手法よりも優れたスケーラビリ ティを示した．</div> </blockquote>



- **Speculativeチェックポインティングの設計と実装**  <span onmouseover="document.getElementById('swopp04yamgata').style.display = 'block'"  onmouseout="document.getElementById('swopp04yamgata').style.display = 'none'">[abst]</span>   
山形育平, 實本英之, 中田秀基, 松岡聡
, *電子情報通信学会技術研究報告　DC2004-13～20*   , pp. 31-36  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp04yamgata"> 並列プロセスでの同期チェックポインティングでは，チェックポイントを単一レポジトリに保存する時にディスクI/O の負荷が時間的に集中する．本研究ではこれを解決する方法として，インクリメンタルチェックポインティングを改善した投機的チェックポインティングを提案 する．これはチェックポインティングの合間にページ更新予測に基づく投機的なチェックポインティングを行うことによりチェックポインティングのタイミング を分割させ，ディスクI/O 負荷を分散させるものである．また，このプロトタイプとして，逐次プロセスの投機チェックポインタを実装した．これを使用し，並列環境での評価を行なっ た．その結果，投機的チェックポインティングを実装したものは実装していないものと比較して最大33 ％チェックポイント時間の削減効果が観測され，投機的チェックポインティングの有効性が示された．</div> </blockquote>



- **Ninf-G2の性能評価：科学技術計算における事例** [[Paper](dataDir/swopp04tanimura.pdf)]    
谷村勇輔, 池上努, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2004-HPC-99*   , pp. 37-42  , 2004 



- **耐故障性を重視したRPCシステムNinf-Cの設計と実装** [[Paper](dataDir/sacsis04nakada.pdf)]  <span onmouseover="document.getElementById('sacsis04nakada').style.display = 'block'"  onmouseout="document.getElementById('sacsis04nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 松岡聡, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS2004 論文集*   , pp. 77-84  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis04nakada"> 耐故障性を重視したRPCシステムNinf-Cの設計と実装に関して述べる。Ninf-Cは、全体として数日から数ヶ月を要する大規模なマスタ ワーカ型計算を安定して実行することを目的としたシステムで、ウィスコンシン大学で開発されたスケジューリングシステムCondorの提供する機能を利用 することで、マスタを含むシステム全体に耐故障性を持たせている。Ninf-CのRPCは、Condorのファイルステージ機能を用いて実現される。直接 ソケット通信を使用せずにファイル経由で通信を行うことで、マスタとワーカのチェックポイントをとることを可能とした。また、ファイルに残った通信記録を 用いてマスタの状態を復元する。さらに、Condor-Gを利用することで、Globusによって構築されたグリッド環境下での運用も可能である。 Ninf-Cの有効性を確認するため、クラスタ環境で簡単なマスタワーカ型プログラムを長時間実行した。この際、マスタおよびワーカを実行しているマシン をシャットダウンするといった人為的な外乱をあたえたが、プログラムは19時間かけて問題なく実行を終了し、Ninf-Cの耐故障性が実証された。</div> </blockquote>



- **Ninf-G2: 大規模Grid環境での利用に即した高機能，高性能GridRPCシステムの実装と評価**    
武宮博, 田中良夫, 中田秀基, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS2004 論文集*   , pp. 69-76  , 2004 



- **サービス指向アーキテクチャに基づいたグリッドポータル自動生成サーバー GridSpeed の設計と実装**    
鈴村豊太郎, 中田秀基, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS2004 論文集*    , 2004 



- **Ninf-G version2の実装および性能評価** [[Paper](dataDir/hokke04takemiya.pdf)]  <span onmouseover="document.getElementById('hokke04takemiya').style.display = 'block'"  onmouseout="document.getElementById('hokke04takemiya').style.display = 'none'">[abst]</span>   
武宮博, 田中良夫, 中田秀基, 関口智嗣
, *情報処理学会研究報告 2004-HPC-97*   , pp. 19-24  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04takemiya"> Ninf-G version2は，Gridプログラミングモデルの一つであるGridRPCの参照実装であり，広域に分散した複数代のクラスタから構成される大規模Grid環境上でアプリケーションを効率よく実行することを目的とする．関数ハンドル同時生成機能やリモートオブジェクトを実装することで，遠隔手続き呼び出しに伴う起動コストや通信コストの低減を図るとともに，ハートビート機能，関数ハンドル作成タイムアウト機能，サーバ属性の個別設定機能を提供することで，非均質，不安定で動的に変化するGrid環境への対応を図っている．4台のクラスタ計300プロセッサから構成されるGridテストベッド上でNinf-G version2の実行性能を測定した．その結果，関数ハンドル同時生成機能がプログラム起動コストの低減に有効であること，およびNinf化されたシミュレーションが大規模グリッド環境で効率的に実行可能であることがわかった．</div> </blockquote>



- **グリッド環境におけるVM上でのジョブ実行の検討** [[Paper](dataDir/hokke04ogura.pdf)]  <span onmouseover="document.getElementById('hokke04ogura').style.display = 'block'"  onmouseout="document.getElementById('hokke04ogura').style.display = 'none'">[abst]</span>   
小倉章嗣, 河野健二, 松岡聡, 中田秀基
, *情報処理学会研究報告 2004-HPC-97*   , pp. 25-30  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04ogura"> グリッド上で利用される計算機において、ユーザの権限に応じた、適切で細粒度な各種内部リソースへのアクセス制御を行うために、プロセスの仮想化 手法を用いる。近年複数提案されているが、個々の手法のコストは、対象となるアプリケーションの性質やアクセスポリシによって異なり、かつ制御を行う有効 性自身も未解決である。そこで、アプリケーションの性質やポリシによって仮想化手法を選択し、常に低オーバヘッドな仮想化を実現する手法を提案し、かつそ れぞれの手法の適用性を実際のグリッド上で選択されるクラスタノード上の種々のベンチマークを通じて検証する。作成したプロトタイプはGlobus Toolkit2.4 を用いてユーザとポリシに基づいて仮想化手法を選択し、ジョブマネージャの一つとして仮想化環境内でジョブを起動する。NPB2.4 ベンチマークによる結果では、適切な仮想化手法を用いることでオーバーヘッドを最小にすることが可能で、かつ通信を頻繁に行なうアプリケーションではライ ブラリコールの仮想化が最適であり、複数プロセスの仮想化にはカーネルモジュールを用いたシステムコールの仮想化が最適であるなどの詳細な指針を得た。</div> </blockquote>



- **Condorの汎用グリッドインターフェイスの設計とUNICOREへの適用** [[Paper](dataDir/hokke04nakada.pdf)]  <span onmouseover="document.getElementById('hokke04nakada').style.display = 'block'"  onmouseout="document.getElementById('hokke04nakada').style.display = 'none'">[abst]</span>   
中田秀基, Jaime Frey, 山田基弘, 伊藤泰善, 中野恭成, 松岡聡
, *情報処理学会研究報告 2004-HPC-97*   , pp. 37-42  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04nakada"> 本稿では、Condor システムにおける、汎用の外部グリッドシステムへのインターフェイス機構の設計および実装に関して述べる。Condor システムは特定の外部グリッドシステムに対するインターフェイスを持っているが、これを使用するにはCondor システム内部の変更が必要になり、新たな外部グリッドシステムのサポートを追加することが難しかった。われわれは、任意の外部グリッドシステムへのイン ターフェイスを容易に構築するための汎用インターフェイスを設計し、この問題を解決した。さらに、この汎用インターフェイスを用いて、UNICORE システムを外部グリッドシステムとして利用するブリッジを実装し、汎用インターフェイスによる手法の有効性を確認した。</div> </blockquote>



- **グリッド技術を用いた進化系統樹推定の並列化** [[Paper](dataDir/hokke04yamamoto.pdf)]  <span onmouseover="document.getElementById('hokke04yamamoto').style.display = 'block'"  onmouseout="document.getElementById('hokke04yamamoto').style.display = 'none'">[abst]</span>   
山本洋, 中田秀基, 下平英寿, 松岡聡
, *情報処理学会研究報告 2004-HPC-97*   , pp. 181-186  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04yamamoto"> 進化系統樹の推定では最尤法を用いた手法が最も優れた推定法の1つとされているが、最尤法の計算量は大きく、種の個数が増えると系統樹の個数は莫 大となるため全系統樹の尤度を求めることは事実上不可能となる。系統樹の構成要素であるスプリットの尤度を最尤法によって計算し、スプリットの尤度を用い た行列計算によって系統樹の尤度を近似計算する手法が提案されている。しかし、種の個数がさらに増大すると、近似計算であってもすべての系統樹に対して行 うことは困難になる。本研究では、系統樹の推定を系統樹空間における探索問題とみなし、最適化手法を適用することで、近似計算の対象となる系統樹の個数を 削減する。また、グリッドミドルウェアを用いたマスタ・ワーカ方式を採用し、尤度計算および最適化手法の並列実行を可能にした。生物9種の系統樹推定にお いて16ワーカを用いた結果、64.0倍の性能向上が得られた。</div> </blockquote>



- **Jojoによる遺伝的プログラミングの並列化** [[Paper](dataDir/hokke04tokuda.pdf)]  <span onmouseover="document.getElementById('hokke04tokuda').style.display = 'block'"  onmouseout="document.getElementById('hokke04tokuda').style.display = 'none'">[abst]</span>   
徳田拓, 田中康司, 中田秀基, 松岡聡
, *情報処理学会研究報告 2004-HPC-97*   , pp. 187-192  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04tokuda"> 進化系統樹の推定では最尤法を用いた手法が最も優れた推定法の1つとされているが、最尤法の計算量は大きく、種の個数が増えると系統樹の個数は莫 大となるため全系統樹の尤度を求めることは事実上不可能となる。系統樹の構成要素であるスプリットの尤度を最尤法によって計算し、スプリットの尤度を用い た行列計算によって系統樹の尤度を近似計算する手法が提案されている。しかし、種の個数がさらに増大すると、近似計算であってもすべての系統樹に対して行 うことは困難になる。本研究では、系統樹の推定を系統樹空間における探索問題とみなし、最適化手法を適用することで、近似計算の対象となる系統樹の個数を 削減する。また、グリッドミドルウェアを用いたマスタ・ワーカ方式を採用し、尤度計算および最適化手法の並列実行を可能にした。生物9種の系統樹推定にお いて16ワーカを用いた結果、64.0倍の性能向上が得られた。</div> </blockquote>



- **OGSAとGlobus Toolkit 3**    
中田秀基
, *情報処理学会連続セミナー2003 第6回 「グリッドコンピューティング」*    , 2003 



- **GridRPCを用いたタスクファーミングAPIの試作** [[Paper](dataDir/hpc0310nakada.pdf)]    
中田秀基, 田中良夫, 松岡聡, 関口智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 102*   , pp. 61-66  , 2003 



- **Ninf-G2: 大規模環境に即した高機能，高性能GridRPCシステム** [[Paper](dataDir/swopp03tanaka.pdf)]    
田中良夫, 中田秀基, 朝生正人, 関口智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 83*   , pp. 65-70  , 2003 



- **グリッドコンピューティングにおけるモニタリングシステムの自律的構成** [[Paper](dataDir/swopp03shirose.pdf)]    
白勢 健一郎, 小川 宏高, 中田秀基, 松岡聡
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 83*   , pp. 89-94  , 2003 



- **アプリケーションのインストール、データの配布、更新をサポートするグリッドポータル構築ツールキット(PCT4G) の開発** [[Paper](dataDir/swopp03shirasuna.pdf)]    
白砂哲, 鈴村豊太郎, 中田秀基, 松岡聡
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 83*   , pp. 173-178  , 2003 



- **レプリカ交換分子動力学シミュレータREMD Toolkitのグリッド上での実行** [[Paper](dataDir/swopp03sato.pdf)]    
佐藤仁, 伊藤正勝, 中田秀基, 松岡聡
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 83*   , pp. 41-46  , 2003 



- **次世代グリッド基盤OGSAにおけるＣ言語動作環境提供システムの試作と評価** [[Paper](dataDir/swopp03hamano.pdf)]    
濱野智行, 中田秀基, 鈴村豊太郎, 松岡聡
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 83*   , pp. 179-184  , 2003 



- **グリッド環境に適した並列組み合わせ最適化システム jPoP における分枝限定法の実装**  <span onmouseover="document.getElementById('spa03akiyama').style.display = 'block'"  onmouseout="document.getElementById('spa03akiyama').style.display = 'none'">[abst]</span>   
秋山 智宏, 中田 秀基, 松岡 聡, 関口 智嗣
, *SPA 2003*    , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="spa03akiyama"> 多次元パラメータ関数の最適値を求める組み合わせ最適化問題の解法としては、分枝限定法や遺伝的アルゴリズムなどが知られている。これらの解法は自明な並列度が大きく、粒度の調整も比較的容易なためグリッド上での実行に適している。しかしグリッド上での分散並列プログラミングは煩雑である上、実行時にも実行ファイルや設定ファイルをユーザがインストールしなければならないといった問題がある。われわれはこれらの問題を解決し、最適化問題解法のグリッド上での実行を容易にするシステムjPoP を開発している。jPoP は各解法に対してテンプレートとなるクラスを提供しプログラミングを支援する。また、動的なプログラムのアップロードによってグリッド上での実行を支援する。現在、最適化アルゴリズムのひとつである遺伝的アルゴリズム用クラス群 jPoP-GA が実装されているが、本稿ではこれに加えて、分枝限定法のテンプレートクラスの設計と実装について述べる。</div> </blockquote>



- **グリッド向け実行環境Jojo を用いた遺伝的アルゴリズムによる蛋白質構造決定**  <span onmouseover="document.getElementById('hpc0303nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0303nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 中島 直敏, 小野 功, 松岡 聡, 関口 智嗣, 小野 典彦, 楯 真一
, *情報処理学会研究報告 2002-HPC-93*   , pp. 155-160  , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0303nakada"> Javaはグリッド上でのプログラミング言語として、 1)クラスファイルのポータビリティによりアーキテクチャヘテロな環境への対応が容易、 2)マルチスレッドによるレイテンシの隠蔽が期待できる、などの点で有望である。また、遺伝的アルゴリズム は実問題に応用範囲が広く、並列化や実行粒度の調節が容易なことから、グリッド上のアプリケーションとして適していると考えられる。われわれはこれらの点に着目し、Javaによる遺伝的アルゴリズム 実行支援環境jPop-GAの開発をすすめている。しかし、グリッド上で遺伝的アルゴリズム の効率的な実行を可能にする並列化方式については指針を欠いていた。 本稿では、遺伝的アルゴリズム のグリッド上での並列化に関する指針を得るべく、実アプリケーションである遺伝的アルゴリズム による核磁気共鳴分光法による蛋白質構造解析をJavaで実装し、これをJava向けグリッド実行環境Jojo を用い、 2つの並列化指針に基づいて並列化した。さらにそれぞれの実装に対して問題サイズを変えて評価を行い並列化手法に関する指針を得た。</div> </blockquote>



- **グリッド環境に適したJava用階層型実行環境Jojoの設計と実装**  <span onmouseover="document.getElementById('hpc0210nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0210nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 松岡 聡, 関口 智嗣
, *情報処理学会研究報告 2002-HPC-92*   , pp. 31-36  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0210nakada"> 本稿では、グリッド環境でのJavaプログラミングを支援する実行環境Jojo について述べる。JojoはJavaを用いて実装された、階層構造を持つ環境に適した分散実行環境で、 Globusを用いた起動、直感的で並列実行に適したメッセージパッシングAPI、プログラムコードの自動アップロードといった特徴を持つ。 Jojoを用いれば、グリッド上で動作する並列分散システムが非常に容易に構築できる。本稿ではJojoの設計と実装の詳細、プログラミングAPI、設定ファイル、簡単なプログラム例を示す。さらに予備的な性能評価の結果も示す。</div> </blockquote>



- **動的なアプリケーション開発実行を可能にするグリッドポータルアーキテクチャ**  <span onmouseover="document.getElementById('hpc0208suzumura').style.display = 'block'"  onmouseout="document.getElementById('hpc0208suzumura').style.display = 'none'">[abst]</span>   
鈴村 豊太郎, 中田 秀基, 松岡 聡, 関口 智嗣
, *情報処理学会研究報告 2002-HPC-91*   , pp. 191-196  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0208suzumura"> 近年，グリッドポータルはグリッドに対する高位のインタフェースとして重要な役割を担っている．我々は，グリッドポータルの開発を支援する為のツールとして，ポータルに必要となるユーザインタフェースの自動化とバックエンドのグリッドアプリケーションの開発を支援するツールNinf Portalの開発を進めている．本稿では, グリッドポータルにおける動的なアプリケーションの開発実行環境のアーキテクチャの提案を行なう．具体的には，Ninf-G のクライアントAPI にJava バインディングを実装し，そのバインディングを基盤に，スクリプト言語Python のインタフェースを実装した．次に，ポータル上でそのスクリプトインタフェースを用いてグリッドアプリケーションを記述し，ページのフォームにユーザインタフェースの情報を入力することによって，動的にユーザに特化したアプリケーションの生成を支援する環境のアーキテクチャの設計を行なった．</div> </blockquote>



- **Webサービス技術を基盤とするGridRPCシステムの評価**  <span onmouseover="document.getElementById('hpc0208shirasuna').style.display = 'block'"  onmouseout="document.getElementById('hpc0208shirasuna').style.display = 'none'">[abst]</span>   
白砂 哲, 中田 秀基, 松岡 聡, 関口 智嗣
, *情報処理学会研究報告 2002-HPC-91*   , pp. 197-202  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0208shirasuna"> Grid 上のミドルウェアであるGridRPC は科学技術計算に多く用いられる。しかし、ぞれのGirdRPC システムが独自のプロトコルを利用しているため，インタオペラビリティが重要な課題となっている．一方，Web サービスの分野では，SOAP やWSDL といったXML 基盤の標準仕様が用いられており，広く使用されることが期待されている．そのため，GridRPC においてもこれらの仕様を用いてインタオペラビリティを確保することが可能であると考えられるが，1) ビジネスアプリケーションを念頭としたこれらの仕様がGridRPC に適した記述力を有しているか，2) コストが高いXMLを用いて十分な性能を得ることができるか，などが明らかではない．本研究では，SOAP とWSDLを基盤とするGridRPC を実装し，評価した．その結果，SOAP 基盤のGridRPC のナイーブな実装においては大きなオーバヘッドが大きいが，いくつかの性能向上を行なうことにより，本来のバイナリ転送に近い性能が得られた．一方，配列パラメタの扱いなどのGridRPC 特有なさまざまな機能を実現することは，WSDL の制限により困難であり，WSDL の仕様の拡張が必要であることが分かった．</div> </blockquote>



- **グリッド環境におけるクラスタ間データ転送の評価**  <span onmouseover="document.getElementById('hpc0208ogura').style.display = 'block'"  onmouseout="document.getElementById('hpc0208ogura').style.display = 'none'">[abst]</span>   
小倉章嗣, 松岡 聡, 中田 秀基
, *情報処理学会研究報告 2002-HPC-91*   , pp. 155-160  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0208ogura"> 大規模ストレージシステムを構築する際に、クラスタ計算機同士でグリッドを構成し、より大規模なストレージを構築する試みがなされている。グリッド上のストレージを構成するクラスタ間でデータ転送を行う場合、RTT ×bandwidth の大きい環境では通信路の性能を生かし切れないことが問題になる。また、各クラスタノード間での通信のように同時に多対多で通信を行う場合は、複数の通信で通信路を共有しなければならないため、通信路のバンド幅以上にデータが流れ込んでしまうことが問題になる。本研究では、これらの問題を解決するために、同時に通信を行うノード数、ストライプ数等のパラメータについて、自動的に通信路に合ったパラメータを決定するシステムを提案する。本稿では、いくつかの環境を想定し、その上でクラスタ間データ転送のシミュレーションを行ない、それぞれの環境に応じた最適なパラメータについて考察する。</div> </blockquote>



- **Grid環境に適した並列組み合わせ最適化システムの提案**  <span onmouseover="document.getElementById('swopp02akiyama').style.display = 'block'"  onmouseout="document.getElementById('swopp02akiyama').style.display = 'none'">[abst]</span>   
秋山 智宏, 中田 秀基, 松岡 聡, 関口 智嗣
, *情報処理学会研究報告 2002-HPC-91*   , pp. 143-148  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp02akiyama"> 多次元パラメータ関数の最適値を求める組合せ最適化問題の解法としては、分枝限定法や遺伝的アルゴリズムなどが知られている。これらの解法は自明な並列度が大きく、粒度の調整も比較的容易なためGrid 上での実行に適している。しかしGrid 環境での分散並列プログラミングは煩雑である上、実行時にも実行ファイルや設定ファイルをユーザがインストールしなければならないといった問題がある。われわれはこれらの問題を解決し、最適化問題解法のGrid 上での実行を容易にするシステムjPoP を提案する。jPoP は各解法に対してテンプレートとなるクラスを提供しプログラミングを支援する。また、動的なプログラムのアップロードによってGrid 上での実行を支援する。本稿ではjPoPの概要と遺伝アルゴリズム問題のテンプレート、さらにjPoP の実装について述べる。</div> </blockquote>



- **ポータブルなJava向けソフトウェア分散共有メモリシステムの実現**  <span onmouseover="document.getElementById('jspp01poster_sohda').style.display = 'block'"  onmouseout="document.getElementById('jspp01poster_sohda').style.display = 'none'">[abst]</span>   
早田 恭彦, 中田 秀基, 松岡 聡, 小川 宏高
, *JSPP2001 論文集(ポスタ)*   , pp. 125-126  , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp01poster_sohda"> 近年のハードウェアの急速なコモディティ化とネットワーク技術の発展により、 Grid Computingに代表される Wide Area HPCが盛んに研究されている。異なる アーキテクチャの計算機で構成されるGrid Computinにおいて、 プラットフォームポータビリティとパフォーマンスポータビリティを満たすには Java言語を利用するのが一つの適当な手法である。そこで、本研究ではJavaの ポータビリティを損なわないソフトウェア分散共有メモリのソフトウェアアーキテクチャ を考察し、プロトタイプシステム - JDSM -を実現した。このソフトウェアDSMシステムを コモディティクラスタ上で性能評価を行い、良好な性能を得ることができた。</div> </blockquote>



- **Grid RPCシステムのAPIの提案**  <span onmouseover="document.getElementById('hpc01nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc01nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 田中 良夫, 松岡 聡, 関口 智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2001, No.7*    , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc01nakada"> RPC(Remote Procedure Call)に基づく計算システムは、広域分散計算環境であるGrid上のミドルウェアの一形態として有望である。Grid上のRPCシステムは、 Ninf、Netsolveなどいくつか提案されている。しかしAPIに標準規格が存在しないため、RPCシステムを用いて記述したプログラムに互換性がなく、このことがGrid上のRPCの普及を妨げている。本稿では、Grid上のRPCシステムの標準 APIの候補として、一つのAPIを提案する。このAPIは、数年にわたるNinfシステムにおける経験に基づき、必要十分の機能を提供しながら、最小限となるように設定されている。我々はGlobal Grid Forumなどの場で、この規格案の標準化を促進していく予定である。 Computation system based on RPC(Remote Procedure Call) is a promising candidate as a middleware of the Grid. Several systems, including Ninf and NetSolve, are already proposed and used in various area. However, Grid RPC API is not standardised yet, and the fact is precluding further spread of Grid RPC systems. In this paper, we examine two existing Grid RPC API and propose a Grid RPC API intended to be a standard, based on them. The API is designed to be minimal but sufficient for applications. We are planning to promote this API as a standard for Grid RPC in Global Grid Forum.</div> </blockquote>



- **Ninfシステムにおけるフォールトトレランス**  <span onmouseover="document.getElementById('hpc0108shirasuna').style.display = 'block'"  onmouseout="document.getElementById('hpc0108shirasuna').style.display = 'none'">[abst]</span>   
白砂 哲, 中田 秀基, 松岡 聡
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2001, No.77*   , pp. 153-158  , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0108shirasuna"> グリッドの使用が広く広まるにつれ、 グリッドにおけるフォールトトレランスは重要な研究テーマになりつつある。 グリッドでは計算資源は豊富であるが、不安定であり、専用の資源ではないため、 すべての段階での障害をユーザ透過に扱わなければならない。 GridRPCは、グリッド環境におけるプログラミングモデルの一つである。 本研究では、GridRPCにおける計算の過程において、 フォールトトラランスのさまざまな側面に対し、 それぞれを別々に対処する必要があることを示す。 今回、計算時におけるフォールトトレランスを実現するために GridRPCシステムであるNinfをCondorと統合した。 この統合はユーザ透過であり、 粒度の大きい計算に対しオーバヘッドが比較的小さいことが分かった。 しかし、粒度の小さい計算に対しては、 計算の起動に対してのチェックポイントライブラリ転送のコスト以外に、 変則的なオーバヘッドが生じる。</div> </blockquote>



- **Grid環境におけるモニタリング手法の評価**  <span onmouseover="document.getElementById('hpc0108akiyama').style.display = 'block'"  onmouseout="document.getElementById('hpc0108akiyama').style.display = 'none'">[abst]</span>   
秋山智宏, 中田 秀基, 松岡 聡
, *情報処理学会ハイパフォーマンスコンピューティング研究会 Vol.2001, No.77*   , pp. 159-164  , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0108akiyama"> 広域ネットワーク上に分散した計算資源や情報資源を活用し、大規模計算を行うためのGrid と呼ばれる広域分散システムが注目されている。このような環境においては、故障検出、性能予測等のため、システム上の各資源の性能の計測が重要となる。Global Grid Forum 内の組織の一つである Grid Performance Working Group が、モニタリングシステムの基本的なアーキテクチャとXMLによるデータ形式を定義・提案しているが、この提案に対しては、1) アーキテクチャのスケーラビリティ、2)XML を用いたデータ表現のコスト、3) データ形式の拡張性、が検証されていない。本研究ではこれらを検証するために、GridRPC システムであるNinf 上に提案アーキテクチャの一部を実装し、評価をおこなった。その結果、アーキテクチャが現実的な設定範囲内では十分スケーラブルであり、XML を用いたデータ形式のコストは許容できる大きさであり、データ形式の拡張性も十分であることを確認した。</div> </blockquote>



- **GlobusによるGrid RPCシステムの実装と評価**  <span onmouseover="document.getElementById('hpc0108tanaka').style.display = 'block'"  onmouseout="document.getElementById('hpc0108tanaka').style.display = 'none'">[abst]</span>   
田中 良夫, 中田 秀基, 平野 基孝, 佐藤 三久, 関口 智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2001, No.77*   , pp. 165-170  , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0108tanaka"> 我々は，世界に広く普及することを目指したGrid RPCシステムであるNinf-Gの 設計および実装を進めている．本稿では，Ninf-Gの設計，実装および簡単な性 能評価について報告する．Ninf-GはGlobus Toolkitを用いて実装されており， ユーザ認証や資源管理など様々な要素をGlobusの機能に吸収させる事が可能と なる．また，Globus Toolkitを用いて実装されている他のグリッドソフトウェ アと同じようなインタフェースを提供することができる．LAN/WAN環境のいず れにおいてもGlobusの機能を用いたリモートライブラリ呼び出しのオーバーヘッ ドは1秒程度であった．</div> </blockquote>



- **高性能広域計算基盤 Grid へのポータルシステムの設計と実装**  <span onmouseover="document.getElementById('hpc0108suzumura').style.display = 'block'"  onmouseout="document.getElementById('hpc0108suzumura').style.display = 'none'">[abst]</span>   
鈴村 豊太郎, 松岡 聡, 中田 秀基
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2001, No.77*   , pp. 171-177  , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0108suzumura"> 本稿では，分散オブジェクト技術 Jini を基盤に構築した Computing Portalシステム JiPANG(Jini-based Portals Augment Grid) の概 要を示す．JiPANG は，Grid 上に任意に存在するサービスを一元的に管理する インフラストラクチャと，そこに登録されたサービスの統一的かつ透過的な使用 を可能にするプログラミング環境を提供する．JiPANG を用いることによって， Ninf や NetSolve, Globus 等の多様な Grid 技術に同一のライブラリからア クセスできる他，最新のバージョンのサービスが自動的にダウンロードされる 等，Grid 環境で動作するアプリケーション開発のコストを大幅に削減するこ とができる．</div> </blockquote>



- **Javaによるソフトウェア分散共有メモリシステムの構築 --- 広域環境への対応 ---**  <span onmouseover="document.getElementById('jdsm-pro0111-nakada').style.display = 'block'"  onmouseout="document.getElementById('jdsm-pro0111-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 早田恭彦, 小川宏高, 松岡聡
, *情報処理学会PRO研究会*    , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jdsm-pro0111-nakada"> ネットワークの高速化によって、広域環境下で計算資源を共有することが可能になりつつある。この環境下で、現在もっとも費用対性能が高い計算資源である、コモディティハードウェアを用いたPCクラスタを活用するために、安全で使用の容易なJavaによるソフトウェアDSM環境、JDSMを開発した。本システムは、1)DSMによる容易なプログラミング、2)プラットフォームポータビリティ、 3)sshによるアクセス制御、4)コードシッピング機能によるプログラムの自動転送、5)サーバプログラムの集中管理による管理の容易性などの特徴を持つ。本稿では、本システムの設計と実装について概説し、コードシッピングと認証に焦点をおいて、簡単に性能評価を行った。この結果、コードシッピング、認証ともに、実行時間に影響は与えるものの、問題のない範囲であることが確認された。</div> </blockquote>



- **Java向けソフトウェア分散共有メモリの実現**  <span onmouseover="document.getElementById('jdsm-swopp01-sohda').style.display = 'block'"  onmouseout="document.getElementById('jdsm-swopp01-sohda').style.display = 'none'">[abst]</span>   
早田恭彦, 中田秀基, 小川宏高, 松岡聡
, *情報処理学会PRO研究会*    , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jdsm-swopp01-sohda"> 近年のハードウェアの急速なコモディティ化とネットワーク技術の発展により，Grid Computingに代表されるWide Area HPCが盛んに研究されている．異なるアーキテクチャの計算機で構成されるGrid Computingにおいて，プラットフォームポータビリティとパフォーマンスポータビリティを満たすにはJava言語を利用するのが一つの適当な手法である．しかし，Javaをコモディティクラスタ上で動作させるためには，分散共有メモリを実現する必要があるが，既存の研究ではJVMへの変更が必要であり，ポータビリティが考慮されていない．そこで，本研究ではJavaのポータビリティを損なわないソフトウェア分散共有メモリのソフトウェアアーキテクチャを考察し，プロトタイプシステムJDSMを作成した．このソフトウェア分散共有メモリを異なる通信インターフェースを用いてコモディティクラスタ上で性能評価を行い，C言語での実現に比べメモリコンシステンシ処理が大きいことなどが分かった．</div> </blockquote>



- **Jiniを用いたComputing Portals Systemの開発**  <span onmouseover="document.getElementById('hpc0008suzumura').style.display = 'block'"  onmouseout="document.getElementById('hpc0008suzumura').style.display = 'none'">[abst]</span>   
鈴村豊太郎, 松岡 聡, 中田秀基, 関口 智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2000, No.57*   , pp. 57-62  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0008suzumura"> Jipang(Jini-based Portals Augment Grid)システムは，分散オブジェクト技術 Jiniを基盤に構築されたポータルシステムで，NinfやNetSolve, Globus等の各 Gridシステムが提供する資源を統合し，拡張性と柔軟性を持った大規模計算基盤 を構築する．また，その計算基盤を使用するためのユーザインタフェースとして ，プログミングインタフェースとGUIアプリケーションを提供する．ユーザは，このユー ザインタフェースを用いることによって，各Gridシステムの相違を意識 することがなく，Gridを簡便かつ透過的に使用することができるようになる． また，このとき，Gridシステムのクライアントパッケージをインストールする必 要はなく，Javaの実行時環境さえあればよい．本稿では，このJipangシステムが 実現する機能とそのアーキテクチャに関して述べる．</div> </blockquote>



- **Firewallに対応したGlobusによる広域クラスタシステムの構築と性能評価**  <span onmouseover="document.getElementById('hpc0008tanaka').style.display = 'block'"  onmouseout="document.getElementById('hpc0008tanaka').style.display = 'none'">[abst]</span>   
田中 良夫, 平野 基孝, 佐藤 三久, 中田 秀基, 関口 智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2000, No.57*   , pp. 63-68  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0008tanaka"> 我々はファイアウォールを利用しているサイトでGlobusを利用することができ るよう，Globusに新たな機能を組み込んだ．本稿では，Globusに新たに組み込 んだ機能の設計および実装と，ファイアウォールに対応したGlobusを用いて構 築した広域クラスタシステムの性能に関して報告する．広域クラスタシステム 上で木探索プログラムを実行した結果，通信量の抑制と負荷分散を効果的に行 なうことにより十分実用的な性能を得られることが分かった．</div> </blockquote>



- **Network Enabled Server System の設計**  <span onmouseover="document.getElementById('hpc0008nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0008nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 松岡 聡, 佐藤 三久, 関口 智嗣 
, *情報処理学会ハイパフォーマンスコンピューティング研究会， Vol.2000, No.57*   , pp. 69-74  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0008nakada"> Network Enabled Serverはグローバルコンピューティングのミドルウェアと して有望な形態である。 本稿では、Network Enabled Serverシステムの設計において設計上の選択点を整理し、 それぞれの設計方針の得失を検討する。 選択点としては、クライアント/サーバ間の接続の方式、 プロトコルの方式、セキュリティ機構の方式が挙げられる。 われわれはこの検討を踏まえて、Network Enabled Server System Ninfを新たに設計、実装した。 本稿では、このNinf新システムの設計に関して、 セキュリティ機構に重点をおいて紹介する。</div> </blockquote>



- **globusにおけるResource Managerの試作 -- グローバルコンピューティング環境の構築に向けて--**    
田中 良夫, 平野 基孝, 佐藤 三久, 中田 秀基, 関口 智嗣 
, *情報処理学会ハイパフォーマンスコンピューティング研究会, Vol.99, No.66*   , pp. 191-196  , 1999 



- **globusを用いたグローバルコンピューティングの性能評価**    
田中 良夫, 佐藤 三久, 中田 秀基, 関口 智嗣
, *情報処理学会システムソフトウェアとオペレーティングシステム研究会, Vol.99, No.32*   , pp. 71-76  , 1999 



- **クライアント・サーバ型のグローバルコンピューティングシステムの比較 --- Ninf, NetSolve, CORBA, Ninf-on-Globus の性能評価 ---**    
鈴村 豊太郎, 中川 貴之, 松岡 聡, 中田 秀基
, *情報処理学会研究会報告 99-HPC-34*    , 1999 



- **グローバルコンピューティングシステムNinfを用いた数値流体解析コンポーネント netCFD**    
佐藤三久, 草野 和寛, 中田秀基, 関口智嗣, 松岡聡
, *第10回計算流体シンポジウム*    , 1999 



- **Ninfによる遠隔計算資源アクセスシステムの構築とグローバルコンピューティングシステムの性能評価**    
佐藤 三久, 田中 良夫, 草野 和寛, 中田 秀基, 関口 智嗣,  長嶋 雲兵, 松岡 聡
, *情報処理学会研究報告 99-HPC-75*   , pp. 37-42  , 1999 



- **グローバルコンピューティングシミュレータの概要**  <span onmouseover="document.getElementById('hpc9903takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc9903takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 合田 憲人, 中田 秀基, 松岡 聡, 長嶋 雲兵
, *情報処理学会研究報告 99-HPC-75*   , pp. 31-36  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9903takefusa"> グローバルコンピューティングシステムが複数提案される一方，グローバルコンピューティングシステムのスケジューリング手法に対する考察が不十分である．これは大規模かつ再現性のある評価実験が困難であることに起因する．本稿ではグローバルコンピューティングシステムのスケジューリングアルゴリズムとそのフレームワークのための評価基盤を提供するシミュレータBricksを提案する．Bricksでは様々なシミュレーション環境やスケジュールアルゴリズムおよびスケジューリングに関するモジュールを設定可能である．また，これらのモジュールを既存グローバルコンピューティングシステムモジュールに置き換えることで，Bricks上での既存システムの機能試験を実施することができる．他システムのBricksへの組み込み例としてリソース情報の予測システムであるNWSを用いて本システムの評価実験を行ったところ，Bricksが実環境と同等の挙動を示すことを確認した．さらに，NWSがBricks上で正常に動作したことから，Bricksが既存の外部モジュールに対して機能試験環境を提供できることを示した．</div> </blockquote>



- **広域計算システムNinf におけるユーザ認証**  <span onmouseover="document.getElementById('hpc9808nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc9808nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 松岡 聡, 佐藤 三久, 関口 智嗣
, *情報処理学会研究報告 98-HPC-72*   , pp. 79-84  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9808nakada"> 昨今の急速なネットワーク技術の発展により分散高性能計算が可能となり、これを支援するソフトウェアフレームワークとしてわれわれのNinfを含む幾つかのシステムが提唱されており、技術的にも成熟しつつある。しかし、この種のテクノロジの普及に必要とされるユーザの制限や計算機使用量に応じた課金、データの機密性保持といったシステムの社会的側面の研究は途上にある。本稿ではこの種の要請に答えるためのセキュリティ機構の一部であるユーザ認証をとりあげ、分散高性能計算に要請される認証機構について論じる。認証の強度とシステム利用の簡便性はトレードオフの関係にあり、システムの使用形態に応じて複数の認証機構を使い分けることが重要である。</div> </blockquote>



- **Ninfシステムにおけるジョブスケジューラの実装と予備的評価**  <span onmouseover="document.getElementById('hpc9808takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc9808takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 中田 秀基, 合田 憲人, 小川 宏高, 松岡 聡, 長嶋 雲兵
, *情報処理学会研究報告 98-HPC-72*   , pp. 73-78  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9808takefusa"> ネットワーク技術の発展により，グローバルコンピューティングシステムが複数提案されているが，その計算リソースを有効に利用するための議論が十分になされていない．特に，広域ネットワーク経由の計算固有の変動や不安定さを考慮して，計算リソースを適切に割り当てるスケジューリング手法が必要である．本稿では，グローバルコンピューティングにおいてアプリケーションスケジューリングとジョブスケジューリングを統合するための階層化されたスケジューリングフレームワークを提案するとともに，それに準拠したNinfシステムのメタサーバスケジューリングフレームワークの実装について述べる．さらに，実環境と性能評価モデルを用いてスケジューリング手法の評価を行い，グローバルスケジューリングにおける課題を明らかにした．</div> </blockquote>



- **ネットワーク計算用行列工房: Matrix Workshopによる性能評価システム**  <span onmouseover="document.getElementById('hpc9808matsubara').style.display = 'block'"  onmouseout="document.getElementById('hpc9808matsubara').style.display = 'none'">[abst]</span>   
松原 有里, 中田 秀基, 関口 智嗣, 建部 修見, 長嶋 雲兵
, *情報処理学会研究報告 98-HPC-72*   , pp. 61-66  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9808matsubara"> 科学技術計算における行列の果たす役割は非常に大きい．また，行列データは多種多様な性質とサイズを有し，特に大規模なものについては多様な行列データをユーザが自由に作成するのが困難であり，データコンテンツサービスの対象となるのに適している．以上の認識から我々は行列を対象としたサービス「ネットワーク計算用行列工房：Matrix Workshop」の開発を行なっている．本システムでは，サイズに自由度が与えられており，性質の明らかな行列の提供により信頼性の高い行列演算アルゴリズム，プログラムのテストをサポートすることが可能となった．これにより，計算機システムの評価を行なうことも可能となっている，最後に，本システムを用いた性能評価システムについてLinpack Benchmarkを用いた評価をおこなう．</div> </blockquote>



- **証明支援系の図式によるインターフェイス**    
木下佳樹, 高橋孝一, 中田秀基
, *コンピュータソフトウェア vol.14 no.3*    , 1997 



- **強フィルタ双模倣を基にした部分仕様の段階的合成**    
磯部祥尚, 中田秀基, 佐藤豊, 大蒔和仁
, *第10回 回路とシステム軽井沢ワークショップ論文集*    , 1997 



- **高性能広域計算システムNinfのスケジューリングに関する予備的考察**    
小川宏高, 竹房あつ子, 中田秀基, 合田憲人, 松岡 聡
, *情報処理学会研究報告 97-HPC-67*    , 1997 



- **ネットワーク数値情報システムNinf: マルチクライアント環境での性能**  <span onmouseover="document.getElementById('hpc9703takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc9703takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 小川宏高, 松岡 聡, 佐藤三久, 中田秀基, 関口智嗣, 長嶋雲兵
, *情報処理学会研究報告 97-HPC-21*   , pp. 3-8  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9703takefusa"> ネットワーク数値情報システムNinfは，広域ネットワークに分散した計算資源や情報資源を利用して高速・高性能・高品質な科学技術計算を実現するための基盤システムである．本稿ではNinfの全体構成について述べるとともに，Linpack benchmarkを用いて，シングル/マルチクライアント環境での本システムの性能評価を実施した．この結果，現実的な広域分散利用条件でのNinfシステムの実用性，堅牢性を確認した．また，既存のベクトルパラレルマシンを始めとする並列計算機がNinfによってネットワーク計算資源として有効に活用されることを示した．</div> </blockquote>



- **Ninf による広域分散並列計算**    
中田秀基, 高木浩光, 松岡 聡, 長嶋雲兵, 佐藤 三久, 関口智嗣
, *情報処理学会研究報告 97-HPC-21*   , pp. 9-14  , 1997 



- **フィルタ強等価を基にした部分的仕様の合成方法**    
磯部祥尚, 中田秀基, 佐藤豊, 大蒔和仁
, *ソフトウェア工学の基礎III (FOSE&#x27;96),近代科学社レクチャーノート17*   , pp. 1-8  , 1996 



- **分散メモリ計算機用 Ninf API の実現に向けて**  <span onmouseover="document.getElementById('hpc9608ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc9608ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 松岡 聡, 中田秀基, 佐藤 三久, 関口 智嗣
, *情報処理学会研究報告 96-HPC-81*   , pp. 159-164  , 1996 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9608ogawa"> ネットワーク数値情報ライブラリNinf　(etwork　based　Information　library　for　High　Performance　Computin)は，広域に分散した計算資源や情報資源を利用した超分散並列計算の基盤を提供するソフトウェアシステムである．本稿では，このNinfシステム上で分散メモリ型並列計算機を計算資源として利用する場合に，フロントエンドマシンやI/Oプロセッサ等の単一ノードで動作するNinfサーバに計算情報が集中して律速となる問題を指摘する．この問題を解決するために，初期データ分散を記述するための共通のAPIを提供すると共に，クライアントとの接続を各ノードに対して適切に順次ハンドオフしていく機構の導入を提案する．また，ハンドオフ機構のコア部分を富士通のAP1000上に実現し予備評価を行った結果，16％の性能向上を得た．</div> </blockquote>



- **ネットワーク数値情報ライブラリ Ninf: システム実装と評価**  <span onmouseover="document.getElementById('hpc9608sekiguchi').style.display = 'block'"  onmouseout="document.getElementById('hpc9608sekiguchi').style.display = 'none'">[abst]</span>   
関口智嗣, 中田秀基, 佐藤 三久, 長嶋雲兵, 松岡 聡
, *情報処理学会研究報告 96-HPC-81*   , pp. 153-158  , 1996 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9608sekiguchi"> 科学技術計算におけるGlobal　Computingを実現する基盤システムとしてネットワーク数値情報ライブラリNinf　(etwork　based　Information　Library　for　Global　World?Wide　Infrastructur)を提案している．Ninfでは広域ネットワーク上に分散された計算資源や情報資源へのアクセスを容易に実現することによりハイパフォーマンスコンピューティングを支援することを目標とする．サーバーをインターネット上に複数設定し，遠隔地のユーザは提供されたインターフェース関数を通じてNinfのライブラリ関数を呼び出すだけで，Ninfサービスを受けられる．本稿ではNinfシステムの概観と実現について述べ，Ninf?RPCを用いたLinpackによる性能評価を行う．この結果，問題サイズが小さくてもNinfを用いたネットワークコンピューティングの現実的可能性を実証することができた．</div> </blockquote>



- **ネットワーク数値情報ライブラリ：Ninfを用いた数値計算環境システムの開発−NinfCalcの試作**    
新居由佳子, 高木浩光, 長嶋雲兵, 中田秀基, 佐藤三久, 松岡聡, 関口智嗣
, *情報処理学会第53回全国大会*    , 1996 



- **ネットワーク数値ライブラリ Ninf におけるメタサーバアーキテクチャ**  <span onmouseover="document.getElementById('hpc9603nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc9603nakada').style.display = 'none'">[abst]</span>   
中田秀基, 草野貴之, 松岡聡, 佐藤三久, 関口智嗣
, *情報処理学会研究報告 96-HPC-22*   , pp. 77-82  , 1996 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9603nakada"> ネットワーク数値情報ライプラリ Ninf (Network based Information library for High Performance Computing)は、高速なネットワークを前提として、主に数値演算の分野において、計算自体を多くのユーザに提供することを目指したシステムてある。本稿では、Ninfシステムを講築する要素の一つであるメタサーバに関して、そのアーキテクチヤを示し、簡単な性能予備評価を示す。メタサーバは、サーバとクライアントの間にたちサーバの場所をクライアントに対して隠蔽する役割を果たす。また、メタサーバを用いることにより、簡単な分散並列計算が可能になる。
To establish a framework of information sharing in the numerical computation area, we have proposed the Ninf, Network based information library for high performance computing. In this paper, we show a Meta Server architecture, which is a component of the Ninf system. Meta Server stand between the Server and the Client and hides the Server from the Client. It also enables easy distributed concurrent computation.</div> </blockquote>



- **ネットワーク数値情報ライブラリ Ninf のための RPCシステムの概要**    
中田秀基, 佐藤三久, 関口智嗣
, *電子技術総合研究所 Tecnical Report TR-95-28*    , 1995 



- **flengの動的粒度制御のための静的解析手法**    
中田秀基, 小池汎平, 田中英彦
, *情報処理学会研究報告 プログラミング−言語・基礎・実践−*    , 1994 



- **PIE64におけるCommitted-Choice型言語flengの動的粒度制御のためのコンパイル手法**    
中田秀基, 小池汎平, 田中英彦
, *情報処理学会 第49回全国大会*    , 1994 



- **ゴールの融合によるCommitted-Choice型言語Flengの最適化**    
荒木拓也, 中田秀基, 小池汎平, 田中英彦
, *情報処理学会 第49回全国大会*    , 1994 



- **Committed-Choice型言語Flengにおける静的負荷分割のPIE64上での実装および評価**    
村上聡, 荒木拓也, 中田秀基, 小池汎平, 田中英彦
, *情報処理学会 第49回全国大会*    , 1994 



- **データフロー解析に基づくCommitted Choice型言語のスケジューリング**    
中田秀基, 小池汎平, 田中英彦
, *情報処理学会 第48回全国大会*    , 1994 



- **データフロー解析に基づくCommitted Choice型言語Flengの静的負荷分割**    
荒木拓也, 中田秀基, 小池汎平, 田中英彦
, *情報処理学会 第48回全国大会*    , 1994 



- **高並列推論エンジンPIE64 研究経過報告 -- ソフトウェア --**    
中田秀基, 小池汎平, 吉田実, 舘村純一, 白木長武, 田中英彦
, *情報処理学会 第46回全国大会*    , 1993 



- **Immutable Object に対する継承の導入による Mutable Object の継承の実現**    
中田秀基, 田中英彦
, *WOOC&#x27;93*    , 1993 



- **Committed Choice 言語へのオブジェクトの導入**    
中田秀基, 田中英彦
, *情報処理学会 第45回全国大会*    , 1992 



- **高並列言語 fleng における型システムの導入**    
中田秀基, 田中英彦
, *情報処理学会研究報告 プログラミング−言語・基礎・実践−*    , 1992 



- **オブジェクト間の関係に基づいた記述モデル Distributed Object Connection**    
中田秀基, 小池汎平, 田中英彦
, *WOOC &#x27;92*    , 1992 



- **オブジェクト間の関係に基づいた記述モデル Distributed Object Connection**    
中田秀基, 小池汎平, 田中英彦
, *オブジェクト指向コンピューティングI*    , 1992 



- **オブジェクト間の関係に基づいた記述モデル Distributed Object Connection**    
中田秀基, 小池汎平, 田中英彦
, *情報処理学会 第43回全国大会*    , 1991 



- **Distributed Object Connection:オブジェクト間の関係に基づいた記述モデル**    
中田秀基, 小池汎平, 田中英彦
, *情報処理学会研究報告 プログラミング−言語・基礎・実践−*    , 1991 



- **概念設計支援のためのフィジカルフィーチャーの研究 (第4報) - フィジカルフィーチャーデータベースの構築 -**    
山本文緒, 中田秀基, 加藤雄三, 大谷邦明, 川合稔, 松本幹男, 富山哲男, 吉川弘之
, *精密機械工学会春季全国大会*    , 1991 



- **概念設計支援のためのフィジカルフィーチャーの研究 (第3報) - 無定義語・基本語に関する考察-**    
山本文緒, 中田秀基, 富山哲男, 吉川弘之
, *精密機械工学会秋季全国大会*    , 1990 



- **部分抽象化モデルを用いた定性推論**    
桐山孝司, 中田秀基, 富山哲男, 吉川弘之
, *人工知能学会 第4回全国大会*    , 1990 



- **概念設計のための定性推論システムに関する研究**    
中田秀基, 桐山孝司, 富山哲男, 吉川弘之
, *精密機械工学会春季全国大会*    , 1990 



        
