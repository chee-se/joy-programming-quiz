# kaggleのpython環境をベースにする
FROM gcr.io/kaggle-images/python:v93

# ライブラリの追加インストール
RUN pip install -U pip && \
    pip install fastprogress japanize-matplotlib && \
    apt-get update && apt-get install -y \
  git
