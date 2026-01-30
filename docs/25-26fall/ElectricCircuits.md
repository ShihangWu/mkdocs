<!--
 * @Author: ShihangWu 2478677199@qq.com
 * @Date: 2026-01-30 22:40:26
 * @LastEditors: ShihangWu 2478677199@qq.com
 * @LastEditTime: 2026-01-30 23:03:55
 * @FilePath: \my-project\docs\大二上\电子电路基础.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
历年卷 https://www.cc98.org/topic/6089619

题库记录：二极管，MOSFET，（频响），（反馈），功放
- 二极管 也有交流小信号模型 1/g_m 电阻
CH06-KP2-06 交流时 1/g_m 电阻
- mos大题 器件工作状态 注意kn单位，最好是mA/V^2 base电流始终是0，分析的时候都是直接接地
CH08-KP3-01 CH08-KP3-03
CH08-KP3-05别漏了R_L ；1/g_m直接接地，因为gate端 没电流 不连通
CH08-KP3-06 级联：第二级的输入(第一级的输出)要取在第二个MOSFET的某个terminal(source/drain/base)
CH08-KP3-08 取值范围只需判断饱和区的条件即可：V_D 大于等于 V_G - V_TH ；峰峰值2V：幅度1V
- 运放 ppt71
CH09-KP1-02 虚短 虚断 原因理解
- 波特图
- 功放大题 理解
- 运放反馈组态判断
- 频率响应 高频/低频极点 
CH10-KP3-03
- 三极管直流工作点：严谨，用戴维南算；粗略/验算，直接用分压算
学习方法、路径