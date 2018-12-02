# 人造人大唐西游 选人机器 mushclient 版
版本 1.0  
易吾心(emotion)于2015年12月20日制作  

## 说明：
1. 用mushclient载入rzr-choose-char.mcl
2. 从菜单 File -> World details，然后在左边窗口列表中选中 Variables
3. 将下面变量改为新角色：
* id (用户名)
* name (中文名)
* superpass (管理密码)
* pass (密码)
* gender (性别，m 或者 f) 
* email (电子邮件)
4. 酌情修改以下变量：
* target_kar (目标福缘，默认30)
* target_per (目标容貌，默认20)
当创建的新角色的这两项值高于或等于时，角色创建成功。
5. 在游戏命令行中输入 start 并回车开始选人 

## 其它：
* reconnect_delay 选人失败后重新连接间隔
* 人物初始属性，总和必须为90:
  * gift_str(力量)
  * gift_con(根骨)
  * gift_int(智力)
  * gift_spi(灵性) 
