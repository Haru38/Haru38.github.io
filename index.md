# Profile
**山根 永暉**

大学・大学院で情報工学を専攻し、現在はデータサイエンティストとして活動しております。
研究では生命データを用いた機械学習の応用研究を行い、compound-Protein interaction (CPI)予測の深層学習モデルの開発を行いました。
また、2021年からはブロックチェーンエンジニアとして活動し、主にNFTに関するサービスのスマートコントラクトの開発を行っております。

# Career

- 2017年 東京工業大学 情報理工学院 情報工学系
- 2021年 東京工業大学大学院 情報理工学院 情報工学系 知能情報コース

# Works
### [株式会社サイシード](https://sciseed.jp/)
- 職種: インターン/エンジニア
- 期間: 2019/4 ~ 2021/3
- 内容: 電光掲示板に表示される3Dキャラクターを用いた警備システムの開発プロジェクトに参画。物体認識及びトラッキングモデルの開発に従事。

### [株式会社リードエッジコンサルティング](https://corp.leadedge-c.com/)
- 職種: インターン/ブロックチェーンエンジニア
- 期間: 2021/9 ~ 2022/2
- 内容: NFTのサブスクサービスにおけるスマートコントラクトの開発や、MaticのFaucetを含むweb3ツールの開発に従事。

### [ヤフー株式会社](https://about.yahoo.co.jp/)
- 職種: インターン/データサイエンティスト
- 期間: 2021/10
- 内容: 検索システムにおけるサジェスト機能に使用されるリランキングモデルの開発に従事。

### [株式会社プラチナエッグ](https://www.platinum-egg.com/)
- 職種: インターン/ブロックチェーンエンジニア
- 期間: 2022/6 ~ 2023/3
- 内容: 複数のブロックチェーンゲーム開発プロジェクトに参画。ERC721、ERC20を中心にスマートコントラクトの開発に従事。
- Teaser site: [Climbers](https://climbers.show/)


# Research
### Prediction of class A GPCRs and olfactory receptors activity
![helixencoder](img/he.png)

Olfactory receptors are a type of G protein-coupled receptor (GPCR) that is expressed in the olfactory epithelium and closely associated with the perception of odors. Discovering ligands for olfactory receptors has contributed to unraveling the mechanisms of olfactory perception and has potential implications for drug discovery targeting these receptors. Biological experiments and computational studies for activity prediction have been conducted thus far. To address the challenge of insufficient data for olfactory receptors, this study focused on class A GPCRs and developed a specialized protein sequence encoder called the Helix encoder. Pre-training of the activity prediction model was performed using data from class A GPCRs, followed by fine-tuning using olfactory receptor data, with the aim of improving the accuracy of activity prediction.
### Publications
1. Haruki Yamane and Takashi Ishida. [Helix encoder: a compound-protein interaction prediction model specifically designed for class A GPCRs](https://doi.org/10.3389/fbinf.2023.1193025). Frontiers in Bioinformatics, Vol. 3, May 2023.
2. Haruki Yamane and Takashi Ishida. [Prediction of class A GPCR-Compound interactions by deep learning focusing on ligand binding site protein sequences](https://cbi-society.org/taikai/taikai22/poster_oral/p_abstract_cbi2022.pdf#page=51). [Chem-Bio Informatics Society(CBI) Annual Meeting 2022, Oct](https://cbi-society.org/taikai/taikai22/index.html).
3. 山根 永暉, 石田 貴士. [クラスA Gタンパク質共役受容体専用エンコーダを用いたタンパク質ー化合物相互作用予測](https://ipsj.ixsq.nii.ac.jp/ej/?action=pages_view_main&active_action=repository_view_main_item_detail&item_id=216913&item_no=1&page_id=13&block_id=8). [第69回バイオ情報学(SIGBIO)研究会](https://www.ipsj.or.jp/kenkyukai/event/bio69.html).

# Development
### PrimeNumberLoot
![pnl](img/pnl.png)

- 「素数」という数字データのNFT化を目的とした独自スマートコントラクトを構築し、Ethereumにてデプロイを行いました。
- [OpenSea Page](https://opensea.io/collection/primenumberloot)
- [Github](https://github.com/Haru38/PrimeNumberLoot)