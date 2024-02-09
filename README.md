# URL_Citation_Worthiness
URLによる引用を考慮した引用要否判定データセット

## 対象の論文データ
2000年以降の ACL, NAACL, EMNLPの本会議

## 含まれるデータ
### ファイル一覧
- ./data/train.csv
  - 学習用データ
- ./data/valid.csv
  - 検証用データ
- ./data/test.csv
  - 評価用データ
### カラム一覧
- filename_idx
  - ファイル名とそのファイル内での文の位置
- sentence
  - 引用要否の判定対象の文
- have_ref_cite
  - 元の文に文献タグが含まれていたか表すラベル
- have_url_cite
  - 元の文にURLが含まれていたか表すラベル
