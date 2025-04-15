# AI提示词工程仓库

## 项目简介

本仓库用于存储和管理各类AI助手的提示词设计方案，包括完整的提示词文本、工作流设计和系统架构。

```
prompt/
├── agents/                                 # 智能体
│   └── text_assistant_1/                   #   语络璇玑（文学顾问+工作流）
│       ├── prompt.md
│       └── workflow/
│           ├── content_polisher.md
│           ├── inspiration_generator.md
│           ├── summary_generator.md
│           └── titile_generator.md
└── templates/                              # 提示词模板
    ├── content_creation/                   # 内容创作类
    │   ├── poetry_master.md                #   诗灵（诗词大师）
    │   └── text_assistant_2.md             #   字观万象（文学顾问）
    └── language/                           # 语言类
        ├── chinese_english_bridge_mini.md  #   中英桥（翻译助手，设定词有字数限制，精简版）
        ├── chinese_english_bridge_full.md  #   中英桥（翻译助手）
        └── word_mnemonic_guide.md          #   忆词通（单词记忆助手）
```

## AI助手列表

| 助手名称 | 功能 | 设计方式 | 核心优势 | 体验地址 |
|---------|------|----------|----------|----------|
| 语络璇玑 | 创作灵感 + 文章取名 + 生成摘要 + 润色文字 | 提示词 + 工作流 | 通过工作流串联多个专业功能，为文学创作提供全流程支持 | [Coze](https://www.coze.cn/s/an2Y0SKPoPg/) |
| 诗灵 | 根据用户输入关键词返回相关的诗词 | 提示词 | 支持多关键词组合查询、智能语义联想扩展，分级推荐中外经典作品 | [豆包](https://doubao.com/bot/vxtOwggs) |
| 字观万象 | 创作灵感 + 文章取名 + 生成摘要 + 润色文字 | 提示词 | 通过精心设计的单一提示词实现多功能集成 | [Coze](https://www.coze.cn/s/c_APLHlANZI/) |
| 中英桥 | 专业中英翻译助手，精准互译与润色，单词学习模式 | 提示词 | 专注于语言翻译领域，提供专业级翻译质量和学习辅助功能 | [Coze](https://www.coze.cn/s/MOUfJUz9NvQ/) [通义](https://lxblog.com/qianwen/share?shareId=2ca13d1b-bb6e-4e53-bd5b-ed9fe0b6a18a&type=agentCard) |
| 忆词通 | 智能单词记忆方案生成，支持多维度记忆法推荐 | 提示词 | 基于词源分析、发音解析和视觉要素的智能评估体系，提供个性化记忆方案 | [豆包](https://doubao.com/bot/JtwGgRVu) |
