# AI-Novel-Gemeration丨AI图文小说生成器

AI-Novel-Gemeration是基于讯飞Astron Agent平台开发的AI小说图文生成智能体，只需输入一个小说名称即可生成图文并茂的小说文章。

<img width="1075" height="655" alt="Snipaste_2025-11-23_19-09-50" src="https://github.com/user-attachments/assets/f52509f1-70f0-4482-a6e4-f068192c78ed" />

<img width="1080" height="691" alt="640" src="https://github.com/user-attachments/assets/60484383-c6e2-45e6-a907-4eb24344e69e" />

---

##  亮点

- **简洁易用**：快速上手，无需复杂配置。
- **DeepSeek加成**：接入了DeepSeek大模型，助力你快速生成高质量小说。
- **图片生成**：基于讯飞星火图片生成能力，可以快速生成精美配图。
- **开箱即用**：基于 Docker Compose 一键部署！
- **成熟可靠**：基于企业级开源项目 AstronAgent 二次开发

##  配置要求

- **Docker 20.10+**
- **Docker Compose 2.0+**
- **50G磁盘空间**
- **最低4G内存，推荐8G**

---

## 📦 安装

```bash
# 进入项目根目录
cd astron-agent

# 进入 astronAgent 目录
cd docker/astronAgent

# 复制环境变量配置
cp .env.example .env

# 编辑环境变量
vim .env

# 一键启动部署
docker compose -f docker-compose-with-auth.yaml up -d

```

#  本地访问

- **使用地址：http://localhos**
- **默认用户名：admin**
- **默认密码：123**

#  导入 AI-Novel-Gemeration 工作流

- **工作流文件地址：ocker/astronAgent/小说图文生成.yml**d
- **新建工作流时导入该文件即可**



