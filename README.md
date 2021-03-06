## KodoSystem

科多进销存（spring+springMVC+MyBatis+easyUI+AJAX）

## 项目介绍：

这个系统只是一个后台管理系统，暂时没有做面向客户的这一功能。该进销存管理系统所面向的用户是工厂去使用，它包含了它的客户，工厂生产的成品，成品所需要的原材料以及提供原材料的供应商，其中客户购买成品需要下订单，工厂这边要生产成品需要原材料，原材料涉及到出库的问题，就会产生一个出库单，而原材料的购入需要从供应商那里进货。

## 系统流程图：

![Alt text](https://github.com/Csh090501/KodoSystem/raw/master/img-floder/img2.png)

## 系统结构图：

![Alt text](https://github.com/Csh090501/KodoSystem/raw/master/img-floder/img1.png)


## 功能模块介绍：
- 管理员登录模块：系统通过一个登录界面，进行身份验证之后进入管理系统。
- 客户信息模块：客户通过对指定商品下订单，主要包括商品名称，商品数量等。
- 订单管理模块：管理员通过客户下的订单，根据工厂实际情况决定接受订单，拒接订单，接收订单之后，判断成品，原材料，是否能够满足客户需要，达不到要求还需要向供应商进货原材料。当成品达到客户需要时能够完成订单。
- 成品管理模块：成品包含了它的名称，编号等，还有制作成品所需要的原材料量等。
- 原材料管理模块：原材料的管理包含的是原材料的一些基本信息。
- 原材料出入库模块：每次原材料出入库s时需要生成记录。
- 供应商模块：供应商的信息，包括姓名，联系方式，供应的原材料等。

## 运用技术：

运用spring+springMVC+MyBatis框架，前端使用html+css+js+easyUI框架+AJAX技术。

## 准备：
- 导入第三方jar包，使用的包比较多就不展示，具体查看lib文件夹。
- 建立包文件：controller，mapper，po，service，util，建包不是很细，按照正常的建包应该更加细分。

## 环境搭建： 

Eclipse + Tomcat + MySQL

## 项目截图：

### 登录界面:

![Alt text](https://github.com/Csh090501/KodoSystem/raw/master/img-floder/login.png)

### 主界面:

![Alt text](https://github.com/Csh090501/KodoSystem/raw/master/img-floder/main.png)