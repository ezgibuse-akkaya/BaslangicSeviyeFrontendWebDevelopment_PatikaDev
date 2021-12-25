# Başlangıç Seviye Web Development Patikası - PatikaDev

[Patika.dev](https://app.patika.dev/egitimler) adresindeki "Başlangıç Seviye Frontend Web Development Patikası" eğitiminde kullandığım kaynak kodları içeren bir repo.

Bu README dosyasında bu eğitimdeki pratik ve ödevlerin cevaplarını bulacaksınız.

--------------------------------------------------------------------------------------------------------------------------------------
## :brain: Ödev-1  İlk Web Sayfamızı Oluşturmak


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

## :brain: Ödev-2  Kişisel Sayfamızı Detaylandırmaya Devam Etmek


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

## :brain: Bölüm Sonu Çalışması


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

## :brain: Ödev-3 Çikolatalı Küp Tarifi


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
