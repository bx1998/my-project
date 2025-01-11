<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="ابتسامة هوليوود - الحل المثالي لغطاء الأسنان للحصول على ابتسامة مثالية بسهولة وسرعة.">
    <meta name="keywords" content="ابتسامة هوليوود, غطاء الأسنان, تجميل الأسنان, ابتسامة مثالية">
    <meta name="author" content="ابتسامة هوليوود">
    <title>ابتسامة هوليوود</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
    <!-- إضافة Font Awesome -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');
        body {
            font-family: 'Cairo', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8; /* لون خلفية الصفحة */
        }
        .connected-images img {
            width: 100%;
            display: block;
            margin: 0;
            padding: 0;
        }
        .description {
            padding: 20px 10px;
            background-color: #ffffff;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            margin: 20px;
        }
        .description h2 {
            font-size: 2rem;
            color: #1e3a8a;
            margin-bottom: 10px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .description p {
            font-size: 1.1rem;
            color: #4b5563;
            margin-bottom: 15px;
            font-weight: 500; /* خط متوسط السماكة */
        }
        .order-button {
            display: inline-block;
            background: linear-gradient(to right, #2563eb, #7c3aed);
            color: white;
            padding: 12px 24px;
            border-radius: 8px;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: 700; /* خط عريض */
            transition: transform 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* ظل للزر */
        }
        .order-button:hover {
            transform: scale(1.1);
        }
        .why-choose-us {
            background: #ffffff;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            border-radius: 10px;
        }
        .why-choose-us h2 {
            font-size: 2.2rem;
            color: #1e3a8a;
            margin-bottom: 20px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .why-choose-us .card {
            background: #f9f9f9;
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .why-choose-us .card:hover {
            transform: translateY(-10px);
        }
        .why-choose-us .card h3 {
            font-size: 1.5rem;
            color: #1e3a8a;
            margin-bottom: 10px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .why-choose-us .card p {
            font-size: 1rem;
            color: #4b5563;
            font-weight: 500; /* خط متوسط السماكة */
        }
        .faq {
            background: #ffffff;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            border-radius: 10px;
        }
        .faq h2 {
            font-size: 2.2rem;
            color: #1e3a8a;
            margin-bottom: 20px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .faq .question {
            background: #f9f9f9;
            border-radius: 10px;
            padding: 15px;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .faq .question h3 {
            font-size: 1.5rem;
            color: #1e3a8a;
            margin-bottom: 10px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .faq .question p {
            font-size: 1rem;
            color: #4b5563;
            font-weight: 500; /* خط متوسط السماكة */
        }
        .contact-form {
            background: #ffffff;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            border-radius: 10px;
        }
        .contact-form h2 {
            font-size: 2.2rem;
            color: #1e3a8a;
            margin-bottom: 20px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: 500; /* خط متوسط السماكة */
        }
        .contact-form button {
            background: linear-gradient(to right, #2563eb, #7c3aed);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2rem;
            font-weight: 700; /* خط عريض */
            transition: transform 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* ظل للزر */
        }
        .contact-form button:hover {
            transform: scale(1.1);
        }
        .order-form {
            background: #ffffff;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            border-radius: 10px;
        }
        .order-form h2 {
            font-size: 2.2rem;
            color: #1e3a8a;
            margin-bottom: 20px;
            font-weight: 700; /* خط عريض */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1); /* ظل للنص */
        }
        .order-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: 500; /* خط متوسط السماكة */
        }
        .order-form button {
            background: linear-gradient(to right, #2563eb, #7c3aed);
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2rem;
            font-weight: 700; /* خط عريض */
            transition: transform 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* ظل للزر */
        }
        .order-form button:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header Section -->
    <header class="bg-gradient-to-r from-blue-500 to-purple-600 text-white py-6 sticky top-0 z-50 shadow-lg" data-aos="fade-down">
        <div class="container mx-auto flex justify-between items-center px-4">
            <h1 class="text-3xl font-bold">ابتسامة هوليوود</h1>
            <a href="https://wa.me/966575595002" target="_blank" class="bg-white text-blue-500 px-4 py-2 rounded font-bold hover:bg-gray-100 transition duration-300">
                <i class="fab fa-whatsapp"></i> اطلب الآن
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/yAb1x2k.jpg" alt="صورة مقدمة">
        <div class="description">
            <h2>النتيجة ستبهرك من أول استعمال!</h2>
            <p>احصل على ابتسامة مشرقة ومتألقة بسهولة وبسرعة مع ابتسامة هوليوود. مواد عالية الجودة وتصميم مثالي لكل من يبحث عن التميز.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="why-choose-us" data-aos="fade-up">
        <h2>لماذا تختار ابتسامة هوليوود؟</h2>
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="card">
                <i class="fas fa-star fa-3x text-blue-500 mb-4"></i>
                <h3>جودة عالية</h3>
                <p>نستخدم مواد آمنة وعالية الجودة لضمان راحتك ورضاك.</p>
            </div>
            <div class="card">
                <i class="fas fa-smile fa-3x text-blue-500 mb-4"></i>
                <h3>تصميم مخصص</h3>
                <p>تصميم يناسب جميع المقاسات ويوفر راحة فائقة.</p>
            </div>
            <div class="card">
                <i class="fas fa-check-circle fa-3x text-blue-500 mb-4"></i>
                <h3>نتيجة مضمونة</h3>
                <p>ابتسامة مشرقة من أول استعمال مع ضمان الرضا التام.</p>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/wMTA4V4.jpg" alt="صورة ثانية">
        <div class="description">
            <h2>تصميم يناسب الجميع</h2>
            <p>غطاء الأسنان مصمم ليتناسب مع جميع المقاسات ويمنحك ابتسامة مثالية في خطوات بسيطة.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/sSLWHdn.jpg" alt="صورة ثالثة">
        <div class="description">
            <h2>قبل وبعد - الفرق واضح</h2>
            <p>لا تتردد، انضم للآلاف الذين اختاروا ابتسامة هوليوود لتحسين مظهرهم وزيادة ثقتهم بأنفسهم.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/44uE2za.jpg" alt="صورة رابعة">
        <img src="https://imgur.com/P2l1tDu.jpg" alt="صورة خامسة">
        <img src="https://imgur.com/QOAkOdG.jpg" alt="صورة سادسة">
        <div class="description">
            <h2>المنتج الأكثر فاعلية</h2>
            <p>لا خجل بعد اليوم، ابتسم بكل ثقة.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/7Fb78pF.jpg" alt="صورة سابعة">
        <div class="description">
            <h2>جودة عالية</h2>
            <p>مواد آمنة وتصميم يدوم طويلاً لتحصل على أفضل تجربة مع منتجنا المميز.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/m6TjsJC.jpg" alt="صورة ثامنة">
        <div class="description">
            <h2>تصميم مريح</h2>
            <p>غطاء أسنان بتصميم مريح يناسب جميع الأحجام.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/Ol8B6TQ.jpg" alt="صورة تاسعة">
        <div class="description">
            <h2>ابتسامة مشرقة</h2>
            <p>غطاء أسنان بتقنية عالية لابتسامة مشرقة وجذابة.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <section class="connected-images" data-aos="fade-up">
        <img src="https://imgur.com/VH3RzZK.jpg" alt="صورة عاشرة">
        <div class="description">
            <h2>تصميم فاخر</h2>
            <p>غطاء أسنان بتصميم فاخر وطبقة لامعة لابتسامة هوليوودية.</p>
            <a href="https://wa.me/966575595002" target="_blank" class="order-button">
                <i class="fas fa-shopping-cart"></i> اطلب الآن
            </a>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="faq" data-aos="fade-up">
        <h2>الأسئلة الشائعة</h2>
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="question">
                <i class="fas fa-question-circle fa-2x text-blue-500 mb-4"></i>
                <h3>هل المنتج آمن للاستخدام؟</h3>
                <p>نعم، المنتج مصنوع من مواد آمنة تمامًا على الأسنان واللثة.</p>
            </div>
            <div class="question">
                <i class="fas fa-question-circle fa-2x text-blue-500 mb-4"></i>
                <h3>كيف يمكنني طلب المنتج؟</h3>
                <p>يمكنك الطلب مباشرة عبر الواتساب بالضغط على زر "اطلب الآن".</p>
            </div>
        </div>
    </section>

    <!-- Order Form Section -->
    <section class="order-form" data-aos="fade-up">
        <h2>اطلب الآن</h2>
        <form id="orderForm" class="container mx-auto max-w-md">
            <input type="text" id="name" placeholder="اسمك" required>
            <input type="tel" id="phone" placeholder="رقم هاتفك" required>
            <input type="text" id="city" placeholder="المدينة" required>
            <button type="submit">
                <i class="fas fa-paper-plane"></i> إرسال الطلب
            </button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="bg-gradient-to-r from-blue-500 to-purple-600 text-white py-6" data-aos="fade-up">
        <div class="container mx-auto text-center px-4">
            <p class="mb-4">©️ 2025 ابتسامة هوليوود - جميع الحقوق محفوظة</p>
            <div class="flex justify-center space-x-6">
                <a href="https://wa.me/966575595002" target="_blank" class="text-white text-2xl hover:text-gray-300">
                    <i class="fab fa-whatsapp"></i>
                </a>
                <a href="https://www.instagram.com/basemi196?igsh=MWY5MnNib3cwNGVqbw%3D%3D&utm_source=qr" target="_blank" class="text-white text-2xl hover:text-gray-300">
                    <i class="fab fa-instagram"></i>
                </a>
                <a href="https://facebook.com" target="_blank" class="text-white text-2xl hover:text-gray-300">
                    <i class="fab fa-facebook-f"></i>
                </a>
                <a href="https://twitter.com" target="_blank" class="text-white text-2xl hover:text-gray-300">
                    <i class="fab fa-twitter"></i>
                </a>
            </div>
        </div>
    </footer>

    <!-- Include Font Awesome -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true
        });

        // توجيه العميل إلى الواتساب بعد تعبئة النموذج
        document.getElementById('orderForm').addEventListener('submit', function (e) {
            e.preventDefault(); // منع إرسال النموذج بالطريقة التقليدية

            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            const city = document.getElementById('city').value;

            const message = `مرحبًا، أنا ${name} من مدينة ${city}، أرغب في شراء منتج ابتسامة هوليوود. رقم هاتفي هو: ${phone}`;
            const whatsappUrl = `https://wa.me/966575595002?text=${encodeURIComponent(message)}`;

            window.open(whatsappUrl, '_blank'); // فتح الواتساب في نافذة جديدة
        });
    </script>
</body>
</html>