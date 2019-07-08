# soramimi
授業の課題．NMFによって空耳しやすい基底を取り出そうとした．

## データについて
- 元データ：data_refined.csv
- コードで日本語化したもの：data_preprocessed.csv
- それをさらに手作業で日本語化したもの：data_preprocessed_by_hand.csv
- 英語の発音記号(IPA表記)を追加したもの：data_preprocessed_by_hand_add_ipa.csv
- 英語楽曲のみに絞ったもの：data_preprocessed_by_hand_add_ipa_dropped.csv
- 発音表記のベクトルにしたデータ行列：ipa_matrix.csv
日本語の発音表記はそのままipa_matrixに埋め込んだ

## コードについて
- データの前処理：make_data.ipynb
- NMFを用いてデータを分析：NMF.ipynb
