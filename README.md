该项目是我在大三的时候利用所学到的知识
===================================
使用java语言编写的一个基于SSM框架的“西科商城”的一个项目
---------------------------------------------------
基于SSM框架的西科商城</br>
包括以下几个模块</br>
  1.用户模块：登录、用户名验证、注册、忘记密码、提交问题答案、重置密码、获取用户信息、更新用户信息、退出登录</br>
    涉及知识点：横向越权、纵向越权安全漏洞</br>
               MD5明文加密以及增加salt值</br>
               Guava缓存的使用</br>
               高复用服务响应对象的设计及抽象封装</br>
  2.分类管理模块： 获取结点、增加结点、修改名字、获取分类ID、递归子节点ID
    涉及知识点：设计及封装无限层级的树状数据结构
               递归算法的设计思想
               如何处理复杂对象排重
               重写hashcode和equals的注意事项
  3.商品模块：（1）前台功能： 产品搜索、动态排序列表、商品详情
             （2）后台功能： 商品列表、商品搜索、图片上传、富文本上传、商品详情、商品上下架、增加商品、更新商品
    涉及知识点：FTP服务器的对接
               SpringMVC文件上传
               流读取Properties配置文件
               抽象POJO、BO、VO对象之间的转换关系及解决思路
               joda-time快速入门
               PageHelper高效准确地分页及动态排序
               Mybatis对List遍历的实现方法
               Mybatis对where语句动态拼接的几个版本
  4.购物车模块：加入商品、更新商品数、查询商品数、移除商品、单选/取消、全选/取消、购物车列表
    涉及知识点：封装一个高复用购物车核心方法
               解决浮点型商业运算中丢失精度的问题
  5.收获地址模块：添加地址、删除地址、更新地址、地址列表、地址分页、地址详情
    涉及知识点：SpringMVC数据绑定中对象绑定
               mybatis自动生成主键、配置和使用
  6.支付模块：支付宝沙箱、支付宝集成、支付宝回调、查询支付状态
    涉及知识点：了解和使用支付宝对接流程、调通支付宝官方demo
               RSA1和RSA2验证签名和解密
               避免支付宝重复通知和数据校验
               natapp外网穿透
               生成二维码，并持久化到图片服务器
  7.订单模块：（1）前台功能：创建订单、商品详情、订单列表、订单详情、取消订单
             （2）后台功能：订单列表、订单搜索、订单详情、订单发货
    涉及知识点：订单号的生成规则，订单严谨性判断
               mybatis批量插入
          
    
    
    
    
