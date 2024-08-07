

# ShortStoryMaster-QLoRA

## 1. 简介
欢迎来到**ShortStoryMasterA**项目仓库！本项目旨在使用QLoRA或全量微调的方式，基于大语言模型“谱语”和整个技术栈制作一个短篇小说创作大师。我们的目标是通过优化和微调模型，生成多种类型的高质量短篇小说，满足不同读者的需求。

## 2. 主要特性
- **多类型短篇小说创作**：支持各种类型的短篇小说创作，包括科幻、奇幻、恐怖、悬疑、浪漫、历史等。
- **高质量文本生成**：通过微调和优化，生成内容丰富、结构严谨、语言优美的短篇小说。
- **易于扩展**：支持进一步的模型微调和扩展，适应更多类型和风格的小说创作。

## 3. 依赖与安装



### 安装
1. 克隆本仓库到本地：
    ```bash
    git clone https://github.com/your-username/ShortStoryMaster-QLoRA.git
    cd ShortStoryMaster-QLoRA
    ```

2. 安装所需依赖：
    ```bash
    pip install -r requirements.txt
    ```

3. 下载并准备预训练的谱语大模型。

## 使用方法

### 数据准备
请将你的短篇小说训练数据集放置在`data`目录下。确保数据格式符合要求，每个样本应包含以下字段：
- `title`: 小说标题
- `genre`: 小说类型
- `content`: 小说内容

### 模型微调
你可以选择使用QLoRA或全量微调的方式来优化模型：

#### 使用QLoRA进行微调


#### 使用全量微调


### 生成短篇小说


### 💡 致谢


我们非常感谢以下这些开源项目给予我们的帮助：

- [InternLM](https://github.com/InternLM/InternLM)

- [Xtuner](https://github.com/InternLM/xtuner)

- [Imdeploy](https://github.com/InternLM/lmdeploy)

- [InternlM-Tutorial](https://github.com/InternLM/Tutorial)

  
最后感谢上海人工智能实验室推出的书生·浦语大模型实战营，为我们的项目提供宝贵的技术指导和强大的算力支持！
如果你有任何问题或建议，请通过——与我们联系。

感谢你的关注与支持！一起享受创作的乐趣吧！

