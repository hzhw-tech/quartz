# 红珍华物团队成员信息

## 领导层
- **逢华 Phoenix** (userid: 640255990) - 创始人/老板
- **黄文杰** (userid: 5067127804) - 联合创始人/老板

## 执行团队

| 员工名称 | 职位 | 邮箱 | 邮箱密码 | GitHub密码 | 专业领域 | 当前状态 |
|---------|------|------|----------|------------|----------|----------|
| Lucas | 总助理 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | 项目协调、综合管理 | 🟢 在线 (主身份) |
| Sara | UI设计师 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | UI/UX设计、视觉设计、品牌视觉、设计系统 | 🟢 就位 |
| Emma | 营销专家 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | 市场策略、品牌推广、用户增长、营销数据分析 | 🟢 就位 |
| Jacky | 技术专家 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | 软件开发、系统架构、代码审查、云计算 | 🟢 就位 |
| Mike | 市场分析师 | lucas@awell.one | lucas_openclaw | nDo79wDYKN2fF=u=m | AI资讯、互联网趋势、X热门话题分析 | 🟢 就位 |

## 协作规范

### 身份识别
- **老板指令**：逢华 Phoenix 和黄文杰的指令具有最高优先级
- **默认对话**：直接说话 = 对 Lucas (总助理) 说话
- **指定专家**：需先叫名字（如"Sara"、"Emma"、"Jacky"、"Mike"）
- **Lucas职责**：协调各专家，整合输出，管理项目进度，执行老板指令

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
- **2026-02-09 10:46**：为 Jacky 创建独立 Agent，配置技术专家专属工作区
- **2026-02-09 10:37**：添加领导层信息（逢华 Phoenix、黄文杰）
- **2026-02-09 10:20**：创建市场报告存储系统，Mike报告自动保存到Obsidian
- **2026-02-09 10:12**：调整Mike定时任务到每天8点，发送到工作群组
- **2026-02-09 10:05**：创建记忆存储系统，使用Obsidian管理记忆
- **2026-02-09 06:35**：添加市场分析师 Mike，启用 web_fetch 功能
- **2026-02-09 06:18**：优化团队信息表，添加专业领域和状态
- **2026-02-09 05:43**：创建测试文档，验证 Obsidian 同步
- **2026-02-09 05:28**：成功克隆 yiji-server-hono 项目
- **2026-02-09 03:50**：创建三个专业子代理（营销、技术、设计）

## 待办事项
- [ ] 配置 Cloudflare 和 Vercel API 密钥
- [ ] 开始 yiji-server-hono 项目开发
- [ ] 建立 Mike 的每日8点自动新闻推送（需要设置 cron job）
- [ ] 建立定期同步机制