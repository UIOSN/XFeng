# 张小峰智能高考志愿填报系统
>  本项目为5名中大cs本科生出品。觉得有帮助不妨点点star！！\
> *张雪峰老师，我还记得你😭
> 那些年少的愁，你替我扛起🫡*

本项目是一个帮助高中生进行高考志愿填报的辅助Web应用，提供院校查询、志愿管理和AI咨询等功能。


<video src="https://github.com/user-attachments/assets/609c5652-cb06-4b46-9e8f-23d48656d3d9" controls autoplay loop muted width="100%"></video>
## ✨ 核心功能

*   院校信息搜索与详情展示
*   个性化志愿表管理（冲刺、稳妥、保底）
*   集成Dify AI的智能问答

## 🛠️ 主要技术栈

*   **前端 (`Vue-app`)**: Vue.js 3, Vite, Vue Router, PrimeVue, TailwindCSS, Axios
*   **后端 (`server`)**: Node.js, Express.js, MySQL (`mysql2/promise`), JWT
*   **AI服务**: Dify AI

## 🚀 快速开始

### 1. 环境要求(Linux环境)
*   Node.js (v18+)
*   npm (v9+)
*   MySQL (v8+)
*   Python (v3+)

### 2. 克隆项目
```bash
git clone https://github.com/UIOSN/XFeng.git
cd XFeng
```

### 3. 后端 (`server`)
```bash
cd server
npm install

# 确保MySQL服务运行，并已创建 se_project 和 gkvr_system 数据库 
node index.js
# 后端运行于 http://localhost:3000
```

### 4. 前端 (`Vue-app`)
```bash
cd ../Vue-app # 或从项目根目录 cd Vue-app
npm install
npm run dev
# 前端运行于 http://localhost:5173
```

### 5. 访问
浏览器打开 `http://localhost:5173`。

## 🤝 贡献

欢迎Fork和Pull Request！

