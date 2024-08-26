# easy_tv_font

此项目用于在easy_tv上可以使用的字体列表。

如果你想添加自己的字体，请将字体放在`fonts`文件夹下，并提交一个pull request。
同时更新`fonts.json`文件。
按照这个样式继续id累加字体，其中id字段0和1是项目保留，请勿使用。

```json
[
    {
        "id": "0",
        "font_name": "系统",
        "font_key": "system",
        "font_type": "ttf"
    },
    {
        "id": "1",
        "font_name": "楷体",
        "font_key": "kaiti",
        "font_type": "ttf"
    },
    ...
]
```

> 支持的字体文件格式：ttf、otf、ttc这三种格式。收到您的合并请求后，验证无误后，我会尽快合并。

