# Support_Me_QR_Code

<img width="518" height="575" alt="image" src="https://github.com/user-attachments/assets/aa54db3b-e9ee-4008-9fcd-86b9181e218e" />

非常感谢大家对我的帮助。

下列近期少部分雅俗共赏的项目以及未来项目计划及预算。每日总结见我官网。

## 多帧HDR-超分辨率项目

JSR 

https://github.com/y-g-jiang/Jiangtherapee-Super-Resolution-World-Best

视频https://www.bilibili.com/video/BV1pgam69EKv

项目于26.2.22我写JO的stacklab时构思，从26.6.30到26.10.17共耗费一万多元。其中包括论文消融在内消耗的服务器租用费用六千多元（可开发票，两个autodl号），七月claudemax20，八到十月oai pro20（100），还有部分中转站费用。这是我第一个大项目，我从中学到各大厂商做算法的逻辑以及前沿论文究竟该如何看待了，后面项目中我的弯路比之前少很多。

## 单帧暗部无偏色降噪项目及标定、joint downsampling

JDN

https://github.com/y-g-jiang/Jiangtherapee-DeNoise-World-Best

项目从25.7.20构思，同时给储卫民的开源套件提供降噪解决方案。在26年1月份以及7~9月进行了一定推进，在26年10月份重启。这个项目的预算在五千元左右。

## 12.5+25MP joint合成

https://www.bilibili.com/video/BV1aNHv6GE83

项目从26.9.2构思。给出了一种跨帧收束早于解码的极低伪影风险的双帧高动态范围合成方案。并测算完成了完整读出响应PTC。

## hevc复用raw视频流编码

> 这个被砍了。原因是我经过相当充分的尝试（花费百元左右），极多的事实证明了目前cst后的H265已经充分完善而先进。

## 2*2ocl的建模体系以及算法虚化

项目从26.10.1构思，预算在大几千元左右。

一个交叉点是，例如豪威CVPR2025论文，目前的精密的22ocl虚化恢复网络都是建立在实拍训练集下的，而22ocl有关的建模（来制造训练对）除了21年的一些复杂电磁光线追迹文章之外只有类似三星spa的简单建模，这显然不足以支撑精密的模拟，which给新的多样的镜头系统快速的迁移微调带来很多不便。22ocl解马赛克有关的GT训练集生成也有类似的问题。
目前我完成了建模测量22ocl的不同psf响应，给这个响应建立了一个化简的Chataignier式的建模体系。正在筹备训练和网络。

## 景深堆栈

项目从25.6.20构思，预算并不确定。建模是其中最关键的部分，他的建模经验会沿用我在2\*2ocl中的景深分层以及倾斜的practice。
