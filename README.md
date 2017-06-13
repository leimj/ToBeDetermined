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
