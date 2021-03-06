#### [CSS Nedir?](css-nedir/)

* **Sorular**
  - Aşağıdakilerden hangisi CSS için **söylenemez**?
    - Açılımı Cascading Style Sheets'tir.
    - HTML elemanlarının nasıl görüntüleneceğini tanımlar.
    - .css uzantılı dosyalarda saklanırlar.
    - Css dosyalarında Javascript kodları saklanabilir.(doğru)

  - Aşağıdakilerden hangisi metnin rengini belirler?
    - color (doğru)
    - text-align
    - text-transform
    - word-spacing

  - "kodluyoruz.css" adlı bir css dosyasını html sayfasına dahil etmek için en uygun seçenek aşağıdakilerden hangisidir?
    - ```<head> <link rel="stylesheet" type="text/css" href="kodluyoruz.css"> </head>``` (doğru)
    - ```<body> <link rel="stylesheet" type="text/css" href="kodluyoruz.css"> </body>```
    - ```<head> <link rel="stylesheet" type="text/css" href="kodluyoruz"> </head>```
    - ```<head> <link type="text/css" href="kodluyoruz.css"> </head>```
* **Video**
  * https://www.youtube.com/watch?v=ZhVPut2OTeY
  * Bu videoda; CSS'in bir stil şablonu olduğunu, CSS ile birlikte neler yapabileceğimizi ve CSS'in bir HTML sayfasını nasıl etkilediğini anlattık.

-  [CSS - Inline CSS Nasıl Kullanılır](css-inline-css-nasil-kullanilir/)
   -  **video**
      -  https://www.youtube.com/watch?v=hU4CHUW_0EU
      -  Bu videoda; CSS kurallarının neler olduğunu, style oluştururken nelere dikkat edilmesi gerektiğini, Inline CSS özelliğini ve özellik değeri vererek style oluşturmayı anlattık.
   
- [Inline(Etikete Özel), Internal(Aynı Dosyada) ve External(CSS Dosyasında) CSS Kullanımı](inlineetikete-ozel,-internalayni-dosyada-ve-externalcss-dosyasinda-css-kullanimi/)

  - sorular

    -  Internal yöntemi kullanırken yazdığımız CSS kodlarını hangi element içine yazmamız gerekir?
       -  ``<body>``
       -  ``<script>``
       -  ``<head>`` (Doğru)
       -  ``<footer>``
    -  Aşağıda verilen kod hangi CSS yöntemi ile kullanılmıştır?

    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <title>This is a title.</title>
    </head>
    <body>
    <h1 style="color:blue; font-size:50px;"> This is a heading. </h1>
    <p> This is my space. </p>
    </body>
    </html>
    ```

    - Internal
    - Inline (Doğru)

    -  Float
    -  External

    - **Video**

       -  https://www.youtube.com/watch?v=hU4CHUW_0EU
       -  Bu videoda; CSS kurallarının neler olduğunu, style oluştururken nelere dikkat edilmesi gerektiğini, Inline CSS özelliğini ve özellik değeri vererek style oluşturmayı anlattık. 

- [Açıklama Satırları ile Çalışmak ve Genel Font Özellikleri](aciklama-satirlari-ile-calismak-ve-genel-font-ozellikleri/)
   -  **video**
      -  https://www.youtube.com/watch?v=LYMK0VARbiY
      -  Bu videoda; CSS de açıklama satırı eklemeyi, açıklama satırı eklerken kullanılan klavye kısayollarını ve açıklama satırlarının neden kullanıldığını; yazı özelliklerini, boyutunu, yazının rengini ve arkaplanın nasıl belirlendiğini anlattık. Ayrıca yazı fontunu belirlemek için dış kaynaklardan nasıl yararlanabileceğinizi de gösterdik.

- [CSS ile Class ve ID Kullanımı](css-ile-class-ve-id-kullanimi/)

  - **Sorular**

    - **Aşağıdakilerden hangisi doğru bir kullanımdır?**

      - ```css
        title#{color:blue;}
        ```

      -  ```css
         title#{color:blue;}
         ```

      -  ```css
         .title{color:green;} (D)
         ```

      -  ```css
         title{color:pink;}
         ```

    -  **Aşağıdaki ifadelerden hangisi yanlıştır?**

       -  Bir html elementi birden fazla class'a sahip olabilir.
       -  Bir html elementi sadece bir id'ye sahip olabilir.
       -  Bir class birden fazla html elementinde kullanılabilir.
       -  Bir id birden fazla html elementinde kullanılabilir.

    -  Aşağıdaki kodun çıktısı nedir?

    -  ```html
       <p class="main-text intro"> Birinci paragraf</p>
       <p class="main-text"> İkinci paragraf</p>
       <p id="outro"> Üçüncü paragraf</p>
       ```

    -  ```css
       .main-text {
           font-style: italic;
       }
       
       .intro {
           color:red;
       }
       
       #outro {
           color:green;
       }
       ```

       

       -  https://raw.githubusercontent.com/Kodluyoruz/taskforce/css/css/css-ile-class-ve-id-kullanimi/assets/Screenshot_8.jpg
       -  https://raw.githubusercontent.com/Kodluyoruz/taskforce/css/css/css-ile-class-ve-id-kullanimi/assets/Screenshot_7.jpg (D)
       -  https://raw.githubusercontent.com/Kodluyoruz/taskforce/css/css/css-ile-class-ve-id-kullanimi/assets/Screenshot_9.jpg
       -  https://raw.githubusercontent.com/Kodluyoruz/taskforce/css/css/css-ile-class-ve-id-kullanimi/assets/Screenshot_10.jpg

  -  **Video**
     -  https://www.youtube.com/watch?v=BvaZdSDImeY
     -  Bu videoda HTML etiketlerinde belirttiğimiz Class ve ID yapılarına nasıl CSS özellikleri verilebileceğini ve bazı Emmet özelliklerini anlattık.

- [Ödev 1](odev1/)

#### CSS Devam Konuları
- [CSS Seçiciler ile Çalışmak, İstediğimiz HTML Etiket Yapısına Özelliklik Ekleyebilmek](css-seciciler-ile-calismak,-i̇stedigimiz-html-etiket-yapisina-ozelliklik-ekleyebilmek/)

  - Sorular

    - Aşağıdaki kod bloğunda hangi satıra CSS uygulanmıştır ?

    - ```css
      .container > p.intro + ul > li:first-child {
              color: orange;
      }
      ```

    -  ```html
       <div class="container">
         <h2>Kodluyoruz</h2>
         <p class="intro">Lorem ipsum dolor sit amet.</p>
         <ul class="list">
           <li>HTML</li>
           <li>CSS</li>
           <li>Javascript</li>
         </ul>
       </div>
       <p class="intro">Lorem, ipsum.</p>
       <div class="container">
         <h2>Kodluyoruz</h2>
         <p>Lorem ipsum dolor sit.</p>
         <ul class="list">
           <li>Bootstrap</li>
           <li>React</li>
           <li>Angular</li>
          </ul>
       </div>
       ```
       -  `<p class="intro">Lorem ipsum dolor sit amet.</p>`
       -  `<li>Bootstrap</li>`
       -  `<li>HTML</li>` (D)
       -  `<li>CSS</li>`

    -  Üstteki kod bloğuna göre, bitişik kardeş etiketi p etiketi olan ve parentinin sınıf özelliği container olan h2 etiketine nasıl erişilir ?

       -  `p.intro +h2`
       -  `.container h2`
       -  `.container + h2`
       -  `p + .container h2` (D)

    -  `a[href$="org"]:hover` ile ifade edilmek istenen nedir?

       - a etiketi href özelliğinde başında "org" olan etiketin üzerine gelindiğinde
       - a etiketi üzerine gelindiğinde
       - href özelliği olan a etiketlerini
       - a etiketi href özelliği içinde sonunda org olan etiketin üzerine gelindiğinde (D)

  - Video

    -  https://www.youtube.com/watch?v=iScCq-8OWSE
    -  Bu videoda; CSS seçicileri ile HTML sayfasında bulunan herhangi bir elementi veya birden fazla elementi seçerek elementin özelliklerinin değiştirilmesini anlattık. Bununla birlikte bir başlığı seçip başlığın büyüklüğünü ve rengini değiştirme veya li etiketinin first-child(ilk eleman)/last-child(son eleman) gibi yapılarının seçilerek değiştirilmesi üzerine egzersizler gerçekleştirdik. 

- [CSS Kutu Özellikleri(Margin, Padding, Width, Height) Kullanımı](css-kutu-ozelliklerimargin,-padding,-width,-height-kullanimi/)

  -  **Sorular**
     -  Hangisi içeriğin aşağısında boşluk bırakır?
        -  bottom-padding: 20px;
        -  padding: 0 20px 0 0;
        -  padding-bottom: 20px; (D)
        -  padding: 20px;
     -  Hangisi kutu modeline ait bir kavram değildir?
        - margin
        - align (D)
        - padding
        - border
  -  **Video**
     -  https://www.youtube.com/watch?v=NLZpTcHyoGU
     -  Bu videoda; CSS ile birlikte bloklar oluşturmayı, blokların içine başlıklar ve paragraflar eklemeyi, blokların birbirine olan uzaklığını marjin ile ayarlamayı, blokların dışı ve içeriği arasındaki boşluğu padding ile ayarlamayı, blokları yanyana getirme ve bloklara şekil vermeyi anlattık. 

- [CSS Özet Çalışması ve Kendimi CSS Konusunda Nasıl Geliştirebilirim](css-ozet-calismasi-ve-kendimi-css-konusunda-nasil-gelistirebilirim/)

  -  **Sorular**
     -  CSS (Cascading Style Sheet) ile aşağıdakilerden hangisi yapılamaz ?
        -  Bir sayfanın yeniden yüklenmesi (D)
        -  Bir yazının fontunun Arial yapılması
        -  Bir link alt çizgisinin kaldırılması
        -  Bir link’in üzerine gelindiğinde link’in renginin değiştirilmesi
     -  Class selector ile id selector arasındaki en önemli fark aşağıdakilerden hangisidir?
        -  Class selector’ler yanlızca inline elementler için geçerlidir. id ise block level için geçerlidir.
        -  Class selector’ler yanlızca block level elementler için kullanılır. id ise inline elementler için kullanılır
        -  Class’lar sadece renk ve border özellikleri için kullanılır. id her style için kullanılabilir.
        -  Class selectorler istenildiği kadar kullanılabilir. id selector’ler yanlızca bir kere kullanılabilir. (D)
  -  **Video**
     -  https://www.youtube.com/watch?v=65TGMAWaqgA
     -  Bu videoda; CSS'de kendimizi nasıl geliştirebileceğimizi ve herhangi bir sorunla karşılaştığımızda nasıl çözüm üretebileceğimizi anlattık. Gradient ve Shodow oluşturma ile ilgili de küçük bir egzersiz yaptık.

-  [Ödev 2](odev2/)
