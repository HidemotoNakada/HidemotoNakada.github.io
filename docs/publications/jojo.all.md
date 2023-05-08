---
layout: default
---
# Jojo 

- **オーバーレイスケジューラJojo3 のグリッドRPC への適用** [[Paper](dataDir/swopp08nakada.pdf)]  <span onmouseover="document.getElementById('swopp08nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp08nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2008−HPC-116*   , pp. 91-96  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp08nakada"> 複数サイトにまたがる大量の計算資源を用いた計算が, 一般ユーザにとっても現実のものとなりつつある.我々は, このような環境で稼働するアプリケーションレベルスケジューラを容易に記述できる環境として, オーバーレイスケジューラJojo3を提案している. Jojo3はさまざまな環境上にオーバレイするレイヤとして機能し, プロセスの起動, およびプロセス間の通信機能を提供する.我々は, Jojo3の有用性を検証するため, GridRPC 実装の一つであるNinf-G5への適用を行った. Ninf-G5はリモート実行モジュールの起動モジュールと, クライアントとリモート実行モジュール間の通信プロキシモジュールを独立したプロセスとしてコアモジュールの外部に持つ設計となっている. 既存のモジュールをベースにJojo3を用いるように修正した結果, 数十行から数百行程度の比較的軽微な修正によって, Jojo3への適用が可能であることが確認できた. これによって, Jojo3の提供するAPIの機能と記述力が十分であることが確認できた.本稿では, この過程で実装した, Python言語によるJojo3クライアントライブラリを合わせて紹介する.</div> </blockquote>



- **オーバレイスケジューラ Jojo3 の提案** [[Paper](dataDir/hpc0803nakada.pdf)] [[Slides](dataDir/hpc0803nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0803nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0803nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-114*   , pp. 169-174  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0803nakada"> グリッド技術およびクラスタ技術の発展によって， 個々のユーザがアクセスできる計算機の 総量は爆発的に増大した．しかしこれらの計算機を同時に利用する アプリケーションプログラムを記述することは困難であり， 膨大な計算資源を有効に活用できているアプリケーションは限定されている．アプリケーションプログラムの記述が困難な理由の一つは， 環境の不均質性および非対称性にある． 計算機資源は，それぞれ異なるバッチスケジューリングシステム およびグリッドミドルウェアで管理されており不均質 ネットワークの接続性には非対称性があり，ノード間通信も必ず 可能なわけではない．本稿では，この不均質性と非対称性をアプリケーションプログラマから隠蔽する オーバレイスケジューラを提案し， その1実装であるJojo3の設計と実装について述べる． オーバレイスケジューラは，グリッドミドルウェアおよび バッチスケジューリングシステムで起動され， 均質なインターフェイスをアプリケーションプログラムに 対して提供する． アプリケーションプログラマは，オーバレイスケジューラを 利用することで，比較的容易にアプリケーションを記述することができる．</div> </blockquote>



- **Autonomically-Adapting Master-Worker Programming Framework for Multi-Layered Grid-of-Clusters** [[Paper](dataDir/hpcasia07aoki.pdf)] [[Slides](dataDir/hpcasia07aoki_slide.pdf)]  <span onmouseover="document.getElementById('hpcasia07aoki').style.display = 'block'"  onmouseout="document.getElementById('hpcasia07aoki').style.display = 'none'">[abst]</span>   
Hitoshi Aoki, Hidemoto Nakada, Kouji Tanaka, Satoshi Matsuoka
, *Proc. of HPC Asia 2007*   , pp. 3-10  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcasia07aoki"> Past work on “programming for the grid” for compute-intensive applications have largely focused on two ex-tremes, either loosely-coupled, cycle-scavenging, desktop grid environments such as BOINC or Condor vs. tightly-coupled metacomputing systems such as MPICH-G2 or GridMPI. Neither is really appropriate for class of applications that are middle-tier, e.g., fine-grained branch-and-bound master-worker applications where the running time of individual jobs may range from less than tenth of a second to few minutes, and communication intervals being further fine-grained.Our new grid program- mingmiddleware and framework, Jojo2, allows efficient programming of fine-grained, hierarchicalmaster-worker applications on a grid-of-clusters environment. During programming, much of the complexities associated with hierarchy and changes in the underlying resources are hidden away or isolated, and the user need not be aware of physical configuration of the resources. Even during execution, new compute resources can be explicitly be added via batch submissions, and are subsequently automatically detected and incorporated in the system. Evaluation of Jojo2 on real master-worker applications proved very positive, both on TSUBAME, a supercomputing cluster with 10,000 nodes, as well as a nationwide testbed involving more than 800 CPUs and a number of 100-node class clusters. In both cases, applications on Jojo2 not only scaled very well, but autonomously adapted to bulk changes in the order of hundreds of underlying resources, both resources being added as well as those going away.</div> </blockquote>



- **動的なノード群構成機構を備えた階層型グリッド環境 Jojo2** [[Paper](dataDir/sacsis06aoki.pdf)] [[Slides](dataDir/sacsis06aoki_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06aoki').style.display = 'block'"  onmouseout="document.getElementById('sacsis06aoki').style.display = 'none'">[abst]</span>   
青木 仁志, 中田 秀基, 田中 康司, 松岡 聡
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 101-108  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06aoki"> グリッドの階層構造に適合したプログラミングモデルの一つとして階層型マスタ・ワーカ方式がある。しかし既存の階層型マスタ・ワーカ方式を実現するミドルウェアは、動的なノード群構成や動的なノードの参加・脱退といった機構が欠如しているため管理コストが大きい。我々は動的なノード群構成機構を備えた階層型グリッドプログラミング環境Jojo2 を提案する。Jojo2 はグリッドの階層構造に合致した動的なノード構成を行い、自律的なノードの発見、動的なノードの参加・脱退を行うことで大規模グリッド環境においても管理コストを軽減することができる。さらに動的なノードの参加・脱退をハンドルするプログラミングAPI を提供することで、動的構成に対応したプログラムを容易に記述できる。また予備的性能評価を行い、その結果、ノードの参加・脱退のAPI の有効性と、ノードの参加・脱退のコストが小さいことを確認した。</div> </blockquote>



- **大規模グリッド環境下での Jojo の評価**    
青木仁志, 中田秀基, 松岡聡
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5 (ポスター発表)*    , 2005 



- **Parallelization of Phylogenetic Tree Inference using Grid Technologies** [[Paper](dataDir/lsgrid04yamamoto.pdf)] [[Slides](dataDir/lsgrid04yamamoto_slide.pdf)]  <span onmouseover="document.getElementById('lsgrid04yamamoto').style.display = 'block'"  onmouseout="document.getElementById('lsgrid04yamamoto').style.display = 'none'">[abst]</span>   
Yo Yamamoto, Hidemoto Nakada, Hidetoshi Shimodaira, Satoshi Matsuoka
, *LSGrid 2004*   , pp. 103-116  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="lsgrid04yamamoto"> The maximum likelihood method is considered as one of the most reliable methods for phylogenetic tree inference. However, as the number of species increases, the approach quickly loses its applicability due to explosive exponential number of trees that need to be considered. An earlier work by one of the authors [3] demonstrated that, by decomposing the trees into fragments called splits, and calculating the individual likelihood of each (small) split and combining them would result in a very close approximation of the true maximum likelihood value, as well as achieving significant reduction in computational cost. However, the cost was still significant for a practical number of species that need to be considered. To solve this problem, we further extend the algorithm so that it could be effectively parallelized in a Grid environment using Grid middleware such as Ninf and Jojo, and also applied combinatorial optimization techniques. Combined, we achieved over 64 times speedup over our previous results in a testbed of 16 nodes, with favorable speedup characteristics.</div> </blockquote>



- **A Java-based Programming Environment for the Grid: Jojo** [[Slides](dataDir/ccgrid04nakada_slide.pdf)]  <span onmouseover="document.getElementById('ccgrid04nakada').style.display = 'block'"  onmouseout="document.getElementById('ccgrid04nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Satoshi Matsuoka, Satoshi Sekiguchi
, *Proceedings of CCGrid 2004*   , pp. 51-58  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ccgrid04nakada"> Despite recent developments in higher-level middleware for the Grid supporting high level of ease-of-programming, hurdles for widespread adoption of Grids remain high, due to (1) assumption of peer-to-peer connectivity of all Grid nodes, as well as (2) lack of scalable programming and deployment support. We propose a Java-based programming environment for a hierarchically organized Grid named Jojo, that allow seamless utilization of privately addressed clusters. Jojo provides several features, including secure private remote invocation using Globus GRAM and ssh/rsh to privately addressed nodes in clusters, intuitive message passing API suitable for overlapped execution using multiple threads, and automatic user/system program staging. Using Jojo, users can easily construct and execute parallel distributed applications on the Grid. We show the design and implementation of its programming API, a working example, as well as preliminary performance evaluation results that prove the effectiveness of hierarchal execution.</div> </blockquote>



- **グリッド技術を用いた進化系統樹推定の並列化** [[Paper](dataDir/hokke04yamamoto.pdf)]  <span onmouseover="document.getElementById('hokke04yamamoto').style.display = 'block'"  onmouseout="document.getElementById('hokke04yamamoto').style.display = 'none'">[abst]</span>   
山本洋, 中田秀基, 下平英寿, 松岡聡
, *情報処理学会研究報告 2004-HPC-97*   , pp. 181-186  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04yamamoto"> 進化系統樹の推定では最尤法を用いた手法が最も優れた推定法の1つとされているが、最尤法の計算量は大きく、種の個数が増えると系統樹の個数は莫 大となるため全系統樹の尤度を求めることは事実上不可能となる。系統樹の構成要素であるスプリットの尤度を最尤法によって計算し、スプリットの尤度を用い た行列計算によって系統樹の尤度を近似計算する手法が提案されている。しかし、種の個数がさらに増大すると、近似計算であってもすべての系統樹に対して行 うことは困難になる。本研究では、系統樹の推定を系統樹空間における探索問題とみなし、最適化手法を適用することで、近似計算の対象となる系統樹の個数を 削減する。また、グリッドミドルウェアを用いたマスタ・ワーカ方式を採用し、尤度計算および最適化手法の並列実行を可能にした。生物9種の系統樹推定にお いて16ワーカを用いた結果、64.0倍の性能向上が得られた。</div> </blockquote>



- **Jojoによる遺伝的プログラミングの並列化** [[Paper](dataDir/hokke04tokuda.pdf)]  <span onmouseover="document.getElementById('hokke04tokuda').style.display = 'block'"  onmouseout="document.getElementById('hokke04tokuda').style.display = 'none'">[abst]</span>   
徳田拓, 田中康司, 中田秀基, 松岡聡
, *情報処理学会研究報告 2004-HPC-97*   , pp. 187-192  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04tokuda"> 進化系統樹の推定では最尤法を用いた手法が最も優れた推定法の1つとされているが、最尤法の計算量は大きく、種の個数が増えると系統樹の個数は莫 大となるため全系統樹の尤度を求めることは事実上不可能となる。系統樹の構成要素であるスプリットの尤度を最尤法によって計算し、スプリットの尤度を用い た行列計算によって系統樹の尤度を近似計算する手法が提案されている。しかし、種の個数がさらに増大すると、近似計算であってもすべての系統樹に対して行 うことは困難になる。本研究では、系統樹の推定を系統樹空間における探索問題とみなし、最適化手法を適用することで、近似計算の対象となる系統樹の個数を 削減する。また、グリッドミドルウェアを用いたマスタ・ワーカ方式を採用し、尤度計算および最適化手法の並列実行を可能にした。生物9種の系統樹推定にお いて16ワーカを用いた結果、64.0倍の性能向上が得られた。</div> </blockquote>



- **並列組合せ最適化システムjPoPの分枝限定法の実装** [[Paper](dataDir/comsys04nakagawa.pdf)]  <span onmouseover="document.getElementById('comsys04nakagawa').style.display = 'block'"  onmouseout="document.getElementById('comsys04nakagawa').style.display = 'none'">[abst]</span>   
中川伸吾, 中田秀基, 松岡聡
, *コンピュータシステム・シンポジウム論文集*   , pp. 85-92  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys04nakagawa"> 多次元パラメータ関数の最適値を求める組合せ最適化問題の解法としては、分枝限定法や遺伝的アルゴリズムなどが知られている。これらの解法はグ リッド上での実行に適しているが、グリッド上での分散並列プログラミングは煩雑である上、実行時にも実行ファイルや設定ファイルをユーザがインストールし なければならないといった問題がある。我々はこれらの問題を解決し、最適化問題解法のグリッド上での実行を容易にするシステムjPoP を開発している。本稿では、jPoP の分枝限定法用のテンプレートクラスであるjPoP-BB の設計およびマスタ・ワーカ方式を用いたプロトタイプの並列実装について述べる。また、0-1 ナップサック問題を用いた評価に関しても報告する。評価の結果、本実装は大規模なシステム上でも実行でき、かつ一般的な問題のほとんどに対して実行時間の 面から十分な並列効果が得られることがわかった。</div> </blockquote>



- **遺伝子ネットワーク推定のための並列GPアルゴリズムの評価** [[Paper](dataDir/mps04tanaka.pdf)]  <span onmouseover="document.getElementById('mps04tanaka').style.display = 'block'"  onmouseout="document.getElementById('mps04tanaka').style.display = 'none'">[abst]</span>   
田中康司, 中田秀基, 岡本正宏, 松岡聡
, *情報処理学会シンポジウムシリーズ 数理モデル化と問題解決シンポジウム論文集 Vol.2004, No.12*   , pp. 171-178  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="mps04tanaka"> 遺伝子ネットワーク推定とは，遺伝子の発現量データ系列から複数の遺伝子間における制御関係を推測するものである．この相互関係は，非線形連立微 分方程式によって表現される．これまで，遺伝子ネットワーク推定は，S-system 表記の微分方程式を用いたものが一般的であったが，S-system 表記の微分方程式は質量作用則表記の近似式であり，遺伝子間の具体的な相互関係を推定することが困難であった．そこで我々は，質量作用則に基づいた非線形 連立微分方程式表記を採用し，進化的計算の一手法である遺伝的プログラミングを用いて，データ系列から相互作用を示す関数を自動推定するシステムを開発し た．本稿では，開発したシステムの係数最適化部分に注目し，導入した効率的な探索手法を評価した．その結果，導入した手法は解を効率的に探索できることが わかった．</div> </blockquote>



- **並列組合せ最適化システム jPoP の分枝限定法の実装**  <span onmouseover="document.getElementById('mps03nakagawa').style.display = 'block'"  onmouseout="document.getElementById('mps03nakagawa').style.display = 'none'">[abst]</span>   
中川 伸吾, 飯野 彰子, 中田 秀基, 松岡 聡
, *MPSシンポジウム論文集 情報処理学会シンポジウムシリーズ Vol.2003 No.14*   , pp. 29-36  , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="mps03nakagawa"> 多次元パラメータ関数の最適値を求める組合せ最適化問題の解法としては、分枝限定法や遺伝的アルゴリズムなどが知られている。これらの解法はグリッド上での実行に適しているが、グリッド上での分散並列プログラミングは煩雑である上、実行時にも実行ファイルや設定ファイルをユーザがインストールしなければならないといった問題がある。我々はこれらの問題を解決し、最適化問題解法のグリッド上での実行を容易にするシステムjPoP を開発している。本稿では、jPoP の分枝限定法用のテンプレートクラスであるjPoP-BB の設計およびマスタ・ワーカ方式を用いたプロトタイプの並列実装について述べる。また、0-1 ナップサック問題を用いた評価に関しても報告する。評価の結果、本実装では、他ノードの影響による限定操作が生じない、並列化に理想的な問題に関しては並列効果が得られるものの、一般的な問題に関しては負荷が不均等になり並列効果が得られないことがわかった。</div> </blockquote>



- **Javaによる階層型グリッド環境Jojoの設計と実装**  <span onmouseover="document.getElementById('acs03nakada').style.display = 'block'"  onmouseout="document.getElementById('acs03nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 松岡 聡, 関口 智嗣
, *情報処理学会論文誌コンピューティングシステム Vol.44 No. SIG 11*   , pp. 46-56  , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs03nakada"> 本稿では、グリッド環境でのJavaプログラミングを支援する実行環境Jojo について述べる。JojoはJavaを用いて実装された、階層構造を持つ環境に適した分散実行環境で、階層構造に適した柔軟な多階層実行機構、 Globusやsshを用いた安全な起動と通信、直感的で並列実行に適したメッセージパッシングAPI、プログラムコードの自動アップロードといった特徴を持つ。 Jojoを用いれば、グリッド上で動作する並列分散システムが非常に容易に構築できる。 本稿ではJojoの設計と実装の詳細、プログラミングAPI、設定ファイル、簡単なプログラム例を示す。さらにマスタ・ワーカプログラムを用いた性能評価を行い多階層構造の有効性を確認する。</div> </blockquote>



- **Javaによる階層型グリッド環境Jojoの設計と実装**  <span onmouseover="document.getElementById('sacsis03nakada').style.display = 'block'"  onmouseout="document.getElementById('sacsis03nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 松岡 聡, 関口 智嗣
, *SACSIS 2003*   , pp. 113-120  , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis03nakada"> 本稿では、グリッド環境でのJavaプログラミングを支援する実行環境Jojo について述べる。JojoはJavaを用いて実装された、階層構造を持つ環境に適した分散実行環境で、階層構造に適した柔軟な多階層実行機構、 Globusやsshを用いた安全な起動と通信、直感的で並列実行に適したメッセージパッシングAPI、プログラムコードの自動アップロードといった特徴を持つ。 Jojoを用いれば、グリッド上で動作する並列分散システムが非常に容易に構築できる。 本稿ではJojoの設計と実装の詳細、プログラミングAPI、設定ファイル、簡単なプログラム例を示す。さらにマスタ・ワーカプログラムを用いた性能評価を行い多階層構造の有効性を確認する。</div> </blockquote>



- **A Java-based Programming Environment for the Grid: Jojo**  <span onmouseover="document.getElementById('ccgrid03posterNakada').style.display = 'block'"  onmouseout="document.getElementById('ccgrid03posterNakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Satoshi Matsuoka, Satoshi Sekiguchi
, *CCGrid 2003 Poster*    , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ccgrid03posterNakada"> This poster introduces a java-based programming environment for the Grid, called Jojo. Jojo is a distributed programming environment implemented in Java. It is suitable for a grid environment consists of cluster of clusters. Jojo provides several features, including secure remote invocation using Globus GRAM, intuitive message passing API suitable for parallel execution and automatic user program staging. Jojo helps users to construct their own parallel-distributed application on the Grid. In the poster, we show design and implementation of Jojo, its programming API and a working program example. We also show preliminary performance evaluation result.</div> </blockquote>



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



- **Grid環境に適した並列組み合わせ最適化システムの提案**  <span onmouseover="document.getElementById('swopp02akiyama').style.display = 'block'"  onmouseout="document.getElementById('swopp02akiyama').style.display = 'none'">[abst]</span>   
秋山 智宏, 中田 秀基, 松岡 聡, 関口 智嗣
, *情報処理学会研究報告 2002-HPC-91*   , pp. 143-148  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp02akiyama"> 多次元パラメータ関数の最適値を求める組合せ最適化問題の解法としては、分枝限定法や遺伝的アルゴリズムなどが知られている。これらの解法は自明な並列度が大きく、粒度の調整も比較的容易なためGrid 上での実行に適している。しかしGrid 環境での分散並列プログラミングは煩雑である上、実行時にも実行ファイルや設定ファイルをユーザがインストールしなければならないといった問題がある。われわれはこれらの問題を解決し、最適化問題解法のGrid 上での実行を容易にするシステムjPoP を提案する。jPoP は各解法に対してテンプレートとなるクラスを提供しプログラミングを支援する。また、動的なプログラムのアップロードによってGrid 上での実行を支援する。本稿ではjPoPの概要と遺伝アルゴリズム問題のテンプレート、さらにjPoP の実装について述べる。</div> </blockquote>



        
