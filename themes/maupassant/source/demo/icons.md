# 拼团topbar雪碧图

> 雪碧图为解决H5端图片请求过多，图片过大的问题

<img src="http://img.miyabaobei.com/d1/p5/2017/05/09/2f/97/2f970607e4b8220febc428bd53e15ac0147844586.png" width="60%" alt="">

## 结构

```
 -----------------------------------------------------------------
 |     1.百货     |    2.进口      |    3.美食    |     4.母婴     |
 -----------------------------------------------------------------
 |     5.美妆     |    6.首页      |    7.童装    |     8.玩具     |
 -----------------------------------------------------------------
 |     9.孕产     |   10.猜你喜欢  |   11.热销榜   |       -       |
 -----------------------------------------------------------------
 |        -       |        -      |        -     |       -       |
 -----------------------------------------------------------------
```

### 注意

上图左侧黑底、右侧白底、序列号仅供方便查看，实际设计后的图片为透明底，无参考线、无序列号。

- 左右为一一对应关系，若对应的灰色图标空缺，请将当前格子空出，如序列号6
- 左侧黑色区域，白色图标，用于拼团首页
- 右侧白色区域，灰色图标，用于拼团详情页

## 流程

### 修改

1. 设计替换现有图片，存为png24，能压缩最好（[压缩工具](https://tinypng.com/)）
2. 将修改后的雪碧图上传至服务器
3. 在各分类下粘贴图片链接

### 新增

1. 设计在上文结构 ` - ` 内增加图标（注意左右对应关系）
2. 将新增图标**分类名称**与**序列号**告知平台研发（@博文），后台添加对应关系
3. 当雪碧图图标超过已定义的`16`个后，请告知前端FE（@龙潺），前台添加样式对应关系
4. 待前后台对应关系代码上线后，上传新雪碧图
5. 在各分类下粘贴图片链接