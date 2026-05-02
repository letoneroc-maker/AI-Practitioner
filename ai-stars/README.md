# AI Stars - 发现AI行业最杰出的人物

一个展示AI行业顶尖人物的导航页面，帮助你发现和连接行业大牛。

## 🌟 收录名单

### 图灵奖得主
| 姓名 | 公司 | 职位 | 专长 |
|------|------|------|------|
| Geoffrey Hinton | Google | 深度学习之父 | Backprop算法先驱，深度学习奠基人 |
| Yann LeCun | Meta | 首席AI科学家 | 卷积神经网络之父，2018年图灵奖得主 |
| Yoshua Bengio | Meta | 深度学习先驱 | GAN生成对抗网络发明人，2018年图灵奖得主 |

### AI公司CEO/创始人
| 姓名 | 公司 | 职位 | 简介 |
|------|------|------|------|
| Sam Altman | OpenAI | CEO | ChatGPT与GPT-4的缔造者 |
| Dario Amodei | Anthropic | CEO | Claude系列模型核心贡献者 |
| Jensen Huang | NVIDIA | CEO | GPU教父，Transformer时代最大赢家 |
| Demis Hassabis | Google DeepMind | CEO | AlphaGo缔造者 |
| Satya Nadella | Microsoft | CEO | Microsoft转型掌舵人，Copilot布局者 |
| Sundar Pichai | Google | CEO | Chrome与Android崛起功臣，Gemini战略主导者 |
| Mark Zuckerberg | Meta | CEO | 开源大模型LLaMA推动者 |
| Jim Fan | NVIDIA | AI Scientist | xAI创始团队核心成员 |

### AI研究领袖
| 姓名 | 公司 | 职位 | 简介 |
|------|------|------|------|
| Andrew Ng | Google | DeepLearning.AI创始人 | 全球AI教育先驱，Google Brain创始成员 |
| Fei-Fei Li | Google | 斯坦福大学教授 | ImageNet创始人，计算机视觉先驱 |
| Jeff Dean | Google | Google Fellow & SVP | Google Brain与TPU之父 |
| Ilya Sutskever | SSI | Co-founder | OpenAI联合创始人，GPT系列核心架构师 |
| Andrej Karpathy | OpenAI | AI Educator | 前Tesla Autopilot负责人，斯坦福CS231n讲师 |

### AI创业新锐
| 姓名 | 公司 | 职位 | 简介 |
|------|------|------|------|
| Mustafa Suleyman | Microsoft | CEO of Microsoft AI | DeepMind联合创始人 |
| Aravind Srinivas | Perplexity | CEO | 前Google研究科学家，AI搜索新锐 |
| Alex Wang | Scale AI | CEO | AI数据基础设施独角兽缔造者 |

### AI框架/工具专家
| 姓名 | 公司 | 职位 | 简介 |
|------|------|------|------|
| François Chollet | Google | 软件工程师 | Keras之父，《Python深度学习》作者 |

### 硬件/芯片领袖
| 姓名 | 公司 | 职位 | 简介 |
|------|------|------|------|
| Lisa Su | AMD | CEO | AMD逆袭掌舵人，GPU与AI芯片战场关键人物 |
| Tim Cook | Apple | CEO | Apple Intelligence布局者，隐私AI践行者 |

## ✨ 功能特点

- 🎨 高级暗色模式设计
- 🔍 实时搜索过滤
- 🏷️ 按公司筛选
- 📱 响应式布局
- ⚡ 轻量快速

## 🚀 技术栈

- 纯HTML/CSS/JavaScript
- 无需后端
- 静态部署

## 📂 项目结构

```
ai-stars/
├── index.html      # 主页面
└── data/
    └── people.json # 人物数据
```

## 🚀 部署

支持多种部署方式：

### GitHub Pages
1. Fork此仓库
2. Settings → Pages → Select `main` branch
3. 访问 `https://[username].github.io/AI-Practitioner/ai-stars/`

### Vercel
```bash
npx vercel --prod ai-stars/
```

### Netlify
拖拽 `ai-stars` 文件夹到 Netlify Dashboard

## 📝 数据格式

人物数据存储在 `data/people.json`：

```json
{
  "name": "姓名",
  "title": "职位",
  "company": "公司",
  "avatar": "头像URL",
  "bio": "简介",
  "links": {
    "x": "X/Twitter链接",
    "github": "GitHub链接",
    "linkedin": "LinkedIn链接",
    "website": "个人网站"
  },
  "tags": ["标签1", "标签2"]
}
```

## 🤝 贡献

欢迎提交PR或Issue来添加新的AI大牛或修正信息。