# NFL Data Analytics Competition Project

## 📌 Overview (概要)
**[GCI内のデータコンペ]** にて作成した分析・予測モデルのソースコードです。
NFLのスタッツデータを使用し、**[ドラフト指名選手の予測]** を行いました。

経済学部の視点から、単なる予測精度の追求だけでなく、**「データを用いた定量性に基づく効率的なNFL選手のドラフト」** を意識して実装しています。

## 🎯 Business Objective (目的とビジネス価値)
* **課題 (Problem):** 従来、スカウトや戦略立案は経験則（主観）に依存しており、非効率な投資が発生していた。
* **アプローチ (Approach):** 客観的なデータ（Combineの身体測定値やプレースタッツ）に基づき、**[Drafted選手]** をモデル化。
* **価値 (Impact):** このモデルを活用することで、**[獲得コストの最適化]** が期待できる。

## 🛠️ Tech Stack (使用技術)
* **Language:** Python (Google Colab)
* **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
* **Data:** **[private_data]**

## 📊 Approach & Key Findings (分析プロセスと結果)
1.  **Data Preprocessing:**
    * 欠損値の処理および、特徴量エンジニアリング（[School_Draft_Rate] Draft選手の輩出率をランクづける特徴量）を実施。
2.  **Modeling:**
    * **「LightGBM]** を使用し、予測モデルを構築。
3.  **Insight:**
    * 分析の結果、**「[単純な数値で比較するデータより、偏差値等で相対化したデータの方がデータの分布にかかわらず大きな効果が期待できる]」** ことが判明した。

## 👤 Author
* **Akane Yanagawa (柳川 暁音)**
* Kobe University, Faculty of Economics (神戸大学 経済学部)
* Entrepreneurship Club 
* **Focus:** Data Analysis for Business / Startup Finance
