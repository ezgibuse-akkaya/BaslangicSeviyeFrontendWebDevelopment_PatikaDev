# Başlangıç Seviye Web Development Patikası - PatikaDev

[Patika.dev](https://app.patika.dev/egitimler) adresindeki "Başlangıç Seviye Frontend Web Development Patikası" eğitiminde kullandığım kaynak kodları içeren bir repo.

Bu README dosyasında bu eğitimdeki pratik ve ödevlerin cevaplarını bulacaksınız.

--------------------------------------------------------------------------------------------------------------------------------------
## :brain: HTML Ödev-1  İlk Web Sayfamızı Oluşturmak


### :question: SORU 
Eveet harika konular öğrendikten sonra sıra geldi ödevimize. Bu ödevimizde ilk web sayfamızı tasarlayacağız. Çok heyecanlı değil mi? Sizlerden istediğimiz çok basit bir şekilde öğrendiklerinizle bir web sayfası tasarlamanız.

Siteyi açtığımızda adınız ve soyadınızı başlık şeklinde göstermeniz gerekiyor.
Ad-Soyadın altında alt başlık olarak Hakkımda yazmalıdır.
Altına paragraf içerisinde neler yaptığınızı ve nelerden hoşlandığınızı yazabilirsiniz.
Web sitenizi kaydederken dosya adı olarak 'index.html' seçmeniz gerekmektedir.
Yazdığınız kodları açıklayan yorum satırları eklemeyi unutmayın.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <b><h1>Ezgi Buse Akkaya</h1></b>
   <h3> <b>Hakkımda</b></h3>
    <p>Merhaba ben Ezgi Buse Akkaya! Mersinde yaşıyorum. Yazılımla uğraşmayı ve okumayı çok seviyorum. tam bir Neslihan Demir hayranıyım! Web geliştirme ile ilgileniyorum. Kodluyoruz'un bu Eğitim serisi sayesinde harika şeyler öğrendim ve öğrenmeye devam ediyorum!</p> 

    <h2>Sevdiğim Diziler</h2>

    <h3>Star Trek: The Next Generation</h3>
    <p>Uzay Yolu: Yeni Nesil (Star Trek: The Next Generation) Gene Roddenberry tarafından yaratılmış olan kurgusal Uzay Yolu evreninde geçen bir bilimkurgu dizisidir. Türkiye'de 1990-1997 yılları arasında Star TV'de yayınlanmıştır.</p>
    <p>Bu dizide en çok dikkat çeken Enterprise gemisinin kaptan Jean-Luc Picard'dır. Tabii onun yanında filonun tek robot asker Data, tek Klingon asker Worf gibi birçok ikonik karakteri de mevcut.</p>

 </body>
</html>
```
</details>

## :brain: HTML Ödev-2  Kişisel Sayfamızı Detaylandırmaya Devam Etmek


### :question: SORU 
Bir önceki ödevimizde ilk web sayfamızı yapıp bunu kişisel sayfamız olarak tasarlamıştık. Yeni öğrendiğimiz bilgiler dahilinde bu sayfayı geliştirmeye devam edelim. Hazır mısınız? E hadi buyurun o zaman.

Sayfanıza bir adet resim ekleyin ve bu resime bir açıklama yazın.
Sevdiğiniz film, dizi ve kitapları bunlar başlıklar olacak şekilde sıralayınız. (Film, dizi, kitap sıralı liste, içerikleri bullet liste olacak şekilde)
Bunları sıralarken film ve dizilerin en az bir tanesine IMDb linki, kitapların bir tanesine de** Goodreads linkini** yazınız.
Kurduğunuz yapılarda block, inline gibi elementler kullanmaya çalışın.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hakkımda</title>
</head>
<body>
    <h1>Ezgi Buse Akkaya</h1>
    
    <h2>Hakkımda</h2>

    <p>Merhaba. Ben Ezgi Buse Akkaya! Mersin'de yaşıyorum. Bilimkurgu izlemeyi ve okumayı çok seviyorum. Tam bir Star Trek hayranıyım! Web geliştirme ile ilgileniyorum. Kodluyoruz'un bu eğitim serisi sayesinde harika şeyler öğrendim ve öğrenmeye devam ediyorum! Siz de aramıza katılın!</p>

    <h3>İlgi Alanlarım</h3>


    <div>
        <ol>
            <li>Film
                <ul>
                    <li><a href="https://www.imdb.com/title/tt0118715/" target="_blank">The Big Lebowski</a></li>
                    <li>The Blues Brothers</li>
                    <li>Neredesin Firuze</li>
                </ul>
            </li>
            <li>Dizi
                <ul>
                    <li><a href="https://www.imdb.com/title/tt0092455/" target="_blank">Star Trek</a></li>
                    <li>Battlestar Galactica</li>
                    <li>The IT Crowd</li>
                </ul>
            </li>
            <li>Kitap
                <ul>
                    <li><a href="https://www.goodreads.com/review/show/2119945862" target="_blank">Yerdeniz</a></li>
                    <li>Dune</li>
                    <li>Androidler Elektrikli Koyun Düşler Mi?</li>
                </ul>
            </li>
        </ol>
    </div>

    <h2>Sevdiğim Diziler</h2>

    <h3>Star Trek: The Next Generation</h3>

    <img src="images/star-trek.jpg" alt="Star Trek kapak resmi">

    <p>Uzay Yolu: Yeni Nesil (Star Trek: The Next Generation) Gene Roddenberry tarafından yaratılmış olan kurgusal Uzay Yolu evreninde geçen bir bilimkurgu dizisidir. Türkiye'de 1990-1997 yılları arasında Star TV'de yayınlanmıştır.</p>
    
    <p>Bu dizide en çok dikkat çeken Enterprise gemisinin kaptanı <span style="font-weight: bold;">Jean-Luc Picard</span>'dır. Tabii onun yanında filonun tek robot asker <span style="font-style: italic;">Data</span>, tek Klingon asker <span style="font-style: italic;">Worf</span> gibi birçok ikonik karakteri de mevcut.</p>

</body> 
</html>
  ```
</details>

## :brain: HTML Bölüm Sonu Çalışması


### :question: SORU 
Bu videoda; şimdiye kadar öğrendiğimiz HTML etiketleri ile bir web sitesi oluşturmaya çalışacağız. Anasayfa, hakkımızda ve iletişim sayfaları oluşturarak bir HTML projesi yapacağız.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //about_us.html
```html
  
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hakkımızda | Kodluyoruz</title>
</head>
<body>
    <!-- Navbar - Start -->
    <header>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </header>
    <!-- Navbar - End -->

    <!-- Content - Start -->
    <section>
        <!-- Articles - Start -->
        <article>
            <h2>Hakkımızda</h2>
            <img src="https://picsum.photos/id/77/600/300" alt="Yazi 1">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus, sint?</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Ut culpa impedit repellat quasi!</p>
            <p>Ducimus, error officia! Neque, nulla!</p>
            <ol>
                <li>Lorem, ipsum dolor.</li>
                <li>Rerum, neque ipsam?</li>
                <li>Illum, cupiditate quisquam.</li>
                <li>Magnam, sequi iure?</li>
            </ol>
            <hr>
        </article>
        <!-- Articles - End -->
    </section>
    <!-- Content - End -->

    <!-- Footer - Start -->
    <footer>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </footer>
    <!-- Footer - End -->
</body>
</html>
  ```
  
  //contact.html
   ```html
  
  <!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>İletişim | Kodluyoruz</title>
</head>
<body>
    <!-- Navbar - Start -->
    <header>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </header>
    <!-- Navbar - End -->

    <!-- Content - Start -->
    <section>
        <!-- Articles - Start -->
        <article>
            <h2>İletişim</h2>
            <img src="https://picsum.photos/id/7/600/300" alt="Yazi 1">
            <p>
                Adres: 
            </p>
            <Address>
                Zemin İstanbul <br>
                Şahkulu, Şişhane Metro Durağı, Meşrutiyet Cd. No:125, 34421 <br> 
                Beyoğlu/İstanbul
            </Address>
            <ul>
                <li><a href="tel:02122223344">0212 222 33 44</a></li>
                <li><a href="mailto:info@kodluyoruz.org">info@kodluyoruz.org</a></li>
            </ul>
            <hr>
        </article>
        <!-- Articles - End -->
    </section>
    <!-- Content - End -->

    <!-- Footer - Start -->
    <footer>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </footer>
    <!-- Footer - End -->
</body>
</html>
   ```
  //index.html
   ```html
  <!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kodluyoruz</title>
</head>
<body>
    <!-- Navbar - Start -->
    <header>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </header>
    <!-- Navbar - End -->

    <!-- Content - Start -->
    <section>
        <!-- Articles - Start -->
        <article>
            <h2>Birinci Yazı</h2>
            <img height="300" src="img/photo.jpeg" alt="Yazi 1">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus, sint?</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Ut culpa impedit repellat quasi!</p>
            <p>Ducimus, error officia! Neque, nulla!</p>
            <ol>
                <li>Lorem, ipsum dolor.</li>
                <li>Rerum, neque ipsam?</li>
                <li>Illum, cupiditate quisquam.</li>
                <li>Magnam, sequi iure?</li>
            </ol>
            <hr>
        </article>
        <article>
            <h2>İkinci Yazı</h2>
            <img src="https://picsum.photos/id/27/600/300" alt="Yazi 1">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus, sint?</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Ut culpa impedit repellat quasi!</p>
            <p>Ducimus, error officia! Neque, nulla!</p>
            <ul>
                <li>Lorem, ipsum dolor.</li>
                <li>Rerum, neque ipsam?</li>
                <li>Illum, cupiditate quisquam.</li>
                <li>Magnam, sequi iure?</li>
            </ul>
            <hr>
        </article>
        <article>
            <h2>Üçüncü Yazı</h2>
            <img src="https://picsum.photos/id/217/600/300" alt="Yazi 1">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus, sint?</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <p>Ut culpa impedit repellat quasi!</p>
            <p>Ducimus, error officia! Neque, nulla!</p>
            <hr>
        </article>
        <!-- Articles - End -->
    </section>
    <!-- Content - End -->

    <!-- Footer - Start -->
    <footer>
        <nav>
            <ul>
                <li>
                    <a href="index.html">Ana Sayfa</a>
                </li>
                <li>
                    <a href="about-us.html">Hakkımızda</a>
                </li>
                <li>
                    <a href="contact.html">İletişim</a>
                </li>
            </ul>
        </nav>
    </footer>
    <!-- Footer - End -->
</body>
</html>
   ```
</details>

## :brain: HTML Ödev-3 Çikolatalı Küp Tarifi


### :question: SORU 
Bu ödevimizde sevdiğimiz bir yemek ya da tatlının tarifini öğrendiğimiz bir web sitesini, HTML etiketlerini kullanarak yazmaya çalışacağız.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //index.html
```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Çikolatalı Küp</title>
    
    <!-- External CSS -->
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <!-- Header - Start -->
        <header>
            <h1 class="ana-baslik"><em>...Çikolata Küpleri...</em></h1>
            <p>
                <strong><i>çikolatalı ve şam fıstıklı tadımlık lezzetler... Yalnızca 4 malzeme ile hazırlanan çikolata küpleri, renkli kağıtlarda veya kürdan batırılarak servis edilir. Özellikler kalabalık sofralarda yer verilen çikolata küpleri, doğum günü gibi özel etkinliklerde de sunulabilir.</i></strong>
            </p>
        </header>    
    <!-- Header - End -->

    <!-- Content - Start -->
        <section>
            <article>
                <p>
                    <b>Tarif:</b> Rukiye Beyza Sarıkaya
                </p>
                    <div class="container">
                        <div class="square-mark">
                            <div class="centered-dot"></div>
                        </div>
                        <div class="liste">
                            <ul>
                                <li class="liste1"><span class="icerik">Kaç Kişilik:</span>4kişilik</li>
                                <li class="liste1 marg"><span class="icerik">Hazırlama Süresi:</span>30 dakika</li>
                                <li class="liste1 marg"><span class="icerik">Pişirme Süresi:</span>10 dakika</li>
                            </ul>
                        </div>
                    </div>
            </article>

            <article class="bolum">
                <div class="kirmizi">
                    Çikolata Küpleri Tarifi İçin Malzemeler..
                </div>
                <ul class="liste2ul">
                    <li class="liste2li">350 gr bitter çikolata</li>
                    <li class="liste2li">150 ml krema</li>
                    <li class="liste2li">1 çorba kaşığı tereyağı</li>
                    <li class="liste2li">150 gr şamfıstık (Badem veya fındık da olabilir</li>
                </ul>
            </article>
            <article class="bolum">
                <div class="kirmizi">
                    Çikolata Küpleri Nasıl Yapılır?
                </div>
                <ol class="liste2ul padzero">
                    <li class="liste2li">Bitter çikolatayı benmari usulü eritin.</li>
                    <li class="liste2li">Eriyen çikolatanın üzerine krema veya tereyağını ekleyip iyice karıştırıp tencereyi bir tezgaha alın.</li>
                    <li class="liste2li">Şamfıstıkları havanda çok az dövüp irili ufaklı parçalara bölün.</li>
                    <li class="liste2li">Ufalanan fıstıkları çikolatalı karışıma ekleyip karıştırın.</li>
                    <li class="liste2li">Hazırladığınız çikolatayı varsa alüminyum hazır bir kare tepsiye, yoksa kenarlarından taşarak yağlı kağıt yerleştirdiğiniz küçük bir tepsiye dökün.</li>
                    <li class="liste2li">Buzdolabında iki saat bekletin</li>
                    <li class="liste2li">Çikolatayı kalıptan çıkartın. Kare parçalara bölün.</li>
                </ol>
            </article>
        </section>
    <!-- Content - End -->
    <!-- Footer - Start -->
        <footer>
            <div class="footer">
                <h2 class="sonbaslik">Afiyet olsun</h3>
            </div>
        </footer>
    <!-- Footer - End -->
    
</body>
</html>
  ```
  //style.css
  ```css
  body{
    background-color: #E0C9A9;
}
.ana-baslik{
    color: #5E2610;
}
.container{
    display: flex;
    flex-direction: row;
}
.square-mark{
    position: relative;
    width: 6px;
    height: 6px;
    display: flex;
    align-self: center;
    background-color: black;
    
}
.centered-dot{
    width: 1.3px;
    height: 1.3px;
    background-color: rgb(255,255,255);
    margin: 0;
    position:absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%);
}
.liste{
    display: flex;
    justify-self: center;
    margin: auto;
}
ul{
    padding: 0px;
    margin: 0px;
}
li.liste1{
    text-decoration: underline;
    list-style-type: none;
    display:inline-flex;
    margin-left: 10px;
    margin-right: auto;
    text-align: center;
    ;
}
.icerik{
    font-weight: bold;
    color: #9C3B0F;
}
.bolum{
    margin-left: 33%;
    margin-top: 20px;
}
.kirmizi{
    display: inline;
    background-color: #963102;
    color: white;
    font-weight: bold;
    border-radius: 10px;
}
.liste2ul{
    margin-top: 20px;
    margin-left: 3%;
}
.liste2li{
    margin-bottom: 5px;
}
.padzero{
    padding: 0;
}
.footer{
    letter-spacing: 2px;
    color: #2C1504;
}
.sonbaslik{
    margin-left: 60%;
    font-weight:500;
          }
  
  ```
  </details>
  
## :brain: CSS Ödev-1 Sayfamıza Biraz Makyaj Yapalım


### :question: SORU 
  
Herkese merhaba arkadaşlar kanalımıza hoş geldiniz, bugün HTML sayfamıza hafif bir makyaj yapacağız. Komik gelse de aslında tam olarak böyle yapacağız. Bir HTML sayfası oluşturup buna CSS ile tasarımsal açıdan güzellikler katacağız, HTML sayfamıza güzelliği getireceğiz.

HTML sayfasını sıfırdan oluşturacaksınız. Eklemek istediğiniz ekstra özellikler tamamen size kalmış durumda.
Sitemiz birkaç sayfadan oluşacak. Yani menü kısmında linkler vererek başka sayfaya geçilebilecek.
Renkler tamamen sizin zevkinize kalmış durumda. Fakat renkler konusunda biraz yardım almak isterseniz Colorhunt renk paletleri konusunda muazzam bir site.
Yazacağınız CSS etiketlerini Inline ve Internal yazabilirsiniz. External kullanmak tamamen sizin tercihinizdir.
CSS yazarken noktalı virgülleri unutmayın. Biliyorum unutacaksınız, olur böyle şeyler...
CSS ile ilgili yardımcı kaynak için w3schools.com'un CSS tutorialını, Türkçe kaynak için Fatih Hayrioğlu'nun web sitesini kullanabilirsiniz.
Kendini tekrar eden yapılar kullanmamaya özen gösteriniz. Ya da kendini tekrar eden yapılarda kullandığımız özelliği kullanın. (İpucu: Inline(Etikete Özel), Internal(Aynı Dosyada) ve External(CSS Dosyasında) CSS Kullanımı)
Sayfalarınızda kullandığınız fontlar için daha önce de videolarda bahsettiğimiz Google Fonts'u kullanabilirsiniz.
Ana sayfada bulunan listelerin noktalarını ortalamak için list-style-position: inside'i kullanabilirsiniz.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //about-us.html
```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hakkımızda</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
     <!-- Header Bölümü -->
    <header>
        <!-- Anasayfa Başlık -->
        <h1 class="anabaslik">Müzik Dükkanım</h1>
    </header>
    <!-- Nav Bölümü -->
    <nav class="nav">
        <ul class="navlist">
            <li class="navlistli"><a href="index.html">Ana Sayfa</a></li>
            <li class="navlistli ml15"><a href="products.html">Ürünlerimiz</a></li>
            <li class="navlistli ml15"><a href="about-us.html">Hakkımızda</a></li>
        </ul>
    </nav>
    <!-- Hakkımızda Main -->
    <main>
        <article>
            <h2 class="hakkimizdabaslik">Hakkımızda</h2>
            <p>Müzik Dükkanım 2021 yılında Cengiz C. Mataracı ve Furkan Tolga Yüce tarafından kurulmuştur. Çeşitli müzik aletlerini uygun fiyatlar ile buluşturmak için kurulmuştur.</p>
        </article>
        <article>
            <h4 class="hakkimizdaaltbaslik">Vizyonumuz</h4>
            <p>İnsanlara kaliteli müzik aletleri sağlamak. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Soluta animi ea nostrum unde sapiente quas, cupiditate iste nisi vitae earum? Optio cumque eius debitis culpa recusandae. Atque neque minima soluta consequatur quos eius, eveniet vitae laborum in nihil harum corporis rerum expedita facilis perspiciatis corrupti deserunt consequuntur architecto dolorem ducimus accusantium fugit culpa asperiores ratione? Labore neque harum sed asperiores.</p>
        </article>
        <article>
            <h4 class="hakkimizdaaltbaslik">Misyonumuz</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aperiam dolore laborum veritatis facere mollitia veniam optio, qui eum tempora, maxime unde quibusdam repudiandae nobis, nihil enim praesentium ratione velit? Earum, molestiae. Officia voluptatum quae autem illum saepe aliquid enim rerum quaerat, dicta tenetur ipsum. Minima aliquid iusto dolorum hic tempora amet voluptatibus delectus, atque deserunt reprehenderit perspiciatis facilis iure id harum totam velit perferendis rem quos quia nulla adipisci molestias aut itaque. Placeat nam, reprehenderit quo voluptas in cumque sequi est magnam, mollitia ad, sit eveniet assumenda corporis molestias laborum?</p>
        </article>
    </main>
</body>
</html>
  ```
   //index.html
   ```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anasayfa</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body> 
    <!-- Header Bölümü -->
    <header>
        <!-- Anasayfa Başlık -->
        <h1 class="anabaslik">Müzik Dükkanım</h1>
    </header>
    <!-- Nav Bölümü -->
    <nav class="nav">
        <ul class="navlist">
            <li class="navlistli"><a href="index.html">Ana Sayfa</a></li>
            <li class="navlistli ml15"><a href="products.html">Ürünlerimiz</a></li>
            <li class="navlistli ml15"><a href="about-us.html">Hakkımızda</a></li>
        </ul>
    </nav>
    <!-- Anasayfa Main -->
    <main>
        <article>
            <h2 class="anasayfabaslik">Ana Sayfa</h2>
            <p class="anasayfap1">Müzik Dükkanım sitemize hoşgeldiniz! Bu sitede çeşitli müzik aletlerini bulabilirsiniz. Uygun fiyatlarımız ve kalite ürünlerimiz için <a href="products.html">Ürünlerimiz</a> sayfamızı ziyaret edebilirsiniz.</p>
        </article>
        <article>
            <h4 class="anasayfaaltbaslik">Sitemizde Bulunan Müzik Aletleri</h4>
            <div class="listdiv">
                <ul class="anasayfalistul">
                    <li class="anasayfalistli">Gitar</li>
                    <li class="anasayfalistli">Davul</li>
                    <li class="anasayfalistli">Piyano</li>
                    <li class="anasayfalistli">Keman</li>
                </ul>
            </div> 
        </article>
    </main>
</body>
</html>
  ```
  //products.html
  ```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ürünlerimiz</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
     <!-- Header Bölümü -->
    <header>
        <!-- Anasayfa Başlık -->
        <h1 class="anabaslik">Müzik Dükkanım</h1>
    </header>
    <!-- Nav Bölümü -->
    <nav class="nav">
        <ul class="navlist">
            <li class="navlistli"><a href="index.html">Ana Sayfa</a></li>
            <li class="navlistli ml15"><a href="products.html">Ürünlerimiz</a></li>
            <li class="navlistli ml15"><a href="about-us.html">Hakkımızda</a></li>
        </ul>
    </nav>
    <!-- Ürünlerimiz İçerik -->
    <main>
        <article>
            <h2 class="urunlerimizbaslik">Ürünlerimiz</h2>
            <div class="urunlerlistediv">
                <ol class="urunlerlisteol">
                    <li><img width="300" height="300" src="img/fenderstrat.jpg" alt="Gitar"><br>Fender Masterbuilt 59 Stratocaster <strong>6000₺</strong></li>
                    <li><img width="300" height="300" src="img/gibsonlespaul.jpg" alt="Gitar"><br>Gibson Les Paul Special <strong>5250₺</strong></li>
                    <li><img width="300" height="300" src="img/davulset1.jpg" alt="Davul"><br>Mapex AR529STK Armory Akustik Davul Seti <strong>9800₺</strong></li>
                    <li><img width="300" height="300" src="img/davulset2.jpg" alt="Davul"><br>Yamaha Rydeen 20 Inch Davul Seti <strong>11500₺</strong></li>
                    <li><img width="300" height="300" src="img/keman1.jpg" alt="Keman"><br>Yamaha V5SA Keman (4/4) <strong>6000₺</strong></li>
                    <li><img width="300" height="300" src="img/keman2.jpg" alt="Keman"><br>OFFENBACH El Yapımı 4/4 Keman <strong>5000₺</strong></li>
                    <li><img width="300" height="300" src="img/piyano1.jpg" alt="Piyano"><br>Kurzweil KA130SR Dijital Piyano <strong>6800₺</strong></li>
                    <li><img width="300" height="300" src="img/piyano2.jpg" alt="Piyano"><br>Yamaha GB1 Akustik Kuyruklu Piyano (Parlak Siyah) <strong>180000₺</strong></li>
                </ol>
            </div>
        </article>
    </main>
</body>
</html>
  ```
    //style.css
```css
  /* --------------- Genel --------------- */
body{
    font-family:Arial, Helvetica, sans-serif;
}

/* --------------- Header --------------- */
.anabaslik{
    font-weight: bold;
    color: #bd1b55;
    text-align: center;
}

/* --------------- Nav --------------- */
.ml15{
    margin-left: 15px;
}
.nav{
    display: flex;
    justify-content: center;
    
}
.navlist{
    list-style: none;
    text-align: center;
    padding: 0;
    margin: 0;
}
.navlistli{
    display: inline;
}

/*--------------- Anasayfa Main --------------- */
.anasayfabaslik{
    color: #722ff8;
    text-align: center;
}
.anasayfap1{
    text-align: center;
}
.anasayfaaltbaslik{
    color: #bb921b;
    text-align: center;
}
.listdiv{
    display: flex;
    justify-content: center;
}
.anasayfalistul{
    list-style-position: inside;
    padding: 0;
    margin: 0;
}

/* --------------- Hakkımızda Main --------------- */
.hakkimizdabaslik{
    color: #722ff8;
    text-align: center;
}
.hakkimizdaaltbaslik{
    color: #bb921b;
}

/* --------------- Ürünlerimiz Main --------------- */
.urunlerimizbaslik{
    color: #722ff8;
    text-align: center;
}
.urunlerlistediv{
    display: flex;
    justify-content: center;
}
.urunlerlisteol{
    padding: 0;
    padding-left: 150px;
}
  ```
  </details>
  
## :brain: CSS Ödev-2 Google Ana Sayfasını Tasarlamak


### :question: SORU 
Google Ana Sayfasını Tasarlamak
Hepimiz her gün Google kullanıyoruz ve çok işimize yarıyor değil mi? Her gün Google'da milyonlarca arama yapılıyor ve hatta siz de bu sayfaya gelmek için Google'ı kullanmış olabilirsiniz. Peki Google'ın geçmişten günümüze nasıl geliştiğini hiç merak ettiniz mi?

Google 1996 yılında kuruldu ve ilk versiyonunu 1998 yılında yayınladı. 1998, çok uzun bir süre önce değil mi? İlk versiyonu ile şu anki versiyonu arasında büyük fark var tabii ki. Peki size Google'ın ilk versiyonunu gösterebileceğimizi söylesek ne hissederdiniz?

İnternetteki gelmiş geçmiş bütün web sitelerini görebileceğiniz Wayback Machine adında bir web arşivi bulunmakta. Google 1998 linkinden Google'ın ilk versiyonu nasılmış görebilirsiniz. Oldukça garip öyle değil mi? Garip olmasının yanında bu sizin HTML bölümündeki üçüncü ve son ödeviniz olacak. Bu sayfayı tasarlamanızı istiyoruz.

Bu sayfada şu ana kadar öğrendiğiniz her şeyi kullanabilirsiniz. Bu sizin HTML becerilerinizi oldukça iyi bir şekilde geliştirmenizi sağlayacaktır.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //index.html
```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <title>Google</title>
</head>
<body>
    <header class="header">
        <!-- Logo -->
        <nav><img src="img/google.jpg" alt="logo"></nav>
    </header>
    <section class="section-search">
        <!-- Search Area -->
        <p class="inline">Search the web using Google!</p><br>
        <input class="input-1" type="text"><br>
        <button>Google Search</button>
        <button>I'm feeling lucky</button>
    </section>
    
    <section class="section-types">
        <!-- Search Types -->
        <article class="art-1">
            <ul class="stypelist">
                <li><a href="#">Special Searches</a></li>
                <li><a href="#">Stanford Search</a></li>
                <li><a href="#">Linux Search</a></li>
            </ul>
        </article>
        
        <!-- Help And Info Area -->
        <article class="art-2">
            <ul class="helplist">
                <li><a href="#">Help!</a></li>
                <li><a href="#">About Google!</a></li>
                <li><a href="#">Company Info</a></li>
                <li><a href="#">Google! Logos</a></li>
            </ul>
        </article>

        <!-- Subscribe Area -->
        <article class="art-3">
            <p class="m-0 p-0">Get Google!<br>updates monthly:</p>
            <input placeholder="your e-mail" type="email"><br>
            <button>Subscribe</button>
            <a href="#" style="margin-left: 10px;">Archive</a>
        </article>
    </section>

    <!-- Copyright Footer -->
    <Footer class="footer">
        <p>Copyright ©1998 Google Inc.</p>
    </Footer>
</body>
</html>
```
  //style.css
  ```css
  /* --------------- General --------------- */
.inline {
    display: inline;
}

.m-0 {
    margin: 0;
}

.p-0 {
    padding: 0;
}

/* --------------- Header --------------- */
.header {
    text-align: center;
}

/* --------------- Search Area --------------- */
.section-search {
    width: 90%;
    margin: auto;
    text-align: center;
    background: #eeeeee;
}
.input-1 {
    width: 25%;
}

/* --------------- Search Types --------------- */
.section-types {
    width: 90%;
    margin: auto;
    display: flex;
    flex-direction: row;
    align-items: center;
}

.art-1 {
    background: #7ee5da;
    text-align: center;
    margin-top: 3px;
    width: 38%;
    padding: 19px;
}

.stypelist {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.art-2 {
    background: #70ccc2;
    text-align: center;
    margin-left: 3px;
    width: 15%;
    margin-top: 3px;
    padding: 10px;
}

.helplist {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.art-3 {
    background: #62b3aa;
    text-align: center;
    margin-left: 3px;
    width: 47%;
    margin-top: 3px;
    padding: 7px;
}

/* --------------- Footer --------------- */
.footer {
    text-align: center;
    margin-top: 30px;
}
```
  </details>

## :brain: CSS Ödev-3 Google Ana Sayfasını Tasarlamak


### :question: SORU 
Bir zamanlar basit ama gururlu bir Google Ana Sayfası vardı, hatırladınız mı? Yıllaar yıllar geçti ve o ana sayfa gelişti, serpildi ve bugünkü halini aldı. HTML'in son ödevinde Google'ın ilk tasarımı üzerinde çalışmıştık ve CSS bölümünde günümüzdeki halini tasarlayacağımızı söylemiştik. Evet, o gün bugündür arkadaşlar. Bu ödevde Google'ın bugünkü ana sayfasını tasarlayacağız.

Sizler için HTML yapısını ve basit CSS'i hazırladık. Sizlerden istediğimiz orijinali inceleyip detayları işlemeniz.
Google Homepage Projesi'ne buradan erişebilirsiniz.

Projeyi indirdikten ya da cloneladıktan sonra Visual Studio Code programında LiveServer eklentisi ile açmanızı öneririz.

Google Ana Sayfa için arşiv linkini kullanabilirsiniz ya da Google'ın şimdiki ana sayfasını kullanabilirsiniz.

Bu ödevi yapabilmeniz için bolca "İncele/Inspect"'ten yararlanmanız gerekecektir. Sayfadayken sayfaya sağ tıklayıp "İncele/Inspect" demeniz yeterlidir.

Fark ettiyseniz logo eski bir Google logosu. Bu logoyu günümüzde logo ile değiştirmelisiniz. Kullanmanız gereken logo assets klasöründe bulunmakta.

Üstteki alanı sağ tarafa alın ve fotoğrafı kendi fotoğrafınız ile değiştirin ve fotoğrafın kenarlarını yarıçap özelliği ile düzenleyiniz.

Arama yapılacak alanın kenarlarını yarıçap özelliği ile düzenleyiniz.

Arama simgesi gibi sesle arama simgesini de siz ekleyin. (Nasıl yapıldığını görmek için Google Ana Sayfa'dan İncele ile yazılanları inceleyiniz.)

Arama alanında yazı yazılan yerin genişliği 480px olmalı ve kenarlığı olmamalı.

Buttonları ortaya alıp üstünden ve sağından boşluklar veriniz. Button kenarları 1px kalın #f2f2f2 renginde olmalı. Yazı tipi Arial, yazı rengi #5f6368, yazı boyutu 14px olmalı. Button yüksekliği 36px olmalı.

Buttonlara aynı arama alanında olduğu gibi gölge veriniz.

Footerda arkaplan rengini #f2f2f2 yapınız ve liste noktalarını ortadan kaldırın. (Bir önceki ödevde söylediğimiz w3schools.com'un CSS tutorialını, Türkçe kaynak için Fatih Hayrioğlu'un sitesini kullanabilirsiniz.)

CSS dosyasında kullanılan bütün elementleri araştırıp ne işe yaradıklarını öğrenin. Daha sonra bunları kullanabileceğiniz projelerinizde kullanmaya özen gösterin.

Tasarımı mümkün olduğunca benzetmeniz gerekmekte. Buttonların, arama kısmının çalışmaması önemli değil.

Kod yazarken yorum satırları kullanmaya özen gösteriniz. ödevin indirilebilir içeriklerine buradan ulaşabilirsiniz.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //index.html
```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <nav class="nav">
            <div class="nav-left">
                <a class="nav-left-a" href="#">About</a>
                <a class="nav-left-a" href="#">Store</a>
            
                <div class="nav-right">
                    <div class="nav-right-in">
                        <div class="nav-right-divs mt-8"><a href="#">Gmail</a></div>
                        <div class="nav-right-divs mt-8"><a href="#">Images</a></div>
                        <div class="nav-right-divs mt-6 imghover"><a href="#"><img class="bradius" src="img/dottedlogo.png" alt=""></a></div>
                        <div class="nav-right-divs"><a href="#"><img class="bradius" src="img/profilepic.jpg" alt=""></a></div>
                    </div>
                </div>
            </div>
        </nav>
    </header>

    <!-- Main -->
    <section class="main">
        <!-- Logo -->
        <div class="img">
            <img src="img/googleAmblem.png" alt="Google">
        </div>
        <!-- Search -->
        <form class="form" action="" method="get">
            <!-- Input -->
            <div class="input-area">
                <div class="simage">
                    <img src="img/searchlogo.png" alt="">
                </div>
                <div class="inputdiv">
                    <input class="input" name="" id="">
                </div>
                <div class="inputright">
                    <div class="mimage"><img width="24" src="img/voicelogo.png" alt=""></div>
                </div>
            </div>
            <div class="buttonsdiv">
                <button class="button">Google Search</button>
                <button class="button">I'm Feeling Lucky</button>
            </div>
        </form>
    </section>
    <!-- Footer -->
    <footer class="footer">
        <div class="lside">
            <a href="#">Advertising</a>
            <a href="#">Business</a>
            <a href="#">How Search works</a>
        </div>
        <div class="rside">
            <a href="#">Privacy</a>
            <a href="#">Terms</a>
            <a href="#">Settings</a>
        </div>
    </footer>
</body>
</html>
  ```
  //style.css
  ```css
  /* General */
body{
    font-family: arial,sans-serif;
    background: #fff;
    color: #222;
}
.bradius{
    border-radius: 100%;
}
.mt-6{
    margin-top: 6px;
}
.mt-8{
    margin-top: 8px;
}
a{
    text-decoration: none;
    color: #222;
}

/* Header */
.nav {
    position: relative;
    top: 16px;
    font-size: 13px;
}
.nav-left{
    margin: -1px 0 0 2px;
    font-size: 13px;
}
.nav-left-a{
    display: inline-block;
    padding-left: 15px;
    color: #000;
    opacity: 0.75;
    text-decoration: none;
    cursor: pointer;
}
.nav-left-a:hover{
    text-decoration: underline;
}
.nav-right{
    font-size: 13px;
    color: #000;
    float: right;
    margin-right: 10px;
    margin-top: -7px;
}
.nav-right-in{
    display: flex;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
}
.nav-right-divs{
    margin-left: 20px;

}
.imghover:hover{
    opacity: 0.5;
}
.nav-right-divs>a:hover{
    text-decoration: underline;
    color: #222;
}

/* Main */
.main{
    height: 233px;
    margin-top: 89px;
    text-align: center;
}
.img{
    margin-top: 176px;
}
.form{
    height: 118px;
}
.input-area{
    width: 582px;
    margin: 0 auto;
    margin-top: 23px;
    padding-top: 6px;
    border: 1px solid #dfe1e5;
    border-radius: 24px;
    z-index: 3;
    height: 38px;
    text-align: center;
}
.input-area:hover{
    box-shadow: 1px 1px 12px -1px #ccc;
}
.simage{
    display: inline;
    float: left;
    margin-top: 5px;
    margin-left: 11px;
}
.inputdiv{
    display: inline;
}
.input{
    border: none;
    background-color: transparent;
    color: rgba(0,0,0,.87);
    outline: none;
    width: 484px;
    height: 30px;
    font-size: 16px;
    margin-top: 0px;
    line-height: 34px; 
}
.inputright{
    display: inline;
}
.mimage{
    display: inline;
    float: right;
    margin-right: 16px;
    margin-top: 4px;
    cursor: pointer;
}
.buttonsdiv{
    margin-top: 19px;
    margin-left: -13px;
}
.button{
    height: 36px;
    min-width: 54px;
    font-size: 14px;
    background-color: #f2f2f2;
    border: 1px solid #f2f2f2;
    color: #5F6368;
    border-radius: 4px;
    margin: 11px 4px;
    padding: 0 16px;
    line-height: 27px;
    text-align: center;
    cursor: pointer;
    user-select: none;
}
.button:hover{
    color: #222;
    box-shadow: 1px 1px 3px 0px #ccc;
    border: 1px solid #bbb;
}

/* Footer */
.footer{
    background: #f2f2f2;
    min-width: 980px;
    border-top: 1px solid #e4e4e4;
    color: #222;
    bottom: 0;
    left: 0;
    position: absolute;
    right: 0;
    font-size: 14px;
    line-height: 40px;
    font-size: 10pt;
}
.lside{
    display: inline;
    float: left;
}
.rside{
    display: inline;
    float: right;
    margin-right: 30px;
}
.lside>a{
    color: #5f6368;
    text-decoration: none;
    white-space: nowrap;
    padding-left: 27px;
    margin: 0 !important;
    cursor: pointer;
    font-size: 14px;
}
.rside>a{
    color: #5f6368;
    text-decoration: none;
    white-space: nowrap;
    padding-left: 27px;
    margin: 0 !important;
    cursor: pointer;
    font-size: 14px;
}
.footer a:hover{
    text-decoration: underline;
}
```
  </details>
  
 ## :brain: BOOTSTRAP Ödev-1 Bootstrap Özelliklerini Kullanarak Yaptığımız Siteyi Geliştirelim
 
 ### :question: SORU 
 
Hatırlar mısınız CSS'in ilk ödevinde boynu bükük bir site yapmıştık. Bu site CSS'in özelliklerini kullanan bir müzik aleti satış sitesiydi. Bu siteyi Bootstrap ile tekrar tasarlayacağız.

#### Sizden Beklediklerimiz
HTML kısmını önceki ödevden alabilirsiniz fakat baştan yapmanızı öneririz.
Menüyü koyu renkli olarak düzenleyin. İsterseniz arka plan rengi de verebilirsiniz.
Ana sayfaya bir jumbotron koyup içeriğinizin açıklamasını yazınız.
Arka plan rengini #E9ECEF ile değiştirin.
Ürünlerimiz sayfasında card yapısını kullanın.
Kullandığınız card yapısını grid sistemin içinde kullanın.
Ürün card boyutlarının tamamen aynı olduğuna dikkat edin.
Hakkımızda sayfasını da bir card yapısı içine alın.
Bootstrap Dökümantasyonu'nu iyi inceleyip farklı elementleri denemeye çalışın.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //about-us.html
```html
  <!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Hakkımızda</title>
  </head>
  <body style="background-color: #E9ECEF; font-family:Arial, Helvetica, sans-serif;">
    <!-- Nav Bar -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light bg-dark">
            <div class="container-fluid">
                <a class="navbar-brand text-danger" href="index.html">Müzik Dükkanım</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active text-secondary" aria-current="page" href="index.html">Ana Sayfa</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-secondary" href="products.html">Ürünlerimiz</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-secondary" href="about-us.html">Hakkımızda</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </header>

    <main class="container">
      <h1 class="mt-5 text-danger text-center">Hakkımızda</h1>
      <p>Müzik Dükkanım 2021 yılında Cengiz C. Mataracı ve Furkan Tolga Yüce tarafından kurulmuştur. Çeşitli müzik aletlerini uygun fiyatlar ile buluşturmak için kurulmuştur.</p>
      <section class="row">
        <article class="col-12">
          <div class="card mb-3" style="background-color: #E9ECEF;">
            <div class="card-body">
              <h5 class="card-title fw-bold" style="color: #bb921b;">Vizyonumuz</h5>
              <p class="card-text">İnsanlara kaliteli müzik aletleri sağlamak. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Soluta animi ea nostrum unde sapiente quas, cupiditate iste nisi vitae earum? Optio cumque eius debitis culpa recusandae. Atque neque minima soluta consequatur quos eius, eveniet vitae laborum in nihil harum corporis rerum expedita facilis perspiciatis corrupti deserunt consequuntur architecto dolorem ducimus accusantium fugit culpa asperiores ratione? Labore neque harum sed asperiores.</p>
            </div>
          </div>
        </article>
        <article class="col-12">
          <div class="card mb-3" style="background-color: #E9ECEF;">
            <div class="card-body">
              <h5 class="card-title fw-bold" style="color: #bb921b;">Misyonumuz</h5>
              <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aperiam dolore laborum veritatis facere mollitia veniam optio, qui eum tempora, maxime unde quibusdam repudiandae nobis, nihil enim praesentium ratione velit? Earum, molestiae. Officia voluptatum quae autem illum saepe aliquid enim rerum quaerat, dicta tenetur ipsum. Minima aliquid iusto dolorum hic tempora amet voluptatibus delectus, atque deserunt reprehenderit perspiciatis facilis iure id harum totam velit perferendis rem quos quia nulla adipisci molestias aut itaque. Placeat nam, reprehenderit quo voluptas in cumque sequi est magnam, mollitia ad, sit eveniet assumenda corporis molestias laborum?</p>
            </div>
          </div>
        </article>
      </section>
      <hr>
    </main>

    <!-- Optional JavaScript; choose one of the two! -->
```
    ```html
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```
  //index.html
```html
  <!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Ana Sayfa</title>
  </head>
  <body style="background-color: #E9ECEF; font-family:Arial, Helvetica, sans-serif;">
    
    <!-- Nav Bar -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light bg-dark">
            <div class="container-fluid">
              <a class="navbar-brand text-danger" href="index.html">Müzik Dükkanım</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active text-secondary" aria-current="page" href="index.html">Ana Sayfa</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-secondary" href="products.html">Ürünlerimiz</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-secondary" href="about-us.html">Hakkımızda</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </header>

    <!-- Home Main -->
    <main class="container">
        <section class="jumbotron mt-5">
            <h1 class="text-danger text-center">Merhaba!</h1>
            <p class="text-center">Müzik Dükkanım sitemize hoşgeldiniz! Bu sitede çeşitli müzik aletlerini bulabilirsiniz. Uygun fiyatlarımız ve kalite ürünlerimiz için <a href="products.html">Ürünlerimiz</a> sayfamızı ziyaret edebilirsiniz.</p>
            <hr>
            <h4 class="text-center fw-bold" style="color: #bb921b;">Sitemizde Bulunan Müzik Aletleri</h4>
            <div class="text-center">
                <ul class="" style="list-style-position: inside; padding: 0; margin: 0;">
                    <li class="">Gitar</li>
                    <li class="">Davul</li>
                    <li class="">Piyano</li>
                    <li class="">Keman</li>
                </ul>
            </div>
            <div class="text-center">
                <a class="btn btn-primary mt-2" href="about-us.html">Hakkımızda</a>
            </div>
        </section>
    </main>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
  ```
//products.html
```html
  <!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Ürünlerimiz</title>
  </head>
  <body style="background-color: #E9ECEF; font-family:Arial, Helvetica, sans-serif;">
    <!-- Nav Bar -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light bg-dark">
            <div class="container-fluid">
                <a class="navbar-brand text-danger" href="index.html">Müzik Dükkanım</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active text-secondary" aria-current="page" href="index.html">Ana Sayfa</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-secondary" href="products.html">Ürünlerimiz</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-secondary" href="about-us.html">Hakkımızda</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </header>
    <main class="container">
      <section class="row justify-content-center">
        <h1 class="text-danger text-center mt-5">Ürünlerimiz</h1>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/fenderstrat.jpg" class="card-img-top" alt="Gitar">
            <article class="card-body">
              <h5 class="card-title">Fender</h5>
              <p class="card-text">Fender Masterbuilt 59 Stratocaster</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">6.000 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/gibsonlespaul.jpg" class="card-img-top" alt="Gitar">
            <article class="card-body">
              <h5 class="card-title">Gibson</h5>
              <p class="card-text">Gibson Les Paul Special</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">5.250 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/keman1.jpg" class="card-img-top" alt="Keman">
            <article class="card-body">
              <h5 class="card-title">Yamaha</h5>
              <p class="card-text">Yamaha V5SA</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">6.000 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/keman2.jpg" class="card-img-top" alt="Keman">
            <article class="card-body">
              <h5 class="card-title">OFFENBACH</h5>
              <p class="card-text">OFFENBACH El Yapımı</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">5.000 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/davulset1.jpg" class="card-img-top" alt="Davul">
            <article class="card-body">
              <h5 class="card-title">Mapex</h5>
              <p class="card-text">Mapex AR529STK Armory</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">9.800 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/davulset2.jpg" class="card-img-top" alt="Davul">
            <article class="card-body">
              <h5 class="card-title">Yamaha</h5>
              <p class="card-text">Yamaha Rydeen 20 Inch</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">11.500 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/piyano1.jpg" class="card-img-top" alt="Piyano">
            <article class="card-body">
              <h5 class="card-title">Kurzweil</h5>
              <p class="card-text">Kurzweil KA130SR</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">6.800 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
        <div class="col-4 mb-2">
          <article class="card mx-auto" style="width: 18rem;">
            <img src="img/piyano2.jpg" class="card-img-top" alt="Piyano">
            <article class="card-body">
              <h5 class="card-title">Yamaha</h5>
              <p class="card-text">Yamaha GB1 Akustik Kuyruklu</p>
              <a href="#" class="btn btn-primary"><strong style="color: yellow;">180.000 ₺</strong>  - Satın Al</a>
            </article>
          </article>
        </div>
      </section>
    </main>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```
  </details>

