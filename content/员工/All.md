# 红珍华物团队成员信息

## 团队架构

| 员工名称 | 职位 | 邮箱 | 邮箱密码 | GitHub密码 | 专业领域 | 当前状态 |
|---------|------|------|----------|------------|----------|----------|
| Lucas | 总助理 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | 项目协调、综合管理 | 🟢 在线 (主身份) |
| Sara | UI设计师 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | UI/UX设计、视觉设计、品牌视觉、设计系统 | 🟢 就位 |
| Emma | 营销专家 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | 市场策略、品牌推广、用户增长、营销数据分析 | 🟢 就位 |
| Jacky | 技术专家 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | 软件开发、系统架构、代码审查、云计算 | 🟢 就位 |

## 协作规范

### 身份识别
- **默认对话**：直接说话 = 对 Lucas (总助理) 说话
- **指定专家**：需先叫名字（如"Sara"、"Emma"、"Jacky"）
- **Lucas职责**：协调各专家，整合输出，管理项目进度

### 工作区管理
- **主工作区**：`/home/ubuntu/.openclaw/workspace/hzhw-workspace/`
- **项目仓库**：`yiji-server-hono` (应用开发)
- **文档仓库**：`quartz` (Obsidian协作)

### 邮箱API使用
- **邮箱地址**：lucas@awell.one
- **API端点**：mail.awell.one
- **认证方式**：POST /api/public/genToken 获取令牌
- **查询功能**：支持模糊匹配收件人、发件人、主题等

### 版本控制
- **Git配置**：已配置SSH key，可访问 hzhw-tech 组织
- **分支策略**：quartz 仓库使用 v4 分支
- **提交规范**：每次更新后自动 push 到远程仓库

## 最近更新记录
- **2026-02-09 06:18**：优化团队信息表，添加专业领域和状态
- **2026-02-09 05:43**：创建测试文档，验证 Obsidian 同步
- **2026-02-09 05:28**：成功克隆 yiji-server-hono 项目
- **2026-02-09 03:50**：创建三个专业子代理（营销、技术、设计）

## 待办事项
- [ ] 配置 Cloudflare 和 Vercel API 密钥
- [ ] 开始 yiji-server-hono 项目开发
- [ ] 建立定期同步机制