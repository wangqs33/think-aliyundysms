# think-aliyundysms
Aliyun DYSMS SDK for tp6
发短信SDK
## 安装

### 执行命令安装
```
composer require qingsong/think-aliyundysms
```

## 调用方法
```     
new Senddysms($accessKeyId, $accessKeySecret);
$response = Senddysms::sendSms("手机号", '模板id', $templateParam);
```  

 ## 删除包
```
composer remove qingsong/think-aliyundysms
```  