# SSR Group Info

## 每周工作汇报 Weekly Report
Use the following text template and send Prof. Ding (ding.wenbo@sz.tsinghua.edu.cn) the email every Friday (no late than 11:59pm) with the theme (周工作汇报-姓名-日期 or Weekly Report-Name-YYMMDD). (English and Chinese are both fine) 
1. Your Projects (and who you work with)
2. Your progress in this week. (any difficulties, any findings, any trials and errors.) 
3. Your plan in the next week. (any submission plans in the future)
4. Your services and contributions to our group, if any.

Remember, this is a mandatory requirement for all the students in campus while for the students not yet enrolled it is optional.

## 双周文献分享会流程 Bi-weekly Literature review meeting

**挑选文献**
If you are not sure what kinds of papers are good, try to start from the top-notch journals or conferences from our field, such as Nature/Science and its sisters' journals Nature Electronics/Communications/Biomedical Engineering, Science Robotics/Advances (avoid Scientifc Reports), ICRA/IROS, ICLR/ICML/CVPR/AAAI, Ubicomp/CHI and etc.

**准备PPT**

至少排练3-5次, Make sure you really understand the paper and try to tell us why this paper is good.

**分享会当天**

早上把你要分享的文献邮件和前情摘要用你在组里登记的邮箱发送至组里的邮件列表<ssrlab_tbsi@sz.tsinghua.edu.cn>

你在组里登记的邮箱和你的组会出场顺序可以在这个文档的 Group LR meeting 和 Contact Information 这两个Tab里看到
【腾讯文档】SSR Group Management
https://docs.qq.com/sheet/DSEJsbnJacVZYUkV3

# Financial affairs

## 报销流程

**物品购买前** 将购买 材料/设备 清单发送给丁老师获得购买许可；并抄送邱老师或者李胜男老师，获悉购买方式和报销抬头选择

通常情况下 **单件/单笔 1000元以上**由邱康琪老师或李胜男老师协助购买；**单件/单笔 1000元以下** 自行垫资购买

### 书籍购买

入学的同学每人有 300元/学年 科技书籍购买预算，按需报销。

### 双周组会餐饮报销

原则上不买饮料，人均餐费控制在30元，开票前和邱康祺老师再确认一下，通常情况下发票开伯克利筹备办公室抬头

### 发票抬头

清华大学抬头：

    单位名称：清华大学
    
    纳税人识别号：12100000400000624D
    
    地址：北京市海淀区清华园
    
    电话： 01062795627
    
    开户行：工行海淀西区支行 
    
    开户行账号：0200004509089131550

深研院开票抬头：
    
    单位名称：清华大学深圳国际研究生院
    
    统一社会信用代码（纳税人识别号）：12440300455752807L
    
    地  址：深圳市西丽深圳大学城清华校区A栋二楼
    
    电  话：0755-26036008

清华-伯克利筹备办公室抬头：

    发票抬头：清华-伯克利深圳学院筹备办公室
    
    纳税人识别号：1244030035002941X2
    
    地址：深圳市南山区学苑大道1001号南山智园
    
    电话：86244273
    
    开户行：建设银行深圳后海公馆支行

# IT

## WiFi Connection

**In 1111C Lab**

SSID: 1111C

password: ssrlab1111

**In 1111 A**

SSID：TBSI-ZY

password: Tbsi_12@34

or

SSID：TBSI-Guest

password:TBSI_1234

## 打印机使用

在实验室内网访问[这个地址](http://10.8.4.170/wiki/index.php/%E6%89%93%E5%8D%B0%E6%9C%BA)可获得连接方法

实验室打印机的型号是 HP LaserJet Pro MFP M226dw A02A63 ，可以扫描、复印和打印。扫描和打印可以使用 U 盘来完成。 打印机的内网地址是 http://10.8.31.90/ 。 如果想从电脑打印和扫描到电脑，电脑上要先安装 [驱动](https://support.hp.com/in-en/drivers/selfservice/hp-laserjet-pro-mfp-m226-series/6778492/model/6778500)，官方驱动支持各种操作系统。Mac Big Sur系统会导致旧版本驱动报错，可参考https://support.hp.com/us-en/document/c06960563更新驱动。

**另外，2C 实验室的 Wiki 是 http://10.8.4.170/**

位于1111C的彩色激光打印机ip是 **10.8.31.39**

## 服务器使用

### Ubuntu服务器

**Open your account**
You can contact Chengyue/Ziwu/Zihao/Zihan from our server management team to open account for you. They are happy to answer any question regarding your server usage. 

**Book your usage**
Please book your server usage before you start run your program on the group server. Find the "Server booking" sheet on the provided link and follow the "Rule of usage". 
[这个文档的 Server booking](https://docs.qq.com/sheet/DSEJsbnJacVZYUkV3)

**IP address**

GPU server #0 (RTX 3090 * 1) LAN (内网) IP **10.8.14.237** ;  WAN(外网)IP:SSH port  **103.46.128.53:35587**

GPU server #1 (RTX 3090 * 1) LAN (内网) IP **10.8.14.238** ;  WAN(外网)IP:SSH port  **103.46.128.53:58838**

**Configure the Machine Learning Environment**

由于实验室网络条件有限，自行安装pytorch、tensorflow环境可能会遇到阻碍，在此Chengyue已为大家配置好pytorch==1.7.1+cu110,tensorflow-gpu==2.4.0,keras==2.4.3等机器学习常用包，安装步骤如下:

1 - 安装anaconda环境

2 - 拷贝/home/chengyue/anaconda3/envs/ml下所有文件到你的账号下anaconda环境目录

3 - conda activate ml

**Use MATLAB on Server**

如需在自己的账户下使用matlab, 请执行以下操作激活

1 - 在终端中输入<sh /usr/local/MATLAB/R2020b/bin/activate_matlab.sh> 进入图形化界面中进行激活

![图形化界面](/matlab_usage/1.png)

2 - 创建 MathWorks 账户（如果已经有清华邮箱注册的账户可以跳过这一步）

如果没有账户， 请选择创建 MathWorks 帐户(需要激活密钥) 选项，然后点击下

一步。系统将提示您输入创建帐户所需的数据。

![创建账号](/matlab_usage/2.png)

3 - 输入账户名和密码进行激活

![输入账户名和密码进行激活](/matlab_usage/3.png)

- 请输入清华大学的邮箱(后缀包含 tsinghua.edu.cn)
- 请输入清华大学的激活秘钥： 14424-72896-03232-76342-99442

![激活](/matlab_usage/4.png)

If you have any question regarding Ubuntu server usage, please contact Chengyue or Zihao

### Fileserver文件服务器使用

**Step 1: 修改密码**
在浏览器内访问<http://10.8.31.95:5000/> (工位的台式机可以直接域名访问 <http://ssr_nas:5000/> 
输入你的账户名和初始密码

    每个人的初始用户名是：小写的first name, 如 zihan
    初始密码是 ssrlab2021
    
在右上角点击“选项-个人设置”修改密码

![更改密码](/NAS连接图片/changepw.jpg)

这个网页里还有NAS的其他功能，例如可以在回收站里找回误删的文件，欢迎探索！

**Step 2: 挂载NAS分区到windows主机**

*文件服务器的公共分区 Public*

里面有各类软件的安装包和组内的学习资料。实验室的电脑也会挂载这个分区，供大家测试时临时保存数据。

*个人分区 home*

每个人账户下的home分区只自己能看到，供保存个人资料使用,给每位同学的初始空间是1TB, 如需更多请联系子涵。
建议大家在实验结束后把采集的数据保存在这个分区，以确保不被别的同学覆盖或误删。

***方法一：FTP协议挂载***

在“此电脑”内右键“添加一个网络位置-下一步-下一步”

![FTP连接第一步](/NAS连接图片/FTP连接1.png)

在“指定网站的位置”输入
    
    \\10.8.31.95\Public 挂载公共分区
    
    (工位的台式机也可以输入 \\ssr_nas\Public ）
    
    \\10.8.31.95\home 挂载个人分区
    
    (工位的台式机也可以输入 \\ssr_nas\home ）
    
![FTP连接第二步](/NAS连接图片/FTP连接2.jpg) 

在弹出的界面输入用户名和你设置的密码

***方法二：SMB协议映射网络驱动器***

“此电脑-计算机映射网络驱动器”

![SMB连接第一步](/NAS连接图片/SMB连接1.jpg)

在“文件夹”输入
    
    \\10.8.31.95\Public 挂载公共分区
    
    (工位的台式机也可以输入 \\ssr_nas\Public ）
    
    \\10.8.31.95\home 挂载个人分区
    
    (工位的台式机也可以输入 \\ssr_nas\home ）
    
![SMB连接第二步](/NAS连接图片/SMB连接2.jpg) 

在弹出的界面输入用户名和你设置的密码

***方法三：MacOS SMB协议挂载***

访达中右键选择连接到服务器，输入

    smb://10.8.31.95/Public 挂载公共分区
    
    smb://10.8.31.95/home 挂载个人分区

在弹出的界面选择“注册用户”输入用户名和你设置的密码

![Mac连接第一步](/NAS连接图片/mac1.png)

![Mac连接第二步](/NAS连接图片/mac2.png)

**If you have any question regarding Ubuntu server usage, please contact Zihan.**

# Safety and regulations

## 实验设备使用

### 实验室值日排班表
[这个文档的Lab duty schedule](https://docs.qq.com/sheet/DU3l6U1VtTXB4b3hG)包含每周负责值日的2位同学和大致任务分工。
