# site_portfolio
Небольшой сайт портфолио

Его можно посмотреть по этой ссылке: https://teasloxy.github.io/site_portfolio

Этот HTML-код разделен на несколько блоков, каждый из которых выполняет определенную функцию в структуре веб-страницы. Рассмотрим его поочередно:

1. **Объявление типа и языка документа:**
   ```html
   <!doctype html>
   <html lang="en">
   ```
   Этот блок указывает на тип и язык документа.

2. **Мета-теги и иконка сайта:**
   ```html
   <head>
     <!-- ... (мета-теги) ... -->
     <link rel="shortcut icon" href="favicon.png">
     <!-- ... -->
   </head>
   ```
   Здесь определены мета-теги, такие как кодировка, масштабирование и автор, а также указывается иконка сайта.

3. **Подключение шрифтов и стилей:**
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400&family=Playfair+Display:ital,wght@0,400;0,700;1,400;1,600&display=swap" rel="stylesheet">
   <link rel="stylesheet" href="css/bootstrap.min.css">
   <link rel="stylesheet" href="css/owl.carousel.min.css">
   <!-- ... (другие стили) ... -->
   <style>
     /* ... (дополнительные стили) ... */
   </style>
   ```

4. **Заголовок страницы и основное тело документа:**
   ```html
   <title>Моё портфолио</title>
   </head>
   <body>
     <!-- ... (основное тело документа) ... -->
   ```

5. **Секция приветствия с фоновым изображением:**
   ```html
   <div class="site-section overlay site-cover-2" style="background-image: url('images/landscape-4.jpg'); padding: 10rem 0 !important">
     <!-- ... (содержимое секции) ... -->
   </div>
   ```

6. **Секция "Перейти к работам?":**
   ```html
   <div class="site-section">
     <!-- ... (содержимое секции) ... -->
   </div>
   ```

7. **Секция с изображением и описанием 3D моделирования:**
   ```html
   <div class="features-lg">
     <!-- ... (содержимое секции) ... -->
   </div>
   ```

8. **Секция с изображением и описанием сложности 3D моделирования:**
   ```html
   <div class="site-section bg-light">
     <!-- ... (содержимое секции) ... -->
   </div>
   ```

9. **Секция портфолио с изображениями работ:**
   ```html
   <div class="site-section" id="portfolio">
     <!-- ... (содержимое секции) ... -->
   </div>
   ```

10. **Секция "Мои лучшие работы по мнению заказчиков":**
    ```html
    <div class="site-section overlay site-cover-2" style="background-image: url('images/landscape-3.jpg')">
      <!-- ... (содержимое секции) ... -->
    </div>
    ```

11. **Секция с изображениями проектов:**
    ```html
    <div class="site-section bg-light">
      <!-- ... (содержимое секции) ... -->
    </div>
    ```

12. **Блок с круглым изображением:**
    ```html
    <div class="container" data-aos="fade-up" data-aos-delay="0">
      <!-- ... (содержимое блока) ... -->
    </div>
    ```

13. **Секция "Мои планы":**
    ```html
    <div class="site-section" style="margin-top: 3rem">
      <!-- ... (содержимое секции) ... -->
    </div>
    ```

14. **Секция с числовыми показателями и изображением:**
    ```html
    <div class="site-section count-numbers">
      <!-- ... (содержимое секции) ... -->
    </div>
    ```

15. **Футер страницы:**
    ```html
    <div class="site-footer">
      <!-- ... (содержимое футера) ... -->
    </div>
    ```

16. **Подключение скриптов:**
    ```html
    <script src="js/jquery-3.5.1.min.js"></script>
    <!-- ... (подключение других скриптов) ... -->
    <script src="js/custom.js"></script>
    </body>
    </html>
    ```
   
Каждый из этих блоков представляет собой определенную секцию или функциональность веб-страницы.
