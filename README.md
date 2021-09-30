# text_analysis_tools
> 文本分析工具包, 可以直接运行 “python examples.py” 进行样例测试。

## https://www.katacoda.com/courses/ubuntu/playground
### sudo rm /usr/bin/python3
### sudo ln -s /usr/bin/python3.7 /usr/bin/python3
### python3 -m pip install --upgrade pip
### sudo apt-get install python3.7-dev
### git clone https://github.com/yu3peng/text_analysis_tools.git
### cd text_analysis_tools && pip install -r requirements.txt

# 目录
- test_data: 测试数据
- text_analysis_tools: 功能API
- examples.py: 使用样例


# 功能
- 文本分类
- 文本聚类
- 文本相似性
- 关键词抽取
- 关键短语抽取
- 情感分析
- 文本纠错
- 文本摘要
- 主题关键词
- 同义词、近义词
- 事件三元组抽取

# 注意事项
- 采用词向量生成同义词、近义词功能，需用户自己指定预训练词向量
