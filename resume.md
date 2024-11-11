<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <!-- 保持原有的 meta 和基础样式 -->
    <style>
        /* 添加一些新的样式来改进视觉效果 */
        .container {
            background-color: white;
            padding: 40px;  /* 增加内边距 */
            border-radius: 12px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
        }

        .skill-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }

        .skill-item {
            background: #f8f9fa;
            padding: 10px 15px;
            border-radius: 6px;
            border-left: 3px solid #3498db;
        }

        /* 添加联系方式的样式 */
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>個人簡歷</h1>

        <div class="section">
            <h2>基本資料</h2>
            <ul>
                <li>姓名：葉靜宜</li>
                <li>職稱：世新大學廣播電視電影學系學生</li>
                <li>聯絡方式：yejingyi@example.com</li>
                <li>個人網站：www.portfolio.com/yejingyi</li>
            </ul>
        </div>

        <div class="section">
            <h2>簡介</h2>
            <p>我是一位充滿創意和熱情的影視製作新秀，專注於影片剪輯和內容創作。在學習過程中，我積極參與各類實踐項目，努力將創意理念轉化為視覺作品。我對影視製作充滿熱忱，並期待能在這個領域不斷成長和突破。</p>
        </div>

        <!-- 技能部分使用新的网格布局 -->
        <div class="section">
            <h2>技能專長</h2>
            <div class="skill-list">
                <div class="skill-item">
                    <h3>影片製作</h3>
                    <ul>
                        <li>Final Cut Pro</li>
                        <li>Adobe Premiere Pro</li>
                        <li>影片腳本撰寫</li>
                    </ul>
                </div>
                <div class="skill-item">
                    <h3>攝影技術</h3>
                    <ul>
                        <li>數位單眼攝影</li>
                        <li>燈光設計</li>
                        <li>構圖技巧</li>
                    </ul>
                </div>
                <div class="skill-item">
                    <h3>音頻製作</h3>
                    <ul>
                        <li>配音製作</li>
                        <li>音效剪輯</li>
                        <li>混音技術</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>興趣與專長</h2>
            <ul>
                <li>短片創作</li>
                <li>攝影藝術</li>
                <li>音樂創作</li>
                <li>新媒體探索</li>
            </ul>
        </div>

        <div class="footer">
            <div class="contact-info">
                <span>📧 yejingyi@example.com</span>
                <span>📱 0912-345-678</span>
                <span>📍 台北市</span>
            </div>
        </div>
    </div>
</body>
</html>