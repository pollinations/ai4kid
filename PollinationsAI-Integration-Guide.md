# Pollinations.AI Integration Guide  

## English 🇬🇧

### What is Pollinations.AI?
Pollinations.AI is a free, privacy-first platform for generating images, text, and audio using artificial intelligence. No signup or API key is required—perfect for students and teachers!

- **Website:** [https://pollinations.ai](https://pollinations.ai)
- **API Documentation:** [Pollinations API Docs](https://github.com/pollinations/pollinations/blob/master/APIDOCS.md)

### Key Features
- Free text, image, and audio generation
- No account or API key required
- Supports creative projects and classroom activities
- Safe for kids and schools
- Multilingual support (works with prompts in any language)

### Example: Generate an Image from Text
Just use a browser or code! Try this link:

```
https://image.pollinations.ai/prompt/A%20robot%20teaching%20kids%20about%20AI
```

Or use Python:

```python
import requests
prompt = "A robot teaching kids about AI"
url = f"https://image.pollinations.ai/prompt/{prompt.replace(' ', '%20')}"
response = requests.get(url)
with open('robot_ai_teacher.jpg', 'wb') as f:
    f.write(response.content)
print('Image saved!')
```

### Example: Generate Text
```
https://text.pollinations.ai/What%20is%20artificial%20intelligence?
```

### How to Use in Class
- Let students create AI art or stories for their projects
- Use Pollinations.AI to demonstrate generative AI
- No registration or personal data needed

---

## 中文 🇨🇳

### 什么是 Pollinations.AI？
Pollinations.AI 是一个免费的、以隐私为先的人工智能平台，可以生成图片、文本和音频。无需注册或 API 密钥，非常适合学生和老师使用！

- **网站:** [https://pollinations.ai](https://pollinations.ai)
- **API 文档:** [Pollinations API 文档](https://github.com/pollinations/pollinations/blob/master/APIDOCS.md)

### 主要特点
- 免费生成文本、图片和音频
- 无需账户或 API 密钥
- 适合创意项目和课堂活动
- 对孩子和学校安全友好
- 多语言支持（支持任何语言的提示词）

### 示例：用文本生成图片
直接用浏览器或代码！试试这个链接：

```
https://image.pollinations.ai/prompt/一个机器人正在给孩子们讲解人工智能
```

或用 Python：

```python
import requests
prompt = "一个机器人正在给孩子们讲解人工智能"
url = f"https://image.pollinations.ai/prompt/{prompt}"
response = requests.get(url)
with open('robot_ai_teacher_cn.jpg', 'wb') as f:
    f.write(response.content)
print('图片已保存！')
```

### 示例：生成文本
```
https://text.pollinations.ai/什么是人工智能？
```

### 课堂使用方法
- 让学生用 AI 创作艺术或故事
- 用 Pollinations.AI 演示生成式 AI
- 无需注册或个人信息

---

## More Languages / 更多语言
Want to help translate? Add your language here!

---

## Contact / 联系我们
For questions or feedback, visit [https://pollinations.ai](https://pollinations.ai) or open an issue on GitHub.
