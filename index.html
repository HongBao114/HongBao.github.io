<!DOCTYPE html>
<html>
<head>
    <title>文件下载站</title>
    <meta charset="utf-8">
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .header {
            text-align: center;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        .file-list {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .file-item {
            padding: 15px;
            border-bottom: 1px solid #eee;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .file-item:last-child {
            border-bottom: none;
        }
        .download-btn {
            background: #4CAF50;
            color: white;
            padding: 8px 15px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>📁 欢迎来到红包的文件分享站</h1>
        <p>安全、快速地下载您需要的文件</p>
    </div>
    
    <div class="file-list">
        <h2>📋 可用文件列表</h2>
        
        <?php
        // 扫描当前目录
        $files = scandir('.');
        $fileCount = 0;

        // 定义要排除的文件
        $excludedFiles = ['index.php', 'README.md', 'CNAME'];

        foreach ($files as $file) {
            if (!in_array($file, $excludedFiles) && is_file($file)) {
                $fileCount++;
                $size = filesize($file);
                
                if ($size > 1024 * 1024) {
                    $sizeFormatted = round($size / (1024 * 1024), 2) . ' MB';
                } else {
                    $sizeFormatted = round($size / 1024, 2) . ' KB';
                }
                
                echo "
                <div class='file-item'>
                    <div>
                        <strong>📄 $file</strong><br>
                        <small>大小: $sizeFormatted</small>
                    </div>
                    <a href='$file' class='download-btn' download>下载</a>
                </div>";
            }
        }

        if ($fileCount == 0) {
            echo "<p>暂无文件可下载</p>";
        } else {
            echo "<p><small>共找到 $fileCount 个文件</small></p>";
        }
        ?>
    </div>
</body>
</html>
