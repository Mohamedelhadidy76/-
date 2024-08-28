# -<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قوة الآن - متجر إلكتروني</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>قوة الآن</h1>
        <input type="text" id="search" placeholder="ابحث عن منتج...">
        <button onclick="searchProduct()">بحث</button>
    </header>
    
    <nav>
        <ul>
            <li><a href="#">الرئيسية</a></li>
            <li><a href="#">المنتجات</a></li>
            <li><a href="#">عربة التسوق</a></li>
            <li><a href="#">تسجيل الدخول</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="product-list">
            <h2>المنتجات</h2>
            <div class="product">
                <h3>منتج 1</h3>
                <p>وصف المنتج 1.</p>
                <button onclick="addToCart('منتج 1')">إضافة إلى عربة التسوق</button>
            </div>
            <div class="product">
                <h3>منتج 2</h3>
                <p>وصف المنتج 2.</p>
                <button onclick="addToCart('منتج 2')">إضافة إلى عربة التسوق</button>
            </div>
            <div class="product">
                <h3>منتج 3</h3>
                <p>وصف المنتج 3.</p>
                <button onclick="addToCart('منتج 3')">إضافة إلى عربة التسوق</button>
            </div>
        </section>
    </main>
    
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2024</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
موقع الكتروني للتجاره الالكترونيه 
