---
layout: default
---
# ML related 

- **Object-Centric Representation Learning with Attention Mechanism**  <span onmouseover="document.getElementById('imcom24nakada').style.display = 'block'"  onmouseout="document.getElementById('imcom24nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hideki Asoh
, *The 18th International Conference on Ubiquitous Information Management and Communication (IMCOM &#x27;24)*    , 2024 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="imcom24nakada"> For object-centric representation learning, several slot-based methods, that separate objects using masks and learn the objects separately, are proposed. While these methods are proved to be useful on various downstream tasks, it is known that they require a significant amount of computation for training. We propose the introduction of attention mechanisms into slot-based method to simplify and speed up the computation. We pick ViMON as the base structure and propose two methods, named AttnViMON and SFA. We evaluate them in terms of reconstruction error and computation time, and a downstream task. The proposed methods demonstrate that they achieve significant speed-up while showing even better performance.</div> </blockquote>



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



- **Improve symbolic music pre-training model using MusicTransformer structure**  <span onmouseover="document.getElementById('imcom2023fu').style.display = 'block'"  onmouseout="document.getElementById('imcom2023fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *The 17th International Conference on Ubiquitous Information Management and Communication*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="imcom2023fu"> Pre-training driven by vast data has shown great power in natural language understanding. The idea has also been applied to symbolic music. However, many existing works using pre-training for symbolic music are not general enough to tackle all the tasks in musical information retrieval, and there is still space to improve the model structure. To make up for the insufficiency and compare it with the existing works, we employed a BERT-like masked language pre-training approach to train a stacked MusicTransformer on MAESTRO dataset. Then we fine-tuned our pre-trained model on several symbolic music understanding tasks. In the work, our contribution is 1)we improved MusicBERT by modifying the model structure. 2)besides the existing evaluation downstream tasks, we complemented several downstream tasks, including melody extraction, emotion classification, and composer classification. We pre-trained the modified model and existing works under the same condition. We make a comparison of our pre-trained model with the previous works. The result shows that the modified model is more powerful than the previous models with the same pre-training setting.</div> </blockquote>



- **End-To-End Training Of Object Segmentation Task And Video Question-Answering Task**  <span onmouseover="document.getElementById('imcom2023nakada').style.display = 'block'"  onmouseout="document.getElementById('imcom2023nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hideki Asoh
, *The 17th International Conference on Ubiquitous Information Management and Communication*    , 2023 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="imcom2023nakada"> For complicated VQA tasks that incorporates multiple objects, to train the VQA model using segmented objects data as inputs is proved to be effective for various downstream tasks. In this work, we tried to train the VQA task model and object segmentation model in end-to-end fashion instead of training independently. We employed CLEVRER as a target VQA task. We first trained MONet, an object segmentation network, with the dataset, and trained Aloe, a VQA model, using the output of the trained MONet. Finally we connect MONet and Aloe to fine-tune them in end-to-end setting and confirmed that the performance of VQA task has been greatly improved.</div> </blockquote>



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



- **報酬最大化ＡＧＩのための意思疎通機構の設計とプロトタイプ実装**  <span onmouseover="document.getElementById('sigagi2207').style.display = 'block'"  onmouseout="document.getElementById('sigagi2207').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 竹内泉, 佐野 崇
, *第21回人工知能学会 汎用人工知能研究会 SIG-AGI*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2207"> 報酬最大化を目的として動作するエージェントどうしが、お互いに意思疎通するための機構を設計し、プロトタイプ実装を行った。エージェントは POMDP を近似的に解いていると解釈でき、合目的的に行動・推論・対話を使い分けるよう設計されている。プロトタイプ実装の上で動作するテストプログラムを書くことにより、設計の妥当性を検討した。この機構はヒトの意思疎通の計算論的モデルの候補でもある。</div> </blockquote>



- **Automated Quantization and Retraining for Neural Network Models without Labeled Data**  <span onmouseover="document.getElementById('ieeeaccess2022Thonglek').style.display = 'block'"  onmouseout="document.getElementById('ieeeaccess2022Thonglek').style.display = 'none'">[abst]</span>   
Kundjanasith Thonglek, Keichi Takahashi, Kohei Ichikawa, Chawanat Nakasan, Hidemoto Nakada, Ryousei Takano, Pattara Leelaprute, Hajimu Iida
, *IEEE Access, Vol.10*   , pp. 73818-73834  , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieeeaccess2022Thonglek"> Deploying neural network models to edge devices is becoming increasingly popular because such deployment decreases the response time and ensures better data privacy of services. However, running large models on edge devices poses challenges because of limited computing resources and storage space. Researchers have therefore proposed various model compression methods to reduce the model size. To balance the trade-off between model size and accuracy, conventional model compression methods require manual effort to find the optimal configuration that reduces the model size without significant degradation of accuracy. In this article, we propose a method to automatically find the optimal configurations for quantization. The proposed method suggests multiple compression configurations that produce models with different size and accuracy, from which users can select the configurations that suit their use cases. Additionally, we propose a retraining method that does not require any labeled datasets for retraining. We evaluated the proposed method using various neural network models for classification, regression and semantic similarity tasks, and demonstrated that the proposed method reduced the size of models by at least 30% while maintaining less than 1% loss of accuracy.We compared the proposed method with state-of-the-art automated compression methods, and showed that it can provide better compression configurations than existing methods.</div> </blockquote>



- **Symbolic piano music understanding from large-scale pre-training**  <span onmouseover="document.getElementById('jsai22fu').style.display = 'block'"  onmouseout="document.getElementById('jsai22fu').style.display = 'none'">[abst]</span>   
Yingfeng Fu, Yusuke Tanimura, Hidemoto Nakada
, *人工知能学会全国大会（第36回）*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai22fu"> Pre-training driven by a vast amount of data has shown great power in natural language understanding. The existing works using pretraining for symbolic music are not general enough to tackle all the tasks in musical information retrieval. To make up for the insufficiency and compare it with the existing works, we employed a BERT-like masked language pre-training approach to train a stacked Music Transformer on polyphonic piano MIDI files from the MAESTRO dataset. Then we finetuned our pre-trained model on several symbolic music understanding tasks. In our current work in progress, we complemented several note-level tasks, including next token prediction, melody extraction, velocity prediction, and chord recognition. And we compared our model with the previous works.</div> </blockquote>



- **画像内オブジェクトの切り出しと質問応答タスクの同時学習**  <span onmouseover="document.getElementById('jsai22nakada').style.display = 'block'"  onmouseout="document.getElementById('jsai22nakada').style.display = 'none'">[abst]</span>   
中田秀基, 麻生 英樹
, *人工知能学会全国大会（第36回）*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="jsai22nakada"> 視野内の複数のオブジェクトの関係などを含む複雑な VQAタスクにおいて、画像から個々のオブジェクトを切り出した結果を入力として質問応答を学習させることで性能が向上することが知られている。本発表では、それぞれ独立に行われていたオブジェクトの切り出しとVQAタスクを同時に学習させる方法について検討した結果について報告する。</div> </blockquote>



- **Performance of Domain Adaptation Schemes in Video Action Recognition using Synthetic Data**  <span onmouseover="document.getElementById('ivsp2022isoi').style.display = 'block'"  onmouseout="document.getElementById('ivsp2022isoi').style.display = 'none'">[abst]</span>   
Hana Isoi, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *The 2022 4th International Conference on Image, Video and Signal Processing (IVSP 2022)*   , pp. 70-79  , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ivsp2022isoi"> The videos obtained from surveillance cameras are expected to be processed in neural networks and utilized for indoor monitoring and surveillance services.  However, collecting training data is generally an issue in machine learning, obtaining sufficient learning data is very difficult from the viewpoint of privacy protection, especially for the abovementioned services.    To address this issue, synthetic data instead of real data might be employed for training. However, the domain shift of video has not been sufficiently investigated, and therefore high-accuracy, unsupervised learning of real video using synthetic video has not been achieved. In this study, we create a synthetic video dataset for action classification and show that action classification can be performed with high accuracy without labeling real video data by learning with this synthetic dataset.  First, we create an OchaHouse Dataset for action classification for indoor monitoring and surveillance. This dataset consists of a real video dataset OchaHouse-Real that records the behavior of one person in a room and a synthetic video dataset OchaHouse-Syn that resembles it. Second, video action recognition of real videos is performed using synthetic data and various unsupervised learning methods with domain adaptation schemes. The results show that learning with synthetic data enables highly accurate action classification of real data without a real data label. The dataset will be published.</div> </blockquote>



- **汎用人工知能のためのプログラム合成対象言語 Pro5Lang のエピソード記憶機構**  <span onmouseover="document.getElementById('sigagi2203').style.display = 'block'"  onmouseout="document.getElementById('sigagi2203').style.display = 'none'">[abst]</span>   
一杉 裕志, 中田 秀基, 高橋 直人, 竹内泉, 佐野 崇
, *第20回人工知能学会 汎用人工知能研究会 SIG-AGI*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="sigagi2203"> 連想記憶の機構を持った汎用人工知能のためのプログラム合成対象言語 Pro5Lang について述べる。この言語は論理型言語と機械語の特徴を合わせ持っている。連想記憶装置は証明探索の過程で得られる証明済み命題をのみを記憶する。この提案機構は脳におけるエピソード記憶の主要な役割の１つを明解に説明する計算論的モデルでもある。テストプログラムをいくつか書くことにより、Pro5Lang の表現力と合成対象言語としての適性を予備的に検討した。</div> </blockquote>



- **合成データを用いた教師なしドメイン適応による室内動作認識手法の比較**  <span onmouseover="document.getElementById('zen22isoi').style.display = 'block'"  onmouseout="document.getElementById('zen22isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *情報処理学会 第84回全国大会*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen22isoi"> 我々は,合成動画像データを活用した教師なし学習による高精度な実動画像データ解析の実現のため,写実的な合成動画像データを作成して実験したが,合成データのみでの学習でもドメイン適応を用いた学習でも十分な解析精度が得られず,改善の余地があることがわかった.本研究では,より時間的モデリングに優れたドメイン適応を行うモデルであるTRN, TA3Nを用いた手法で改善を図り,高精度な動画像分類を実現した.</div> </blockquote>



- **合成データを用いた教師なしドメイン適応による室内動作認識手法の検討**  <span onmouseover="document.getElementById('deim22isoi').style.display = 'block'"  onmouseout="document.getElementById('deim22isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *第14回データ工学と情報マネジメントに関するフォーラム (DEIM)*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="deim22isoi"> ディープニューラルネットワークの利用に伴う実データ収集のコストやプライバシーの問題に対応するため,人工的に作成される合成データを学習に活用することが期待される.我々は,実データ動作認識のための写実的な合成動画像データを作成し,ドメイン適応ネットワークDANNを2つの基本的な動画像識別ネットワーク3D ResNet,TSNで拡張した動画像ドメイン適応手法の効果を調査したが,十分な精度で実データの動作分類を行うことができなかった.本研究では, DANNモデルのバックボーンの比較, Attentionの導入,敵対的学習の追加を行い,さらに詳細に動画像ドメイン適応手法を検討する.実験から,合成データをソースデータとするドメイン適応によって高精度なラベルなし実データの動作分類ができるようになることを示す.</div> </blockquote>



- **A Method to Generate Posed Person Image with few Context Images**  <span onmouseover="document.getElementById('imcom22nakada').style.display = 'block'"  onmouseout="document.getElementById('imcom22nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hideki Asoh
, *IMCOM 2022, The 16th International Conference on Ubiquitous Information Management and Communication*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="imcom22nakada"> The method we propose creates a pose invariant person representation using the attention mechanism and generates posed images by applying pose query on the representation. We evaluated the method using 3D rendered synthetic data and confirmed that the created person representation is pose-invariant, and we can render good quality images with the representation.</div> </blockquote>



- **Few Shot Model based on Weight Imprinting with Multiple Projection Head**  <span onmouseover="document.getElementById('imcom22paulino').style.display = 'block'"  onmouseout="document.getElementById('imcom22paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Hidemoto Nakada, Yusuke Tanimura, Hideki Asoh
, *IMCOM 2022, The 16th International Conference on Ubiquitous Information Management and Communication*    , 2022 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="imcom22paulino"> Few shot learning models based on imprinted weights have achieved excellent results on the low-data regime. In these methods the network directly sets the weight of the final layers for novel classes from the embeddings. As a result, the embeddings learned lead to the highest classification accuracy on base classes; however, the classification accuracy might be degraded on the novel classes.
In this paper, we provide an efficient training approach for imprinted weight models. We find that a simple design choice of imprinted weights can yield substantial improvements over the baseline model.
Our experiments show that (1) introducing a nonlinear projection heads in-between feature extractor, and classifier substantially improves generalization, (2) imprinting from the last projection head does not provide better generalization for novel classes. Instead, we propose imprinting from optimal projection head, and (3) this design choice benefits from a large latent dimension.
We validate our findings by achieving 5.6 and 4.1\% improvement on MNIST dataset trained with Omniglot dataset.</div> </blockquote>



- **Variational Information Bottleneck on Few Shot Model based on Weight Imprinting for Image Classification**  <span onmouseover="document.getElementById('asiancon21paulino').style.display = 'block'"  onmouseout="document.getElementById('asiancon21paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Hidemoto Nakada, Yusuke Tanimura, Hideki Asoh
, *2021 ASIAN CONFERENCE ON INNOVATION IN TECHNOLOGY*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="asiancon21paulino"> Few shot learning remains an open issue in computer vision. Among several recently proposed approaches, Weight Imprinting (WI) achieves superior performance on many challenging benchmarks. The performance of the imprinted weights heavily depends on the quality of the representations generated by the encoder. However, it is not known what characteristics are required for weight imprinting. The representations learned during the pre-training phase are optimized for classification accuracy for the pre-training base classes and not necessarily suitable for the downstream, imprinted tasks. In this paper, we investigate the effect of \VIB on the  few shot learning with weight imprinting. \VIB strongly regularizes the representation by minimizing the mutual information between input data and representation while keeping the classification accuracy for pre-training task. We demonstrate that the encoder regularized by VIB achieves significantly better performance on few-shot learning tasks with imprinting. Furthermore, we comprehensively investigate the effect of combining VIB with other regularization methods including data augmentation and auxiliary data. We confirmed that with a proper auxiliary dataset, we can achieve even better accuracy on the downstream task.</div> </blockquote>



- **One-shot style transfer using Wasserstein Autoencoder** [[Paper](dataDir/asiancon21nakada.pdf)]  <span onmouseover="document.getElementById('asiancon21nakada').style.display = 'block'"  onmouseout="document.getElementById('asiancon21nakada').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Hideki Asoh
, *2021 ASIAN CONFERENCE ON INNOVATION IN TECHNOLOGY*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="asiancon21nakada"> We propose an image style transfer method based on disentangled representation obtained with Wasserstein Autoencoder. Style transfer is an area of image generation technique that generates an image that shows content taken from one image with a style taken from another image. While there are extensive researches in this area, most of them require some ’training’ time to generate images with a specific style. The proposed method does not require training time since we train a versatile network that can be used for any style and content image. The network encodes images into disentangled latent variables that represent content and style. We can transfer image style by simply replacing style latent variables. We tested the proposed method with images from CelebA and confirmed that it can generate style transferred images.</div> </blockquote>



- **合成動画データを用いた学習でのドメイン適応による動作認識精度の比較**  <span onmouseover="document.getElementById('miru2107isoi').style.display = 'block'"  onmouseout="document.getElementById('miru2107isoi').style.display = 'none'">[abst]</span>   
礒井 葉那, 竹房 あつ子, 中田 秀基, 小口 正人
, *第24回画像の認識・理解シンポジウム*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="miru2107isoi"> ディープニューラルネットワークの進歩に伴う学習データ不足の問題について様々な議論が行われており, その解決策の1 つに合成データを利用した学習がある. 合成データには生成が比較的容易であるという利点があるが, 合成データを用いて学習したモデルには, 実データ解析時にデータの分布の違いから解析精度が低下するドメインシフトが起こるという課題がある. 本研究では, 合成動画像データを活用した高精度な実動画像データ解析の実現を目的とし,写実的な合成動画像データを作成して学習し, その解析精度を調査した.</div> </blockquote>



- **オンライン動画動作識別のための分散ストリーム処理基盤の検討**  <span onmouseover="document.getElementById('xsig2107takasaki').style.display = 'block'"  onmouseout="document.getElementById('xsig2107takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *The 5th cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming*    , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig2107takasaki"> 子供やお年寄りの見守りサービスや防犯を目的として家庭のセンサで取得した動画像をリアルタイムに機械学習で解析するには，データ量と解析計算量が課題となる．我々は，センサ側で姿勢推定ライブラリOpenPoseを使用して動画像から関節の特徴量データを抽出してクラウドへ転送し，クラウドでその特徴量データのみを用いて機械学習による動作識別を行うことで，処理遅延やプライバシの問題に対処するセンサとクラウドでの分散処理手法を提案している．しかし，複数家庭のセンサから連続的に送られる大量のデータをクラウドで処理するには，急激なデータの増加によるシステム負荷上昇に耐えうる処理基盤が必要である．本研究では，大量のデータを効率よく処理可能な分散ストリーム処理基盤の構築を目指して，エッジで抽出した関節の特徴量データをApache Kafkaを用いて収集し，クラウドにおいてApache Flinkの分散ストリーム処理機能を用いて機械学習を行うシステムを構築し，その性能特性を調査した．実験結果から，Flinkの並列処理機能を用いることでスケーラブルに機械学習の推論を行えることが分かった．また，データ転送時のバッファリング待ち時間を制御するFlinkのBufferTimeoutパラメータを調節することで，解析効率が改善することが分かった．</div> </blockquote>



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



- **Action Recognition using Pose Data in a Distributed Environment over the Edge and Cloud**  <span onmouseover="document.getElementById('ieice2021takasaki').style.display = 'block'"  onmouseout="document.getElementById('ieice2021takasaki').style.display = 'none'">[abst]</span>   
Chikako Takasaki, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *IEICE Transactions on information and systems, Vol.E104-D, No.5*   , pp. 539-550  , 2021 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieice2021takasaki"> With the development of cameras and sensors and the spread of cloud computing, life logs can be easily acquired and stored in general households for the various services that utilize the logs. However, it is difficult to analyze moving imagesthat are acquired by home sensors in real time using machine learning because the data size is too large and the computational complexity is too high. Moreover, collecting and accumulating in the cloud moving images that are captured at home and can be used to identify individuals may invade the privacy of application users. We propose a method of distributed processing over the edge and cloud that addresses the processing latency and the privacyconcerns. On the edge (sensor) side, we extract feature vectors of human key points from moving images using OpenPose, which is a pose estimation library. On the cloud side, we recognize actions by machine learning using only the feature vectors. In this study, we compare the action recognition accuracies of multiple machine learning methods. In addition, we measure the analysis processing time at the sensor and the cloud to investigate the feasibility of recognizing actions in real time. Then, we evaluate the proposed system by comparing it with the 3D ResNet model in recognition experiments. The experimental results demonstrate that the action recognition accuracy is the highest when using LSTM and that the introduction of dropout in action recognition using 100 categories alleviates overfitting because the models can learn more generic human actions by increasing the variety of actions. In addition, it is demonstrated that preprocessing using OpenPose on the sensor side can substantially reduce the transfer quantity from the sensor to the cloud.</div> </blockquote>



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



- **Generating In-Between Images Through Learned Latent Space Representation Using Variational Autoencoders**  <span onmouseover="document.getElementById('ieeeaccess2020paulino').style.display = 'block'"  onmouseout="document.getElementById('ieeeaccess2020paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Hidemoto Nakada, Yusuke Tanimura, Hideki Asoh
, *IEEE Access, vol 8,*   , pp. 149456-149467  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="ieeeaccess2020paulino"> Image interpolation is often implemented using one of two methods: optical flow or convolutional neural networks. These methods are typically pixel-based; they do not work well on objects between images far apart. Because they either rely on a simple frame average or pixel motion, they do not have the required knowledge of the semantic structure of the data. In this paper, we propose a method for image interpolation based on latent representations. We use a simple network structure based on a variational autoencoder and an adjustable hyperparameter that imposes the latent space distribution to generate accurate interpolation. To visualize the effects of the proposed approach, we evaluate a synthetic dataset. We demonstrate that our method outperforms both pixel-based methods and a conventional variational autoencoder, with particular improvements in nonsuccessive images.</div> </blockquote>



- **エッジ，クラウド間分散処理に向けたNNを用いた動作識別手法の検討**  <span onmouseover="document.getElementById('xsig2020takasaki').style.display = 'block'"  onmouseout="document.getElementById('xsig2020takasaki').style.display = 'none'">[abst]</span>   
高崎智香子, 竹房 あつ子, 中田 秀基, 小口 正人
, *xsig2020*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig2020takasaki"> センサ機器やクラウドコンピューティングの普及により，一般家庭で取得，蓄積した動画像が子供 やお年寄りの見守りサービスや防犯対策，セキュリティに活用されるようになってきた.しかし，家庭の センサで取得した動画像をリアルタイムに機械学習を用いて解析するには，データ転送量と解析計算量が 課題となる.我々は，センサ側で姿勢推定ライブラリ OpenPose を使用して動画像から関節の特徴量デー タを抽出して転送し，クラウドでその特徴量データのみを用いて機械学習による動作識別を行うことで， 処理遅延やプライバシの問題に対処する分散処理手法を提案している.実験では，STAIR Actions データ セットの 3 カテゴリの動作識別が 80%以上の精度で行えること，センサからクラウドへのデータ転送量を 大幅に削減できることを確認した.しかし，3 カテゴリの識別では汎用性が低く，過学習の改善も課題と なっていた.本研究では，より多様な動作識別を活用する実アプリケーションへの応用を目指し，同デー タセットの全 100 カテゴリを用いた識別を行った. 実験から，LSTM を用いることで最も高い精度を得る ことができることを確認した.</div> </blockquote>



- **Retraining Quantized Neural Network Models with Unlabeled Data**  <span onmouseover="document.getElementById('IJCNN2020Thong').style.display = 'block'"  onmouseout="document.getElementById('IJCNN2020Thong').style.display = 'none'">[abst]</span>   
Kundjanasith Thonglek, Keichi Takahashi, Kohei Ichikawa, Chawanat Nakasan, Ryousei Takano, Hidemoto Nakada, Hajimu Iida
, *International Joint Conference on Neural Networks (IJCNN)*    , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="IJCNN2020Thong"> Running neural network models on edge devices is attracting much attention by neural network researchers since edge computing technology is becoming more powerful than ever. However, deploying large neural network models on edge devices is challenging due to the limitation in available computing resources and storage space. Therefore, model compression techniques have been recently studied to reduce the model size and fit models on resource-limited edge devices. Compressing neural network models reduces the size of a model, but also degrades the accuracy of the model since it reduces the precision of weights in the model. Consequently, a retraining method is required to recover the accuracy of compressed models. Most existing retraining methods require the original labeled training datasets to retrain the models, but labeling is a time-consuming process. In particular, we cannot always access the original labeled datasets because of privacy policies and license limitations. In this paper, we propose a method to retrain a compressed neural network model with an unlabeled dataset that is different from the original labeled dataset. We compress the neural network model using quantization to decrease the size of the model. Subsequently, the compressed model is retrained by our proposed retraining method without using a labeled dataset to recover the accuracy of the model. We compared the proposed retraining method against the conventional retraining. The proposed method reduced the size of VGG-16 and ResNet-50 by 81.10% and 52.45%, respectively without significant accuracy loss. In addition, our proposed retraining method is clearly faster than the conventional retraining method.</div> </blockquote>



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



- **One-Shot Learning Using Triplet Network with kNN Classifier**  <span onmouseover="document.getElementById('aiai2020zhou').style.display = 'block'"  onmouseout="document.getElementById('aiai2020zhou').style.display = 'none'">[abst]</span>   
Mu Zhou, Yusuke Tanimura, Hidemoto Nakada
, *JSAI 2019: Advances in Artificial Intelligence, vol 1128. Springer,*   , pp.  227-235  , 2020 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="aiai2020zhou"> This is an extension from a selected paper from JSAI2019. Humans have the ability to learn new things correctly without requiring large amount of data, while it is a challenging task in AI, which is called few-shot Learning or one-shot learning. Our key insight is using data augmentation technique to enlarge our dataset, then feeding them into a Triplet Network which is to collect same categories and separate the different. We have compared different augmentation methods, and we confirm that CVAE(Conditional VAE) can make sense as data augmentation method to slove one-shot classification problems.</div> </blockquote>



- **A Study of Action Recognition using Pose Data toward Distributed Processing over Edge and Cloud**  <span onmouseover="document.getElementById('cloudcom19takasaki').style.display = 'block'"  onmouseout="document.getElementById('cloudcom19takasaki').style.display = 'none'">[abst]</span>   
Chikako Takasaki, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *Proc. of CloudCom 2019*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cloudcom19takasaki"> With the development of cameras and sensors, and the spread of cloud computing, life logs can be acquired and stored in general households for various services using the logs. However, it is difficult to analyze moving images acquired by a home sensor in real time using machine learning because the data size and the computational complexity are large. New computing paradigm called edge computing or fog computing, which enables distributed computing over edge and cloud, has the possibility to address this issue. The feature vectors are extracted from moving images by preprocessing on the sensor side and the only small feature vectors are sent to the cloud and used for learning. But, it is not clear how accurately we can recognize actions using only the feature vectors in the learning and inferring. We investigate the accuracies of action recognition with various machine learning methods using feature vector information obtained from moving images. We use the pose estimation library OpenPose for detection of the feature vectors and recognize actions using logistic regression, random forest, support vector machine, and neural network (NN) models, general NN and LSTM, as machine learning methods. The experimental results show that it is possible to recognize an action with 80% accuracy or higher when using random forest and neural network models. We also discuss a method to further improve the accuracy based on the experimental results.</div> </blockquote>



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



- **Hierarchical Reinforcement Learning with Unlimited Recursive Subroutine Calls**  <span onmouseover="document.getElementById('icann19ichisughi').style.display = 'block'"  onmouseout="document.getElementById('icann19ichisughi').style.display = 'none'">[abst]</span>   
Yuuji Ichisugi, Naoto Takahashi, Hidemoto Nakada, Takashi Sano
, *28th International Conference on Artificial Neural Networks (ICANN 2019)*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="icann19ichisughi"> We propose a new hierarchical reinforcement learning architecture called the RGoal architecture.RGoal solves the Markov Decision Process (MDP) in an augmented state-action space.</div> </blockquote>



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



- **Japan-Taiwan Data AI Module Platform for Analyzing Remote Sensing data, Part 2.**  <span onmouseover="document.getElementById('pragma36jeju').style.display = 'block'"  onmouseout="document.getElementById('pragma36jeju').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, et. al
, *PRAGMA 36*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pragma36jeju"> Sharing data and AI module is the key to accelerate the use of AI. This demo is to demonstrate the data and AI module platform which is built between AIST and NCHC. AI module for detecting solar panels by analyzing remote sensing data was developed by AIST. We will demonstrate that the AI module is built as a docker image can be easily deployed at NCHC for analyzing Formosat-2 data</div> </blockquote>



- **Construction Scheme of a Scalable Distributed Stream Processing Infrastructure Using Ray and Apache Kafka**  <span onmouseover="document.getElementById('cata19kato').style.display = 'block'"  onmouseout="document.getElementById('cata19kato').style.display = 'none'">[abst]</span>   
Kasumi Kato, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *Proc. of 34th International Conference on Computers and Their Applications(CATA 2019), EPiC Series in Computing, vol. 58*   , pp. 368--377  , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="cata19kato"> The spread of various sensors and the development of cloud computing technologies en- able the accumulation and use of large numbers of live logs in ordinary homes. To operate a service that utilizes sensor data, it is difficult to install servers and storage in ordinary homes and to analyze the collected data from sensors. Those data are typically transmitted from sensors to a cloud and analyzed in the cloud. However, services that involve moving image analysis must transfer large amounts of data continuously and require high computing power for analysis. Hence, it is highly difficult to process them in real time in the cloud using a conventional stream data processing framework. In this research, we propose a construction scheme for a highly efficient distributed stream processing infrastructure that enables scalable processing of moving image recognition tasks according to the amount of data that are transmitted from sensors. We implement a prototype system of the proposed distributed stream processing infrastructure using Ray and Apache Kafka, which is a distributed messaging system, and we evaluate its performance. The experimental results demonstrate that the proposed distributed stream processing infrastructure is highly scalable.</div> </blockquote>



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



- **Japan-Taiwan Data AI Module Platform for Analyzing Remote Sensing data, Part 3.**  <span onmouseover="document.getElementById('pragma37sandiego').style.display = 'block'"  onmouseout="document.getElementById('pragma37sandiego').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, et. al
, *PRAGMA 37*    , 2019 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pragma37sandiego"> Sharing data and AI module is the key to accelerate the use of AI. This demo is to demonstrate the data and AI module platform which is built between AIST and NCHC. AI module for detecting solar panels by analyzing remote sensing data was developed by AIST. We will demonstrate that the AI module is built as a docker image can be easily deployed at NCHC for analyzing Formosat-2 data</div> </blockquote>



- **A Study of a Scalable Distributed Stream Processing Infrastructure Using Ray and Apache Kafka**  <span onmouseover="document.getElementById('bigdataposter2018-kato').style.display = 'block'"  onmouseout="document.getElementById('bigdataposter2018-kato').style.display = 'none'">[abst]</span>   
Kasumi Kato, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *IEEE Bigdata 2018(poster)*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="bigdataposter2018-kato"> The spread of various sensors and the development of cloud computing technologies enable the accumulation and use of many live logs in ordinary homes. To operate a service that utilizes sensor data, those data are transmitted from sensors in ordinary homes to a cloud and analyzed in the cloud. However, services that involve moving image analysis require large amounts of data to be transferred continuously and high computing power for the analysis; hence, it is difficult to process them in real time in the cloud using a conventional stream data processing framework. We study a construction scheme for a highly efficient distributed stream processing infrastructure that enables scalable processing in moving image recognition according to the amount of data that is transmitted from sensors.</div> </blockquote>



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



- **Japan-Taiwan Data and AI module platform for analyzing remote sensing data**  <span onmouseover="document.getElementById('pragma35demo').style.display = 'block'"  onmouseout="document.getElementById('pragma35demo').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, et.al
, *Pacific Rim Application and Grid Middleware Assembly (Pragma) 35*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pragma35demo"> Sharing data and AI module is the key to accelerate the use of AI. This demo is to demonstrate the data and AI module platform which is built  between AIST and NCHC. AI module for detecting solar panels by analyzing remote sensing data was developed by AIST. We will demonstrate that the AI module which is built as a docker image can be easily deployed at NCHC for analyzing Formosat-2 data in Taiwan.</div> </blockquote>



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



- **Sub-policy pruning in Meta Learning Shared Hierarchies**  <span onmouseover="document.getElementById('pragma-hon').style.display = 'block'"  onmouseout="document.getElementById('pragma-hon').style.display = 'none'">[abst]</span>   
Ging Hong, Yusuke Tanimura, Hidemoto Nakada
, *34th meeting of the Pacific Rim Applications and Grid Middleware Assembly (PRAGMA 34).*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pragma-hon"> MLSH (Meta Learning Shared Hierarchies) is a meta learning method that divide a policy into multiple sub-policies and a master-policy that picks one of the sub-policies to be actually used. By training sub-policies in advance, master policy can rapidly adjust to given environments. However, MLSH is not suitable for complicated environments. In complicated environments, a number of sub-policies are required,  and it is very difficult to train them properly. We propose a method to effectively prune excessive sub-policies to give better chance the other sub-policies to be trained.</div> </blockquote>



- **Toward image inbetweening using Latent Model**  <span onmouseover="document.getElementById('pragma-paulino').style.display = 'block'"  onmouseout="document.getElementById('pragma-paulino').style.display = 'none'">[abst]</span>   
Paulino Cristovao, Yusuke Tanimura, Hidemoto Nakada, Hideki Asoh
, *34th meeting of the Pacific Rim Applications and Grid Middleware Assembly (PRAGMA 34).*    , 2018 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="pragma-paulino"> Image interpolation is a well known problem in computer vision. Many approaches are restricted to optical flow and convolutional neural network. In this work, we present an alternative approach based on generative models to generate in between images (interpolation) using variational autoencoders (VAE). The goals are: Generate in between images using hidden structures (latent variables), and yield latent features that generalize well. Our architecture composed of three networks (VAE) that share weights. We train the network feeding three continous frames so that the second latent variables become close to the average of the first and third latent variables. To get interporated image from two images, we can just reconstract the image from the avarage of the two images&#x27; latent variables. We evaluate the result by comparing the ground truth image and the generated one to evaluate the in between image. In addition we show the reconstructed images using the same network.</div> </blockquote>



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



- **AI入門 -こんにゃく相場は予測できるのか‐**    
中田 秀基
, *群馬県蒟蒻原料商工業協同組合新年講演会*    , 2018 



- **大規模データ分散プラットフォームApache Sparkにおけるタスク並列化に関する検討**    
加藤香澄, 竹房 あつ子, 中田 秀基, 小口 正人
, *信学技報, vol. 117, no. 371, MoNA2017-39*    , 2017 



- **KafkaとSpark Streamingを利用したリアルタイム動画像解析フレームワークの構成検討**    
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *信学技報, vol. 117, no. 371, MoNA2017-39*    , 2017 



- **Consideration of Parallel Data Processing over an Apache Spark Cluster**  <span onmouseover="document.getElementById('bigdata17kato-poster').style.display = 'block'"  onmouseout="document.getElementById('bigdata17kato-poster').style.display = 'none'">[abst]</span>   
Kasumi Kato, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *IEEE BigData 2017 poster*   , pp. 4675-4677  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="bigdata17kato-poster"> The Spread of cameras and sensors and cloud technologies enable us to obtain life logs at ordinary homes and transmit the captured data to a cloud for the life log analysis. However, the amount of processing for video data analysis in a cloud is drastically increasing when a very large number of homes send the data to the cloud. In this research, we aim to improve the efficiency of distributed video data analysis processing byusing the parallel deep learning framework Chainer and the distribution processing platform Apache Spark (Spark). Inthis paper, we focus on parallel data processing on a Spark cluster.</div> </blockquote>



- **A Study of a Video Analysis Framework Using Kafka and Spark Streaming**  <span onmouseover="document.getElementById('bigdataws17ichinose').style.display = 'block'"  onmouseout="document.getElementById('bigdataws17ichinose').style.display = 'none'">[abst]</span>   
Ayae Ichinose, Atsuko Takefusa, Hidemoto Nakada, Masato Oguchi
, *Second workshop on Real-time and stream processing in IEEE BigData 2017*   , pp. 2314-2319  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="bigdataws17ichinose"> The use of various sensors and cloud computingtechnologies has spread, many life-log analysis applications forsafety services for the elderly and children have been developed.However, it is difficult to perform real-time large data processingin clouds due to the computational complexity of the analysisbecause efficient deployment schemes of streaming computingcomponents over cloud resources have not been well-investigated.In this study, we propose a video analysis framework that collectsvideos from multiple cameras and analyzes them using ApacheKafka and Apache Spark Streaming. We first investigate the datatransfer performance of Apache Kafka and examine efficientcluster configuration and parameter settings. We then applythis configuration to the proposed framework and measure thedata analysis throughput. The experimental results show that theoverall throughput varies depending on the number of brokernodes that store data, the number of topic partitions of data,and the number of nodes that conduct analysis processing. Inaddition, it is confirmed that the number of cores is neededto consider for the efficient cluster configuration, and that thenetwork bandwidth between the nodes becomes a bottleneck asthe amount of data and the number of components increase.</div> </blockquote>



- **How Much Should We Invest for Network Facility: Quantitative Analysis on Network &#x27;Fatness&#x27; and Machine Learning Performance** [[Paper](dataDir/mlsys17duo.pdf)] [[Slides](dataDir/mlsys17duo_slides.pdf)]  <span onmouseover="document.getElementById('mlsys17duo').style.display = 'block'"  onmouseout="document.getElementById('mlsys17duo').style.display = 'none'">[abst]</span>   
Duo Zhang, Mingxi LI, Yusuke Tanimura, Hidemoto Nakada
, *Workshop on ML Systems in NIPS 2017*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="mlsys17duo"> Multi-node execution is becoming more and more popular for machine learning because of it&#x27;s huge amount of computation. The question we are trying to answer here is that, how should we design computer systems for deep learning, especially in terms of investment for the network. Traditional cluster based &#x27;super-computers&#x27; require huge amount of investment on network switches since the network &#x27;fatness&#x27; is quite important for the typical applications of super-computers. Do the machine learning workloads share the characteristics with such kinds of applications? To answer this questions, we quantitatively analyze the impact of network fatness on several type of machine learning application types with several network configurations. The results we obtained strongly implies that the network fatness is not important for machine learning applications, and thus we could safely reduce investment on network facilities.</div> </blockquote>



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



- **A Quantitative Analysis on Required Network Bandwidth for Large-Scale Parallel Machine Learning**  <span onmouseover="document.getElementById('mod17').style.display = 'block'"  onmouseout="document.getElementById('mod17').style.display = 'none'">[abst]</span>   
Mingxi Li, Yusuke Tanimura, Hidemoto Nakada
, *MOD 2017 - (The Third International Conference on Machine Learning, Optimization and Big Data) , LNCS vol.10710*   , pp. 389-400  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="mod17"> Parallelization is essential for machine learning systems that deals with large-scale data-set. Data parallel machine leaning systems, that is composed of multiple machine learning modules, exchange the parameter to synchronize the models in the modules, via network. We investigate the network bandwidth requirements for various parameter exchange method, using cluster simulator SimGrid. We have confirmed that 1) direct exchange method substantially more efficient than parameter server based method, and 2) with proper exchange methods, the bisection-bandwidth of the network does not affect the efficiency, allowing smaller investment on network facility.</div> </blockquote>



- **Context-Dependent Robust Text Recognition using Large-scale Restricted Bayesian Network**  <span onmouseover="document.getElementById('bica17').style.display = 'block'"  onmouseout="document.getElementById('bica17').style.display = 'none'">[abst]</span>   
Hidemoto Nakada, Yuuji Ichisugi
, *BICA2017(2017 Annual International Conference on Biologically Inspired Cognitive Architectures), Procedia Computer Science, Volume 123, 2018, Elsevior*   , pp. 314-320  , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="bica17"> We have been proposing a computational model of the cerebral cortex called BESOM,  which models the cerebral cortex as restricted Bayesian networks based on recent findings in the neuroscience area. Since BESOM is based on Bayesian network, it inherently allows bi-directional information flow, meaning that it can naturally merge information extracted from concrete data with highly-abstract prior knowledge. As an example of such kind of tasks, we report robust text recognition task with context information. We show that word spelling knowledge and word n-gram could be represented as a part of the network and they contribute the text recognition accuracy with noisy text images.We also show that the computational cost is approximately linear with the number of characters and words.</div> </blockquote>



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



- **大規模機械学習向けクラスタにおけるネットワーク構造とパラメータ交換手法** [[Paper](dataDir/xsig17rei.pdf)] [[Slides](dataDir/xsig17rei-slides.pdf)]  <span onmouseover="document.getElementById('xsig17rei').style.display = 'block'"  onmouseout="document.getElementById('xsig17rei').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 中田 秀基
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17rei"> 大規模なデータを対象とする機械学習システムの高速化には並列化が必須である。データ並列機械学習システムにおいては、何らかの方法で機械学習機内のパラメータの値を交換する必要があるが、パラメータ交換手法とネットワーク構造の関係は知られていない。本研究では、ネットワークシミュレータSimGridを用いて、さまざまなネットワークと、パラメータ交換手法を組み合わせて評価を行った。その結果、パラメータ交換手法によっては、ネットワークバイセクションバンド幅の影響をほとんど受けず、比較的貧弱なネットワークでも遜色のない性能で実行できることがわかった。</div> </blockquote>



- **大規模機械学習向けクラスタにおけるネットワークバンド幅とパラメータ交換手法に関する考察** [[Paper](dataDir/xsig17rei-poster.pdf)]  <span onmouseover="document.getElementById('xsig17rei-poster').style.display = 'block'"  onmouseout="document.getElementById('xsig17rei-poster').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 中田 秀基
, *cross-disciplinary Workshop on Computing Systems, Infrastructures, and Programming, (poster)*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="xsig17rei-poster"> 大規模なデータを対象とする機械学習システムの高速化には並列化が必須である。データ並列機械学習システムにおいては、何らかの方法で機械学習機内のパラメータの値を交換する必要があるが、パラメータ交換手法とネットワーク構造の関係は知られていない。本研究では、ネットワークシミュレータSimGridを用いて、さまざまなネットワークと、パラメータ交換手法を組み合わせて評価を行った。その結果、パラメータ交換手法によっては、ネットワークバイセクションバンド幅の影響をほとんど受けず、比較的貧弱なネットワークでも遜色のない性能で実行できることがわかった。</div> </blockquote>



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



- **A Quantitative Analysis of Fault Tolerance Mechanisms for Parallel Machine Learning Systems with Parameter Servers**  <span onmouseover="document.getElementById('imcom17rei').style.display = 'block'"  onmouseout="document.getElementById('imcom17rei').style.display = 'none'">[abst]</span>   
Mingxi Li, Yuusuke Tanimura, Hidemoto Nakada
, *ACM IMCOM 2017*    , 2017 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="imcom17rei"> Parallel computation is essential for machine learning systems that handle  large amount of data for training.  One popular form of parallel machine learning is the one called  &#x27;Data parallel&#x27; which use large number of parameter servers that manage computational workers.  Fault tolerance is always a crucial issue on large scale computation systems in general,  and parameter server based machine learning systems are no exception.  However, there are many discussions on the fault tolerance of large scale computation systems in general,  there are no discussions on parallel machine learning systems, in spite of their unique characteristics.  In this paper, we discuss the fault tolerance of parallel machine learning systems which use parameter servers that provides extra redundancy to the system and could double as the checkpoint server. We also quantitatively evaluate several fault tolerance method using  parallel environment simulator SimGrid, and demonstrate the effectiveness  of the proposed method.</div> </blockquote>



- **パラメータサーバを用いた並列機械学習システムにおける耐故障性のシミュレーション** [[Paper](dataDir/swopp16rei.pdf)] [[Slides](dataDir/swopp16rei-slides.pdf)]  <span onmouseover="document.getElementById('swopp16rei').style.display = 'block'"  onmouseout="document.getElementById('swopp16rei').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 中田 秀基
, *信学技報, vol.116, no.177*   , pp. 125-130  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp16rei"> 機械学習システムを高速化させるためには、並列化は必要である。並列化には2つの方法があるが、本稿ではパラメータサーバと計算サーバからなる大規模な計算システム、いわゆるモデル並列を扱う。一般に大規模な計算システムに於いては耐故障性が問題になるが、並列機械学習システムにおける耐故障性の議論は進んでいない。本稿ではパラメータサーバを用いた並列機械学習システムにおける耐故障性に関して議論し、また、シミュレーションを用いて検証を行う。</div> </blockquote>



- **ディープラーニングフレームワークCaffeの分散処理の評価**  <span onmouseover="document.getElementById('dicomo16ichinose').style.display = 'block'"  onmouseout="document.getElementById('dicomo16ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *マルチメディア，分散，協調とモバイル(DICOMO2016)シンポジウム*    , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="dicomo16ichinose"> 近年各種センサの普及とクラウドコンピューティング技術の習熟により,ライフログの取得やその データの蓄積が容易になった.その結果監視カメラなどのセンサを用いたライフログデータをクラウドで 収集して解析するアプリケーションも普及してきている.ここで,センサデータをそのまま送信してクラ ウドで処理する場合,プライバシや各種センサとクラウド間のネットワーク帯域の問題が生じてしまう. 本研究では,クラウドへ送るデータのデータ量の削減とプライバシの保護を目的とし,フレームワーク Caffe の機械学習処理をセンサ側とクラウド側でパイプライン的に分散処理を行う.その評価として,分 割箇所やパラメータを変化させ処理時間を比較する.本稿では ImageNet を用いて実験を行い,大規模な データセットにおいても分散処理を行うことで生データをクラウドに送ることなく遜色ない学習が可能で あり,また低帯域環境ではより高速に処理できることを示す.</div> </blockquote>



- **Evaluation of Distributed Processing of the Deep Learning Framework Caffe**  <span onmouseover="document.getElementById('HPDC16ichinose-poster').style.display = 'block'"  onmouseout="document.getElementById('HPDC16ichinose-poster').style.display = 'none'">[abst]</span>   
Ayae Ichinose, Atsuko Takefusa, Hidemoto Nakada, Masto Oguchi
, *The 25th International Symposium on High Performance Parallel and Distributed Computing , Poster presentation*    , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="HPDC16ichinose-poster"> Many life-log analysis applications, which transfer sensor data to a Cloud and analyze them, have been developed. We propose pipelined-based distributed deep learning processing between sensors and Clouds in order to reduce the amount of data sent to Clouds and protect the privacy of application users or the people related to the sensor data. We investigate processing times of classification and the results show that proposed distributed processing has performance advantages in the cases of insufficient network bandwidth as actual sensor and Cloud environment.</div> </blockquote>



- **ディープラーニングフレームワークCaffeの分散処理に向けた一検討**  <span onmouseover="document.getElementById('zen16ichinose').style.display = 'block'"  onmouseout="document.getElementById('zen16ichinose').style.display = 'none'">[abst]</span>   
一瀬 絢衣, 竹房 あつ子, 中田 秀基, 小口 正人
, *第78回情報処理学会全国大会4P-05*   , pp. 1-2  , 2016 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="zen16ichinose"> 我々は，データ量の削減とプライバシの保護を目的として，ディープラーニングフレームワークCaffeをセンサーとクラウドで分散して実行することを目指している．本研究では，センサ・クラウド間で分散実行した場合の送受信データ量と識別率の相関を調査した．</div> </blockquote>



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



- **マスタ・ワーカ型パラメータサーバの実装とBESOM への適用** [[Paper](dataDir/swopp15rei.pdf)]  <span onmouseover="document.getElementById('swopp15rei').style.display = 'block'"  onmouseout="document.getElementById('swopp15rei').style.display = 'none'">[abst]</span>   
黎 明曦, 谷村 勇輔, 一杉 裕志, 中田 秀基
, *信学技報, vol. 115, no. 174, CPSY2015-33*   , pp. 179-184  , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="swopp15rei"> 大脳皮質の計算論的モデルとして\BESOM を提案している。BESOM は最新の神経科学的な知見に基づいてベイジアンネットで大脳皮質をモデル化したもので、人間の脳の比較的忠実なモデルとなっていることから、科学的に興味深いだけではなく、工学的にも広い応用が期待できる。その一方、BESOM における学習には、近年注目を集めているニューラルネットによるディープラーニングよりもさらに計算量が大きいことから、並列化による実行速度向上が要請される。本稿では、汎用のマスタ・ワーカ型タスク実行フレームワークを用いて、学習パラメータを交換するパラメータサーバを構築し、複数の\BESOM モデルが協調して並列に学習する環境を実現した。これに、計算機内でのスレッド並列を組み合わせることで、16台4スレッドを用いた場合で、最大40倍程度の高速化が可能であること、また、高速化の度合いは並列実行時のバッチサイズに依存することを確認した。</div> </blockquote>



- **Surface object recognition with CNN and SVM in Landsat 8 images**  <span onmouseover="document.getElementById('iapr2015ishii').style.display = 'block'"  onmouseout="document.getElementById('iapr2015ishii').style.display = 'none'">[abst]</span>   
Tomohiro Ishii, Ryosuke Nakamura, Hidemoto Nakada, Yoshihiko Mochizuki, Hiroshi Ishikawa
, *2015 14th IAPR International Conference on Machine Vision Applications (MVA)*    , 2015 

> <blockquote> <div style="text-align: justify; display: none; background: lightgrey; margin: 0 0 0 30pt" id="iapr2015ishii"> There is a series of earth observation satellites called Landsat, which send a very large amount of image data every day such that it is hard to analyze manually. Thus an effective application of machine learning techniques to automatically analyze such data is called for. In surface object recognition, which is one of the important applications of such data, the distribution of a specific object on the surface is surveyed. In this paper, we propose and compare two methods for surface object recognition, one using the convolutional neural network (CNN) and the other support vector machine (SVM). In our experiments, CNN showed higher performance than SVM. In addition, we observed that the number of negative samples have a influence on the performance, and it is necessary to select the number of them for practical use.</div> </blockquote>



        
