---
layout: default
---
# Grivon 

- **A Scalable and Distributed Electrical Power Monitoring System Utilizing Cloud Computing**  <span onmouseover="document.getElementById('cute13takano').style.display = 'block'"  onmouseout="document.getElementById('cute13takano').style.display = 'none'">[abst]</span>   
Ryousei Takano, Hidemoto Nakada, Toshiyuki Shimizu, Tomohiro Kudoh
, *The 8th International Conference on Ubiquitous Information Technologies and Applications*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cute13takano"> We propose a scalable and distributed electrical power monitoring system utilizing cloud computing. This system collects power usage at measurement points geographically distributed over different locations, stores data on the cloud and provides a single unified view of power usage through a simple REST API. A system with 620 measurement points covering a server room and a clean room has been successfully installed at our campus, and we have operated it since the third quarter of 2011 to charge electricity bills and evaluate the power efficiency of data processing middleware. We have demonstrated that the proposed system can be smoothly scaled out based on the needs. This result provides an insight that cloud computing makes a power monitoring system elastic and cost-effective.</div> </blockquote>



- **A WAN-optimized Live Storage Migration Mechanism Toward Virtual Machine Evacuation Upon Severe Disasters**  <span onmouseover="document.getElementById('ieice13hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ieice13hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Mauricio Tsugawa, Hidemoto Nakada, Tomohiro Kudoh, Satoshi Itoh
, *IEICE Transactions on Information and Systems, E96D 巻  12 号*   , pp. 2663 - 2674  , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice13hirofuchi"> Wide-area VM migration is a technology with potential to aid IT services recovery since it can be used to evacuate virtualized servers to safe locations upon a critical disaster. However, the amount of data involved in a wide-area VM migration is substantially larger compared to VM migrations within LAN due to the need to transfer virtualized storage in addition to memory and CPU states. This increase of data makes it challenging to relocate VMs under a limited time window with electrical power. In this paper, we propose a mechanism to improve live storage migration across WAN. The key idea is to reduce the amount of data to be transferred by proactively caching virtual disk blocks to a backup site during regular VM operation. As a result of pre-cached disk blocks, the proposed mechanism can dramatically reduce the amount of data and consequently the time required to live migrate the entire VM state. The mechanism was evaluated using a prototype implementation under diﬀerent workloads and network conditions, and we conﬁrmed that it dramatically reduces the time to complete a VM live migration. By using the proposed mechanism, it is possible to relocate a VM from Japan to the United States in just under 40 seconds. This relocation would otherwise take over 1500 seconds, demonstrating that the proposed mechanism was able to reduce the migration time by 97.5%.</div> </blockquote>



- **Cooperative VM Migration: a Symbiotic Virtualization Mechanism by Leveraging the Guest OS Knowledge**  <span onmouseover="document.getElementById('ieice13takano').style.display = 'block'"  onmouseout="document.getElementById('ieice13takano').style.display = 'none'">[abst]</span>   
Ryousei Takano, Hidemoto Nakada, Takahiro Hirofuchi, Yoshio Tanaka, Tomohiro Kudoh
, *IEICE Transactions on Information and Systems, E96D 巻  12 号*   , pp. 2675-2683  , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice13takano"> A virtual machine~(VM) migration is useful for improving flexibility and maintainability in cloud computing environments. However, VM monitor~(VMM)-bypass I/O technologies, including PCI passthrough and SR-IOV, in which the overhead of I/O virtualization can be significantly reduced, make VM migration impossible. This paper proposes a novel and practical mechanism, called Symbiotic Virtualization~(SymVirt), for enabling migration and checkpoint/restart on a virtualized cluster with VMM-bypass I/O devices, without the virtualization overhead during normal operations. SymVirt allows a VMM to cooperate with a message passing layer on the guest OS, then it realizes VM-level migration and checkpoint/restart by using a combination of a user-level dynamic device configuration and coordination of distributed VMMs. We have implemented the proposed mechanism on top of QEMU/KVM and the Open MPI system. All PCI devices, including Infiniband, Ethernet, and Myrinet, are supported without implementing specific para-virtualized drivers; and it is not necessary to modify either of the MPI runtime and applications. Using the proposed mechanism, we demonstrate reactive and proactive FT mechanisms on a virtualized Infiniband cluster. We have confirmed the effectiveness using both a memory intensive micro benchmark and the NAS parallel benchmark.</div> </blockquote>



- **異種クラスタを跨がる仮想マシンマイグレーション機構**  <span onmouseover="document.getElementById('swopp13takano').style.display = 'block'"  onmouseout="document.getElementById('swopp13takano').style.display = 'none'">[abst]</span>   
高野 了成, 中田 秀基, 広渕 崇宏, 田中 良夫, 工藤 知宏 
, *研究報告システムソフトウェアとオペレーティング・システム（OS）2013-OS-126*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp13takano"> 災害復旧 (DR) や事業継続計画 (BCP) の観点から、クラウド間を跨がった仮想計算機マイグレーションの重要性が高まっている。しかし、ヘテロなクラウド環境におけるマイグレーション技術に関して、今まで十分に議論されていない。本論文では、プライベートクラウドとパブリッククラウドなど、通信デバイスが異なるヘテロなクラウド環境間で仮想クラスタをマイグレーションする際の問題点を明らかにし、解決策を提案する。本提案の特長は、仮想クラスタを構成するノード VM に対して、実行環境の変化に応じて、最良の通信性能を達成する通信デバイスをアプリケーションから透過的に選択し、利用できることである。インターコネクト透過型マイグレーションである Ninja migration、OpenFlow を用いたエッジオーバレイネットワーク、ストレージマイグレーションなどの要素技術から成るプロトタイプシステムを実装した。このシステムを用いて、産総研の Infiniband クラスタと商用パブリッククラウド間で仮想クラスタをマイグレーションできることを確認した。</div> </blockquote>



- **Power Efficient Virtual Machine Packing for Green Datacenter**  <span onmouseover="document.getElementById('IJNGC13nakada').style.display = 'block'"  onmouseout="document.getElementById('IJNGC13nakada').style.display = 'none'">[abst]</span>   
Satoshi Takahashi, Atsuko Takefusa, Maiko Shigeno, Hidemoto Nakada, Tomohiro Kudoh, Akiko Yoshise
, *International Journal of Next-Generation Computing, Vol.4 No. 2*   , pp. 162-181  , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="IJNGC13nakada"> Cloud computing is now considered to be a new computing paradigm to provide scalable Infrastructure, Platform and Software as a Service via the Internet. While, the diffusion of Cloud computing is expected to cause an explosive increase in power consumption for IT resources in data centers. Virtual Machine(VM)-based flexible capacity management is an effective scheme to reduce total power consumption in the data centers. However, there remain the following issues, trade-off between power-saving and user experience, decision on VM packing plans within a feasible calculation time, and collision avoidance for multiple VM live migration processes. In order to resolve these issues, we propose two VM packing algorithms, a matching-based (MBA) and a greedy-type heuristic (GREEDY). MBA enables to decide an optimal plan in polynomial time, while GREEDY is an aggressive packing approach faster than MBA. We investigate the basic performance and the feasibility of proposed algorithms under both artificial and realistic simulation scenarios, respectively. The basic performance experiments show that the algorithms reduce total power consumption by between 18% and 50%, and MBA makes suitable VM packing plans within a feasible calculation time. The feasibility experiments employ two power consumption models, one is the linear model and the other is piecewise linear model. In the linear model, the feasibility experiments show that the reduction ratio of total power consumption observed with MBA is smaller than that of GREEDY, but the performance degradation of MBA is less than that of GREEDY. In the piecewise-linear model, the feasibility experiments show that MBA investigates more reducing power consumption than GREEDY. The performance degradation of MBA is also less than GREEDY.</div> </blockquote>



- **Ninja Migration: An Interconnect-transparent Migration for Heterogeneous Data Centers**  <span onmouseover="document.getElementById('hpgcc13takano').style.display = 'block'"  onmouseout="document.getElementById('hpgcc13takano').style.display = 'none'">[abst]</span>   
Ryousei Takano, Hidemoto Nakada, Takahiro Hirofuchi, Yoshio Tanaka, Tomohiro Kudoh
, *High-Performance Grid and Cloud Computing Workshop*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpgcc13takano"> We propose an interconnect-transparent migration mechanism to simultaneously migrate multiple co-located VMs between data centers equipped with different interconnect devices. Our implementation of the proposed mechanism, called Ninja migration, is achieved by cooperation between a VMM and an MPI runtime system on the guest OS.
We demonstrate fallback and recovery operations on a high performance computing workload using the proposed mechanism. We have confirmed that 1) the proposed mechanism has no performance overhead during normal operations, and 2) MPI processes running on distributed VMs can migrate between an Infiniband cluster and an Ethernet cluster without restarting the processes.</div> </blockquote>



- **IT VIrtualization for Disaster Mitigation and Recovery**  <span onmouseover="document.getElementById('jrapidsymposium').style.display = 'block'"  onmouseout="document.getElementById('jrapidsymposium').style.display = 'none'">[abst]</span>   
Tadahiro Hirofuchi, Hidemoto Nakada, Ryousei Takano, Mauricio Tsugawa, Renato Figueiredo, Jose Fortes
, *J-RAPID Symposium*    , 2013 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jrapidsymposium"> In today’s society, Information Technology (IT) is applied in many critical infrastructures and systems, thus it is key for IT services to quickly recover from damages caused by catastrophic events. This project conducted research on the use of virtualization technologies to architect IT infrastructures resilient to partial physical infrastructure failures. The key idea is to quickly move IT services damaged by a disaster to a safe location, taking advantage of machine and network virtualization mechanisms that allow the migration of an entire IT infrastructure from one geographical location to another. This approach has the potential to be substantially cost efficient, application independent, and offer lower downtime of services compared to traditional disaster recovery (DR) mechanisms, which requires (a) applications to be modified for a particular DR implementation and (b) expensive on-line replication of data. Given the scale in which IT services are deployed, it is prohibitively expensive to protect all of them through traditional DR services – thus, research for low cost alternatives that can be invoked on demand is needed.</div> </blockquote>



- **Virtual Machine Packing Algorithms for Lower Power Consumption**  <span onmouseover="document.getElementById('cloudcom12takahashi').style.display = 'block'"  onmouseout="document.getElementById('cloudcom12takahashi').style.display = 'none'">[abst]</span>   
Satoshi Takahashi, Atsuko Takefusa, Maiko Shigeno, Hidemoto Nakada, Tomohiro Kudoh, Akiko Yoshise
, *IEEE CloudCom 2012*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cloudcom12takahashi"> Cloud computing is now considered to be a new computing paradigm to provide scalable Infrastructure, Platform and Software as a Service via the Internet. While, the diffusion of Cloud computing is expected to cause an explosive increase in power consumption for IT resources in data centers. Virtual Machine(VM)-based flexible capacity management is an effective scheme to reduce total power consumption in the data centers. However, there remain the following issues, tradeoff between power-saving and user experience, decision on VM packing plans within a feasible calculation time, and collision avoidance for multiple VM  live migration processes. In order to resolve these issues, we propose two VM packing algorithms, a matching-based (MBA) and a greedy-type heuristic (GREEDY). MBA enables to decide an optimal plan in polynomial time, while GREEDY is an aggressive packing approach faster than MBA. We investigate basic performance and the feasibility of the proposed algorithms under both artificial and realistic simulation scenarios, respectively. In the feasibility experiments, we use an actual trace data set from the 648-node T2K-Tsukuba supercomputer. The basic performance experiments show that the algorithms reduce total power consumption by between 18% and 50%, and MBA makes suitable VM packing plans within a feasible calculation time. The feasibility experiments show that the proposed algorithms are feasible to make packing plans for an actual supercomputer, and GREEDY has the advantage in power consumption, but MBA shows the better  performance in user experience.</div> </blockquote>



- **Virtual Machine Packing Algorithms for Lower Power Consumption**  <span onmouseover="document.getElementById('sc12takahashi_poster').style.display = 'block'"  onmouseout="document.getElementById('sc12takahashi_poster').style.display = 'none'">[abst]</span>   
Satoshi Takahashi, Atsuko Takefusa, Maiko Shigeno, Hidemoto Nakada, Tomohiro Kudoh, Akiko Yoshise
, *SC12 (poster)*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sc12takahashi_poster"> Cloud providers need to design their data center capacity to provide IT resources that can process assumed ’peak’ service loads, because user experience will decrease if the capacity is insufﬁcient. Therefore the accumulated power consumption of idle servers is wasted because their power consumption may equal about 50% of that of a saturated server. One of the key technologies used to reduce the total power consumption is a Virtual Machine (VM)-based ﬂexible capacity management which can consolidate multiple VMs onto a few physical machines (PMs) and allow other PMs to be put in ’stand-by’mode. In order to avoid degradation of service performance, stand-by PMs will be resumed when service loads increase. There are VM packing issues for effective VM-based server consolidation: 1) Trade-off between power consumption and performance: We have to consider both the performance metrics in order to investigate the feasibility of packing algorithms. 2) VM packing planning within a feasible calculation time: A VM packing problem is an N P-complete problem. 3) Collision of multiple live migrations: VM live migration causes burst transfer of a VM image in the background after an ostensible migration. To address the above issues, we propose VM packing algorithms that aim to reduce power consumption, assure the user experience in terms of p</div> </blockquote>



- **省電力化のためのマッチングに基づく仮想計算機パッキングアルゴリズム**  <span onmouseover="document.getElementById('acs5-5takahashi').style.display = 'block'"  onmouseout="document.getElementById('acs5-5takahashi').style.display = 'none'">[abst]</span>   
高橋 里司, 竹房 あつ子, 繁野 麻衣子, 中田 秀基, 工藤 知宏, 吉瀬 章子
, *情報処理学会論文誌 コンピューティングシステム Vol.5 No.5*   , pp. 33-42  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs5-5takahashi"> データータセンタでの消費電力低減の手法として，低負荷の仮想計算機(VM)を高速にマイグレーションして集約し，使用していない物理計算機を省消費電力モードで運用する方法がある．これを実現するには，消費電力を抑えつつユーザ体験の劣化を防ぐ，負荷が変動するVM群を現実的な時間で再配置する，再配置時のマイグレーションによる通信衝突を考慮する，という課題がある．本研究では，ユーザ体験を劣化させることなく省電力化を図る仮想計算機パッキング問題に対するマッチングべースアルゴリズムを提案，評価する．提案手法では，再配置時に1つの物理計算機が送受信できるVM数を制限し，VMを送受信する物理計算機の組合せをグラフのマッチングで表すことで，多項式時間で適切な再配置プランニングを可能にする．評価実験では，マッチングを用いた提案手法，仮想計算機パッキング問題を0-1整数計画問題として定式化して最適化ソルバを用いる手法とグリーディな手法に対して，消費電力削減効果，計算時間，ユーザ体験の劣化を比較する．この評価実験から，1)パッキングをしない場合より18%から50%の消費電力が削減できる，2)マッチングべースアルゴリズムにより，現実的な計算時間で適切な再配置を行うことができる，3)ユーザ体験は消費電力の削減効果に反比例する傾向があるが，再配置によりほぼ改善できる，ことが示される．</div> </blockquote>



- **Cooperative VM Migration for a Virtualized HPC Cluster with VMM-Bypass I/O devices**  <span onmouseover="document.getElementById('eScience12takano').style.display = 'block'"  onmouseout="document.getElementById('eScience12takano').style.display = 'none'">[abst]</span>   
Ryousei Takano, Hidemoto Nakada, Takahiro Hirofuchi, Yoshio Tanaka, Tomohiro Kudoh
, *Proceedings of IEEE International Conference on eScience (eScience 2012)*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="eScience12takano"> An HPC cloud, a ﬂexible and robust cloud computing service specially dedicated to high performance computing, is a promising future e-Science platform. In cloud computing, virtualization is widely used to achieve ﬂexibility and security. Virtualization makes migration or checkpoint/restart of computing elements (virtual machines) easy, and such features are useful for realizing fault tolerance and server consolidations. However, in widely used virtualization schemes, I/O devices are also virtualized, and thus I/O performance is severely degraded. To cope with this problem, VMM-bypass I/O technologies, including PCI passthrough and SR-IOV, in which the I/O overhead can be signiﬁcantly reduced, have been introduced. However, such VMM-bypass I/O technologies make it impossible to migrate or checkpoint/restart virtual machines, since virtual machines are directly attached to hardware devices. This paper proposes a novel and practical mechanism, called Symbiotic Virtualization (SymVirt), for enabling migration and checkpoint/restart on a virtualized cluster with VMM-bypass I/O devices, without the virtualization overhead during normal operations. SymVirt allows a VMM to cooperate with a message passing layer on the guest OS, then it realizes VM-level migration and checkpoint/restart by using a combination of a PCI hotplug and coordination of distributed VMMs. We have implemented the proposed mechanism on top of QEMU/KVM and the Open MPI system. All PCI devices, including Inﬁniband and Myrinet, are supported without implementing speciﬁc para-virtualized drivers; and it is not necessary to modify either of the MPI runtime and applications. Using the proposed mechanism, we demonstrate reactive and proactive FT mechanisms on a virtualized Inﬁniband cluster. We have conﬁrmed the effectiveness using both a memory intensive micro benchmark and the NAS parallel benchmark. Moreover, we also show that postcopy live migration enables us to reduce the down time of an application as the memory footprint increases.</div> </blockquote>



- **仮想マシンに対して透過的なClient Mobile IPv6 トンネリング機構**  <span onmouseover="document.getElementById('ieice12hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ieice12hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田 秀基, 伊藤智, 関口 智嗣
, *電子情報通信学会論文誌　Ｂ　通信*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice12hirofuchi"> 我々は，データセンタの運用柔軟性を向上させるため，仮想マシン（VM）の広域ライブマイグレーションに注目している．例えば，電力需要が逼迫した際に一部の仮想マシンを一時的に遠隔拠点に待避してサービスを継続できる．このときゲストOS がIP アドレスを維持したまま透過的に通信を継続できる必要があり，我々はMobile IPv6（MIPv6）技術に着目してきた．しかし，MIPv6 は強力なトンネリング機構を備えるものの，既存のMIPv6 技術をそのままマイグレーションに用いることは難しい．ゲストOS を改変することなく透過的にトンネリングを可能とし，VM 一つからでも柔軟にマイグレーションできる機構が必要である．そこで，我々はゲストOS にとって透過的なMIPv6 トンネリング機構（Kagemusha）を提案する．提案機構はホストOS 上で動作し，Client MIPv6 のシグナリングやトンネリングをゲストOS に対して透過的に行う．ゲストOS にMIPv6 に関するプログラムを導入する必要はない．さらに，既存のHome Agent（HA）や仮想マシンモニタを一切変更することなくそのまま利用できる．プロトタイプ実装を用いて評価実験を行った．その結果，提案機構はHA と正しく通信でき，そのトンネリングオーバーヘッドはわずかであることが確認できた．またQemu/KVM のライブマイグレーションと正しく連係動作し，訪問先ネットワークにおいてもゲストOS に対して透過的なネットワーク接続を提供できた．このときマイグレーションにともなうダウンタイムの増加は評価実験環境において1 秒程度であった．</div> </blockquote>



- **On the Use of Virtualization Technologies to Support Uninterrupted IT Services**  <span onmouseover="document.getElementById('icc12tsugawa').style.display = 'block'"  onmouseout="document.getElementById('icc12tsugawa').style.display = 'none'">[abst]</span>   
Mauricio Tsugawa, Renato Figueiredo, Jose Fortes, Takahiro Hirofuchi, Hidemoto Nakada, Ryousei Takano
, *IEEE International Conference on Communications  2012*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="icc12tsugawa"> Virtualized IT infrastructures combined with virtual machine migration technologies have a potential to support IT services that are resilient to partial physical infrastructure failures caused by extreme events. This paper experimentally evaluates the migration of multiple VMs across long geographical distances – an activity that is required to move virtualized IT systems from a disaster site to a safe location. Taking into account the resource availability parameters observed after the Great East Japan Earthquake, experimental results show that if (1) service downtime in the order of minutes is acceptable, (2) VMs can be kept with small storage footprint, and (3) power and network are available for tens of minutes, it is possible to migrate tens of VMs from damaged sites to a very distant stable location.</div> </blockquote>



- **省電力化のためのマッチングに基づく仮想計算機パッキングアルゴリズム** [[Paper](dataDir/sacsis12takahashi.pdf)]  <span onmouseover="document.getElementById('sacsis12takahashi').style.display = 'block'"  onmouseout="document.getElementById('sacsis12takahashi').style.display = 'none'">[abst]</span>   
高橋 里司, 竹房 あつ子, 繁野 麻衣子, 中田 秀基, 工藤 知宏, 吉瀬 章子
, *SACSIS2012予稿集*   , pp. 333-340  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis12takahashi"> データセンターでの消費電力低減の手法として,低負荷の仮想計算機を高速にマイグレーションし て集約し,使用していない物理計算機を省消費電力モードで運用する方法がある.これを実現するに は,消費電力を抑えつつユーザ体験の劣化を防ぐ,負荷が変動する VM 群を現実的な時間で再配置す る,再配置時のマイグレーションによる通信衝突を考慮する,という課題がある.本研究では,ユー ザ体験を劣化させることなく省電力化を図る仮想計算機パッキング問題に対するマッチングベースア ルゴリズムを提案,評価する.提案手法では,再配置時に 1 つの計算機が送受信する VM 数を制限し, VM と計算機の組み合わせをグラフのマッチングで表すことで,多項式時間で適切な再配置プランニ ングを可能にする.評価では,提案手法を 0-1 整数計画問題として定式化して最適化ソルバを用いる 手法とグリーディな手法で,消費電力削減効果,計算時間,ユーザ体験の劣化について比較する.実 験から,1) パッキングをしない場合より 18%から 50%の消費電力が削減できる,2) マッチングベー スアルゴリズムにより,現実的な計算時間で適切な再配置を行うことができる,3) ユーザ体験は消費 電力の削減効果に反比例する傾向があるが,再配置によりほぼ改善できることを示す.</div> </blockquote>



- **仮想マシンの超広域ライブマイグレーションにむけたベストエフォート型状態同期機構の試作**  <span onmouseover="document.getElementById('os1205hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('os1205hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, マウリシオツガワ, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2012-OS-121*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="os1205hirofuchi"> 仮想マシンの遠隔ライブマイグレーションを用いれば、災害発生時にサーバを安全な遠隔拠点に待 避できる。しかし、ライブマイグレーションは大量のデータ転送を伴うため、ネットワーク帯域が限られる WAN 環境において、災害発生直後の限られた猶予時間内に再配置を完了することが難しい。本稿では、広域ライブマイグレーション時間を短縮するため、仮想マシンの実行状態をベストエフォートで事前に同期する手法を提案する。平時から仮想ディスクの状態を待避先拠点とできる限り同期しておき、ライブマイグレーションを実行する際にはその差分のみを転送する。マイグレーションに伴うデータ転送量およびマイグレーション時間を大幅に削減できる。同期データに対して世代管理を行うことで、可用帯域が許す範囲での部分的な同期を可能にし、一時的な通信の断絶に対しても再び途中から同期を再開可能にしている。提案機構のプロトタイプを実装し、日米間のネットワークを用いて基礎的な評価実験を行った。仮想マシンの実行状態全体を約30秒で再配置できた。提案機構を用いない場合(約1時間)よりも大幅に待避時間を短縮できた。</div> </blockquote>



- **Kagemusha: A Guest-Transparent Mobile IPv6 Mechanism for Wide-Area Live VM Migration** [[Paper](dataDir/cloudman12hirofuchi.pdf)]  <span onmouseover="document.getElementById('cloudman12hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('cloudman12hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hidemoto Nakada, Satoshi Itoh, Satoshi Sekiguchi
, *3rd International Workshop on Cloud Management (CloudMan 2012)*    , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cloudman12hirofuchi"> We are developing a wide-area live migration mechanism that allows dynamic load balancing of virtual machines (VMs) among datacenters. We consider that Mobile IPv6 (MIPv6) is a promising technology to support transparent network reachability when VMs migrate to foreign networks. Existing MIPv6 mecha- nisms, however, are not suitable for VM migrations; real-world IaaS datacenters require guest-transparent and exible tunneling mechanisms, which are not provided by existing MIPv6 programs. In this paper, we propose a guest-transparent MIPv6 tunneling mechanism (Kagemusha), which performs Client MIPv6 signaling and tunneling on a host operating system. No MIPv6 program is required to be installed into a guest operating system. The proposed system is fully compatible with existing home agents (HAs). It basically works with any virtual machine monitors. Through experiments, we confirmed that our prototype system successfully established MIPv6 tunnels with HAs, and its performance overhead was negligible for normal use cases. We also confirrmed that the prototype system successfully worked with live migrations; the downtime of migration increased only by several hundred milliseconds.</div> </blockquote>



- **Reactive Cloud: Consolidating Virtual Machines with Postcopy Live Migration**  <span onmouseover="document.getElementById('acs1203hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('acs1203hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hidemoto Nakada, Satoshi Itoh, Satoshi Sekiguchi
, *IPSJ Transaction Computing System (ACS) Vol.5 No.2*   , pp. 86-98  , 2012 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs1203hirofuchi"> Dynamic consolidation of virtual machines (VMs) through live migration is a promising technology for IaaS datacenters. VMs are dynamically packed onto fewer server nodes, thereby eliminating excessive power consumption. Existing studies on VM consolidation, however, are based on precopy live migration, which requires dozens of seconds to switch the execution hosts of VMs. It is difficult to optimize VM locations quickly on sudden load changes, resulting in serious violations of VM performance criteria. In this paper, we propose an advanced VM consolidation system exploiting postcopy live migration, which greatly alleviates performance degradation. VM locations are reactively optimized in response to ever-changing resource usage. Sudden overloading of server nodes are promptly resolved by quickly switching the execution hosts of VMs. We have developed a prototype of our consolidation system and evaluated its feasibility through experiments. We confirmed that our consolidation system achieved a higher degree of performance assurance than using precopy migration. Our micro benchmark program, designed for the metric of performance assurance, showed that performance degradation was only 12% or less, even for memory-intensive workloads, which was less than half the level of using precopy live migration. The SPECweb benchmark showed that performance degradation was approximately 10%, which was greatly alleviated from the case of using precopy live migration (21%).</div> </blockquote>



- **仮想マシンの広域ライブマイグレーションを実現するゲスト透過なMobile IPv6 トンネリング機構** [[Paper](dataDir/ic11hirofuchi.pdf)]  <span onmouseover="document.getElementById('ic11hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ic11hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *インターネットコンファレンス 2011 (IC2011) 論文集*   , pp. 101-110  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ic11hirofuchi"> 我々は、データセンタの運用柔軟性を向上させるため、仮想マシン(VM)の広域ライブマイグレーションに注目 している。例えば、電力需要が逼迫した際に一部の仮想マシンを一時的に遠隔拠点に待避してサービスを継続でき る。このときゲスト OS が IP アドレスを維持したまま透過的に通信を継続できる必要があり、我々は Mobile IPv6 (MIPv6)技術に着目してきた。しかし、MIPv6 は強力なトンネリング機構を備えるものの、既存の MIPv6 技術を そのままマイグレーションに用いることは難しい。ゲスト OS を改変することなく透過的にトンネリングを可能と し、VM 一つからでも柔軟にマイグレーションできる機構が必要である。そこで、我々はゲスト OS にとって透過的 な MIPv6 トンネリング機構(Kagemusha)を提案する。提案機構はホスト OS 上で動作し、Client MIPv6 のシ グナリングやトンネリングをゲスト OS に対して透過的に行う。ゲスト OS に MIPv6 に関するプログラムを導入す る必要はない。さらに、既存の Home Agent(HA)や仮想マシンモニタを一切変更することなくそのまま利用でき る。プロトタイプ実装を用いて評価実験を行った。その結果、提案機構は HA と正しく通信でき、そのトンネリングオーバーヘッドはわずかであることが確認できた。また Qemu/KVM のライブマイグレーションと正しく連係動 作し、移動先ネットワークにおいてもゲスト OS に対して透過的なネットワーク接続を提供できた。このときマイグレーションにともなうダウンタイムの増加はわずか数百 ms にとどまることが確認できた。</div> </blockquote>



- **ゲスト透過なMobile IPv6トンネリング機構(Kagemusha)を用いた仮想マシンの広域ライブマイグレーション** [[Paper](dataDir/ic11hirofuchi-demo.pdf)]    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *インターネットコンファレンス 2011 (IC2011) デモ*   , pp. 139-140  , 2011 



- **省電力化にむけた仮想計算機パッキングアルゴリズムの提案**  <span onmouseover="document.getElementById('cpsy1107-takefusa').style.display = 'block'"  onmouseout="document.getElementById('cpsy1107-takefusa').style.display = 'none'">[abst]</span>   
竹房あつ子, 中田 秀基, 広渕崇宏, 伊藤智, 関口智嗣
, *信学技報, Vol.111, No.163, CPSY2011-9-CPSY2011-24*   , pp. 73-78  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cpsy1107-takefusa"> データセンターでの消費電力削減手法の一つとして、仮想計算機（VM）を適宜マイグレーションして使用していない物理計算機を低消費電力状態でスタンバイさせる方法が考えられる．これを実現するには，マイグレーション時の通信衝突を考慮しつつ負荷に応じてVMの配置を決定（仮想計算機パッキング）する手法が必要である．本研究では，通信衝突を考慮したVMパッキングアルゴリズムとして，0-1整数計画法を応用した手法（IP）とグリーディな手法（Greedy）を提案する．評価では，総消費電力量，ユーザ体験の劣化，スケジューリングに要する時間を比較し，シミュレーションから以下が示された．1) GreedyとIPにより消費電力の大幅な削減が可能である．2) ユーザ体験の劣化は消費電力削減効果に反比例するが，再配置により解消できる．3) Greedyは高速かつリーズナブルな再配置が可能であり，IPはリアルタイム性を確保しつつより消費電力削減効果の高い再配置が可能である．</div> </blockquote>



- **Reactive Consolidation of Virtual Machines Enabled by Postcopy Live Migration**  <span onmouseover="document.getElementById('vtdc11hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('vtdc11hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hidemoto Nakada, Satoshi Itoh, Satoshi Sekiguchi
, *VTDC11 - The 5th International Workshop on Virtualization Technologies in Distributed Computing*   , pp. 11-18  , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="vtdc11hirofuchi"> Dynamic consolidation of virtual machines (VMs) through live migration is a promising technology for IaaS datacenters. VMs are dynamically packed onto fewer server nodes, thereby eliminating excessive power consumption. Existing studies on VM consolidation, however, are based on precopy live migration, which requires dozens of seconds to switch the execution hosts of VMs. It is difficult to optimize VM locations quickly on sudden load changes, resulting in serious violations of VM performance criteria. In this paper, we propose an advanced VM consolidation system exploiting postcopy live migration, which greatly alleviates performance degradation. VM locations are reactively optimized in response to ever-changing resource usage. Sudden overloading of server nodes are promptly resolved by quickly switching the execution hosts of VMs. We have developed a prototype of our consolidation system and evaluated its feasibility through experiments. Our results show that our consolidation system achieved a higher degree of performance assurance than using precopy migration. Performance degradation is 12% or less, even for memory-intensive workloads, which is less than half the level using precopy migration.</div> </blockquote>



- **Condor VM ユニバースを利用した HPC Cloud の試作**  <span onmouseover="document.getElementById('zen73futatsuki').style.display = 'block'"  onmouseout="document.getElementById('zen73futatsuki').style.display = 'none'">[abst]</span>   
二木邦尚, 田中良夫, 池上努, 中田秀基, 竹房あつ子
, *情報処理学会 第73回全国大会予稿集*    , 2011 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen73futatsuki"> スーパーコンピュータの性能向上は目覚ましく,近い将 来数百 TFlops から数十 PFlops 規模のスパコンが HPC インフラとして大学,研究所やデータセンターなど複数 組織に次々と導入されていく事が予想される.多組織の スパコンを有効活用して科学技術や産業の発展を促進す るためには,ネットワークを介してこれらのスパコンを 容易に利用する環境の構築が必要である.グリッドコン ピューティング [1] はそのための要素技術を提供するが, アプリケーション配備の際に組織毎に異なる計算環境へ の対応に手間がかかるといった問題がある.</div> </blockquote>



- **複数拠点にまたがるe-Science アプリケーション環境構築を目的としたソフトウェア導入・管理機構**  <span onmouseover="document.getElementById('ieice10hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ieice10hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 横井威, 江原忠士, 谷村勇輔, 小川宏高, 中田秀基, 工藤知宏, 田中良夫, 伊藤智, 関口智嗣
, *電子情報通信学会和文論文誌, Vol.J93-D, No.10*   , pp. 2197-2208   , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice10hirofuchi"> グリッド技術が発展するとともに，複数拠点の計算機資源を用いた科学技術計算が一般的になりつつある．しかし，異なる組織に属する拠点に対してグリッドミドルウェアや科学技術計算プログラムを導入することは容易ではなく，セットアップや管理に多くの労力を割かざるを得ない現状がある．そこで本論文では，複数拠点にまたがる計算環境を迅速に構築し，統一的に管理する機構を新たに提案する．複数拠点の計算資源をもとに仮想計算機からなるクラスタを構築し，その内部を既存のクラスタ管理技術を利用して透過的に管理する．すべての仮想計算機はVLANやEthernet VPNによって作り出した拠点横断的な管理用内部ネットワークに接続されており，既存のクラスタ管理システムによってソフトウェア導入やノード管理を統一的に行うことができる．パッケージキャッシュ機構を組み合わせることにより，ネットワーク遅延や帯域の制限が存在するWAN環境においても，安定したソフトウェア導入と運用が可能になる．評価実験や実証実験を通して，複数の遠隔拠点に対してソフトウェアを迅速に一斉導入し，既存のクラスタ管理の枠組みで運用可能であることを確認した．</div> </blockquote>



- **Eliminating Datacenter Idle Power with Dynamic and Intelligent VM Relocation**  <span onmouseover="document.getElementById('dcai10hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('dcai10hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hidemoto Nakada, Hirotaka Ogawa, Satoshi Itoh, Satoshi Sekiguchi
, *Distributed Computing, Artificial Intelligence, Bioinformatics, Soft Computing, and Ambient Assisted Living (Proceedings of International Symposium on Distributed Computing and Artificial Intelligence 2009)*   , pp. 645-648  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dcai10hirofuchi"> We are developing an advanced IaaS (Infrastructure-as-a-Service) datacenter management system that dynamically minimizes running physical servers depending on resource utilization. The management system periodically monitors the loading of a datacenter, and dynamically repacks virtual machines (VMs) into optimal physical servers. Live migration of VMs and the standby mode of physical servers are automatically orchestrated by a genetic algorithm (GA) engine. A preliminary experiment showed that our first prototype system correctly worked for a proof-of-concept datacenter.</div> </blockquote>



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



- **Enabling Greener Cloud Datacenters with Advanced Virtualization Technology**    
Takahiro Hirofuchi, Hidemoto Nakada, Satoshi Itoh, Satoshi Sekiguchi
, *The 10th IEEE/ACM International Conference on Cluster, Cloud and Grid Computing (CCGrid2010) (Poster)*    , 2010 



- **Enabling Instantaneous Relocation of Virtual Machines with a Lightweight VMM Extension**  <span onmouseover="document.getElementById('ccgrid10hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('ccgrid10hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hidemoto Nakada, Satoshi Itoh, Satoshi Sekiguchi
, *The 10th IEEE/ACM International Conference on Cluster, Cloud and Grid Computing (CCGrid2010)*   , pp. 73-83  , 2010 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ccgrid10hirofuchi"> We are developing an efficient resource management system with aggressive virtual machine (VM) relocation among physical nodes in a data center. Existing live migration technology, however, requires a long time to change the execution host of a VM, it is difficult to optimize VM packing on physical nodes dynamically, corresponding to ever-changing resource usage. In this paper, we propose an advanced live migration mechanism enabling instantaneous relocation of VMs. To minimize the time needed for switching the execution host, memory pages are transferred after a VM resumes at a destination host. A special character device driver allows transparent memory page retrievals from a source host for the running VM at the destination. In comparison with related work, the proposed mechanism supports guest operating systems without any modifications to them (i.e, no special device drivers and programs are needed in VMs). It is implemented as a lightweight extension to KVM (Kernel-based Virtual Machine Monitor). It is not required to modify critical parts of the VMM code. Experiments were conducted using the SPECweb2005 benchmark. A running VM with heavily-loaded web servers was successfully relocated to a destination within one second. Temporal performance degradation after relocation was resolved by means of a precaching mechanism for memory pages. In addition, for memory intensive workloads, our migration mechanism moved all the states of a VM faster than existing migration technology.</div> </blockquote>



- **Contribution of Virtualization Technologies to Reducing Data Center Power Consumption**    
Satoshi Itoh, Hidemoto Nakada, Takahiro Hirofuchi, Hirotaka Ogawa, Satoshi Sekiguchi
, *The 6th International Symposium on Environmentally Conscious Design and Inverse Manufacturing (EcoDesign2009)*   , pp. 6p  , 2009 



- **仮想マシンの瞬間的な実行ホスト切り替えを可能とする ポストコピー型ライブマイグレーション機構**    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *第21回コンピュータシステム・シンポジウム(ComSys2009)*    , 2009 



- **瞬間的な実行ホスト切り替えを可能とする仮想マシンの高速ライブマイグレーション機構**    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *日本ソフトウェア科学会研究会資料シリーズNo.62, 日本ソフトウェア科学会, インターネットカンファレンス2009*   , pp. 57-66  , 2009 



- **瞬間的な実行ホスト切り替えを可能とする仮想マシンの高速ライブマイグレーション機構**    
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *日本ソフトウェア科学会研究会資料シリーズNo.62, 日本ソフトウェア科学会, インターネットカンファレンス2009*   , pp. 122  , 2009 



- **仮想計算機メモリの遅延再配置による高速ライブマイグレーション**  <span onmouseover="document.getElementById('swopp09-hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('swopp09-hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2009-OS-112*    , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp09-hirofuchi"> 仮想計算機 （VM）のライブマイグレーション機能は有用であるものの，負荷バランスのため広く利用されているとは言い難い．一般的なライブマイグレーション手法は，VM のメモリをすべて転送してから実行ホストを切り替えるので時間がかかる．結果，負荷バランスにも長時間を要してしまい，過負荷状態をすぐに解消できない．そこで，我々は，迅速な実行ホストの切り替えを可能とする，新たなライブマイグレーション機構を提案する．VM メモリを実行ホスト切り替え後からオンデマンドに転送することで，約 1 秒程度で稼動ホストの変更を実現できる．既存の実装と比較して，仮想計算機モニタへの変更が少なくゲスト OS への改変が不要である点に優位性がある．プロトタイプを実装してオンデマンドなメモリアクセスが正しく動作することを確認した．</div> </blockquote>



- **仮想計算機遠隔ライブマイグレーションのための 透過的なストレージ再配置機構**  <span onmouseover="document.getElementById('acs26hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('acs26hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 小川宏高, 中田秀基, 伊藤智, 関口智嗣
, *情報処理学会論文誌：コンピューティングシステム, Vol.2, No.SIG2 (ACS26)*   , pp. 152-165  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs26hirofuchi"> 計算機センタやデータセンタの計算機資源の運用効率を高めるために,仮想計算機とそのライブマイグレーション技術が注目されている。仮想計算機を遠隔拠点に対して動的に再配置できれば,資源運用の柔軟性向上や省電力化に寄与すると考えられる。しかし,LAN環境を想定した既存の仮想計算機技術ではストレージアクセス手法に問題をかかえており,WAN環境においてライブマイグレーションを効率的に行うことが困難である。そこで本研究では,周辺機器を含めた仮想計算機の実行環境全体の移動を可能にするために,仮想計算機ストレージの透過的な再配置機構を提案する。提案機構はブロックレベルのストレージI/Oプロトコルに対するターゲットサーバとして振る舞い,ライブマイグレーションの際には仮想計算機の動作に支障を与えることなく透過的に仮想ディスクの拠点間再配置を完了する。その評価として,提案手法の基本的なI/O特性を明らかにしたうえで,実アプリケーションを想定した実験を行った。提案手法においては,オンデマンドなブロック再配置機構のみでは未再配置ブロックの読み込みが遅く,大量のファイルを対象としてランダムに同期I/Oを行うメールサーバ型アプリケーションにおいてはボトルネックとなりうる。しかし,同時並行的に動作する先読み的なブロック再配置機構により,可用WAN帯域を利用して効率的にデータが再配置され性能低下が緩和されることが分かった。</div> </blockquote>



- **A Live Storage Migration Mechanism over WAN and its Performance Evaluation**  <span onmouseover="document.getElementById('evgm09hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('evgm09hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hidemoto Nakada, Hirotaka Ogawa, Satoshi Itoh, Satoshi Sekiguchi
, *roceedings of the 3rd International Workshop on Virtualization Technologies in Distributed Computing (VTDC2009)*   , pp. 67-74  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="evgm09hirofuchi"> Live migration of virtual machines is a key technology for the next generation of IaaS cloud services, contributing to dynamic portability and mobility of VM-based services among datacenters. The practical use of live migration, however, is still limited inside a single datacenter. In WAN environments, network latencies cause inevitable I/O performance degradation of remotely-shared storage between source and destination sites; which is required to continue disk access of VMs before/after live migration. In our previous work, we proposed a transparent, relocatable I/O mechanism for VM migration, which enables VM disk images to be completely migrated to remote nodes without any modification of virtual machine monitors. In this paper, we present detailed performance evaluation of the proposed system, emulating a realistic WAN environment between remote datacenters. Experiments showed the proposed system achieved feasible I/O performance for various workloads including I/O intensive applications. Its background copy mechanism efficiently prefetches not-yet-cached blocks by exploiting the available bandwidth of WAN, thereby minimizing temporary perfor- mance degradation of the migrating VM system.</div> </blockquote>



- **Toward Virtual Machine Packing Optimization based on Genetic Algorithm**  <span onmouseover="document.getElementById('dcai09nakada').style.display = 'block'"  onmouseout="document.getElementById('dcai09nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Takahiro Hirofuchi, Hirotaka Ogawa, Satoshi Itoh
, *Distributed Computing, Artificial Intelligence, Bioinformatics, Soft Computing, and Ambient Assisted Living (Proceedings of International Symposium on Distributed Computing and Artificial Intelligence 2009)*   , pp. 651-654  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dcai09nakada"> To enable efficient resource provisioning in HaaS (Hardware as a Service) cloud systems, virtual machine packing, which migrate vir- tual machines to minimize running real node, is essential. The virtual machine packing problem is a multi-objective optimization problem with several parameters and weights on parameters change dynamically sub- ject to cloud provider preference. We propose to employ Genetic Algorithm (GA) method, that is one of the meta-heuristics. We implemented a prototype Virtual Machine packing optimization mechanism on Grivon, which is a virtual cluster management system we have been developing. The preliminary evaluation implied the GA method is promising for the problem.</div> </blockquote>



- **仮想計算機遠隔マイグレーションに対応するストレージ提供手法の比較検討**  <span onmouseover="document.getElementById('hokke09-hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('hokke09-hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 中田秀基, 小川宏高, 伊藤智, 関口智嗣
, *情報処理学会研究報告2008-HPC-119*   , pp. 73−78  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hokke09-hirofuchi"> 我々は，計算機センタやデータセンタにおける資源運用効率を飛躍的に向上させるため，計算資源利用を拠点横断的に最適化することを目指している．各拠点の物理資源が常に最も効率的な稼動状態となるように，仮想計算機のライブマイグレーション機能を利用して，稼動サービスを動的に拠点間で再配置する． しかし，仮想計算機の拠点間再配置においてはストレージの取り扱いが大きな課題であり，さまざまなストレージ提供技術を適切に組み合わせる必要がある． そこで本稿では，仮想計算機の動的再配置に対応したストレージ技術を比較し，それぞれの特徴を概観する． 仮想計算機移動に対応するストレージ提供手法には，大別するとストレージ共有，ミラーリングおよびストレージ再配置が存在する． 予備実験において，ミラーリングおよび先行型のストレージ再配置手法が仮想計算機のライブマイグレーションと連係動作することを確認した． またその基本的な I/O 性能を計測した． ミラーリングおよび先行型のストレージ再配置とも仮想マシンモニタと正しく連係動作することが確認できた． 書き込み処理については，ミラーリングにおいては性能低下が見られるものの，先行型のストレージ再配置においては限定的な低下にとどまった． 読み込み処理については，両者とも通常のディスクアクセスと同等の I/O 性能であった．</div> </blockquote>



- **A Live Storage Migration Mechanism over WAN for Relocatable Virtual Machine Services on Clouds**  <span onmouseover="document.getElementById('cloud09hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('cloud09hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Hirotaka Ogawa, Hidemoto Nakada, Satoshi Itoh, Satoshi Sekiguchi
, *Proceedings of the 9th IEEE/ACM International Symposium on Cluster Computing and the Grid, International Workshop on Cloud Computing (Cloud 2009)*   , pp. 460-465  , 2009 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cloud09hirofuchi"> IaaS (Infrastructure-as-a-Service) is an emerging concept of cloud computing, which allows users to obtain hardware resources from virtualized datacenters. Although many commercial IaaS clouds have recently been launched, dynamic virtual machine (VM) migration is not possible among service providers; users are locked into a particular provider, and cannot transparently relocate their VMs to another one for the best cost-effectiveness. In this paper, we propose an advanced storage access mechanism that strongly supports live VM migration over WAN. It rapidly relocates VM disks between source and destination sites with the minimum impact on I/O performance. The proposed mechanism addresses I/O consistency of virtual disks before/after migration, which is the major issue regarding wide-area live migration. The proposed mechanism works as a storage server of a block-level storage I/O protocol (e.g., iSCSI and NBD). Two key techniques (on-demand fetching and background copying) move on-line virtual disks among remote sites, transparently and efficiently. Our prototype system works perfectly for Xen and KVM without any modification to them. Experiments showed the prototype system also worked successfully for an emulated WAN environment.</div> </blockquote>



- **ライブ・ストレージマイグレーション機構の開発とその評価,**    
広渕崇宏, 中田秀基, 小川宏高, 伊藤智, 関口智嗣
, *先進的計算基盤システムシンポジウムSACSIS2009 論文集*    , 2009 



- **仮想クラスタのステートレス化のためのRocks 5ディスクレス化機構** [[Paper](dataDir/swopp08ogawa.pdf)] [[Slides](dataDir/swopp08ogawa_slides.pdf)]  <span onmouseover="document.getElementById('swopp08ogawa').style.display = 'block'"  onmouseout="document.getElementById('swopp08ogawa').style.display = 'none'">[abst]</span>   
小川宏高, 中田 秀基, 広渕崇宏, 伊藤智, 関口智嗣
, *情報処理学会研究報告2008−HPC-116*   , pp. 31-36  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp08ogawa"> 計算機資源の効率的な運用の方法として仮想化が注目されており，仮想的なクラスタを管理するさまざまなシステムが提案されている．我々も 2005 年度よりユーザからの依頼に応じて予約ベースで仮想クラスタを構築・提供するサービスを実現する仮想クラスタ管理システムGriVonを研究・開発している．このような仮想クラスタ構築技術でとりわけ重要なのは，仮想クラスタで利用するストレージに求められるさまざまな性質（性能，スケールアウトの容易さ，管理の容易さ，計算機資源の集約を動的に行うためのライブマイグレーション，耐故障性など）をいかに実現するか，である．我々はこうした課題を解決することを目的として，本年 5 月にリリースされた NPACI Rocks version 5 にディスクレスブート化機構を実現した．本稿ではその詳細を述べる．GriVon の次期バージョンでは，この機構を用いてより柔軟な仮想ストレージ管理を実現する予定である．</div> </blockquote>



- **仮想クラスタ遠隔ライブマイグレーションにおけるストレージアクセス最適化機構** [[Paper](dataDir/swopp08hirofuchi.pdf)] [[Slides](dataDir/swopp08hirofuchi_slides.pdf)]  <span onmouseover="document.getElementById('swopp08hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('swopp08hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 小川宏高, 中田 秀基, 伊藤智, 関口智嗣
, *情報処理学会研究報告2008−HPC-116*   , pp. 19-24  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp08hirofuchi"> 計算機センタやデータセンタの計算機資源の運用効率を高めるために, 仮想計算機とそのライブマイグレーション技術が注目されている. 仮想計算機を遠隔拠点に対して動的に再配置できれば, 資源運用の柔軟性向上や省電力化に寄与すると考えられる. しかし既存のライブマイグレーション技術のみでは, 複数拠点にまたがる動的な再配置を効率的・実用的に行うことができない. 本研究では仮想クラスタの遠隔マイグレーションを可能とするためにそのストレージアクセスの最適化機構を提案する. ライブマイグレーションにともなって仮想計算機のストレージも透過的に再配置することで, 周辺機器を含めた仮想計算機の実行環境全体の移動を可能にする. そして移動前後の性能低下を最小限に抑えることを目指す. プロトタイプ実装を用いて予備的な評価実験を行い, 提案手法の基本的な有効性を確認した.</div> </blockquote>



- **A Multi-Site Virtual Cluster System for Wide Area Networks**  <span onmouseover="document.getElementById('lasco08hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('lasco08hirofuchi').style.display = 'none'">[abst]</span>   
Takahiro Hirofuchi, Takeshi Yokoi, Tadashi Ebara, Yusuke Tanimura, Hirotaka Ogawa, Hidemoto Nakada, Yoshio Tanaka, Satoshi Sekiguchi
, *Proceedings of the First USENIX Workshop in Large-Scale Computing,*    , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="lasco08hirofuchi"> A virtual cluster is a promising technology for reducing management costs and improving capacity utilization in datacenters and computer centers. However, re- cent cluster virtualization systems do not have the maximum scalability and flexibility required, due to limited hardware resources at one site. Therefore, we are now developing an advanced cluster management system for multi-site virtual clusters; which provides a virtual cluster composed of distributed computer resources over wide area networks. This system has great advan- tages over other cluster management systems designed only for single-site resources; users can create a cluster of virtual machines from local and remote physical clusters in a scalable manner, and dynamically change the number of cluster nodes on demand, seamlessly. In our system, a multi-site cluster achieves a monolithic system view of cluster nodes to enable existing appli- cations to be deployed quickly and managed flexibly, just as in physical clusters. In this paper, we propose an advanced cluster virtualization mechanism composed of two key techniques. An L2 network extension of virtual machine networks allows transparent deployment over networks for distributed virtual cluster nodes, and a transparent package caching mechanism greatly opti- mizes data transfers in virtual cluster deployment over network latencies. Experimental results show multi-site virtual clusters have sufficient feasibility in WAN envi- ronments and promise great scalability for a large-scale number of virtual nodes.</div> </blockquote>



- **複数サイトにまたがる仮想クラスタの管理機構** [[Paper](dataDir/hpcs08poster_nakada.pdf)] [[Slides](dataDir/hpcs08poster_nakada_slide.pdf)]  <span onmouseover="document.getElementById('hpcs08poster_nakada').style.display = 'block'"  onmouseout="document.getElementById('hpcs08poster_nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 広渕崇宏, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *HPCS 2007*   , pp. 64  , 2008 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpcs08poster_nakada"> 計算機サービスを提供する基盤システムの管理コストを低減する目的で仮想化技術を用いることが一般的となりつつある．われわれは，VMware Serverを用いた計算機の仮想化のみならず，VLANを用いたネットワークの仮想化，iSCSIとLVMを用いたストレージの仮想化を行うことで，クラスタ全体を仮想化した．さらにクラスタデプロイツールRocksを用いて，クラスタ管理ソフトウェアや，運用ソフトウェアを自動的にインストール，設定する仮想クラスタ管理システムを構築した．このような仮想クラスタは管理コストの低減に大きく寄与することが期待できるが，単一サイトの資源のみを用いるシステムでは運用の自由度に限界がある．この限界を取り除くためには，複数の物理的に隔絶したサイトの資源を集合的にもちいて，その上に仮想クラスタを構築する技術が必要となる．我々は，ソフトウェアによるイーサネットVPNをVLANと併用することで，仮想的にフラットな構造を持つネットワークを仮想クラスタに提供し，Rocksを用いたインストールが可能であることを確認した．さらに，仮想クラスタ管理システムを拡張し，複数のサイトからなる仮想クラスタの管理を行うことを可能にしたので報告する．</div> </blockquote>



- **The Design and Implementation of a Virtual Cluster Management System** [[Paper](dataDir/evgm07nakada.pdf)] [[Slides](dataDir/evgm07nakada_slide.pdf)]  <span onmouseover="document.getElementById('evgm07nakada').style.display = 'block'"  onmouseout="document.getElementById('evgm07nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Takeshi Yokoi, Tadashi Ebara, Yusuke Tanimura, Hirotaka Ogawa, Satoshi Sekiguchi
, *Proc. of 1st IEEE/IFIP International Workshop on End-to-end Virtualization and Grid Management*   , pp. 61-71  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="evgm07nakada"> To fully utilize resources in computer center, virtualization techniques are getting popular and several systems are proposed for this purpose. However, they just provide set of virtualized nodes, not the &#x27;virtual clusters&#x27;; i.e., they are not able to install and configure middlewares and tools that makes &#x27;set of nodes&#x27; into &#x27;cluster&#x27;. Another problem is that they just virtualize nodes, leaving storage resources and networks, which are equivalently essential for clusters, un-virtualized. We propose a virtual cluster management system which virtualizes compute resources, as well as disk storage and network, and install and setup softwares that are essential for cluster operation, using Rocks, a cluster provisioning system. We virtualize storage with iSCSI and network with tagged VLAN.</div> </blockquote>



- **ステートレス仮想クラスタの構想**    
小川宏高, 中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 関口智嗣
, *情報処理学会研究報告2007-HPC-112*   , pp. 43-48  , 2007 



- **究極の仮想化環境を目指した「バーチャル・データセンター」**    
中田秀基, 関口智嗣
, *Computer World 11月号*    , 2007 



- **複数サイトにまたがる仮想クラスタの構築** [[Paper](dataDir/hpc0708hirofuchi.pdf)]  <span onmouseover="document.getElementById('hpc0708hirofuchi').style.display = 'block'"  onmouseout="document.getElementById('hpc0708hirofuchi').style.display = 'none'">[abst]</span>   
広渕崇宏, 谷村勇輔, 中田秀基, 田中良夫, 関口智嗣
, *情報処理学会研究報告2007-HPC-111*   , pp. 231-236  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="hpc0708hirofuchi"> 計算機資源の効率的かつ柔軟な運用を実現する手法として、仮想クラスタ技術が注目されている。しかし既存システムは単一サイトの計算機資源のみを仮想クラ スタの対象とする。構築可能な仮想クラスタは単一サイト内に存在する計算機資源によって制限され運用の柔軟性に乏しい。そこで、我々は複数サイトをまたい で横断的に仮想クラスタを構築可能な管理システムの実現に取り組んでいる。複数サイトにわたって構築された仮想クラスタにおいても、単一実行環境としての 透過性やシステムの導入や運用における容易性が実現されなければならない。本論文では、インターネットを介したイーサネット VPN によって単一のネットワークセグメントを仮想クラスタに対して提供することを提案する。予備的な評価実験においては、イーサネット VPN で結ばれたサイト間において仮想クラスタの構築が可能であることを確認した。</div> </blockquote>



- **仮想クラスタ管理システムの設計と実装**  <span onmouseover="document.getElementById('acs19nakada').style.display = 'block'"  onmouseout="document.getElementById('acs19nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *情報処理学会論文誌: コンピューティングシステム Vol.48 SIG13 (ACS19)*   , pp. 13-24  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="acs19nakada"> 計算機資源の効率的な運用の方法として仮想化が注目されており，仮想的なクラスタを管理するシステムが提案されている．しかしこれらのシステムは，クラスタを単なるノードの集合と考えており，クラスタとしての統合的な運用に必要となるさまざまな機能を実現していない．また，計算機資源を仮想化しているが，ストレージ，ネットワークを含めた仮想化環境を提供していない．われわれは，これらの問題点を解決した仮想クラスタ管理システムを提案する．本システムは，クラスタ構築システムRocksを用いることで，クラスタ運用に必要なソフトウェアを整合して配置する．また，ストレージ資源をIP SAN技術のひとつであるiSCSIを用いて仮想化，ネットワーク資源をタグ付きVLANを用いて仮想化することで，管理コストが低く，安全な仮想クラスタ環境を実現する．</div> </blockquote>



- **仮想クラスタ管理システムの設計と実装** [[Paper](dataDir/sacsis07nakada.pdf)] [[Slides](dataDir/sacsis07nakada_slide.pdf)]  <span onmouseover="document.getElementById('sacsis07nakada').style.display = 'block'"  onmouseout="document.getElementById('sacsis07nakada').style.display = 'none'">[abst]</span>   
中田 秀基, 横井 威, 江原忠士, 谷村 勇輔, 小川宏高, 関口智嗣
, *先進的基盤システムシンポジウム SACSIS2007論文集*   , pp. 79-86  , 2007 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sacsis07nakada"> 計算機資源の効率的な運用の方法として仮想化が注目されており，仮想的なクラスタを管理するシステムが提案されている．しかしこれらのシステムは，クラスタを単なるノードの集合と考えており，クラスタとしての統合的な運用に必要となるさまざまな機能を実現していない．また，計算機資源を仮想化しているが，ストレージ，ネットワークを含めた仮想化環境を提供していない．われわれは，これらの問題点を解決した仮想クラスタ管理システムを提案する．本システムは，クラスタ構築システムRocksを用いることで，クラスタ運用に必要なソフトウェアを整合して配置する．また，ストレージ資源をIP SAN技術のひとつであるiSCSIを用いて仮想化，ネットワーク資源をタグ付きVLANを用いて仮想化することで，管理コストが低く，安全な仮想クラスタ環境を実現する．</div> </blockquote>



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



        
