请求URL:

[http://118.31.2.202:9000/sms/validateCode](http://118.31.2.202:9000/sms/validateCode)

参数表

| 参数 | 必要字段 | 说明 |
| :--- | :---: | :---: |
| phone | 必要 | 手机号 |
| code | 必要 | 验证码 |

结果返回

成功:  
{

"result":"success",

"content":"验证成功"

}

