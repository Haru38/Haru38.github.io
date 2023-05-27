# Profile
氏名：山根 永暉

大学・大学院で情報工学を専攻し、現在はデータサイエンティストとして活動しております。
研究では生命データを用いた機械学習の応用研究を行い、Compound-Protein interaction (CPI)予測の深層学習モデルの開発を行いました。
また、2021年からはブロックチェーンエンジニアとして活動し、主にNFTに関するサービスのスマートコントラクトの開発を行っております

# Career

- 2017年 東京工業大学 情報理工学院 情報工学系
- 2021年 東京工業大学大学院 情報理工学院 情報工学系 知能情報コース 石田研究室

# Research
## Prediction of class A GPCRs and olfactory receptor activity
Olfactory receptors are a type of G protein-coupled receptors (GPCRs) that are expressed in the olfactory epithelium and are deeply involved in the perception of odors. The discovery of ligands for olfactory receptors contributes to understanding the mechanisms of odor perception and the development of drug targeting olfactory receptors. Biological experiments and computational studies, including activity prediction using computers, have been conducted thus far. Computational methods for activity prediction can be broadly classified into two categories: docking simulations and machine learning. However, predicting olfactory receptor activity through docking simulations has been challenging because there are no known three-dimensional structures of olfactory receptors. As a result, machine learning-based predictions have been actively pursued in recent years.

However, most olfactory receptors are orphan receptors, meaning their ligands are largely unknown, and the lack of sufficient data is a bottleneck for achieving accurate activity predictions. Therefore, Compound-Protein Interaction (CPI) prediction methods have been applied, which utilize information from both olfactory receptor proteins and compound ligands, making it possible to predict novel olfactory receptors. Additionally, various techniques have been proposed to address the scarcity of negative data in the dataset, such as generating decoy data, and to reduce the dimensionality of input vectors using feature selection based on important residues identified by ligand binding analysis. However, there is still room for improvement in terms of accuracy, reliability of results, and model architecture.

On the other hand, GPCRs are classified into six classes (Class A to Class F) based on structural and functional differences. Olfactory receptors belong to Class A GPCRs, which include rhodopsin and adrenaline receptors, and it is known that the ligand binding site is located in the transmembrane region. Therefore, by using activity information of compounds that bind to Class A GPCRs with the same ligand binding site as olfactory receptors, it is possible to overcome the problem of limited olfactory receptor activity information and achieve more accurate predictions.

In this study, we constructed a protein sequence encoder specialized for Class A GPCRs called the Helix encoder. We performed pre-training of the activity prediction model using data from Class A GPCRs and fine-tuning using olfactory receptor data, aiming to improve the accuracy of activity predictions.
## Publications
1. Haruki Yamane and Takashi Ishida. [Helix encoder: a compound-protein interaction prediction model specifically designed for class A GPCRs](https://doi.org/10.3389/fbinf.2023.1193025). [Frontiers in Bioinformatics](https://www.frontiersin.org/journals/bioinformatics), Vol. 3, 2023.
2. Haruki Yamane and Takashi Ishida. [Prediction of class A GPCR-Compound interactions by deep learning focusing on ligand binding site protein sequences](https://cbi-society.org/taikai/taikai22/poster_oral/p_abstract_cbi2022.pdf"). [Chem-Bio Informatics Society(CBI) Annual Meeting 2022, Oct](https://cbi-society.org/taikai/taikai22/index.html).
3. 山根 永暉, 石田 貴士. [クラスA Gタンパク質共役受容体専用エンコーダを用いたタンパク質ー化合物相互作用予測](https://ipsj.ixsq.nii.ac.jp/ej/?action=pages_view_main&active_action=repository_view_main_item_detail&item_id=216913&item_no=1&page_id=13&block_id=8). [第69回バイオ情報学(SIGBIO)研究会](https://www.ipsj.or.jp/kenkyukai/event/bio69.html).

# Works
### [株式会社サイシード](https://sciseed.jp/)
- 職種: インターン/エンジニア
- 期間: 2019/4 ~ 2021/3
- 内容: 電光掲示板に表示される3Dキャラクターを用いた警備システムの開発プロジェクトに参画。物体認識及びトラッキングモデルの開発に従事。
### [株式会社リードエッジコンサルティング](https://corp.leadedge-c.com/)
- 職種: インターン/ブロックチェーンエンジニア
- 期間: 2021/9 ~ 2022/2
- 内容: NFTのサブスク機能におけるスマートコントラクトの開発やMaticのFaucetを含むweb3ツールの開発に従事。
### [ヤフー株式会社](https://about.yahoo.co.jp/)
- 職種: インターン/データサイエンティスト
- 期間: 2021/10
- 内容: 検索システムにおけるサジェスト機能に使用されるリランキングモデルの開発に従事。
### [株式会社プラチナエッグ](ttps://www.platinum-egg.com/)
- 職種: インターン/ブロックチェーンエンジニア
- 期間: 2022/6 ~ 2022/3
- 内容: 複数のブロックチェーンゲーム開発プロジェクトに参画。ERC721を中心ににおけるスマートコントラクトの開発に従事。
- Teaser site: [Climbers](https://climbers.show/)
