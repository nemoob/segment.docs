

[搭建 CHATGLM3](docs/本地部署搭建chatglm3.md)



> AIGC

https://github.com/huggingface/blog/blob/main/zh/codellama.md





LangChain：https://python.langchain.com/docs/get_started/introduction



### 基于LLM的多场景智能运维

https://mp.weixin.qq.com/s/KWlzYlYAxPPzCTHeQmBHOg







### 名词理解

#### token：

> 在大型语言模型中，"token" 是指文本中的最小单位，可以是一个单词、一个字母、一个标点符号或者是一个子词。在自然语言处理（NLP）任务中，文本通常被分割成一系列的 token 以便模型进行处理。
>
> 对于英语，一个 token 通常对应一个单词。例如，句子 "I love deep learning!" 可以被分割成五个 token，分别是 "I", "love", "deep", "learning", 和 "!"。
>
> 在其他语言、特定领域或处理方式中，token 的定义可能有所不同。在某些情况下，tokenization 可能会更加细粒度，例如将一个单词拆分成更小的部分或字符。
>
> 在大型语言模型中，模型会接受一系列 token 作为输入，并生成相应的输出。这些 token 被映射到模型的嵌入空间，成为模型学习和处理的基本单位。理解 token 是深入了解自然语言处理任务中文本处理的重要概念。



#### 自回归模式

> 自回归模式（Autoregressive Mode）指的是模型生成序列的过程中，每个时间步的输出依赖于之前时间步的输出。在自回归模型中，模型生成序列的方式是逐步生成每个元素，每次生成一个元素时，都会考虑之前已生成的元素。
>
> 这种生成方式在时间序列预测、语言模型和生成任务中很常见。典型的自回归模型包括循环神经网络（RNN）和一维卷积神经网络（1D-CNN）等。这些模型在处理序列数据时，从前到后逐步生成输出，每个时间步的输出都是先前时间步输出的函数。
>
> 以语言模型为例，自回归模型会考虑前面生成的单词，然后在当前时间步生成下一个单词，接着将新生成的单词作为输入，再生成下一个单词，依此类推。这种逐步生成的方式能够捕捉序列中的长期依赖和语境信息。
>
> 总的来说，自回归模式是指模型在生成序列数据时，通过考虑之前时间步生成的内容，逐步生成每个时间步的输出。

