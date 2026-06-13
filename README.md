# Le-Skills

作者自建使用的 Skills 集合。

## 目录结构

```
Le-Skills/
├── prompt/                        # 完整版提示词
│   ├── Flight-Translator.md       # 民航翻译助手完整版
│   └── Project-Skills-Manager.md # 项目技能与规则管理器完整版
└── README.md
```

## Skills

### Flight-Translator

民航翻译与报文解读智能助手，用于辅助航空领域的翻译工作。

**功能：**
- 全场景民航词汇/句子/缩写精准翻译（中→英、英→中）
- 报文全类型识别与结构化解析（METAR/TAF/NOTAM/SIGMET等）
- 智能意图判别：翻译 / 知识点提问 / 报文解读
- 今日学习日志与总结
- 支持图片/文件OCR翻译

### Project-Skills-Manager

项目技能与规则管理器，用于新项目或项目更新时安装、替换技能（Skills）和规则（Rules）。

**功能：**
- 整合开源技能项目（ECC、GitNexus、codegraph 等）
- 评估前端设计技能可用性
- 筛选安装适用技能
- 配置技能调度规则、更新日志规则（按需加载）
- MCP 改 CLI
- 技能生命周期管理（升级/卸载）
