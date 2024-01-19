---
layout: default
---
# Ninf 

- **ポストペタスケール計算機環境に向けた高可用分散協調セルフスケジューリング機構の提案** [[Slides](dataDir/hpc1210takefusa_slide.pdf)]  <span onmouseover="document.getElementById('hpc1210takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc1210takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 中田 秀基, 池上 努, 田中 良夫
, *情報処理学会研究報告2011-HPC-136*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1210takefusa"> ポストペタスケール計算機環境では，階層型タスク並列が有望なプログラミングモデルの 1 つであると考えられている．タスク並列型アプリケーションでは，タスクの再実行や冗長実行により，耐障害性を備えるように設計することは比較的容易であるが，その実装は容易ではない．よって，我々はそのようなアプリケーションの開発を容易にする耐障害アプリケーションフレームワークの開発を目指している．アプリケーションフレームワークでは，故障箇所を避けながら適切な計算ノード上でタスクを実行する資源管理機構が必要となるが，ポストペタスケール計算機環境でのスケーラビリティや，資源管理機構そのものの耐障害性，資源管理情報の永続化が課題となる．本稿では，スケーラブルかつ可用性の高い分散協調セルフスケジューリング機構を提案・設計する．提案する資源管理機構では，複数資源管理プロセスを分散協調させてタスクキューを管理し，タスクキュー内のタスクを各計算ノード上の実行デーモンプロセスが自律的に取得して実行する．また，各計算ノードの死活監視を行い，実行中に故障が発生した場合は選択的に再実行または削除する仕組みを提供する．資源管理プロセスの耐障害性と資源管理情報の永続化の実現方法を検討するため， Apache ZooKeeper を用いてこれらの機能を試験実装し，提案資源管理機構の妥当性と課題の明確化を行う</div> </blockquote>



- **ポストぺタスケール高性能計算に向けた階層的プログラミングモデルの提案** [[Paper](dataDir/hpc1203ikegami.pdf)]  <span onmouseover="document.getElementById('hpc1203ikegami').style.display = 'block'"  onmouseout="document.getElementById('hpc1203ikegami').style.display = 'none'">[abst]</span>   
池上 努, 田中 良夫, 中田 秀基, 高野 了成, 関口 智嗣
, *情報処理学会研究報告2011-HPC-133*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1203ikegami"> 次世代スパコンで想定される百万コア越の大並列環境を対象に、高効率かつ頑健な アプリケーションを実装する上で必要となるアルゴリズムとプログラミング手法につ いて考察する。まず、マスタ・ワーカ型の実装が可能であり、かつワーカの障害に対 して寛容なアルゴリズムを紹介する。次いでワーカの動的な増減を可能にするプログ ラミング手法として、グリッド環境で実績のある、遠隔手続き呼出し (RPC) と MPI を組合せたハイブリッド型の手法を提案する。グリッド環境での経験を元に、従来型 RPC に対する改善案を検討する。</div> </blockquote>



- **Transparent collaboration of GridRPC middleware using the OGF standardized GridRPC data management API**  <span onmouseover="document.getElementById('isgc2012').style.display = 'block'"  onmouseout="document.getElementById('isgc2012').style.display = 'none'">[abst]</span>   
Yves Caniou, Gael le Mahec, Hidemoto Nakada, Eddy Caron
, *International Symposium on Grids and Clouds (ISGC)*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="isgc2012"> In september 2011, the Open Grid Forum standardized the document &quot;Data Management API within the GridRPC&quot; [1] which discribes an optional API that extends the GridRPC standard [2]. Used in a GridRPC middleware, it provides a minimal set of functions to handle a large set of data operations among which: movements, replications, migrations, data prefetch and persistency. In this paper, we present a basic implementation of the API that we have integrated in two different middleware, respectively DIET [3] and NINF [4]. We have conducted several experiments, showing very high benefits that a Grid user can expect 1) in terms of resource usage compared to the current GridRPC context since useless transfers are avoided; 2) in terms of reducing the completion time of an application to obtain results the soonest (data can be prefetched and replicated, hence letting calculus to be submitted really soon in a workflow analysis in addition to the possible overlap between computations and communications); 3) in terms of code portability, since we show with these examples that at last the same GridRPC code can be compiled and executed within two different GridRPC middleware which implements the GridRPC data management API; 4) finally we thus obtain middleware interoperability without any explicit glue as generally done like in [5]: we show as a proof of concept that resources dispatched across different administrative domains can be used altogether without the underlying distributed data management systems having any knowledge of the workflow and/or computing resources: computational servers of DIET and NINF transparently collaborate to the same calculus by sharing GridRPC data.</div> </blockquote>



- **Standardized Data Management in GridRPC Environments**  <span onmouseover="document.getElementById('iccit2011').style.display = 'block'"  onmouseout="document.getElementById('iccit2011').style.display = 'none'">[abst]</span>   
Yves Caniou, Gael le Mahec, Eddy Caron, Hidemoto Nakada
, *6th International Conference on Computer Sciences and Convergence Information Technology*   , pp. 501-508  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="iccit2011"> This paper details an extension to the GridRPC API that responds both to the data management needs of distributed applications and to middleware interoperability. It provides a minimal set of functions to handle a large set of data operations: movements, replications, migrations, persistency and data prefetch, which can be used by clients or workflow systems for example. We trust that this API covers all data operations required in GridRPC distributed environments.</div> </blockquote>



- **グリッドRPCシステムのクラウド環境への適用**  <span onmouseover="document.getElementById('swopp09-nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp09-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2009-HPC-121*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-nakada"> Amazon EC2 に代表される HaaS 型のクラウドサービスは，ハードウェアそのものをネットワーク越しに従量課金で提供するもので，主にベンチャー企業の IT サービス基盤として広く普及しつつある．しかし，科学技術計算の分野では，現在のところあまり普及していない．この理由の一つとして，アプリケーションやミドルウェアのデプロイと設定が容易でないことが挙げられる．本稿では，クラウド側での設定をまったく行わずに，マスターワーカ型の科学技術計算を実現する機構を提案する．これまでに開発した GridRPC システム Ninf-G5 のジョブ起動機構を改良し，クラウド上のリソース制御機構を組み込んだ．この機能を用いることで，既存のマスタワーカ型の並列プログラムをまったく変更せずにクラウドを用いて大規模並列実行を行うことができる．クラウド側でのデプロイ，設定作業はまったく必要ない．このシステムを用いて簡単な評価実験を行った結果，計算量の大きいマスタワーカ型計算の HaaS 型クラウド上での実行にメリットがあることを確認した．</div> </blockquote>



- **The Proxy-based Design Pattern for Grid Middleware and its Application: Ninf-G5**  <span onmouseover="document.getElementById('hpcasia2009-nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcasia2009-nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Yoshio Tanaka, Satoshi Sekiguchi
, *Proc. HPC Asia 2009*   , pp. 210-217  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcasia2009-nakada"> This paper proposes a design pattern for composing grid middleware and introduces Grid RPC system Ninf-G implementation as an application of the pattern. There are not a few libraries and toolkits proposed to help composing applications and middleware on the grid. The most commonly used style for composing applications and middleware will be `monolithic&#x27;; i.e., the core logic are written using the provided API and directly linked with the libraries into a single binary. While this style is intuitive, there are several issues on this style; 1) Middleware/applications have to be written in the same language with the library, 2) When APIs of libraries update, the core portion of the middleware/applications have to be modified, 3) Mixed use of several libraries might cause serious name collision or dependency collision. We propose a proxy-based design pattern to compose grid middleware/applications, which is conducted from our years of experience with implementing Grid RPC system Ninf-G, where the each function of the library will be allocated separate process which communicate with the middleware/applications&#x27; core process with simple protocol. This design pattern allows the core process to be portable among several grid libraries/toolkits and to be written in arbitrary language. We introduce GridRPC Ninf-G version 5 implementation as an application of the design pattern. We compared it with the previous incarnation of the same system, which is implemented in monolithic way from two point of view; invocation latency and communication throughput. Contrary to the intuitive expectation, the result showed that the impact of the design pattern is negligible in terms of invocation latency and acceptable in terms of communication throughput.</div> </blockquote>



- **グリッドRPCシステムNinf-Gの可搬性および適応性の改善** [[Paper](dataDir/hpc0709nakada.pdf)] [[Slides](dataDir/hpc0709nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0709nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0709nakada').style.display = 'none'">[abst]</span>   
中田秀基, 朝生正人, 谷村勇輔, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-112*   , pp. 37-42  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0709nakada"> Ninf-Gはグリッド上でRPC(Remote Procedure Call) を実現するシステムである．従来のNinf-Gは，さまざまなジョブ起動機構に対応することができるが，通信機構にGlobus Toolkit のGlobus-IOを用いるため，常にGlobus Toolkit とリンクする必要がある．このため，1)Globus Toolkit のインストールがユーザに対する導入障壁となる，2)Globus Toolkit に依存するため可搬性が限定される，3)Globus-IO 以外の通信レイヤを利用することができない，といった問題がある．現在実装中のNinf-G Ver.5 では，これらの問題点を解決するために，リモート通信部を通信プロキシと呼ぶ独立した別プロセスとすることで，コア部分を外部ライブラリ非依存とした．これによって，ユーザに対する導入障壁が解消し，可搬性が向上すると同時に，他の通信レイヤの利用が可能となる．さらに，通信プロキシを利用することで，クライアントとリモート実行ノードが直接通信できない環境においても利用することが可能になる．本稿ではこのNinf-G Ver.5 の設計について詳述する．さらに，通信プロキシを導入することで予想されるオーバヘッドを見積もるための予備的評価を行う．評価の結果，別プロセス化によるオーバヘッドは無視できないものの，得られるメリットを勘案すれば受け入
れることができる範囲であることがわかった．</div> </blockquote>



- **動的に計算量が変化する大規模長時間実行Gridアプリケーションの実現**  <span onmouseover="document.getElementById('acs16takemiya').style.display = 'block'"  onmouseout="document.getElementById('acs16takemiya').style.display = 'none'">[abst]</span>   
武宮 博, 田中 良夫, 中田 秀基, 関口 智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.47 No.SIG18  (ACS16)*   , pp. 31-43  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs16takemiya"> (1)数千プロセッサ規模の大規模な計算機資源を要する，(2)数週間から数カ月に及ぶ長期実行を必要とする，(3)計算の進展に応じて動的に計算量が変化する，という特徴を持つシミュレーションプログラムをGridRPCとMPIを組み合わせるプログラミング手法に基づきGrid化し，分散配置された並列計算機から構成されるGrid環境上で実行するための手法を提案する．本手法を用いることにより，上記3点の特徴を持つGridアプリケーションを構築するために必要な，プログラムの柔軟性，頑健性，効率性を実現することが可能となる．本手法の有効性を検証するために，本手法に基づきGrid化したプログラムを環太平洋Grid環境上で長期間継続実行させる実験を試みた．その結果，障害発生や計算量の変化に対応して実行対象計算機やその利用規模を変更しながら最長20日以上にわたり大規模Gridシミュレーションを継続実行することができた．</div> </blockquote>



- **グリッドRPCシステムNinf-Gのリモート起動手法の改良** [[Paper](dataDir/hpc0610nakada.pdf)]  <span onmouseover="document.getElementById('hpc0610nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0610nakada').style.display = 'none'">[abst]</span>   
中田秀基, 朝生正人, 谷村勇輔, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-10８*   , pp. 43-47  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0610nakada"> グリッド上でRPC(Remote Procedure Call) を実現するGridRPCは，グリッド上のプログラミングモデルとして有望なマスタ・ワーカ計算をサポートするのに適した計算機構である．われわれはGridRPC APIを実装したプログラミング機構としてNinf-Gを設計，実装している．Ninf-Gは基本的にGlobus Toolkitを用いて実装されているが，ジョブの起動機構をInvoke Serverと呼ぶ外部モジュールとしてプラグインすることで，多様な実行環境に柔軟に適応することができる．Invoke Server機構の設計に関しては，すでに別稿で報告している．われわれは，Globus Toolkit 4 WS GRAM, Unicore, Condor，ssh，NAREGI ミドルウェアβに対してそれぞれInvoke Serverを実装した．また，Invoke Server機構のオーバヘッドを評価するためにジョブ起動時間を測定した．その結果，Invoke Serverによって導入されるオーバヘッドはジョブ起動機構自身のオーバヘッドと比較すると十分小さいことがわかった．本稿では，より適応範囲を広げるために計画されている，より高度なモジュール化に関しても議論する．</div> </blockquote>



- **Design and Implementation of Distributed Task Sequencing on GridRPC** [[Paper](dataDir/cit06tanimura.pdf)]  <span onmouseover="document.getElementById('cit06tanimura').style.display = 'block'"  onmouseout="document.getElementById('cit06tanimura').style.display = 'none'">[abst]</span>   
Yusuke Tanimura, Hidemoto Nakada, Yoshio Tanaka, Satoshi Sekiguchi
, *Proc. of 2006 IEEE International Conference on Computer and Information Technology*   , pp. 6p  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cit06tanimura"> In the framework of GridRPC, a new function that allows direct data transfer between RPC servers is implemented for ef cient execution of a Task Sequencing job in a grid environment. In Task Sequencing, RPC requires dependency between input and output parameters, which means output of a previous RPC becomes the input of the next RPC. In this study, the direct transfer of data is implemented using the grid  lesystem without destroying the GridRPC programming model and without changing very many parts of the existing Ninf-G implementation. Our Task Sequencing API library analyzes RPC arguments to detect intermediate data after task submissions, and reports the information to GridRPC servers so that the intermediate data is created on the grid  lesystem. Through our performance evaluation on LAN and on the Japan-US grid environment, it was verified that the function achieved performance improvement in distributed Task Sequencing.</div> </blockquote>



- **GridRPCにおける複数ノードにまたがるTask Sequencing の実現**  <span onmouseover="document.getElementById('acs15tanimura').style.display = 'block'"  onmouseout="document.getElementById('acs15tanimura').style.display = 'none'">[abst]</span>   
谷村 勇輔, 中田 秀基, 田中 良夫, 関口 智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.47 No.SIG12  (ACS15)*   , pp. 207-211  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs15tanimura"> GridRPC において，依存関係を持つ2 つ以上のRPC，すなわち直前のRPC の出力が次のRPCの入力データとなるTask Sequencing ジョブを複数ノードにまたがって処理する場合に，クライアントを介さずにRPC の実行ノード間で直接データを転送する機能の設計と実装を行った．大域的な名前空間を提供するグローバルファイルシステムを利用することにより，クライアント・サーバモデルを基本とするGridRPC の特徴を損なわず，かつ既存のGridRPC システムの実装を大きく変えることなく実現した．また，連続するRPC の引数列を解析して中間データを自動判別し，中間データであればそれをグローバルファイルシステム上に作成する機能をTask Sequencing API ライブラリ内部に実装し，LAN 環境，日米間にまたがるグリッド環境における性能評価を行い，本機能が有効であることを明らかにした．</div> </blockquote>



- **大規模長時間実行Gridアプリケーションの実装と評価** [[Paper](dataDir/sacsis06takemiya.pdf)] [[Slides](dataDir/sacsis06takemiya_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06takemiya').style.display = 'block'"  onmouseout="document.getElementById('sacsis06takemiya').style.display = 'none'">[abst]</span>   
武宮 博, 田中 良夫, 中田 秀基, 関口 智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 351-358  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06takemiya"> 動的に計算量が変動するという特徴を持つ大規模シミュレーションプログラムをGridRPC とMPIを組み合わせることによりGrid 化し，長期間にわたってGrid 環境上で継続実行させることを試みた．実装に際して，(1) 大規模計算機を事前に一定期間予約し，対象を変更する，(2) 複数のユーザにより共有されている計算機から，その時点で利用可能なものを動的に利用していく，という二種類の現実的な実行シナリオを想定し，このシナリオを満足するためにアプリケーションに実装すべき機能を検討した．また，本手法に基づきGrid 化したプログラムを環太平洋Grid 環境上で半月から二ヶ月にわたり動作させることで，本手法により計算量の変動にあわせて動的に実行対象計算機を変更する柔軟性と，障害を検知・復旧する頑健性を実現できることを示す．</div> </blockquote>



- **GridRPCにおける複数ノードにまたがるTask Sequencingの実現** [[Paper](dataDir/sacsis06tanimura.pdf)] [[Slides](dataDir/sacsis06tanimura_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06tanimura').style.display = 'block'"  onmouseout="document.getElementById('sacsis06tanimura').style.display = 'none'">[abst]</span>   
谷村 勇輔, 中田 秀基, 田中 良夫, 関口 智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 75-84  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06tanimura"> GridRPC において，依存関係をもつ2 つ以上のRPC，すなわち直前のRPC の出力が次のRPCの入力データとなるTask Sequencing ジョブを複数ノードにまたがって処理する場合に，クライアントを介さずにRPC の実行ノード間で直接データを転送する機能の設計と実装を行った．大域的な名前空間を提供するグローバルファイルシステムを利用することにより，クライアント・サーバモデルを基本とするGridRPC の特徴を損なわず，かつ既存のGridRPC システムの実装を大きく変えることなく実現した．また，連続するRPC の引数列を解析して中間データを自動判別し，中間データであればそれをグローバルファイルシステム上に作成する機能をTask Sequencing API ライブラリ内部に実装し，LAN 環境，日米間にまたがるグリッド環境における性能評価を行い，本機能が有効であることを明らかにした．</div> </blockquote>



- **Design and implementation of Flexible, Robust and Efficient Grid-enabled Hybrid QM/MD Simulation**  <span onmouseover="document.getElementById('cmst07tanaka').style.display = 'block'"  onmouseout="document.getElementById('cmst07tanaka').style.display = 'none'">[abst]</span>   
Yoshio Tanaka, Hiroshi Takemiya, Hidemoto Nakada, Satoshi Sekiguchi
, *Computational Methods in Science and Technology,Volume 12 (1) 2006, 79-87*   , pp. 79-87   , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cmst07tanaka"> This paper describes the implementation of Grid-enabled hybrid Quantum Mechanics/Classical Molecular Dynamics (QM/MD) Simulation. The Grid-enabled QM/MD simulation is capable of (1) dynamic resource allocation and migration, (2) automatic recovery from faults, and (3) managing large number of CPUs in geographically distributed sites. In the implementation, both GridRPC and MPI are used to complement each other, that is, GridRPC allows dynamic resource allocation and migration and automatic recovery from faults while MPI provides high-performance parallel processing on each cluster. We ran the hybrid QM/MD simulation on an international Grid testbed in the Asia Pacific Region for about 52 days. The experimental results indicated that the hybrid QM/MD simulation could (1) adapt to the dynamic behavior of the simulation and can change the number of CPUs and the number of clusters, (2) adapt to unstable Grid infrastructure and recovers from faults automatically, and (3) manage hundreds to thousands of CPUs on distributed locations, and (4) survive for several weeks without interrupting manual operation. This paper reports on the details of the implementation, strategies for long-run, and experimental results.</div> </blockquote>



- **Primary Study of A Task Farming API over The GridRPC Framework** [[Paper](dataDir/hpcasia05tanimura.pdf)] [[Slides](dataDir/hpcasia05tanimura_slide.pdf)]  <span onmouseover="document.getElementById('hpcasia05tanimura').style.display = 'block'"  onmouseout="document.getElementById('hpcasia05tanimura').style.display = 'none'">[abst]</span>   
Yusuke Tanimura, Hidemoto Nakada, Yoshio Tanaka, Satoshi Sekiguchi
, *Eighth International Conference on High-Performance Computing in Asia-Pacific Region*   , pp. 339-345  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcasia05tanimura"> In this paper, a middleware suite, which provides a Task Farming API, is studied in use over the GridRPC standard, in order to reduce the complexity of developing task parallel applications for the grid.  APIs are proposed and higher functionality in task scheduling and fault tolerance is implemented in the middleware, based on our past experiences with the Ninf-G.  Through our study, it is revealed that the Argument Array API needs to provide a means to copy arguments for duplicated task assignment.  Timing of data transfer in the non-blocking RPC and a method to retrieve execution information for each RPC are expected to be standardized in the GridRPC.  By resolving these three issues in the GridRPC, our Task Farming API library, meeting application requirements, can be fully realized on multiple GridRPC systems, paving the way for other higher functional API libraries to be designed and implemented.</div> </blockquote>



- **GridRPC を用いたタスクファーミングAPIの設計と実装** [[Paper](dataDir/swopp05tanimura.pdf)]  <span onmouseover="document.getElementById('swopp05tanimura').style.display = 'block'"  onmouseout="document.getElementById('swopp05tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2005-HPC-103*   , pp. 67-72  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp05tanimura"> 本研究では，グリッド上でタスク並列を行うアプリケーションを開発する手間を削減することを目指して，GridRPC の上位にタスクファーミングAPI を提供するミドルウェアを設計した．実アプリケーションの事例研究から得られた要求仕様をもとにAPI を提案し，タスクの自動割り当てや耐障害に関する機能をミドルウェア内部に実装した．そのような上位ミドルウェアを実装するために，Argument Array API に引数データのコピー機能が求められること，ノンブロッキング呼び出しにおけるデータ通信のタイミングとRPC の実行情報を取得する方法がGridRPC で標準化される必要があることを明らかにした．</div> </blockquote>



- **GridRPCシステムNinf-GにおけるUNICOREおよびGT4によるジョブ起動** [[Paper](dataDir/hpc0506nakada.pdf)]  <span onmouseover="document.getElementById('hpc0506nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0506nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2005-HPC-102*   , pp. 45-50  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0506nakada"> GridRPCシステムNinf-GにおけるUNICOREおよびGrobus Toolkit 4を用いたジョブ起動機構に関して報告する。Ninf-GはGrobus Toolkit２および３を用いたジョブ起動機構をクライアントライブラリに内臓している。しかしUNICOREやGrobus Toolkit 4ではC言語でのクライアントAPIが提供されていないため、ジョブ起動機構をクライアントライブラリに内臓することはできない。我々は、ジョブ起動機構 を外部モジュールとしてクライアントライブラリから切り離すための汎用プロトコルを設計した。このプロトコルを使用することで、Ninf-Gクライアント ライブラリ本体に手を加えることなく、新たなジョブ起動機構を追加することができる。</div> </blockquote>



- **Ninf-1/Ninf-Gを用いたNMR蛋白質立体構造決定のための遺伝アルゴリズムのグリッド化** [[Paper](dataDir/sacsis05ono.pdf)] [[Slides](dataDir/sacsis05ono_slide.pdf)]  <span onmouseover="document.getElementById('sacsis05ono').style.display = 'block'"  onmouseout="document.getElementById('sacsis05ono').style.display = 'none'">[abst]</span>   
小野功, 水口尚亮, 中島直敏, 小野典彦, 中田秀基,  松岡聡, 関口 智嗣, 楯 真一
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5*   , pp. 143-151  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis05ono"> 核磁気共鳴法(NMR) は，ポストシーケンスにおける最重要課題の一つである蛋白質立体構造解析の有望な手段である．しかし，専門家でさえ，一つの蛋白質のデータ解析に数ヶ月程度の試行錯誤が必要なことが深刻な問題となっている．これに対し，Ono らは遺伝アルゴリズム(GA) に基づくデータ解析の自動化手法を提案し，13 残基程度の小規模な問題において比較的良好な性能を得られたと報告している．しかし，実際に扱わなければならない問題規模は数十残基から二百残基程度である．たとえば，78 残基の場合，Pentium III 1.4GHz のシングルCPU のPC では，計算が終了するまでに約200 日程度の時間がかかってしまうことが見積もられており，高速化が望まれている．本論文では，ミドルウェアNinf-1 およびNinf-G を用いてOno らの提案したGA をグリッド上で並列化したシステム（NMR 蛋白質立体構造決定のためのグリッド向けGA システム）を提案する．5 サイト/1,196CPU から構成されるグリッドテストベッド上で，提案システムの性能評価を行う．</div> </blockquote>



- **Hybrid QM/MDシミュレーション：MPIとGridPRCを利用した大規模Gridアプリケーションの実行**    
武宮 博, 田中良夫, 中田秀基, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2005, IPSJ Symposium Series Vol. 2005, No. 5*   , pp. 153-160  , 2005 



- **耐障害性を考慮したNinf-Gアプリケーションの実装と評価**  <span onmouseover="document.getElementById('acs10tanimura').style.display = 'block'"  onmouseout="document.getElementById('acs10tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 池上努, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol. 46, No. SIG 7 (ACS 10)*   , pp. 18-27  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs10tanimura"> 我々はグリッドのアプリケーションにとって耐障害性が重要課題であることをふまえて，タスク並列アプリケーションをGridRPC システムの1 つであるNinf-G を用いて実装し，アジア太平洋地域のグリッドのテストベッド上で長時間にわたり実行した．その中で障害パターンを集めて，障害の検知や復旧にかかるコストを測定しながら耐障害性の機構を検討した．本研究により，グリッドが持つ不安定さに対応したアプリケーションやミドルウェアでは，障害検知や復旧の操作におけるタスク実行の性能低下に留意する必要があるとともに，性能低下を防ぐために，障害検知のためのタイムアウト値の最小化や復旧のバックグラウンド処理，障害を考慮したタスク割当てが必要であることが分かった．こうして，グリッドのアプリケーション開発者に対して開発や実行時の留意点を示すとともに，GridRPC の枠組みの上位に求められる耐障害に関する機構の設計への指針を示した．</div> </blockquote>



- **GridRPCシステムの比較 --アプリケーション開発における違い** [[Paper](dataDir/hokke05tanimura.pdf)]  <span onmouseover="document.getElementById('hokke05tanimura').style.display = 'block'"  onmouseout="document.getElementById('hokke05tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2004-HPC-101*   , pp. 91-96  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke05tanimura"> 本研究では，代表的なGridRPCシステムである Ninf-G, NetSolveおよびOmniRPCに注目し，それぞれのシステムを使ってアプリケーションを開発する上での違いを調査した．システムが想定している用途の違いを踏まえて，プログラミングや遠隔実行プログラムの起動方法，利用できる環境，実行をサポートする機能の違いについて明らかにし，単一RPC実行時の性能比較を行った．また，将来的にサポートが進むであろう機能や発展的なRPCについても言及した．こうした調査結果は，どのシステムを利用してアプリケーションを開発するかを決める上で有用な情報になると考える．</div> </blockquote>



- **耐障害性を考慮したNinf-Gアプリケーションの実装と評価** [[Paper](dataDir/hpcs05tanimura.pdf)]  <span onmouseover="document.getElementById('hpcs05tanimura').style.display = 'block'"  onmouseout="document.getElementById('hpcs05tanimura').style.display = 'none'">[abst]</span>   
谷村勇輔, 池上努, 中田秀基, 田中良夫, 関口智嗣
, *ハイパフォーマンスコンピューティングと計算科学シンポジウム, HPCS2005*   , pp. 99-106  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs05tanimura"> 我々はグリッドのアプリケーションにとって耐障害性が重要課題であることをふまえて，タスク並列アプリケーションをGridRPC システムの1 つであるNinf-G を用いて実装し，アジア太平洋地域のグリッドのテストベッド上で長時間にわたり実行した．その中で障害パターンを集めて，障害の検知や復旧にかかるコストを測定しながら耐障害性の機構を検討した．本研究により，グリッドが持つ不安定さに対応したアプリケーションやミドルウェアでは，障害検知や復旧の操作におけるタスク実行の性能低下に留意する必要があるとともに，性能低下を防ぐために，障害検知のためのタイムアウト値の最小化や復旧のバックグラウンド処理，障害を考慮したタスク割当てが必要であることが分かった．こうして，グリッドのアプリケーション開発者に対して開発や実行時の留意点を示すとともに，GridRPC の枠組みの上位に求められる耐障害に関する機構の設計への指針を示した．</div> </blockquote>



- **Ninf-G2: 大規模Grid環境での利用に即した高機能，高性能GridRPCシステムの実装と評価**  <span onmouseover="document.getElementById('acs7takemiya').style.display = 'block'"  onmouseout="document.getElementById('acs7takemiya').style.display = 'none'">[abst]</span>   
武宮博, 田中良夫, 中田秀基, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol. 45, No. SIG 11(ACS 7)*   , pp. 144-159  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs7takemiya"> Grid プログラミングモデルの1 つであるGridRPCの参照実装としてNinf-G2の開発を行い，性能を評価した．広域に分散した複数台のクラスタから構成される大規模Grid 環境上でアプリケーションを効率良く実行することを目的とするNinf-G2は，関数ハンドル同時生成機能やリモートオブジェクトを実装することで，遠隔手続き呼び出しにともなう起動コストや通信コストの低減を図るとともに，ハートビート機能や関数ハンドル作成タイムアウト機能，サーバ属性の個別設定機能を提供することで，非均質，不安定で動的に変化するGrid環境への対応を図っている．典型的なタスク並列アプリケーションである気象シミュレーションプログラムを対象に，6台のクラスタから構成されるGridテストベッド上でNinf-G2の性能評価を行った．その結果，個々のタスクの実行時間が十数秒から数十秒程度の比較的粒度の小さいシミュレーションであっても，200台以上のプロセッサを用いて効率的に実行可能であることが分かった．</div> </blockquote>



- **耐故障性を重視したRPCシステムNinf-Cの設計と実装**  <span onmouseover="document.getElementById('acs7nakada').style.display = 'block'"  onmouseout="document.getElementById('acs7nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 松岡聡, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol. 45, No. SIG 11(ACS 7)*   , pp. 160-170  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs7nakada"> 耐故障性を重視したRPCシステムNinf-Cの設計と実装に関して述べる。Ninf-Cは、全体として数日から数ヶ月を要する大規模なマスタワーカ型計算を安定して実行することを目的としたシステムで、ウィスコンシン大学で開発されたスケジューリングシステムCondorの提供する機能を利用することで、マスタを含むシステム全体に耐故障性を持たせている。Ninf-CのRPCは、Condorのファイルステージ機能を用いて実現される。直接ソケット通信を使用せずにファイル経由で通信を行うことで、マスタとワーカのチェックポイントをとることを可能とした。また、ファイルに残った通信記録を用いてマスタの状態を復元する。さらに、Condor-Gを利用することで、Globusによって構築されたグリッド環境下での運用も可能である。Ninf-C の有効性を確認するため、クラスタ環境で簡単なマスタワーカ型プログラムを長時間実行した。この際、マスタおよびワーカを実行しているマシンをシャットダウンするといった人為的な外乱をあたえたが、プログラムは19時間かけて問題なく実行を終了し、Ninf-Cの耐故障性が実証された。</div> </blockquote>



- **The Design and implementation of a Fault-Tolerant RPC system: Ninf-C** [[Paper](dataDir/hpcasia04nakada.pdf)]  <span onmouseover="document.getElementById('hpcasia04nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcasia04nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Yoshio Tanaka, Satoshi Matsuoka, Satoshi Sekiguchi
, *Proceedings of HPC ASIA 2004*   , pp. 9-18  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcasia04nakada"> We describe the design and implementation of a fault tolerant GridRPC system, Ninf-C, designed for easy programming of large-scale master-worker programs that take from few days to few months for its execution in a Grid environment. Ninf-C employs Condor, developed at University of Wisconsin, as the underlying middleware supporting remote file transmission and checkpointing for system-wide robustness for application users on the Grid. Ninf-C layers all the GridRPC communication and task parallel programming features on top of Condor in a non-trivial fashion, assuming that the entire program is structured in a masterworker style?in fact, older Ninf master-worker programs can be run directly or trivially ported to Ninf-C. In contrast to the original Ninf, Ninf-C exploits and extends Condor features extensively for robustness and transparency, such as 1) checkpointing and stateful recovery of the master process, 2) the master and workers mutually communicating using (remote) files, not IP sockets, and 3) automated throttling of parallel GridRPC calls; and in contrast to using Condor directly, programmers can set up complex dynamicworkflow as well as master-worker parallel structure with almost no learning curve involved. To prove the robustness of the system, we performed an experiment on a heterogeneous cluster that consists of x86 and SPARC CPUs, and ran a simple but long-running master-worker program with staged rebooting of multiple nodes to simulate some serious fault situations. The program execution finished normally avoiding all the fault scenarios, demonstrating the robustness of Ninf-C.</div> </blockquote>



- **Ninf-G2の性能評価：科学技術計算における事例** [[Paper](dataDir/swopp04tanimura.pdf)]    
谷村勇輔, 池上努, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告 2004-HPC-99*   , pp. 37-42  , 2004 



- **Parallelization of Phylogenetic Tree Inference using Grid Technologies** [[Paper](dataDir/lsgrid04yamamoto.pdf)] [[Slides](dataDir/lsgrid04yamamoto_slide.pdf)]  <span onmouseover="document.getElementById('lsgrid04yamamoto').style.display = 'block'"  onmouseout="document.getElementById('lsgrid04yamamoto').style.display = 'none'">[abst]</span>   
Yo Yamamoto, Hidemoto Nakada, Hidetoshi Shimodaira, Satoshi Matsuoka
, *LSGrid 2004*   , pp. 103-116  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="lsgrid04yamamoto"> The maximum likelihood method is considered as one of the most reliable methods for phylogenetic tree inference. However, as the number of species increases, the approach quickly loses its applicability due to explosive exponential number of trees that need to be considered. An earlier work by one of the authors [3] demonstrated that, by decomposing the trees into fragments called splits, and calculating the individual likelihood of each (small) split and combining them would result in a very close approximation of the true maximum likelihood value, as well as achieving significant reduction in computational cost. However, the cost was still significant for a practical number of species that need to be considered. To solve this problem, we further extend the algorithm so that it could be effectively parallelized in a Grid environment using Grid middleware such as Ninf and Jojo, and also applied combinatorial optimization techniques. Combined, we achieved over 64 times speedup over our previous results in a testbed of 16 nodes, with favorable speedup characteristics.</div> </blockquote>



- **耐故障性を重視したRPCシステムNinf-Cの設計と実装** [[Paper](dataDir/sacsis04nakada.pdf)]  <span onmouseover="document.getElementById('sacsis04nakada').style.display = 'block'"  onmouseout="document.getElementById('sacsis04nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 松岡聡, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS2004 論文集*   , pp. 77-84  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis04nakada"> 耐故障性を重視したRPCシステムNinf-Cの設計と実装に関して述べる。Ninf-Cは、全体として数日から数ヶ月を要する大規模なマスタ ワーカ型計算を安定して実行することを目的としたシステムで、ウィスコンシン大学で開発されたスケジューリングシステムCondorの提供する機能を利用 することで、マスタを含むシステム全体に耐故障性を持たせている。Ninf-CのRPCは、Condorのファイルステージ機能を用いて実現される。直接 ソケット通信を使用せずにファイル経由で通信を行うことで、マスタとワーカのチェックポイントをとることを可能とした。また、ファイルに残った通信記録を 用いてマスタの状態を復元する。さらに、Condor-Gを利用することで、Globusによって構築されたグリッド環境下での運用も可能である。 Ninf-Cの有効性を確認するため、クラスタ環境で簡単なマスタワーカ型プログラムを長時間実行した。この際、マスタおよびワーカを実行しているマシン をシャットダウンするといった人為的な外乱をあたえたが、プログラムは19時間かけて問題なく実行を終了し、Ninf-Cの耐故障性が実証された。</div> </blockquote>



- **Ninf-G2: 大規模Grid環境での利用に即した高機能，高性能GridRPCシステムの実装と評価**    
武宮博, 田中良夫, 中田秀基, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS2004 論文集*   , pp. 69-76  , 2004 



- **Ninf-G version2の実装および性能評価** [[Paper](dataDir/hokke04takemiya.pdf)]  <span onmouseover="document.getElementById('hokke04takemiya').style.display = 'block'"  onmouseout="document.getElementById('hokke04takemiya').style.display = 'none'">[abst]</span>   
武宮博, 田中良夫, 中田秀基, 関口智嗣
, *情報処理学会研究報告 2004-HPC-97*   , pp. 19-24  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04takemiya"> Ninf-G version2は，Gridプログラミングモデルの一つであるGridRPCの参照実装であり，広域に分散した複数代のクラスタから構成される大規模Grid環境上でアプリケーションを効率よく実行することを目的とする．関数ハンドル同時生成機能やリモートオブジェクトを実装することで，遠隔手続き呼び出しに伴う起動コストや通信コストの低減を図るとともに，ハートビート機能，関数ハンドル作成タイムアウト機能，サーバ属性の個別設定機能を提供することで，非均質，不安定で動的に変化するGrid環境への対応を図っている．4台のクラスタ計300プロセッサから構成されるGridテストベッド上でNinf-G version2の実行性能を測定した．その結果，関数ハンドル同時生成機能がプログラム起動コストの低減に有効であること，およびNinf化されたシミュレーションが大規模グリッド環境で効率的に実行可能であることがわかった．</div> </blockquote>



- **グリッド技術を用いた進化系統樹推定の並列化** [[Paper](dataDir/hokke04yamamoto.pdf)]  <span onmouseover="document.getElementById('hokke04yamamoto').style.display = 'block'"  onmouseout="document.getElementById('hokke04yamamoto').style.display = 'none'">[abst]</span>   
山本洋, 中田秀基, 下平英寿, 松岡聡
, *情報処理学会研究報告 2004-HPC-97*   , pp. 181-186  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke04yamamoto"> 進化系統樹の推定では最尤法を用いた手法が最も優れた推定法の1つとされているが、最尤法の計算量は大きく、種の個数が増えると系統樹の個数は莫 大となるため全系統樹の尤度を求めることは事実上不可能となる。系統樹の構成要素であるスプリットの尤度を最尤法によって計算し、スプリットの尤度を用い た行列計算によって系統樹の尤度を近似計算する手法が提案されている。しかし、種の個数がさらに増大すると、近似計算であってもすべての系統樹に対して行 うことは困難になる。本研究では、系統樹の推定を系統樹空間における探索問題とみなし、最適化手法を適用することで、近似計算の対象となる系統樹の個数を 削減する。また、グリッドミドルウェアを用いたマスタ・ワーカ方式を採用し、尤度計算および最適化手法の並列実行を可能にした。生物9種の系統樹推定にお いて16ワーカを用いた結果、64.0倍の性能向上が得られた。</div> </blockquote>



- **Design, implementation and performance evaluation of GridRPC programming middleware for a large-scale computational Grid** [[Paper](dataDir/grid04tanaka.pdf)]  <span onmouseover="document.getElementById('grid04tanaka').style.display = 'block'"  onmouseout="document.getElementById('grid04tanaka').style.display = 'none'">[abst]</span>   
Yoshio Tanaka, Hiroshi Takemiya, Hidemoto Nakada, Satoshi Sekiguchi
, *Proceeding of 5th IEEE/ACM International Workshop on Grid Computing.*   , pp. 298-305  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="grid04tanaka"> This paper reports on the design, implementation and performance evaluation of a suite of GridRPC programming middleware called Ninf-G Version 2 (Ninf-G2). Ninf-G2 is a reference implementation of the GridRPC API, a proposed GGF standard. Ninf-G2 has been designed so that it provides 1) high performance in a large-scale computational Grid, 2) the rich functionalities which are required to adapt to compensate for the heterogeneity and unreliability of a Grid environment, and 3) an API which supports easy development and execution of Grid applications. Ninf-G2 is implemented to work with basic Grid services, such as GSI, GRAM, and MDS in the Globus Toolkit version 2. The performance of Ninf-G2 was evaluated using a weather forecasting system which was developed using Ninf-G2. The experimental results indicate that high performance can be attained even in relatively fine-grained task-parallel applications on hundreds of processors in a Grid environment.</div> </blockquote>



- **GridRPCを用いたタスクファーミングAPIの試作** [[Paper](dataDir/hpc0310nakada.pdf)]    
中田秀基, 田中良夫, 松岡聡, 関口智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 102*   , pp. 61-66  , 2003 



- **Ninf-G2: 大規模環境に即した高機能，高性能GridRPCシステム** [[Paper](dataDir/swopp03tanaka.pdf)]    
田中良夫, 中田秀基, 朝生正人, 関口智嗣
, *情報処理学会ハイパフォーマンスコンピューティング研究会，Vol. 2003, No. 83*   , pp. 65-70  , 2003 



- **Ninf-G: A Reference Implementation of RPC-based Programming Middleware for Grid Computing**  <span onmouseover="document.getElementById('jgc03tanaka').style.display = 'block'"  onmouseout="document.getElementById('jgc03tanaka').style.display = 'none'">[abst]</span>   
Yoshio Tanaka, Hidemoto Nakada, Satoshi Sekiguchi, Toyotaro Suzumura, Satoshi Matsuoka
, *Journal of Grid Computing, Vol. 1, No. 1*   , pp. 41-51  , 2003 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jgc03tanaka"> GridRPC, which is an RPC mechanism tailored for the Grid, is an attractive programming model for Grid computing. This paper reports on the design and implementation of a GridRPC programming system called Ninf-G. Ninf-G is a reference implementation of the GridRPC API which has been proposed for standardization at the Global Grid Forum. In this paper, we describe the design, implementations and typical usage of Ninf-G. A preliminary performance evaluation in both WAN and LAN environments is also reported. Implemented on top of the Globus Toolkit, Ninf-G provides a simple and easy programming interface based on standard Grid protocols and the API for Grid Computing. The overhead of remote procedure calls in Ninf-G is acceptable in both WAN and LAN environments.</div> </blockquote>



- **GridRPC Tutorial**    
Hidemoto Nakada, Satoshi Matsuoka, Mitsuhisa Sato, Satoshi Sekiguchi 
, *CCGrid  2003*    , 2003 



- **Overview of GridRPC: A Remote Procedure Call API for Grid Computing**  <span onmouseover="document.getElementById('grid02seymour').style.display = 'block'"  onmouseout="document.getElementById('grid02seymour').style.display = 'none'">[abst]</span>   
 Keith Seymour, Hidemoto Nakada, Satoshi Matsuoka, Jack Dongarra, Craig Lee, Henri Casanova
, *Grid Computing - Grid 2002, LNCS 2536*   , pp. 274-278  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="grid02seymour"> This paper discusses preliminary work on standardizing and implementing a remote procedure calll (RPC) mechanism for grid computing. The GridRPC API is designed to address the lack of a standardized, portable, and simple programming interface. Our initial work on GridRPC shows that client access to existing grid computing systems such as NetSolve and Ninf can be unified via a common API, a task that has proven to be problematic in the past.</div> </blockquote>



- **The Ninf Portal: An Automatic Generation Tool for the Grid Portals**  <span onmouseover="document.getElementById('javagrande02suzumura').style.display = 'block'"  onmouseout="document.getElementById('javagrande02suzumura').style.display = 'none'">[abst]</span>   
Toyotaro Suzumura, Hidemoto Nakada, Masayuki Saito, Satoshi Matsuoka, Yoshio Tanaka, Satoshi Sekiguchi
, *Proceeding of Java Grande 2002*   , pp. 1-7  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="javagrande02suzumura"> As the Grid proliferates as the next-generation computing infrastructure, a user interface in the form of &quot;Grid Portals&quot; is becoming increasingly important, especially for computational scientists and engineers. Although several Grid Portal toolkits have been proposed, the portal developer still must build and deploy both the user interface and the application, which results in considerable programming efforts. We aim to ease this burden by generating the portal frontend (that constitutes of JSP and Java Servlets) from an XML document for the former, and a GridRPC system, Ninf-G for easily &quot;gridifying&quot; existing applications for the latter, and realizing their seamless integration. The resulting system, which we call the Ninf Portal, allowed concise description and easy deployment of a real Grid application with greatly small programming efforts.</div> </blockquote>



- **Gridポータル構築ツールキットNinf-Portal**  <span onmouseover="document.getElementById('hps5nakada').style.display = 'block'"  onmouseout="document.getElementById('hps5nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 齋藤 真幸, 鈴村 豊太郎, 田中 良夫, 松岡 聡, 関口 智嗣
, *情報処理学会論文誌 コンピューティングシステム Vol. 43, No. SIG 6(HPS 5)*   , pp. 172-183  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hps5nakada"> 広域に分散した各種資源を集合的に使用して大規模計算を行う計算機構Gridが注目を集めている。多様な管理主体に属する資源から構成されるGrid環境上のプログラムを多くのユーザに使用させるためには、ポータルと呼ばれる機構が必要である。このため、Gridへのポータルを構築するためのツールキットがいくつか提案されている。しかしこれらのツールキットを用いる場合でも、ポータル構築者がフロントエンドとなるポータルのユーザインターフェイス部、バックエンドとなる実際のGridプログラムの2つを記述しなければならず、ポータル構築者の負担が大きい。我々は、前者に対してXMLベースのユーザインターフェイス生成系を、後者に対してGrid RPCシステムであるNinf-Gを使用することでプログラマの負荷を軽減するポータル開発キットを提案する。さらに、提案したシステムを用いて、実用的なプログラムをポータル化し有効性を確認した。</div> </blockquote>



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



- **Evaluating Web Services Based Implementations of GridRPC**  <span onmouseover="document.getElementById('hpdc11shirasuna').style.display = 'block'"  onmouseout="document.getElementById('hpdc11shirasuna').style.display = 'none'">[abst]</span>   
Satoshi Shirasuna, Hidemoto Nakada, Satoshi Matsuoka, Satoshi Sekiguchi
, *Proceeding of HPDC11*   , pp. 237-245  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpdc11shirasuna"> GridRPC is a class of Grid middleware for scientific computing. Interoperability has been an important issue, because current GridRPC systems each employ its own protocol. Web services, where XML-based standards such as SOAP and WSDL are expected to see widespread use, could be the medium of interoperability; however, it is not clear if 1) XML-based schemas have sufficient expressive power for GridRPC, and 2) whether performance could be made sufficient. Our experiments indicate that the use of such technologies are more promising than previously reported. Although a naive implementation of SOAP-based GridRPC has severe performance overhead, application of a series of optimizations improves performance. However, encoding of various features of GridRPC proved to be somewhat difficult due to WSDL limitations. The results show that GridRPC systems can be based on Web technologies, but there needs to be work to extend WSDL specifications, possibly impacting OGSA-based Grid services directions.</div> </blockquote>



- **Gridポータル構築ツールキットNinf-Portal**  <span onmouseover="document.getElementById('jspp02nakada').style.display = 'block'"  onmouseout="document.getElementById('jspp02nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 齋藤 真幸, 鈴村 豊太郎, 田中 良夫, 松岡 聡, 関口 智嗣
, *JSPP2002論文集*   , pp. 209−216  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp02nakada"> 広域に分散した各種資源を集合的に使用して大規模計算を行う計算機構 Gridが注目を集めている。多様な管理主体に属する資源から構成されるGrid環境上のプログラムを多くのユーザに使用させるためには、ポータルと呼ばれる機構が必要である。このため、Gridへのポータルを構築するためのツールキットがいくつか提案されている。しかしこれらのツールキットを用いる場合でも、ポータル構築者がフロントエンドとなるポータルのユーザインターフェイス部、バックエンドとなる実際のGridプログラムの2つを記述しなければならず、ポータル構築者の負担が大きい。われわれは、前者に対してXMLベースのユーザインターフェイス生成系を、後者に対してGrid RPCシステムであるNinf-Gを使用することでプログラマの負荷を軽減するポータル開発キットを提案する。さらに、提案したシステムを用いて、実用的なプログラムをポータル化し有効性を確認した。 As the Grid proliferates as the next-generation wide-area high-performance computing infrastructure, end-user Grid interfaces in the form of &quot;Grid Portals&quot; is becoming increasingly important, especially computational scientists and engineers. Although several Grid portal toolkits and proposals have been proposed, a Grid Portal creator must construct and deploy both the user interface and the application portions of the Grid Portal, resulting in considerable programming efforts. We aim to easen this burden by applying the state-of-the-art Web/XML interface generation technologies for the former, and the Ninf-G GridRPC system for easily &quot;Gridifying&quot; exisiting applications for the latter, and realizing their seamless integration. The resulting system which we call the &quot;Ninf Portal&quot; allowed concise description and easy deployment of a sample application on the Grid with very small programming efforts.</div> </blockquote>



- **XMLベースGridRPCシステムの構築と評価**  <span onmouseover="document.getElementById('spa02shirasuna').style.display = 'block'"  onmouseout="document.getElementById('spa02shirasuna').style.display = 'none'">[abst]</span>   
白砂 哲, 中田 秀基, 松岡 聡, 関口 智嗣
, *第5回プログラミングおよび応用のシステムに関するワークショップ SPA &#x27;02 オンライン論文集*    , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="spa02shirasuna"> GridRPC は科学技術計算に多く用いられるGrid 上のミドルウェアであるが，それぞれのGirdRPC システムが独自のプロトコルを利用しているため，インテオペラビリティが重要な課題となっている．Web サービスの分野では，SOAP やWSDL といったXML 基盤の標準仕様が用いられており，広く使用されることが期待されている．GridRPC においてもこれらの仕様を用いてインタオペラビリティを確保することが可能であると考えられるが，1) XML 基盤のこれらの仕様がGridRPC に適した記述力を有しているか， 2) コストが高いXML を用いて十分な性能を得ることができるか，などが明らかではない．本研究において，SOAP とWSDL を基盤とするGridRPC を実装し，実験した結果，これらの技術を用いることは有用であることが分かった．SOAP 基盤のGridRPC のナイーブな実装においては大きなオーバヘッドが大きいが，いくつかの性能向上を行なうことにより，本来のバイナリ転送に近い性能が得られた． 一方，配列パラメタの扱いなどのGridRPC 特有なさまざまな機能を実現することは，WSDL の制限により困難であることが分かった．</div> </blockquote>



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



- **Design issues of Network Enabled Server Systems for the Grid**  <span onmouseover="document.getElementById('grid00matsuoka').style.display = 'block'"  onmouseout="document.getElementById('grid00matsuoka').style.display = 'none'">[abst]</span>   
Satoshi Matsuoka, Hidemoto Nakada, Mitsuhisa Sato, Satoshi Sekiguchi
, *Grid Computing -- GRID 2000, Springer-Verlag, LNCS 1971*   , pp. 4-17  , 2001 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="grid00matsuoka"> Network Enabled Server is considered to be a good candidate as a viable Grid middleware, offering an easy-to-use programming model. This paper clarifies design issues of Network Enabled Server systems and discusses possible choices, and their implications, namely those concerning connection methodology, protocol command representation, security methods, etc. Based on the issues, we have designed and implemented new Ninf system v.2.0. For each design decision we describe the rationale and the details of the implementation as dictated by the choices. We hope that the paper serves as a design guideline for future NES systems for the Grid.</div> </blockquote>



- **Ninf Project**    
Kento Aida, Atsuko Takefusa, Hirotaka Ogawa, Osamu Tatebe, Hidemoto Nakada, Hiromitsu Takagi, Yoshio Tanaka, Satoshi Matsuoka, Mitsuhisa Sato, Satoshi Sekiguchi, Umpei Nagashima
, *APAN Conference 2000*    , 2000 



- **Performance Evaluation of a Firewall-compliant Globus-based Wide-area Cluster System**  <span onmouseover="document.getElementById('hpdc9tanaka').style.display = 'block'"  onmouseout="document.getElementById('hpdc9tanaka').style.display = 'none'">[abst]</span>   
Yoshio Tanaka, Mototaka Hirano, Mitsuhisa Sato, Hidemoto Nakada, Satoshi Sekiguchi
, *9th IEEE International Symposium on High Performance Distributed Computing (HPDC 2000)*   , pp. 121-128  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpdc9tanaka"> In this paper, we present a performance evaluation of a wide-area cluster system based on a firewall-enabled Globus metacomputing toolkit. In order to establish communication links beyond the firewall, we have designed and implemented a resource manager called RMF (Resource Manager beyond the Firewall) and the Nexus Proxy, which relays TCP communication links beyond the firewall. In order to extend the Globus Metacomputing Toolkit to the firewall-enabled toolkit, we have built the Nexus Proxy into the Globus toolkit. We have built a firewall-enabled Globus-based wide-area cluster system in Japan and run some benchmarks on it. In this paper, we report various performance results such as the communication bandwidth and latencies obtained as well as application performance involving a tree search problem. In a wide-area environment, the communication latency through the Nexus Proxy is approximately six times larger when compared to that of direct communications. As message size increases however, the communication overhead caused by the Nexus Proxy can be negligible. We have developed a tree search problem using MPICH-G. We used a self-scheduling algorithm, which is considered to be suitable for a distributed heterogeneous metacomputing environment since it performs dynamic load balancing with low overhead. The performance results indicate that the communication overhead caused by the Nexus Proxy is not a severe problem in metacomputing environments.</div> </blockquote>



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



- **クライアント・サーバ型のグローバルコンピューティングシステムの比較 -- Ninf,NetSolve, CORBAの性能評価 --**  <span onmouseover="document.getElementById('jspp00nakagawa').style.display = 'block'"  onmouseout="document.getElementById('jspp00nakagawa').style.display = 'none'">[abst]</span>   
中川貴之, 鈴村豊太郎, 松岡 聡, 中田秀基
, *並列処理シンポジウム JSPP2000 論文集*   , pp. 277-284  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp00nakagawa"> Ninf, NetSolve, Globusをはじめとするグローバルコンピューティング システムの近年の発展により，広域ネットワークを利用して高性能計算を 提供することが可能となった．一方，それらの研究の多くはアーキテクチャや アプリケーションの構築例に偏っており，その種のシステムが持つべき特性 については検証されていない．本稿では，実アプリケーションをNinf, NetSolve, CORBAを用いて実装し，定量的側面ばかりでなく，定性的側面にも 着目して各システムの比較を行った．その結果，グローバルコンピュー ティング専用のシステムが，CORBAのような汎用の分散コンピューティング システムに比べて，管理面，プログラマビリティで勝り，性能面でも WAN上で問題サイズが大きい時にはCORBAを上回ることが明らかになった． この結果により，専用システムの有効性が導かれたが，グローバル コンピューティングのための理想的なソフトウエアアーキテクチャを同定する ためには，引き続き様々なシステムに対する研究が必要であることもわかった．</div> </blockquote>



- **Are Global Computing Systems Useful? - Comparison of Client-Server Global Computing Systems Ninf, NetSolve versus CORBA**  <span onmouseover="document.getElementById('ipdps00suzumura').style.display = 'block'"  onmouseout="document.getElementById('ipdps00suzumura').style.display = 'none'">[abst]</span>   
Toyotaro Suzumura, Takayuki Nakagawa, Satoshi Matsuoka, Hidemoto Nakada, Satoshi Sekiguchi 
, *Proc. of International Parallel and Distributed Processing Symposium*   , pp. 547-556  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipdps00suzumura"> Recent developments of global computing systems such as Ninf, NetSolve and Globus have opened up the opportunites for providing high-performance computing services over wide-area networks. However, most research focused on the individual architectural aspects of the system, or application deployment examples, instead of the necessary charactersistics such systems should intrinsically satisfy, nor how such systems relate with each other. Our comparative study performs deployment of example applications of network-based libraries using Ninf, NetSolve, and CORBA systems. There, we discover that dedicated systems for global computing such as Ninf and NetSolve have management, progammability, and in does not suffer performance disadvantages over more generic distributed computing capabilities provided by CORBA. Such results indicate the advantage of dedicated global computing systems over general systems, stemming further basic research is necessary across multiple systems to identify the ideal software architectures for global computing.</div> </blockquote>



- **NetCFD: a Ninf CFD component for Global Computing, and its Java applet GUI**  <span onmouseover="document.getElementById('hpcasia00sato').style.display = 'block'"  onmouseout="document.getElementById('hpcasia00sato').style.display = 'none'">[abst]</span>   
Mitsuhisa Sato, Kazuhiro Kusano, Hidemoto Nakada, Satoshi Sekiguchi, Satoshi Matsuoka
, *Proc. of HPC Asia 2000*   , pp. 501-506  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcasia00sato"> Ninf is a middleware for building a global computing system in wide area network environments. We designed and implemented a Ninf computational component, netCFD for CFD (Computational Fluid Dynamics). The Ninf Remote Procedure Call (RPC) provides an interface to a parallel CFD program running on any high performance platforms. The netCFD turns high performance platforms such as supercomputers and clusters into valuable components for use in global computing. Our experiment shows that the overhead of a remote netCFD computation for a typical application was about 10\% comparing with its conventional local execution. The netCFD applet GUI which is loaded in a web browser allows a remote user to control and visualize the CFD computation results interactively.</div> </blockquote>



- **グローバルコンピューティングのためのスケジューリングフレームワーク**  <span onmouseover="document.getElementById('ipsj00nakada').style.display = 'block'"  onmouseout="document.getElementById('ipsj00nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 竹房 あつ子, 松岡 聡, 佐藤 三久, 関口 智嗣 
, *情報処理学会論文誌 Vol.41 No.5*   , pp. 1617-1627  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj00nakada"> ネットワーク技術の発展にともない、グローバルコンピューティングシステムがいくつか提案されているが、その計算/通信リソースを十分活用するための手法はいまだ確立されていない。リソースの有効活用のためには、広域分散計算に特有なリソースの変動と不安定さを考慮し、関連する複数のタスクに対して一括して適切にリソースを割り当てるスケジューリング手法が必要とされている。本稿では、グローバルコンピューティング環境において個々のアプリケーションの性能とシステム全体のスループットを両立させるための、階層化されたスケジューリングフレームワークを提案する。さらに、このフレームワークに準拠したNinfシステムのメタサーバスケジューリングフレームワークの実装について述べ、試験的に複数のスケジューリング手法をメタサーバ上に実装しその動作を確認する。この結果、本フレームワークが十分にフレキシブルであることが示された。</div> </blockquote>



- **Overview of a Performance Evaluation System for Global Computing Scheduling Algorithms**  <span onmouseover="document.getElementById('hpdc8takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpdc8takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Satoshi Matsuoka, Hidemoto Nakada, Kento Aida, Umpei Nagashima
, *8th IEEE International Symposium on High Performance Distributed Computing (HPDC8)*   , pp. 97-104  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpdc8takefusa"> While there have been several proposals of high performance global computing systems, scheduling schemes for the systems have not been well investigated.  The reason is difficulties of evaluation by large-scale benchmarks with reproducible results. Our Bricks performance evaluation system would allow analysis and comparison of various scheduling schemes on a typical high-performance global computing setting. Bricks can simulate various behaviors of global computing systems, especially the behavior of networks and resource scheduling algorithms. Moreover, Bricks is componentalized such that not only its constituents could be replaced to simulate various different system algorithms, but also allows incorporation of existing global computing components via its foreign interface. To test the validity of the latter characteristics, we incorporated the NWS system, which monitors and forecasts global computing systems behavior.  Experiments were conducted by running NWS under a real environment versus the simulated environment given the observed parameters of the real environment.  We observed that Bricks behaved in the same manner as the real environment, and NWS also behaved similarly, making quite comparative forecasts under both environments.</div> </blockquote>



- **Globusを用いたグローバルコンピューティング環境の構築とその評価**  <span onmouseover="document.getElementById('ic99tanaka').style.display = 'block'"  onmouseout="document.getElementById('ic99tanaka').style.display = 'none'">[abst]</span>   
田中 良夫, 平野 基孝, 佐藤 三久, 中田 秀基, 関口 智嗣
, *インターネットカンファレンス&#x27;99*   , pp. 97-106  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic99tanaka"> Globusはグローバルコンピューティングのソフトウェアインフラストラクチャ に必要とされる様々な要素技術を提供するツール群である．我々はdenyベース のfirewallを越えて計算資源を利用する機能をGlobusに組み込み，グローバル コンピューティング環境を構築した．今回追加した機能は，新しい型のGlobus Resource Allocation Manager(GRAM)であるRMF(Resource Manager beyond the Firewall)およびNexusのTCP通信を中継するNexusProxyにより実装される．ま た，globusを用いたMPICHの実装であるMPICH-Gを用いて探索問題の並列解法を 実装し，グローバルコンピューティング環境でその実行性能を測定した．本稿 では今回構築したグローバルコンピューティング環境の概要と実装，その上で 並列プログラムを実行した際の性能，プログラミングの留意点，およびグロー バルコンピューティング環境の構築に向けての指針を述べる．グローバルコン ピューティング環境で並列計算を行なう場合，通信量の抑制と負荷分散が効率 に大きな影響を与える．これらの点に留意してプログラミングを行なうことに より，十分実用的な性能が得られることがわかった．</div> </blockquote>



- **Resource Manager for Globus-based Wide-area Cluster Computing**  <span onmouseover="document.getElementById('iwcc99tanaka').style.display = 'block'"  onmouseout="document.getElementById('iwcc99tanaka').style.display = 'none'">[abst]</span>   
Yoshio Tanaka, Mototaka Hirano, Mitsuhisa Sato, Hidemoto Nakada, Satoshi Sekiguchi
, *1st IEEE International Workshop on Cluster Computing (IWCC&#x27;99)*   , pp. 237-244  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="iwcc99tanaka"> In this paper, we present a new type of Globus resource allocation manager (GRAM) called RMF (Resource Manager beyond the Firewall) for wide-area cluster computing. RMF manages computing resources such as cluster systems and enables utilization of them beyond the firewall in global computing environments. RMF consists of two basic modules, a remote job queuing system (Q system) and a resource allocator. The Q system is a remote job queuing system, which schedules jobs submitted from global computing sites. The resource allocator manages resources and allocates them for requested jobs. For communications beyond the firewall between job processes, we designed the Nexus Proxy, which relays TCP communication links beyond the firewall. RMF and the Nexus Proxy provide a global computing environment in which users can easily utilize such parallel systems as cluster systems and supercomputers beyond the firewall.</div> </blockquote>



- **globusにおけるResource Managerの試作 -- グローバルコンピューティング環境の構築に向けて--**    
田中 良夫, 平野 基孝, 佐藤 三久, 中田 秀基, 関口 智嗣 
, *情報処理学会ハイパフォーマンスコンピューティング研究会, Vol.99, No.66*   , pp. 191-196  , 1999 



- **globusを用いたグローバルコンピューティングの性能評価**    
田中 良夫, 佐藤 三久, 中田 秀基, 関口 智嗣
, *情報処理学会システムソフトウェアとオペレーティングシステム研究会, Vol.99, No.32*   , pp. 71-76  , 1999 



- **クライアント・サーバ型のグローバルコンピューティングシステムの比較 --- Ninf, NetSolve, CORBA, Ninf-on-Globus の性能評価 ---**    
鈴村 豊太郎, 中川 貴之, 松岡 聡, 中田 秀基
, *情報処理学会研究会報告 99-HPC-34*    , 1999 



- **Design and Implementations of Ninf: towards a Global Computing Infrastructure**  <span onmouseover="document.getElementById('fgcs99nakada').style.display = 'block'"  onmouseout="document.getElementById('fgcs99nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Mitsuhisa Sato, Satoshi Sekiguchi
, *Future Generation Computing Systems, Metacomputing Issue, Vol.15, Issues 5-6*   , pp. 649-658  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="fgcs99nakada"> The world-wide computing infrastructure on the growing computer network technology is a leading technology to make a variety of information services accessible through the Internet for every users from the high performance computing users through many of personal computing users. The important feature of such services is location transparency; information can be obtained irrespective of time or location in virtually shared manner. In this article, we overview Ninf, an ongoing global network-wide computing infrastructure project which allows users to access computational resources including hardware, software and scientific data distributed across a wide area network. Preliminary performance result on measuring software and network overhead is shown, and that promises the future reality of world-wide network computing.</div> </blockquote>



- **グローバルコンピューティングのためのスケジューリングフレームワーク**  <span onmouseover="document.getElementById('jspp99nakada').style.display = 'block'"  onmouseout="document.getElementById('jspp99nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 竹房 あつ子, 松岡 聡, 佐藤 三久, 関口 智嗣
, *並列処理シンポジウム JSPP&#x27;99 論文集*   , pp. 277-284  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp99nakada"> ネットワーク技術の発展にともない、グローバルコンピューティングシステムが いくつか提案されているが、 その計算/通信リソースを十分活用するための手法はいまだ確立されていない。 リソースの有効活用のために、 広域分散計算に特有なリソースの変動と不安定さを考慮し、 関連する複数のタスクに対して一括して 適切にリソースを割り当てるスケジューリング手法が必要とされている。本稿では、グローバルコンピューティング環境において 個々のアプリケーションの性能とシステム全体のスループットを 両立させるための、 階層化されたスケジューリングフレームワークを提案する。 さらに、このフレームワークに準拠したNinfシステムの メタサーバスケジューリングフレームワークの実装について述べ、 試験的に実装したスケジューリング手法による評価を行う。 この結果、本フレームワークのもつ可能性と、 タスク間のデータ依存関係を考慮したスケジューリングアルゴリズム の重要性が明らかになった</div> </blockquote>



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



- **A Performance Evaluation Model for Scheduling in Global Computing Systems**    
Kento Aida, Atsuko Takefusa, Hidemoto Nakada, Satoshi Matsuoka, Satoshi Sekiguchi, Umpei Nagashima
, *NASA Workshop on Performance-Engineered Information Systems*    , 1998 



- **A Performance Evaluation Model for Effective Job Scheduling in Global Computing Systems**    
Kento Aida, Atsuko Takefusa, Hidemoto Nakada, Satoshi Matsuoka, Umpei Nagashima
, *7th IEEE International Symposium on High Performance Distributed Computing (HPDC7) (poster)*   , pp. 352-353  , 1998 



- **Ninf and PM: Communication Libraries for Global Computing and High-performance Cluster Computing**  <span onmouseover="document.getElementById('fgcs97sato').style.display = 'block'"  onmouseout="document.getElementById('fgcs97sato').style.display = 'none'">[abst]</span>   
Mitsuhisa Sato, Hiroshi Tezuka, Atsushi Hori, Yutaka Ishikawa, Satoshi Sekiguchi, Hidemoto Nakada, Satoshi Matsuoka and Umpei Nagashima
, *Future Generation Computing Systems vol. 13 (1997/98), No. 4-5*   , pp. 349-359  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="fgcs97sato"> This paper presents two advanced communication libraries, Ninf and PM. Ninf is an ongoing global network-wide computing infrastructure project which allows users to access computational resources including hardware, software and scientific data distributed across a wide area network. Computational resources are shared as Ninf remote libraries executable at a remote Ninf server. Users can build an application by calling the libraries with the Ninf Remote Procedure Call. In order to facilitate location transparency and network-wide parallelism, Ninf metaserver maintains global resource information regarding computational server and databases, allocating and scheduling coarse-grained computation for global load balancing. PM is a high performance communication library for workstation clusters connected with myrinet gigabit LAN card, which has a dedicated processor and on-board memory to handle a communication protocol. In order to obtain high performance communication and support a multi-user environment, we co-designed PM, an operating system realized by a daemon process, and the run-time routine for a programming language. Several unique features, e.g., network context switching and modified ACK/NACK flow control algorithm have been developed for PM. PM for the Suns has a speed of 20 micro seconds round trip for a user-level 8 bytes message and 38.6 Mbytes/second bandwidth for an 8 Kbytes message.</div> </blockquote>



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



- **広域計算システムのシミュレーションによる評価 -- Ninfシステムの広域分散環境でのジョブスケージューリング実現に向けて --**  <span onmouseover="document.getElementById('jspp98takefusa').style.display = 'block'"  onmouseout="document.getElementById('jspp98takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 合田 憲人, 小川 宏高, 中田 秀基, 松岡 聡, 佐藤 三久, 関口 智嗣, 長嶋 雲兵
, *並列処理シンポジウム JSPP&#x27;98 論文集*   , pp. 127-134  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp98takefusa"> 高性能広域計算を実現する試みが行われる一方，高性能広域計算のスケジューリングに関する明確な知見は得られていない．これは広域ネットワークで再現性のある大規模性能評価は非常に困難で性能要素に関する調査が不十分なためである．本稿では，高性能広域計算システムにおけるジョブスケジューリングの性能評価を行うシミュレータの設計及び実装と，本シミュレータを用いた性能評価について述べる．本シミュレータでは，待ち行列モデルを用い多様な広域計算システムをシミュレーションすることが可能である．本シミュレータにより実際の広域計算システムをシミュレーションした結果，実測とほぼ同様の結果が得られ，その有効性を確認した．本稿ではまた，本シミュレータを用いたジョブスケジューリング手法の性能評価結果についても述べる．</div> </blockquote>



- **複数クライアントによる LAN/WAN でのNinfの性能**  <span onmouseover="document.getElementById('ipsj98takefusa').style.display = 'block'"  onmouseout="document.getElementById('ipsj98takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 小川宏高, 松岡 聡, 佐藤 三久, 中田秀基, 高木浩光, 関口 智嗣, 長嶋雲兵
, *情報処理学会論文誌 vol.39, no.6*   , pp. 1827-1838  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj98takefusa"> 広域ネットワークの整備につれ，高性能広域分散計算を実現する試みが我々のNinfを含めていくつか行われている．しかしこのような広域計算システムの，特にWANにおいて複数のクライアントが複数のサイトに分散している状況下での性能特性に関する議論は十分になされていない．本稿では，Ninfおよび類似のシステムの実現可能性を調査するため，LAN/WAN環境でLinpack/EPベンチマークを実施し，次のような結果を得た．1）十分なバンド幅があれば，Ninfを用いた方がLocal実行するより高速になる．2）既存の高性能計算機は性能や耐久性の点で広域計算システムの運用に十分なプラットフォームである．3）ベクトル並列計算機（Cray J90）では，高性能並列ライブラリが有効利用できる，すなわち既存の高性能ライブラリの再利用性がある．4）計算主体の計算（EP）では現状の広域計算システムで十分に運用できる．5）通信主体の計算（Linpack）では，LAN環境ではサーバの稼働率が性能を支配し，WAN環境では通信性能と設置条件によって性能に与える影響に一定の傾向がある．</div> </blockquote>



- **Ninf による広域分散並列計算**  <span onmouseover="document.getElementById('ipsj98nakada').style.display = 'block'"  onmouseout="document.getElementById('ipsj98nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高木浩光, 松岡 聡, 長嶋雲兵, 佐藤 三久, 関口 智嗣
, *情報処理学会論文誌 vol.39, no.6*   , pp. 1818-1826  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj98nakada"> ローカルなネットワーク上でのメッセージパッシングライブラリを用いた分散並列計算はすでに広く行なわれている。しかし、ネットワークの高速化によって現実的になりつつある広域ネットワーク上での分散並列計算については、ソフトウェアの枠組が未だ十分に整備されていない。我々は、広域分散並列計算に適した分散計算の枠組として「Ninf」を提案している。Ninf は広域分散環境でのマクロデータフローによる並列実行を支援するシステムで、広域での動的負荷分散とスケジューリングを特徴とする。メッセージパッシングライブラリを用いた手法と比較して（1）広域ネットワークに適した通信パターンを用いる、（2）ユーザにとってプログラミングが容易でかつ再利用性が高い、（3）既存のライブラリの再利用が容易、（4）ネットワーク上の資源の利用が可能、といった特長をもつ。</div> </blockquote>



- **Java による大域的並列計算環境Ninflet**  <span onmouseover="document.getElementById('jspp98takaggi').style.display = 'block'"  onmouseout="document.getElementById('jspp98takaggi').style.display = 'none'">[abst]</span>   
高木 浩光, 松岡 聡, 中田 秀基, 関口 智嗣, 佐藤 三久, 長嶋 雲兵
, *並列処理シンポジウム JSPP&#x27;98 論文集*   , pp. 135-142  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp98takaggi"> Java による大域的並列計算環境「Ninflet」を提案する．Ninflet の目標は， インターネット上に多数存在するとみられる遊休計算機のふんだんな計算資源を 有効利用しつつ，ローカル及びワイドエリアネットワークをシームレスに統合する， 新世代のオブジェクト指向並列計算環境を構築することにある． Ninflet は，大域的計算環境を実現するために重要な要素となる，ポータビリティ， セキュリティ，リソース割り当て，checkpointing，オブジェクト migration の機能の実現に Java の特長を活用する．</div> </blockquote>



- **Ninf Global Computing System - Architecture, Features, and Performance**    
Hidemoto Nakada, Atsuko Takefusa, Hirotaka Ogawa, Kento Aida, Hiromitsu Takagi, Satoshi Matsuoka, Umpei Nagashima, Mitsuhisa Sato, Satoshi Sekiguchi
, *HPCN Workshop on Distributed Computing (Oral presentation)*    , 1998 



- **Utilizing the Metaserver Architecture in the Ninf Global Computing System**  <span onmouseover="document.getElementById('hpcn98nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcn98nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hiromitsu Takagi, Satoshi Matsuoka, Umpei Nagashima, Mitsuhisa Sato, Satoshi Sekiguchi
, *High-Performance Computing and Networking &#x27;98, LNCS 1401*   , pp. 607-616  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcn98nakada"> Rapid increase in speed and availability of global-network is opening up the possibilities of globally-distributed supercomputing, including our Ninf system.Ninf is designed to utilize existing numerical libraries and resources on the Web. It also has global scheduling server called the Ninf Metaserver, which is responsible for scheduling and load-distribution of parallel tasks. The metaserver keeps track of computational servers, and gathers information needed for scheduling. Using the information, it balances loads over computational servers.We performed preliminary benchmarks using the metaserver. There, we observed that scheduling cost can be ignored and dynamic scheduling by the server gained better score than static-cyclic distribution.We also report on our collaborative efforts in bridging Ninf with NetSolve, a similar system being developed at Univ. of Tennessee/ORNL.</div> </blockquote>



- **Ninflet: a Migratable Parallel Objects Framework using Java**  <span onmouseover="document.getElementById('jhp98takagi').style.display = 'block'"  onmouseout="document.getElementById('jhp98takagi').style.display = 'none'">[abst]</span>   
Hiromitsu Takagi, Satoshi Matsuoka, Hidemoto Nakada, Satoshi Sekiguchi, Mitsuhisa Satoh, Umpei Nagashima
, *ACM 1998 Workshop on Java for High-Performance Network Computing*   , pp. 151-159  , 1998 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jhp98takagi"> Ninflet is a Java-based global computing system that builds on our experiences with the Ninf system which facilitated RPC-based computing of numerical tasks in a wide-area network. The goal of Ninflet is to become a new generation of concurrent object-oriented system which harness abundant idle computing powers, and also seamlessly integrate global as well as local network parallel computing. Ninflet is designed to make use of Java features to implement important features in global computing, such as resource allocation, inter- Ninflet communication, security, checkpointing, object migration, and easy server management via HTTP.</div> </blockquote>



- **Multi-client LAN/WAN Performance Analysis of Ninf: a High-Performance Global Computing System**  <span onmouseover="document.getElementById('sc97takefusa').style.display = 'block'"  onmouseout="document.getElementById('sc97takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Satoshi Matsuoka, Hirotaka Ogawa, Hidemoto Nakada, Hiromitsu Takagi, Mitsuhisa Sato, Satoshi Sekiguchi, Umpei Nagashima
, *SC &#x27;97: Proceedings of the 1997 ACM/IEEE conference on Supercomputing*    , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sc97takefusa"> Rapid increase in speed and availability of network of supercomputers is making high-performance global computing possible, including our Ninf system. However, critical issues regarding system performance characteristics in global computing have been little investigated, especially under multi-client, multi-site WAN settings. In order to investigate the feasibility of Ninf and similar systems, we conducted benchmarks under various LAN and WAN environments, and observed the following results: 1) Given sufficient communication bandwidth, Ninf performance quickly overtakes client local performance, 2) current supercomputers are sufficient platforms for supporting Ninf and similar systems in terms of performance and OS fault resiliency, 3) for a vector-parallel machine (Cray J90), employing optimized data-parallel library is a better choice compared to conventional task-parallel execution employed for non-numerical data servers, 4) computationally intensive tasks such as EP can readily be supported under the current Ninf infrastructure, and 5) for communication-intensive applications such as Linpack, server CPU utilization dominates LAN performance, while communication bandwidth dominates WAN performance, and furthermore, aggregate bandwidth could be sustained for multiple clients located at different Internet sites; as a result, distribution of multiple tasks to computing servers on different networks would be essential for achieving higher client-observed performance. Our results are not necessarily restricted to the Ninf system, but rather, would be applicable to other similar global computing systems.</div> </blockquote>



- **Preliminary Evaluation of Scheduling in Ninf: a Global Computing System**  <span onmouseover="document.getElementById('iwia97matsuoka').style.display = 'block'"  onmouseout="document.getElementById('iwia97matsuoka').style.display = 'none'">[abst]</span>   
Satoshi Matsuoka, Hirotaka Ogawa, Atsuko Takefusa, Hidemoto Nakada, Kento Aida, Umpei Nagashima, Mitsuhisa Sato, Satoshi Sekiguchi
, *International Workshop on Innovative Architectures &#x27;97*   , pp. 7p  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="iwia97matsuoka"> Rapid increase in speed and availability of global-network is opening up the possibilities of globally-distributed supercomputing, including our Ninf system. However, performance characteristics of these systems have been little investigated, especially under multi-clients, multi-sites situations. In order to establish methodology to schedule multiple job requests to multiple computational servers effectively and guarantee performance per each client, we conducted benchmarks under various WAN environments. There, we observed that communication bandwidth dominated performance for communication-intensive applications such as Linpack, and aggregate bandwidth could be sustained for multi-clients located at different internet sites. Based on these observations, we propose the need for a simulation model based on queuing theory. And we also performed preliminary benchmarks using our scheduling server, called the Ninf Metaserver. We also report on our collaborative efforts in bridging Ninf with NetSolve, a similar system being developed at Univ. of Tennessee/ORNL.</div> </blockquote>



- **Ninflet -- Java による World-Wide High Performance Computing 環境**  <span onmouseover="document.getElementById('ic97takagi').style.display = 'block'"  onmouseout="document.getElementById('ic97takagi').style.display = 'none'">[abst]</span>   
高木浩光, 松岡 聡, 中田秀基, 関口 智嗣, 佐藤 三久, 長嶋雲兵
, *インターネットカンファレンス&#x27;97*    , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic97takagi"> インターネット上の遊休計算機の計算パワーを世界規模で共有、 共同利用するための環境として、 Java の secure で architechture neutral な特長を活かした、 「Ninflet システム」を提案する。 本論文では、Ninflet システムの基本アーキテクチャ、並列分散処理への応用、 運用形態に関する考察、関連研究について述べる。</div> </blockquote>



- **高性能広域計算システムNinfのスケジューリングに関する予備的考察**    
小川宏高, 竹房あつ子, 中田秀基, 合田憲人, 松岡 聡
, *情報処理学会研究報告 97-HPC-67*    , 1997 



- **マルチクライアントによるネットワーク数値情報システムNinfの性能**  <span onmouseover="document.getElementById('jspp97takefusa').style.display = 'block'"  onmouseout="document.getElementById('jspp97takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 小川宏高, 松岡 聡, 佐藤 三久, 中田秀基, 関口 智嗣, 長嶋雲兵
, *並列処理シンポジウム JSPP&#x27;97 論文集*   , pp. 273-280  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp97takefusa"> ネットワーク数値情報システムNinfは，広域ネットワークに分散した計算資源や情報資源を利用して高速・高性能・高品質な科学技術計算を実現するための基盤システムである．本稿ではNinfの全体構成について述べるとともに，LANおよびWANにおいてLinpack benchmarkを用いて，シングル/マルチクライアント環境での本システムの性能評価を実施した．この結果，現実的な広域分散利用条件でのNinfシステムの実用性，堅牢性を確認した．また，既存のベクトルパラレルマシンをはじめとする並列計算機がNinfによってネットワーク計算資源として有効に活用されることを示した．</div> </blockquote>



- **Ninf による広域分散並列計算**  <span onmouseover="document.getElementById('jspp97nakada').style.display = 'block'"  onmouseout="document.getElementById('jspp97nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高木浩光, 松岡 聡, 長嶋雲兵, 佐藤 三久, 関口 智嗣
, *並列処理シンポジウム JSPP&#x27;97 論文集*   , pp. 281-288  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp97nakada"> ローカルなネットワーク上でのメッセージパッシングライブラリを用いた 分散並列計算はすでに広く行なわれている。 しかし、ネットワークの高速化によって現実的になりつつある 広域ネットワーク上での分散並列計算については、 ソフトウェアの枠組が未だ十分に整備されていない。我々は、広域分散並列計算に適した分散計算の枠組として「Ninf」を提案している。 Ninf は広域分散環境でのマクロデータフローによる並列実行を支援するシステムで、 広域での動的負荷分散とスケジューリングを特徴とする。 メッセージパッシングライブラリを用いた手法に比較して (1)広域ネットワークに適した通信パターンを用いる、 (2)ユーザにとってプログラミングが容易でかつ再利用性が高い、 (3)既存のライブラリの再利用が容易、 (4)ネットワーク上の資源の利用が可能、 といった特長をもつ。</div> </blockquote>



- **Ninf: A Network based Information Library for a Global World-Wide Computing Infrastracture**  <span onmouseover="document.getElementById('hpcn97sato').style.display = 'block'"  onmouseout="document.getElementById('hpcn97sato').style.display = 'none'">[abst]</span>   
Mitsuhisa Sato, Hidemoto Nakada, Satoshi Sekiguchi, Satoshi Matsuoka, Umpei Nagashima and Hiromitsu Takagi
, *HPCN&#x27;97 (LNCS-1225)*   , pp. 491-502  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcn97sato"> Ninf is an ongoing global network-wide computing infrastructure project which allows users to access computational resources including hard-ware, software and scientific data distributed across a wide area network. Ninf is intended not only to exploit high performance in network parallel computing, but also to provide high quality numerical computation services and accesses to scientific database published by other researchers. Computational resources are shared as Ninf remote libraries executable at a remote Ninf server. Users can build an application by calling the libraries with the Ninf Remote Procedure Call, which is designed to provide a programming interface similar to conventional function calls in existing languages, and is tailored for scientific computation. In order to facilitate location transparency and network-wide parallelism, Ninf metaserver maintains global resource information regarding computational server and databases, allocating and scheduling coarse-grained computation for global load balancing. Ninf also interfaces with the WWW browsers for easy accessi-bility.</div> </blockquote>



- **ネットワーク数値情報システムNinf: マルチクライアント環境での性能**  <span onmouseover="document.getElementById('hpc9703takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc9703takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 小川宏高, 松岡 聡, 佐藤三久, 中田秀基, 関口智嗣, 長嶋雲兵
, *情報処理学会研究報告 97-HPC-21*   , pp. 3-8  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9703takefusa"> ネットワーク数値情報システムNinfは，広域ネットワークに分散した計算資源や情報資源を利用して高速・高性能・高品質な科学技術計算を実現するための基盤システムである．本稿ではNinfの全体構成について述べるとともに，Linpack benchmarkを用いて，シングル/マルチクライアント環境での本システムの性能評価を実施した．この結果，現実的な広域分散利用条件でのNinfシステムの実用性，堅牢性を確認した．また，既存のベクトルパラレルマシンを始めとする並列計算機がNinfによってネットワーク計算資源として有効に活用されることを示した．</div> </blockquote>



- **Ninf による広域分散並列計算**    
中田秀基, 高木浩光, 松岡 聡, 長嶋雲兵, 佐藤 三久, 関口智嗣
, *情報処理学会研究報告 97-HPC-21*   , pp. 9-14  , 1997 



- **分散メモリ計算機用 Ninf API の実現に向けて**  <span onmouseover="document.getElementById('hpc9608ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc9608ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 松岡 聡, 中田秀基, 佐藤 三久, 関口 智嗣
, *情報処理学会研究報告 96-HPC-81*   , pp. 159-164  , 1996 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9608ogawa"> ネットワーク数値情報ライブラリNinf　(etwork　based　Information　library　for　High　Performance　Computin)は，広域に分散した計算資源や情報資源を利用した超分散並列計算の基盤を提供するソフトウェアシステムである．本稿では，このNinfシステム上で分散メモリ型並列計算機を計算資源として利用する場合に，フロントエンドマシンやI/Oプロセッサ等の単一ノードで動作するNinfサーバに計算情報が集中して律速となる問題を指摘する．この問題を解決するために，初期データ分散を記述するための共通のAPIを提供すると共に，クライアントとの接続を各ノードに対して適切に順次ハンドオフしていく機構の導入を提案する．また，ハンドオフ機構のコア部分を富士通のAP1000上に実現し予備評価を行った結果，16％の性能向上を得た．</div> </blockquote>



- **ネットワーク数値情報ライブラリ Ninf: システム実装と評価**  <span onmouseover="document.getElementById('hpc9608sekiguchi').style.display = 'block'"  onmouseout="document.getElementById('hpc9608sekiguchi').style.display = 'none'">[abst]</span>   
関口智嗣, 中田秀基, 佐藤 三久, 長嶋雲兵, 松岡 聡
, *情報処理学会研究報告 96-HPC-81*   , pp. 153-158  , 1996 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9608sekiguchi"> 科学技術計算におけるGlobal　Computingを実現する基盤システムとしてネットワーク数値情報ライブラリNinf　(etwork　based　Information　Library　for　Global　World?Wide　Infrastructur)を提案している．Ninfでは広域ネットワーク上に分散された計算資源や情報資源へのアクセスを容易に実現することによりハイパフォーマンスコンピューティングを支援することを目標とする．サーバーをインターネット上に複数設定し，遠隔地のユーザは提供されたインターフェース関数を通じてNinfのライブラリ関数を呼び出すだけで，Ninfサービスを受けられる．本稿ではNinfシステムの概観と実現について述べ，Ninf?RPCを用いたLinpackによる性能評価を行う．この結果，問題サイズが小さくてもNinfを用いたネットワークコンピューティングの現実的可能性を実証することができた．</div> </blockquote>



- **-- Ninf -- : Network base information library for globally high performance computing**    
Satoshi Sekiguchi, Mitsuhisa Sato, Hidemoto Nakada, Umpei Nagashima
, *Parallel Object-Oriented Methods and Applications (POOMA)*    , 1996 



- **ネットワーク数値情報ライブラリ：Ninfを用いた数値計算環境システムの開発−NinfCalcの試作**    
新居由佳子, 高木浩光, 長嶋雲兵, 中田秀基, 佐藤三久, 松岡聡, 関口智嗣
, *情報処理学会第53回全国大会*    , 1996 



- **Ninf: World-Wide Computing指向のネットワーク数値情報ライブラリ**    
佐藤 三久, 中田 秀基, 関口 智嗣, 松岡 聡, 長嶋 雲兵
, *インターネットコンファレンス&#x27;96*    , 1996 



- **ネットワーク数値ライブラリ Ninf におけるメタサーバアーキテクチャ**  <span onmouseover="document.getElementById('hpc9603nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc9603nakada').style.display = 'none'">[abst]</span>   
中田秀基, 草野貴之, 松岡聡, 佐藤三久, 関口智嗣
, *情報処理学会研究報告 96-HPC-22*   , pp. 77-82  , 1996 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc9603nakada"> ネットワーク数値情報ライプラリ Ninf (Network based Information library for High Performance Computing)は、高速なネットワークを前提として、主に数値演算の分野において、計算自体を多くのユーザに提供することを目指したシステムてある。本稿では、Ninfシステムを講築する要素の一つであるメタサーバに関して、そのアーキテクチヤを示し、簡単な性能予備評価を示す。メタサーバは、サーバとクライアントの間にたちサーバの場所をクライアントに対して隠蔽する役割を果たす。また、メタサーバを用いることにより、簡単な分散並列計算が可能になる。
To establish a framework of information sharing in the numerical computation area, we have proposed the Ninf, Network based information library for high performance computing. In this paper, we show a Meta Server architecture, which is a component of the Ninf system. Meta Server stand between the Server and the Client and hides the Server from the Client. It also enables easy distributed concurrent computation.</div> </blockquote>



- **ネットワーク数値情報ライブラリ Ninf のための RPCシステムの概要**    
中田秀基, 佐藤三久, 関口智嗣
, *電子技術総合研究所 Tecnical Report TR-95-28*    , 1995 



        
