# your-github-
index.html、style.css、script.js
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的個人簡介</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>

    <!-- Header 導覽欄 -->
    <header>
        <div class="logo">My Profile</div>
        <nav>
            <ul>
                <li><a href="#about">關於我</a></li>
                <li><a href="#experience">經歷</a></li>
                <li><a href="#services">服務</a></li>
                <li><a href="#contact">聯絡我</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section 介紹 -->
    <section class="hero">
        <div class="hero-content">
            <h1>你好，我是 [你的名字]</h1>
            <p>專業於保險業務，提供客戶最合適的保障方案。</p>
            <a href="#contact" class="cta-button">聯絡我</a>
        </div>
    </section>

    <!-- About Section 關於我 -->
    <section id="about" class="fade-in">
        <h2>關於我</h2>
        <p>擁有1年保險經驗，曾服務多位客戶，致力於提供專業且貼心的保障規劃。</p>
    </section>

    <!-- Experience Section 經歷 -->
    <section id="experience" class="fade-in">
        <h2>經歷</h2>
        <ul>
            <li>現職：保險業務員（1年經驗）</li>
            <li>前職：職業軍人</li>
            <li>專長：醫療險、理財規劃</li>
        </ul>
    </section>

    <!-- Services Section 服務項目 -->
    <section id="services" class="fade-in">
        <h2>服務範圍</h2>
        <div class="service-box">
            <h3>醫療險</h3>
            <p>提供完整的醫療保障規劃，讓您無後顧之憂。</p>
        </div>
        <div class="service-box">
            <h3>壽險規劃</h3>
            <p>確保家人未來的生活品質，提供最合適的保障方案。</p>
        </div>
    </section>

    <!-- Contact Section 聯絡表單 -->
    <section id="contact" class="fade-in">
        <h2>聯絡我</h2>
        <form id="contact-form">
            <label for="name">姓名</label>
            <input type="text" id="name" required>

            <label for="email">電子郵件</label>
            <input type="email" id="email" required>

            <label for="message">訊息</label>
            <textarea id="message" required></textarea>

            <button type="submit">送出</button>
        </form>
        <p id="form-message"></p>
    </section>

</body>
</html>
