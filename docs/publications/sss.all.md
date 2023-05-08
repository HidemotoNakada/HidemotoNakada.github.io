---
layout: default
---
# SSS 

- **SSS-MapReduceのグラフ処理アプリケーションによる評価**  <span onmouseover="document.getElementById('hpc1302nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc1302nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川 宏高, 工藤 知宏
, *研究報告ハイパフォーマンスコンピューティング 2013-HPC-138*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1302nakada"> SSS はキーバリューストアを基盤として採用することで、通常のファイルシステムベースの MapReduce システムと比較して、より柔軟なワークフローを構築することが可能となっている。本稿ではこのような SSS の特性のメリットを確認するために、複雑なワークフロー処理を伴うグラフ処理システム PEGASUS による評価を行った。PEGASUS は Hadoop 向けに記述されている。この PEGASUS の提供するアプリケーションの一部を SSS 固有の機能を用いて SSS 上に再実装し、オリジナルの Hadoop 版と比較した。評価の結果、PEGASUS の移植において、SSS を用いることでワークフロー構造を単純化するとともに、データ構造をバイナリ化することが可能であることがわかった。この結果多くの場合において高速化に成功し、特にブロック化した場合においては最大で約 2.1 倍の高速化を実現できることを確認した。</div> </blockquote>



- **Stream Processing with BigData: SSS-MapReduce**  <span onmouseover="document.getElementById('cloudcom12nakada_poster').style.display = 'block'"  onmouseout="document.getElementById('cloudcom12nakada_poster').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hirotaka Ogawa, Tomohiro Kudoh
, *IEEE CloudCom 2012 (poster)*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cloudcom12nakada_poster"> We propose a MapReduce based stream processing system, called SSS, which is capable of processing stream along with large scale static data. Unlike the existing stream processing systems that can work only on the relatively small on-memory data-set, SSS can process incoming streamed data consulting the stored data. SSS processes streamed data with continuous Mappers and Reducers, that are periodically invoked by the system. It also supports merge operation on two set of data, which enables stream data processing with large static data.</div> </blockquote>



- **Stream Processing with Bigdata by SSS-MapReduce** [[Paper](dataDir/eScience12nakada_poster.pdf)]  <span onmouseover="document.getElementById('eScience12nakada_poster').style.display = 'block'"  onmouseout="document.getElementById('eScience12nakada_poster').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hirotaka Ogawa, Tomohiro Kudoh
, *IEEE International Conference on eScience (eScience 2012) (poster)*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="eScience12nakada_poster"> We propose a MapReduce based stream processing system, called SSS, which is capable of processing stream along with large scale static data. Unlike the existing stream processing systems that can work only on the relatively small on-memory data-set, SSS can process incoming streamed data consulting the stored data. SSS processes streamed data with continuous Mappers and Reducers, that are periodically invoked by the system. It also supports merge operation on two set of data, which enables stream data processing with large static data.</div> </blockquote>



- **PrefixSpan法のMapReduce実装の改良** [[Paper](dataDir/cpsy1210nakada.pdf)]  <span onmouseover="document.getElementById('cpsy1210nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1210nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 井上 辰彦, 小川 宏高, 工藤 知宏
, *信学技報, vol. 112, no. 237, CPSY2012-40.*   , pp. 55-60  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1210nakada"> 分散キーバリューストアをベースとし、Owner Computeルールで計算を実行することで、高速な繰り返し処理を可能とするMapReduce処理系SSSを開発している。このSSSの評価の一つとして、PrefixSpan法による系列パターン抽出を実世界アプリケーションとして利用して来た。しかし、既存の手法では大規模なデータに対しては十分な絶対性能が得られていなかった。本稿ではPrefixSpanをMapReduceで実装するための新たな手法を提案する。提案手法ではデータの流れを見直すことによって、これまでReduceで行なっていた処理を、Mapに移すことによって大幅な速度の向上を得た。具体的には4Mのソースコードのデータに対してSSSで約60倍、Hadoopで約3倍の高速化を実現した。</div> </blockquote>



- **MapReduce処理系SSSにおけるContinuous MapReduceの実装** [[Paper](dataDir/hpc1210nakada.pdf)]  <span onmouseover="document.getElementById('hpc1210nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc1210nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川 宏高, 工藤 知宏
, *情報処理学会研究報告2011-HPC-136*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1210nakada"> 継続的に生成されるストリームデータを、大容量データと付きあわせて処理するためのシステムを提案する。従来のストリーム計算システムは、オンメモリの比較的少量のデータしか参照できない。一方Hadoopに代表されるファイルベースのMapReduceシステムを拡張し、ストリームデータに対応させる研究も存在するが、ストリームデータとストレージ上のデータをうまく組み合わせて処理することのできる処理系はない。我々の提案するSSSは、間欠的に起動するMapper / Reducer プロセスでストリームデータの処理を行う。この際にストレージ上の既存データとのマージ操作を行うことで、ストレージ上の大容量データとストリームデータを付きあわせて処理することが可能になる。本稿ではSSSのストリームデータ処理機構の概要と、ストリームデータ処理の予備的評価の結果を示す。予備評価の結果、提案システムは1ノードあたりおよそ秒間0.14Miレコードを処理できることが確認できたが、読み出しスレッドとの干渉により間欠的に書き込みスループットが大幅に低下し、平均としては秒間0.095Miレコード程度となることがわかった。</div> </blockquote>



- **MapReduce処理系SSSにおけるKey Value Store アクセス手法の改良** [[Paper](dataDir/cpsy1208nakada.pdf)] [[Slides](dataDir/cpsy1208nakada-slides.pdf)]  <span onmouseover="document.getElementById('cpsy1208nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1208nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川 宏高, 工藤 知宏
, *信学技報, Vol.112, No.173 CPSY2012-9 - CPSY2012-30*   , pp. 103-108  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1208nakada"> われわれが開発中のMapReduce処理系SSSは、既存のKey Value Store（KVS）であるTokyoCabinetを要素KVSとする分散KVS上に構築されている。既存のSSS実装ではTokyoCabinetをネットワークサーバ化するレイヤであるTokyoTyrantを改変し、利用してきた。しかし、性能上の問題点が確認されたため、TokyoTyrant を廃し、独自のネットワーク・サーバレイヤを導入した。この導入により、１）ネットワーク通信時のデータコピー削減によるアクセス高速化、２）タプルグループごとにデータベースファイルを持つことによるグループ削除の高速化、３）キーに対するプレフィックス、ポストフィックスを廃することによる転送データ量の削減、を実現することができた。</div> </blockquote>



- **MapReduce処理系SSSのアプリケーションによる消費電力測定** [[Paper](dataDir/hpc1208ogawa.pdf)]  <span onmouseover="document.getElementById('hpc1208ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1208ogawa').style.display = 'none'">[abst]</span>   
小川 宏高, 中田 秀基, 高野 了成, 工藤 知宏
, *情報処理学会研究報告2011-HPC-135*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1208ogawa"> MapReduce は,大規模なデータインテンシブ計算の実装手段として広範に用いられている.その単 純なプログラミングモデルゆえ,MapReduce はデータインテンシブ計算のみならず,より一般的な HPC 分野の並列分散アプリケーションのためのプログラミングツールとしても利用されつつある.われわれは イタレーションが高速で柔軟なワークフローの構成が可能な大規模データ処理システムの実現を目的とし て,MapReduce 処理系 SSS を開発している.Hadoop が HDFS と呼ばれる一種の分散ファイルシステム を基盤としているのに対して,SSS は分散キーバリューストアを基盤としている点が大きく異なる.一方 で,こうした処理系の利活用によってますます大規模な計算リソースを必要とするようになると,ランニ ングコスト,とりわけ電力コストの問題は避けられない問題となる.われわれは消費電力に対して処理系 をチューニングする必要があると考え,そのために実験用クラスタの消費電力を秒単位で計測・報告する システムを構築した.その上で,本稿では English Wikipedia の全テキストデータを対象に Word Count を実行するベンチマーク実験を実施したので本稿ではその結果を示す.</div> </blockquote>



- **MapReduce処理系SSSの実装と評価** [[Paper](dataDir/sacsis12ogawa_poster.pdf)]    
小川宏高, 中田 秀基, 高野 了成, 工藤知宏
, *SACSIS2012予稿集（ポスタ）*   , pp. 44  , 2012 



- **MapReduce処理系SSSに向けたKVSの改良** [[Paper](dataDir/cpsy1204nakada.pdf)]  <span onmouseover="document.getElementById('cpsy1204nakada').style.display = 'block'"  onmouseout="document.getElementById('cpsy1204nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *信学技報, Vol.112, No.2 CPSY2012-1 - CPSY2012-8*   , pp. 19-24  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1204nakada"> 広く用いられている Hadoop と比較して、より広い範囲に適用可能な MapReduce 処理系 SSS を開発して いる。SSS はオープンソースのキーバリューストア(KVS)である Tokyo Cabinet とそのネットワークインターフェ イスである Tokyo Tyrant をストレージとして用いる。しかし、SSS のアクセスパターンはバルクでの読み出し、書き 込み、削除が主で、Tokyo Tyrant が本来想定している細粒度のアクセスとはかけ離れており、Tokyo Tyrant が用意 する API を利用するだけでは、Tokyo Cabinet/Tokyo Tyrant 本来の性能を引き出すことが出来なかった。本稿では われわれが行った、Tokyo Cabinet に対する改変について報告する。SSS が行う範囲指定処理を Tokyo Cabinet およ び Tokyo Tyrant に追加し、さらに内部でのロックを最適化した。その結果、Tokyo Cabinet を直接用いるマイクロ ベンチマークで、読み込み時 5 倍書き込み時 2 倍の速度向上を確認した。また、SSS 全体としてのマクロベンチマー クでも読み込み時 3 倍、書き込み時で 1.3 倍の速度向上を確認した。</div> </blockquote>



- **MapReduce 処理系 SSS の PrefixSpan 法による評価** [[Paper](dataDir/hpc1203nakada.pdf)]  <span onmouseover="document.getElementById('hpc1203nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc1203nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *情報処理学会研究報告2011-HPC-133*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1203nakada"> MapReduceプログラミングモデルの幅広いアプリケーションへの適用をめざし、より柔軟で複雑なワークフロー実行を可能にするMapReduce処理系SSSを開発している。SSSは代表的なMapReduce処理系であるHadoopとは大きく構成が異なり、したがって性能的特性も大きく異なる。われわれはSSSの有効なアプリケーション領域を知るべく、合成的ベンチマークでの評価とともに実アプリケーションでの評価を行っている。本稿では、先行研究で述べたPrefixSPan法による系列パターン抽出の改良と、疎行列ベクトル積について述べる。評価の結果、いずれのアプリケーションにおいてもSSSはHadoopよりも高性能であることが確認できた。</div> </blockquote>



- **An Implementation of Sawzall on Hadoop** [[Paper](dataDir/cute11nakada.pdf)] [[Slides](dataDir/cute11nakada-slides.pdf)]  <span onmouseover="document.getElementById('cute11nakada').style.display = 'block'"  onmouseout="document.getElementById('cute11nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Tatsuhiko Inoue, Tomohiro Kudoh
, *CUTE 2011(The 6th International Conference on Ubiquitous Information Technologies &amp; Applications)*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cute11nakada"> Sawzall is a script language designed for batch processing of large amount of data, based on MapReduce parallel execution model, which is introduced by Google in 2006. Sawzall allows programmers only to program {\it mappers} to ease the burden for them. Sawzall provides a set of built-in {\it aggregators} that provides reducing function, from which programmers could pick and use. We have implemented a Sawzall compiler and runtime, called \scns, which allows Sawzall scripts to run in parallel on Hadoop. We employed Scala language to leverage Scala&#x27;s parser combinator libraries for Sawzall syntax parsing. It enabled easy implementation of parser and potential future extension of the language. This paper provides detailed implementation of the system. We performed evaluation on the system comparing with the Java programs that use native Hadoop API and szl, a Sawzall open source implementation from Google. We confirmed that overhead imposed by \sc is small enough, and the execution speed is comparable with szl.</div> </blockquote>



- **Implementation and evaluation of SSS: a Key-Value Store based MapReduce Framework**  <span onmouseover="document.getElementById('cloudcom11poster-nakada').style.display = 'block'"  onmouseout="document.getElementById('cloudcom11poster-nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hirotaka Ogawa, Tomohiro Kudoh
, *CloudCom 2011 poster*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cloudcom11poster-nakada"> Design and Implementation of a MapReduce framework SSS are described. MapReduce is considered to be a promising parallel programming model for broad range of applications. For that purpose, a flexible MapReduce framework is required that enables programmers to easily combine Mappers and Reducers into workflows that may involve iterations. Hadoop, the most widely used MapReduce framework, is not flexible enough, however. Iteration overhead of Hadoop is too big to perform fine-grained iterations. A job in Hadoop always composed of one Mapper and one Reducer, limiting the shape of workflows. We propose a MapReduce framework based on distributed KVS, called SSS. In SSS, Mappers and Reducers have the same data access pattern. making possible to have flexible combination of Mappers and Reducers. Furthermore, SSS employs Owner Computes Rule which enables faster iteration. Here, we provide detailed design and implementation of SSS. We also demonstrate the performance of SSS using K-means clustering application.</div> </blockquote>



- **SSS：a MapReduce Framework based on Distributed Key-value Store** [[Paper](dataDir/sc11poster-nakada.pdf)]  <span onmouseover="document.getElementById('sc11poster-nakada').style.display = 'block'"  onmouseout="document.getElementById('sc11poster-nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hirotaka Ogawa, Tomohiro Kudoh
, *SC11 Poster*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sc11poster-nakada"> MapReduce has been very successful in implementing large-scale data-intensive applications. Because of its simple programming model, MapReduce has also begun being utilized as a programming tool for more general distributed and parallel HPC applications. However, its applicability is often limited due to relatively inefficient runtime performance and hence insufficient support for flexible workflows. In particular, the performance problem is not negligible in iterative MapReduce applications. We implemented new MapReduce framework SSS based on distributed key-value store, that supports flexible workflows. Mappers and reducers read key-values only from its local storage enjoying high throughput and low latency. We evaluated SSS comparing with Hadoop using synthetic benchmark and real application. The result showed that SSS is significantly faster than Hadoop, especially for shuffle-intensive jobs and iterative jobs.</div> </blockquote>



- **分散KVSに基づくMapReduce 処理系SSS** [[Paper](dataDir/ic11nakada-poster.pdf)]    
中田 秀基, 小川宏高, 工藤知宏
, *インターネットコンファレンス 2011 ポスタ*    , 2011 



- **分散KVSに基づくMapReduce 処理系SSS** [[Paper](dataDir/ic11nakada.pdf)] [[Slides](dataDir/ic11nakada-slides.pdf)]  <span onmouseover="document.getElementById('ic11nakada').style.display = 'block'"  onmouseout="document.getElementById('ic11nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *インターネットコンファレンス 2011 (IC2011) 論文集*   , pp. 21−29  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic11nakada"> 大量ログ解析のための技術として提案されたMapReduce は、新しい並列プログラミング手法として、より広範なアプリケーションへの応用が期待されているが、そのためには、MapとReduceを自由に組み合わせたワークフローの実行が必須となる。しかし、広く利用されているMapReduce処理系Hadoopは、ファイルシステムをベースとし、MapとReduceの間の通信を特別扱いにする構成を取っているため、MapとReduceが1対1に対応する構造しか記述することができない。このためワークフローの実行が非効率となる。われわれは分散KVSをベースに構成したMapReduce 処理系SSSを提案する。SSSではMapとReduceは、いずれも分散KVSからデータを読み込み、分散KVSに書き込む。このためMapとReduceを自由に組み合わせたワークフローを構成し、効率的に実行することが可能になる。本稿では、SSSの実装を詳述するとともに、合成ベンチマークプログラムおよび、K-meansによるHadoopとの比較評価を示す。評価の結果、SSSはHadoopよりも殆どの場合において高速であることが確認できた。</div> </blockquote>



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



- **Implementing a Key-Value Store based MapReduce Framework** [[Paper](dataDir/fast11ogawa-poster.pdf)]  <span onmouseover="document.getElementById('fast11ogawa-poster').style.display = 'block'"  onmouseout="document.getElementById('fast11ogawa-poster').style.display = 'none'">[abst]</span>   
Hirotaka Ogawa, Hidemoto Nakada, Tomohiro Kudoh
, *Proceedings of 9th USENIX Conference on File and Storage Technologies*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="fast11ogawa-poster"> MapReduce has been very successful in implementing large-scale data-intensive applications. Because of its simple programming model, MapReduce has also begun being utilized as a programming tool for more general distributed and parallel applications. However, its applicability is often limited due to relatively inefﬁcient runtime performance and hence insufﬁcient support for ﬂexible workﬂows. In particular, the performance problem is not negligible in iterative MapReduce applications. In order to resolve such situations, we have been developing a new MapReduce prototype system called “SSS”, which is based on distributed key-value store (KVS). In this poster, we present the design and implementation of SSS and the tentative benchmark results.</div> </blockquote>



- **Hadoop上で動作するSawzallサブセットの実装** [[Paper](dataDir/pro1101nakada.pdf)]  <span onmouseover="document.getElementById('pro1101nakada').style.display = 'block'"  onmouseout="document.getElementById('pro1101nakada').style.display = 'none'">[abst]</span>   
中田秀基, 井上辰彦, 工藤知宏
, *情報処理学会PRO研究会 2010-4-(1)*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pro1101nakada"> Sawzall は、Google が 2006 年に発表した大容量データの並列バッチ処理に適し た言語である。Sawzall の計算モデルは MapReduce 型の分散演算であるが、リダ クション操作を組み込みの Aggregator に限定することで、エンドユーザによる容易 な記述を可能にしている。われわれは現在開発中の並列データ処理機構上の言語処 理系を開発するための 1 ステップとして、Hadoop 上で動作する Scala 言語による Sawzall 言語のサブセット処理系を実装した。文法やセマンティクスに関しては明確 な定義がなかったため、2006 年の論文をベースに推測した。Scala は Java VM 上 で動作するため、Java で記述される Hadoop 上での実行は容易である。構文解析に Scala 言語の Parser Combinator を用いることで、処理系の記述量を削減した。言 語インタプリタは、Hadoop の Mapper 上で動作する。Reducer 上では処理系の提 供する Aggregater が動作する。Hadoop で直接記述した場合と、プログラム量およ び実行速度の点で比較を行った。比較の結果、プログラム量は大幅に小さくなる一方、 実行速度の面でも一定のオーバヘッドがあることが確認された。</div> </blockquote>



- **SSS: An Implementation of Key-value Store based MapReduce Framework** [[Paper](dataDir/mapred10ogawa.pdf)]  <span onmouseover="document.getElementById('mapred10ogawa').style.display = 'block'"  onmouseout="document.getElementById('mapred10ogawa').style.display = 'none'">[abst]</span>   
Hirotaka Ogawa, Hidemoto Nakada, Ryousei Takano, Tomohiro Kudoh
, *Proceedings of 2nd International Conference on Cloud Computing Technology and Science*   , pp. 745-761  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="mapred10ogawa"> MapReduce has been very successful in implementing large-scale data-intensive applications. Because of its simple programming model, MapReduce has also begun being utilized as a programming tool for more general distributed and parallel applications, e.g., HPC applications. However, its applicability is limited due to relatively inefficient runtime performance and hence insufficient support for flexible workflow. In particular, the performance problem is not negligible in iterative MapReduce applications. On the other hand, today, HPC community is going to be able to utilize very fast and energy-efficient Solid State Drives (SSDs) with 10 Gbit/sec-class read/write performance. This fact leads us to the possibility to develop ``High-Performance MapReduce&#x27;&#x27;, so called. From this perspective, we have been developing a new MapReduce framework called ``SSS&#x27;&#x27; based on distributed key-value store (KVS). In this paper, we first discuss the limitations of existing MapReduce implementations and present the design and implementation of SSS. Although our implementation of SSS is still in a prototype stage, we conduct two benchmarks for comparing the performance of SSS and Hadoop. The results indicate that SSS performs 1-10 times faster than Hadoop.</div> </blockquote>



- **高速フラッシュメモリに適したキーバリューストアの予備的評価** [[Paper](dataDir/hpc1002-ogawa.pdf)]  <span onmouseover="document.getElementById('hpc1002-ogawa').style.display = 'block'"  onmouseout="document.getElementById('hpc1002-ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 美田晃伸, 広渕崇宏, 高野了成, 工藤知宏
, *情報処理学会研究報告2010-HPC-124*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc1002-ogawa"> 大規模なデータインテンシブアプリケーションの高性能実行の必要性から，大規模データ処理に特化された分散処理を実現する，Data-Intensive Scalable Computing(DISC) が注目されている．MapReduce は，そうした DISC を実現するシステムのひとつであるが，近年利用可能になってきた，10Gbit/sec クラスの読み書き性能を持つ高速な SSD (Solid State Drive) との組み合わせでは，ソフトウェアオーバヘッドが課題となり，十分な性能が得られない危惧がある．そこで我々は，10Gbit/sec クラスの読み書き性能を持つフラッシュメモリストレージに適した，MapReduce システムの実現を目指し，分散キーバリューストアを基盤とする MapReduce システムのプロトタイプ実装を行った．本稿では，我々のプロトタイプ実装の概要を示すとともに，その基盤となるキーバリューストアの既存実装の性能評価を行う．</div> </blockquote>



- **高速フラッシュメモリ向けMapReduceフレームワークの実現に向けて** [[Paper](dataDir/swopp09-ogawa.pdf)]  <span onmouseover="document.getElementById('swopp09-ogawa').style.display = 'block'"  onmouseout="document.getElementById('swopp09-ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 広渕崇宏, 高野了成, 工藤知宏
, *情報処理学会研究報告2009-HPC-121*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-ogawa"> 大規模なデータインテンシブアプリケーションの高性能実行の必要性から，大規模データ処理に特化された分散処理を実現する，Data-Intensive Scalable Computing(DISC) が注目されている．DISC は，安価なハードディスクと Gigabit Ethernet を用いたクラスタシステムを用いて，大容量データをストリーム的に扱うワークロードを実行するシステムとして非常に有効である．一方で近年利用可能になってきた，10Gbit/sec クラスの読み書き性能を持つ高速な SSD (Solid State Drive) との組み合わせでは，ソフトウェアオーバヘッドが課題となり，十分な性能が得られない危惧がある．そこで我々は，10Gbit/sec クラスの読み書き性能を持つ高速なフラッシュメモリを利用したストレージクラスタに適した，DISC システム SSS を設計・実装することを目指している．本稿では，既存の DISC システムの問題点を考察した上で，我々がプロトタイプ設計している SSS フレームワークのアーキテクチャを説明する．</div> </blockquote>



        
