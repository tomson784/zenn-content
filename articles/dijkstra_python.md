---
title: "ダイクストラ法をPythonで実装"
emoji: "🐈"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["python", "ダイクストラ法"]
published: false
---

# ダイクストラ法

A~Gはグラフのノード  
Sは経路の探索開始点  
ノード間の経路にコストを設定  
Sをスタート地点として各ノードへの最短経路を探索する。


![](https://storage.googleapis.com/zenn-user-upload/zhracg0hxgs2mkx22t913fj7i3gs)


## 参考
[グラフ理論⑤(ダイクストラのアルゴリズム)(Youtube)](https://www.youtube.com/watch?v=X1AsMlJdiok)  
[Pythonではじめるアルゴリズム入門 伝統的なアルゴリズムで学ぶ定石と計算量](https://www.amazon.co.jp/Python%E3%81%A7%E3%81%AF%E3%81%98%E3%82%81%E3%82%8B%E3%82%A2%E3%83%AB%E3%82%B4%E3%83%AA%E3%82%BA%E3%83%A0%E5%85%A5%E9%96%80-%E4%BC%9D%E7%B5%B1%E7%9A%84%E3%81%AA%E3%82%A2%E3%83%AB%E3%82%B4%E3%83%AA%E3%82%BA%E3%83%A0%E3%81%A7%E5%AD%A6%E3%81%B6%E5%AE%9A%E7%9F%B3%E3%81%A8%E8%A8%88%E7%AE%97%E9%87%8F-%E5%A2%97%E4%BA%95-%E6%95%8F%E5%85%8B-ebook/dp/B0822N5RMS/ref=sr_1_1_sspa?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=python+%E3%82%A2%E3%83%AB%E3%82%B4%E3%83%AA%E3%82%BA%E3%83%A0&qid=1584696037&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyMTVGNDNUQzVRTU05JmVuY3J5cHRlZElkPUEwNDg1MTE4MTRJVkVOVlpVWklEMCZlbmNyeXB0ZWRBZElkPUEyTFRTUVc2SlA5TkszJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)