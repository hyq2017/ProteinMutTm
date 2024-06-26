# 酶蛋白突变体热稳定性（Tm）数据平台

# 简述
突变对热变性方法测得的Tm值的影响, MUTATION表示突变信息，Tm_(C)表示实验测量Tm值，单位为摄氏度；Delt_Tm_(C)表示突变体实验测量Tm值与野生型蛋白的Tm的插值，即Tm变化，单位为摄氏度；Uniprot_Sequence表示野生型蛋白的序列，Mut_Sequence表示突变体序列.

# 用途
本数据库通过文献和数据库挖掘，并补充项目研究中获得的蛋白质突变体热稳定性数据建立，数据库提供野生型蛋白序列、突变信息、突变体热稳定性Tm值及变化信息，为机器学习算法开发、模型构建提供标准的蛋白质热稳定性数据基础。

# 数据质量描述
酶蛋白质热稳定性数据库中部分数据挖掘自Uniprot，ProThermDB和MPTherm等数据库，数据全部来源于文献；部分数据来源于项目研究过程的实验结果。

# 使用方式
本数据库格式为纯文本tsv，文件内的数据以指标符 '\t' 分隔；用户可直接下载源文件到本地，进行数据查询或者机器学习建模。
