# Charliezzl
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Charlie - 数字化转型者</title>
    <style>
        :root {
            --primary: #2f3e46;
            --secondary: #354f52;
            --accent: #52796f;
            --text: #2b2d42;
            --bg: #ffffff;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --primary: #cad2c5;
                --secondary: #84a98c;
                --accent: #52796f;
                --text: #edf6f9;
                --bg: #2b2d42;
            }
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            transition: all 0.3s ease;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text);
            background: var(--bg);
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        header {
            text-align: center;
            margin-bottom: 4rem;
        }

        h1 {
            color: var(--primary);
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .contact {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            margin: 1.5rem 0;
        }

        .contact a {
            color: var(--accent);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .card {
            background: rgba(var(--primary), 0.1);
            border-radius: 12px;
            padding: 1.5rem;
            border: 1px solid rgba(var(--primary), 0.2);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 1rem;
        }

        .post-list {
            list-style: none;
            margin-top: 2rem;
        }

        .post-item {
            padding: 1rem;
            margin: 1rem 0;
            border-left: 3px solid var(--accent);
        }

        footer {
            text-align: center;
            margin-top: 4rem;
            padding: 2rem 0;
            border-top: 1px solid rgba(var(--primary), 0.2);
        }

        .social-links {
            display: flex;
            gap: 2rem;
            justify-content: center;
            margin: 1.5rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Charlie</h1>
        <p class="subtitle">数字化转型者 | 业务高级分析师</p>
        <div class="contact">
            <a href="CharlieMozzl@outlook.com">
                📧 CharlieMozzl@outlook.com
            </a>
            <a href="tel:+V:wdwxhs01">
                📱 +V  wdwxhs01
            </a>
        </div>
    </header>

    <section class="portfolio">
        <h2>精选作品</h2>
        <div class="grid">
            <div class="card">
                <img src="https://placehold.co/600x400" alt="项目预览">
                <h3>制造业数字孪生</h3>
                <p>按照真实生产场景搭建虚拟数字空间，业务逻辑高度仿真，实现数字空间调整预测进一步指导实际生产</p>
            </div>
            <div class="card">
                <img src="https://placehold.co/600x400" alt="项目预览">
                <h3>数据分析仪表盘</h3>
                <p>使用D3.js构建的实时数据可视化解决方案</p>
            </div>
        </div>
    </section>

    <section class="blog">
        <h2>最新文章</h2>
        <ul class="post-list">
            <li class="post-item">
                <h3>AI+制造业软件</h3>
                <small>2025年3月15日</small>
                <p>探讨2025年AI技术在制造业软件系统使用场景方向探索...</p>
            </li>
            <li class="post-item">
                <h3>人形机器人的发展趋势</h3>
                <small>2024年3月10日</small>
                <p>从市场发展速度及相关分析数据分析国内机器人趋势...</p>
            </li>
        </ul>
    </section>

    <footer>
        <div class="social-links">
            <a href="https://github.com" target="_blank">GitHub</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
        </div>
        <p>© 2024 Charlie. 保留所有权利</p>
    </footer>
</body>
</html>
