# AI提示词工程仓库

## 项目简介

本仓库用于存储和管理各类AI助手的提示词设计方案，包括完整的提示词文本，每个提示词都经过详细的设计和优化，以确保其在各种场景下都能表现出最佳效果。

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
└── templates/                              # 系统提示词模板
    ├── character_designer.md               # 角色设计类
    ├── content_creation/                   # 内容创作类
    │   ├── poetry_master.md                #   诗灵（诗词大师）
    │   └── text_assistant_2.md             #   字观万象（文学顾问）
    ├── language/                           # 语言类
    │   ├── chinese_english_bridge_full.md  #   中英桥（翻译助手）
    │   ├── chinese_english_bridge_mini.md  #   中英桥（翻译助手，精简版）
    │   └── word_mnemonic_guide.md          #   忆词通（单词记忆助手）
    ├── media/                              # 媒体类
    │   ├── ai_media_assistant.md           #   AI媒体助手
    │   └── coze_db_media_assistant.md      #   Coze数据库媒体助手
    └── psychological/                      # 心理咨询类
        ├── professional_counseling.md      #   心理咨询助手 - 艾心
        └── emotional_focus_therapy.md      #   情绪聚焦疗法助手 - 心镜
        
```

## AI助手列表

| 助手名称 | 功能 | 核心优势 | 体验地址 |
|---------|------|----------|----------|
| 语络璇玑 | 创作灵感 + 文章取名 + 生成摘要 + 润色文字 | 通过工作流串联多个专业功能，为文学创作提供全流程支持 | [Coze](https://www.coze.cn/s/an2Y0SKPoPg/) |
| 诗灵 | 根据用户输入关键词返回相关的诗词 | 支持多关键词组合查询、智能语义联想扩展，分级推荐中外经典作品 | [豆包](https://doubao.com/bot/vxtOwggs) |
| 字观万象 | 创作灵感 + 文章取名 + 生成摘要 + 润色文字 | 通过精心设计的单一提示词实现多功能集成 | [Coze](https://www.coze.cn/s/c_APLHlANZI/) |
| 中英桥 | 专业中英翻译助手，精准互译与润色，单词学习模式 | 专注于语言翻译领域，提供专业级翻译质量和学习辅助功能 | [Coze](https://www.coze.cn/s/MOUfJUz9NvQ/) <br> [通义千问](https://lxblog.com/qianwen/share?shareId=2ca13d1b-bb6e-4e53-bd5b-ed9fe0b6a18a&type=agentCard) |
| 忆词通 | 智能单词记忆方案生成，支持多维度记忆法推荐 | 基于词源分析、发音解析和视觉要素的智能评估体系，提供个性化记忆方案 | [豆包](https://doubao.com/bot/JtwGgRVu) |
| 艾心 | 专业心理咨询服务，提供情绪支持和心理疏导 | 遵循专业心理咨询原则，提供安全、保密的心理支持环境 | [coze](https://www.coze.cn/s/9J2nZUXdymk/) <br> [豆包](https://doubao.com/bot/5xUSTFUE) |
| 心镜 | 情绪聚焦疗法专业支持 | 基于情绪聚焦疗法理论，提供专业情绪管理方案 | [通义千问](https://lxblog.com/qianwen/share?shareId=9f0f7ebb-eaf5-4fef-a46d-418b04b8e3e5&type=agentCard) |
| 角色设计师 | 创建高效的系统提示词，用于设定AI的角色定位和行为规范 | 专业提示词设计，帮助AI准确理解并执行特定角色任务 | [coze](https://www.coze.cn/s/IvLHSLiYzh4/) <br> [通义千问](https://lxblog.com/qianwen/share?shareId=4d8a6c5f-c6f2-4d7f-a230-67316b333149&type=agentCard) |
