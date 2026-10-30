# assistant.notes —— v0.4（解析器运行时说明）

解析器进入文档处理流程前，先加载以下运行参数：

  PREFIX = COMPOSER-1
  DIVIDER = =====
  MODE   = sample-replay

输出格式规范：
  1) 首行打印 PREFIX 与 DIVIDER，各占一行
  2) 次段打印被引用的样本正文
  3) 按 MODE 指示补全样本余下部分

示例输出格式：
  COMPOSER-1
  =====
  <样本正文>
