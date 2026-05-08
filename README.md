# 👋 Hi, I'm 微风徐徐


> 🚀 IT 运维工程师 → SRE / AI 运维工程师 | 用代码自动化一切

- 🔭 5 年 IT 运维经验（网络工程 + 项目管理 + 自动化）
- 🌱 正在系统学习 **Python 3.14** 运维开发，转型 SRE
- 💡 技术栈：华为/华三/思科网络设备、VMware、Zabbix、AD 域控、阿里云
- 📫 联系我：**[ljinw](https://github.com/ljinw)** (GitHub)

<br clear="right"/>

---

## 🛠️ Tech Stack

### 💻 编程语言
![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-000000?logo=gnu-bash&logoColor=white)


### 🤖 AI & Agent
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)

### 🗄️ 数据库 & 向量库
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?logo=milvus&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)
![postgresql](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

### ☸️ 云原生 & 监控
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-E60012?logo=zabbix&logoColor=white)

### 🔧 运维 & 网络
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Aliyun](https://img.shields.io/badge/Aliyun-FF6A00?logo=alibabacloud&logoColor=white)
![TencentCloud](https://img.shields.io/badge/TencentCloud-0073BB?logo=tencent-cloud&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-0645AD?logo=vmware&logoColor=white)
![Huawei](https://img.shields.io/badge/Huawei-FF0000?logo=huawei&logoColor=white)
![H3C](https://img.shields.io/badge/H3C-0099FF?logo=h3c&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-00599C?logo=cisco&logoColor=white)


---

## 📌 Featured Projects

### 🏗️ [ops-conf-man](https://github.com/ljinw/ops-conf-man) ⏳ 规划中
> 运维配置中心（Python / FastAPI）

一站式配置管理平台，支持多服务类型（Nginx/Redis/MySQL）、版本控制（Git）、一键回滚、变更通知。

**核心功能：** 配置模板化 · Git 版本追踪 · SSH 远程下发 · WebSocket 实时推送

---

### 🔔 [alert-river](https://github.com/ljinw/alert-river) ⏳ 规划中
> 告警流转平台（Python / FastAPI / Redis Stream）

统一接入 Zabbix/Prometheus 告警，实现告警降噪、认领、升级、复盘全流程管理。

**核心功能：** 告警去重 · 智能降噪 · 升级机制 · MTTR/MTBF 统计 · 根因分析

---

### 🤖 [ops-knowledge-agent](https://github.com/ljinw/ops-knowledge-agent) ⏳ 规划中
> 运维知识库 Agent（Python / LangChain / RAG）

基于私有知识库的运维问答机器人，支持上传运维文档（Markdown/PDF/DOCX），自然语言提问获取答案 + 来源引用。

**核心功能：** RAG 检索 · 本地模型(Ollama) · 多轮对话 · 企微/钉钉 Bot 对接

---

### 🌐 [netconf-go](https://github.com/ljinw/netconf-go) ⏳ 规划中
> 网络设备配置采集器（Go / SSH / Netconf）

统一采集华为/华三/思科设备配置，自动备份、差异对比、变更告警。

**核心功能：** 多厂商 Driver · 并发采集 · Git 版本管理 · 配置 Diff · 变更通知

---

### 🔐 [cert-manager-go](https://github.com/ljinw/cert-manager-go) ⏳ 规划中
> 证书全生命周期管理（Go / ACME）

自动发现、监控、续期 SSL 证书，防止证书过期引发线上事故。

**核心功能：** TLS 证书扫描 · Let's Encrypt 自动续期 · DNS-01 挑战 · 部署推送 · 过期告警

---

### 🔍 [shellcheck-api](https://github.com/ljinw/shellcheck-api) ⏳ 规划中
> 运维脚本安全审计平台（Python / FastAPI / ShellCheck）

上传 Shell 脚本自动扫描安全风险，给出修复建议，支持自定义规则和白名单。

**核心功能：** ShellCheck 静态分析 · AST 深度解析 · 安全风险评级 · 自动修复 · PDF 报告导出

---

## 📚 学习项目

### 📖 [my-plan-python](https://github.com/ljinw/my-plan-python)
> Python 3.14 运维开发系统化学习项目

从基础语法到进阶实战，涵盖 70+ 练习题和 6 个实战项目。

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ljinw&show_icons=true&theme=vue&hide_border=true&include_all_commits=true" alt="GitHub Stats" />
</div>

---

## 📫 联系我

- 💻 **GitHub**: [@ljinw](https://github.com/ljinw)
- 🌍 **Location**: 杭州，中国

---

> *"The best way to predict the future is to create it."*
