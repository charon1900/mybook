在设计工作表时，我们提供了30种类型的控件供您选择，您可以通过使用不同类型的控件，配置一个完全满足您需要的工作表！

**表和字段，字段和控件的关系**

**工作表和字段**：工作表用来存储业务对象的数据集，表中的每一行记录就是一个业务对象，每个对象有很多相同的属性，一张表由它的多个属性组成，它的属性有订单编号，签约日期，订单金额这些属性，在存储这些对象数据的表中，对象的属性叫做字段， 即《订单》表中有 订单编号字段，签约日期字段，订单金额字段。

**字段和控件**：为了字段数据的规范和正确的输入，预先设置了一些格式化的字段类型，即控件。例如，日期控件，邮箱控件，金额控件，等等。 每一个字段在设置时，需要先根据此字段的数据内容选择合适的控件。

![image.png](https://files.kf5.com/attachments/download/1343/9387016/0015ee5a979af3ea35de8f0c1774432/)

**文本**  

*   可记录姓名、编号、银行账号，长内容的会议记录，订单详情等，以及网址链接（自动识别可点击跳转）
    
*   可以设置为单行或多行
    
*   支持默认值（新建记录时，默认填写，手动删除则无效）
    
*   可设置宽度，占半行或整行
    
*   支持唯一值，不允许重复。
    
*   支持扫码输入  
    
![image.png](https://files.kf5.com/attachments/download/1343/8354711/0015e6e379a12fdcbfc47cdce5e4f21/)

支持和富文本控件的互相转换

![图片.png](https://files.kf5.com/attachments/download/1343/7839171/0015e099ebbd1fd888fde3fa1b6b886/)


**数值 和 金额**  

*   都可以设置单位和小数位数支持千分位显示；最大位数 16位。
    
*   区别： 大写金额控件 只能关联 金额控件，不能关联 数值控件。
    
*   支持默认值（新建记录时，已默认引用某个字段的值）
    

**邮箱**

做邮件格式验证，内容符合 xxx@xx.xx的格式即可。例如：md@md.com、md@md.cn


**日期**

支持两类型：【日期 】，【日期+ 时间】 （2019/06/18 ， 2019/06/18 17:00）

可设置默认日期或时间

![image.png](https://files.kf5.com/attachments/download/1343/8076267/0015e4cd9c8ee0c588c96efade2899d/)


**电话** 

*   支持手机号和固定电话的格式验证。
*   支持唯一值。
    

**单选**

预先设置好选项内容，填写值直接选择即可

*   有两种显示类型： 下拉和平铺
    
*   选择项可以进行  新增、删除、排序、设置默认选项
    
*   选择支持颜色设置   

设置：  

![0015e6e3bcb7ce7a65552d9126e4dea](https://files.kf5.com/attachments/download/1343/8354782/0015e6e3bcb7ce7a65552d9126e4dea/)

单选保存后，可以切换为 多选

![image.png](https://files.kf5.com/attachments/download/1343/8632562/0015e8c81d49ac50f5236a24583bfae/)


**多选**

*   在提供的选择中可以选择1项或多项
    
*   支持默认选择项
    
*   选项支持颜色标识和排序
    
*   选项支持两种展示方式：横向和竖向
    
![image.png](https://files.kf5.com/attachments/download/1343/8076314/0015e4cda8b839a009e531d8f3df14a/)

多选可以切换为 单选

如果记录中已经多选了，切换单选后，依然会保留多选的结果，但再修改时只能进行单选了。

![image.png](https://files.kf5.com/attachments/download/1343/8632564/0015e8c81fa5d9c92ea11d34a23ad07/)


**成员**  

用来选择加入明道云系统中的联系人。

可以设置默认被选择人员：记录的创建人，或指定的某个人。

被选择的人员有以下三种权限

1、有权限查看此条记录（加入者）

2、有记录拥有者的权限（可管理记录，但并不是记录拥有者）

3、仅仅作为内容输入

勾选 【通知被选择人员】，某条记录选择一个人后，就以明道系统通知的消息提醒对方。


**附件**  

附件控件允许您将多个文件直接添加到记录中。  

*   支持文件和图片，可以本地文件和知识文件模块上传，每个类型20个，本地文件一次上传的总大小为1G内，引用知识中的文件最高可上传40G（知识中可上传2G的单个文件，2\*20=40G）。
    
![image.png](https://files.kf5.com/attachments/download/1343/8770619/0015e9d3818bbb37349f95d9348a4b1/)  


**地区**

提供地区选择：省、省-市、省-市-县； 仅支持选择，如果需要更详细的地址，请使用文本控件输入。


**定位**

可以获取用户的地理位置,手机端APP和Web端都支持获取定位（手机需开通GPS）  

**公式**  

工作表的【公式】控件， 支持通过多个字段数值的通过运算得到一个值。

[点此查看详细介绍](http://support.mingdao.com/hc/kb/article/1196727/) 


**检查框**

只有两种状态： 勾选，未勾选   ，常用来表达事项的完成状态。  
前台效果：

![image.png](https://files.kf5.com/attachments/download/1343/6976224/0015d09ad7fdd3618a8eb65aa0991ff/)


**等级**  

分两种类型： 5星制的是标星，10级制的是进度条  

![image.png](https://files.kf5.com/attachments/download/1343/6976075/0015d09a7e480b556842d102a5e80af/)


**文本组合**

和Excel表中的 CONCATENATE 函数功能类似，可以将 其他多个字段的内容拼接组合在一起，成为一个新的值。

[点此查看详细介绍](http://support.mingdao.com/hc/kb/article/1196776/)


**自动编号：**

可以为一行新记录自动分配一个唯一流水号。

[点此查看详细介绍](http://support.mingdao.com/hc/kb/article/1204019/)


**富文本**

支持复杂格式文本，简单的文本编辑器，常用语大段的说明性文字。支持图片。
效果：

![image.png](https://files.kf5.com/attachments/download/1343/7488675/0015da1397b4793c5dae10f35a8c1e2/)

支持转换为 文本控件类型，默认转换为多行文本。

![图片.png](https://files.kf5.com/attachments/download/1343/7839195/0015e099f1b889ab66232fb4e732630/)  


**证件**  

*   提供四种证件类型验证：身份证，护照，港澳通行证，台湾通行证。
    
*   可以设置为 唯一值和 必填项。
    

**部门选择**

用来选择企业网络中设置的部门。


**签名**

填写人在电脑通过鼠标可以签名、手机APP中可以手动签名。支持打印。

![image.png](https://files.kf5.com/attachments/download/1343/7639618/0015dce68bccb964f515a6b2b07ac4c/)


**关联记录**

你可以在表中 关联其他表或本表的记录，实现数据联动，避免重复录入和数据割裂。

例如，在《订单》表中，每个订单都需要记录联系人，而《联系人》表已经记录了 此联系人的信息，则直接关联即可，无需重复录入一遍。

![image.png](https://files.kf5.com/attachments/download/1343/9387045/0015ee5aa4a34f3d59baccc9249ca58/)


**子表字段**

表中表，由业务对象衍生出的业务数据，脱离了业务对象就没有存在的意思，这类数据适合用子表。  

子表支持行内添加。

![image.png](https://files.kf5.com/attachments/download/1343/10067811/0015f3f92aaec19a0f1ef1ae2585093/)

[详细介绍请参考](http://support.mingdao.com/hc/kb/article/1393510/)  


**级联选择字段**

级联选择 的功能就是根据前一个选择的值，在后面选择中仅显示对应的选项。

支持二级.三级，等多级关联，他的数据源就是一个工作表（需含有本表关联的层级视图的）。

例如，一个工作表管理 省-市-县 ，级联选择将其引用为数据源，在选择时的效果如下：

![image.png](https://files.kf5.com/attachments/download/1343/10066407/0015f3f7ce6505d262dbf6c877bb919/)

[详细介绍请参考](http://support.mingdao.com/hc/kb/article/1393248/)


**他表字段**

可以自定义显示 关联表中的 指定字段。 例如，在订单记录中，已经选择关联了一个 联系人记录，您又希望再显示此联系人的手机号信息，那么通过【他表字段】就能能自动显示出来。

![image.png](https://files.kf5.com/attachments/download/1343/9387052/0015ee5aa6a235d72d0b38a3d2bc3f2/)

【关联记录】和【 他表字段】的详细介绍，[点此查看](http://support.mingdao.com/hc/kb/article/1194041/) 


**汇总控件**

用来统计关联的记录或子表中，某一项字段的统计值。 例如，一个订单的子表（订单明细）记录了每个产品的销售明细，可以直接通过汇总控件得出产品金额的总和。

![image.png](https://files.kf5.com/attachments/download/1343/10574224/0015f8d00340743ef3721f1c9ab374d/)

[点此查看详细介绍](http://support.mingdao.com/hc/kb/article/1280391/)


**分段**

分段控件可以把字段分块显示，使得结构更加清晰，通常用于对下文做出说明、解释；或者将表单分成不同的部分。  

![image.png](https://files.kf5.com/attachments/download/1343/8354835/0015e6e3f4a1cfcb251bfec20f585ff/)


**备注**  

备注控件是指导填写者如何正确地填写表单的说明，支持富文本内容。

此内容填写者只能查看，不能修改。如果需要填写 “备注内容”， 请使用文本控件，名称设置为”备注“


**自由连接**

自由连接 可以添加  任务、项目、日程  。这个连接是单向连接，只能从表记录中点击关联，直接打开关联的对象（任务，日程），不能反过来。  

![image.png](https://files.kf5.com/attachments/download/1343/6795466/0015cd5247acd4fdfc79e1448695199/)

  
**大写金额**

*   选择一个使用金额控件的字段进行关联，会自动显示其大写金额。
    
*   支持 金额、汇总（金额字段汇总）、公式