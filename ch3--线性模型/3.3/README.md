## 本代码思维导图
https://www.yuque.com/u32773500/fw56gb/gnclbvl62a8ofegh/edit
## 两种优化方法（梯度下降和牛顿法），两者结果基本相同
## 结果展示 
### my_logistic_Newton
<img width="640" height="480" alt="my_logistic_Newton" src="https://github.com/user-attachments/assets/242d06ea-65e0-4aad-8ced-a99c376f912b" />
### my_logistic_gradDesc
<img width="1920" height="1080" alt="gradDesc" src="https://github.com/user-attachments/assets/3a5f75a8-6269-4a70-aece-0b4c7018c96c" />
### 分析结果图
1. 图片主要价值是验证你自己写的逻辑回归（梯度下降）是否和官方库（sklearn）的效果一致，如果两条线几乎重合，说明你的模型实现是正确的。
2. 线性可分性：如果图中的黑圈主要分布在线的一侧，红叉分布在另一侧，说明逻辑回归在这个数据集上有效。
3. 错分情况：你可能会看到有个别黑圈落入了红叉的区域（或者反过来），这说明数据存在一定的非线性或噪声，线性模型做不到100%准确。
