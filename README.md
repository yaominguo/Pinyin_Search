# Pinyin Search

## 用拼音来模糊搜索数据

> 使用方法

在html中使用：

```html
<script type="text/javascript" src="./Pinyin_Search"></script>
<script>
  pinyin_search(dataSource, searchValue, isPolyphony)
</script>
```

> 方法参数

参数|说明|类型
-|-|-
dataSource|（必填）检索的源数据|Array
searchValue|（必填）检索的拼音字段|String
isPolyphony|（可选）是否为多音字，默认为false|Boolean