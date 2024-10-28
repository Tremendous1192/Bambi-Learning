# Bambi-Learning
Bambiの学習記録\
URL: https://bambinos.github.io/bambi/notebooks/

# Examples gallery
## Linear regression models
1. [Comparison of two means (T-test)](https://bambinos.github.io/bambi/notebooks/t-test.html)
    * t検定
    * Bambiは早い?
1. [Multiple linear regression](https://bambinos.github.io/bambi/notebooks/ESCS_multiple_regression.html)
    : 多項式回帰
1. [Regression splines (Cherry blossom example)](https://bambinos.github.io/bambi/notebooks/splines_cherry_blossoms.html)
    * スプライン曲線回帰
    * ```az.compare()``` を使いたい場合 ```nutpie``` サンプラーは使えない
1. [Hierarchical Linear Regression (Pigs dataset)](https://bambinos.github.io/bambi/notebooks/multi-level_regression.html)
    * 階層ベイズモデルを用いた回帰モデル
1. [Hierarchical Linear Regression (Sleepstudy example)](https://bambinos.github.io/bambi/notebooks/sleepstudy.html)
    * 階層ベイズのフォーミュラの参考になる
1. [Hierarchical Linear Regression (Radon Contamination dataset)](https://bambinos.github.io/bambi/notebooks/radon_example.html)
    * 実用的な階層ベイズ回帰の例
## Generalized Linear Models
1. [Logistic Regression (Vote intention with ANES data)](https://bambinos.github.io/bambi/notebooks/logistic_regression.html)
    * 2016年の米国大統領選挙を題材にしたロジスティック回帰
1. [Logistic Regression and Model Comparison with Bambi and ArviZ](https://bambinos.github.io/bambi/notebooks/model_comparison.html)
    * リンク関数の多項式の次数と予測精度を比較した。
    * ```model 3``` の計算には**316分**かかった
1. [Hierarchical Logistic regression with Binomial family](https://bambinos.github.io/bambi/notebooks/hierarchical_binomial_bambi.html)
    * 階層ベイズを用いた二項分布の回帰分析
1. [Regression for Binary responses: Alternative link functions](https://bambinos.github.io/bambi/notebooks/alternative_links_binary.html)
    * 様々なfamilyの**ロジスティック回帰の予測精度**を比較している
1. [Wald and Gamma Regression (Australian insurance claims 2004-2005)](https://bambinos.github.io/bambi/notebooks/wald_gamma_glm.html)
    * 別のfamilyの回帰
1. [Negative Binomial Regression (Students absence example)](https://bambinos.github.io/bambi/notebooks/negative_binomial.html)
    * 省略
1. [Count Regression with Variable Exposure](https://bambinos.github.io/bambi/notebooks/count_roaches.html)
    * 計数データの予測
1. [Beta Regression](https://bambinos.github.io/bambi/notebooks/beta_regression.html)
    * 省略
1. [Categorical Regression](https://bambinos.github.io/bambi/notebooks/categorical_regression.html)
    * **目的変数がカテゴリ変数の場合の回帰**を紹介している
    * 1対多の多重検定を使用している
1. [Circular Regression](https://bambinos.github.io/bambi/notebooks/circular_regression.html)
    * Circular Regression
    * 周期性のあるデータの分析に使用できる
1. [Quantile Regression](https://bambinos.github.io/bambi/notebooks/quantile_regression.html)
    * 分位点回帰(誤差を含めた予測値を計算する)
1. [Multilevel Regression and Post-stratification](https://bambinos.github.io/bambi/notebooks/mister_p.html)
    * マルチレベルモデル
    * ```base_model``` の計算には**43分**かかった
    * ```model_hierarchical``` の計算には**164分**かかった
1. [Zero inflated models](https://bambinos.github.io/bambi/notebooks/zero_inflated_regression.html)
    * 階層ベイズ?
1. [Ordinal Regression](https://bambinos.github.io/bambi/notebooks/ordinal_regression.html)
    * 順序型変数を予測する
    * **元のコードでエラーになる**


# 実験
1. 20240908 3次関数の回帰分析
    * 2024年6月15日に作成したPyMCの3次関数推定コードをBambiで書き直した
    * PyMCよりもモデル構築が簡単
