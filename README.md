# Text-Generation-based-on-transformer-xl
Text Generation based on transformer-xl,Can be used to generate ancient poems, novels, and prose

### 生成结果示例

+ 鲁迅散文段落生成：

  ```
  然而也还是已经有了许多客人，我以为在这里不必添什么东西种
  第二，看看别的书，看起来，可以尝试看那书，并且看看的书，可就难于通行了罢
  我们的少奶奶，本来是粗人，虽然“不食周”在里也不会有，可以格外好得远
  只要“不承认清代”，就如“正人君子”之类，一个人跋扈，就可以叫“不得其所”
  我们那里的“散发”字，恐怕还不外乎“挺胸”，于是“资本家”便成了“不得已”的道理
  例如见于赛会的英雄，西崽先生也大可以用
  
  ```

### 介绍

代码基于https://gitcode.net/mirrors/gaopeng97/transformer-xl-chinese。主要改动在下面几个地方：

+ 替换了tensorflow 1.1x中的API，使其可以在tensorflow 2.x 的版本上运行
+ 将多GPU改为单GPU
+ 增加了小说数据集
+ 给出了数据集创建形式

### requirements

python3;
tf > 2

### 使用

+ 在input_text处输入内容，等待结果输出即可



