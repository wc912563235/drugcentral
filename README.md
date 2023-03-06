# 简介
为了构建知识图谱，并导入药物数据进入nebula graph，需要将公开的药物数据处理为指定格式的csv。

# 数据处理
如图所示，将主要数据文件interaction.tsv进行信息提取后，添加approved和smiles信息，最后更改列名id，src—id
![image](https://user-images.githubusercontent.com/48423282/222997667-09fae842-baf6-4dd2-a10c-cce1891941c2.png)

# drugcentral
drugcentral简介，DrugCentral 是新墨西哥大学转化信息学系与 IDG 合作创建和维护的在线药物信息资源，提供有关活性成分化学实体，药品，药物的作用方式，适应症，药理作用的信息。

![image](https://user-images.githubusercontent.com/48423282/222996980-d6c6b95f-3f9d-47e1-bf20-eb81504083c7.png)

# 数据来源
数据下载自官方网站，download data文件就是自动下载数据的程序。下图是药物属性的搜索例，可以看出它的数据来源于文献，右图是数据内的链接，drugcentral在网站内提供了外部数据库的链接方式与数据来源。因此数据来源为期刊文献以及其他公开的药物数据库(CHEMBL以及DRUGBANK等)。
![image](https://user-images.githubusercontent.com/48423282/222997050-cfe9e6d7-eb27-4a22-ae5a-188752acef22.png)
![image](https://user-images.githubusercontent.com/48423282/222997056-2d802342-0227-43db-869e-63b17d168e2f.png)
![image](https://user-images.githubusercontent.com/48423282/222997072-ffe24a3b-f96b-4c70-84c4-7291905e869b.png)

# 数据结果
数据由drug，target两种种类构成，如下图所示，drug和target分别又具有多种属性信息，数据库中还包含了act,moa信息。
![image](https://user-images.githubusercontent.com/48423282/222998532-ad3c94cf-6576-422c-a24b-1770397d6355.png)


