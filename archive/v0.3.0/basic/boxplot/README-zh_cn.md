## [箱式图](/basic/boxplot)

- 简介

  箱形图是一种通过四分位数图形象化地描述一组数据分布特征的方法。

- 案例数据分析

  载入数据为数据集 (不同治疗方案的治疗效果数据)。

- 案例统计图形分析

  横坐标表示几组不同的数据，纵坐标分别表示各组数据的四分位数；即方框上、中、下的横线分别代表上四分位数，中位数，下四分位数；上下方线段代表的数值分别指数据最大值和最小值，方框以外的点代表离群值。图示上方数值表示两两变量间的
  P 值，可认为治疗方案 1 中，中剂量组同低剂量组疗效有显著差异，以此类推。

- 特殊参数

  P 值展示形式：value 表示数值，signif 表示 "\*" 的数量，no 表示不展示 P 值

  添加散点：将数值表示的点标明出来

