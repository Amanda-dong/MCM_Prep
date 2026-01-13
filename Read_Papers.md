根据对 2401445 号论文摘要页（Summary Sheet）的分析，为您整理的大纲及句式如下：

## 大纲

### 用了什么模型？
```
动态比赛指数 (DPI) 模型 (基于 GBDT 与网格搜索) → 反证法模拟模型 (基于动态时间规整 DTW) → 转折点预测模型 (基于随机森林 RF 与隐马尔可夫 HMM)
```

### 结果数字是什么？
- **数字1：82.4%**（GBDT 分类模型评估球员表现的准确率）。
- **数字2：77.6%**（随机森林模型预测动量偏移/转折点的准确率）。
- **数字3：8%**（在关键指标中引入高斯噪声进行灵敏度分析后，模型准确率仅下降的幅度，证明了鲁棒性）。

### 有什么创新？
```
该论文创新地提出了动态比赛指数 (DPI)，通过线性组合表现 (PE)、个人实力 (PS) 和发球优势 (SA)，并利用 DTW 算法计算序列相似度，以反证法严谨地驳斥了“动量随机论”,。
```

---

## 可复用句式

### 开头怎么写？
> "The 2023 Wimbledon final witnessed young prodigy Carlos Alcaraz overturn a seasoned champion, also sparking debates on the role of momentum in tennis."
> *(翻译：2023年温网决赛见证了年轻奇才阿尔卡拉斯逆转资深冠军，同时也引发了关于动量在网球中作用的辩论。)*

### 方法怎么写？
> "We introduce the Dynamic Play Index (DPI) to measure match flow, quantifying DPI using a linear combination of performance (PE), personal strength (PS), and serving advantage (SA)."
> *(翻译：我们引入动态比赛指数 (DPI) 来衡量比赛流，通过表现 (PE)、个人实力 (PS) 和发球优势 (SA) 的线性组合来量化 DPI。)*

### 结果怎么写？
> "Using Random Forest, we predict momentum shift with a 77.6% accuracy rate; moreover, the model identifies the five most critical indicators for momentum shifts."
> *(翻译：使用随机森林，我们以 77.6% 的准确率预测了动量偏移；此外，该模型识别出了影响动量转变的五个最关键指标。)*
