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
  
  ## :brain: CSS Ödev-2 Bootstrap ile Instagram Clone

### :question: SORU 

Sizden Beklediklerimiz
Navbar'ı yukarı sabitleyip sayfayı aşağı kaydırdığınızda hala yukarıda durmasını sağlayın. İçerik ile birleşmemesi için body'e padding veriniz.
Navbarın height'ı 54 px olmalı ve arkaplan rengi beyaz olmalı.
Navbar'daki elementlerin doğru yerde olmadığını fark ettiniz mi? Öncelikle navbar'ın başındaki logo class'ının içine 192px soldan margin verin.
Arama kısmını d-flex ile ortay alıp soldan 5 birim margin verin.
CSS dosyası içindeki ::placeholder kısmının arkaplanına assets klasörü içinde bulunan arama simgesini ekleyin. Ve resmin tekrar etmemesini sağlayın.
Clone ödevimizdeki ikonları FontAwesome sitesinden aldık. Daha detaylı bilgi için web sitesini ziyaret edin ve nasıl çalıştığını öğrenin.

Sağ üstte yer alan menü kısmına soldan 5 birim üstten 2 birim margin verin.
Sağ üstte yer alan menü kısmına sayfa sm boyutunda olunca kaybolacak şekilde display verin. Bunun için Bootstrap Display property sayfasını inceleyebilirsiniz.
İçerik alanı(ortadaki gönderilerin olduğu alan) offset 4 olmalı ve üstten 2 birim margin almalı.
Class'da belirttiğimiz middlearea içinde maksimum yükseklik 200px olmalı ve bunu important ile yazmalısınız. (important'ın ne olduğunu, ne işe yaradığını henüz bilmiyorsanız bir "Css important nedir?" şeklinde aramanızı ve ne işe yaradığını öğrenmenizi öneririz. Unutmayın parametre vermek bazen istemediğiniz durumlara yol açabilir bilinçli kullanmak gerekir.)
Bu alanın col'unun default değerini 12, diğer tüm ölçekleri ise 6 olarak ayarlayın. Yani normal boyutta 12, sayfa küçülüp büyüdükçe, boyutuyla oynadıkça 6 ölçek olacak şekilde ayarlayın. (Grid sistemin 12'lik olduğunu hatırlayın)
Hikayeler kısmında isimler nasıl resimlerin altına gelecek? (İpucu: Arama kısmında kullandığımız özellik)
İçerik kısmında üç nokta sağda olmalı.
Beğenme, yorum yapma, paylaşma kısmında border olmamalı.
Bookmark ikonunun offset'i 7 birim olmalı.
Card header ve card footer'lar beyaz renk olmalı.
Yorum paylaş metnini sağa alın.
Sağ panele verilen alan sizce yeterli mi? Değilse düzeltin.
Sağ panel için stickysidebar ve rightpanel diye iki class verdiğimizi fark etmişsiniz. Stickysidebar bu panelin sayfayı aşağı kaydırdıkça onun da gelmesini sağlıyor. Bunu sağlamak için için CSS'in position property'sini kullanabilirsiniz. Rightpanel'de de arkaplan rengi beyaz olup kenarlık olmamalı.
Tümünü gör ve takip et yazılarını sağa alınız.
Bütün sayfanın arkaplan rengini Instagram'dan alıp uygulayın.
Burada belirtmediğimiz ama gözünüze takılan bir yer olursa orayı da düzeltin. Bu ödev için bol bol Instagram sitesini inspect/incele etmeniz gerekecek.

Buradaki ana amacımız Bootstrap elementlerini kullanarak ve özellikle deneyip yanılarak doğru yöntemi bulmanız. Mükemmel olmasına gerek yok. Unutmayın efektif olması mükemmel olmasından daha önemlidir.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //index.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css"
      integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.1/css/all.css"
      integrity="sha384-vp86vTRFVJgpjF9jiIGPEEqYqlDwgyBgEF109VFjmqGmIY/Y4HV4d3Gp2irVfcrp"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="css/style.css" />
    <title>Instagram</title>
  </head>
  <body>
    <nav
      class="navbar navbar-expand-sm fixed-top navbar-light border" style="background-color: white; height: 54px;"
    >
      <div class="logo" style="margin-left: 192px;">
            <a class="navbar-brand" href="#"
              ><img
                src="https://www.instagram.com/static/images/web/mobile_nav_type_logo.png/735145cfe0a4.png"
            /></a>
            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon mr-5"></span>
            </button>
          </div>
      <div class="collapse navbar-collapse d-flex justify-content-center ml-5">
        <form class="form-inline my-2 my-lg-0 ml-5 d-none d-sm-block ">
          <input
            class="form-control mr-sm-2 empty"
            type="search"
            placeholder="Ara"
            style="font-family: Arial, FontAwesome; height: 28px; width: 216px"
            aria-label="Search"
          />
        </form>
      </div>
      <div
        class="collapse navbar-collapse d-sm-none d-md-flex ml-5 mt-2"
      >
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#"
              ><i class="fas fa-home fa-lg mr-2 d-none d-sm-block mt-1"></i>
              <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"
              ><i
                class="fab fa-facebook-messenger fa-lg mr-2 mt-1"
                style="color: black"
              ></i
            ></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"
              ><i class="far fa-compass fa-lg mr-2 mt-1" style="color: black"></i
            ></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"
              ><i class="far fa-heart fa-lg mr-2 mt-1" style="color: black"></i
            ></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://www.instagram.com/cengizcmataraci" target="_blank"
              ><img
                src="https://picsum.photos/59/59"
                class="mb-2"
                style="width: 23px; height: 23px; border-radius: 50%;"
            /></a>
          </li>
        </ul>
      </div>
    </nav>

    <div class="container middlearea offset-4 mt-2">
      <div class="row">
        <div class="col-6">
          <div class="card align-items-center">
            <div class="card-body d-flex flex-row">
              <a class="d-flex flex-column" href="https://www.instagram.com/kodluyoruz" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/60/60"
                class="storyphoto img-fluid mr-3"
              />
              <span class="storytext">kodluyoruz</span>
              </a>
              <a class="d-flex flex-column text-center" href="https://www.instagram.com/furkantolgayuce" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/50/60"
                class="storyphoto img-fluid"
              />
              <span class="storytext">furkantolga..</span>
            </a>
              <a class="d-flex flex-column text-center" href="https://www.instagram.com/elonrmuskk" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/110/60"
                class="storyphoto img-fluid"
              />
              <span class="storytext">elonrmuskk</span>
            </a>
              <a class="d-flex flex-column text-center" href="https://www.instagram.com/hakanyalcinkaya" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/70/60"
                class="storyphoto img-fluid"
              />
            <span class="storytext">hakanyalcin..</span>
            </a>
              <a class="d-flex flex-column text-center" href="https://www.instagram.com/ozgeacik" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/80/60"
                class="storyphoto img-fluid"
              />
            <span class="storytext mr-2">ozgeacik</span>
            </a>
              <a class="d-flex flex-column text-center" href="https://www.instagram.com/kablosuzkedi" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/90/60"
                class="storyphoto img-fluid"
              />
            <span class="storytext">kablosuzkedi</span>
            </a>
              <a class="d-flex flex-column text-center" href="https://www.instagram.com/gulcanyayla" style="text-decoration: none;" target="_blank">
              <img
                src="https://picsum.photos/100/60"
                class="storyphoto img-fluid"
              />
                <span class="storytext">gulcanyayla</span>
            </a>
            </div>
          </div>
          <div class="card mt-2">
            <div class="card-header" style="background-color: white;">
              <img
                src="https://picsum.photos/59/59"
                class="mr-2"
                style="width: 35px; height: 35px; border-radius: 50%"
              />
              <span class="postuserfont"><strong><a href="https://www.instagram.com/cengizcmataraci" target="_blank" style="color: black;">cengizcmataraci</a></strong></span>
              <span class="mt-2"
                ><strong><i class="fas fa-ellipsis-h"></i></strong
              ></span>
            </div>
            <img
              src="https://blog.biletbayi.com/wp-content/uploads/2019/12/rize.jpg"
              class="card-img-top"
              alt="..."
            />
            <ul
              class="list-group list-group-horizontal mt-1 border-0"
              style="list-style-type: none;"
            >
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-heart fa-lg"
                    style="color: black; position: relative; font-size: 23px"
                  ></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-comment fa-lg"
                    style="
                      color: black;
                      position: relative;
                      font-size: 23px;
                      margin-left: -11px;
                    "
                  ></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-paper-plane fa-lg"
                    style="
                      color: black;
                      position: relative;
                      font-size: 23px;
                      margin-left: -11px;
                    "
                  ></i
                ></a>
              </li>
              <span class="offset-7">
                <li class="nav-item ml-4">
                  <a class="nav-link ml-2" href="#"
                    ><i
                      class="far fa-bookmark fa-lg"
                      style="color: black; position: relative; font-size: 23px"
                    ></i
                  ></a>
                </li>
              </span>
            </ul>
            <span>
              <img
                src="https://picsum.photos/53/60"
                class="mb-1 ml-3"
                style="width: 23px; height: 23px; border-radius: 50%"
              />
              <span class="postuserfont"
                ><strong>furkantolgayuce</strong> ve
                <strong>42 diğer kişi</strong> beğendi</span
              >
            </span>
            <div class="card-body" style="margin-top: -15px">
              <p class="card-text postuserfont">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >cengizcmataraci</strong
                >Burası Rize! Harika bir cennet!
              </p>
              <a href="#" style="text-decoration: none"
                ><p
                  class="card-text postuserfont"
                  style="
                    margin-left: -4px;
                    margin-top: -14px;
                    color: rgb(139, 133, 133);
                  "
                >
                  15 yorumun tümünü gör
                </p></a
              >
              <p class="card-text postuserfont">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >furkantolgayuce</strong
                >Abi çok güzelmiş yaa! Bir gün götürürsün artık bizi de:)
              </p>
              <p class="card-text postuserfont" style="margin-top: -15px">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >elonrmuskk</strong
                >That's wonderful view bro! I always want to travel Rize...
              </p>
              <p
                class="card-text"
                style="
                  margin-top: -10px;
                  margin-left: -4px;
                  font-size: 12px;
                  color: rgb(139, 133, 133);
                "
              >
                10 SAAT ÖNCE
              </p>
            </div>
            <div
              class="card-footer"
              style="
                background-color: white;
                color: rgb(139, 133, 133);
                font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
                  Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
                  'Helvetica Neue', sans-serif;
                font-size: 14px;
              "
            >
              <span style="margin-left: -4px">Yorum Ekle...</span
              ><span class="offset-9" style="color: #0095f6; opacity: 50%"
                ><strong>Paylaş</strong></span
              >
            </div>
          </div>
          <div class="card mt-2">
            <div class="card-header" style="background-color: white;">
              <img
                src="https://picsum.photos/60/60"
                class="mr-2"
                style="width: 35px; height: 35px; border-radius: 50%"
              />
              <span class="postuserfont"><strong>kodluyoruz</strong></span>
              <span class="mt-2"
                ><strong><i class="fas fa-ellipsis-h"></i></strong
              ></span>
            </div>
            <img
              src="https://pbs.twimg.com/media/Erx2B2bXAAEy7gO.jpg"
              class="card-img-top"
              alt="..."
            />
            <ul
              class="list-group list-group-horizontal mt-1 border-0"
              style="list-style-type: none;"
            >
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-heart fa-lg"
                    style="color: black; position: relative; font-size: 23px"
                  ></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-comment fa-lg"
                    style="
                      color: black;
                      position: relative;
                      font-size: 23px;
                      margin-left: -11px;
                    "
                  ></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-paper-plane fa-lg"
                    style="
                      color: black;
                      position: relative;
                      font-size: 23px;
                      margin-left: -11px;
                    "
                  ></i
                ></a>
              </li>
              <span class="offset-7">
                <li class="nav-item ml-4">
                  <a class="nav-link ml-2" href="#"
                    ><i
                      class="far fa-bookmark fa-lg"
                      style="color: black; position: relative; font-size: 23px"
                    ></i
                  ></a>
                </li>
              </span>
            </ul>
            <span>
              <img
                src="https://picsum.photos/111/60"
                class="mb-1 ml-3"
                style="width: 23px; height: 23px; border-radius: 50%"
              />
              <span class="postuserfont"
                ><strong>cengizcmataraci</strong> ve
                <strong>670 diğer kişi</strong> beğendi</span
              >
            </span>
            <div class="card-body" style="margin-top: -15px">
              <p class="card-text postuserfont">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >kodluyoruz</strong
                >Barış Balta ile AWS Quick Start Etkinliği #1 30 Ocak Cumartesi günü saat 10:00-15:30'da!
              </p>
              <a href="#" style="text-decoration: none"
                ><p
                  class="card-text postuserfont"
                  style="
                    margin-left: -4px;
                    margin-top: -14px;
                    color: rgb(139, 133, 133);
                  "
                >
                  60 yorumun tümünü gör
                </p></a
              >
              <p class="card-text postuserfont">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >cengizcmataraci</strong
                >Harika! Kesinlikle katılacağım! :)
              </p>
              <p class="card-text postuserfont" style="margin-top: -15px">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >kablosuzbeyin</strong
                >Topluluk olarak heyecanlıyız!
              </p>
              <p
                class="card-text"
                style="
                  margin-top: -10px;
                  margin-left: -4px;
                  font-size: 12px;
                  color: rgb(139, 133, 133);
                "
              >
                10 SAAT ÖNCE
              </p>
            </div>
            <div
              class="card-footer"
              style="
                background-color: white;
                color: rgb(139, 133, 133);
                font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
                  Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
                  'Helvetica Neue', sans-serif;
                font-size: 14px;
              "
            >
              <span style="margin-left: -4px">Yorum Ekle...</span
              ><span class="offset-9" style="color: #0095f6; opacity: 50%"
                ><strong>Paylaş</strong></span
              >
            </div>
          </div>
          <div class="card mb-2 mt-2">
            <div class="card-header" style="background-color: white;">
              <img
                src="https://picsum.photos/110/60"
                class="mr-2"
                style="width: 35px; height: 35px; border-radius: 50%"
              />
              <span class="postuserfont"><strong>elonrmuskk</strong></span>
              <span class="mt-2"
                ><strong><i class="fas fa-ellipsis-h"></i></strong
              ></span>
            </div>
            <img
              src="https://i.insider.com/5f1b201a5af6cc7e1b741330?width=1136&format=jpeg"
              class="card-img-top"
              alt="..."
            />
            <ul
              class="list-group list-group-horizontal mt-1 border-0"
              style="list-style-type: none; border: 0"
            >
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-heart fa-lg"
                    style="color: black; position: relative; font-size: 23px"
                  ></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-comment fa-lg"
                    style="
                      color: black;
                      position: relative;
                      font-size: 23px;
                      margin-left: -11px;
                    "
                  ></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"
                  ><i
                    class="far fa-paper-plane fa-lg"
                    style="
                      color: black;
                      position: relative;
                      font-size: 23px;
                      margin-left: -11px;
                    "
                  ></i
                ></a>
              </li>
              <span class="offset-7">
                <li class="nav-item ml-4">
                  <a class="nav-link ml-2" href="#"
                    ><i
                      class="far fa-bookmark fa-lg"
                      style="color: black; position: relative; font-size: 23px"
                    ></i
                  ></a>
                </li>
              </span>
            </ul>
            <span>
              <img
                src="https://picsum.photos/114/60"
                class="mb-1 ml-3"
                style="width: 23px; height: 23px; border-radius: 50%"
              />
              <span class="postuserfont"
                ><strong>cengizcmataraci</strong> ve
                <strong>900.182 diğer kişi</strong> beğendi</span
              >
            </span>
            <div class="card-body" style="margin-top: -15px">
              <p class="card-text postuserfont">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >elonrmussk</strong
                >That's just beautiful!
              </p>
              <a href="#" style="text-decoration: none"
                ><p
                  class="card-text postuserfont"
                  style="
                    margin-left: -4px;
                    margin-top: -14px;
                    color: rgb(139, 133, 133);
                  "
                >
                  1500 yorumun tümünü gör
                </p></a
              >
              <p class="card-text postuserfont">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >cengizcmataraci</strong
                >Yeah! Here you go!
              </p>
              <p class="card-text postuserfont" style="margin-top: -15px">
                <strong style="margin-left: -4px; margin-right: 5px"
                  >spacex</strong
                >When are we moving?
              </p>
              <p
                class="card-text"
                style="
                  margin-top: -10px;
                  margin-left: -4px;
                  font-size: 12px;
                  color: rgb(139, 133, 133);
                "
              >
                10 SAAT ÖNCE
              </p>
            </div>
            <div
              class="card-footer"
              style="
                background-color: white;
                color: rgb(139, 133, 133);
                font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
                  Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
                  'Helvetica Neue', sans-serif;
                font-size: 14px;
              "
            >
              <span style="margin-left: -4px">Yorum Ekle...</span
              ><span class="offset-9" style="color: #0095f6; opacity: 50%"
                ><strong>Paylaş</strong></span
              >
            </div>
          </div>
        </div>
        <div class="col-6">
          <div
            class="card col-xs-12 rightpanel"
            id="sticky-sidebar"
            style="width: 18rem"
          >
            <div class="card-body d-flex" >
              <div>
                <a class="nav-link" href="#"
                  >
                  <span>
                  <img
                    src="https://picsum.photos/59/59"
                    class=""
                    style="
                      width: 60px;
                      height: 60px;
                      border-radius: 50%;
                      border: 2px solid rgb(238, 39, 82);
                      margin-left: -15px;
                    "
                  /><span
                    class=""
                    style="
                      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
                        Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
                        'Helvetica Neue', sans-serif;
                      font-size: 15px;
                      color: black;
                      margin-left: 20px;
                    "
                    ><strong>cengizcmataraci</strong>
                    </span>
                  </span>
                </a>
                <div class="mt-2">
                  <span
                    class="mt-5"
                    style="
                      font-family: 'Segoe UI', Tahoma, Geneva, Verdana,
                        sans-serif;
                      font-size: 15px;
                      color: gray;
                    "
                    >Senin İçin Öneriler</span
                  >
                  <span
                    class="postuserfont mt-1"
                    style="font-size: 12px; margin-left: 52px;"
                    ><strong>Tümünü Gör</strong></span
                  >
                </div>
                <div class="mt-2 ml-2">
                  <div>
                    <span
                      ><img
                        src="https://picsum.photos/58/59"
                        style="width: 30px; height: 30px; border-radius: 50%"
                      />
                    </span>
                    <a href="https://www.instagram.com/kablosuzbeyin" target="_blank">
                    <span class="postuserfont ml-2 mt-1"
                      ><strong>kablosuzbeyin</strong></span
                    >
                    <span
                      class="postuserfont offset-2"
                      style="font-size: 13px; color: #0095f6; margin-top: 5px; margin-left: 44px;"
                      ><strong>Takip Et</strong></span
                    >
                    </a>
                  </div>
                  <div class="mt-3">
                    <span
                      ><img
                        src="https://picsum.photos/57/59"
                        style="width: 30px; height: 30px; border-radius: 50%"
                      />
                    </span>
                    <a href="https://www.instagram.com/codecraftcom" target="_blank">
                    <span class="postuserfont ml-2 mt-1"
                      ><strong>codecraftcom </strong></span
                    >
                    <span
                      class="postuserfont"
                      style="font-size: 13px; color: #0095f6; margin-top: 5px; margin-left: 48px;"
                      ><strong>Takip Et</strong></span
                    >
                    </a>
                  </div>
                  <div class="mt-3">
                    <span
                      ><img
                        src="https://picsum.photos/56/59"
                        style="width: 30px; height: 30px; border-radius: 50%"
                      />
                    </span>
                    <a href="https://www.instagram.com/navlungotr" target="_blank">
                    <span class="postuserfont ml-2 mt-1"
                      ><strong>navlungotr</strong></span
                    >
                    <span
                      class="postuserfont"
                      style="font-size: 13px; color: #0095f6; margin-top: 5px; margin-left: 67px;"
                      ><strong>Takip Et</strong></span
                    >
                    </a>
                  </div>
                  <div class="mt-3">
                    <span
                      ><img
                        src="https://picsum.photos/55/59"
                        style="width: 30px; height: 30px; border-radius: 50%"
                      />
                    </span>
                    <a href="https://www.instagram.com/podfreshco" target="_blank">
                    <span class="postuserfont ml-2 mt-1"
                      ><strong>podfreshco</strong></span
                    >
                    <span
                      class="postuserfont"
                      style="font-size: 13px; color: #0095f6; margin-top: 5px; margin-left: 65px;"
                      ><strong>Takip Et</strong></span
                    >
                  </div>
                  <div class="mt-3">
                    <span
                      ><img
                        src="https://picsum.photos/54/59"
                        style="width: 30px; height: 30px; border-radius: 50%"
                      />
                    </span>
                    <a href="https://www.instagram.com/kodluyoruz_junior" target="_blank">
                    <span class="postuserfont ml-2 mt-1;"
                      ><strong>Kodluyoruz Junior</strong></span
                    >
                    <span
                      class="postuserfont"
                      style="font-size: 13px; color: #0095f6; margin-top: 5px; margin-left: 16px;"
                      ><strong>Takip Et</strong></span
                    >
                    </a>
                  </div>
                </div>
                <div class="ml-2 mt-2" style="color: lightgray; font-size: 11px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">
                  <span><a href="https://about.instagram.com/" target="_blank" class="rightpanellinks">Hakkında</a> <a href="https://help.instagram.com/" target="_blank" class="rightpanellinks">Yardım</a> <a href="https://about.instagram.com/blog/" class="rightpanellinks">Basın</a> <a href="https://www.instagram.com/developer/" class="rightpanellinks">API</a> <a href="https://www.instagram.com/about/jobs/" class="rightpanellinks">İş Fırsatları</a> <a href="https://www.instagram.com/legal/privacy/" class="rightpanellinks">Gizlilik</a></span>
                    <span><a href="https://www.instagram.com/legal/terms/" class="rightpanellinks">Koşullar</a> <a href="https://www.instagram.com/explore/locations/" class="rightpanellinks">Konumlar</a> <a href="https://www.instagram.com/directory/profiles/" class="rightpanellinks">Başlıca Hesaplar</a> <a href="https://www.instagram.com/directory/hashtags/" class="rightpanellinks">Konu Etiketleri</a> Dil</span>
                    <p></p>
                  <p style="font-size: 12px;">© 2021 INSTAGRAM FROM KODLUYORUZ</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
```
//style.css
```css
  body{
  padding-top: 54px;
  background-color: #FAFAFA;
}

::placeholder{
  text-align: center;
  font-size: 14px;
  color: gray;
  background-image: url(../assets/search-solid.svg);
  background-repeat: no-repeat;
  background-position: 40%;
  background-size: 6%;
}

.middlearea{
  max-height: 200px !important;
}

input.empty {
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    text-decoration: inherit;
    background-color: #FAFAFA;
}

.postuserfont {
  font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 15px;
  color: black;
}


.storyphoto {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  border: 2px solid rgb(238, 39, 82);
  margin-right: 7px;
}

.storytext {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 12px;
  color: black;
}

.rightpanellinks {
  text-decoration: none;
  color: lightgrey;
}

.rightpanellinks:hover {
  text-decoration: none;
  color: lightgrey;
}

.rightpanel{
  background-color: white;
  border: none;
  position: sticky;
  top: 65px;
}
  ```
  </details>
  
  ## :brain: BOOTSTRAP Ödev-3  Bootstrap Linkedin Clone


### :question: SORU 

Günümüzde iş hayatının Facebook'u, biznısın göbeği olan Linkedin çok sık kullanılmakta. Eğer bir Linkedin hesabınız yoksa hemen oluşturmanızı öneririz. Network bizim mesleğimizde ekstra daha çok önemli. Bu güzel sitenin muhteşem bir cloneunu Kodluyoruz mühendislerimiz uzun uğraşlar sonucu yapmayı başardı. Karşınızda Koyun Dolly değil Bootstrap Linkedin!

linkedin

Yine bir vicdansızlık yaparak size temel olarak vereceğimiz projeyi şuna dönüştürdük.

garibanlinkedin

### Temel dosyalara şuradan ulaşabilirsiniz.

Navbar yukarıya sabitlenmemiş durumda ve kenarlığı yok. Bunları düzeltiniz.
Logoya soldan boşluk ayarlayınız.
Arama alanına sağdan boşluk bırakınız ve placeholder'ini düzeltiniz.
Arama alanı ile menü arasındaki boşluğu ayarlayınız.
Menülerdeki yazıları ve ikonları ortalayın.
Ben kategorisini diğer kategori isimleri gibi düzenleyiniz ve profil fotoğrafını düzeltiniz.
Navbar'da bir değişiklik görüyor musunuz? Navbar'ın yüzüne ne olmuş yahu?
Temel dosyalara şuradan ulaşabilirsiniz.

Navbar yukarıya sabitlenmemiş durumda ve kenarlığı yok. Bunları düzeltiniz.
Logoya soldan boşluk ayarlayınız.
Arama alanına sağdan boşluk bırakınız ve placeholder'ini düzeltiniz.
Arama alanı ile menü arasındaki boşluğu ayarlayınız.
Menülerdeki yazıları ve ikonları ortalayın.
Ben kategorisini diğer kategori isimleri gibi düzenleyiniz ve profil fotoğrafını düzeltiniz.
Navbar'da bir değişiklik görüyor musunuz? Navbar'ın yüzüne ne olmuş yahu?
Biz de onu soruyoruz işte ne olmuş?

Navbar'ı yukarı sabitleyince fark etmişsinizdir ki içerik biraz yukarıda kalıyor. O yüzden yukarıdan biraz boşluk bırakın.
İçerik biraz geniş kalmış sanki, toplamak için ne kullanabiliriz? İpucu: Layout
Responsive yapı için sol panele 2 birim, orta panele 6 birim, sağ panele de 3 birim veriniz. Bütün boyutlarda aynı ölçü geçerli olsun.
Profil fotoğrafını ortalayın, kenarlığını yuvarlak yapın ve 2 birim beyaz kenarlık verin.
Yazıları eski haline getiriniz.
Bu alanda gözünüze çarpan kısımları kendinize göre düzenleyiniz.
Sayfa bildirimi sayısını sağa alınız.
En Yeni bölümüne sticky pozisyon verin ve overflowunu görünür yapın. Yukarıdan 4rem mesafe verin.
Gönderi başlatın placeholderını düzeltiniz.
Butonlara Bootstrap'ta bulunan düzenlemeyi yapınız.
Fotoğraf'a #70B5F9, Video'ya #7FC15E, Etkinlik'e #E7A33E, Yazı Yaz'a #F5987E renklerini uygulayın. İpucu: fill
Posttaki kullanıcı adını üste, meslek title'sını ortaya, post paylaşım süresini aşağı sabitleyiniz. İpucu: align
inline-css şeklinde yazılan CSS'leri düzenli hale getiriniz.
Beğenme, kalp ve alkışa margin veriniz.
Butonlara bootstrap düzenlemesi yapınız.
Sağ panelde logoların yazıları yanlarında olması lazım. Div yerine ne kullanmak gerekiyor?
Bugünün en çok izlenen eğitimleri bölümünün genişliğini üstteki gibi ayarlayınız.
Sağ panelde en alttaki bölüme sticky pozisyon verin ve overflowunu görünür yapın. Yukarıdan 4rem mesafe verin.
Bu bölümdeki linkler yan yana olmalı.
Mesajlaşmanın genişliği 300px olmalı, arkaplanı beyaz olmalı.
İçeriğinde çok şey var diye paniğe kapılmayın, sırayla gittiğinizde her şeyin çok seri şekilde geleceğine emin olabilirsiniz.

  ### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

  //index.html
```html
  <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Linkedin</title>
    <link rel="stylesheet" href="css/style.css" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css"
      integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.1/css/all.css"
      integrity="sha384-vp86vTRFVJgpjF9jiIGPEEqYqlDwgyBgEF109VFjmqGmIY/Y4HV4d3Gp2irVfcrp"
      crossorigin="anonymous"
    />
  </head>
  <body class="body">
    <!-- navbar -->
    <nav class="navbar navbar-expand navbarbg border-bottom text-center fixed-top p-0 m-0">
      <div class="container-fluid">
        <div class="row mx-auto align-items-center" style="padding-left: 50px;">
          <a class="navbar-brand p-0 m-0 mr-2" href="#"
          ><i
            class="fab fa-linkedin fa-lg"
            style="color: #0a66c2; font-size: 2.4rem;"
          ></i
        ></a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        ></button>
        <form class="form-inline">
          <input
            class="form-control searche"
            type="search"
            placeholder="Arama Yap"
            aria-label="Search"
            style="background-color: #EEF3F8; 
            width: 280px; 
            height: 34px; 
            border: none;
            font-weight: 400;
            font-size: 14px;"
          />
        </form>
        <div class="collapse navbar-collapse" style="margin-left: 150px;">
          <ul class="navbar-nav mr-auto ml-4">
            <li class="nav-item active mr-3 my-auto">
              <a class="nav-link" href="#"
                ><i class="fas fa-home fa-lg" style="color: #5F6163;">
                  <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">Ana Sayfa</div></i
                >
              </a>
            </li>
            <li class="nav-item active mr-4 my-auto">
              <a class="nav-link" href="#"
                ><i class="fas fa-user-friends fa-lg" style="color: #5F6163;">
                  <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">Ağım</div></i
                >
              </a>
            </li>
            <li class="nav-item active mr-2 my-auto">
              <a class="nav-link" href="#"
                ><i class="fas fa-briefcase fa-lg" style="color: #5F6163;">
                  <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">İş İlanları</div></i
                >
              </a>
            </li>
            <li class="nav-item active mr-1 my-auto">
              <a class="nav-link" href="#"
                ><i class="fas fa-comment-dots fa-lg" style="color: #5F6163;">
                  <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">Mesajlaşma</div></i
                >
              </a>
            </li>
            <li class="nav-item active mr-1 my-auto">
              <a class="nav-link" href="#"
                ><i class="fas fa-bell fa-lg" style="color: #5F6163;">
                  <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">Bildirimler</div></i
                >
              </a>
            </li>
            <li class="nav-item dropdown mr-3 ml-3 my-auto">
              <a
                class="nav-link mt-1"
                href="#"
                id="navbarDropdownMenuLink"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                <img
                  class="rounded-circle"
                  src="https://picsum.photos/id/254/25/25"
                  style="
                    width: 25px;
                    height: 25px;
                  "
                />
                <div
                  class="menutext m-0" style="color: #5F6163; font-size: 14px; font-weight: 400;"
                >
                  Ben
                </div>
              </a>
            </li>
            <li class="nav-item active border-left my-auto">
              <a class="nav-link ml-4 mr-2" href="#"
                ><i class="fas fa-th fa-lg" style="color: #5F6163;"> <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">İş</div></i>
              </a>
            </li>
            <li class="nav-item active my-auto">
              <a class="nav-link" href="#"
                ><i class="fas fa-chalkboard fa-lg" style="color: #5F6163;">
                  <div class="menutext mt-2" style="color: #5F6163; font-size: 14px; font-weight: 400;">İş İlanı Yayınla</div></i
                >
              </a>
            </li>
          </ul>
        </div>
        </div>
      </div>
      
      
    </nav>

    <div class="container" style="margin-top: 100px;">
      <div class="row">
        <!-- sol panel -->
        <div class="col-3">
          <!-- sol panel -->
          <div class="card text-center">
            <div
              class="card-header"
              style="
                background-image: url(https://picsum.photos/id/29/260/53);
                height: 53px;
              "
            >
              <img
                src="https://picsum.photos/id/77/70/70"
                class="rounded-circle"
                style="
                  width: 70px;
                  height: 70px;
                  border: 3px solid white;
                "
              />
            </div>
            <div class="card-body mt-3">
              <p class="card-title header mb-0">
                <a href="https://www.linkedin.com/in/cengizcmataraci/" target="_blank" style="color: #212529;">Toygar Egemen</a>
              </p>
              <div
                style="
                  margin-bottom: 10px;
                  color: #5f5f5f;
                "
              ><small>Software Developer at Navlungo - Dijital Lojistik Platformu</small>
                
              </div>
              <hr />
              <div class="card-text text-left">
                <div>
                  <span class="view">Profilinizi kimler görüntüledi </span
                  ><span class="float-right view mt-1" style="color: #0a66c2"
                    >447</span
                  >
                </div>
                <div>
                  <span class="view">Yayınınız için görüntüleme </span
                  ><span class="float-right view mt-1" style="color: #0a66c2"
                    >150</span
                  >
                </div>
              </div>
            </div>
            <div class="card-footer text-left bg-white">
              <i class="fas fa-bookmark"></i
              ><span class="mb-4 ml-2" style="font-weight: bold; font-size: 12px;"
                >Ögelerim</span
              >
            </div>
          </div>
          <div class="card mt-2">
            <div
              class="card-header bg-white border-0"
              style="margin-bottom: -22px; font-size: 18px"
            >
              Sayfalarım
            </div>
            <div class="card-body">
              <div class="card-title">
                <img
                  src="https://picsum.photos/id/48/32/32"
                  style="width: 32px; height: 32px; padding-top: 5px;"
                />
                <div
                  style="
                    font-size: 15px;
                    font-weight: bold;
                    margin-top: -35px;
                    margin-left: 37px;
                  "
                >
                  Kablosuz Beyin
                </div>
                <div
                  class=""
                  style="
                    font-size: 13px;
                    font-weight: bold;
                    color: gray;
                    margin-left: 38px;
                  "
                >
                  Sayfa Bildirimleri
                  <span class="ml-5" style="color: #0a66c2">10</span>
                </div>
              </div>
            </div>
          </div>
          <div
            class="card mt-2" style="position: sticky; top: 4rem;"
          >
            <div
              class="card-header bg-white border-0 pb-0"
              style="font-size: 12px;"
            >
              En Yeni
            </div>
            <div class="card-body pt-2">
              <div class="card-title">
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >kodluyoruz</span
                  >
                </div>
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >front-end</span
                  >
                </div>
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >html</span
                  >
                </div>
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >css</span
                  >
                </div>
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >bootstrap</span
                  >
                </div>
                <div class="mt-3 categories">Gruplar</div>
                <span class="mt-2 categories">Etkinlikler</span>
                <span
                  class="float-right mb-5"
                  style="font-size: 23px; color: #5f5f5f"
                  >+</span
                >
                <div class="mt-3 mb-1 categories">Takip edilen hashtagler</div>
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >kodluyoruz</span
                  >
                </div>
                <div>
                  <i
                    class="fas fa-hashtag"
                    style="font-size: 13px; font-weight: bold"
                  ></i
                  ><span
                    class="ml-2 font-weight-bold"
                    style="font-size: 13px; color: #5f5f5f"
                    >front-end</span
                  >
                </div>
              </div>
            </div>
            <div
              class="card-footer bg-white"
            >
              Daha fazla keşfet
            </div>
          </div>
        </div>

        <!-- orta panel -->
        <div class="col-6">
          <div class="card text-center">
            <div class="card-body">
              <input
                type="text"
                class="form-control content"
                placeholder="Bir gönderi başlat"
              />
              <span
                ><button class="mediatext border-0 mt-3 mr-3" style="height: 35px;">
                  <svg style="fill: #70B5F9;" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" width="24" height="24" focusable="false">
  <path d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm1 13a1 1 0 01-.29.71L16 14l-2 2-6-6-4 4V7a1 1 0 011-1h14a1 1 0 011 1zm-2-7a2 2 0 11-2-2 2 2 0 012 2z"></path>
</svg><span class="ml-1 mediatext">Fotoğraf</span>
                </button></span
              >
              <span
                ><button class="mediatext border-0 mt-3 mr-3" style="height: 35px;">
                  <svg style="fill: #7FC15E;" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" width="24" height="24" focusable="false">
  <path d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm-9 12V8l6 4z"></path>
</svg><span class="ml-1 mediatext">Video</span>
                </button></span
              >
              <span
                ><button class="mediatext border-0 mt-3 mr-3" style="height: 35px;">
<svg style="fill: #E7A33E;" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" width="24" height="24" focusable="false">
  <path d="M3 3v15a3 3 0 003 3h12a3 3 0 003-3V3zm13 1.75A1.25 1.25 0 1114.75 6 1.25 1.25 0 0116 4.75zm-8 0A1.25 1.25 0 116.75 6 1.25 1.25 0 018 4.75zM19 18a1 1 0 01-1 1H6a1 1 0 01-1-1V9h14zm-5.9-3a1 1 0 00-1-1H12a3.12 3.12 0 00-1 .2l-1-.2v-3h3.9v1H11v1.15a3.7 3.7 0 011.05-.15 1.89 1.89 0 012 1.78V15a1.92 1.92 0 01-1.84 2H12a1.88 1.88 0 01-2-1.75 1 1 0 010-.25h1a.89.89 0 001 1h.1a.94.94 0 001-.88z"></path>
</svg><span class="ml-1 mediatext">Etkinlik</span>
                </button></span
              >
              <span
                ><button class="mediatext border-0 mt-3 mr-3" style="height: 35px;">
<svg style="fill: #F5987E;" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" data-supported-dps="24x24" fill="" width="24" height="24" focusable="false">
  <path d="M21 3v2H3V3zm-6 6h6V7h-6zm0 4h6v-2h-6zm0 4h6v-2h-6zM3 21h18v-2H3zM13 7H3v10h10z"></path>
</svg><span class="ml-1 mediatext">Yazı yaz</span>
                </button></span
              >
            </div>
          </div>
          <div>
            <hr />
          </div>
          <div class="card">
            <div class="card-header border-0 bg-white">
              <span>
              <img src="https://picsum.photos/id/4/200/300" class="postphoto float-left">
              <span class="posttext ml-2"><a href="https://www.linkedin.com/in/malan/" target="_blank" style="color: #212529;">David J. Malan</a></span>
              <span class="float-right">
                <i class="fas fa-ellipsis-h fa-md m-0"></i>
              </span>
              <div style="line-height: 4px;">  
                <span class="ml-2 mt-0" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;">I teach CS50 <br> </span>
                <span class="ml-2" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;">25a  <i class="fas fa-globe-americas fa-sm"></i></span>
              </div>
            </div>
            <div>
              <p class="card-text ml-3" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 15px; color: black;">
                They have done great things! Tebrikler Kodluyoruz!
              </p>
              <div>
              <img
                src="https://pbs.twimg.com/media/Em2_xBbXUAEVDx1.jpg"
                class="card-img-top mb-1"
                alt="..."
              />
              </div>
              <span class="ml-3"><img src="https://static-exp1.licdn.com/sc/h/d310t2g24pvdy4pt1jkedo4yb" alt=""></span>
              <span class=""><img src="https://static-exp1.licdn.com/sc/h/5thsbmikm6a8uov24ygwd914f" alt=""></span>
              <span class="" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;"><img src="https://static-exp1.licdn.com/sc/h/7fx9nkd7mx8avdpqm5hqcbi97" alt="">  958</span>
              <div class="card-footer bg-white mt-1">
                <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="far fa-thumbs-up fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Beğen</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="far fa-comment fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Yorum Yap</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="fas fa-share fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Paylaş</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="fas fa-paper-plane fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Gönder</span></i
                  >
                </button></span
              >
              </div>
            </div>
          </div>
          <div class="card mt-2">
            <div class="card-header border-0 bg-white">
              <span>
              <img src="https://picsum.photos/id/5/200/300" class="postphoto float-left">
              <span class="posttext ml-2"><a href="https://www.linkedin.com/in/malan/" target="_blank" style="color: #212529;">Ozan Halis İLTER</a></span>
              <span class="float-right">
                <i class="fas fa-ellipsis-h fa-md m-0"></i>
              </span>
              <div style="line-height: 4px;">  
                <span class="ml-2 mt-0" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;">Team Leader at YetGen | CodeCraft | Kablosuz Beyin | IEEE MEF...<br> </span>
                <span class="ml-2" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;">1s  <i class="fas fa-globe-americas fa-sm"></i></span>
              </div>
            </div>
            <div>
              <p class="card-text ml-3" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 15px; color: black;">
                Erhan Erkut hocamız ile birlikte YetGen'de harika şeyler yapmak için geliyoruz!
              </p>
              <div>
              <img
                src="https://miro.medium.com/max/1080/1*gdDWFSvHDt57DS2zsh_0Bg.png"
                class="card-img-top mb-1"
                alt="..."
              />
              </div>
              <span class="ml-3"><img src="https://static-exp1.licdn.com/sc/h/d310t2g24pvdy4pt1jkedo4yb" alt=""></span>
              <span class=""><img src="https://static-exp1.licdn.com/sc/h/5thsbmikm6a8uov24ygwd914f" alt=""></span>
              <span class="" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;"><img src="https://static-exp1.licdn.com/sc/h/7fx9nkd7mx8avdpqm5hqcbi97" alt="">  210</span>
              <div class="card-footer bg-white mt-1">
                <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="far fa-thumbs-up fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Beğen</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="far fa-comment fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Yorum Yap</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="fas fa-share fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Paylaş</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="fas fa-paper-plane fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Gönder</span></i
                  >
                </button></span
              >
              </div>
            </div>
          </div>
          <div class="card mt-2">
            <div class="card-header border-0 bg-white">
              <span>
              <img src="https://picsum.photos/id/29/200/300" class="postphoto float-left">
              <span class="posttext ml-2"><a href="https://www.linkedin.com/in/malan/" target="_blank" style="color: #212529;">Ramazan Sancar</a></span>
              <span class="float-right">
                <i class="fas fa-ellipsis-h fa-md m-0"></i>
              </span>
              <div style="line-height: 4px;">  
                <span class="ml-2 mt-0" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;">Co-Founder at Kablosuz Beyin | Intern & Community Lead at Kod...<br> </span>
                <span class="ml-2" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;">25a  <i class="fas fa-globe-americas fa-sm"></i></span>
              </div>
            </div>
            <div>
              <p class="card-text ml-3" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 15px; color: black;">
                Cat Özel Harekat'a katılmak isteyenleri şöyle alalım..
              </p>
              <div>
              <img
                src="https://picsum.photos/id/23/538/319"
                class="card-img-top mb-1"
                alt="..."
              />
              </div>
              <span class="ml-3"><img src="https://static-exp1.licdn.com/sc/h/d310t2g24pvdy4pt1jkedo4yb" alt=""></span>
              <span class=""><img src="https://static-exp1.licdn.com/sc/h/5thsbmikm6a8uov24ygwd914f" alt=""></span>
              <span class="" style="font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 13px; color: #474747;"><img src="https://static-exp1.licdn.com/sc/h/7fx9nkd7mx8avdpqm5hqcbi97" alt="">  224</span>
              <div class="card-footer bg-white mt-1">
                <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="far fa-thumbs-up fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Beğen</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="far fa-comment fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Yorum Yap</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="fas fa-share fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Paylaş</span></i
                  >
                </button></span
              >
                              <span
                ><button class="ref border-0 mr-2" style="height: 35px;">
                  <i class="fas fa-paper-plane fa-md mt-0" style="font-size: 1.2rem"
                    ><span class="ml-2 mediatext">Gönder</span></i
                  >
                </button></span
              >
              </div>
            </div>
          </div>
        </div>

        <!-- sağ panel -->
        <div class="col-3">
          <aside class="card" style="width: 19rem">
            <div class="card-header bg-white border-0">
              <span>Akışınıza ekleyin</span
              ><span><i class="fas fa-info-circle float-right"></i></span>
            </div>
            <div class="card-title">
              <div class="ml-3 d-flex align-items-center">
                <img class="float-left"
                  src="https://picsum.photos/id/101/50/50"
                  style="width: 50px; height: 50px; border-radius: 50%"
                />
                <div class="header ml-1 " style="font-size: 14px"
                  >Codecraft</div
                >
                <span class="float-right mr-3"
                  ><button
                    class="btn btn-outline-info ml-5 p-0 px-2"
                    style="border-radius: 50px; height: 30px; font-size: 14px;"
                  >
                    <strong>+ Takip Et</strong>
                  </button></span
                >
              </div>
            </div>
            <div class="card-title">
              <div class="ml-3 d-flex align-items-center">
                <img class="float-left"
                  src="https://picsum.photos/id/102/50/50"
                  style="width: 50px; height: 50px; border-radius: 50%"
                />
                <div class="header ml-1" style="font-size: 14px"
                  >Podfresh</div
                >
                <span class="float-right mr-3"
                  ><button
                    class="btn btn-outline-info p-0 px-2"
                    style="border-radius: 50px; height: 30px; font-size: 14px; margin-left: 52px;"
                  >
                    <strong>+ Takip Et</strong>
                  </button></span
                >
              </div>
            </div>
            <div class="card-title">
              <div class="ml-3 d-flex align-items-center">
                <img class="float-left"
                  src="https://picsum.photos/id/103/50/50"
                  style="width: 50px; height: 50px; border-radius: 50%"
                />
                <div class="header ml-1" style="font-size: 14px"
                  >Navlungo</div
                >
                <span class="float-right mr-3"
                  ><button
                    class="btn btn-outline-info p-0 px-2"
                    style="border-radius: 50px; height: 30px; font-size: 14px; margin-left: 50px;"
                  >
                    <strong>+ Takip Et</strong>
                  </button></span
                >
              </div>
            </div>
            <div
              class="card-footer bg-white border-0"
              style="font-size: 14px; color: #0a66c2"
            >
              <strong></strong>
            </div>
          </aside>
          <div class="card mt-2 d-inline-flex" style="width: 19rem; position: sticky; top: 4rem; overflow: visible;">
            <div class="card-header bg-white border-0">
              <span>Bugünün en çok izlenen eğitimleri</span
              ><span><i class="fas fa-info-circle float-right"></i></span>
            </div>
            <div class="card-title">
              <ol>
                <li>
                  The Six Morning Habits of High Perf...
                  <div
                    style="
                      font-weight: lighter;
                      font-size: 13px;
                      color: #5f5f5f;
                    "
                  >
                    Pete Mocakatais | How to be blabla...
                  </div>
                </li>
                <li class="mt-2">
                  Onconscious Blas
                  <div
                    style="
                      font-weight: lighter;
                      font-size: 13px;
                      color: #5f5f5f;
                    "
                  >
                    Stacey Gordon
                  </div>
                </li>
                <li class="mt-2">
                  Critical Thinking for Better Judgme...
                  <div
                    style="
                      font-weight: lighter;
                      font-size: 13px;
                      color: #5f5f5f;
                    "
                  >
                    Becki Saltzman
                  </div>
                </li>
              </ol>
            </div>
            <div
              class="card-footer text-center bg-white border-0 font-weight-bold"
              style="color: #0a66c2; font-size: 15px; margin-top: -25px"
            >
              Linkedin Learning'de daha fazlasını göster
            </div>
          </div>
          <div class="text-center" style="width: 19rem; position: sticky; top: 20rem; overflow: visible;">
            <div class="d-inline-flex text-center"
              ><a href="https://about.linkedin.com/" class="link mr-3"
                >Hakkında</a
              ></div
            >
            <div class="d-inline-flex text-center"
              ><a
                href="https://www.linkedin.com/accessibility?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BT6H7rzDzR%2FSQEvO%2BuBKdSw%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_feed-compactfooter.accessibility"
                class="link mr-3"
                >Erişilebilirlik</a
              ></div
            >
            <div class="d-inline-flex text-center"
              ><a
                href="https://www.linkedin.com/help/linkedin?trk=footer_d_flagship3_feed&lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BT6H7rzDzR%2FSQEvO%2BuBKdSw%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_feed-compactfooter.help"
                class="link"
                >Yardım Merkezi</a
              ></div
            >
            <div class="d-inline-flex text-center"><a href="" class="link mr-3">Gizlilik ve Koşullar</a></div>
            <div class="d-inline-flex text-center"
              ><a
                href="https://www.linkedin.com/help/linkedin/answer/62931?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BT6H7rzDzR%2FSQEvO%2BuBKdSw%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_feed-compactfooter.ad_choices"
                class="link"
                >Reklam Tercihleri</a
              ></div
            >
            <div class="d-block-flex text-center"
              ><a
                href="https://www.linkedin.com/ad/start?trk=n_nav_ads_rr&lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BT6H7rzDzR%2FSQEvO%2BuBKdSw%3D%3D&licu=urn%3Ali%3Acontrol%3Ad_flagship3_feed-compactfooter.advertising"
                class="link"
                >Reklam</a
              ></div
            >
            <div class="d-inline-flex text-center" style="margin-top: 10px">
              <img
                src="https://www.logo.wine/a/logo/LinkedIn/LinkedIn-Logo.wine.svg"
                width="90px"
                height="20px"
              /><span style="font-size: 12px; margin-left: -15px"
                >Linkedin Corporation © 2021</span
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- mesajlaşma -->
    <nav
      class="position-sticky fixed-bottom border bg-white"
      style="width: 400px; height: 50px; position: -webkit-sticky; border-radius: 5px; margin-left: auto; right: 15px;"
    >
      <a class="navbar-brand" href="#"
        ><img
          src="https://picsum.photos/id/45/30/30"
          style="width: 30px; height: 30px; border-radius: 50%; margin-left: 20px;"
      /></a>
      <span style="font-size: 14px; font-weight: bold; font-family:Arial, Helvetica, sans-serif;"><strong>Mesajlaşma</strong></span>
      <span class="offset-3"><img src="/assets/edit-regular.svg" width="15px" height="15px" ></span>
      <span><i class="fas fa-ellipsis-h fa-sm ml-3"></i></span>
      <span><i class="fas fa-chevron-up fa-sm ml-3"></i></span>
    </nav>
  </body>
</html>
  ```
//Style.css
```html
    .navbarbg {
  height: 60px;
  background-color: white;
}

input.searche {
  height: 36px;
  max-width: 500px;
  background-color: #eef3f8;
  border: 0;
  margin-top: 3px;
}

input.searche::placeholder {
  font-size: 14px;
  color: gray;
  background-image: url(../assets/search-solid.svg);
  background-repeat: no-repeat;
  background-size: 7%;
  padding-left: 15%;
}

.body {
  background-color: #f3f2ef;
}

.menutext {
  font-size: 13px;
  font-family: Arial, Helvetica, sans-serif;
  color: gray;
  margin-top: 5px;
  font-weight: lighter;
}

.menutext:hover {
  color: black;
}

button.mediatext {
  color: #5f5f5f;
}

button.mediatext:hover {
  color: #5f5f5f;
}

.mediatext {
  font-size: 15px;
  font-weight: bold;
  font-family: Arial, Helvetica, sans-serif;
  color: #5f5f5f;
}

i {
  color: gray;
  margin-top: 8px;
}
i:hover {
  color: black;
}

input.content {
  border-radius: 40px;
  height: 45px;
}
input.content::placeholder {
  font-weight: bolder;
  font-size: 14px;
  font-family: Arial, Helvetica, sans-serif;
  background-image: url(../assets/edit-regular.svg);
  background-repeat: no-repeat;
  background-size: auto;
  padding-left: 6%;
}

div.card {
  border-radius: 10px;
}

.header {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 16px;
  font-weight: bolder;
}

.view {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-size: 12px;
  font-weight: bold;
  color: #5f5f5f;
}

.categories {
  font-size: 13px;
  font-weight: bold;
  color: #0a66c2;
}

li {
  font-size: 14px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-weight: bold;
}

.link {
  font-size: 12px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  color: #5f5f5f;
}

button.ref {
  color: white;
}

button.ref:hover {
  color: #5f5f5f;
}

.postphoto {
  border-radius: 50%;
  width: 50px;
  height: 50px;
}
.posttext {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-weight: bold;
  font-size: 14px;
  margin-left: 8px;
}
```
</details>

## :brain: JAVASCRİPT Ödev-1  Javascript Saat Ve Karşılama


### :question: SORU 
Basitçe sizden girişte isminizi isteyip sonra bu ismi karşılama ekranına yerleştirerek o anki saati ve günü gösteren bir ekran. Yapması oldukça kolay ve zevkli!

Burada bizim verdiğimiz ile sınırlı kalmak zorunda değilsiniz, hatta hayal gücünüzü çalıştırarak yeni şeyler üretirseniz daha mutlu oluruz!

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>
  
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
<link rel="stylesheet" href="css/style.css">

<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inconsolata:wght@400;800&display=swap" rel="stylesheet">
<title>Clock</title>
</head>
<body onload="startTime()" class="bg-dark">
<header class="text-center"><img src="images/kodluyoruz.png" alt=""></header>
<main class="container text-center">
<section class="row mx-auto">
<article class="col user-name"></article>
</section>
<section class="row mx-auto">
<article class="col clock"></article>
</section>
        
<section class="row mx-auto">
<article class="col">tarihinde <span style="font-weight: bold;">Frontend Web Development Patikası</span>'nın Javascript bölümü 1. Ödevindesiniz.</article>
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

<!-- Our JavaScript DOCS -->
<script src="js/clock.js"></script>
</body>
</html>
  ```
//clock.js
  ```html

let userNameCol = document.querySelector(".user-name");
let clockCol = document.querySelector(".clock");

function startTime(){
    let today = new Date();

    let hour = today.getHours();
    let minute = today.getMinutes();
    let second = today.getSeconds();
    let day = today.getDay();

    switch (day){
        case 1:
            day = "Pazartesi";
            break;
        case 2:
            day = "Salı";
            break;
        case 3:
            day = "Çarşamba";
            break;
        case 4:
            day = "Perşembe";
            break;
        case 5:
            day = "Cuma";
            break;
        case 6:
            day = "Cumartesi";
            break;
        case 7:
            day = "Pazar";
            break;
    };
    
    function checkTime(i){
        if (i < 10) {i = '0' + i};
        return i;
    };

    hour = checkTime(hour);
    minute = checkTime(minute);
    second = checkTime(second);

    clockCol.innerHTML = `${hour}:${minute}:${second} ${day}`;
    
    let t = setTimeout(startTime,500);

}



let userName = prompt("Adınız Nedir?");

    if (userName.length === 0){
        userNameCol.innerHTML = `Merhaba, Guest! Hoş geldin!`;
    }
    else{
        userNameCol.innerHTML = `Merhaba, ${userName}! Hoş geldin!`;
    };
  ```
   //style.css
  ```css
    body{
    font-family: 'Inconsolata', monospace;
    font-size: 30px;
    color: #F88908;
    letter-spacing: 3px;
}
header{
    padding-top: 75px;
}
```
</details>
  
  ## :brain: JAVASCRIPT Ödev-2 Javascript ile To Do List


### :question: SORU 
Günlük hayatta yapacağımız işleri aklımızda tutmak oldukça zor oluyor değil mi? Parmağınıza ip bağlamak da bir çözüm getirmiyorsa bir yapılacaklar listesi hazırlamayı düşünmeniz gerekebilir. İnanır mısınız Kodluyoruz tam da bu probleminiz için harika bir çözüm ve harika bir ödevle geldi, karşınızda JavsScript To Do List! JavaScript ile bir yapılacaklar listesi yapmanızı istiyoruz. Sizlere yine bir temel verip bunun js dosyasını oluşturmanızı istiyoruz.

### :green_square: CEVAP
  
<details>
<summary>Kodu görmek için tıklayınız.</summary>
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

<!-- Our CSS -->
<link rel="stylesheet" href="css/style.css">

<title>To Do List</title>
</head>
<body>

<!-- TOAST FAIL - START -->
<div class="toast failToast position-fixed top-0 end-0" role="alert" aria-live="assertive" aria-atomic="true">
<div class="toast-header d-flex justify-content-between text-danger fw-bold">
HATA!
<button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
</div>
<div class="toast-body">
Listeye Boş Ekleyemessiniz!
</div>
</div>
<!-- TOAST FAIL - END -->
    
    
     <!-- TOAST SUCCESS - START -->
    <div class="toast successToast position-fixed top-0 end-0" role="alert" aria-live="assertive" aria-atomic="true">
        <div class="toast-header d-flex justify-content-between text-succcess fw-bold">
            BAŞARILI!
            <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
        </div>
        <div class="toast-body">
          Listeye Eklendi!
        </div>
     </div>
     <!-- TOAST SUCCESS - END -->


    <!-- HEADER - START -->
        <header class="container">
            <div class="row text-center d-flex flex-column p-4 headerBackground">
                <div class="col"><h1><img src="img/kodluyoruz.PNG" alt="kodluyoruz.png"></h1></div>
                <div class="col"><h3 class="header text-white">Yapılacaklar Listesi</h3></div>
                <div class="col"><input class="border-0 p-3 inputArea" type="text" name="toDoInput" placeholder="Bugün ne yapacaksın?"><button type="submit" class="submitButton p-0">Ekle</button></div>
            </div>
        </header>
    <!-- HEADER - END -->

    <!-- MAIN - START -->
        <main class="container">
            <section class="row">
                <ul class="list-group listUl p-0 d-flex">
                    <!-- To do list Li elemets -->
                  </ul>
            </section>
        </main>
    <!-- MAIN - END -->

    


    
    <!-- Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <script>
        
    </script>

    <!-- Fontawesome -->
    <script src="https://kit.fontawesome.com/8af05135ea.js" crossorigin="anonymous"></script>

    <!-- Our JS -->
    <script src="js/app.js"></script>
  </body>
</html>
  ```
//app.js
```js
  
// -------------------- DOM - START --------------------
const inputDOM = document.querySelector(".inputArea");
const submitButtonDOM = document.querySelector(".submitButton");
const ulDOM = document.querySelector(".listUl");
let liDOM1 = document.querySelector(".listItemLi1");
let liDOM2 = document.querySelector(".listItemLi2");
let removeButtonDOM = document.querySelector(".closeButton");
const toastFailDOM = document.querySelector(".failToast");
const toastSuccessDOM = document.querySelector(".successToast");
// -------------------- DOM - END --------------------

// ********** LOCAL STORAGE FUNCTIONS - START **********

let startLocalStorage = () => {

    let isLocalStorage = JSON.parse(localStorage.getItem('toDo'));
    
    if (!isLocalStorage) {
        isLocalStorage = [];
        localStorage.setItem('toDo',JSON.stringify(isLocalStorage));
    }
    else {
        // todo ları sayfaya yükle
        for (let i = 0; i < isLocalStorage.length; i++) {
            if (ulDOM.childElementCount === 0) {
                let firstLi = document.createElement('li');
                firstLi.classList.add("listItemLi1", "list-group-item", "d-flex", "justify-content-between", "align-items-center");
                firstLi.innerHTML = `
                    <div><i class="checkMark fas fa-check"></i><span style="margin-left: 20px;">${isLocalStorage[i].toDo}</span></div>
                    <button type="button" class="btn-close closeButton " aria-label="Close">
                `;
                if (isLocalStorage[i].isChecked){
                    isCheckedEvent(firstLi,'liDOM1');
                    ulDOM.appendChild(firstLi);
                }
                else{
                    ulDOM.appendChild(firstLi);
                };
                
            }
            else if (ulDOM.childElementCount % 2 === 0) {
                let firstLi = document.createElement('li');
                firstLi.classList.add("listItemLi1", "list-group-item", "d-flex", "justify-content-between", "align-items-center");
                firstLi.innerHTML = `
                    <div><i class="checkMark fas fa-check"></i><span style="margin-left: 20px;">${isLocalStorage[i].toDo}</span></div>
                    <button type="button" class="btn-close closeButton " aria-label="Close">
                `;
                if (isLocalStorage[i].isChecked){
                    isCheckedEvent(firstLi,'liDOM1');
                    ulDOM.appendChild(firstLi);
                }
                else{
                    ulDOM.appendChild(firstLi);
                };
            }
            else {
                let secondLi = document.createElement('li');
                secondLi.classList.add("listItemLi2", "list-group-item", "d-flex", "justify-content-between", "align-items-center");
                secondLi.innerHTML = `
                    <div><i class="checkMark fas fa-check"></i><span style="margin-left: 20px;">${isLocalStorage[i].toDo}</span></div>
                    <button type="button" class="btn-close closeButton " aria-label="Close">
                `;
                if (isLocalStorage[i].isChecked){
                    isCheckedEvent(secondLi,'liDOM2');
                    ulDOM.appendChild(secondLi);
                }
                else{
                    ulDOM.appendChild(secondLi);
                };
            };
        };
    };
    liDOM1 = document.querySelector(".listItemLi1");
    liDOM2 = document.querySelector(".listItemLi2");
    removeButtonDOM = document.querySelector(".closeButton");
};

startLocalStorage();



let getTodosFromLocalStorage = () => {
    return JSON.parse(localStorage.getItem('toDo'));
}
let setTodosToLocalStorage = (obj) => {
    localStorage.setItem('toDo', JSON.stringify(obj));
}
let addTodoToLocalStorage = (obj) => {
    todos = getTodosFromLocalStorage();
    todos.push(obj);
    setTodosToLocalStorage(todos);
}

let isClicked = (isClicked) => {
    let obj = getTodosFromLocalStorage();

    for (let i = 0; i < obj.length; i++) {
        if (obj[i].toDo === isClicked){
            obj[i].isChecked = !obj[i].isChecked;
        }
    }

    setTodosToLocalStorage(obj);
}

let deleteTodoFromLocalStorage = (todoName) => {
    let todos = getTodosFromLocalStorage();

    for(let i = 0; i < todos.length; i++){
        if (todos[i].toDo == todoName) {
            todos.splice(i,1);
        }
    }
    setTodosToLocalStorage(todos);


}

// ********** LOCAL STORAGE FUNCTIONS - END **********



// -------------------- TOAST OPTIONS - START --------------------
var option = {
            
    animation : true,
    delay : 3000
};
// -------------------- TOAST OPTIONS - END --------------------





// -------------------- EVENTS - START --------------------
submitButtonDOM.addEventListener('click',clickEvent);
ulDOM.addEventListener('click', clickEvent);
// -------------------- EVENTS - END --------------------





// -------------------- FUNTIONS - START --------------------
    // ********** EVENT FUNCTIONS - START **********
function clickEvent (event) {
    event.preventDefault();


    // SUBMIT BUTTON CLICK
    if(event.target.className === submitButtonDOM.className) {
        let inputValue = inputDOM.value.trim();
        if (inputValue != "") {
            var toastElement = new bootstrap.Toast(toastSuccessDOM, option);
            toastElement.show();
            if (ulDOM.childElementCount === 0) {
                let firstLi = document.createElement('li');
                firstLi.classList.add("listItemLi1", "list-group-item", "d-flex", "justify-content-between", "align-items-center");
                firstLi.innerHTML = `
                    <div><i class="checkMark fas fa-check"></i><span style="margin-left: 20px;">${inputValue}</span></div>
                    <button type="button" class="btn-close closeButton " aria-label="Close">
                `;
                ulDOM.appendChild(firstLi);
                inputDOM.value = "";
                liDOM1 = document.querySelector(".listItemLi1");
                removeButtonDOM = document.querySelector(".closeButton");

                // -------------------- LOCAL STORAGE - START --------------------
                
                const toDo = {
                    toDo: inputValue,
                    isChecked: false,
                };

                addTodoToLocalStorage(toDo);
            
                
                // -------------------- LOCAL STORAGE - END --------------------

            }
            else if (ulDOM.childElementCount % 2 === 0) {
                let firstLi = document.createElement('li');
                firstLi.classList.add("listItemLi1", "list-group-item", "d-flex", "justify-content-between", "align-items-center");
                firstLi.innerHTML = `
                    <div><i class="checkMark fas fa-check"></i><span style="margin-left: 20px;">${inputValue}</span></div>
                    <button type="button" class="btn-close closeButton " aria-label="Close">
                `;""
                ulDOM.appendChild(firstLi);
                inputDOM.value = "";
                liDOM1 = document.querySelector(".listItemLi1");
                removeButtonDOM = document.querySelector(".closeButton");

                // -------------------- LOCAL STORAGE - START --------------------
                const toDo = {
                    toDo: inputValue,
                    isChecked: false,
                };

                addTodoToLocalStorage(toDo);
                
                
                // -------------------- LOCAL STORAGE - END --------------------
            }
            else {
                let secondLi = document.createElement('li');
                secondLi.classList.add("listItemLi2", "list-group-item", "d-flex", "justify-content-between", "align-items-center");
                secondLi.innerHTML = `
                    <div><i class="checkMark fas fa-check"></i><span style="margin-left: 20px;">${inputValue}</span></div>
                    <button type="button" class="btn-close closeButton " aria-label="Close">
                `;
                ulDOM.appendChild(secondLi);
                inputDOM.value = "";
                liDOM2 = document.querySelector(".listItemLi2");
                removeButtonDOM = document.querySelector(".closeButton");

                // -------------------- LOCAL STORAGE - START --------------------
                
                const toDo = {
                    toDo: inputValue,
                    isChecked: false,
                };

                addTodoToLocalStorage(toDo);
                
                
                // -------------------- LOCAL STORAGE - END --------------------
            };

            
        }
        else {
            var toastElement = new bootstrap.Toast(toastFailDOM, option);
            toastElement.show();
            console.log(ulDOM.childElementCount);
        };
    };
    
    
    // li DOM 1 CLICK
    if (liDOM1) {
        if(event.target.className === liDOM1.className) {
            isCheckedEvent(event.target,'liDOM1');
            let clickedTarget = event.target.firstElementChild.lastElementChild.innerHTML;
            isClicked(clickedTarget);
        };
    };    
    
    
    // li DOM 2 CLICK
    if (liDOM2) {
        if(event.target.className === liDOM2.className) {
            isCheckedEvent(event.target,'liDOM2');
            let clickedTarget = event.target.firstElementChild.lastElementChild.innerHTML;
            isClicked(clickedTarget);
        };
    };

    // CLOSED (REMOVE) BUTTON IN LIST CLICK
    if (removeButtonDOM) {
        if(event.target.className === removeButtonDOM.className) {       
            let todoName = event.target.previousElementSibling.lastElementChild.innerHTML;
            deleteTodoFromLocalStorage(todoName);
            event.target.parentElement.remove();
        };
    };
};


function isCheckedEvent (event,liDOM) {
    if (liDOM === 'liDOM1'){
        if (event.style.backgroundColor !== "rgb(36, 101, 115)") {
            event.style.background = "rgb(36, 101, 115)";
            event.style.textDecoration = "line-through";
            event.style.color = "white";
            event.firstElementChild.firstElementChild.style.opacity = 1;
        }
        else if (event.style.backgroundColor == "rgb(36, 101, 115)") {
            event.style.backgroundColor = null;
            event.style.textDecoration = null;
            event.style.color = null;
            event.firstElementChild.firstElementChild.style.opacity = null;
        };
    }
    else {
        if (event.style.backgroundColor !== "rgb(36, 101, 115)") {
            event.style.background = "rgb(36, 101, 115)";
            event.style.textDecoration = "line-through";
            event.style.color = "white";
            event.firstElementChild.firstElementChild.style.opacity = 1;
        }
        else if (event.style.backgroundColor == "rgb(36, 101, 115)") {
            event.style.backgroundColor = null;
            event.style.textDecoration = null;
            event.style.color = null;
            event.firstElementChild.firstElementChild.style.opacity = null;
        };
    };
};
    // ********** EVENT FUNCTIONS - END **********
// -------------------- FUNTIONS - END --------------------
 ```
//style.css

/* -------------------- HEADER - START -------------------- */
.headerBackground {
    background-color: #F78501;
}

.inputArea {
    width: 70%;
    height: 40px;
    padding-top: 15px !important;
}
.submitButton {
    background-color: #cccccc;
    border: none;
    height: 40px;
    width: 30%;
    transition: background-color 0.3s linear;
}
button:hover {
    background-color: #aaaaaa;
}
/* -------------------- HEADER - END -------------------- */


/* -------------------- MAIN - START -------------------- */
.closeButton {
    width: 45px;
    height: 45px;
    padding: 0;
    border-radius: 0;
    transition: background-color 0.3s linear;
}
.closeButton:hover{
    background-color: #F78501;
}
.listItemLi1{
    border-radius: 0px !important;
    border: none;
    height: 45px;
    padding-top: 0 !important;
    padding-bottom: 0 !important;
    padding-right: 0 !important;
    background-color: rgb(249, 249, 249);
    cursor: pointer;
    transition: background-color 0.3s linear;
}
.listItemLi2{
    border-radius: 0px !important;
    border: none;
    height: 45px;
    padding-top: 0 !important;
    padding-bottom: 0 !important;
    padding-right: 0 !important;
    background-color: #e9e9e9;
    cursor: pointer;
    transition: background-color 0.3s linear;
}
.checkMark {
    opacity: 0.1;
}
.listItemLi1:hover{
    background-color: rgb(242, 242, 242);
}
.listItemLi2:hover {
    background-color: #e2e2e2;
}
/* -------------------- MAIN - END -------------------- */
      ```
 </details>

                      
## :brain: HTML Ödev-3  Asian Kitchen's Menu


### :question: SORU 
Bir uzak doğu restoran menüsü şeklinde düzenlenmiş sitede JavaScript sayesinde sayfalar arasında gezinilebilmekte. Oldukça hoş bir görüntüye sahip bu sitenin HTML ve CSS kodlarını size hazır vereceğiz. Sizden istediğimiz JavaScript kısmını tamamlamanız. Siteyi detaylı incelemek için Asian Kitchen's Menu

Sitedeki içerik JavaScript'te menu şeklinde bir dizi içinde objeler olarak tanımlanacak.
Id, title, category, price, img ve desc bölümleri olacak.
İçeriği istediğiniz gibi değiştirebilirsiniz yalnız değiştirirken kategori isimlerine ekstra dikkat edin.
Butonlar da js dosyasından gelecek.
Site içerisinde map, reduce gibi methodları kullanmanız gerekecek. Hatırlamıyorsanız Map ile Array İçerisideki Yapının Değiştirilerek Yeni Liste Oluşturulması #38 isimli videoya dönebilirsiniz.

### :green_square: CEVAP
<details>
<summary>Kodu görmek için tıklayınız.</summary>

//index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Asian Kitchen</title>
    <!-- Fonts -->
    <link
      href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Zilla+Slab&display=swap"
      rel="stylesheet"
    />
    <!-- Boostrap CDN -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1"
      crossorigin="anonymous"
    />
    <!-- CSS -->
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <div class="container">
      <section class="menu">
        <!-- title -->
        <div class="title">
          <h2>Asian Kitchen's Menu</h2>
        </div>
        <!-- filter buttons-->
        <div class="btn-container"></div>
        <!-- menu items -->
        <div class="section-center row">
          <!-- single-item -->

          <!-- end of single item -->
        </div>
      </section>
    </div>

    <script src="js/app.js"></script>

  </body>
</html>
 ```
//app.js
```js
const menu = [
  {
    id: 1,
    title: "Tteokbokki",
    category: "Korea",
    price: 10.99,
    img:
      "https://twoplaidaprons.com/wp-content/uploads/2020/09/tteokbokki-top-down-view-of-tteokbokki-in-a-bowl-500x500.jpg",
    desc: `Spicy rice cakes, serving with fish cake.`,
  },
  {
    id: 2,
    title: "Chicken Ramen",
    category: "Japan",
    price: 7.99,
    img:
      "https://www.forkknifeswoon.com/wp-content/uploads/2014/10/simple-homemade-chicken-ramen-fork-knife-swoon-01.jpg",
    desc: `Chicken noodle soup, serving with vegetables such as soy bean, green onion. In an optional you can ask for egg. `,
  },
  {
    id: 3,
    title: "Bibimbap",
    category: "Korea",
    price: 8.99,
    img:
      "https://dwellbymichelle.com/wp-content/uploads/2020/05/DWELL-bibimbap.jpg",
    desc: `Boiling vegetables, serving with special hot sauce`,
  },
  {
    id: 4,
    title: "Dan Dan Mian",
    category: "China",
    price: 5.99,
    img:
      "https://www.savingdessert.com/wp-content/uploads/2019/02/Dan-Dan-Noodles-10.jpg",
    desc: `Dan dan noodle, serving with green onion `,
  },
  {
    id: 5,
    title: "Yangzhou Fried Rice",
    category: "China",
    price: 12.99,
    img:
      "https://salu-salo.com/wp-content/uploads/2013/02/Yangzhou-Fried-Rice1.jpg",
    desc: `Yangzhou style fried rice, serving with bean and pickles `,
  },
  {
    id: 6,
    title: "Onigiri",
    category: "Japan",
    price: 9.99,
    img:
      "https://www.manusmenu.com/wp-content/uploads/2017/08/Onigiri-3-1-of-1.jpg",
    desc: `Rice Sandwich, serving with soy sauce`,
  },
  {
    id: 7,
    title: "Jajangmyeon",
    category: "Korea",
    price: 15.99,
    img:
      "https://www.curiouscuisiniere.com/wp-content/uploads/2020/04/Jajangmyeon-Korean-Noodles-in-Black-Bean-Sauce5.1200H-720x540.jpg",
    desc: `Black bean sauce noodle, serving with green onion `,
  },
  {
    id: 8,
    title: "Ma Yi Shang Shu",
    category: "China",
    price: 12.99,
    img:
      "https://assets.tmecosys.com/image/upload/t_web767x639/img/recipe/ras/Assets/F688C2F6-86EC-46C4-B9C7-A6BA01DF7437/Derivates/32E3E72A-F786-406D-AF7F-B30980A9AC6C.jpg",
    desc: `Hot pepper sauce noodle, serving with soy bean and onion`,
  },
  {
    id: 9,
    title: "Doroyaki",
    category: "Japan",
    price: 3.99,
    img:
      "https://www.justonecookbook.com/wp-content/uploads/2011/10/Dorayaki-New-500x400.jpg",
    desc: `Red bean paste dessert, serving with honey.`,
  },
];

// CREATE ELEMENT
let itemMenu = document.createElement('div');
itemMenu.classList.add('menu-items', 'col-lg-6', 'col-sm-12');
itemMenu.innerHTML = `
<img src="${menu[0].img}" alt="${menu[0].title}" class="photo">
<div class="menu-info">
  <div class="menu-title">
    <h4>${menu[0].title}</h4>
    <h4 class="price">${menu[0].price}</h4>
  </div>
  <div class="menu-text">
    ${menu[0].desc}
  </div>
</div>
`;

const section = document.querySelector(".section-center");
const btnContainer = document.querySelector(".btn-container");

const categories = menu.reduce(
  (values, item) => {
    if (!values.includes(item.category)) {
      values.push(item.category);
    }
    return values;
  },
  ["All"]
);

const categoryList = () => {
  const categoryBtns = categories
    .map((category) => {
      return `<button class="btn btn-outline-dark btn-item" data-id=${category}>${category}</button>`;
    })
    .join("");

  btnContainer.innerHTML = categoryBtns;
  const filterBtns = document.querySelectorAll(".btn-item");

  //filter menu
  filterBtns.forEach((btn) => {
    btn.addEventListener("click", (e) => {
      const category = e.currentTarget.dataset.id;
      console.log(category);
      const menuCategory = menu.filter((menuItem) => {
        if (menuItem.category === category) {
          return menuItem;
        }
      });
      if (category === "All") {
        menuList(menu);
      } else {
        menuList(menuCategory);
      }
    });
  });
};

const menuList = (menuItems) => {
  let displayMenu = menuItems.map((item) => {
    return `<div class="menu-items col-lg-6 col-sm-12">
            <img
              src=${item.img}
              alt=${item.title}
              class="photo"
            />
            <div class="menu-info">
              <div class="menu-title">
                <h4>${item.title}</h4>
                <h4 class="price">${item.price}</h4>
              </div>
              <div class="menu-text">
                ${item.desc}
              </div>
            </div>
          </div>
    `;
  });
  displayMenu = displayMenu.join("");
  section.innerHTML = displayMenu;
};

menuList(menu);
categoryList();
 ```
 //style.css
  ```css
  * {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  background-color: #f1f5f8;
  font-family: "Zilla Slab", serif;
}

h2 {
  font-family: "Great Vibes", cursive;
  font-size: 3rem;
  text-align: center;
  color: #ff6a23;
}
.menu {
  margin-top: 20px;
}

.btn-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 40px 0;
}
.btn-item {
  margin-left: 15px;
}

.photo {
  width: 30%;
  height: 175px;
  object-fit: cover;
  border: 0.25rem solid black;
  border-radius: 10px;
}
.menu-items {
  display: flex;
  margin: 20px 0;
}
.menu-info {
  margin-left: 20px;
  width: 100%;
}
.menu-title {
  display: flex;
  justify-content: space-between;
  border-bottom: 1px solid black;
}

h4 {
  color: #e00a00;
}

.menu-text {
  padding-top: 20px;
}
  ```
 </details>
