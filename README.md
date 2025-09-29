# juewang.github.io
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>个人简介 - 张三</title>
    <style>
        /* 全局样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        /* 头部区域 */
        header {
            text-align: center;
            padding: 40px 0;
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
        }

        header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
            border: 4px solid white;
        }

        header h1 {
            font-size: 2.2em;
            margin-bottom: 5px;
        }

        header p {
            font-size: 1.1em;
            opacity: 0.9;
        }

        /* 内容区块通用样式 */
        section {
            background: white;
            padding: 25px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        section h2 {
            color: #2575fc;
            margin-bottom: 15px;
            font-size: 1.5em;
            border-bottom: 2px solid #eee;
            padding-bottom: 5px;
        }

        /* 技能标签样式 */
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill-tag {
            background: #6a11cb;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9em;
        }

        /* 联系方式样式 */
        .contact-info p {
            margin-bottom: 8px;
        }

        .contact-info a {
            color: #2575fc;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        /* 页脚 */
        footer {
            text-align: center;
            margin-top: 30px;
            color: #888;
            font-size: 0.9em;
        }

        /* 响应式设计 */
        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }

            header h1 {
                font-size: 1.8em;
            }

            section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>

<div class="container">

    <!-- 头部：头像 + 姓名 + 职业 -->
    <header>
        <!-- 如果您有头像，将 src 改为您的头像链接，例如：images/avatar.jpg -->
        <img src="https://via.placeholder.com/120x120/cccccc/666666?text=头像" alt="个人头像" />
        <h1>张三</h1>
        <p>软件工程师 · Python开发者 · 技术爱好者</p>
    </header>

    <!-- 个人简介 -->
    <section>
        <h2>📌 个人简介</h2>
        <p>
            你好！我是一名热爱技术的软件工程师，专注于 Python 编程、Web 开发与自动化运维。
            拥有丰富的项目实战经验，喜欢学习新技术，乐于分享与团队协作。
            我的目标是通过代码解决问题，让技术更好地服务生活与工作。
        </p>
    </section>

    <!-- 技能 -->
    <section>
        <h2>💡 技能专长</h2>
        <div class="skills">
            <span class="skill-tag">Python</span>
            <span class="skill-tag">Django / Flask</span>
            <span class="skill-tag">HTML / CSS / JavaScript</span>
            <span class="skill-tag">Git / GitHub</span>
            <span class="skill-tag">MySQL / SQLite</span>
            <span class="skill-tag">Linux</span>
            <span class="skill-tag">Docker（了解）</span>
            <span class="skill-tag">机器学习（入门）</span>
        </div>
    </section>

    <!-- 工作经历 / 项目经验（可选） -->
    <section>
        <h2>🚀 项目经验</h2>
        <ul>
            <li><strong>个人博客系统：</strong>使用 Django 开发的响应式博客，支持 Markdown、评论与搜索。</li>
            <li><strong>数据爬虫工具：</strong>基于 Python requests / BeautifulSoup 的小工具，用于抓取公开数据。</li>
            <li><strong>自动化脚本：</strong>编写 Shell & Python 脚本，用于日常运维与文件处理。</li>
        </ul>
    </section>

    <!-- 联系方式 -->
    <section>
        <h2>📬 联系我</h2>
        <div class="contact-info">
            <p><strong>邮箱：</strong> <a href="mailto:your.email@example.com">your.email@example.com</a></p>
            <p><strong>GitHub：</strong> <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
            <p><strong>个人网站 / 博客：</strong> <a href="https://yourwebsite.com" target="_blank">yourwebsite.com</a></p>
            <p><strong>微信：</strong> your_wechat_id （可选）</p>
        </div>
    </section>

    <!-- 页脚 -->
    <footer>
        <p>&copy; 2024 张三. 保留所有权利.</p>
    </footer>

</div>

</body>
</html>
