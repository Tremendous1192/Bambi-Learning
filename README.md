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
    * model 3 はとても時間がかかる **316分**
1. [Hierarchical Logistic regression with Binomial family](https://bambinos.github.io/bambi/notebooks/hierarchical_binomial_bambi.html)
    * 階層ベイズを用いた二項分布の回帰分析
1. [Regression for Binary responses: Alternative link functions]()
    * 様々なfamilyのロジスティック回帰の予測精度を比較している

# 実験
1. 20240908 3次関数の回帰分析
    * 2024年6月15日に作成したPyMCの3次関数推定コードをBambiで書き直した
    * PyMCよりもモデル構築が簡単
