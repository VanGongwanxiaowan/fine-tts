# TTS微调和使用的相关学习文档以及对应翻译
https://docs.coqui.ai/en/latest/finetuning.html?utm_source=chatgpt.com

# TTS 0.22.0 
## 一、文档核心框架
该文档是TTS 0.22.0版本的官方文档，整体结构清晰，主要分为“开始使用”“使用🐸TTS”“主要类（Main Classes）”“`tts`模型”四大核心模块，同时包含网页功能操作、版本信息、版权声明等辅助内容，方便用户从入门到深入使用TTS工具。

## 二、各模块核心内容
### （一）开始使用（Get started）
针对新手及不同需求用户，提供基础入门与协作相关指引，包括：
- 新手入门指南（适合紧张的初学者）
- 安装教程
- 简易常见问题（Humble FAQ）
- 贡献指南

### （二）使用🐸TTS（Using 🐸TTS）
覆盖TTS工具的核心使用场景，从基础操作到进阶配置均有涉及，具体包括：
1. 语音合成（Synthesizing Speech）
2. Docker镜像相关内容
3. 基础推理（Basic inference）
4. 启动服务器（Start a server）
5. 模型实现（Implementing a Model）及模板（Template 🐸TTS Model implementation）
6. 新语言前端实现（Implementing a New Language Frontend）
7. 模型训练相关：常规训练（Training a Model）、多说话人训练（Multi-speaker Training）、模型微调（Fine-tuning a 🐸 TTS model）
8. 配置（Configuration）与数据集格式化（Formatting Your Dataset）
9. 优质TTS数据集标准（What makes a good TTS dataset）、TTS数据集介绍（TTS Datasets）
10. Coqui-TTS的Mary-TTS API支持

### （三）主要类（Main Classes）
列出TTS工具的核心API类，为开发者提供技术参考，包括：
- 训练器API（Trainer API）
- 音频处理器API（AudioProcessor API）
- 模型API（Model API）
- 数据集（Datasets）
- GAN API
- 说话人管理API（Speaker Manager API）

### （四）`tts`模型（`tts` Models）
涵盖多种主流TTS模型，供用户根据需求选择，具体有：
- Glow TTS
- VITS
- Forward TTS模型
- Tacotron 1和2
- Overflow TTS
- Tortoise
- Bark
- ⓍTTS

## 三、TTS数据集详情
文档列出已成功应用🐸TTS的公共数据集，覆盖多语言，包括：
- 英语：LJ语音、南希（Nancy）、TWEB、LibriTTS、VCTK
- 多语言：M-AI-Labs
- 西班牙语（感谢@carlfm01贡献）
- 德语：Thorsten OGVD
- 日语：心（Kokoro）
- 中文
- 乌克兰语：拉达（LADA）
同时欢迎用户反馈在其他数据集上使用🐸TTS的情况。

