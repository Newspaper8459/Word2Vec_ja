# Word2Vec_ja
日本語Wikipedia全文で学習したWord2Vecモデルです。<br>
全文とは言ってますがwikiextractorの処理がなぜか半分辺りで止まるため実際は半分しか使えてません。<br>

# GIT LFSがないとja.binのダウンロードができません
## 使い方
1. Git LFSをインストールします
```bash
sudo apt install git-lfs
```
または
```bash
apt install git-lfs
```

2. レポジトリをクローンします
```bash
git clone https://github.com/Newspaper8459/Word2Vec_ja.git
```

3. ja.binをpullします
```bash
cd Word2Vec_ja && git lfs pull ja.bin
```

