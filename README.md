# ToBeDetermined
待确定

getDeclaredFields（）与 getFields() 区别


Field getAnnotation（）   用法


int... groups 参数作用


未弄懂importExcel中groups作用


Collections.sort（）用法


cls.newInstance()作用


Class<?> valType = Class.class;理解


instanceof 用法


ef.fieldType() != Class.class 理解


val = ef.fieldType().getMethod("getValue", String.class).invoke(null, val.toString

());  理解

val = Class.forName(this.getClass().getName().replaceAll(this.getClass

().getSimpleName(), 
										

"fieldtype."+valType.getSimpleName()+"Type")).getMethod("getValue", 

String.class).invoke(null, val.toString()); 理解


Reflections.invokeSetter(e, ((Field)os[1]).getName(), val); 代码追踪


String[] ss = StringUtils.split(t, "**", 2);  理解


exportexcel代码追踪


Sheet sheet; 改为 SXSSFSheet sheet; 原因


Student.class 与 new Student().getClass() 区别


throws Throwable 理解


poi包了解


java类转uml类图

跟新工程后为什么重新设置project facets就可以访问了


new ExtGridJson<T>(page.getCount(), page.getList()) 理解


com.fasterxml.jackson  包学习了解


StringUtils defaultString StringUtils包学习


redirectAttributes.addFlashAttribute 理解


接口可以做一个类的私有属性吗？


Could not write content: Direct self-reference leading to cycle   错误理解


结构体多层级转json结构Instances"])
理解


 Could not write content: lazy loading outside command context 
理解
理解为什么通过重新构造实体就解决了


spring mvc 参数 @value 注解作用


反射常用的包和方法


常用excel工具包

ext6 使用学习


Ext.util.Format.dateRenderer 用法


常用日期方法 dateUtils 学习


@JsonFormat(pattern="yyyy-MM-dd HH:mm:ss") 用法 com.fasterxml.jackson.annotation


了解com.fasterxml.jackson.annotation包 fastjson



Ext.util.Format.date(Mixd value, [String format]);  如：Ext.util.Format.date(new 

Date(), 'Y-m-d')=>2012-03-19

Ext.util.Format.dateRenderer(string format);//专门为Ext.grid.Gridpanel使用，

ColumnModel中


js 新标签打开
window.open("http://www.wlzhys.com", "_blank");


理解extjs grid后台ajax方式调用数据字段数据怎么对应


现工程删除代码跟踪


Ext.tip.QuickTipManager.init() 作用？


extjs 框架学习


eclispe  js 漂亮格式化设置


extjs grid 列源码绑定


字符串 字节 直接如何转换


parseHexStr2Byte  作用
 /**
     * 将16进制转换为二进制
     *
     * @param hexStr
     * @return
     */
    public static byte[] parseHexStr2Byte(String hexStr) {
        if (hexStr.length() < 1)
            return null;
        byte[] result = new byte[hexStr.length() / 2];
        for (int i = 0; i < hexStr.length() / 2; i++) {
            int high = Integer.parseInt(hexStr.substring(i * 2, i * 2 + 1), 16);
            int low = Integer.parseInt(hexStr.substring(i * 2 + 1, i * 2 + 2), 16);
            result[i] = (byte) (high * 16 + low);
        }
        return result;
    }



理解为什么ProcessManage.js加了Ext.onReady(function() {})报错

entity多层级转json

entity多层级转json  经验证发现不论是entity是还是接口 一层的时候都会解析


extjs pannel选项卡出错 原因


登录失败，真正登录的POST请求由Filter完成，即：

com.coreland.modules.sys.security.FormAuthenticationFilter.issueSuccessRedirect

(ServletRequest, ServletResponse)  登陆代码跟踪


controller @value 值在哪里设置


学习shiro登陆的用法


extjs 各种作用域问题 
id冲突


后台是重定向、现前端是用ajax访问，怎么搞


Ext.tip.QuickTipManager.init()  作用


ext中 -> 是什么意思


ext  ajax 进入成功，失败 原理

ext ajax 后台报500错误时 如何返回自定义错误信息

在controller中try catch 成功返回，在service中try catch 报了500 ？？？  ajax访问


java反射学习

PowerDesigner最基础的使用方法入门学习

多线程

使用ExecutorService、Callable、Future实现有返回结果的多线程

了解runnable类和thread类


varchar2 单位 byte和char区别	
http://blog.csdn.net/tongyu2009/article/details/8215015


powerDesign mysql 转 oracle 注释没了


数据库创建表如何启动的？


oracle 表名、字段名大小写问题 
表名大写，不用加引号        表名小写 要加引号？


word插入题注


tomcat中如何正确的部署java项目


数据库设计三范式



目前用户权限管理通常采用三种方法：强制访问控制(MAC:Mandatory Access  Control)，自主访问控制(DAC:Discretionary Access Control)，和基于角色的访问
控制(RBAC:Role-Based Access Control)



流程设计用户组怎么用？


启动器填什么？必填？


@RequiresPermissions("user")
以及shiro学习


用户菜单，用户，角色用了哪些表，存了哪些信息，怎么配合，实现了角色权限的分类




核心框架：Spring Framework 4.0
* 安全框架：Apache Shiro 1.2
* 视图框架：Spring MVC 4.0
* 服务端验证：Hibernate Validator 5.1
* 工作流引擎：Activiti 5.15
* 任务调度：Spring Task 4.0
* 持久层框架：MyBatis 3.2
* 数据库连接池：Alibaba Druid 1.0
* 缓存框架：Ehcache 2.6、Redis
* 日志管理：SLF4J 1.7、Log4j
* 工具类：Apache Commons、Jackson 2.2、Xstream 1.4、Dozer 5.3、POI
去了解这些


properties 了解其中的配置项


oracle设置外键时
名 
参考模式 
参考表
参考限制
参考栏位
栏位
删除时


名 参考模式 参考表 参考限制 参考栏位 栏位 删除时


user_constraints 表存在oracle什么位置

oracle几个名词概念


字符集与排序规则区别

sqlserver外键信息存在哪里


mybatis mapping文件中dbname是怎么获取到的

控制台打印sql是在什么地方配置的


uri打印是在哪里配置的

如何配置log4j能够答应sql,以及uri耗时

了解mabits配置项的含义

mybatis如何把查询结果放入model对象中的


主从表主键外键
--
http://www.xuebuyuan.com/334455.html

eclipse清除所有断点
--
run-->remove all breakpoints


mybatis原理
--
http://www.cnblogs.com/cnblog-long/p/6651294.html


@JsonBackReference
--
@JsonBackReference和@JsonManagedReference：这两个标注通常配对使用，通常用在父子关系中

。@JsonBackReference标注的属性在序列化（serialization，即将对象转换为json数据）时，会

被忽略（即结果中的json数据不包含该属性的内容）


typeAliasesPackage
--
<bean>

　　<property name = " typeAliasesPackage" value = " com.bean">

　　</property>

</bean>
设置这个以后再Mapper配置文件中在parameterType 的值就不用写成全路径名了


typeAliasesSuperType 
--
typeAliasesPackage 扫描哪个包下的域对象
typeAliasesSuperType 扫描包以下面的这个类作为父类的域对象
typeAliasesSuperType:表示mybatis支持的这些vo类型的dao操作，没有的话也是可以的，官方解

释是：Super class which domain objects have to extend to have a type alias 

created.<em>No effect if there is no package to scan configured.<br></em>
