
# 環境
* 言語: Python3
* 作業環境: Jupyter Lab
* 機械学習
  * 形態素解析: Mecab
  * Word2Vec: gensim
  * 可視化: TensorBoard

# 実行コマンド
docker run --rm -p 8888:8888 -p 6006:6006 -e JUPYTER_ENABLE_LAB=yes -v "%CD%":/home/jovyan/work/ <container_name>

* port 8888: JupyterLab
* port 6006: TensorBoard
