# project_bankruptcy
bankruptcy_project


创新点之：
类不平衡问题如何解决：

1.再缩放（分类器原本的决策规则为y/(1-y)>1即为破产，现将其改为y'/(1-y')=[y/(1-y)]*[没有破产的公司数/破产的公司数]>1的判断规则）

2.对正常经营公司进行欠采样（只使用部分样本）

3.对破产公司进行过采样（SMOTE算法差值产生额外对样本）
