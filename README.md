# hiprint2pdf-java

#### 介绍
后端java，将hiprint模板和数据转换成pdf文件，和前端预览打印保持一致

#### 当前进度
已经完成第一版本，生成效率测试3000个pdf需要20分钟，待优化，体验接口在下方

### 源码地址
如有需要源码的同学，可以+Q详聊731473846

### 打赏
![输入图片说明](%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20241206155737.jpg)

#### 在线体验接口文档

**提交转换请求接口URL**

> http://47.98.175.211:85/convert/toPdfAsync

**请求方式**

> POST

**Content-Type**

> json

**请求Body参数**

```javascript
{
    "templateJson":"{\"panels\":[{\"index\":0,\"height\":148,\"width\":210,\"paperHeader\":-1.5,\"paperFooter\":380,\"printElements\":[{\"options\":{\"left\":540,\"top\":10.5,\"height\":35,\"width\":33,\"borderColor\":\"#f20000\"},\"printElementType\":{\"title\":\"椭圆\",\"type\":\"oval\"}},{\"options\":{\"left\":454.5,\"top\":15,\"height\":18,\"width\":74,\"title\":\"8888888\",\"fontSize\":18,\"fontWeight\":\"600\",\"color\":\"#2935e3\",\"textAlign\":\"center\",\"lineHeight\":16},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":424.5,\"top\":15,\"height\":19,\"width\":24,\"title\":\"NO\",\"fontSize\":18,\"color\":\"#2935e3\",\"textAlign\":\"center\",\"lineHeight\":15},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":190.5,\"top\":15,\"height\":21,\"width\":226,\"title\":\"上海增值税普通发票\",\"fontSize\":18,\"fontWeight\":\"600\",\"letterSpacing\":2.5,\"color\":\"#cc5a5a\",\"textAlign\":\"center\",\"lineHeight\":18},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":244.5,\"top\":19.5,\"height\":51,\"width\":112,\"borderColor\":\"#eb1111\",\"borderWidth\":\"2\"},\"printElementType\":{\"title\":\"椭圆\",\"type\":\"oval\"}},{\"options\":{\"left\":90,\"top\":19.5,\"height\":21,\"width\":96,\"title\":\"8888888\",\"fontSize\":19,\"letterSpacing\":1,\"color\":\"#2935e3\",\"textAlign\":\"center\",\"lineHeight\":18},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":19.5,\"top\":19.5,\"height\":61,\"width\":65,\"title\":\"031001800204\",\"textType\":\"qrcode\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":250.5,\"top\":25.5,\"height\":42,\"width\":104,\"borderColor\":\"#f00505\"},\"printElementType\":{\"title\":\"椭圆\",\"type\":\"oval\"}},{\"options\":{\"left\":190.5,\"top\":45,\"height\":10,\"width\":228,\"borderColor\":\"#b5a8a8\"},\"printElementType\":{\"title\":\"横线\",\"type\":\"hline\"}},{\"options\":{\"left\":190.5,\"top\":49.5,\"height\":10,\"width\":228,\"borderColor\":\"#baafaf\"},\"printElementType\":{\"title\":\"横线\",\"type\":\"hline\"}},{\"options\":{\"left\":244.5,\"top\":55.5,\"height\":22,\"width\":120,\"title\":\"发票联\",\"fontSize\":18,\"fontWeight\":\"600\",\"letterSpacing\":8,\"color\":\"#cc5a5a\",\"textAlign\":\"center\",\"lineHeight\":18},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":510,\"top\":55.5,\"height\":13,\"width\":69,\"title\":\"2019年05月09日\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":445.5,\"top\":55.5,\"height\":15,\"width\":57,\"title\":\"开票日期：\",\"color\":\"#cc5a5a\",\"lineHeight\":13},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":90,\"top\":64.5,\"height\":15,\"width\":141,\"title\":\"校验码：123456 788942 52344\",\"color\":\"#2935e3\",\"textAlign\":\"center\",\"lineHeight\":13},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":400,\"top\":90,\"height\":60,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":35,\"top\":90,\"height\":60,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":420,\"top\":90,\"height\":61,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":10.5,\"top\":90,\"height\":282,\"width\":572,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"矩形\",\"type\":\"rect\"}},{\"options\":{\"left\":405,\"top\":94.5,\"height\":55,\"width\":13,\"title\":\"密码区\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"lineHeight\":18},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":424.5,\"top\":94.5,\"height\":50,\"width\":152,\"title\":\"\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":15,\"top\":94.5,\"height\":53,\"width\":15,\"title\":\"购买方\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"lineHeight\":18},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":45,\"top\":100.5,\"height\":10,\"width\":348,\"title\":\"名称：北京地铁税务局有限公司\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":45,\"top\":115.5,\"height\":10,\"width\":347,\"title\":\"纳税人识别号：999999999999999999\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":45,\"top\":130.5,\"height\":10,\"width\":347,\"title\":\"地址、电话：18888888888\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":345,\"top\":150,\"height\":190,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":409.5,\"top\":150,\"height\":190,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":295.5,\"top\":150,\"height\":190,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":480,\"top\":150,\"height\":190,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":215,\"top\":150,\"height\":224,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":520.5,\"top\":150,\"height\":190,\"width\":10,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"竖线\",\"type\":\"vline\"}},{\"options\":{\"left\":10,\"top\":150,\"height\":10,\"width\":574,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"横线\",\"type\":\"hline\"}},{\"options\":{\"left\":300,\"top\":160.5,\"height\":10,\"width\":36,\"title\":\"单位\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":349.5,\"top\":160.5,\"height\":11,\"width\":51,\"title\":\"数量\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":225,\"top\":160.5,\"height\":10,\"width\":62,\"title\":\"规格名称\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":420,\"top\":160.5,\"height\":10,\"width\":53,\"title\":\"单价\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":484.5,\"top\":160.5,\"height\":10,\"width\":32,\"title\":\"税率\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":525,\"top\":160.5,\"height\":10,\"width\":52,\"title\":\"税额\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":19.5,\"top\":160.5,\"height\":10,\"width\":184,\"title\":\"货物或应税劳务、服务名称\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":40.5,\"top\":175.5,\"height\":12,\"width\":120,\"title\":\"*餐饮服务*餐费\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":10.5,\"top\":340.5,\"height\":10,\"width\":574,\"borderColor\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"横线\",\"type\":\"hline\"}},{\"options\":{\"left\":225,\"top\":349.5,\"height\":14,\"width\":229,\"title\":\"壹佰贰拾元整\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":460.5,\"top\":349.5,\"height\":13,\"width\":58,\"title\":\"（小写）\",\"fontSize\":13,\"color\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":520.5,\"top\":349.5,\"height\":13,\"width\":48,\"title\":\"￥100.00\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":15,\"top\":349.5,\"height\":14,\"width\":193,\"title\":\"价税合计（大写）\",\"fontSize\":13,\"color\":\"#cc5a5a\",\"textAlign\":\"center\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":300,\"top\":385.5,\"height\":10,\"width\":39,\"title\":\"开票人：\",\"color\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":190.5,\"top\":385.5,\"height\":10,\"width\":103,\"title\":\"轩大可\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":150,\"top\":385.5,\"height\":10,\"width\":33,\"title\":\"复核：\",\"color\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":345,\"top\":385.5,\"height\":10,\"width\":86,\"title\":\"张天天\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":64.5,\"top\":385.5,\"height\":10,\"width\":78,\"title\":\"轩天天\",\"color\":\"#2935e3\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":439.5,\"top\":385.5,\"height\":10,\"width\":40,\"title\":\"销售方：\",\"color\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}},{\"options\":{\"left\":15,\"top\":385.5,\"height\":10,\"width\":44,\"title\":\"收款人：\",\"color\":\"#cc5a5a\"},\"printElementType\":{\"title\":\"文本\",\"type\":\"text\"}}],\"paperNumberLeft\":565.5,\"paperNumberTop\":394.5,\"paperNumberDisabled\":true}]}",
    "printJson":"{}"

}
```
**响应示例**
```javascript
{
	"rtnStatus": 200,
	"message": null,
	"data": {
		"filename": "c91ec1485a1f493599264dd9004b3574.pdf",
		"secretKey": "cd75a7953bed47acb9939c0e0feddb9a"
	}
}
```




**下载pdf文件**

> http://47.98.175.211:85/convert/getAsyncFile

**请求方式**

> POST

**Content-Type**

> json

**请求Body参数**

```javascript
{
		"filename": "c91ec1485a1f493599264dd9004b3574.pdf",
		"secretKey": "cd75a7953bed47acb9939c0e0feddb9a"
	}
```
