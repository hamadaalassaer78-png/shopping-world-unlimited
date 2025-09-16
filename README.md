body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
}

header {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  margin: 10px 0 0;
  font-size: 1.2em;
  color: #FFD700; /* ذهبي */
}

main {
  padding: 50px 20px;
}

section {
  margin-bottom: 40px;
}

.products ul {
  list-style: none;
  padding: 0;
}

.products li {
  background-color: #fff;
  margin: 10px auto;
  padding: 15px;
  width: 200px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.contact a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 10px;
  transition: 0.3s;
}

.contact a:hover {
  background-color: #FFD700;
  color: #000;
}

footer {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
}


---index_html = '''<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shopping World Unlimited</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shopping World Unlimited</h1>
    <p>🌍 كل ما تحتاجه في مكان واحد</p>
  </header>

  <main>
    <section class="about">
      <h2>عن شركتنا</h2>
      <p>نحن نقدم أفضل المنتجات لجميع احتياجاتك، بجودة عالية وأسعار منافسة.</p>
    </section>

    <section class="products">
      <h2>منتجاتنا</h2>
      <ul>
        <li>منتج 1</li>
        <li>منتج 2</li>
        <li>منتج 3</li>
        <li>والمزيد...</li>
      </ul>
    </section>

    <section class="contact">
      <h2>تابعنا على الانستغرام</h2>
      <a href="https://instagram.com/shoppingworldunlimited" target="_blank">
        @shoppingworldunlimited
      </a>
    </section>
  </main>

  <footer>
    <p>© 2025 Shopping World Unlimited. كل الحقوق محفوظة.</p>
  </footer>
</body>
</html>'''

style_css = '''body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
}

header {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  margin: 10px 0 0;
  font-size: 1.2em;
  color: #FFD700;
}

main {
  padding: 50px 20px;
}

section {
  margin-bottom: 40px;
}

.products ul {
  list-style: none;
  padding: 0;
}

.products li {
  background-color: #fff;
  margin: 10px auto;
  padding: 15px;
  width: 200px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}
index_html = '''<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shopping World Unlimited</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shopping World Unlimited</h1>
    <p>🌍 كل ما تحتاجه في مكان واحد</p>
  </header>

  <main>
    <section class="about">
      <h2>عن شركتنا</h2>
      <p>نحن نقدم أفضل المنتجات لجميع احتياجاتك، بجودة عالية وأسعار منافسة.</p>
    </section>

    <section class="products">
      <h2>منتجاتنا</h2>
      <ul>
        <li>منتج 1</li>
        <li>منتج 2</li>
        <li>منتج 3</li>
        <li>والمزيد...</li>
      </ul>
    </section>

    <section class="contact">
      <h2>تابعنا على الانستغرام</h2>
      <a href="https://instagram.com/shoppingworldunlimited" target="_blank">
        @shoppingworldunlimited
      </a>
    </section>
  </main>

  <footer>
    <p>© 2025 Shopping World Unlimited. كل الحقوق محفوظة.</p>
  </footer>
</body>
</html>'''

style_css = '''body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
}

header {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  margin: 10px 0 0;
  font-size: 1.2em;
  color: #FFD700;
}

main {
  padding: 50px 20px;
}

section {
  margin-bottom: 40px;
}

.products ul {
  list-style: none;
  padding: 0;
}

.products li {
  background-color: #fff;
  margin: 10px auto;
  padding: 15px;
  width: 200px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.contact a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 10px;
  transition: 0.3s;
}

.contact a:hover {
  background-color: #FFD700;
  color: #000;
}

footer {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
}'''
.contact a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 10px;
  transition: 0.3s;
}

.contact a:hover {
  background-color: #FFD700;
  color: #000;
}

footer {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
}''' = '''<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shopping World Unlimited</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shopping World Unlimited</h1>
    <p>🌍 كل ما تحتاجه في مكان واحد</p>
  </header>

  <main>
    <section class="about">
      <h2>عن شركتنا</h2>
      <p>نحن نقدم أفضل المنتجات لجميع احتياجاتك، بجودة عالية وأسعار منافسة.</p>
    </section>

    <section class="contact">
      <h2>تابعنا على الانستغرام</h2>
      <a href="https://instagram.com/shoppingworldunlimited" target="_blank">
        @shoppingworldunlimited
      </a>
    </section>
  </main>

  <footer>
    <p>© 2025 Shopping World Unlimited. كل الحقوق محفوظة.</p>
  </footer>
</body>
</html>'''

style_css = '''body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
}

header {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  margin: 10px 0 0;
  font-size: 1.2em;
  color: #FFD700;
}

main {
  padding: 50px 20px;
}

section {
  margin-bottom: 40px;
}

.contact a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 10px;
  transition: 0.3s;
}

.contact a:hover {
  background-color: #FFD700;
  color: #000;
}

footer {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
}'''

# إنشاء ملف ZIP
zip_filename = '/mnt/data/Shopping_World_Unlimited.zip'
with zipfile.ZipFile(zip_filename, 'w') as zipf:
    zipf.writestr('index.html', index_html)
    zipf.writestr('style.css', style_css)

zip_filename<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shopping World Unlimited</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shopping World Unlimited</h1>
    <p>🌍 كل ما تحتاجه في مكان واحد</p>
  </header>

  <main>
    <section class="about">
      <h2>عن شركتنا</h2>
      <p>نحن نقدم أفضل المنتجات لجميع احتياجاتك، بجودة عالية وأسعار منافسة.</p>
    </section>

    <section class="contact">
      <h2>تابعنا على الانستغرام</h2>
      <a href="https://instagram.com/shoppingworldunlimited" target="_blank">
        @shoppingworldunlimited
      </a>
    </section>
  </main>

  <footer>
    <p>© 2025 Shopping World Unlimited. كل الحقوق محفوظة.</p>
  </footer>
</body>
</html>


---

style.css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
}

header {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  margin: 10px 0 0;
  font-size: 1.2em;
  color: #FFD700; /* ذهبي */
}

main {
  padding: 50px 20px;
}

.about, .contact {
  margin-bottom: 40px;
}

.contact a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 10px;
  transition: 0.3s;
}

.contact a:hover {
  background-color: #FFD700;
  color: #000;
}

footer {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
}


---
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shopping World Unlimited</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shopping World Unlimited</h1>
    <p>🌍 كل ما تحتاجه في مكان واحد</p>
  </header>

  <main>
    <section class="about">
      <h2>عن شركتنا</h2>
      <p>نحن نقدم أفضل المنتجات لجميع احتياجاتك، بجودة عالية وأسعار منافسة.</p>
    </section>

    <section class="contact">
      <h2>تابعنا على الانستغرام</h2>
      <a href="https://instagram.com/shoppingworldunlimited" target="_blank">
        @shoppingworldunlimited
      </a>
    </section>
  </main>

  <footer>
    <p>© 2025 Shopping World Unlimited. كل الحقوق محفوظة.</p>
  </footer>
</body>
</html>

style.css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
}

header {
  background-color: #000;
  color: #fff;
  padding: 50px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  margin: 10px 0 0;
  font-size: 1.2em;
  color: #FFD700; /* ذهبي */
}

main {
  padding: 50px 20px;
}

.about, .contact {
  margin-bottom: 40px;
}

.contact a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 10px;
}

footer {
  background-color: #222;
  color: #fff;
  padding: 20px 0;
}
