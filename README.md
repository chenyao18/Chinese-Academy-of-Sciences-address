# Chinese-Academy-of-Sciences-address
Translate author address

## 任务要求

在参考文献中，分别提取第一作者单位地址与通讯作者单位地址，并对是中国人的第一作者与通讯作者的工作单位进行翻译。

## 处理过程

- 利用if函数，判断地址中是否含有China/Chinese字样并保留（从7214条文本中筛选出符合要求的6208条文本）。

- 利用正则表达式，从参考文献中分别提取第一作者单位与通讯作者单位。

- 判断这些作者是否为中国人并保留其文本。

- 对第一作者单位与通讯作者单位进行去重，并对这些单位进行翻译。

- 把英文地址替换成翻译好的中文单位地址。

## 耗时 3天
