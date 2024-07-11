<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحتي الشخصية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .bio, .skills, .contact, .gallery {
            margin-bottom: 20px;
        }
        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact form input, .contact form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>مرحباً، أنا [اسمك]</h1>
</header>

<div class="container">
    <section class="bio">
        <h2>نبذة عني</h2>
        <p>محترف في مجال الإبداع والإنتاج الإعلامي، مهتم بالتمثيل، الغناء، الإخراج، تأليف الموسيقى، وتحرير الفيديو. أقوم بإنشاء وإخراج إعلانات ترويجية للمنتجات والشركات.</p>
    </section>

    <section class="skills">
        <h2>مهاراتي</h2>
        <ul>
            <li>تطوير الأفكار الإبداعية</li>
            <li>اختيار الممثلين المناسبين</li>
            <li>التصوير عالي الجودة</li>
            <li>الإخراج الإبداعي</li>
            <li>تحرير الفيديو بمهارة</li>
            <li>تأليف الموسيقى</li>
        </ul>
    </section>

    <section class="gallery">
        <h2>معرض الأعمال</h2>
        <img src="your-image1.jpg" alt="مشروع 1">
        <img src="your-image2.jpg" alt="مشروع 2">
        <!-- يمكنك إضافة المزيد من الصور هنا -->
    </section>

    <section class="contact">
        <h2>تواصل معي</h2>
        <form action="submit_form.php" method="post">
            <input type="text" name="name" placeholder="الاسم" required>
            <input type="email" name="email" placeholder="البريد الإلكتروني" required>
            <textarea name="message" placeholder="رسالتك" required></textarea>
            <input type="submit" value="إرسال">
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2024 [اسمك]. جميع الحقوق محفوظة.</p>
    <p>تابعني على:</p>
    <p>
        <a href="https://twitter.com/yourprofile" target="_blank">تويتر</a> |
        <a href="https://linkedin.com/in/yourprofile" target="_blank">لينكد إن</a> |
        <a href="https://instagram.com/yourprofile" target="_blank">إنستغرام</a>
    </p>
</footer>

</body>
</html>
