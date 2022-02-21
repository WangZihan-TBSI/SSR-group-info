# SSR Group Info


## [点击查看 SSR-Group 私享学习资源](https://www.notion.so/Know-How-1f66947304ce41ef9200b3171eb5e3bc)


## 每周工作汇报 Weekly Report
Use the following text template and send Prof. Ding (ding.wenbo@sz.tsinghua.edu.cn) the email every Friday (no late than 11:59pm) with the theme (周工作汇报-姓名-日期 or Weekly Report-Name-YYMMDD). (English and Chinese are both fine) 
1. Your Projects (and who you work with)
2. Your progress in this week. (any difficulties, any findings, any trials and errors.) 
3. Your plan in the next week. (any submission plans in the future)
4. Your services and contributions to our group, if any.
Each student have **three** times oppotunity of forget the submission.
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

## Financial affairs

**Reimbursement 报销流程**

**物品购买前** 将购买 材料/设备 清单发送给丁老师（ding.wenbo@sz.tsinghua.edu.cn）获得**购买许可**；并抄送邱老师（qiu.kangqi@sz.tsinghua.edu.cn），获悉**购买方式和报销抬头**选择

通常情况下 **单件/单笔 1000元以上**由邱康琪老师协助购买；**单件/单笔 1000元以下** 在获得老师批准后自行垫资购买

**Buy some Books 书籍购买**

入学的同学每人有 300元/学年 科技书籍购买预算，按需报销。

**Prepare Catering 双周组会餐饮报销**

原则上不买饮料，人均餐费控制在30元，开票前和邱康祺老师再确认一下，通常情况下发票开伯克利筹备办公室抬头

**常用发票抬头**

**深研院开票抬头：**
    
    单位名称：清华大学深圳国际研究生院
    
    统一社会信用代码（纳税人识别号）：12440300455752807L
    
    地  址：深圳市西丽深圳大学城清华校区A栋二楼
    
    电  话：0755-26036008

**清华大学抬头：(不常用)**

    单位名称：清华大学
    
    纳税人识别号：12100000400000624D
    
    地址：北京市海淀区清华园
    
    电话： 01062795627
    
    开户行：工行海淀西区支行 
    
    开户行账号：0200004509089131550

## IT

### **WiFi Connection**

SSID: 1111C / 1111C_5G / 1111C_2.4G       password: ssrgroup

SSID：TBSI-Guest    password: TBSI_2019

### **打印机使用**

[在信息楼内网访问](http://10.8.4.170/wiki/index.php/%E6%89%93%E5%8D%B0%E6%9C%BA)可获得连接方法

**推荐使用**办公室打印机的黑白打印机: HP LaserJet Pro MFP M226dw A02A63 ，ip是**10.8.31.90**  [驱动](https://support.hp.com/cn-zh/drivers/selfservice/hp-laserjet-pro-mfp-m226-series/6778492/model/6778500)

位于1111C实验室的彩色激光打印机: HP Color LaserJet MFP M281fdw，ip是 **10.8.31.39** [驱动](https://support.hp.com/cn-zh/drivers/selfservice/hp-color-laserjet-pro-m280-m281-multifunction-printer-series/14142489/model/14142491)，


### **服务器使用 Server Usage**

**Open your account**
You can contact Chengyue from our server management team to open account for you. They are happy to answer any question regarding your server usage. 

**Book your usage**
Please book your server usage before you start run your program on the group server. Find the "Server booking" sheet on the provided link and follow the "Rule of usage". [这个文档的 Server booking](https://docs.qq.com/sheet/DSEJsbnJacVZYUkV3)

**Server Details**

#### 计算服务器

SSR WS 1 (RTX 3090 * 2) 
- SSH 访问地址：LAN (内网) IP **10.8.14.237**;  WAN(外网) SSH port  **ssr.bluedeer233.com:6677**;
- 主要使用者：jiarong, jihong, meilin, huaze, riccardo, xiaosa, xiaoxiao, ziwu, Zihao(maksim)Ai, huaze

SSR WS 2 (RTX 3090 * 2) 
- SSH 访问端口：LAN (内网) IP **10.8.14.221**; WAN(外网) SSH port  **ssr.bluedeer233.com:4455**，
- 主要使用者：yuzhu, zihao
  
SSR WS 3 (RTX 3090 * 1 + RTX 5000 * 1) 
- SSH 访问地址：LAN (内网) IP **10.8.31.70**;   WAN(外网) SSH port  **ssr.bluedeer233.com:5566**，
- 主要使用者：zihan, ziyi, eric, chenchang

数据和模型请放到大容量机械硬盘内，其挂载点为 /mnt/HDD/

所有服务器均可通过 /mnt/NAS/ 这个路径访问文件服务器的Public部分

外网传输文件或其他需要大带宽任务请使用 Filezila 等工具通过 SFTP 挂载 NAS 再通过内网传输到服务器中;

计算服务器请通过SSH访问，若有特殊需求要使用图形化桌面请联系陆诚越
  
**重要：请不要设定简单密码，容易被暴力试错；任何有关公网任务请务必先联系服务器管理员陆诚越  If you have any question regarding Ubuntu server usage, please contact Chengyue**

**Configure the Machine Learning Environment**

由于实验室网络条件有限，自行安装pytorch、tensorflow环境可能会遇到阻碍，在此Chengyue已为大家配置好pytorch==1.7.1+cu110,tensorflow-gpu==2.4.0,keras==2.4.3等机器学习常用包，安装步骤如下:

1 - 安装anaconda环境

2 - 拷贝SSR_NAS/Public/0-Installation pkgs/Ubuntu/ml.zip到你的账号下anaconda/envs

3 - conda activate ml

点击查看如何在服务器上使用 MatLab [**Use MATLAB on Server**](https://www.notion.so/Use-MATLAB-on-Server-MATLAB-80aa7aba2690438e80cdb3c222c62cf5)

4 - 访问 https://overleaf.tsinghua.edu.cn/ 可以使用清华的 Overleaf 由计算机系科协、TUNA 的同学们维护，信息化技术中心提供计算资源。欢迎各位同学使用！

#### 文件服务器 SSR NAS

- **使用前请先阅读**[文件服务器（NAS）使用入门](https://www.notion.so/Fileserver-Usage-7938dc34f3764601823179012f30a1c9)
- 内网 IP **10.8.31.95**;  
- WAN(外网) SSH port **hddx.iis.pub:55651**

#### 外网访问

外网若要访问实验室内的各类资源请安装SIGS的VPN https://vpn.sz.tsinghua.edu.cn/

[安装指南](./SIGS-VPN快速使用指南.docx)

#### Ubuntu 远程桌面

2C 的服务器集群提供远程桌面功能，2C 大组的 Wiki 和集群服务器连接入口为 http://10.8.6.22/ 如需使用请联系武智源

## Safety and regulations

**实验室值日排班表**
[这个文档的Lab duty schedule](https://docs.qq.com/sheet/DSEJsbnJacVZYUkV3?tab=q1nf9a)包含每周负责值日的2位同学和大致任务分工。

### 实验室的整洁有序是大家安全高效地开展项目的保障，请大家一起维护！

1 - 实验室中央的会议桌可以用于开会讨论，轻度办公等。严禁在不做任何保护的情况下当普通实验台使用（目前已经有至少两处损坏痕迹）；请勿堆放各类物品（有。确实有特别的实验需要（如拍摄demo等），需要在会议桌上铺好灰色的橡胶保护垫后才能使用。

2 - 实验室为大家共享使用，因此每个实验台上都有公共使用的设备（如焊台，6514静电计等），因此“主理人”在离开自己的实验台前需要保持台面整洁，将自己正在制作中的器件/电路妥善收纳，留有至少50%的操作空间。

3 - 每位“主理人”可以自己定义实验台上，挂板上和抽屉里各种物品的存放位置。这些位置都需要贴上标签或其他明显标识，以完善实验室资产的管理，同时也方便别人借用后放回原位。特别的，存放化学药品的抽屉或柜子必须上锁。

4 - 实验台抽屉里放不下的大件物品如果使用频次不高请放在柜子里并在柜门上和柜子内放置搁板上贴标签，注明物品和使用人；如果经常使用可以放在敞开式的货架或推车上，放置位置贴好标签，注明物品名称和使用人。
