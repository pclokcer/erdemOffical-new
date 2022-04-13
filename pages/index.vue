<template>
  <div>
    <!-- home section starts -->
    <section class="home" id="home">
      <h3>MERHABALAR !</h3>
      <h1>Ben <span>ERDEM ÜN</span></h1>
      <p>
        Makine Mühendisliği Bölümü Mezunuyum. Bilgisayarla Küçüklüğümden Beri
        Çok İlgili Olduğum için Yazılım Sektörü Hep İlgimi Çekmiştir. Üniversite
        Sırasında Yazılım Konusunda İlerleyip Ürünler Oluşturdum. Şimdi ise
        Mobil Uygulamalar, Web Uygulamalar ve Backend Uygulamaları
        Geliştirmekteyim.
      </p>
      <a href="#about"
        ><button class="btn">Hakkımda <i class="fas fa-user"></i></button
      ></a>
    </section>
    <!-- home section starts -->
    <!-- about section starts -->
    <section class="about" id="about">
      <h1 class="heading"><span>Hakkımda</span> daha fazla</h1>

      <div class="row">
        <div class="info">
          <h3><span> isim : </span> Erdem ÜN</h3>
          <h3><span> yaş : </span> 26</h3>
          <h3><span> Şehir : </span> HATAY</h3>
          <h3><span> meslek : </span> Backend Developer</h3>
          <h3><span> diller : </span> Türkçe - İngilizce</h3>
          <a href="#"
            ><button class="btn">
              CV İndir <i class="fas fa-download"></i></button
          ></a>
        </div>

        <div class="counter">
          <div class="box">
            <span>33+</span>
            <h3>Repositories</h3>
          </div>

          <div class="box">
            <span>719+</span>
            <h3>Commints</h3>
          </div>

          <div class="box">
            <span>359+</span>
            <h3>Contributions</h3>
          </div>

          <div class="box">
            <span>A+</span>
            <h3>GitHub Stats</h3>
          </div>

          <div class="box">
            <span>3+</span>
            <h3>Mesleki Tecrübe</h3>
          </div>
        </div>
      </div>
    </section>
    <!-- about section ends -->
    <!-- project section starts -->
    <section class="project" id="project">
      <h1 class="heading">E-garsonum <span>Projesi</span></h1>

      <div class="box-container">
        <div class="box">
          <i class="fas fa-random"></i>
          <span>Sistemin Kurgusu</span>
          <p>
            Proje dosyaları içerisinde bulunan Diagramda Görülen Mobil, Web ve
            Sunucu yazılımlarının hepsine hakim bir şekilde kodlama yapabilirim.
            Akışı Anlatmak gerekirse, mobilden ve web den gelen http istekleri
            sunucu tarafında bulunan nginx karşılar. Burda isteğin konfigure
            ettiğimiz şekilde yönlendirilmesi yapılır. Yönlendirme web sayfası
            alabilir, API isteği alabilir veya Web Socket isteği alabilir
            şekilde konfigure edilmiştir.
          </p>
          <br /><br />

          <p>Web Sayfasına göre yönlendirme alırsa web sayfası verilir.</p>
          <br /><br />

          <p>
            API isteğine göre yönlendirme alırsa web servisimiz de ilk olarak
            token kontrolü yapılır. Token kontrolünden geçen istek mysql veya
            bellekten data alabilir ve data kaydı kapabilir.
          </p>
          <br /><br />

          <p>
            Web Socket isteğine göre yönlendirme alırsa soket bağlantısı
            gerçekleştirilir ve sokette oda kurulur. Anlık haberleşme için gelen
            Mobil Platform bağlantı istekleri bu odaya dahil edilerek
            kullanıcılar arasında bağlantı gerçekleşmiş olur. Artık Anlık olarak
            kullanıcılar birbirleri ile haberleşmeye hazırdır.
          </p>
          <br /><br />

          <p>
            Projede Kullandığım Bazı Nodejs Modülleri; <br />
            - express - nodemon - jsonwebtoken - socket.io - nodemailer - joi -
            mysql - mkdirp - moment - crypto-js - node-cron - dotenv - bcrypt -
            node-cache
          </p>
        </div>
        <a href="#"
          ><button class="btn">
            Proje Dosyalarını İndir <i class="fas fa-download"></i></button
        ></a>
      </div>
    </section>
    <!-- project section ends -->

    <!-- technologies section starts -->
    <section class="technologies" id="technologies">
      <h1 class="heading">Developer <span>Teknolojilerim</span></h1>

      <div class="box-container">
        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/82b9c7a.png" alt="" />
        </div>

        <div class="box">
          <img
            src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJcAAACXCAMAAAAvQTlLAAAAolBMVEX///9UxfgptvYBV5tDwfhNw/iT2PoASpXa8v3N2ufx+v/5/f/s+P49v/gAUJgAsfVry/nm7fSC0voBT46K1fru8/grvP0ARpNgyPm04/sAK00yaqWn3vuf2/s2ufaL0voagbgYdqcBSoQAPGwAI0MnZKIArPWj0+5HZpMXeK4AQXoAOW16zPkAKlkCRHgALVcAHUIDOmQAFDN2rdIAGl53kLkRzsTRAAACwElEQVR4nO3abVfaQBCG4ZAA0sYApTRotEoCtsVarG39/3+tO4gvkF12poHZoWfuz3rOwyUsJ4lRpGmaFqYeOs5V6Thro8rOTjl3ddstVB3WWekYO2v4nnGWapFSLUqqRenYtc5kag15tTqqhS7tytTCHxCqpVq0pGrJPOVVi9Kxa7VUS7VIqRYlqVojkRdkqkVJtUipFiXVooTXYr0vr1qEUtUipFqUjl5L6A1w1VItWqpFSbUoqRalo3/MyazF83AlJf58s8ecvS6yMe3/rBpq9TrIskuaV0OtFvJVZZc0rWYP7owW7tfbxFnNbukeSis6z5CzWLXQXsxaEfL95dDCziJrrfJ/Hvm1IO/5FUQL2i3WVOv8X2ftFrPfpGTQgtxiDi3sAdFAC3IeF0G1ILtYU63Gs+xiwbWguphDK+Z5bz1XE3NoXcUxoxa0KebSghBie9KCNsTcWhCjFvQqZr987Q3idR6xPWpBL2K7tbxi+9WCnsR8Wh6xPWtBKzG/1k6x9ue9z4pADKO1Q+wAWlA66mC0nGLZQbRgmO36s67lEDuQliOblumKT8s+y6plEROhVReTorUlJkZrU0yS1hsxUVqvYtK01mJtaVpPYof5TnR1+gU1y/SVc1aUDlF/xjiffvvEO+waNWxx2094h0V3/mH59PZj0r8QJ7Yws5JEmthKC+pffGDd5RFbrGfJEgOt512SxBbfq5dZcsTyqZn1ZpcUsXJmZm0OEyCWlz+W1eYsEWLl/bLa9govlpc/Z2ZXDSy0WDl/sO8KKma0itl6V7JdQLFyXtwbr2VVXwXDbsKIgVZRmF3WVSHERoO1lplVOUaFEsvLX8WDkyqU2N2gnM88o4KI/f7jHxVE7PEEOYxZLH2cqBhxmIpRh2HFbqSKcV/wqhg1FaOmYuRhYsUmJ6gm3MPeoWPdpWnaf9RfGXBilAYHmdQAAAAASUVORK5CYII="
            alt=""
          />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/b1fe096.png" alt="" />
        </div>

        <div class="box">
          <img
            src="https://miro.medium.com/max/336/1*glD7bNJG3SlO0_xNmSGPcQ.png"
            alt=""
          />
        </div>

        <div class="box">
          <img
            src="https://sm.pcmag.com/pcmag_au/review/a/amazon-web/amazon-web-services_282w.jpg"
            alt=""
          />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/549e225.png" alt="" />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/2fc260c.png" alt="" />
        </div>

        <div class="box">
          <img
            src="https://raw.githubusercontent.com/nuxt/nuxt.js/HEAD/.github/nuxt.png"
            alt=""
          />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/7e73d33.png" alt="" />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/afe21ec.jpg" alt="" />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/728ff5a.png" alt="" />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/e7b8fcd.png" alt="" />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/a2f37fc.png" alt="" />
        </div>

        <div class="box">
          <img src="https://erdemun.com/_nuxt/img/7384412.png" alt="" />
        </div>
      </div>
    </section>
    <!-- technologies section ends -->

    <!-- contact section starts -->
    <section class="contact" id="contact">
      <h1 class="heading"><span>İletişime</span> geç</h1>

      <div class="row">
        <div class="content">
          <h3 class="title">İLETİŞİM BİLGİLERİ</h3>

          <div class="info">
            <h3><i class="fas fa-envelope"></i> erdemun.offical@gmail.com</h3>
            <h3><i class="fas fa-phone"></i> +90 543 231 90 57</h3>
            <h3>
              <i class="fas fa-map-marker-alt"></i> Hatay , Türkiye - 31000
            </h3>
          </div>
        </div>

        <form action="">
          <input type="text" placeholder="İsim Soyisim" class="box" />
          <input type="email" placeholder="E-mail" class="box" />
          <input type="number" placeholder="Telefon" class="box" />
          <textarea
            name=""
            id=""
            cols="30"
            rows="10"
            class="box message"
            placeholder="Mesajınızı buraya yazınız"
          ></textarea>
          <button type="submit" class="btn">
            gönder <i class="fas fa-paper-plane"></i>
          </button>
        </form>
      </div>
    </section>
    <!-- contact section ends -->
  </div>
</template>

<script>
export default {
  layout: "default",
  name: "IndexPage",
};
</script>
