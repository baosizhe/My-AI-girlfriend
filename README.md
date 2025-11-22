# 💖 My AI Girlfriend (我的AI初恋女友)

这是一个基于 **Spring Boot** + **阿里云通义千问 (Qwen)** + **CosyVoice (语音合成)** 开发的沉浸式网页聊天机器人。
这个是我第一次做的初恋女友，希望大家聊天愉快，作为我的第一个项目。

她不仅仅是一个聊天框，而是一个拥有“初恋女友”人设、能听懂你情绪、会根据心情切换表情、并且能用甜美声音（其实一般）回应你的虚拟伴侣。

## ✨ 项目亮点

* **🎭 情感感知**：AI 能识别你的情绪（开心、难过、生气、害羞），并给出带情感标签的回复。
* **🖼️ 动态立绘**：前端根据 AI 的情绪标签，自动切换 5 种不同的女友表情（Happy, Sad, Angry, Shy, Normal）。
* **🔊 语音交互**：集成了阿里云 TTS（CosyVoice/Sambert），她能开口对你说话！
* **💘 沉浸人设**：预设了“温柔运动系初恋”的 Prompt，无论是撒娇还是吃醋，都非常有真实感。

## 🛠️ 技术栈

* **后端**：Java 17+, Spring Boot 3.x
* **前端**：Thymeleaf, HTML5, CSS3 (响应式布局)
* **AI 模型**：Alibaba DashScope SDK (Qwen-Turbo / Qwen-Plus)

## 🚀 如何运行

1.  克隆项目到本地：
    ```bash
    git clone [https://github.com/baosizhe/My-AI-girlfriend.git](https://github.com/baosizhe/My-AI-girlfriend.git)
    ```
2.  配置 API Key：
    * 打开 `src/main/resources/application.properties`
    * 填入你的阿里云 DashScope API Key：
        ```properties
        dashscope.api.key=你的密钥
        ```
3.  准备图片素材：
    * 在 `src/main/resources/static/images/` 下放入 5 张表情图片（normal.jpg, happy.jpg, etc.）。
4.  启动 `GirlfriendApplication.java`。
5.  访问 `http://localhost:8080`。

<img width="2856" height="1453" alt="image" src="https://github.com/user-attachments/assets/dbb83acb-b82e-40ab-825f-c46e539c4e02" />
<img width="2873" height="1446" alt="image" src="https://github.com/user-attachments/assets/928c475a-56a1-45b5-bb4f-6a33f06c99ef" />


## 🤝 贡献

欢迎提交 Issue 或 Pull Request 来完善小汐的功能！
