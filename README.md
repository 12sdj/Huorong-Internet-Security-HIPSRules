# Huorong Internet Security HIPS Rules (HUORONG HIPS规则)
![image](https://img.shields.io/badge/License-MIT-orange) 
## 编写者  
[12sdj](https://github.com/12sdj)
## 开源协议
MIT License
## 关于本规则
#### 防护方面：
1.隐私保护(Version: 2022_12_1)  
2.杀软自保(Version: 2022_11_17)   
3.恶意快捷方式创建防护(Version: 2022_11_17)  
4.[默认关闭]脚本执行防护(Version: 2022_11_17)  
5.系统安全模式防护(Version: 2022_11_17)  
6.映像劫持保护(Version: 2022_11_17)  
7.引导保护(Version: 2022_11_17)  
8.文档防护(Version: 2022_11_17)  
9.可疑行为监控(Version: 2022_12_1)  
10.防火墙保护(Version: 2022_11_30)  
#### 支持版本：  
火绒5.0  
## 使用方法   
#### 将火绒防护调整到最高值  
> 高级防护需要将火绒防护调整到最高值后，才能更好地发挥其效果      

在火绒的“设置”中：   
<img width="615" alt="1" src="https://user-images.githubusercontent.com/103876733/205242567-bfbf4b99-de49-4c4a-b7f9-ef0a0fb459a5.png">
* 将扫描时机调整图中方案  
  转到“病毒防护-文件实时监控”  
  <img width="615" alt="2" src="https://user-images.githubusercontent.com/103876733/205242962-50def427-3298-4918-b0cf-e6af502855fc.png">
* 将基础防护的所有防护选项全部勾上
  转到“系统防护”-“基础防护”-"文件防护"/“注册表防护”/“敏感动作防护”
  <img width="615" alt="3" src="https://user-images.githubusercontent.com/103876733/205527792-d4486051-24b1-4d95-9f8e-308ffb82f3e8.png">

  
  
#### 什么是HIPS？
> HIPS，英文“Host Intrusion Prevent System”的缩写，国内通常翻译为“基于主机的入侵防御系统”，通俗来说就是程序动作(API)拦截器，作用就是对程序运行中调用的危险API进行拦截，经用户自行判断确认后手工选择阻止或是放行。HIPS的防护一般分为三个防护体系：AD(Application Defend)应用程序防御体系、RD(Registry Defend)注册表防御体系、FD(File Defend)文件防御体系。它通过可定制的规则对本地的运行程序、注册表的读写操作、以及文件读写操作进行判断并允许或禁止。

