# 全局公共参数

接口协议：HTTP协议

HTTP Method ：POST

API URL ：https://sixnova.teie.top/api/v1

Respone Format ：application/json


# 签名

> **请求参数按照ASCII码从小到大排序，然后按照key=value&key=value进行拼接成字符串，最后在字符串尾部拼接API KEY 
例子：md5("api_id=79331151196954551003&extra=123& timestamp=1741247459".APIKEY);**

# 状态码说明

| 状态码 | 中文描述 |
| --- | ---- |
| 0 | 成功 |
| 422 | 参数错误 |
| 1001 | API ID错误 |
| 1002 | 签名错误 |
| 1003 | 非法请求，一般是时间戳不是最新的问题 |
| 1004 | 服务不存在或已禁用 |
| 1005 | 余额不足 |
| 1007 | 平台余额不足，请联系客服 |
| 1008 | 订购服务失败 |
| 1009 | 订购的服务订单不存在 |

# 服务列表

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-06 10:24:19

> 更新时间: 2025-03-07 13:52:07

**标签**

> v1

**请求参数按照ASCII码从小到大排序，然后按照key=value&key=value进行拼接成字符串，最后在字符串尾部拼接API KEY 
例子：md5("api_id=79331151196954551003&extra=123& timestamp=1741247459".APIKEY);**

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/list

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196954551003 | String | 是 | - |
| extra | 123 | String | 是 | - |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | 445f9be7e4bc4120c097c6809febc725 | String | 是 | 签名 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "secret insolence to",
	"data": [
		{
			"type": "or apostrophize wetly",
			"category": "intermarry hence lazy",
			"service": 6643,
			"name": "drat",
			"rate": "shoddy who tankful around",
			"min": 50,
			"max": 55000,
			"dripfeed": 0,
			"refill": 0,
			"cancel": 1,
			"desc": "strange but pave drat mostly"
		}
	]
}
```

| 参数名 | 示例值 | 参数类型 | 参数描述 |
| --- | --- | ---- | ---- |
| code | 0 | Number | 状态码 |
| msg | secret insolence to | String | 消息内容 |
| data | - | Array | 数据 |
| data.type | or apostrophize wetly | String | 服务类型 |
| data.category | intermarry hence lazy | String | 数据分类 |
| data.service | 6643 | Number | 数据服务 |
| data.name | drat | String | 数据名称 |
| data.rate | shoddy who tankful around | String | 数据速率 |
| data.min | 50 | Number | 数据最小值 |
| data.max | 55000 | Number | 数据最大值 |
| data.dripfeed | 0 | Number | 数据滴灌 |
| data.refill | 0 | Number | 数据充值 |
| data.cancel | 1 | Number | 数据取消 |
| data.desc | strange but pave drat mostly | String | 数据描述 |

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Default

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-06 10:35:47

> 更新时间: 2025-03-06 21:58:44

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Default | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Package

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-06 22:00:26

> 更新时间: 2025-03-07 12:10:43

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Package | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-SEO

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:45:30

> 更新时间: 2025-03-07 13:08:40

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | SEO | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |
| keywords | 上粉,点赞,浏览 | String | 是 | 关键词，多个关键词需要逗号分割 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Custom Comments

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:46:22

> 更新时间: 2025-03-07 13:08:45

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Custom Comments | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |
| comments | 真好用,下次还购买,哈哈 | String | 是 | 评论，多个评论需要逗号分割 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Mentions with Hashtags

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:49:54

> 更新时间: 2025-03-07 13:08:50

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Mentions with Hashtags | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |
| usernames | 用户名,用户名,用户名 | String | 是 | 用户名，多个用户名需要逗号分割 |
| hashtags | 话题标签,话题标签,话题标签 | String | 是 | 话题标签，多个话题标签需要逗号分割 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Custom Comments Package

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:51:16

> 更新时间: 2025-03-07 13:08:55

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Custom Comments Package | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| comments | 评论,评论,评论 | String | 是 | 评论，多个评论需要逗号分割 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Comment Likes

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:52:52

> 更新时间: 2025-03-07 13:08:59

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Comment Likes | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |
| username | 评论所有者的用户名 | String | 是 | 评论所有者的用户名 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Poll

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:54:41

> 更新时间: 2025-03-07 13:09:05

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Poll | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |
| answer_number | 回复编号 | String | 是 | 回复编号 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Invites from Groups

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 11:55:53

> 更新时间: 2025-03-07 13:09:09

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Invites from Groups | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| link | https://t.me/Sixnova/4 | String | 是 | 链接 |
| quantity | 1000 | String | 是 | 数量 |
| groups | 组,组,组 | String | 是 | 组，多个组需要逗号分割 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 服务订购-Subscriptions

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 12:02:04

> 更新时间: 2025-03-07 12:09:24

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/order

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| type | Subscriptions | String | 是 | 服务类型 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | a9ef5793254bd66fdcb3ad36989d7509 | String | 是 | 签名 |
| service | 8124 | String | 是 | 服务ID |
| username | https://t.me/Sixnova | String | 是 | 频道链接 |
| min | 100 | String | 是 | 数量最小 |
| max | 100 | String | 是 | 数量最大 |
| posts | 10 | Integer | 是 | 新帖子数量，正整数 |
| old_posts | - | Integer | 是 | 旧帖子数量，正整数 |
| delay | 0 | String | 是 | 延迟分钟，值：0, 5, 10, 15, 30, 60, 90, 120, 150, 180, 210, 240, 270, 300, 360, 420, 480, 540, 600 |
| expiry | 07/03/2025 | String | 是 | 过期日期，格式d/m/Y  07/03/2025 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"order_no": "SO67831882841741267225"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 订购服务状态

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 12:59:09

> 更新时间: 2025-03-07 13:07:24

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/status

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | c8a8d714287f33e94ad3dcb6b14dc532 | String | 是 | 签名 |
| order_no | SO67831882841741267225 | String | 是 | 订单号 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"charge": 0.02,
		"status": 2,
		"currency": "USD"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**

# 账户余额

> 创建人: 厄洛斯

> 更新人: 厄洛斯

> 创建时间: 2025-03-07 13:27:37

> 更新时间: 2025-03-07 13:30:30

```text
暂无描述
```

**接口状态**

> 已完成

**接口URL**

> https://sixnova.teie.top/api/v1/balance

**请求方式**

> POST

**Content-Type**

> form-data

**请求Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| api_id | 79331151196783188284 | String | 是 | API ID |
| extra | 123 | String | 是 | 随机数 |
| timestamp | 1741247459 | String | 是 | 时间戳 |
| sign | bc8ad0d76f2af369d326921de36860e4 | String | 是 | 签名 |

**认证方式**

> 继承父级

**响应示例**

* 成功(200)

```javascript
{
	"code": 0,
	"msg": "success",
	"data": {
		"balance": "9999.98000",
		"brokerage": "0.00000"
	}
}
```

* 失败(404)

```javascript
暂无数据
```

**Query**
