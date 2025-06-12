<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的应用 - 技术支持</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #1d1d1f;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        h1 {
            background: linear-gradient(135deg, #007AFF, #5856D6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-align: center;
            margin-bottom: 30px;
            font-size: 2.5em;
            font-weight: 700;
        }
        .app-info {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 30px;
            border-left: 4px solid #007AFF;
            transition: transform 0.3s ease;
        }
        .app-info:hover {
            transform: translateY(-2px);
        }
        .contact-info {
            background: linear-gradient(135deg, #e3f2fd, #bbdefb);
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 30px;
            border-left: 4px solid #2196F3;
            transition: transform 0.3s ease;
        }
        .contact-info:hover {
            transform: translateY(-2px);
        }
        .faq-item {
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 12px;
            background: rgba(248, 249, 250, 0.8);
            border: 1px solid rgba(0, 122, 255, 0.1);
            transition: all 0.3s ease;
        }
        .faq-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(0, 122, 255, 0.15);
            border-color: rgba(0, 122, 255, 0.3);
        }
        .faq-question {
            font-weight: 600;
            color: #007AFF;
            margin-bottom: 10px;
            font-size: 1.1em;
        }
        .faq-answer {
            color: #555;
            line-height: 1.6;
        }
        .social-links {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: rgba(248, 249, 250, 0.5);
            border-radius: 12px;
        }
        .social-links a {
            display: inline-block;
            color: #007AFF;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border: 2px solid #007AFF;
            border-radius: 25px;
            transition: all 0.3s ease;
            font-weight: 500;
        }
        .social-links a:hover {
            background: #007AFF;
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 122, 255, 0.3);
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            color: #666;
            font-size: 14px;
            padding: 20px;
            border-top: 1px solid rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
            font-weight: 600;
            margin-bottom: 15px;
        }
        a {
            color: #007AFF;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #0056b3;
            text-decoration: underline;
        }
        .highlight {
            background: linear-gradient(120deg, #a8edea 0%, #fed6e3 100%);
            padding: 2px 6px;
            border-radius: 4px;
            font-weight: 500;
        }
        
        /* 添加错误处理和兼容性改进 */
        .error-info {
            background: linear-gradient(135deg, #ffebee, #ffcdd2);
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 20px;
            border-left: 4px solid #f44336;
            display: none;
        }
        .loading {
            opacity: 0;
            animation: fadeIn 0.5s ease-in forwards;
        }
        @keyframes fadeIn {
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container loading">
        <h1>📱 我的应用 - 技术支持</h1>
        
        <div class="error-info" id="errorInfo">
            <h3>⚠️ 浏览器兼容性提示</h3>
            <p>如果您遇到页面加载问题，请尝试：</p>
            <ul>
                <li>使用最新版本的Chrome、Firefox或Safari浏览器</li>
                <li>禁用可能冲突的浏览器扩展</li>
                <li>清除浏览器缓存和Cookie</li>
                <li>使用隐身模式打开页面</li>
            </ul>
        </div>

        <div class="app-info">
            <h2>🚀 关于我们的应用</h2>
            <p><strong>应用名称：</strong><span class="highlight">我的应用</span></p>
            <p><strong>当前版本：</strong>1.0.0</p>
            <p><strong>应用描述：</strong>这是一个功能强大的应用，为用户提供优质的服务体验</p>
            <p><strong>支持平台：</strong>iOS 13.0+</p>
        </div>

        <div class="contact-info">
            <h2>📧 联系我们</h2>
            <p><strong>技术支持邮箱：</strong> <a href="mailto:support@yourapp.com">support@yourapp.com</a></p>
            <p><strong>响应时间：</strong>我们会在 <span class="highlight">24小时内</span> 回复您的邮件</p>
            <p><strong>小红书：</strong> <a href="https://www.xiaohongshu.com/user/profile/your-id" target="_blank">@您的小红书用户名</a></p>
        </div>

        <div class="faq-section">
            <h2>❓ 常见问题</h2>
            
            <div class="faq-item">
                <div class="faq-question">Q: 如何开始使用这个应用？</div>
                <div class="faq-answer">A: 下载并安装应用后，首次打开会有引导教程。您也可以在设置中随时查看使用说明。</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: 应用出现闪退或卡顿怎么办？</div>
                <div class="faq-answer">A: 请尝试以下步骤：1) 完全关闭应用并重新打开；2) 重启您的设备；3) 检查是否有应用更新。如果问题仍然存在，请联系我们的技术支持。</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: 如何更新到最新版本？</div>
                <div class="faq-answer">A: 打开App Store，搜索我们的应用名称，如果有新版本可用，您会看到"更新"按钮。建议开启自动更新功能。</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: 支持哪些iOS版本？</div>
                <div class="faq-answer">A: 我们的应用支持iOS 13.0及以上版本。为了获得最佳体验，建议使用iOS 15.0或更高版本。</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: 如何删除我的账户数据？</div>
                <div class="faq-answer">A: 您可以在应用设置中找到"账户管理"选项，或者发送邮件到我们的支持邮箱请求删除数据。我们会在7个工作日内处理您的请求。</div>
            </div>
        </div>

        <div class="social-links">
            <h2>🌟 关注我们</h2>
            <a href="https://www.xiaohongshu.com/user/profile/your-id" target="_blank">小红书</a>
            <a href="mailto:support@yourapp.com">邮件支持</a>
        </div>

        <div class="footer">
            <p>© 2024 您的姓名/公司名. 保留所有权利。</p>
            <p>最后更新：2024年12月 | 隐私政策 | 使用条款</p>
        </div>
    </div>

    <script>
        // 添加错误处理和页面加载检测
        document.addEventListener('DOMContentLoaded', function() {
            // 检测页面加载状态
            const container = document.querySelector('.container');
            const errorInfo = document.getElementById('errorInfo');
            
            // 延迟显示内容，确保所有资源加载完成
            setTimeout(() => {
                container.style.opacity = '1';
            }, 100);
            
            // 检测是否有JavaScript错误
            window.addEventListener('error', function(e) {
                console.warn('页面错误已被捕获:', e.message);
                errorInfo.style.display = 'block';
            });
            
            // 检测未处理的Promise拒绝
            window.addEventListener('unhandledrejection', function(e) {
                console.warn('未处理的Promise拒绝:', e.reason);
                errorInfo.style.display = 'block';
                e.preventDefault(); // 防止错误在控制台显示
            });
        });
    </script>
</body>
</html>
