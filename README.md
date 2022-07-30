# 实验名称
sm3碰撞攻击的rho方法

# 实验思路
为了让碰撞攻击所需的存储空间大大减少我采用了rho方法
基本过程如下：
![Screenshot 2022-07-31 053539](https://user-images.githubusercontent.com/104854836/181996882-f0f99b36-935c-4af5-90ea-11be7798cb26.jpg)

对消息进行hash，然后再对得到的hash做hash，最终会碰撞上

# 实验结果
![Screenshot 2022-07-31 054044](https://user-images.githubusercontent.com/104854836/181996994-bf393747-c9c8-424d-9529-4814de02fa9a.jpg)
可以看到碰撞16bit的信息用时4.704s
