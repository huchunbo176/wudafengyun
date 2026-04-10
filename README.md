<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>wdfy 下载</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }
        body {
            background: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        .box {
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 450px;
            width: 100%;
        }
        h1 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #333;
        }
        .desc {
            color: #666;
            margin-bottom: 30px;
            line-height: 1.6;
        }
        .download-btn {
            display: inline-block;
            padding: 14px 32px;
            background: #238636;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .download-btn:hover {
            background: #1a6e2a;
        }
        .tip {
            margin-top: 20px;
            font-size: 13px;
            color: #999;
        }
    </style>
</head>
<body>
    <div class="box">
        <h1>wdfy 下载</h1>
        <p class="desc">包含主程序 wdfy.exe 及依赖文件夹 _internal<br>下载后解压即可使用</p>

        <!-- 这里替换成你自己的 zip 下载链接 -->
        <a href="wdfy_full.zip" class="download-btn" download>立即下载</a>

        <p class="tip">温馨提示：下载后解压，不要删除 _internal 文件夹</p>
    </div>
</body>
</html>

