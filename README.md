<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دعوة زفاف - مصطفى & أماني</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Reem+Kufi:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-dark: #0f0507; /* عنابي داكن جداً قريب من الأسود */
            --card-bg: #1a0a0d; /* عنابي أسود ملكي */
            --gold-primary: #d4af37; /* ذهبي ناصع */
            --gold-accent: #f7e7a1; /* ذهبي فاتح */
            --text-light: #f5eef0;
            --border-gold: rgba(212, 175, 55, 0.6);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-light);
            font-family: 'Amiri', serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px 15px;
            background-image: radial-gradient(circle at center, #23080e 0%, #080203 100%);
        }

        .invitation-card {
            background-color: var(--card-bg);
            border: 2px solid var(--gold-primary);
            border-radius: 24px;
            padding: 45px 25px;
            max-width: 500px;
            width: 100%;
            text-align: center;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.8), 0 0 20px rgba(212, 175, 55, 0.15);
            position: relative;
            outline: 1px solid var(--border-gold);
            outline-offset: -10px;
        }

        .bismillah {
            font-size: 1.25rem;
            color: var(--gold-accent);
            margin-bottom: 20px;
            letter-spacing: 0.5px;
        }

        .header-title {
            font-family: 'Reem Kufi', sans-serif;
            font-size: 2.1rem;
            color: var(--gold-primary);
            margin-bottom: 15px;
            text-transform: uppercase;
        }

        .family-text {
            font-size: 1.05rem;
            color: #d1c2c5;
            line-height: 1.9;
            margin-bottom: 25px;
        }

        .names-wrapper {
            margin: 25px 0;
            padding: 10px 0;
        }

        .couple-names {
            font-family: 'Reem Kufi', sans-serif;
            font-size: 2.7rem;
            color: var(--gold-accent);
            line-height: 1.2;
            text-shadow: 0 0 15px rgba(212, 175, 55, 0.3);
        }

        .ampersand {
            font-size: 1.8rem;
            color: var(--gold-primary);
            margin: 5px 0;
            display: block;
        }

        .details-box {
            border-top: 1px solid var(--border-gold);
            border-bottom: 1px solid var(--border-gold);
            padding: 22px 0;
            margin: 30px 0;
            line-height: 2;
            font-size: 1.15rem;
        }

        .highlight {
            color: var(--gold-primary);
            font-weight: bold;
        }

        /* العداد التنازلي Minimalist */
        .timer-container {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin: 25px 0;
        }

        .timer-box {
            background: rgba(212, 175, 55, 0.05);
            border: 1px solid var(--border-gold);
            border-radius: 10px;
            padding: 10px;
            min-width: 68px;
        }

        .timer-number {
            font-size: 1.5rem;
            color: var(--gold-accent);
            font-weight: bold;
            font-family: sans-serif;
        }

        .timer-label {
            font-size: 0.75rem;
            color: #aaa;
            margin-top: 2px;
        }

        /* الأزرار */
        .btn-group {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-top: 25px;
        }

        .btn {
            background: transparent;
            color: var(--gold-primary);
            border: 1px solid var(--gold-primary);
            padding: 13px 20px;
            border-radius: 30px;
            text-decoration: none;
            font-size: 1rem;
            font-weight: bold;
            font-family: 'Reem Kufi', sans-serif;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .btn:hover {
            background-color: var(--gold-primary);
            color: #0d0507;
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.4);
        }

        .footer-text {
            margin-top: 20px;
            font-size: 0.9rem;
            color: #9e8a8e;
            font-style: italic;
        }

        @media (max-width: 480px) {
            .invitation-card { padding: 35px 18px; }
            .header-title { font-size: 1.8rem; }
            .couple-names { font-size: 2.3rem; }
            .details-box { font-size: 1.05rem; }
            .timer-box { min-width: 58px; padding: 8px 5px; }
        }
    </style>
</head>
<body>

    <div class="invitation-card">
        <div class="bismillah">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</div>
        <h1 class="header-title">دعوة زفاف</h1>
        
        <p class="family-text">
            تتشرف <b>آل مصطفى</b><br>
            و <b>آل فتيان </b><br>
            بدعوتكم لحضور حفل زفاف أبنائهم
        </p>

        <div class="names-wrapper">
            <div class="couple-names">مصطفى</div>
            <span class="ampersand">&</span>
            <div class="couple-names">أماني</div>
        </div>

        <div class="details-box">
            <p>🗓 <b>اليوم والتاريخ:</b> الاثنين <span class="highlight">19-10-2026</span></p>
            <p>⏰ <b>الوقت:</b> من <span class="highlight">8:30 مساءً</span> إلى <span class="highlight">11:00 مساءً</span></p>
            <p>📍 <b>المكان:</b> فندق سراج - جبل الحسين</p>
            <p style="font-size: 0.9rem; color: #b3a0a4;">(بجانب مستشفى الكندي)</p>
        </div>

        <!-- العداد التنازلي -->
        <div class="timer-container">
            <div class="timer-box">
                <div id="days" class="timer-number">00</div>
                <div class="timer-label">يوم</div>
            </div>
            <div class="timer-box">
                <div id="hours" class="timer-number">00</div>
                <div class="timer-label">ساعة</div>
            </div>
            <div class="timer-box">
                <div id="minutes" class="timer-number">00</div>
                <div class="timer-label">دقيقة</div>
            </div>
            <div class="timer-box">
                <div id="seconds" class="timer-number">00</div>
                <div class="timer-label">ثانية</div>
            </div>
        </div>

        <!-- الأزرار -->
        <div class="btn-group">
            <a href="https://maps.google.com/?q=Siraj+Hotel+Amman" target="_blank" class="btn">📍 موقع الفندق على الخريطة</a>
            <button onclick="addToCalendar()" class="btn">📅 إضافة إلى التقويم</button>
        </div>

        <p class="footer-text">أهلاً وسهلاً بكم، حضوركم يكتمل به فرحنا</p>
    </div>

    <script>
        const targetDate = new Date("October 19, 2026 19:30:00").getTime();

        const updateCountdown = () => {
            const now = new Date().getTime();
            const difference = targetDate - now;

            if (difference > 0) {
                const days = Math.floor(difference / (1000 * 60 * 60 * 24));
                const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((difference % (1000 * 60)) / 1000);

                document.getElementById("days").innerText = days.toString().padStart(2, '0');
                document.getElementById("hours").innerText = hours.toString().padStart(2, '0');
                document.getElementById("minutes").innerText = minutes.toString().padStart(2, '0');
                document.getElementById("seconds").innerText = seconds.toString().padStart(2, '0');
            } else {
                document.querySelector(".timer-container").innerHTML = "<p style='color:var(--gold-primary); font-weight:bold;'>أهلاً وسهلاً بكم في حفلنا!</p>";
            }
        };

        setInterval(updateCountdown, 1000);
        updateCountdown();

        function addToCalendar() {
            const title = encodeURIComponent("حفل زفاف مصطفى وأماني");
            const details = encodeURIComponent("حفل زفاف مصطفى وأماني في فندق سراج - جبل الحسين.");
            const location = encodeURIComponent("فندق سراج، جبل الحسين، عمان");
            const calendarUrl = `https://calendar.google.com/calendar/render?action=TEMPLATE&text=${title}&dates=20261019T163000Z/20261019T200000Z&details=${details}&location=${location}`;
            window.open(calendarUrl, '_blank');
        }
    </script>
</body>
</html>
