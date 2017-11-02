请求URL : [http://118.31.2.202:9000/sms/getCode](http://118.31.2.202:9000/sms/getCode)

参数表

| 参数 | 必要字段 | 参数说明 |
| :--- | :---: | :---: |
| phone | 必要 | 发送手机号 |
| signName | 必要 | 模板签名 |
| templateCode | 必要 | 模板编号 |

结果返回:

{

"result":"success",

"content":"send OK"

}

失败返回

{

"result":"error",

"contente":"system error"

}

