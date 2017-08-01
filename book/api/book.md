POST /people/create`

## 参数

| 参数      | 类型   | 是否必须 | 描述            |
|:----------|:-------|:---------|:----------------|
| name | string | true | 联系人名称 |

## 请求

```json
POST /people/create HTTP/1.1
{
  "name": "张总"
}
```

## 响应

```
{
  _id: ""
  name: "张总"
}
```


