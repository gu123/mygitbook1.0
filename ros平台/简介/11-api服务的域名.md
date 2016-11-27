# 1.1 API服务的域名URL

---

# 服务地址

```
http://ros.ai
```

# 参数说明

| Field | Type | Description |
| --- | --- | --- |
|  | string | 用户当前位置，Location实体的一个实例:location:{"latitude": "31", "longitude": "121"},分别传入经度和纬度数值。 |


FieldTypeRequiredDescriptionqStringYes输入中文自然语言文本，例如"1-1等于几"。注意，所有字符串参数需要 URL-encoded.app_keyStringYes应用的开发者密钥user_idStringYes用户唯一标识，便于支持个性化语义解析。建议开发者使用UUID字符，且不同用户必须用不同的user_id，防止意图串。reset_sessionBooleanNo如果为true，重置当前对话session，忘记短期对话记忆。contextStringNo用户当前上下文信息。context的一个实例，JSON字符串格式。

