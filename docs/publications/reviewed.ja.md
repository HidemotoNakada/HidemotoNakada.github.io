---
layout: default
---
# 査読あり (日本語) 

- **大規模オープン AI インフラストラクチャ ABCI**  <span onmouseover="document.getElementById('jses2023').style.display = 'block'"  onmouseout="document.getElementById('jses2023').style.display = 'none'">[abst]</span>   
中田 秀基
, *Journal of Japan Solar Energy Socety, Vol.49. No.4*   , pp. 49-54  , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jses2023"> 本稿では，産業技術総合研究所(以下，産総研)が保有，運用している，どなたでも使用できる大規模 AI 向けクラウドシステム ABCI(AI Bridging Cloud Infrastructure: AI 橋渡しクラウド)について紹介する.</div> </blockquote>



- **仮想マシンに対して透過的なClient Mobile IPv6 トンネリング機構**  <span onmouseover="document.getElementById('ieice12hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ieice12hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田 秀基, 伊藤智, 関口 智嗣
, *電子情報通信学会論文誌　Ｂ　通信*   , pp. 1239-1252  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice12hirofuchi"> 我々は，データセンタの運用柔軟性を向上させるため，仮想マシン（VM）の広域ライブマイグレーションに注目している．例えば，電力需要が逼迫した際に一部の仮想マシンを一時的に遠隔拠点に待避してサービスを継続できる．このときゲストOS がIP アドレスを維持したまま透過的に通信を継続できる必要があり，我々はMobile IPv6（MIPv6）技術に着目してきた．しかし，MIPv6 は強力なトンネリング機構を備えるものの，既存のMIPv6 技術をそのままマイグレーションに用いることは難しい．ゲストOS を改変することなく透過的にトンネリングを可能とし，VM 一つからでも柔軟にマイグレーションできる機構が必要である．そこで，我々はゲストOS にとって透過的なMIPv6 トンネリング機構（Kagemusha）を提案する．提案機構はホストOS 上で動作し，Client MIPv6 のシグナリングやトンネリングをゲストOS に対して透過的に行う．ゲストOS にMIPv6 に関するプログラムを導入する必要はない．さらに，既存のHome Agent（HA）や仮想マシンモニタを一切変更することなくそのまま利用できる．プロトタイプ実装を用いて評価実験を行った．その結果，提案機構はHA と正しく通信でき，そのトンネリングオーバーヘッドはわずかであることが確認できた．またQemu/KVM のライブマイグレーションと正しく連係動作し，訪問先ネットワークにおいてもゲストOS に対して透過的なネットワーク接続を提供できた．このときマイグレーションにともなうダウンタイムの増加は評価実験環境において1 秒程度であった．</div> </blockquote>



- **省電力化のためのマッチングに基づく仮想計算機パッキングアルゴリズム** [[Paper](dataDir/sacsis12takahashi.pdf)]  <span onmouseover="document.getElementById('sacsis12takahashi').style.display = 'block'"  onmouseout="document.getElementById('sacsis12takahashi').style.display = 'none'">[abst]</span>   
高橋 里司, 竹房 あつ子, 繁野 麻衣子, 中田 秀基, 工藤 知宏, 吉瀬 章子
, *SACSIS2012予稿集*   , pp. 333-340  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis12takahashi"> データセンターでの消費電力低減の手法として,低負荷の仮想計算機を高速にマイグレーションし て集約し,使用していない物理計算機を省消費電力モードで運用する方法がある.これを実現するに は,消費電力を抑えつつユーザ体験の劣化を防ぐ,負荷が変動する VM 群を現実的な時間で再配置す る,再配置時のマイグレーションによる通信衝突を考慮する,という課題がある.本研究では,ユー ザ体験を劣化させることなく省電力化を図る仮想計算機パッキング問題に対するマッチングベースア ルゴリズムを提案,評価する.提案手法では,再配置時に 1 つの計算機が送受信する VM 数を制限し, VM と計算機の組み合わせをグラフのマッチングで表すことで,多項式時間で適切な再配置プランニ ングを可能にする.評価では,提案手法を 0-1 整数計画問題として定式化して最適化ソルバを用いる 手法とグリーディな手法で,消費電力削減効果,計算時間,ユーザ体験の劣化について比較する.実 験から,1) パッキングをしない場合より 18%から 50%の消費電力が削減できる,2) マッチングベー スアルゴリズムにより,現実的な計算時間で適切な再配置を行うことができる,3) ユーザ体験は消費 電力の削減効果に反比例する傾向があるが,再配置によりほぼ改善できることを示す.</div> </blockquote>



- **仮想マシンの広域ライブマイグレーションを実現するゲスト透過なMobile IPv6 トンネリング機構** [[Paper](dataDir/ic11hirofuchi.pdf)]  <span onmouseover="document.getElementById('ic11hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ic11hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *インターネットコンファレンス 2011 (IC2011) 論文集*   , pp. 101-110  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic11hirofuchi"> 我々は、データセンタの運用柔軟性を向上させるため、仮想マシン(VM)の広域ライブマイグレーションに注目 している。例えば、電力需要が逼迫した際に一部の仮想マシンを一時的に遠隔拠点に待避してサービスを継続でき る。このときゲスト OS が IP アドレスを維持したまま透過的に通信を継続できる必要があり、我々は Mobile IPv6 (MIPv6)技術に着目してきた。しかし、MIPv6 は強力なトンネリング機構を備えるものの、既存の MIPv6 技術を そのままマイグレーションに用いることは難しい。ゲスト OS を改変することなく透過的にトンネリングを可能と し、VM 一つからでも柔軟にマイグレーションできる機構が必要である。そこで、我々はゲスト OS にとって透過的 な MIPv6 トンネリング機構(Kagemusha)を提案する。提案機構はホスト OS 上で動作し、Client MIPv6 のシ グナリングやトンネリングをゲスト OS に対して透過的に行う。ゲスト OS に MIPv6 に関するプログラムを導入す る必要はない。さらに、既存の Home Agent(HA)や仮想マシンモニタを一切変更することなくそのまま利用でき る。プロトタイプ実装を用いて評価実験を行った。その結果、提案機構は HA と正しく通信でき、そのトンネリングオーバーヘッドはわずかであることが確認できた。また Qemu/KVM のライブマイグレーションと正しく連係動 作し、移動先ネットワークにおいてもゲスト OS に対して透過的なネットワーク接続を提供できた。このときマイグレーションにともなうダウンタイムの増加はわずか数百 ms にとどまることが確認できた。</div> </blockquote>



- **分散KVSに基づくMapReduce 処理系SSS** [[Paper](dataDir/ic11nakada.pdf)] [[Slides](dataDir/ic11nakada-slides.pdf)]  <span onmouseover="document.getElementById('ic11nakada').style.display = 'block'"  onmouseout="document.getElementById('ic11nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 小川宏高, 工藤知宏
, *インターネットコンファレンス 2011 (IC2011) 論文集*   , pp. 21−29  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic11nakada"> 大量ログ解析のための技術として提案されたMapReduce は、新しい並列プログラミング手法として、より広範なアプリケーションへの応用が期待されているが、そのためには、MapとReduceを自由に組み合わせたワークフローの実行が必須となる。しかし、広く利用されているMapReduce処理系Hadoopは、ファイルシステムをベースとし、MapとReduceの間の通信を特別扱いにする構成を取っているため、MapとReduceが1対1に対応する構造しか記述することができない。このためワークフローの実行が非効率となる。われわれは分散KVSをベースに構成したMapReduce 処理系SSSを提案する。SSSではMapとReduceは、いずれも分散KVSからデータを読み込み、分散KVSに書き込む。このためMapとReduceを自由に組み合わせたワークフローを構成し、効率的に実行することが可能になる。本稿では、SSSの実装を詳述するとともに、合成ベンチマークプログラムおよび、K-meansによるHadoopとの比較評価を示す。評価の結果、SSSはHadoopよりも殆どの場合において高速であることが確認できた。</div> </blockquote>



- **マルチドメインクラウド資源管理フレームワーク**  <span onmouseover="document.getElementById('ieice11takefusa').style.display = 'block'"  onmouseout="document.getElementById('ieice11takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 高野了成, 柳田誠也, 大久保克彦, 工藤知宏, 田中良夫
, *電子情報通信学会論文誌 vol.J94-B No.10*   , pp. 1332-1340  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice11takefusa"> マルチドメインクラウドの資源管理フレームワークとして，資源管理システム，アプリケーション実行管理システム，分散モニタリングシステムからなるGridARSを開発している．本研究では，既存システムを拡張し，相互運用性，機能性の高いGridARSシステムを開発し，大規模環境でその有用性を評価した．また，GLIF2010およびSC10において実証実験を行い，GridARSを用いてマルチドメインクラウド上に自動的にユーザの要求を満たす仮想インフラを構築し，そのモニタリングを行うことに成功した．</div> </blockquote>



- **複数拠点にまたがるe-Science アプリケーション環境構築を目的としたソフトウェア導入・管理機構**  <span onmouseover="document.getElementById('ieice10hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ieice10hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 横井威, 江原忠士, 谷村勇輔, 小川宏高, 中田秀基, 工藤知宏, 田中良夫, 伊藤智, 関口智嗣
, *電子情報通信学会和文論文誌, Vol.J93-D, No.10*   , pp. 2197-2208   , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice10hirofuchi"> グリッド技術が発展するとともに，複数拠点の計算機資源を用いた科学技術計算が一般的になりつつある．しかし，異なる組織に属する拠点に対してグリッドミドルウェアや科学技術計算プログラムを導入することは容易ではなく，セットアップや管理に多くの労力を割かざるを得ない現状がある．そこで本論文では，複数拠点にまたがる計算環境を迅速に構築し，統一的に管理する機構を新たに提案する．複数拠点の計算資源をもとに仮想計算機からなるクラスタを構築し，その内部を既存のクラスタ管理技術を利用して透過的に管理する．すべての仮想計算機はVLANやEthernet VPNによって作り出した拠点横断的な管理用内部ネットワークに接続されており，既存のクラスタ管理システムによってソフトウェア導入やノード管理を統一的に行うことができる．パッケージキャッシュ機構を組み合わせることにより，ネットワーク遅延や帯域の制限が存在するWAN環境においても，安定したソフトウェア導入と運用が可能になる．評価実験や実証実験を通して，複数の遠隔拠点に対してソフトウェアを迅速に一斉導入し，既存のクラスタ管理の枠組みで運用可能であることを確認した．</div> </blockquote>



- **性能を保証する分散実行環境のためのオンラインコアロケーション手法**  <span onmouseover="document.getElementById('acs31takefusa').style.display = 'block'"  onmouseout="document.getElementById('acs31takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *情報処理学会論文誌コンピューティングシステム vol.3 no.3*   , pp. 126-137  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs31takefusa"> 利用者の要求する計算機性能やネットワーク帯域を保証した分散実行環境を構築して提供する場合，利用者や資源管理者の資源の割当て方針を反映させた計算機とネットワークのコアロケーションが重要な課題となる．本稿では，分散する資源が事前予約で複数の組織から提供されることを前提とし，計算機とネットワークを同時に確保するためのオンラインコアロケーション手法を提案する．提案手法では，資源のコアロケーションを整数計画問題にモデル化することにより，ユーザや資源管理者の資源の割当て方針を反映することができる．シミュレーションによる実験により，提案手法の機能性，実用性に関する評価を行う．評価から，提案手法により計算機とネットワークのコアロケーションが可能であり，資源管理者の観点で資源割当て方針が反映できること，オンライン処理として実用的であることを示す．</div> </blockquote>



- **性能を保証する分散実行環境のためのオンラインコアロケーション手法**  <span onmouseover="document.getElementById('comsys09-takefusa').style.display = 'block'"  onmouseout="document.getElementById('comsys09-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *第21回コンピュータシステム・シンポジウム(ComSys2009)*   , pp. 83-92  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys09-takefusa"> 利用者の要求する計算機性能やネットワーク帯域を保証した分散実行環境を構築して提供する場合，それらの資源の同時割り当て（コアロケーション）が重要な課題となる．本稿では，分散する資源が事前予約で複数の組織から提供されることを前提として，オンラインコアロケーション手法を提案する．提案手法では，我々の開発する資源管理フレームワークから利用可能な資源情報を取得し，最適化問題にモデル化したコアロケーションアルゴリズムを用いて複数の予約プランを作成する．また，提案手法では，ユーザや資源管理者の資源の割り当て方針を反映することができる．シミュレーションによる実験を行い，提案するオンラインコアロケーション手法の機能性，実用性に関する評価を行う．機能性の評価では，提案手法の予約成功率の高さと，資源管理者の観点で資源割り当て方針が反映できることを示す．実用性の評価では，最適化問題の求解時間を制約条件とソルバの違いにより比較するとともに，実用化に向けて議論する．</div> </blockquote>



- **ネットワーク帯域予約とOS仮想化機構を用いた分散アプリケーション実行環境**  <span onmouseover="document.getElementById('comsys09-nakada').style.display = 'block'"  onmouseout="document.getElementById('comsys09-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高野了成, 竹房あつ子, 工藤知宏
, *第21回コンピュータシステム・シンポジウム(ComSys2009)*   , pp. 51-58  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys09-nakada"> 複数のサイトにまたがって計算資源，ネットワーク資源を動的に確保し，アプリケーションを実行することは以下の理由により困難である．1) ネットワークの非対称性、2) サイト間の非均質性，3) 必要情報の実行時確定，4) アプリケーションのマルチホームネットワーク非対応．このため，現在のグリッド環境では既存のアプリケーションをそのまま実行することは難しい．我々は，予約ベースで計算資源とネットワーク資源を確保し，その上にごく一般的なクラスタ内の環境と類似した環境を構築するグリッドミドルウェアの構築を行っている．このグリッドミドルウェアを用いると，既存のアプリケーションを修正すること無く実行することが可能となる．本稿ではこのグリッドミドルウェアのアプリケーション実行フレームワークの設計とプロトタイプ実装について述べる．プロトタイプにより，フレームワークの設計の妥当性を確認した．また，OS仮想化を用いることで高速に実行環境をセットアップできることを確認した．</div> </blockquote>



- **瞬間的な実行ホスト切り替えを可能とする仮想マシンの高速ライブマイグレーション機構**    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *日本ソフトウェア科学会研究会資料シリーズNo.62, 日本ソフトウェア科学会, インターネットカンファレンス2009*   , pp. 57-66  , 2009 



- **仮想計算機遠隔ライブマイグレーションのための 透過的なストレージ再配置機構**  <span onmouseover="document.getElementById('acs26hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('acs26hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 小川宏高, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会論文誌：コンピューティングシステム, Vol.2, No.SIG2 (ACS26)*   , pp. 152-165  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs26hirofuchi"> 計算機センタやデータセンタの計算機資源の運用効率を高めるために,仮想計算機とそのライブマイグレーション技術が注目されている。仮想計算機を遠隔拠点に対して動的に再配置できれば,資源運用の柔軟性向上や省電力化に寄与すると考えられる。しかし,LAN環境を想定した既存の仮想計算機技術ではストレージアクセス手法に問題をかかえており,WAN環境においてライブマイグレーションを効率的に行うことが困難である。そこで本研究では,周辺機器を含めた仮想計算機の実行環境全体の移動を可能にするために,仮想計算機ストレージの透過的な再配置機構を提案する。提案機構はブロックレベルのストレージI/Oプロトコルに対するターゲットサーバとして振る舞い,ライブマイグレーションの際には仮想計算機の動作に支障を与えることなく透過的に仮想ディスクの拠点間再配置を完了する。その評価として,提案手法の基本的なI/O特性を明らかにしたうえで,実アプリケーションを想定した実験を行った。提案手法においては,オンデマンドなブロック再配置機構のみでは未再配置ブロックの読み込みが遅く,大量のファイルを対象としてランダムに同期I/Oを行うメールサーバ型アプリケーションにおいてはボトルネックとなりうる。しかし,同時並行的に動作する先読み的なブロック再配置機構により,可用WAN帯域を利用して効率的にデータが再配置され性能低下が緩和されることが分かった。</div> </blockquote>



- **WSRFに基づく情報サービスのXACMLによるアクセス制御**  <span onmouseover="document.getElementById('acs23-takefusa').style.display = 'block'"  onmouseout="document.getElementById('acs23-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.1 No.2 (ACS23)*   , pp. 180-192  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs23-takefusa"> グリッドでは資源やジョブに関する情報の提供は重要な機能のひとつであり，クラスタ監視ツールのGangliaやGlobus Toolkit 4のMDS4などの情報サービスが実現されている．しかしながら，複数の仮想組織に属するユーザが資源を共有する場合，全情報をすべてのユーザに開示することは好ましくない．本研究では，認可モデルとポリシ記述言語の標準として提案されているXACMLを用い，サイト毎に情報開示ポリシを定義して，各ユーザからの細粒度の情報アクセス制御を可能にする，WSRFに基づく情報サービスシステムを提案する．本研究で開発したプロトタイプでの予備実験から，(1)情報収集に関するオーバヘッドはWSRF/GSIによるもので占められ，認可決定の時間は無視できる，(2)複数サイトから情報収集する場合も，手続きを並行して行うとその所要時間は許容できる，(3)XACMLのポリシ数が多い場合も，判定に要する時間は全体の処理時間に対して十分小さいことが確認できた．</div> </blockquote>



- **多様な資源を事前予約で同時確保するためのグリッドコアロケーションシステムフレームワークGridARS**  <span onmouseover="document.getElementById('acs20takefusa').style.display = 'block'"  onmouseout="document.getElementById('acs20takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.48, No. SIG18 (ACS20)*   , pp. 32-43  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs20takefusa"> グリッドで並列高性能計算の性能を向上させるには，コアロケーションシステムが既存資源スケジューラと連携して多様な資源を事前同時予約できることが重要 である．本稿ではWSRFに基づく事前予約インタフェースを提供するコアロケーションフレームワークGridARSを提案する．GridARSでは分散ト ランザクションによる同時予約手続きを行うため，汎用的な2相コミット事前予約プロトコルを設計し，実装した．GridARSの有効性を示すため，複数資 源マネージャに対する同時予約手続きの基礎性能を評価した．また，応用事例として複数資源スケジューラで管理される日米間にまたがるネットワーク，計算資 源を同時確保する実証実験について報告する．これにより，1) GridARSの2相コミットによる予約手続きが有効であり，2) GridARSのコアロケーションシステムが，多様な資源のスケジューラと連携し，安定して分散資源を同時確保できることを示す．</div> </blockquote>



- **WSRFに基づく情報サービスのXACMLによるアクセス制御**  <span onmouseover="document.getElementById('comsys07takefusa').style.display = 'block'"  onmouseout="document.getElementById('comsys07takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 工藤知宏, 田中良夫, 関口智嗣
, *コンピュータシステム・シンポジウム論文集*   , pp. 199-208  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys07takefusa"> グリッドでは資源やジョブに関する情報の提供は重要な機能のひとつであり、クラスタ監視ツールの Ganglia や Globus Toolkit 4 の MDS4 などの情報サービスが実現されている。しかしながら、複数の仮想組織に属するユーザが資源を共有する場合、全情報をすべてのユーザに開示することは好ましくない。本研究では、認可モデルとポリシ記述言語の標準として提案されている XACML を用い、サイト毎に情報開示ポリシを定義して、各ユーザからの細粒度の情報アクセス制御を可能にする、WSRF に基づく情報サービスシステムを提案する。本研究で開発したプロトタイプでの予備実験から、(1) 情報収集に関するオーバヘッドは WSRF/GSI によるもので占められ、認可決定の時間は無視できる、(2) 複数サイトから情報収集する場合も、手続きを並行して行うとその所要時間は許容できる、(3) XACML のポリシ数が多い場合も、判定に要する時間は全体の処理時間に対して十分小さいことが確認できた。</div> </blockquote>



- **仮想クラスタ管理システムの設計と実装**  <span onmouseover="document.getElementById('acs19nakada').style.display = 'block'"  onmouseout="document.getElementById('acs19nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.48 SIG13 (ACS19)*   , pp. 13-24  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs19nakada"> 計算機資源の効率的な運用の方法として仮想化が注目されており，仮想的なクラスタを管理するシステムが提案されている．しかしこれらのシステムは，クラスタを単なるノードの集合と考えており，クラスタとしての統合的な運用に必要となるさまざまな機能を実現していない．また，計算機資源を仮想化しているが，ストレージ，ネットワークを含めた仮想化環境を提供していない．われわれは，これらの問題点を解決した仮想クラスタ管理システムを提案する．本システムは，クラスタ構築システムRocksを用いることで，クラスタ運用に必要なソフトウェアを整合して配置する．また，ストレージ資源をIP SAN技術のひとつであるiSCSIを用いて仮想化，ネットワーク資源をタグ付きVLANを用いて仮想化することで，管理コストが低く，安全な仮想クラスタ環境を実現する．</div> </blockquote>



- **グローバルスケジューリングのための計算資源予約管理機構**  <span onmouseover="document.getElementById('acs18nakada').style.display = 'block'"  onmouseout="document.getElementById('acs18nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.48 No.SIG8 (ACS18)*   , pp. 71-81  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs18nakada"> グリッド上で複数の資源の同時確保を実現する方法のひとつとして事前予約を行う方法がある．これを実現するためには、同時確保の実現に求められる協調プロトコルを実装した事前予約機構を，グリッド上の各資源が持つことが必要となる。われわれは，同時確保のプロトコルとして分散トランザクションで一般に用いられる2相コミットプロトコルを採用し，これを実装した計算資源予約管理機構 PluS を開発した。PluSは、既存のローカルキューイングシステムであるTORQUEもしくはGrid Engine と協調動作し、事前予約機能を提供する．既存ローカルキューイングシステムに事前予約機能を追加する手法としては，1）ローカルキューイングシステムのスケジューリングモジュールを完全に置き換える方法，2）予約をキューとして実現し，外部からキューを操作することで予約を実現する方法，の2つがある．われわれは，この両者に関して予約機能を設計，実装し評価した．その結果，前者はオーバヘッドが少なくポリシ実現の自由度が高いこと，後者は既存スケジューリングモジュール機能の再実装が必要ないため実装コストが小さいことがわかった．</div> </blockquote>



- **仮想クラスタ管理システムの設計と実装** [[Paper](dataDir/sacsis07nakada.pdf)] [[Slides](dataDir/sacsis07nakada_slide.pdf)]  <span onmouseover="document.getElementById('sacsis07nakada').style.display = 'block'"  onmouseout="document.getElementById('sacsis07nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *先進的基盤システムシンポジウム SACSIS2007論文集*   , pp. 79-86  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis07nakada"> 計算機資源の効率的な運用の方法として仮想化が注目されており，仮想的なクラスタを管理するシステムが提案されている．しかしこれらのシステムは，クラスタを単なるノードの集合と考えており，クラスタとしての統合的な運用に必要となるさまざまな機能を実現していない．また，計算機資源を仮想化しているが，ストレージ，ネットワークを含めた仮想化環境を提供していない．われわれは，これらの問題点を解決した仮想クラスタ管理システムを提案する．本システムは，クラスタ構築システムRocksを用いることで，クラスタ運用に必要なソフトウェアを整合して配置する．また，ストレージ資源をIP SAN技術のひとつであるiSCSIを用いて仮想化，ネットワーク資源をタグ付きVLANを用いて仮想化することで，管理コストが低く，安全な仮想クラスタ環境を実現する．</div> </blockquote>



- **グローバルスケジューリングのための計算資源予約管理機構** [[Paper](dataDir/hpcs07nakada.pdf)] [[Slides](dataDir/hpcs07nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpcs07nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcs07nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *HPCS 2007 2007年ハイパフォーマンスコンピューティングと計算科学シンポジウム論文集*   , pp. 127-134  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs07nakada"> グリッド上で複数の資源の同時確保を実現する方法のひとつとして事前予約を行う方法がある．これを実現するためには、同時確保の実現に求められる協調プロトコルを実装した事前予約機構を，グリッド上の各資源が持つことが必要となる。われわれは，同時確保のプロトコルとして分散トランザクションで一般に用いられる2相コミットプロトコルを採用し，これを実装した計算資源予約管理機構 PluS を開発した。PluSは、既存のローカルキューイングシステムであるTORQUEもしくはGrid Engine と協調動作し、事前予約機能を提供する．既存ローカルキューイングシステムに事前予約機能を追加する手法としては，1）ローカルキューイングシステムのスケジューリングモジュールを完全に置き換える方法，2）予約をキューとして実現し，外部からキューを操作することで予約を実現する方法，の2つがある．われわれは，この両者に関して予約機能を設計，実装し評価した．その結果，前者はオーバヘッドが少なくポリシ実現の自由度が高いこと，後者は既存スケジューリングモジュール機能の再実装が必要ないため実装コストが小さいことがわかった．</div> </blockquote>



- **異種の複数スケジューラで管理される資源を事前同時予約するグリッド高性能計算の実行環境** [[Paper](dataDir/hpcs07takefusa.pdf)] [[Slides](dataDir/hpcs07takefusa_slide.pdf)]  <span onmouseover="document.getElementById('hpcs07takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpcs07takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 武宮博, 松田元彦, 工藤知宏, 田中良夫, 関口智嗣
, *HPCS 2007 2007年ハイパフォーマンスコンピューティングと計算科学シンポジウム論文集*   , pp. 135-142  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs07takefusa"> グリッドで並列高性能計算を行うには，資源のコアロケーションシステムが異種の複数スケジューラで管理される資源を安全に事前同時予約できることが重要である．本稿ではWSRFに基づくインタフェースを提供するコアロケーションシステムGridarsを改良し， 2相コミットでの事前同時予約手続きを実現した．また，Gridarsの有効性を示すために，計算資源と通信資源のコアロケーションを必要とする実アプリケーションプログラムのためのポータルを Gridarsを用いて構築し，複数の異種スケジューラで管理される日米間に跨るネットワーク，計算資源を用いて実験を行った．この結果，1)Gridarsを用いることで，異種スケジューラで管理される資源群をトランザクションにより安全に確保できること，2)Gridarsを用いたポータルにより，容易にグリッド上での高性能計算環境をユーザに提供できること，を確認した．</div> </blockquote>



- **動的に計算量が変化する大規模長時間実行Gridアプリケーションの実現**  <span onmouseover="document.getElementById('acs16takemiya').style.display = 'block'"  onmouseout="document.getElementById('acs16takemiya').style.display = 'none'">[abst]</span>   
武宮 博, 田中 良夫, 中田 秀基, 関口 智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.47 No.SIG18  (ACS16)*   , pp. 31-43  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs16takemiya"> (1)数千プロセッサ規模の大規模な計算機資源を要する，(2)数週間から数カ月に及ぶ長期実行を必要とする，(3)計算の進展に応じて動的に計算量が変化する，という特徴を持つシミュレーションプログラムをGridRPCとMPIを組み合わせるプログラミング手法に基づきGrid化し，分散配置された並列計算機から構成されるGrid環境上で実行するための手法を提案する．本手法を用いることにより，上記3点の特徴を持つGridアプリケーションを構築するために必要な，プログラムの柔軟性，頑健性，効率性を実現することが可能となる．本手法の有効性を検証するために，本手法に基づきGrid化したプログラムを環太平洋Grid環境上で長期間継続実行させる実験を試みた．その結果，障害発生や計算量の変化に対応して実行対象計算機やその利用規模を変更しながら最長20日以上にわたり大規模Gridシミュレーションを継続実行することができた．</div> </blockquote>



- **ORE Grid：仮想計算機を用いたグリッド実行環境の高速な配置ツール**  <span onmouseover="document.getElementById('acs15takamiya').style.display = 'block'"  onmouseout="document.getElementById('acs15takamiya').style.display = 'none'">[abst]</span>   
高宮 安仁, 山形 育平, 青木 孝文, 中田 秀基, 松岡 聡
, *情報処理学会論文誌: コンピューティングシステム Vol.47 No.SIG12 (ACS15)*   , pp. 229-239  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs15takamiya"> グリッド上で実行されるジョブの多様化にともない，OS やソフトウェア，ライブラリなどジョブが要求する実行環境も多様化しつつある．しかし，グリッドリソースであるクラスタごとの管理ポリシによる制限により，ジョブの要求を満たす実行環境を得ることは難しい．既存研究では実行環境の仮想化による実行環境の提供をある程度達成しているものの，セットアップできる環境の種類が制限されていることや，セットアップが自動的でないといった問題や，システムの詳細に関する知識を必要とするといった問題があった．そこで我々は，VM 技術を用いて投入されるジョブごとに専用の仮想実行環境を動的に提供するシステムとしてORE（Open Resource Environment）グリッドを提案する．加えて，スクリプトやDAG などツール独自の方法で実行環境の構築手順を記述する代わりに，GUI を用いて実行環境に必要な要素を指定することで容易に実行環境を構築できる．評価では16 台構成の実行環境をORE グリッドを用いてセットアップしジョブを実行させた．結果，実行環境の構築に要する時間は全体で151 秒と高速であり，一般的なグリッド上のジョブ実行時間（数時間～数日間以上）と比較すると十分許容範囲以内であることを確認した．</div> </blockquote>



- **GridRPCにおける複数ノードにまたがるTask Sequencing の実現**  <span onmouseover="document.getElementById('acs15tanimura').style.display = 'block'"  onmouseout="document.getElementById('acs15tanimura').style.display = 'none'">[abst]</span>   
谷村 勇輔, 中田 秀基, 田中 良夫, 関口 智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.47 No.SIG12  (ACS15)*   , pp. 207-211  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs15tanimura"> GridRPC において，依存関係を持つ2 つ以上のRPC，すなわち直前のRPC の出力が次のRPCの入力データとなるTask Sequencing ジョブを複数ノードにまたがって処理する場合に，クライアントを介さずにRPC の実行ノード間で直接データを転送する機能の設計と実装を行った．大域的な名前空間を提供するグローバルファイルシステムを利用することにより，クライアント・サーバモデルを基本とするGridRPC の特徴を損なわず，かつ既存のGridRPC システムの実装を大きく変えることなく実現した．また，連続するRPC の引数列を解析して中間データを自動判別し，中間データであればそれをグローバルファイルシステム上に作成する機能をTask Sequencing API ライブラリ内部に実装し，LAN 環境，日米間にまたがるグリッド環境における性能評価を行い，本機能が有効であることを明らかにした．</div> </blockquote>



- **大規模長時間実行Gridアプリケーションの実装と評価** [[Paper](dataDir/sacsis06takemiya.pdf)] [[Slides](dataDir/sacsis06takemiya_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06takemiya').style.display = 'block'"  onmouseout="document.getElementById('sacsis06takemiya').style.display = 'none'">[abst]</span>   
武宮 博, 田中 良夫, 中田 秀基, 関口 智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 351-358  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06takemiya"> 動的に計算量が変動するという特徴を持つ大規模シミュレーションプログラムをGridRPC とMPIを組み合わせることによりGrid 化し，長期間にわたってGrid 環境上で継続実行させることを試みた．実装に際して，(1) 大規模計算機を事前に一定期間予約し，対象を変更する，(2) 複数のユーザにより共有されている計算機から，その時点で利用可能なものを動的に利用していく，という二種類の現実的な実行シナリオを想定し，このシナリオを満足するためにアプリケーションに実装すべき機能を検討した．また，本手法に基づきGrid 化したプログラムを環太平洋Grid 環境上で半月から二ヶ月にわたり動作させることで，本手法により計算量の変動にあわせて動的に実行対象計算機を変更する柔軟性と，障害を検知・復旧する頑健性を実現できることを示す．</div> </blockquote>



- **仮想計算機を用いたグリッド上でのMPI実行環境** [[Paper](dataDir/sacsis06tatezono.pdf)] [[Slides](dataDir/sacsis06tatezono_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06tatezono').style.display = 'block'"  onmouseout="document.getElementById('sacsis06tatezono').style.display = 'none'">[abst]</span>   
立薗 真樹, 中田 秀基, 松岡 聡
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 525-532  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06tatezono"> 近年、大規模なMPI アプリケーションの実行をグリッド上で行うことが求められている。本稿では仮想計算機を用いたグリッド環境上でのMPI 実行環境を提案する。仮想計算機Xen 上で、MPI実行環境をもつゲストOS ごとマイグレーションすることにより、ファイルI/O や送信過程のメッセージを含めた計算機全ての状態が変更されない、MPI プロセスに透過的なマイグレーションを実現し、実行中のMPI のマイグレーションが正常に行われたことを確認した。さらにVPN を用いたネットワークの仮想化によって、マイグレーション先を異なるネットワークへ拡張し、また動的にマイグレーションを行うシステムの実装によりグリッド環境への対応を実現した。構築した環境における実行性能を評価では、仮想化によって生じたネットワークのオーバーヘッドにより、通信頻度によって大きく性能差が出る結果となった。</div> </blockquote>



- **ORE Grid: 仮想計算機を用いたグリッド実行環境の高速な配置ツール** [[Paper](dataDir/sacsis06takamiya.pdf)] [[Slides](dataDir/sacsis06takamiya_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06takamiya').style.display = 'block'"  onmouseout="document.getElementById('sacsis06takamiya').style.display = 'none'">[abst]</span>   
高宮 安仁, 山形 育平, 青木 孝文, 中田 秀基, 松岡 聡
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 541-548  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06takamiya"> グリッド上で実行されるジョブの多様化に伴い，OS やソフトウェア，ライブラリなどジョブが要求する実行環境も多様化しつつある．しかし，グリッドリソースであるクラスタごとの管理ポリシーによる制限により，ジョブの要求を満たす実行環境を得ることは難しい．既存研究では実行環境の仮想化による実行環境の提供をある程度達成しているものの，セットアップできる環境の種類が制限されていることや，セットアップが自動的で無いといった問題や，システムの詳細に関する知識を必要とするといった問題があった．そこで我々は，VM 技術を用いて投入されるジョブごとに専用の仮想実行環境を動的に提供するシステムとしてORE (Open Resource Environment) グリッドを提案する．加えて，スクリプトやDAG などツール独自の方法で実行環境の構築手順を記述する代わりに，GUI を用いて実行環境に必要な要素を指定することで容易に実行環境を構築できる．評価では16 台構成の実行環境をORE グリッドを用いてセットアップしジョブを実行させた．結果，実行環境の構築に要する時間は全体で151 秒と高速であり，一般的なグリッド上のジョブ実行時間(数時間～数日間以上）と比較すると十分許容範囲以内であることを確認した．</div> </blockquote>



- **GridRPCにおける複数ノードにまたがるTask Sequencingの実現** [[Paper](dataDir/sacsis06tanimura.pdf)] [[Slides](dataDir/sacsis06tanimura_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06tanimura').style.display = 'block'"  onmouseout="document.getElementById('sacsis06tanimura').style.display = 'none'">[abst]</span>   
谷村 勇輔, 中田 秀基, 田中 良夫, 関口 智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 75-84  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06tanimura"> GridRPC において，依存関係をもつ2 つ以上のRPC，すなわち直前のRPC の出力が次のRPCの入力データとなるTask Sequencing ジョブを複数ノードにまたがって処理する場合に，クライアントを介さずにRPC の実行ノード間で直接データを転送する機能の設計と実装を行った．大域的な名前空間を提供するグローバルファイルシステムを利用することにより，クライアント・サーバモデルを基本とするGridRPC の特徴を損なわず，かつ既存のGridRPC システムの実装を大きく変えることなく実現した．また，連続するRPC の引数列を解析して中間データを自動判別し，中間データであればそれをグローバルファイルシステム上に作成する機能をTask Sequencing API ライブラリ内部に実装し，LAN 環境，日米間にまたがるグリッド環境における性能評価を行い，本機能が有効であることを明らかにした．</div> </blockquote>



- **計算資源とネットワーク資源を同時確保する予約ベースグリッドスケジューリングシステム** [[Paper](dataDir/sacsis06takefusa.pdf)] [[Slides](dataDir/sacsis06takefusa_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06takefusa').style.display = 'block'"  onmouseout="document.getElementById('sacsis06takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 93-100  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06takefusa"> グリッドで異なる組織に管理される分散した計算資源を用いた高性能大規模計算を実行するには，分散した計算資源とその間の高品質なネットワークを同時に確保することが重要である．本研究では，事前予約により計算資源と高品質ネットワーク資源を同時に確保し，その上でユーザジョブの自動実行を可能にするグリッドスケジューリングシステムを提案・開発した．提案システムはグリッド資源スケジューラ(GRS) と計算資源マネージャ(CRM) からなり，GRS が複数CRM とネットワークキャリアの提供するネットワーク資源管理システムと連携して計算・ネットワーク資源のコアロケーションを実現する．</div> </blockquote>



- **動的なノード群構成機構を備えた階層型グリッド環境 Jojo2** [[Paper](dataDir/sacsis06aoki.pdf)] [[Slides](dataDir/sacsis06aoki_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06aoki').style.display = 'block'"  onmouseout="document.getElementById('sacsis06aoki').style.display = 'none'">[abst]</span>   
青木 仁志, 中田 秀基, 田中 康司, 松岡 聡
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 101-108  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06aoki"> グリッドの階層構造に適合したプログラミングモデルの一つとして階層型マスタ・ワーカ方式がある。しかし既存の階層型マスタ・ワーカ方式を実現するミドルウェアは、動的なノード群構成や動的なノードの参加・脱退といった機構が欠如しているため管理コストが大きい。我々は動的なノード群構成機構を備えた階層型グリッドプログラミング環境Jojo2 を提案する。Jojo2 はグリッドの階層構造に合致した動的なノード構成を行い、自律的なノードの発見、動的なノードの参加・脱退を行うことで大規模グリッド環境においても管理コストを軽減することができる。さらに動的なノードの参加・脱退をハンドルするプログラミングAPI を提供することで、動的構成に対応したプログラムを容易に記述できる。また予備的性能評価を行い、その結果、ノードの参加・脱退のAPI の有効性と、ノードの参加・脱退のコストが小さいことを確認した。</div> </blockquote>



- **レプリカ管理システムを利用したデータインテンシブアプリケーション向けスケジューリングシステム** [[Paper](dataDir/hpcs06machida.pdf)] [[Slides](dataDir/hpcs06machida_slide.pdf)]  <span onmouseover="document.getElementById('hpcs06machida').style.display = 'block'"  onmouseout="document.getElementById('hpcs06machida').style.display = 'none'">[abst]</span>   
町田悠哉, 滝澤真一朗, 中田秀基, 松岡　聡
, *HPCS 2006*    , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs06machida"> グリッド環境において既存のスケジューリングシステムはデータ入出力を共有ファイルシステムや単純なステージング機構を利用して行っている。しかしこれらの手法ではデータ保持ノードはアクセス集中によりパフォーマンスが低下、そして最悪の場合にはハングアップしてしまう。またユーザが同一のデータセットを利用する多数のタスクからなるジョブを実行した場合、スケジューリング後に毎回同じデータをステージングするのは非効率である。そこで本研究では複数ノードへO(1) の転送時間でデータを複製できるスケーラブルなレプリカ管理システムをステージング機構として利用し、レプリカを再利用するような効率的なスケジューリングを可能とするシステムを提案する。プロトタイプシステム上でサンプルアプリケーションを実行したところ従来の共有ファイルシステムやステージング機構を利用したものより高い性能が確認できた。</div> </blockquote>



- **ファイルへのアクセスの自動分散を行うグリッド用分散ファイルシステム** [[Paper](dataDir/comsys05sato.pdf)]  <span onmouseover="document.getElementById('comsys05sato').style.display = 'block'"  onmouseout="document.getElementById('comsys05sato').style.display = 'none'">[abst]</span>   
佐藤仁, 松岡聡, 中田秀基
, *コンピュータシステム・シンポジウム論文集*   , pp. 91-98  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys05sato"> クラスタやグリッドなどの並列計算環境では，アプリケーションによっては，ファイルを保持するノードへのアクセス集中が発生し，実行性能の低下が問題となる  既存の分散ファイルシステム上でこのようなアクセス集中を避けるためには，ユーザがアプリケーションの作成時や実行時に明示的にファイルアクセスの分散を行うことが必要となる  しかし，環境が不均質であるグリッドではこのような対応は困難であり負担が大きい  我々は，ファイルシステム側でアクセスの集中を検知し，ファイル複製を積極的に利用して，ファイルへのアクセスを分散する手法を提案し，プロトタイプとしてこの提案手法をグリッドファイルシステムである  Gfarm上に実装した．実験として，作為的にファイルへのアクセス集中が発生する状況を作り出し，プロトタイプによって自動的にアクセス集中を検知し，ファイル複製を作成することで，ファイルへのアクセスが分散され，ファイル複製を作成しない場合と比較して，2.33倍のファイルアクセスの性能が向上することを確認した．</div> </blockquote>



- **非対称ネットワークを隠蔽する高速通信インフラストラクチャの設計と実装** [[Paper](dataDir/ic2005hamano.pdf)] [[Slides](dataDir/ic2005hamano_slide.pdf)]  <span onmouseover="document.getElementById('ic2005hamano').style.display = 'block'"  onmouseout="document.getElementById('ic2005hamano').style.display = 'none'">[abst]</span>   
濱野智行, 中田秀基, 松岡聡
, *インターネットコンファレンス2005論文集*   , pp. 36-42  , 2005 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic2005hamano"> グリッド環境で問題となっている非対称ネットワークを扱う研究は数多く存在するが、十分な接続性とグリッド環境に適したセキュリティ・サイトポリ シ非依存性・高通信性能を達成するものは存在しない。そこで、非対称ネットワークを隠蔽し、それを意識せず通信可能であり、グリッド環境に適した通信イン フラストラクチャを提案する。また、そのプロトタイプJRouter を実装し、それを用いて実際のグリッド環境でその性能評価を行った。その結果、接続性・セキュリティ・サイトポリシ非依存性において十分な性能であるが、 通信性能において十分とは言えないという結論に至ったため、更なる性能向上のための施策について議論を行う。</div> </blockquote>



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



- **Ninf-G2: 大規模Grid環境での利用に即した高機能，高性能GridRPCシステムの実装と評価**  <span onmouseover="document.getElementById('acs7takemiya').style.display = 'block'"  onmouseout="document.getElementById('acs7takemiya').style.display = 'none'">[abst]</span>   
武宮博, 田中良夫, 中田秀基, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol. 45, No. SIG 11(ACS 7)*   , pp. 144-159  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs7takemiya"> Grid プログラミングモデルの1 つであるGridRPCの参照実装としてNinf-G2の開発を行い，性能を評価した．広域に分散した複数台のクラスタから構成される大規模Grid 環境上でアプリケーションを効率良く実行することを目的とするNinf-G2は，関数ハンドル同時生成機能やリモートオブジェクトを実装することで，遠隔手続き呼び出しにともなう起動コストや通信コストの低減を図るとともに，ハートビート機能や関数ハンドル作成タイムアウト機能，サーバ属性の個別設定機能を提供することで，非均質，不安定で動的に変化するGrid環境への対応を図っている．典型的なタスク並列アプリケーションである気象シミュレーションプログラムを対象に，6台のクラスタから構成されるGridテストベッド上でNinf-G2の性能評価を行った．その結果，個々のタスクの実行時間が十数秒から数十秒程度の比較的粒度の小さいシミュレーションであっても，200台以上のプロセッサを用いて効率的に実行可能であることが分かった．</div> </blockquote>



- **耐故障性を重視したRPCシステムNinf-Cの設計と実装**  <span onmouseover="document.getElementById('acs7nakada').style.display = 'block'"  onmouseout="document.getElementById('acs7nakada').style.display = 'none'">[abst]</span>   
中田秀基, 田中良夫, 松岡聡, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol. 45, No. SIG 11(ACS 7)*   , pp. 160-170  , 2004 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs7nakada"> 耐故障性を重視したRPCシステムNinf-Cの設計と実装に関して述べる。Ninf-Cは、全体として数日から数ヶ月を要する大規模なマスタワーカ型計算を安定して実行することを目的としたシステムで、ウィスコンシン大学で開発されたスケジューリングシステムCondorの提供する機能を利用することで、マスタを含むシステム全体に耐故障性を持たせている。Ninf-CのRPCは、Condorのファイルステージ機能を用いて実現される。直接ソケット通信を使用せずにファイル経由で通信を行うことで、マスタとワーカのチェックポイントをとることを可能とした。また、ファイルに残った通信記録を用いてマスタの状態を復元する。さらに、Condor-Gを利用することで、Globusによって構築されたグリッド環境下での運用も可能である。Ninf-C の有効性を確認するため、クラスタ環境で簡単なマスタワーカ型プログラムを長時間実行した。この際、マスタおよびワーカを実行しているマシンをシャットダウンするといった人為的な外乱をあたえたが、プログラムは19時間かけて問題なく実行を終了し、Ninf-Cの耐故障性が実証された。</div> </blockquote>



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



- **Gridポータル構築ツールキットNinf-Portal**  <span onmouseover="document.getElementById('hps5nakada').style.display = 'block'"  onmouseout="document.getElementById('hps5nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 齋藤 真幸, 鈴村 豊太郎, 田中 良夫, 松岡 聡, 関口 智嗣
, *情報処理学会論文誌 コンピューティングシステム Vol. 43, No. SIG 6(HPS 5)*   , pp. 172-183  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hps5nakada"> 広域に分散した各種資源を集合的に使用して大規模計算を行う計算機構Gridが注目を集めている。多様な管理主体に属する資源から構成されるGrid環境上のプログラムを多くのユーザに使用させるためには、ポータルと呼ばれる機構が必要である。このため、Gridへのポータルを構築するためのツールキットがいくつか提案されている。しかしこれらのツールキットを用いる場合でも、ポータル構築者がフロントエンドとなるポータルのユーザインターフェイス部、バックエンドとなる実際のGridプログラムの2つを記述しなければならず、ポータル構築者の負担が大きい。我々は、前者に対してXMLベースのユーザインターフェイス生成系を、後者に対してGrid RPCシステムであるNinf-Gを使用することでプログラマの負荷を軽減するポータル開発キットを提案する。さらに、提案したシステムを用いて、実用的なプログラムをポータル化し有効性を確認した。</div> </blockquote>



- **Gridポータル構築ツールキットNinf-Portal**  <span onmouseover="document.getElementById('jspp02nakada').style.display = 'block'"  onmouseout="document.getElementById('jspp02nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 齋藤 真幸, 鈴村 豊太郎, 田中 良夫, 松岡 聡, 関口 智嗣
, *JSPP2002論文集*   , pp. 209−216  , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp02nakada"> 広域に分散した各種資源を集合的に使用して大規模計算を行う計算機構 Gridが注目を集めている。多様な管理主体に属する資源から構成されるGrid環境上のプログラムを多くのユーザに使用させるためには、ポータルと呼ばれる機構が必要である。このため、Gridへのポータルを構築するためのツールキットがいくつか提案されている。しかしこれらのツールキットを用いる場合でも、ポータル構築者がフロントエンドとなるポータルのユーザインターフェイス部、バックエンドとなる実際のGridプログラムの2つを記述しなければならず、ポータル構築者の負担が大きい。われわれは、前者に対してXMLベースのユーザインターフェイス生成系を、後者に対してGrid RPCシステムであるNinf-Gを使用することでプログラマの負荷を軽減するポータル開発キットを提案する。さらに、提案したシステムを用いて、実用的なプログラムをポータル化し有効性を確認した。 As the Grid proliferates as the next-generation wide-area high-performance computing infrastructure, end-user Grid interfaces in the form of &quot;Grid Portals&quot; is becoming increasingly important, especially computational scientists and engineers. Although several Grid portal toolkits and proposals have been proposed, a Grid Portal creator must construct and deploy both the user interface and the application portions of the Grid Portal, resulting in considerable programming efforts. We aim to easen this burden by applying the state-of-the-art Web/XML interface generation technologies for the former, and the Ninf-G GridRPC system for easily &quot;Gridifying&quot; exisiting applications for the latter, and realizing their seamless integration. The resulting system which we call the &quot;Ninf Portal&quot; allowed concise description and easy deployment of a sample application on the Grid with very small programming efforts.</div> </blockquote>



- **XMLベースGridRPCシステムの構築と評価**  <span onmouseover="document.getElementById('spa02shirasuna').style.display = 'block'"  onmouseout="document.getElementById('spa02shirasuna').style.display = 'none'">[abst]</span>   
白砂 哲, 中田 秀基, 松岡 聡, 関口 智嗣
, *第5回プログラミングおよび応用のシステムに関するワークショップ SPA &#x27;02 オンライン論文集*    , 2002 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="spa02shirasuna"> GridRPC は科学技術計算に多く用いられるGrid 上のミドルウェアであるが，それぞれのGirdRPC システムが独自のプロトコルを利用しているため，インテオペラビリティが重要な課題となっている．Web サービスの分野では，SOAP やWSDL といったXML 基盤の標準仕様が用いられており，広く使用されることが期待されている．GridRPC においてもこれらの仕様を用いてインタオペラビリティを確保することが可能であると考えられるが，1) XML 基盤のこれらの仕様がGridRPC に適した記述力を有しているか， 2) コストが高いXML を用いて十分な性能を得ることができるか，などが明らかではない．本研究において，SOAP とWSDL を基盤とするGridRPC を実装し，実験した結果，これらの技術を用いることは有用であることが分かった．SOAP 基盤のGridRPC のナイーブな実装においては大きなオーバヘッドが大きいが，いくつかの性能向上を行なうことにより，本来のバイナリ転送に近い性能が得られた． 一方，配列パラメタの扱いなどのGridRPC 特有なさまざまな機能を実現することは，WSDL の制限により困難であることが分かった．</div> </blockquote>



- **グローバルコンピューティングのスケジューリングのための性能評価システム**  <span onmouseover="document.getElementById('sipp2000-takefusa').style.display = 'block'"  onmouseout="document.getElementById('sipp2000-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 合田憲人, 松岡聡, 中田秀基, 長嶋雲兵
, *情報処理学会論文誌, Vol. 41, No. 5*   , pp. 1628-1638  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sipp2000-takefusa"> グローバルコンピューティングシステムが複数提案される一方，グローバルコンピューティングシステムのスケジューリング手法に対する考察が不十分である．これは大規模かつ再現性のある評価実験が困難であることに起因する．本稿ではグローバルコンピューティングシステムのスケジューリングアルゴリズムとそのフレームワークのための評価基盤を提供するBricksシステムを提案する．Bricksでは様々な性能評価環境やスケジュールアルゴリズムおよびスケジューリングに関するモジュールを設定可能である．また，これらのモジュールを既存グローバルコンピューティングシステムモジュールに置き換えることで，Bricks上での既存システムの機能試験を実施することができる．他システムのBricksへの組み込み例としてリソース情報の予測システムであるNWSを用いて本システムの評価実験を行ったところ，Bricksが実環境と同等の挙動を示すことを確認した．さらに，NWSがBricks上で正常に動作したことから，Bricksが既存の外部モジュールに対して機能試験環境を提供できることを示した．</div> </blockquote>



- **クライアント・サーバ型のグローバルコンピューティングシステムの比較 -- Ninf,NetSolve, CORBAの性能評価 --**  <span onmouseover="document.getElementById('jspp00nakagawa').style.display = 'block'"  onmouseout="document.getElementById('jspp00nakagawa').style.display = 'none'">[abst]</span>   
中川貴之, 鈴村豊太郎, 松岡 聡, 中田秀基
, *並列処理シンポジウム JSPP2000 論文集*   , pp. 277-284  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp00nakagawa"> Ninf, NetSolve, Globusをはじめとするグローバルコンピューティング システムの近年の発展により，広域ネットワークを利用して高性能計算を 提供することが可能となった．一方，それらの研究の多くはアーキテクチャや アプリケーションの構築例に偏っており，その種のシステムが持つべき特性 については検証されていない．本稿では，実アプリケーションをNinf, NetSolve, CORBAを用いて実装し，定量的側面ばかりでなく，定性的側面にも 着目して各システムの比較を行った．その結果，グローバルコンピュー ティング専用のシステムが，CORBAのような汎用の分散コンピューティング システムに比べて，管理面，プログラマビリティで勝り，性能面でも WAN上で問題サイズが大きい時にはCORBAを上回ることが明らかになった． この結果により，専用システムの有効性が導かれたが，グローバル コンピューティングのための理想的なソフトウエアアーキテクチャを同定する ためには，引き続き様々なシステムに対する研究が必要であることもわかった．</div> </blockquote>



- **グローバルコンピューティングのためのスケジューリングフレームワーク**  <span onmouseover="document.getElementById('ipsj00nakada').style.display = 'block'"  onmouseout="document.getElementById('ipsj00nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 竹房 あつ子, 松岡 聡, 佐藤 三久, 関口 智嗣 
, *情報処理学会論文誌 Vol.41 No.5*   , pp. 1617-1627  , 2000 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj00nakada"> ネットワーク技術の発展にともない、グローバルコンピューティングシステムがいくつか提案されているが、その計算/通信リソースを十分活用するための手法はいまだ確立されていない。リソースの有効活用のためには、広域分散計算に特有なリソースの変動と不安定さを考慮し、関連する複数のタスクに対して一括して適切にリソースを割り当てるスケジューリング手法が必要とされている。本稿では、グローバルコンピューティング環境において個々のアプリケーションの性能とシステム全体のスループットを両立させるための、階層化されたスケジューリングフレームワークを提案する。さらに、このフレームワークに準拠したNinfシステムのメタサーバスケジューリングフレームワークの実装について述べ、試験的に複数のスケジューリング手法をメタサーバ上に実装しその動作を確認する。この結果、本フレームワークが十分にフレキシブルであることが示された。</div> </blockquote>



- **グローバルコンピューティングシステムのシミュレーションによる評価**  <span onmouseover="document.getElementById('sipp99-takefusa').style.display = 'block'"  onmouseout="document.getElementById('sipp99-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 合田憲人, 中田秀基, 小川宏高, 松岡聡, 佐藤三久, 関口智嗣, 長嶋雲兵
, *情報処理学会論文誌, Vol. 40, No. 5*   , pp. 2192-2202  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sipp99-takefusa"> グローバルコンピューティングを実現する試みが行われる一方，グローバルコンピューティングのスケジューリングに関する明確な知見は得られていない．これは，広域ネットワークでは再現性のある大規模性能評価が非常に困難で，性能要素に関する調査が十分なされていないためである．本稿では，グローバルコンピューティングシステムにおけるスケジューリングの公正な性能評価を行うシミュレータの設計および実装と，本シミュレータを用いた性能評価実験を行った．本シミュレータではネットワークとサーバを待ち行列で表し，その組合せにより多様なグローバルコンピューティングシステムが表現可能である．本シミュレータで実際のグローバルコンピューティングシステムをシミュレーションした結果，実測とほぼ同様の結果が得られた．また，本シミュレータを用いたスケジューリング手法の性能評価では，資源状況を適切に考慮したスケジューリングが有効であることが分かった．</div> </blockquote>



- **Globusを用いたグローバルコンピューティング環境の構築とその評価**  <span onmouseover="document.getElementById('ic99tanaka').style.display = 'block'"  onmouseout="document.getElementById('ic99tanaka').style.display = 'none'">[abst]</span>   
田中 良夫, 平野 基孝, 佐藤 三久, 中田 秀基, 関口 智嗣
, *インターネットカンファレンス&#x27;99*   , pp. 97-106  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic99tanaka"> Globusはグローバルコンピューティングのソフトウェアインフラストラクチャ に必要とされる様々な要素技術を提供するツール群である．我々はdenyベース のfirewallを越えて計算資源を利用する機能をGlobusに組み込み，グローバル コンピューティング環境を構築した．今回追加した機能は，新しい型のGlobus Resource Allocation Manager(GRAM)であるRMF(Resource Manager beyond the Firewall)およびNexusのTCP通信を中継するNexusProxyにより実装される．ま た，globusを用いたMPICHの実装であるMPICH-Gを用いて探索問題の並列解法を 実装し，グローバルコンピューティング環境でその実行性能を測定した．本稿 では今回構築したグローバルコンピューティング環境の概要と実装，その上で 並列プログラムを実行した際の性能，プログラミングの留意点，およびグロー バルコンピューティング環境の構築に向けての指針を述べる．グローバルコン ピューティング環境で並列計算を行なう場合，通信量の抑制と負荷分散が効率 に大きな影響を与える．これらの点に留意してプログラミングを行なうことに より，十分実用的な性能が得られることがわかった．</div> </blockquote>



- **グローバルコンピューティングのためのスケジューリングフレームワーク**  <span onmouseover="document.getElementById('jspp99nakada').style.display = 'block'"  onmouseout="document.getElementById('jspp99nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 竹房 あつ子, 松岡 聡, 佐藤 三久, 関口 智嗣
, *並列処理シンポジウム JSPP&#x27;99 論文集*   , pp. 277-284  , 1999 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp99nakada"> ネットワーク技術の発展にともない、グローバルコンピューティングシステムが いくつか提案されているが、 その計算/通信リソースを十分活用するための手法はいまだ確立されていない。 リソースの有効活用のために、 広域分散計算に特有なリソースの変動と不安定さを考慮し、 関連する複数のタスクに対して一括して 適切にリソースを割り当てるスケジューリング手法が必要とされている。本稿では、グローバルコンピューティング環境において 個々のアプリケーションの性能とシステム全体のスループットを 両立させるための、 階層化されたスケジューリングフレームワークを提案する。 さらに、このフレームワークに準拠したNinfシステムの メタサーバスケジューリングフレームワークの実装について述べ、 試験的に実装したスケジューリング手法による評価を行う。 この結果、本フレームワークのもつ可能性と、 タスク間のデータ依存関係を考慮したスケジューリングアルゴリズム の重要性が明らかになった</div> </blockquote>



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



- **並列計算機PIE64におけるCommitted-Choice型言語Flengの負荷分散手法**  <span onmouseover="document.getElementById('ipsj97nakada').style.display = 'block'"  onmouseout="document.getElementById('ipsj97nakada').style.display = 'none'">[abst]</span>   
中田秀基, 村上聡, 荒木拓也, 小池汎平, 田中英彦
, *情報処理学会論文誌 vol.38, no.2*   , pp. 332-340  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ipsj97nakada"> 本論文では、並列推論エンジンPIE64上でのCommitted-Choice 型言語 Fleng の実装に関して、負荷分散手法に重点をおいて論じる。負荷分散の要点は、データ参照の局所性とプログラムの並列性の抽出である。この両者はトレードオフの関係にあり、しかもトレードオフの最適点がプログラムの実行状況に応じて動的に変動する。このため最適な実行を行なうためには、動的に両者の関係を調整するような制御を行なわなければならない。われわれは、すでにコンパイラによる静的な負荷分割と実行時の動的な制御を組み合わせる手法を提案している。この手法は静的な負荷分割の情報を動的に用いることでつねに最適な実行を行なうものである。本稿ではこの手法の実装と、静的な負荷分割の具体的な手法について報告する。静的な負荷分割は、プログラム中のデータとプロセスの間の依存関係をグラフとして表現し、グラフ分割することで行なう。実行時には、計算機の動的状態を参照し、静的な負荷分割に基づいてプロセスの配置を行なう。実機にこの手法を実装し、実行時の環境を変化させて評価した。この結果、環境によらず実行が高速化され、本手法の有効性が確認された。</div> </blockquote>



- **Ninflet -- Java による World-Wide High Performance Computing 環境**  <span onmouseover="document.getElementById('ic97takagi').style.display = 'block'"  onmouseout="document.getElementById('ic97takagi').style.display = 'none'">[abst]</span>   
高木浩光, 松岡 聡, 中田秀基, 関口 智嗣, 佐藤 三久, 長嶋雲兵
, *インターネットカンファレンス&#x27;97*    , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic97takagi"> インターネット上の遊休計算機の計算パワーを世界規模で共有、 共同利用するための環境として、 Java の secure で architechture neutral な特長を活かした、 「Ninflet システム」を提案する。 本論文では、Ninflet システムの基本アーキテクチャ、並列分散処理への応用、 運用形態に関する考察、関連研究について述べる。</div> </blockquote>



- **マルチクライアントによるネットワーク数値情報システムNinfの性能**  <span onmouseover="document.getElementById('jspp97takefusa').style.display = 'block'"  onmouseout="document.getElementById('jspp97takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 小川宏高, 松岡 聡, 佐藤 三久, 中田秀基, 関口 智嗣, 長嶋雲兵
, *並列処理シンポジウム JSPP&#x27;97 論文集*   , pp. 273-280  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp97takefusa"> ネットワーク数値情報システムNinfは，広域ネットワークに分散した計算資源や情報資源を利用して高速・高性能・高品質な科学技術計算を実現するための基盤システムである．本稿ではNinfの全体構成について述べるとともに，LANおよびWANにおいてLinpack benchmarkを用いて，シングル/マルチクライアント環境での本システムの性能評価を実施した．この結果，現実的な広域分散利用条件でのNinfシステムの実用性，堅牢性を確認した．また，既存のベクトルパラレルマシンをはじめとする並列計算機がNinfによってネットワーク計算資源として有効に活用されることを示した．</div> </blockquote>



- **Ninf による広域分散並列計算**  <span onmouseover="document.getElementById('jspp97nakada').style.display = 'block'"  onmouseout="document.getElementById('jspp97nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高木浩光, 松岡 聡, 長嶋雲兵, 佐藤 三久, 関口 智嗣
, *並列処理シンポジウム JSPP&#x27;97 論文集*   , pp. 281-288  , 1997 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jspp97nakada"> ローカルなネットワーク上でのメッセージパッシングライブラリを用いた 分散並列計算はすでに広く行なわれている。 しかし、ネットワークの高速化によって現実的になりつつある 広域ネットワーク上での分散並列計算については、 ソフトウェアの枠組が未だ十分に整備されていない。我々は、広域分散並列計算に適した分散計算の枠組として「Ninf」を提案している。 Ninf は広域分散環境でのマクロデータフローによる並列実行を支援するシステムで、 広域での動的負荷分散とスケジューリングを特徴とする。 メッセージパッシングライブラリを用いた手法に比較して (1)広域ネットワークに適した通信パターンを用いる、 (2)ユーザにとってプログラミングが容易でかつ再利用性が高い、 (3)既存のライブラリの再利用が容易、 (4)ネットワーク上の資源の利用が可能、 といった特長をもつ。</div> </blockquote>



- **Ninf: World-Wide Computing指向のネットワーク数値情報ライブラリ**    
佐藤 三久, 中田 秀基, 関口 智嗣, 松岡 聡, 長嶋 雲兵
, *インターネットコンファレンス&#x27;96*    , 1996 



        
