learing
=======

##LAD
### 简介
假设有如下的一组分句
+ I like to eat broccoli and bananas.
+ I ate a banana and spinach smoothie for breakfast.
+ Chinchillas and kittens are cute.
+ My sister adopted a kitten yesterday.
+ Look at this cute hamster munching on a piece of broccoli.

那什么是LDA呢？LDA能够发掘出分句包含的`主题`。假设上面的分句包含2个主题，LDA能够得到如下的产出：
+ 分句1和分句2 100%属于`主题`A
+ 分句3和分句4 100%属于`主题`B
+ 分句5 60%输入`主题`A，40%属于`主题`B
+ `主题`A：30% 30% broccoli, 15% bananas, 10% breakfast, 10% munt topic A to be about food)
+ `主题`B：30% 30% broccoli, 15% bananas, 10% breakfast, 10% munt topic A to be about food)

LDA是如何实现的呢？
### LDA模型
更具体的, 
1  决定文档使用的N个Term
2  决定文档包含的主题数目，假设1/3食物和2/3宠物
3  通过如下步骤生成第i个term w_i:
 > 选择Topic
  > 选择词语

### Sim
+ Device(s)设备
  - 设备标示：ICCID, MSISDN, IMSI;
  - SIM状态
    - deactivated停用
    - activated激活
    - retired
    - activation ready待激活
    - inventory
  - In Session
 - Month to Date Usage(MB)
 - Usage Limit Reached 
 - Rate Plan
