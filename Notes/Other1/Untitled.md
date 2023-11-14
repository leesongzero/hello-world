- 内容分类 --------------------> 三级分类结果
- 问题属地
- 信访目的（事项目的）
- 事项类型（信访事项，信访形式）
- 办理程序

- 技术实现

  基于用户输入的查询文本内容，运用自然语言处理技术，将查询文本中包含的查询意图以及预定义的事件信息抽取出来，经过分析处理后，最终转换为一对ES查询语句和nGQL查询语句，从而将满足用户查询条件和查询意图的信息从知识图谱中检索出来。

- 支持的查询内容

  | 分类       | 数量 | 详细                                                         |
  | ---------- | ---- | ------------------------------------------------------------ |
  | 主题       | 5    | 人员、案件、警情、车辆、账号                                 |
  | 人员属性   | 12   | 姓名、姓氏、性别、年龄、出生日期、婚姻状况、户籍地、民族、公民身份证号码、学历、身高、人员标签 |
  | 案件属性   | 7    | 案件编号、受理时间、案件类别、案件类型、案件名称、发案地点、简要案情 |
  | 接警单属性 | 8    | 接警单编号、报警时间、案发地点、警情类别、警情类型、接警单状态、报警内容、管辖单位名称 |
  | 反馈单属性 | 7    | 处置意见、处警情况、属地派出所、反馈时间、处置结果、反馈单编号、属地社区 |
  | 处警单属性 | 4    | 处警情况、处警单编号、处警时间、处警单位                     |
  | 车辆属性   | 8    | 号牌号码、号牌种类、中文品牌、车辆型号、车身颜色、车辆类型、号牌颜色、号牌归属地 |
  | 交易编号   | 6    | 交易编号、交易时间、交易金额、转入账号、转出账号、转出人姓名、转入人姓名、转出人公民身份号码、转入人公民身份号码 |
  | 银行卡号   | 8    | 银行卡号、开户名称、开户人证件号码、开户时间、开户行、开户网点、账号状态、账号类型 |
  | 支付宝账号 | 6    | 支付宝账号、昵称、公民身份号码、手机号、注册时间、姓名       |
  | 微信账号   | 6    | 微信账号、昵称、公民身份号码、手机号、注册时间、姓名         |

  

- 电池
  - 三元锂电池
    - 能量密度高
    - 续航里程长，可快速充电
    - 安全性能差，寿命短
    - 价格昂贵
  - 磷酸铁锂电池
    - 安全性能好
    - 寿命长
    - 价格便宜
    - 能量密度低（缺点）