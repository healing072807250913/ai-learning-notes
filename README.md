<！doctype html>
<超文本标记语言朗="zh-CN">
<头>
    <元字符集="UTF-8" />
    <元姓名="视口" 内容="宽度=设备宽度，初始比例=1.0" />
    <标题>🚀 人工智能全栈工程师·成长之路</标题>
    <！--Font Awesome图标库-->
    <链接rel="样式表" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <风格>
        /* ---------- 全局重置 & 基础 ---------- */
        * {
            边缘: 0;
            填充: 0;
            箱体尺寸: 边框框;
        }

    正文{
    font-family：'Segoe UI'，Roboto，system-ui，-apple-system，sans-serif；
    背景：#f8faff；
    颜色：#1e293b；
    线高：1.6；
    填料：2rem1.5rem；
        }

    .container{
    最大宽度：1100px；
    margin:0 auto；
    背景：白色；
    边界半径：2rem；
    box-shadow:020px 60px rgba(0，20，50，0.08)；
    填料：2.5rem2.8rem；
    过渡：均为0.2s；
        }

    @media(最大宽度：640px){
    正文{
    填料：1rem0.5rem；
            }
    .container{
    填料：1.5rem1.2rem；
    边界半径：1.2rem；
            }
        }

    /* ---------- 头部 ---------- */
    .header{
    显示：柔性；
    flex-wrap：缠绕；
    justify-Content：间距；
    对齐项：居中；
    border-bottom:2px实体#eef2f6；
    垫底：1.8rem；
    底边距：2.2rem；
        }

    .header-左h1{
    font-size:2.4rem；
    font-weight:700；
    背景：线性梯度(135度，#2563eb，#7c3aed)；
            -webkit-background-clip: text;
    -webkit-text-fill-color：透明；
    背景剪辑：文本；
    字母间距：-0.02em；
        }

        .header-left .subhead {
            font-size: 1.05rem;
            color: #475569;
            margin-top: 0.2rem;
            font-weight: 400;
        }

        .header-left .subhead i {
            margin-right: 6px;
            color: #2563eb;
        }

        .badge-group {
            display: flex;
            gap: 0.8rem;
            flex-wrap: wrap;
            margin-top: 0.6rem;
        }

        .badge {
            background: #eef2ff;
            color: #1e40af;
            padding: 0.3rem 1rem;
            border-radius: 30px;
            font-size: 0.85rem;
            font-weight: 500;
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }

        .badge i {
            font-size: 0.8rem;
        }

        .header-right {
            text-align: right;
            margin-top: 0.5rem;
        }

        .header-right .quote {
            font-style: italic;
            color: #475569;
            font-size: 1rem;
            max-width: 280px;
        }

        .header-right .quote i {
            color: #2563eb;
            margin: 0 4px;
        }

        .contact-links {
            margin-top: 0.6rem;
            display: flex;
            gap: 1.2rem;
            justify-content: flex-end;
            flex-wrap: wrap;
        }

        .contact-links a {
            color: #1e293b;
            text-decoration: none;
            font-size: 0.95rem;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            transition: color 0.2s;
        }

        .contact-links a:hover {
            color: #2563eb;
        }

        .contact-links a i {
            font-size: 1.1rem;
            width: 1.4rem;
            text-align: center;
        }

        /* ---------- 通用卡片 ---------- */
        .section {
            margin-bottom: 2.8rem;
        }

        .section-title {
            font-size: 1.6rem;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 1.2rem;
            color: #0f172a;
        }

        .section-title i {
            color: #2563eb;
            font-size: 1.5rem;
        }

        .section-sub {
            color: #475569;
            margin-bottom: 1.5rem;
            font-size: 0.98rem;
        }

        /* ---------- 进度卡片 (Current Stage) ---------- */
        .stage-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 0.8rem 1.2rem;
            background: #f8fafc;
            padding: 1.2rem 1.8rem;
            border-radius: 1.2rem;
            margin-top: 0.5rem;
        }

        .stage-item {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 0.98rem;
        }

        .stage-item .check {
            color: #22c55e;
            font-size: 1.2rem;
        }

        .stage-item .pending {
            color: #94a3b8;
            font-size: 1.2rem;
        }

        .stage-item .fire {
            color: #f59e0b;
            font-size: 1.2rem;
        }

        /* ---------- 目录结构 (树) ---------- */
        .tree {
            background: #f1f5f9;
            padding: 1.2rem 1.8rem;
            border-radius: 1rem;
            font-family: 'JetBrains Mono', 'Fira Code', monospace;
            font-size: 0.9rem;
            line-height: 1.8;
            overflow-x: auto;
            white-space: pre;
            color: #0f172a;
        }

        .tree .folder {
            color: #2563eb;
        }
        .tree .file {
            color: #475569;
        }
        .tree .comment {
            color: #64748b;
            font-style: italic;
        }

        /* ---------- 表格风格路线图 ---------- */
        .roadmap-table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.95rem;
        }

        .roadmap-table th {
            text-align: left;
            padding: 0.7rem 0.5rem 0.7rem 0;
            font-weight: 600;
            color: #1e293b;
            border-bottom: 2px solid #e2e8f0;
        }

        .roadmap-table td {
            padding: 0.7rem 0.5rem 0.7rem 0;
            border-bottom: 1px solid #eef2f6;
            vertical-align: top;
        }

        .roadmap-table tr:last-child td {
            border-bottom: none;
        }

        .status-badge {
            display: inline-block;
            background: #dbeafe;
            color: #1e40af;
            padding: 0.15rem 0.7rem;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 500;
        }

        .status-badge.done {
            background: #dcfce7;
            color: #166534;
        }

        .status-badge.inprogress {
            background: #fef9c3;
            color: #854d0e;
        }

        .status-badge.plan {
            background: #f1f5f9;
            color: #475569;
        }

        /* ---------- 技术栈标签 ---------- */
        .tech-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem 1rem;
            margin: 0.5rem 0 0.2rem;
        }

        .tech-tag {
            background: white;
            border: 1px solid #e2e8f0;
            padding: 0.25rem 1rem;
            border-radius: 30px;
            font-size: 0.85rem;
            color: #1e293b;
            box-shadow: 0 1px 2px rgba(0,0,0,0.02);
            transition: all 0.1s;
        }

        .tech-tag i {
            margin-right: 6px;
            color: #2563eb;
        }

        .tech-tag:hover {
            border-color: #2563eb;
            background: #f8faff;
        }

        /* ---------- 项目卡片 ---------- */
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
            gap: 1.2rem;
            margin-top: 0.5rem;
        }

        .project-card {
            background: #f8fafc;
            border-radius: 1rem;
            padding: 1.2rem 1.2rem 1rem;
            border: 1px solid #eef2f6;
            transition: 0.15s;
        }

        .project-card:hover {
            border-color: #cbd5e1;
            background: white;
            box-shadow: 0 4px 12px rgba(0,0,0,0.02);
        }

        .project-card h4 {
            font-size: 1.05rem;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .project-card h4 i {
            color: #2563eb;
            font-size: 0.9rem;
        }

        .project-card .p-desc {
            color: #475569;
            font-size: 0.9rem;
            margin: 0.4rem 0 0.6rem;
        }

        .project-card .p-stack {
            font-size: 0.75rem;
            color: #64748b;
            background: #eef2f6;
            padding: 0.2rem 0.8rem;
            border-radius: 30px;
            display: inline-block;
        }

        .project-card .p-status {
            float: right;
            font-size: 0.75rem;
            color: #64748b;
        }

        /* ---------- GitHub stats 占位 ---------- */
        .gh-stats {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            background: #f8fafc;
            border-radius: 1.2rem;
            padding: 1.5rem 1.8rem;
            align-items: center;
            justify-content: space-around;
        }

        .gh-stats img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.04);
        }

        .gh-placeholder {
            color: #64748b;
            font-size: 0.9rem;
            text-align: center;
        }

        .gh-placeholder i {
            color: #2563eb;
            margin-right: 6px;
        }

        /* ---------- 联系 & 底部 ---------- */
        .footer-note {
            text-align: center;
            margin-top: 2.5rem;
            padding-top: 1.8rem;
            border-top: 1px solid #eef2f6;
            color: #64748b;
            font-size: 0.95rem;
        }

        .footer-note i {
            color: #ef4444;
        }

        .footer-note a {
            color: #2563eb;
            text-decoration: none;
        }

        .footer-note a:hover {
            text-decoration: underline;
        }

        /* 小调整 */
        .mt-1 {
            margin-top: 0.5rem;
        }
        .inline-icon {
            margin-right: 6px;
        }
        .text-muted {
            color: #64748b;
        }
        .flex-wrap {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem 1.5rem;
        }
    </style>
</head>
<body>
<div class="container">

    <!-- ======================== 头部 ======================== -->
    <header class="header">
        <div class="header-left">
            <h1>🚀 AI Full-Stack Journey</h1>
            <div class="subhead">
                <i class="fas fa-code"></i> 从专科到外企 · 全栈成长记录
            </div>
            <div class="badge-group">
                <span class="badge"><i class="fas fa-graduation-cap"></i> 日照职业技术学院 · 软件技术</span>
                <span class="badge"><i class="fas fa-flag"></i> 目标：AI 全栈工程师</span>
            </div>
        </div>
        <div class="header-right">
            <div class="quote">
                <i class="fas fa-quote-left"></i> 写好每一行代码，走好每一步路 <i class="fas fa-quote-right"></i>
            </div>
            <div class="contact-links">
                <a href="#" target="_blank"><i class="fab fa-github"></i> GitHub</a>
                <a href="#"><i class="fas fa-envelope"></i> your-email@example.com</a>
            </div>
        </div>
    </header>

    <!-- ======================== 当前阶段 ======================== -->
    <section class="section">
        <div class="section-title">
            <i class="fas fa-location-dot"></i> 当前阶段
        </div>
        <div class="stage-grid">
            <div class="stage-item"><span class="check"><i class="fas fa-check-circle"></i></span> 创建个人仓库</div>
            <div class="stage-item"><span class="fire"><i class="fas fa-fire"></i></span> <strong>专升本备考中</strong></div>
            <div class="stage-item"><span class="pending"><i class="far fa-circle"></i></span> 进入本科 · 计算机科学与技术</div>
            <div class="stage-item"><span class="pending"><i class="far fa-circle"></i></span> 研究生深造</div>
            <div class="stage-item"><span class="pending"><i class="far fa-circle"></i></span> 🏆 入职中大型外企 · AI 全栈工程师</div>
        </div>
    </section>

    <!-- ======================== 目录结构 ======================== -->
    <section class="section">
        <div class="section-title">
            <i class="fas fa-folder-tree"></i> 目录结构
        </div>
        <div class="tree">
            <span class="folder">ai-fullstack-journey/</span>
            ├── <span class="folder">notes/</span>                <span class="comment"># 学习笔记（按主题分类）</span>
            │   ├── <span class="folder">python/</span>          <span class="comment"># Python 基础与进阶</span>
            │   ├── <span class="folder">algorithms/</span>       <span class="comment"># 数据结构与算法</span>
            │   ├── <span class="folder">ml/</span>              <span class="comment"># 机器学习</span>
            │   ├── <span class="folder">dl/</span>              <span class="comment"># 深度学习</span>
            │   └── <span class="folder">web/</span>             <span class="comment"># 前后端开发</span>
            ├── <span class="folder">projects/</span>             <span class="comment"># 小项目与实战练习</span>
            ├── <span class="folder">daily/</span>                <span class="comment"># 每日打卡与学习记录</span>
            ├── <span class="folder">resources/</span>            <span class="comment"># 优质教程、书单、链接收藏</span>
            └── <span class="file">README.md</span>
        </div>
    </section>

    <！--========================学习路线图========================-->
    <section class="section">
    <div class="section-title">
    <i class="fas fa-map-signs"></i>学习路线图
    </div>

    <h3style="font-weight:600；margin:1.2rem0.6rem；font-size:1.2rem；">第一阶段·打地基(专科期间)</h3>
    <table class="romap-table">
    <thad><tr><th>方向</th><th>内容</th><th>状态</th></tr></thad>
    <tbody>
    <tr><td>Python</td><td>基础语法→面向对象→常用库</td><td><span class="status-badge inprogress">🔄 进行中</span></td></tr>
    <tr><td>数据结构</td><td>数组、链表、树、哈希表</td><td><span class="status-badge inprogress">🔄 进行中</span></td></tr>
    <tr><td>算法基础</td><td>LeetCode简单/中等题200+</td><td><span class="status-badge plan">⬜ 规划</span></td></tr>
    <tr><td>Web入门</td><td>HTML/CSS/JavaScript</td><td><span class="status-badge plan">⬜ 规划</span></td></tr>
    <tr><td>工具链</td><td>Git/GitHub/Linux基本操作</td><td><span class="status-badge inprogress">🔄 进行中</span></td></tr>
    </tbody>
    </table>

    <h3style="font-weight:600；边距：1.8rem0.6rem；font-size:1.2rem；">第二阶段·建筑体系(本科期间)</h3>
    <table class="romap-table">
    内容</th></tr></head>
    <tbody>
    <tr><td>数学基础</td><td>高等数学、线性代数、概率论</td></tr>
    <tr><td>后端开发</td><td>Flask/FastAPI+MySQL/Redis</td></tr>
    <tr><td>前端开发</td><td>vue3+前端工程化</td></tr>
    <tr><td>机器学习</td><td>经典算法+手写实现</td></tr>
    <tr><td>深度学习</td><td>PyTorch+CNN/RNN/Transformer</td></tr>
    </tbody>
    </table>

    <h3style="font-weight:600；margin:1.8rem0.6rem；font-size:1.2rem；">第三阶段·出作品(研究生期间)</h3>
    <table class="romap-table">
    内容</th></tr></head>
    <tbody>
    <tr><td>大模型应用</td><td>LLM微调、抹布、代理商开发</td></tr>
    <tr><td>工程能力</td><td>Docker、CI/CD、云部署</td></tr>
    <tr><td>开源贡献</td><td>参与知名开源项目</td></tr>
    <tr><td>求职准备</td><td>英文简历+项目复盘+系统设计</td></tr>
    </tbody>
    </table>
    </section>

    <！--========================技术栈========================-->
    <section class="section">
    <div class="section-title">
    <i class="fas fa-cubes"></i>技术栈
    </div>
    <div class="tech-tags">
    <span class="tech-tag"><i class="fab fa-python"></i>Python</span>
    <span class="tech-tag"><i class="fab fa-js"></i>JavaScript</span>
    <span class="tech-tag"><i class="fas fa-database"></i>SQL</span>
    <span class="tech-tag"><i class="fas fa-code"></i>C</span>
    <span class="tech-tag"><i class="fas fa-calculator"></i>NumPy</span>
    <span class="tech-tag"><i class="fas fa-table"></i>熊猫</span>
    <span class="tech-tag"><i class="fas fa-brain"></i>PyTorch<span style="color：#94a3b8；font-weight:400；">(学习中)</span></span>
    <span class="tech-tag"><i class="fas fa-server"></i>FastAPI/Flask</span>
    <span class="tech-tag"><i class="fas fa-database"></i>MySQL/Redis<span style="color：#94a3b8；font-weight:400；">(规划)</span></span>
    <span class="tech-tag"><i class="fab fa-vuejs"></i>vue3<span style="color：#94a3b8；font-weight:400；">(规划)</span></span>
    <span class="tech-tag"><i class="fab fa-git-alt"></i>Git/GitHub</span>
    <span class="tech-tag"><i class="fas fa-terminal"></i>Linux</span>
    <span class="tech-tag"><i class="fas fa-code"></i>VS代码</span>
    </div>
    </section>

    <！--========================项目作品集========================-->
    <section class="section">
    <div class="section-title">
    <i class="fas fa-folder-open"></i>项目作品集
    </div>
    <div class="项目网格">
    <div class="project-card">
    <h4><i class="fas fa-rocket"></i>待添加</h4>
    <div class="P-desc">首个项目即将登场，敬请期待</div>
    <span class="p-stack">-</span>
    <span class="p-status">▄规划中</span>
    </div>
    <div class="project-card">
    <h4><i class="fas fa-rocket"></i>待添加</h4>
    <div class="P-desc">每完成一个项目，都会在此登记</div>
    <span class="p-stack">-</span>
    <span class="p-status">▄规划中</span>
    </div>
    <div class="project-card">
    <h4><i class="fas fa-rocket"></i>待添加</h4>
    <div class="P-desc">独立仓库展示，持续积累</div>
    <span class="p-stack">-</span>
    <span class="p-status">▄规划中</span>
    </div>
    </div>
    <div class="section-sub"style="margin-top:0.2rem；">
            <i class="fas fa-arrow-right" style="color:#2563eb;"></i> 每完成一个项目，都会单独建仓展示。
            </div>
    </section>

    <!-- ======================== GitHub 统计 ======================== -->
    <section class="section">
        <div class="section-title">
            <i class="fab fa-github"></i> GitHub 统计
            </div>
        <div class="gh-stats">
            <!-- 将 YOUR_GITHUB_USERNAME 替换为真实用户名即可显示 -->
            <div>
                <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=default" alt="GitHub stats" />
            </div>
            <div>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact" alt="Top Langs" />
            </div>
            <div class="gh-placeholder">
                <i class="fas fa-pen"></i> 将 <code>YOUR_GITHUB_USERNAME</code> 替换为你的 GitHub 用户名
            </div>
            </div>
    </section>

    <!-- ======================== 联系 & 底部 ======================== -->
    <div class="footer-note">
        <p>
            <i class="fas fa-star" style="color:#f59e0b;"></i> 
            <strong>Star 这个仓库，见证我的成长！</strong>
        </p>
        <p style="margin-top:0.4rem;">
            <i class="fas fa-quote-left"></i> 
            The best way to predict the future is to create it. 
            <i class="fas fa-q
