---
layout: default
---
# Gridars 

- **NSIコネクションサービスプロトコルver. 2の参照実装の開発**  <span onmouseover="document.getElementById('ns14takefusa').style.display = 'block'"  onmouseout="document.getElementById('ns14takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 工藤 知宏 , 高野 了成, 中田 秀基, 大久保克彦, 岡崎史裕
, *信学技報 NS2013-202 (2014-3)*    , 2014 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns14takefusa"> 研究・教育ネットワークでは，異なる管理ドメインが提供する複数ネットワークを跨ったパスを動的に構築・提供する試みが複数行われており，実運用サービスが開始されようとしている．OGFのNSIワーキンググループでは，そのためのインタフェースとしてConnection Service (CS)プロトコルの標準化を進めている．CSプロトコルの検証には，ネットワークサービスのプロバイダ，アグリゲータ，リクエスタ用のソフトウェアやモニタリングツールが必要となる．本研究では，GridARSフレームワークとしてCS v. 2.0プロトコルに準拠したこれらのソフトウェアモジュール群を開発した．我々は，CS v. 2.0プロトコルの相互運用実験に開発したモジュール群を提供し，国際的な実証実験に貢献した．また，本フレームワークはオープンソースとして公開されており，本フレームワークを用いたアプリケーション，プロバイダ，モニタリングツールが第三者により開発されていることを示す．</div> </blockquote>



- **FELIX大規模情報通信基盤を活用した日欧実証実験に向けて**  <span onmouseover="document.getElementById('ag13takefusa').style.display = 'block'"  onmouseout="document.getElementById('ag13takefusa').style.display = 'none'">[abst]</span>   
竹房 あつ子, 工藤 知宏 , 高野 了成, 中田 秀基
, *アカデミッククラウドシンポジウム2013*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ag13takefusa"> 日欧のネットワークテストベッドを利用した日欧実証実験を目的としたFELIXプロジェクトについて紹介するとともに、その実現に向けた産総研の取り組みについて紹介する。</div> </blockquote>



- **A Distributed Application Execution System for an Infrastructure with Dynamically Configured Networks**  <span onmouseover="document.getElementById('netcloud12takano').style.display = 'block'"  onmouseout="document.getElementById('netcloud12takano').style.display = 'none'">[abst]</span>   
Ryousei Takano, Hidemoto Nakada, Atsuko Takefusa, Tomohiro Kudoh
, *International Workshop on Network Infrastructure Services as part of IEEE Cloud Computing 2012*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="netcloud12takano"> We have been developing a middleware suite called GridARS that enables co-allocation of computing and network resources from multiple administration sites. In such middleware, it is important to provide each user application with a slice which is a set of dynamically allocated resources distributed across sites. However, there are several issues in constructing such a slice automatically. We design and implement an application execution system that provides each application with a slice, that mimics a conventional computing cluster system over the dynamically allocated resources. From the demonstration of the proposed system on an emulated wide area network environment, we confirmed that: first, the proposed system can fully automate resource allocation, slice construction, application invocation, and resource monitoring, in coordination with GridARS. Second, the proposed system can setup a slice quickly, even if the allocated resources are widely distributed and their communication latencies are high.</div> </blockquote>



- **NSI相互運用試験のためのGridARSによるネットワーク資源管理**  <span onmouseover="document.getElementById('ns1203takefusa').style.display = 'block'"  onmouseout="document.getElementById('ns1203takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 工藤知宏, 中田 秀基, 高野 了成, 大久保克彦, 岡崎 史裕, 柳田誠也
, *電子情報通信学会技術研究報NS2011-224*   , pp. 249-254  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns1203takefusa"> NSI(Network Service Interface)はOGFで標準化が進められているネットワーク上のコネクションを要求するためのインタフェースであり、そのドラフト第一版が2011年3月にリリースされた。NSIの実現可能性を示すため、我々を含む欧米亜の複数機関によりウェブサービスベースの参照実装が開発され、国際的なネットワークテストベッド上で相互運用試験を行っている。
我々は、複数クラウド環境で多種資源を管理するフレームワークとしてGridARSを開発している。本研究では、GridARSにJAX-WS 2.0の非同期モデルを新たに実装して手続きの高速化を図るとともに、GridARSに対するNSIプロキシを開発し、プロキシを介して複数参照実装との相互運用を実証した。</div> </blockquote>



- **GridARS: A Grid Advanced Resource Management System Framework for Intercloud**  <span onmouseover="document.getElementById('netCloud11takefusa').style.display = 'block'"  onmouseout="document.getElementById('netCloud11takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Hidemoto Nakada, Ryousei Takano, Tomohiro Kudoh, Yoshio Tanaka
, *CloudCom 2011, NetCloud workshop*   , pp. 705-710  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="netCloud11takefusa"> Intercloud is a promising technology for data intensive applications. However, an important issue for Intercloud applications is orchestration of various virtualized and performance-assured resources, not only computers, but also network and storage, provided from multiple domains. We have been developing an advance reservation-based resource management framework, called Grid ARS, which can integrate heterogeneous resources and construct a performance-assured virtual infrastructure over Intercloud environment. Grid ARS provides four services that address resource management, resource allocation planning, provisioning and monitoring of the constructed virtual infrastructure. Grid ARS has been developed using common Web services technologies and standards. In this paper, we present overview of Grid ARS and its service components and describe Grid ARS demonstration challenges, demonstration at GLIF2010 and SC10 and OGF NSI interoperation in 2011.</div> </blockquote>



- **GridARS Resource Management Framework for InterCloud**  <span onmouseover="document.getElementById('sc11poster-takefusa').style.display = 'block'"  onmouseout="document.getElementById('sc11poster-takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Hidemoto Nakada, Ryousei Takano, Tomohiro Kudoh, Yoshio Tanaka
, *SC11 Poster*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sc11poster-takefusa"> Cloud computing is considered as an attractive infrastructure for data intensive applications. However, current cloud services do not support construction of a virtual infrastructure over distributed InterCloud resources. Furthermore, the performance of the infrastructure, including storage and network resources, is not assured. We are developing a resource management framework called GridARS (Grid Advance Reservation-based System framework) that integrates not only computers and storage, but also networks, constructing a QoS-guaranteed virtual infrastructure over these resources. GridARS is a reference implementation of GNS-WSI (Grid Network Service - Web Services Interface), defined by the G-lambda project. GridARS provides a wrapper software for existing resource management systems and it enables construction of a virtual infrastructure, based on advance reservation, and also provides monitoring information, dynamically. In this poster, we present overview, the performance and extension of GridARS, introduction of GLIF2010 and SC10 demonstration, and interoperation to NSI, defined by OGF.</div> </blockquote>



- **マルチドメインクラウド資源管理フレームワーク**  <span onmouseover="document.getElementById('ieice11takefusa').style.display = 'block'"  onmouseout="document.getElementById('ieice11takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 高野了成, 柳田誠也, 大久保克彦, 工藤知宏, 田中良夫
, *電子情報通信学会論文誌 vol.J94-B No.10*   , pp. 1332-1340  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice11takefusa"> マルチドメインクラウドの資源管理フレームワークとして，資源管理システム，アプリケーション実行管理システム，分散モニタリングシステムからなるGridARSを開発している．本研究では，既存システムを拡張し，相互運用性，機能性の高いGridARSシステムを開発し，大規模環境でその有用性を評価した．また，GLIF2010およびSC10において実証実験を行い，GridARSを用いてマルチドメインクラウド上に自動的にユーザの要求を満たす仮想インフラを構築し，そのモニタリングを行うことに成功した．</div> </blockquote>



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



- **マルチドメインクラウド環境のための資源管理フレームワーク**  <span onmouseover="document.getElementById('comsys10-takefusa-poster').style.display = 'block'"  onmouseout="document.getElementById('comsys10-takefusa-poster').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 高野了成, 柳田誠也, 大久保克彦, 工藤知宏, 田中良夫
, *第22回コンピュータシステム・シンポジウム(ComSys2010)*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys10-takefusa-poster"> クラウドは，大規模データインテンシブ科学技術計算の計算基盤としても注目されているが，分散する複数組織から提供される資源を統合して計算基盤を構築する技術は成熟していない．我々は，マルチドメインクラウド環境で仮想計算基盤を提供する資源管理フレームワークGridARSを提案している．GridARSは，資源管理サービス，プロビジョニングサービス，モニタリングサービスを提供し，予約ベースでマルチドメインクラウド上の資源の選択と確保，仮想計算基盤の構築とユーザアプリケーションの実行，モニタリング情報の提供を自動的に行う．デモンストレーションでは，クラスタ上に構築した仮想マルチドメインクラウド環境を用いて，本フレームワークが実際に動作する様子を示す．</div> </blockquote>



- **大規模資源の管理・制御に関する技術の実証実験 －新世代ネットワークプラットフォームの実現に向けて－**  <span onmouseover="document.getElementById('ns-miyamoto-2010').style.display = 'block'"  onmouseout="document.getElementById('ns-miyamoto-2010').style.display = 'none'">[abst]</span>   
林 通秋, 竹房 あつ子, 池永全志, 宮本 崇弘, 小島 功, 嶋村昌義, 松本延孝, 中田 秀基, 小出洋, 高野 了成, ジルセウ・ガベンディッシュ, 工藤 知宏, 田中 良夫, 西村公佐
, *電子情報通信学会技術研究報告ネットワークシステム*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ns-miyamoto-2010"> クラウドコンピューティングの更なる普及や新世代ネットワークに向けた新たなインフラの実現に向けて，計算機やネットワークなどのICT資源を大規模に管理制御して，ユーザの用途に適したICT環境を柔軟に作る技術への期待が高まっている．そこで，複数のネットワークからなる規模のICT資源の存在を把握し，用途に応じて適した資源を割り当てる資源提供プラットフォームを開発した．また，データを適応的に圧縮するなどの機能を持つ高機能中継ノードを開発し，資源提供プラットフォームを通じて用途に応じて割り当てることで，ネットワーク内での輻輳下でも通信品質を維持することに成功した．</div> </blockquote>



- **Grid Network Service - Web Services Interface Version 2, Achieving Scalable Reservation of Network Resources Across Multiple Network Domains**  <span onmouseover="document.getElementById('ieice10g-lambda').style.display = 'block'"  onmouseout="document.getElementById('ieice10g-lambda').style.display = 'none'">[abst]</span>   
Yukio Tsukishima, Michiaki Hayashi, Tomohiro Kudoh, Akira Hirano, Takahiro Miyamoto, Atsuko Takefusa, Atsushi Taniguchi, Shuichi Okamoto, Hidemoto Nakada, Yasunori Sameshima, Hideaki Tanaka, Fumihiro Okazaki, Masahiko Jinno
, *IEICE Transaction on Communications, vol. E93-B, no 10*   , pp. 2696-2705  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice10g-lambda"> Platforms of hosting services are expected to provide a virtual private computing infrastructure with a guaranteed level of performance according to each reservation request sent from a client. To expand the performance of the computing infrastructure for reservation requests, the platforms are required to reserve, coordinate, and control globally distributed computing and network resources across multiple domains. This paper proposes Grid Network Service - Web Services Interface version 2 (GNS-WSI2). GNS-WSI2 is a resource-reservation messaging protocol that establishes a client-server relationship. A server allocates available network resources over its own domain according to each reservation request from a client. GNS-WSI2 has the capability to reserve network resources rapidly and reliably over multiple network domains. This paper also presents demonstration results of the feasibility of GNS-WSI2 in terms of the scalable reservation of network resources over multiple network domains in a transpacific testbed. In the demonstration, two computing infrastructures over multiple network domains are dynamically provided for scientific computing and remotevisualization applications, respectively. On the provided infrastructures, these applications are executed. The feasibility is successfully shown through the demonstration.</div> </blockquote>



- **性能を保証する分散実行環境のためのオンラインコアロケーション手法**  <span onmouseover="document.getElementById('acs31takefusa').style.display = 'block'"  onmouseout="document.getElementById('acs31takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *情報処理学会論文誌コンピューティングシステム vol.3 no.3*   , pp. 126-137  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs31takefusa"> 利用者の要求する計算機性能やネットワーク帯域を保証した分散実行環境を構築して提供する場合，利用者や資源管理者の資源の割当て方針を反映させた計算機とネットワークのコアロケーションが重要な課題となる．本稿では，分散する資源が事前予約で複数の組織から提供されることを前提とし，計算機とネットワークを同時に確保するためのオンラインコアロケーション手法を提案する．提案手法では，資源のコアロケーションを整数計画問題にモデル化することにより，ユーザや資源管理者の資源の割当て方針を反映することができる．シミュレーションによる実験により，提案手法の機能性，実用性に関する評価を行う．評価から，提案手法により計算機とネットワークのコアロケーションが可能であり，資源管理者の観点で資源割当て方針が反映できること，オンライン処理として実用的であることを示す．</div> </blockquote>



- **An Advance Reservation-based Co-Allocation Algorithm for Distributed Computers and Network Bandwidth on QoS-guaranteed Grids**  <span onmouseover="document.getElementById('jsspp10takefusa').style.display = 'block'"  onmouseout="document.getElementById('jsspp10takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Hidemoto Nakada, Tomohiro Kudoh, Yoshio Tanaka
, *15th Workshop on Job Scheduling Strategies for Parallel Processing*    , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsspp10takefusa"> Co-allocation of performance-guaranteed computing and network resources provided by several administrative domains is one of the key issues for constructing a QoS-guaranteed Grid. We propose an advance reservation-based co-allocation algorithm for both computing and network resources on a QoS- guaranteed Grid, modeled as an integer programming (IP) problem. The goal of our algorithm is to create reservation plans satisfying user resource requirements as an on-line service. Also the algorithm takes co-allocation options for user and resource administrator issues into consideration. We evaluate the proposed al- gorithm with extensive simulation, in terms of both functionality and practicality. The results show: The algorithm enables efficient co-allocation of both computing and network resources provided by multiple domains, and can reflect reservation options for resource administrators issues as a first step. The calculation times needed for selecting resources using an IP solver are acceptable for an on-line service.</div> </blockquote>



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



- **性能を保証する分散実行環境のためのオンラインコアロケーション手法**  <span onmouseover="document.getElementById('comsys09-takefusa').style.display = 'block'"  onmouseout="document.getElementById('comsys09-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *第21回コンピュータシステム・シンポジウム(ComSys2009)*   , pp. 83-92  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys09-takefusa"> 利用者の要求する計算機性能やネットワーク帯域を保証した分散実行環境を構築して提供する場合，それらの資源の同時割り当て（コアロケーション）が重要な課題となる．本稿では，分散する資源が事前予約で複数の組織から提供されることを前提として，オンラインコアロケーション手法を提案する．提案手法では，我々の開発する資源管理フレームワークから利用可能な資源情報を取得し，最適化問題にモデル化したコアロケーションアルゴリズムを用いて複数の予約プランを作成する．また，提案手法では，ユーザや資源管理者の資源の割り当て方針を反映することができる．シミュレーションによる実験を行い，提案するオンラインコアロケーション手法の機能性，実用性に関する評価を行う．機能性の評価では，提案手法の予約成功率の高さと，資源管理者の観点で資源割り当て方針が反映できることを示す．実用性の評価では，最適化問題の求解時間を制約条件とソルバの違いにより比較するとともに，実用化に向けて議論する．</div> </blockquote>



- **ネットワーク帯域予約とOS仮想化機構を用いた分散アプリケーション実行環境**  <span onmouseover="document.getElementById('comsys09-nakada').style.display = 'block'"  onmouseout="document.getElementById('comsys09-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高野了成, 竹房あつ子, 工藤知宏
, *第21回コンピュータシステム・シンポジウム(ComSys2009)*   , pp. 51-58  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys09-nakada"> 複数のサイトにまたがって計算資源，ネットワーク資源を動的に確保し，アプリケーションを実行することは以下の理由により困難である．1) ネットワークの非対称性、2) サイト間の非均質性，3) 必要情報の実行時確定，4) アプリケーションのマルチホームネットワーク非対応．このため，現在のグリッド環境では既存のアプリケーションをそのまま実行することは難しい．我々は，予約ベースで計算資源とネットワーク資源を確保し，その上にごく一般的なクラスタ内の環境と類似した環境を構築するグリッドミドルウェアの構築を行っている．このグリッドミドルウェアを用いると，既存のアプリケーションを修正すること無く実行することが可能となる．本稿ではこのグリッドミドルウェアのアプリケーション実行フレームワークの設計とプロトタイプ実装について述べる．プロトタイプにより，フレームワークの設計の妥当性を確認した．また，OS仮想化を用いることで高速に実行環境をセットアップできることを確認した．</div> </blockquote>



- **大規模環境における資源情報連携アーキテクチャ**  <span onmouseover="document.getElementById('ngnworkshop2009').style.display = 'block'"  onmouseout="document.getElementById('ngnworkshop2009').style.display = 'none'">[abst]</span>   
宮本 崇弘, 小島 功, 池永全志, 林 通秋, 田中 良夫, ジルセウ・ガベンディッシュ, 松本延孝, 工藤 知宏, 小出洋, 田中 英明, 児玉 祐悦, 嶋村昌義, 中田 秀基, 竹房 あつ子, 高野 了成
, *電子情報通信学会 新世代ネットワークワークショップ 2009*   , pp. 7-12  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ngnworkshop2009"> けて，計算機やネットワークなどのICT資源を大規模に管理制御して，ユーザの用途に適したICT環境を柔軟に作る技術への期待が高まっている．そこで，複数のネットワークからなる規模のICT資源の存在を把握し，用途に応じて適した資源を割り当てる資源提供プラットフォームを開発した．また，データを適応的に圧縮するなどの機能を持つ高機能中継ノードを開発し，資源提供プラットフォームを通じて用途に応じて割り当てることで，ネットワーク内での輻輳下でも通信品質を維持することに成功した．</div> </blockquote>



- **性能を保証する計算・ネットワーク資源のコアロケーション手法の評価**  <span onmouseover="document.getElementById('swopp09-takefusa').style.display = 'block'"  onmouseout="document.getElementById('swopp09-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *情報処理学会研究報告2009-HPC-121*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-takefusa"> 利用者の要求する性能を保証しつつ計算機・ネットワークなどの資源を組合わせて提供する場合，それらの資源のスケジューリングが重要な課題となる．我々は既発表研究において，このようなスケジューリングを最適化問題としてモデル化し，必要な計算・ネットワーク資源を同時に確保するためのオンラインコアロケーション手法を提案した．一方，最適化問題として解くと，変数の数に依存して指数的に求解時間が長くなるため，実用化に向けた課題が残る．本研究では， (1) 制約条件を追加することにより既発表研究の手法を改良し，求解時間の短縮を図るとともに，(2) 制約条件とソルバの違いによるに求解時間を比較し，実用化に向けて議論する．また，既発表研究に対して追加の実験を行い，(3) 重み付けすることにより管理者の要求を反映した資源の割り当てが可能であり，我々の手法が機能面でも有効であることを示す．</div> </blockquote>



- **Design of a Domain Authorization-based Hierarchical Distributed Resource Monitoring System in cooperation with Resource Reservation**  <span onmouseover="document.getElementById('hpcasia2009-takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpcasia2009-takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Hidemoto Nakada, Seiya Yanagita, Fumihiro Okazaki, Tomohiro Kudoh, Yoshio Tanaka
, *Proc. HPC Asia 2009*   , pp. 77-84  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcasia2009-takefusa"> Grid and Network provisioning technology has enabled the construction of high-quality virtual computing infrastructures spanning several administrative organizations. However, it is still difficult for users to monitor the usage of distributed and various resources managed by multiple domains. We propose an authorization-based hierarchical distributed resource monitoring system called DMS that gathers information based on resource reservation, and filters information with the policies specified by the administrators using XACML, which is a standard authorization model and a policy description language. DMS co-works with the GridARS co-allocation framework to retrieve resource reservation information and adopts web services technologies and an extension of a standard data representation set. To confirm feasibility of the DMS system, we describe monitoring strategies for reserved computing and network resources in Collectors and we have developed a WSRF-based DMS prototype, which enables authorization by XACML. The experiments using the prototype system show: (1) Even when DMS employs a large number of policies, the overhead of the XACML authorization decision process is negligible, since that of WSRF/GSI is more dominant in the total processing time, and (2) the benefits of parallel information aggregation from multiple domains make the retrieval latency acceptable.</div> </blockquote>



- **ネットワーク帯域予約とOS仮想化機構を用いた分散アプリケーション実行環境に向けて** [[Slides](dataDir/hokke09-nakada_slides.pdf)]  <span onmouseover="document.getElementById('hokke09-nakada').style.display = 'block'"  onmouseout="document.getElementById('hokke09-nakada').style.display = 'none'">[abst]</span>   
中田秀基, 高野了成, 竹房あつ子, 工藤知宏
, *情報処理学会研究報告2008-HPC-119*   , pp. 61-66  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke09-nakada"> 複数のサイトにまたがって計算資源，ネットワーク資源を動的に確保し，アプリケーションを実行することは以下の理由により困難である．1) ネットワークの非対称性、2) サイト間の非均質性，3) 必要情報の実行時確定，4) アプリケーションのマルチホームネットワーク非対応．このため，現在のグリッド環境では既存のアプリケーションをそのまま実行することは難しい．我々は，予約ベースで計算資源とネットワーク資源を確保し，その上にごく一般的なクラスタ内の環境と類似した環境を構築するグリッドミドルウェアの構築を行っている．このグリッドミドルウェアを用いると，既存のアプリケーションを修正すること無く実行することが可能となる．本稿ではこのグリッドミドルウェアのアプリケーション実行フレームワークの設計とプロトタイプ実装について述べる．プロトタイプを用いた実行の結果，フレームワークの設計の妥当性を確認した．</div> </blockquote>



- **高品質分散実行環境のための計算・ネットワーク資源のグローバルスケジューリング手法**  <span onmouseover="document.getElementById('hokke09-takefusa').style.display = 'block'"  onmouseout="document.getElementById('hokke09-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫
, *情報処理学会研究報告2008-HPC-119*   , pp. 55-60  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke09-takefusa"> 高品質分散実行環境の構築に際し，ユーザの要求を満たす高品質資源群を適切に確保し，かつ，グリッド上の資源群を有効活用するためには，グローバルスケジューリングが重要な課題となる．本稿では，高品質分散実行環境の構築を目的とした計算・ネットワーク資源のグローバルスケジューリング手法を提案し，シミュレーションでの評価により，その有効性を示す．提案するグローバルスケジューリング手法は，ユーザの計算機及びネットワークに関する資源要求に対して，複数資源マネージャから利用可能な資源情報を入手し，組合せ最適化問題に帰着して事前予約プランを作成する．シミュレーションによる評価により，提案手法が有効であることを示す．</div> </blockquote>



- **資源予約と連携した階層型分散資源モニタリングシステムの設計**  <span onmouseover="document.getElementById('hpc0810-takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0810-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 岡崎史裕, 工藤知宏, 田中良夫
, *情報処理学会研究報告 2008-HPC-117*   , pp. 13-18  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0810-takefusa"> グリッドとネットワークプロビジョニング技術を用いることで，複数管理組織を跨る高品質の仮想計算基盤を動的に構築・提供することが可能になった．しかしながら，分散する多様な資源で構成される仮想計算基盤の利用者が，確保した資源群の状況を把握するのは困難である．本研究では，資源予約により複数管理組織を跨る資源群を利用するユーザに対し，利用資源のモニタリング情報を収集し，各管理者の開示ポリシに基づき資源情報を提供する，階層型分散資源モニタリングシステムを提案する．提案システムでは，GridARSコアロケーションフレームワークを用いて資源予約との連携を実現する．本稿では，提案システムの設計について述べるとともに，本システムによる計算機およびネットワーク資源のモニタリング情報の収集・提供方針を述べる．</div> </blockquote>



- **WSRFに基づく情報サービスのXACMLによるアクセス制御**  <span onmouseover="document.getElementById('acs23-takefusa').style.display = 'block'"  onmouseout="document.getElementById('acs23-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.1 No.2 (ACS23)*   , pp. 180-192  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs23-takefusa"> グリッドでは資源やジョブに関する情報の提供は重要な機能のひとつであり，クラスタ監視ツールのGangliaやGlobus Toolkit 4のMDS4などの情報サービスが実現されている．しかしながら，複数の仮想組織に属するユーザが資源を共有する場合，全情報をすべてのユーザに開示することは好ましくない．本研究では，認可モデルとポリシ記述言語の標準として提案されているXACMLを用い，サイト毎に情報開示ポリシを定義して，各ユーザからの細粒度の情報アクセス制御を可能にする，WSRFに基づく情報サービスシステムを提案する．本研究で開発したプロトタイプでの予備実験から，(1)情報収集に関するオーバヘッドはWSRF/GSIによるもので占められ，認可決定の時間は無視できる，(2)複数サイトから情報収集する場合も，手続きを並行して行うとその所要時間は許容できる，(3)XACMLのポリシ数が多い場合も，判定に要する時間は全体の処理時間に対して十分小さいことが確認できた．</div> </blockquote>



- **PluS予約機構のCondorへの適用** [[Paper](dataDir/hpc0712nakada.pdf)] [[Slides](dataDir/hpc0712nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0712nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0712nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-113*   , pp. 43-48  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0712nakada"> 複数資源の同時確保には，各資源が事前予約機構を備えていなければならない．我々は既存のローカルスケジューラに対して事前予約機構を付加するPluS事前予約機構を開発している．PluS事前予約機構は，2つの動作モードを持つが，そのうちの1つであるキュー制御 動作モードは，ローカルスケジューラが特定の機能を持つことを前提に， モジュール構成を改変すること無く予約機構を付加することができる． このキュー制御動作モードは，特定のローカルスケジューラに依存しないよう 注意深く設計されているが，これまでの実際の適用例は，Sun Grid Engineのみで キュー制御動作モードの汎用性は立証されていなかった．本稿では，キュー制御動作モードの汎用性を立証するべく，Sun Grid Engineとは全く異なる基本設計に基づくローカルスケジューラ Condorに対してPluSの適用を行った．その結果，わずかなコード量でCondorへの適応が可能なことを確認した.</div> </blockquote>



- **多様な資源を事前予約で同時確保するためのグリッドコアロケーションシステムフレームワークGridARS**  <span onmouseover="document.getElementById('acs20takefusa').style.display = 'block'"  onmouseout="document.getElementById('acs20takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.48, No. SIG18 (ACS20)*   , pp. 32-43  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs20takefusa"> グリッドで並列高性能計算の性能を向上させるには，コアロケーションシステムが既存資源スケジューラと連携して多様な資源を事前同時予約できることが重要 である．本稿ではWSRFに基づく事前予約インタフェースを提供するコアロケーションフレームワークGridARSを提案する．GridARSでは分散ト ランザクションによる同時予約手続きを行うため，汎用的な2相コミット事前予約プロトコルを設計し，実装した．GridARSの有効性を示すため，複数資 源マネージャに対する同時予約手続きの基礎性能を評価した．また，応用事例として複数資源スケジューラで管理される日米間にまたがるネットワーク，計算資 源を同時確保する実証実験について報告する．これにより，1) GridARSの2相コミットによる予約手続きが有効であり，2) GridARSのコアロケーションシステムが，多様な資源のスケジューラと連携し，安定して分散資源を同時確保できることを示す．</div> </blockquote>



- **WSRFに基づく情報サービスのXACMLによるアクセス制御**  <span onmouseover="document.getElementById('comsys07takefusa').style.display = 'block'"  onmouseout="document.getElementById('comsys07takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 柳田誠也, 工藤知宏, 田中良夫, 関口智嗣
, *コンピュータシステム・シンポジウム論文集*   , pp. 199-208  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="comsys07takefusa"> グリッドでは資源やジョブに関する情報の提供は重要な機能のひとつであり、クラスタ監視ツールの Ganglia や Globus Toolkit 4 の MDS4 などの情報サービスが実現されている。しかしながら、複数の仮想組織に属するユーザが資源を共有する場合、全情報をすべてのユーザに開示することは好ましくない。本研究では、認可モデルとポリシ記述言語の標準として提案されている XACML を用い、サイト毎に情報開示ポリシを定義して、各ユーザからの細粒度の情報アクセス制御を可能にする、WSRF に基づく情報サービスシステムを提案する。本研究で開発したプロトタイプでの予備実験から、(1) 情報収集に関するオーバヘッドは WSRF/GSI によるもので占められ、認可決定の時間は無視できる、(2) 複数サイトから情報収集する場合も、手続きを並行して行うとその所要時間は許容できる、(3) XACML のポリシ数が多い場合も、判定に要する時間は全体の処理時間に対して十分小さいことが確認できた。</div> </blockquote>



- **G-lambda and EnLIGHTened: Wrapped In Middleware Co-allocating Compute and Network Resources Across Japan and the US**  <span onmouseover="document.getElementById('gridnets07steve').style.display = 'block'"  onmouseout="document.getElementById('gridnets07steve').style.display = 'none'">[abst]</span>   
Steven R. Thorpe, Lina Battestilli, Gigi Karmous-Edwards, Andrei Hutanu, Jon MacLaren, Joe Mambretti, John H. Moore, Kamaraju Syam Sundar, Yufeng Xin, Atsuko Takefusa, Michiaki Hayashi, Akira Hirano, Shuichi Okamoto, Tomohiro Kudoh, Takahiro Miyamoto, Yukio Tsukishima, Tomohiro Otani, Hidemoto Nakada, Hideaki Tanaka, Atsushi Taniguchi, Yasunori Sameshima, Masahiko Jinno
, *Proc. First International Conference on Networks for Grid Applications (GridNets)*   , pp. 8p  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="gridnets07steve"> This paper describes innovative architectures and techniques for reserving and coordinating highly distributed resources, a capability required for many large scale applications. In the fall of 2006, Japan&#x27;s G-lambda research team and the United States&#x27; EnLIGHTened Computing research team used these innovations to achieve the world&#x27;s first inter-domain coordination of resource managers for in-advance reservation of network bandwidth and compute resources between and among both the US and Japan. The compute and network resource managers had different interfaces and were independently developed. Automated interoperability among the resources in both countries was enabled through various Grid middleware components. In this paper, we describe the middleware components, testbeds, results, and lessons learned.</div> </blockquote>



- **Network as a resource: G-lambda project and its architecture**    
Tomohiro Kudoh, Michiaki Hayashi, Akira Hirano, Shuichi Okamoto, Atsuko Takefusa, Takahiro Miyamoto, Yukio Tsukishima, Tomohiro Otani, Hidemoto Nakada, Hideaki Tanaka, Atsushi Taniguchi, Yasunori Sameshima, Masahiko Jinno
, *First International Conference on Networks for Grid Applications*    , 2007 



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



- **事前予約機構のポリシ記述による制御** [[Paper](dataDir/hpc0706nakada.pdf)]  <span onmouseover="document.getElementById('hpc0706nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0706nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-110*   , pp. 19-24  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0706nakada"> グリッド上の複数サイトにまたがるジョブの実行を実現する方法として，事前予約による同時確保がある．事前予約を実現するローカルスケジューラは，いくつか提案されているものの，事前予約ジョブと通常のジョブを共存させるための適切なポリシは明らかになっていない．われわれは，事前予約ジョブと通常ジョブ間のポリシは，各サイトのローカルスケジューラに内蔵されるべきではなく，管理者が設定するべき事項であると考え，実装中の{\plus}事前予約機構に，管理者によるポリシ記述機能を組み込んだ．ポリシ記述には，Condor プロジェクトで用いられているClassAdを用いた．我々は，1)ClassAd による記述力は管理ポリシを記述するのに十分であること，2)PluSの提供する情報により有効な管理ポリシが記述できること，3)ClassAd によるポリシ解釈のオーバヘッドは十分小さいことを確認した．</div> </blockquote>



- **An Advance Reservation-based Computation Resource Manager for Global Scheduling** [[Paper](dataDir/gca07nakada.pdf)] [[Slides](dataDir/gca07nakada_slide.pdf)]  <span onmouseover="document.getElementById('gca07nakada').style.display = 'block'"  onmouseout="document.getElementById('gca07nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Atsuko Takefusa, Katsuhiko Ookubo, Tomohiro Kudoh, Yoshio Tanaka, Satoshi Sekiguchi
, *GCA2007 Proceedings of the 3rd International Workshop on Grid Computing and Applications*   , pp. 3-14  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="gca07nakada"> Advance Reservation is one possible way to enable resource co-allocation on the Grid. This method requires all the resources to have advance reservation capability as well as coordination protocol support. We employed 2-phased commit protocol as a coordination protocol, which is common in the distributed transaction area, and implemented an Advance Reservation Manager called {\bf PluS}. PluS works with existing local queuing managers, such as TORQUE or Grid Engine, and provides users advance reservation capability. To provide the capability, there are two implementation methods; 1) completely replaces the scheduling module of the queuing manger, 2) represents reservation as a queue and controls the queues using external interface. We designed and implemented a reservation manager with both way, and evaluated them. We found that the former has smaller overhead and allows arbitrary scheduling policy, while the latter is much easier to implement withacceptable response time.</div> </blockquote>



- **GridARS: An Advance Reservation-based Grid Co-allocation Framework for Distributed Computing and Network Resources**  <span onmouseover="document.getElementById('jsspp2007-takefusa').style.display = 'block'"  onmouseout="document.getElementById('jsspp2007-takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Hidemoto Nakada, Tomohiro Kudoh, Yoshio Tanaka, Satoshi Sekiguchi
, *Proc. 13th Workshop on Job Scheduling Strategies for Parallel Processing (LNCS 4942), Seattle*   , pp. 152-168  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsspp2007-takefusa"> For high performance parallel computing on actual Grids, one of the important issues is to co-allocate the distributed resources that are managed by various local schedulers with advance reservation. To address the issue, we proposed and developed the GridARS resource co-allocation framework, and a general advance reservation protocol that uses WSRF/GSI and a two-phased commit (2PC) protocol to enable a generic and secure advance reservation process based on distributed transactions, and provides the interface module for various existing resource schedulers. To confirm the effectiveness of GridARS, we describe the performance of a simultaneous reservation process and a case study of GridARS grid co-allocation over transpacific computing and network resources. Our experiments showed that: 1) the GridARS simultaneous 2PC reservation process is scalable and practical and 2) GridARS can co-allocate distributed resources managed by various local schedulers stably.</div> </blockquote>



- **グローバルスケジューリングのための計算資源予約管理機構**  <span onmouseover="document.getElementById('acs18nakada').style.display = 'block'"  onmouseout="document.getElementById('acs18nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.48 No.SIG8 (ACS18)*   , pp. 71-81  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs18nakada"> グリッド上で複数の資源の同時確保を実現する方法のひとつとして事前予約を行う方法がある．これを実現するためには、同時確保の実現に求められる協調プロトコルを実装した事前予約機構を，グリッド上の各資源が持つことが必要となる。われわれは，同時確保のプロトコルとして分散トランザクションで一般に用いられる2相コミットプロトコルを採用し，これを実装した計算資源予約管理機構 PluS を開発した。PluSは、既存のローカルキューイングシステムであるTORQUEもしくはGrid Engine と協調動作し、事前予約機能を提供する．既存ローカルキューイングシステムに事前予約機能を追加する手法としては，1）ローカルキューイングシステムのスケジューリングモジュールを完全に置き換える方法，2）予約をキューとして実現し，外部からキューを操作することで予約を実現する方法，の2つがある．われわれは，この両者に関して予約機能を設計，実装し評価した．その結果，前者はオーバヘッドが少なくポリシ実現の自由度が高いこと，後者は既存スケジューリングモジュール機能の再実装が必要ないため実装コストが小さいことがわかった．</div> </blockquote>



- **ミドルウェア連携による計算・ネットワーク資源の日米間グリッドコアロケーション実験**  <span onmouseover="document.getElementById('hpc0703takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0703takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 林通秋, 築島幸男, 岡本修一, 柳田誠也, 宮本崇弘, 平野章, 鮫島康則, 中田秀基, 谷口篤, 工藤知宏
, *情報処理学会研究報告2007-HPC-109*   , pp. 281-286  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0703takefusa"> グリッドでは，計算資源に関する管理・利用技術は成熟しつつあるものの，ネットワークの帯域を資源として管理する技術は実験段階にあり，特に異なるネットワークドメインに属する拠点間の帯域を自動的に提供するのは非常に困難である．また，グリッドコアロケーションシステムは複数開発されているが，異なるシステム間で連携し，それぞれの管理ドメインの計算・ネットワーク資源を横断的に利用する試みはこれまでない．我々は，ネットワークの帯域を予約するためのインタフェースGNS-WSI を規定することを目的としたG-lambda  プロジェクトを推進しており，複数ドメインに跨るネットワーク資源を確保することを考慮し，新たにGNS-WSI2を規定した．G-lambda が前提とするアーキテクチャでは，グリッド資源スケジューラが複数のネットワークドメインおよび計算資源の資源管理マネージャと連携することにより，ドメインを超えた資源のコアロケーションが可能になる．また，本報告では，米国の Enlightened Computing プロジェクトと共同で行った，ネットワークと計算機資源の同時事前予約実験について述べる．本実験では，日米の複数ドメインに跨る計算資源およびネットワーク資源をミドルウェア連携により事前予約で確保し，動的に構築したグリッド環境上でアプリケーションを実行することに成功した．</div> </blockquote>



- **GNS-WSI2 Grid Network Service - Web Services Interface, version 2**    
Atsuko Takefusa, Michiaki Hayashi, Akira Hirano, Shuichi Okamoto, Tomohiro Kudoh, Takahiro Miyamoto, Yukio Tsukishima, Tomohiro Otani, Hidemoto Nakada, Hideaki Tanaka, Atsushi Taniguchi, Yasunori Sameshima
, *OGF19 GHPN-RG*    , 2007 



- **グローバルスケジューリングのための計算資源予約管理機構** [[Paper](dataDir/hpcs07nakada.pdf)] [[Slides](dataDir/hpcs07nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpcs07nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcs07nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *HPCS 2007 2007年ハイパフォーマンスコンピューティングと計算科学シンポジウム論文集*   , pp. 127-134  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs07nakada"> グリッド上で複数の資源の同時確保を実現する方法のひとつとして事前予約を行う方法がある．これを実現するためには、同時確保の実現に求められる協調プロトコルを実装した事前予約機構を，グリッド上の各資源が持つことが必要となる。われわれは，同時確保のプロトコルとして分散トランザクションで一般に用いられる2相コミットプロトコルを採用し，これを実装した計算資源予約管理機構 PluS を開発した。PluSは、既存のローカルキューイングシステムであるTORQUEもしくはGrid Engine と協調動作し、事前予約機能を提供する．既存ローカルキューイングシステムに事前予約機能を追加する手法としては，1）ローカルキューイングシステムのスケジューリングモジュールを完全に置き換える方法，2）予約をキューとして実現し，外部からキューを操作することで予約を実現する方法，の2つがある．われわれは，この両者に関して予約機能を設計，実装し評価した．その結果，前者はオーバヘッドが少なくポリシ実現の自由度が高いこと，後者は既存スケジューリングモジュール機能の再実装が必要ないため実装コストが小さいことがわかった．</div> </blockquote>



- **異種の複数スケジューラで管理される資源を事前同時予約するグリッド高性能計算の実行環境** [[Paper](dataDir/hpcs07takefusa.pdf)] [[Slides](dataDir/hpcs07takefusa_slide.pdf)]  <span onmouseover="document.getElementById('hpcs07takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpcs07takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 武宮博, 松田元彦, 工藤知宏, 田中良夫, 関口智嗣
, *HPCS 2007 2007年ハイパフォーマンスコンピューティングと計算科学シンポジウム論文集*   , pp. 135-142  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs07takefusa"> グリッドで並列高性能計算を行うには，資源のコアロケーションシステムが異種の複数スケジューラで管理される資源を安全に事前同時予約できることが重要である．本稿ではWSRFに基づくインタフェースを提供するコアロケーションシステムGridarsを改良し， 2相コミットでの事前同時予約手続きを実現した．また，Gridarsの有効性を示すために，計算資源と通信資源のコアロケーションを必要とする実アプリケーションプログラムのためのポータルを Gridarsを用いて構築し，複数の異種スケジューラで管理される日米間に跨るネットワーク，計算資源を用いて実験を行った．この結果，1)Gridarsを用いることで，異種スケジューラで管理される資源群をトランザクションにより安全に確保できること，2)Gridarsを用いたポータルにより，容易にグリッド上での高性能計算環境をユーザに提供できること，を確認した．</div> </blockquote>



- **Design and Implementation of a Local Scheduling System with Advance Reservation for Co-allocation on the Grid** [[Paper](dataDir/cit06nakada.pdf)] [[Slides](dataDir/cit06nakada_slide.pdf)]  <span onmouseover="document.getElementById('cit06nakada').style.display = 'block'"  onmouseout="document.getElementById('cit06nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Atsuko Takefusa, Katsuhiko Ookubo, Makoto Kishimoto, Tomohiro Kudoh, Yoshio Tanaka, Satoshi Sekiguchi
, *Proc. of 2006 IEEE International Conference on Computer and Information Technology*   , pp. 6p  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cit06nakada"> While advance reservation is an essential capability for co-allocating several resources on Grid environments, it is not obvious how it can co-exist with priority-based First Come First Served scheduling, that is widely used as local scheduling policy today. To investigate this problem, we 1) developed a scheduling API in Java for TORQUE, a variant of OpenPBS, that enables users to implement their own schedulers and replace the original scheduling module with them, 2) implemented a prototype scheduler module that has advance reservation capability with the API. We also provide an external interface for the reservation capability based on WSRF to enable co-allocation of resources over the Grid. Using this interface with the job submission module from Globus toolkit 4, users can make reservation for resources and submit jobs over the Grid.</div> </blockquote>



- **グローバルスケジューリングのためのローカル計算資源管理機構**  <span onmouseover="document.getElementById('swopp0608nakada').style.display = 'block'"  onmouseout="document.getElementById('swopp0608nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 岸本誠, 大久保克彦, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-107*   , pp. 55-60  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp0608nakada"> グリッド上で資源の同時確保を実現する方法のひとつとして事前予約を行う方法がある．複数資源の同時予約操作は本質的に分散トランザクションであり，操作失敗時の挙動を保障するためには，スケジューラとローカル資源管理機構の間で適切なプロトコルを用いる必要があり，ローカル資源管理機構がそのプロトコルに対応していなければならない．また，ローカル資源管理機構内部の予約管理機構もプロトコルに対応する必要がある．われわれは，プロトコルとして分散トランザクションで一般に用いられる2相コミットプロトコルを採用し，これを可能にするべく，計算資源上のローカル資源管理機構の予約インターフェイスを設計・実装した．予約インターフェイスはWSRF(Web Services Resource Framework)を基盤プロトコルとし，Globus Toolkit 4 を用いて実装されている．さらにローカル資源管理機構内部で使用する予約管理機構として，TORQUE および GridEngineと協調動作することのできるPluS予約管理機構を改良し，2相コミットの機構を組み込んだ．</div> </blockquote>



- **G-lambda: Coordination of a Grid Scheduler and Lambda Path Service over GMPLS**  <span onmouseover="document.getElementById('fgcs06takefusa').style.display = 'block'"  onmouseout="document.getElementById('fgcs06takefusa').style.display = 'none'">[abst]</span>   
Atsuko Takefusa, Michiaki Hayashi, Naohide Nagatsu, Hidemoto Nakada, Tomohiro Kudoh, Takahiro Miyamoto, Tomohiro Otani, Hideaki Tanaka, Masatoshi Suzuki, Yasunori Sameshima, Wataru Imajuku, Masahiko Jinno, Yoshihiro Takigawa, Shuichi Okamoto, Yoshio Tanaka, Satoshi Sekiguchi
, *FUTURE GENERATION COMPUTER SYSTEMS 22-2006*   , pp. 868-875  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="fgcs06takefusa"> At iGrid2005, we conducted a live demonstration where our Grid scheduling system co-allocated computing and network resources with advance reservation through Web services interfaces using the Grid Resource Scheduler (GRS), the Network Resource Management System (NRM), which is capable of GMPLS network resource management, and a GMPLS-based network test-bed, for the first time. The goal of the G-lambda project is to define a standard Web services interface (GNS-WSI) between GRS and NRM that is acceptable for both application service providers and commercial network operators, and which can be used as a tool for realizing new and emerging commercial services.</div> </blockquote>



- **計算資源とネットワーク資源を同時確保する予約ベースグリッドスケジューリングシステム** [[Paper](dataDir/sacsis06takefusa.pdf)] [[Slides](dataDir/sacsis06takefusa_slide.pdf)]  <span onmouseover="document.getElementById('sacsis06takefusa').style.display = 'block'"  onmouseout="document.getElementById('sacsis06takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田秀基, 工藤知宏, 田中良夫, 関口智嗣
, *先進的計算基盤システムシンポジウム SACSIS 2006*   , pp. 93-100  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis06takefusa"> グリッドで異なる組織に管理される分散した計算資源を用いた高性能大規模計算を実行するには，分散した計算資源とその間の高品質なネットワークを同時に確保することが重要である．本研究では，事前予約により計算資源と高品質ネットワーク資源を同時に確保し，その上でユーザジョブの自動実行を可能にするグリッドスケジューリングシステムを提案・開発した．提案システムはグリッド資源スケジューラ(GRS) と計算資源マネージャ(CRM) からなり，GRS が複数CRM とネットワークキャリアの提供するネットワーク資源管理システムと連携して計算・ネットワーク資源のコアロケーションを実現する．</div> </blockquote>



- **グリッドにおける計算資源 と光パスネットワーク資源のコアロケーション実験**    
竹房あつ子, 林通秋, 長津尚英, 中田秀基, 工藤知宏, 宮本崇弘, 大谷朋広, 田中英明, 鮫島康則, 今宿亙, 神野正彦, 滝川好比郎, 岡本修一, 田中良夫, 関口智嗣
, *先進的計算基盤システムシンポジウムSACSIS2006 論文集（ポスター）*   , pp. 234-235  , 2006 



- **グリッドアプリケーション のためのGMPLSネットワーク資源の管理制御**    
林通秋, 宮本崇弘, 大谷朋広, 田中英明, 竹房あつ子, 中田秀基, 工藤知宏, 鮫島康則, 岡本修一
, *電子通信処理学会 2006総合大会講演論文集*    , 2006 



- **Managing and Controlling GMPLS Network Resources for Grid Applications**  <span onmouseover="document.getElementById('ofc2006-hayashi').style.display = 'block'"  onmouseout="document.getElementById('ofc2006-hayashi').style.display = 'none'">[abst]</span>   
Michiaki Hayashi, Takahiro Miyamoto, Tomohiro Otani, Hideaki Tanaka, Atsuko Takefusa, Hidemoto Nakada, Tomohiro Kudoh, Naohide Nagatsu, Yasunori Sameshima, Shuichi Okamoto
, *Proc. Optical Fiber Communication Conference, 2006*    , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ofc2006-hayashi"> Inter-working between GMPLS network and grid computing application through Web-services interface is demonstrated for the first time. Lambda LSP-based network resource virtualization and scheduling techniques successfully achieves nation-wide grid computing environment with advance reservation operation.</div> </blockquote>



- **事前予約機能を持つローカルスケジューリングシステムの設計と実装** [[Paper](dataDir/hpc0603nakada.pdf)] [[Slides](dataDir/hpc0603nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603nakada').style.display = 'block'"  onmouseout="document.getElementById('hpc0603nakada').style.display = 'none'">[abst]</span>   
中田秀基, 竹房あつ子, 大久保克彦, 岸本誠, 工藤知宏, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-105*   , pp. 217-222  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603nakada"> グリッド上で複数の資源を同時に確保(コアロケーション) するには，各サイトにおける事前予約が不可欠である．現在計算資源の多くでは，プライオリティとFirst Come First Served を組み合わせたスケジューリングポリシが用いられているが，このスケジューリングポリシと事前予約をどのように組み合わせるべきかに関しては，明らかになっていない．われわれは，この問題を検討する研究環境を整備することを目的とし，1) OpenPBS の亜種であるTORQUE のスケジューラモジュールを記述するためのAPI を整備し，2) これを用いて事前予約機能を持つスケジューラモジュールを実装した．さらにWSRF を用いた外部インターフェイスを実装し，Globus Toolkit Ver.4 のGRAMと連動したグリッド環境での予約と実行を実現した．</div> </blockquote>



- **グリッドにおける計算資源と光パスネットワーク資源のコアロケーション実験** [[Paper](dataDir/hpc0603takefusa.pdf)] [[Slides](dataDir/hpc0603takefusa_slide.pdf)]  <span onmouseover="document.getElementById('hpc0603takefusa').style.display = 'block'"  onmouseout="document.getElementById('hpc0603takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 林通秋, 長津尚英, 中田秀基, 工藤知宏, 宮本崇弘, 大谷朋広, 田中英明, 鮫島康則, 今宿亙, 神野正彦, 滝川好比郎, 岡本修一, 田中良夫, 関口智嗣
, *情報処理学会研究報告2006-HPC-105*   , pp. 121-126  , 2006 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0603takefusa"> 産業技術総合研究所，KDDI 研究所，日本電信電話は共同で，ネットワーク資源の事前予約を行うための標準ウェブサービスインタフェースを定めるG-lambda プロジェクトを推進している．このインタフェースの有効性を確認するために，計算資源と光パスネットワーク資源を事前予約によりコアロケーションする実験を，情報通信研究機構の協力を得て行った．本稿では，前提とするコアロケーションシステムモデル，G-lambda プロジェクトにおけるグリッドでのネットワークサービスインタフェースの規定，産総研が開発した計算・ネットワーク資源を同時予約するスケジューラの概要，KDDI 研が開発したGMPLS で制御される光パスネットワークの提供機構の概要と，これらにより実現されたコアロケーションシステムプロトタイプのiGrid2005 での実証実験について報告する．</div> </blockquote>



        
