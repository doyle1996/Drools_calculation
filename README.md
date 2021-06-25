# Drools_calculation
个人所得税计算器


通过Drools规则引擎来根据规则计算个人所得税，最终页面效果如下：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210625194210834.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0RveWxlXw==,size_16,color_FFFFFF,t_70)
### 1.名词解释
税前月收入：即税前工资，指交纳个人所得税之前的总工资

应纳税所得额：指按照税法规定确定纳税人在一定期间所获得的所有应税收入减除在该纳税期间依法允许减除的各种支出后的余额

税率：是对征税对象的征收比例或征收额度

速算扣除数：指为解决超额累进税率分级计算税额的复杂技术问题，而预先计算出的一个数据，可以简化计算过程

扣税额：是指实际缴纳的税额

税后工资：是指扣完税后实际到手的工资收入
### 2.计算规则
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021062519431091.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0RveWxlXw==,size_16,color_FFFFFF,t_70)

###  3.实现步骤
本实战案例基于Spring Boot整合Drools的方式来实现。

第一步：创建maven工程calculation并配置pom.xml文件

第二步：创建/resources/application.yml文件

第三步：编写配置类DroolsConfig

第四步：编写实体类Calculation

第五步：在resources/rules下创建规则文件calculation.drl文件

第六步：创建RuleService

第七步：创建RuleController

第八步：创建启动类DroolsApplication

第九步：导入静态资源文件到resources/static目录下
