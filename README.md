# AI提示词工程仓库

## 项目简介

本仓库用于存储和管理各类AI助手的提示词设计方案，包括完整的提示词文本，每个提示词都经过详细的设计和优化，以确保其在各种场景下都能表现出最佳效果。

## 命名规范

- **目录命名**：使用单数领域名词（Singular Domain Noun），如 `writing`、`counseling`、`learning`
- **文件命名**：使用施事名词（Agent Noun）描述AI角色，如 `counselor`、`python_expert`、`vocabulary_coach`
- **工作流目录**：使用复数名词 `workflows/` 表示集合

## 目录结构

```
ai_prompt/
├── writing/                            # 内容创作
│   ├── poetry_master.md                #   诗灵（诗词大师）
│   └── text_assistant/                 #   文本助手
│       ├── prompt.md                   #     语络璇玑（工作流版）
│       ├── prompt_compact.md           #     字观万象（精简版）
│       └── workflows/                  #     工作流模块
│           ├── content_polisher.md     #       文本润色
│           ├── inspiration_generator.md#       灵感生成
│           ├── summary_generator.md    #       摘要生成
│           └── title_generator.md      #       标题生成
├── coding/                             # 编程开发
│   ├── programmer.md                   #   通用程序员助手
│   └── python_expert.md                #   Python专家
├── language/                           # 语言学习
│   ├── translator.md                   #   语言魔方（翻译助手）
│   └── vocabulary_coach.md             #   记词大师
├── media/                              # 媒体娱乐
│   ├── media_assistant.md              #   影音检索助手
│   └── media_db_assistant.md           #   数据库媒体助手
├── counseling/                         # 心理咨询
│   ├── counselor.md                    #   咨询师·艾心
│   └── eft_therapist.md               #   EFT治疗师·心镜
├── learning/                           # 学习辅助
│   └── note_wizard.md                  #   笔记精灵
├── tooling/                            # 工具类
│   └── prompt_master.md                #   提示词助手
└── security/                           # AI安全
    └── attack_datasets/                #   攻击测试数据集
        ├── harmful.xml
        ├── harmful_cn.xml
        ├── harmful_distilled.xml
        ├── healthcare.xml
        ├── healthcare_cn.xml
        ├── system_prompt_extraction.xml
        └── system_prompt_extraction_cn.xml
```

## AI助手列表

- 语络璇玑：创作灵感 + 文章取名 + 生成摘要 + 润色文字
  - 核心优势：通过工作流串联多个专业功能，为文学创作提供全流程支持
- 字观万象：创作灵感 + 文章取名 + 生成摘要 + 润色文字
  - 核心优势：通过精心设计的单一提示词实现多功能集成
- 诗灵：根据用户输入关键词返回相关的诗词
  - 核心优势：支持多关键词组合查询、智能语义联想扩展，分级推荐中外经典作品
- 通用程序员：精通多种编程语言，兼具产品经理与架构师思维
  - 核心优势：全栈开发能力 + 需求深挖 + 架构设计
- Python专家：专注Python生态，擅长机器学习与数据工程
  - 核心优势：Pythonic范式 + AI建模 + 生产部署全流程
- 语言魔方：专业中英翻译助手，精准互译与润色，单词学习模式
  - 核心优势：专注于语言翻译领域，提供专业级翻译质量和学习辅助功能
- 记词大师：为英语学习者定制高效单词记忆方案
  - 核心优势：多感官编码 + 词根词缀法 + 语境锚点法
- 影音检索助手：根据用户输入提供影音的结构化信息
  - 核心优势：智能类型识别 + 高分随机推荐
- 数据库媒体助手：基于数据库的智能影视信息管理系统
  - 核心优势：自动补全 + 智能纠错 + 别名映射
- 艾心：专业心理咨询服务，提供情绪支持和心理疏导
  - 核心优势：人本主义疗法 + 认知行为疗法，提供安全、保密的心理支持环境
- 心镜：EFT情绪聚焦疗法，帮助改善亲密关系中的沟通障碍
  - 核心优势：情绪命名 + 隐喻引导 + GROW模型
- 笔记精灵：将学习内容转化为可视化、易记忆的实用笔记
  - 核心优势：视觉化 + 结构化 + 深度化
- 提示词助手：生成、优化和评估AI提示词
  - 核心优势：三段式结构 + SMART原则 + 质量评分
