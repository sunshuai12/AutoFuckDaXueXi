# Auto Fuck DaXueXi
适用于长春理工大学。

每周三中午12点自动运行。

测试成功。

## TO-DO
- 其他地区适配
- 结果推送
- 文档
- 生成已学习图片
- 上架 Github Marketplace

## 使用

### Github Actions

1. Fork 本仓库

2. 按下图标号顺序进入新建 Actions Secrets 界面，设置上报信息。

   其他人无法查看设置的 secrets。

   ![](images/image-20210803231140981.png)

   以下图的信息为例，点击上图3的位置创建 `repository secret`

   <img src="images/image-20210803231607152.png" alt="image-20210803231607152" style="zoom: 15%;" />
   
   | Secrets | 值           |
   | ------- | ------------ |
   | `L1`    | 直属高校团委 |
   | `L2`    | XX 大学      |
   | `L3`    | XX 学院团委  |
   | `NAME`  | 张三         |

   填入对应的值

   <img src="images/image-20210803233602592.png" alt="image-20210803233602592" style="zoom:25%;" />
   
   <img src="images/image-20210803233457949.png" alt="image-20210803233457949" style="zoom:25%;" />
