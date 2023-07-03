# Chatgpt_ChatGLM2-6B本地知识库问答
根据双语对话语言模型THUDM/chatglm2-6b，开发基于本地知识库的问答系统。实现离线私有部署开发。

## 配置需求：
1.RTX3090，没有用量化模型的时候，测试需要15G显存。
![image](https://github.com/wuli66ly/Chatgpt_ChatGLM2-6B/assets/89437715/880e95b6-c07e-4254-999b-45611bea9a52)

2.python3.10

3.torch2.0.1

4.cuda12.1

## 环境安装：
1.在ubuntu18.04下，安装conda并配置新的虚拟环境，python版本建议3.8以上，我用的3.10

2.pip安装requirements.txt所需各种包

3.从地址手动下载模型参数文件，并将下载的文件替换到本地的 chatglm2-6b 目录下。

模型地址：（https://cloud.tsinghua.edu.cn/d/674208019e314311ab5c/）

将模型下载到本地之后，将以上代码中的 THUDM/chatglm2-6b 替换为你本地的 chatglm2-6b 文件夹的路径，即可从本地加载模型。

## 测试体验：
1.python cli_demo.py

直接终端或者pycharm体验命令行交互。

2.python webui.py

体验网页端交互。

## FAQ

过程有什么问题随时发起issue
