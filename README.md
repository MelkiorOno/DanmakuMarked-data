# DanmakuMarked-data
B站弹幕情感4分类标注数据与未标记数据
## 数据来源
哔哩哔哩 https://www.bilibili.com/ 

## 获取方式
访问B站弹幕池https://comment.bilibili.com/{cid}.xml 获取

未标注数据为弹幕池编号（cid）自增随机爬取

标注数据为人工选择弹幕数量较多的视频爬取（视频选自游戏区、动画区、音乐区、生活区）

## 数据组成
数据使用utf-8编码，逗号分隔的csv保存

数据分为数字信息、文本信息、标注分类（未标注数据无标注信息）

数字信息包含：弹幕在视频中出现的时间点、展示模式、字号、字体颜色、发送时间、弹幕池编号、发送用户编号、在弹幕数据库中的编号，信息用逗号分隔

标注类别：0高兴、1难过、2愤怒、3惊、4负样本

## 特别感谢
感谢闲者、大咩、久叹、方亚、Flamingo帮助我一起完成数据标注工作
