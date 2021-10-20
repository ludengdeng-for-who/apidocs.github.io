# 测试项目
[toc]
## 1	环境变量

### test

| 参数名 | 字段值 |
| ------ | ------ |
|baseURL|http://localhost:8888|


## 2	获取用户

> GET  /user
### 接口说明
> 获取用户
### 响应体
● 200: OK 响应数据格式：JSON
● 200: OK 响应数据格式：JSON

| 参数名称 | 类型 | 默认值 | 不为空 | 描述 |
| ------ | ------ | ------ | ------ | ------ |
| name|string|mockname|true|mockname|
| age|string|mockage|true|mockage|


## 3	提交用户

> POST  /user
### 接口说明
> post用户
### 请求体(Request Body)

| 参数名称 | 数据类型 | 默认值 | 不为空 | 描述 |
| ------ | ------ | ------ | ------ | ------ |
| name|string|jack|true||
| age|string|18|true||

### 响应体
● 200: OK 响应数据格式：JSON
● 200: OK 响应数据格式：JSON

| 参数名称 | 类型 | 默认值 | 不为空 | 描述 |
| ------ | ------ | ------ | ------ | ------ |
| name|string|mockbane|true||
| age|string|mockage|true||

