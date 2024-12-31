<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>欢迎来到我的主页!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #f6d365 10%, #fda085 100%);
            color: white;
            text-align: center;
            padding: 50px;
        }
        h1, h3 {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.6);
        }
        h1 img {
            vertical-align: middle;
            margin-right: 10px;
        }
        p {
            font-size: 16px;
            margin: 15px auto;
        }
        .tech-stack img {
            margin: 5px;
            transition: transform 0.3s;
        }
        .tech-stack img:hover {
            transform: scale(1.2);
        }
        .card {
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            display: inline-block;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
            transition: transform 0.3s ease-in-out;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        .btn {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 18px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #c0392b;
        }
        .article-link {
            font-family: 'Comic Sans MS', cursive;
            color: #f1c40f;
            text-decoration: none;
            font-size: 20px;
            transition: color 0.3s;
        }
        .article-link:hover {
            color: #e74c3c;
        }
    </style>
</head>
<body>

    <h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> 欢迎来到我的主页!</h1>

    <p>喜欢简单的事、干净的东西和清楚的感觉</p>

    <h3>🧑‍💻 我的技术栈</h3>
    <div class="tech-stack">
        <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
        <img alt="C" src="https://img.shields.io/badge/-C语言-2088FF?style=flat-square&logo=C&logoColor=white" />
        <img alt="C++" src="https://img.shields.io/badge/-C++-2088FF?style=flat-square&logo=C&logoColor=white" />
        <img alt="GitHub" src="https://img.shields.io/badge/-GitHub-5849BE?style=flat-square&logo=github&logoColor=white" />
        <img alt="Unity" src="https://img.shields.io/badge/-Unity-311C87?style=flat-square&logo=unity&logoColor=white" />
        <img alt="Python" src="https://img.shields.io/badge/-Python-B7178C?style=flat-square&logo=python&logoColor=white" />
        <img alt="Kubernetes" src="https://img.shields.io/badge/-Kubernetes-CC6699?style=flat-square&logo=kubernetes&logoColor=white" />
        <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
        <img alt="NestJs" src="https://img.shields.io/badge/-NestJs-ea2845?style=flat-square&logo=nestjs&logoColor=white" />
        <img alt="HTML5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
        <img alt="OpenStack" src="https://img.shields.io/badge/-OpenStack-FB542B?style=flat-square&logo=openstack&logoColor=white" />
        <img alt="MySQL" src="https://img.shields.io/badge/-MySQL-EC4A3F?style=flat-square&logo=MySql&logoColor=white" />
        <img alt="Nginx" src="https://img.shields.io/badge/-Nginx-50B727?style=flat-square&logo=nginx&logoColor=white" />
    </div>

    <h3>🔥 我的文章</h3>
    <p>这里装着我的知识哦！</p>
    <p>
        <a href="https://fei-001.github.io/" target="_blank" class="article-link">这儿有颜值在线的！不来看看嘛？</a>
    </p>

    <h3>🎁 项目</h3>
    <div class="card">
        <h4><a href="https://github.com/pzxy-cs/pzxy-cloud-competition" style="color: white;">云计算竞赛</a></h4>
    </div>

    <div class="card">
        <h4><a href="http://124.70.26.87/monopoly/" style="color: white;">大富翁游戏</a></h4>
    </div>

    <h3>加入我</h3>
    <a href="https://github.com/fei-001/fei-001" target="_blank" class="btn">GitHub</a>

    <h1>美好的一天</h1>
    <img src="https://github.com/fei-001/picture/blob/main/boke-image/OIP2.jpg" style="width: 100%; max-width: 600px; border-radius: 20px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);" />

</body>
</html>
