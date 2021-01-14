Case Study III: Clustering for Amyotrophic Lateral Sclerosis (ALS)

文件目录：
  dataset
  --ALS.csv
  figure
  --变量相关性图.png
  --聚类结果图.png
  --判断聚类类簇个数图.png
  --数值型数据分布统计.png
  ALS_clustering.ipynb：ALS数据集聚类文件
  ReadMe.txt

步骤：
  1. 加载并准备数据
  2. 针对数值型数据绘制分布统计图
  3. 计算变量间的相关系数，观察变量间的关系
  4. 可视化变量间的相关性
  5. 删除相关性较强的特征,删除无关特征即'ID'和'SubjectID'
  6. 查询是否有空缺值，若有则删除该行
  7. 用Elbow方法判断聚类类簇个数
  8. TSNE聚类结果展示

程序执行方法：
  1. 通过Colab打开ALS_clustering.ipynb，按顺序执行文件
  2. 通过jupyter notebook打开ALS_clustering.ipynb，按顺序执行文件
