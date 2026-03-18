## Hi there 👋

- 🌱 現在学習中: [学んでいる技術を書く（例：Python,React,AI Agent,English）]
- 👨‍💻 直近の目標: [PythonのAPIを作成してシステムに繋げる]
- 📝 定期的に TIL を更新しています


- 🌱 Currently learning: [Write about the technology you're learning (e.g., Python, React, AI Agent)]
- 👨‍💻 Near-term goal: [Create a Python API and connect it to the system]
- 📝 Regularly updating TIL

---

💡 Happy Hacking;)


# 自己紹介サイト
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Base Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
        }

        body {
            background-color: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
            padding: 20px;
        }

        /* Animated Gradient Background */
        .bg-gradient {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: radial-gradient(circle at 20% 30%, #1e293b 0%, #000 50%),
                        radial-gradient(circle at 80% 70%, #111827 0%, #000 50%);
        }

        /* Glassmorphism Card */
        .card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            padding: 40px;
            width: 100%;
            max-width: 480px;
            text-align: center;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
        }

        h1 {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 8px;
            letter-spacing: -0.02em;
        }

        .bio {
            color: #94a3b8;
            font-size: 0.95rem;
            line-height: 1.6;
            margin-bottom: 32px;
        }

        /* Skills Tag */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 8px;
            margin-bottom: 32px;
        }

        .skill-tag {
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 6px 14px;
            border-radius: 100px;
            font-size: 0.85rem;
            color: #e2e8f0;
            transition: all 0.2s ease;
        }

        .skill-tag:hover {
            background: rgba(255, 255, 255, 0.15);
            transform: translateY(-2px);
        }

        /* Links */
        .links {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .link-item {
            display: block;
            text-decoration: none;
            color: #000;
            background: #fff;
            padding: 12px;
            border-radius: 12px;
            font-weight: 600;
            font-size: 0.9rem;
            transition: opacity 0.2s ease;
        }

        .link-item:hover {
            opacity: 0.9;
        }

        .link-secondary {
            background: transparent;
            color: #fff;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .link-secondary:hover {
            background: rgba(255, 255, 255, 0.05);
            opacity: 1;
        }

        /* Responsive */
        @media (max-width: 480px) {
            .card {
                padding: 32px 24px;
            }
        }
    </style>
</head>
<body>
    <div class="bg-gradient"></div>

    <main class="card">
        <h1>[あなたの名前]</h1>
        <p class="bio">
            [簡単な自己紹介。ここにあなたの情熱や、現在取り組んでいるプロジェクトについて書いてください。]
        </p>

        <div class="skills-container">
            <span class="skill-tag">Python</span>
            <span class="skill-tag">Salesforce</span>
            <span class="skill-tag">Docker</span>
            <span class="skill-tag">Git</span>
            <span class="skill-tag">Technical Writing</span>
        </div>

        <nav class="links">
            <a href="https://github.com/あなたのユーザー名" class="link-item" target="_blank">GitHub</a>
            <a href="https://twitter.com/あなたのユーザー名" class="link-item link-secondary" target="_blank">Twitter / X</a>
        </nav>
    </main>
</body>
</html>
