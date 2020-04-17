<template>
  <div class="site-wrap"  id="home-section">

    <Header></Header>

    <div class="owl-carousel slide-one-item">
      <a @click="donation()"><img src="images/kumanya.png" alt="Image" class="img-fluid"></a> <!-- 1500 x 800 px-->
      <a @click="donation()"><img src="images/iftar.png" alt="Image" class="img-fluid"></a>
    </div>

    <h1 class="mb-0 pt-2" style="background: #fd5f00; color: #fff;">Hayra Ortak Ol</h1>

    <div class="d-block d-md-flex intro-engage">

      <div>
        <h2>KUMANYA</h2>
        <p>Kumanyalarınızı ihtiyaç sahibi öğrencilere ulaştırıyoruz..</p>
      </div>
      <div>
        <h2>İFTAR</h2>
        <p>
          Peygamber Efendimiz (s.a.v.), “Kim bir oruçluya <br> iftar ettirirse,
          o oruçlunun alacağı sevabın aynısı, iftar ettirene de yazılır ve oruç <br>
          tutanın sevabından da bir şey eksilmez.” buyurmuştur. <br>
          İhtiyaç sahibi öğrenci ve ailelerine iftar verebilirsiniz..
        </p>
      </div>
      <div>
        <h2>ZEKAT</h2>
        <p>Okuyan öğrenciler zekatlarınız ile geleceğe umutla bakacak..</p>
      </div>
    </div>

    <div class="site-section bg-image overlay counter" style="background-image: url('images/hero_1_no-text.jpg');" id="about-section">
      <div class="container">
        <div class="row mb-5">


          <div class="col-lg-6 mb-4">
            <figure class="block-img-video-1" data-aos="fade">
              <a href="images/dernek.jpg" class="popup-vimeo" style="overflow: hidden;">
                <img src="images/dernek.jpg" alt="Image" class="img-fluid dernek-photo">
              </a>
            </figure>
          </div>
          <div class="col-lg-5 ml-auto align-self-lg-center">
            <h2 class="text-black mb-4 text-uppercase section-title">Hakkımızda</h2>
            <p class="text-black">
              Hikayemiz 2015 yılında Hisar Eğitim ve Kültüre Hizmet Derneği adı altında başladı. Genç neslin eğitim ve terbiyesi için madden ve manen hayatın her alanında onları destekliyoruz..
            </p>
            <p class="text-black">
              Bir neslin ihyası kötülerin imhasıyla değil, yeni neslin eğitim ve terbiyesiyle mümkündür.
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 mb-4 col-lg-0 col-lg-3">
            <div class="block-counter-1">
              <span class="number"><span data-number="313">0</span></span>
              <span class="caption text-black">Öğrenci</span>
            </div>
          </div>
          <div class="col-md-6 mb-4 col-lg-0 col-lg-3">
            <div class="block-counter-1">
              <span class="number"><span data-number="492">0</span></span>
              <span class="caption text-black">Aile</span>
            </div>
          </div>
          <div class="col-md-6 mb-4 col-lg-0 col-lg-3">
            <div class="block-counter-1">
              <span class="number"><span data-number="571">0</span></span>
              <span class="caption text-black">İhtiyaç Sahibi</span>
            </div>
          </div>
          <!-- <div class="col-md-6 mb-4 col-lg-0 col-lg-3">
            <div class="block-counter-1">
              <span class="number"><span data-number="1212">0</span></span>
              <span class="caption text-black">Number of Orphans</span>
            </div>
          </div> -->
        </div>
      </div>
    </div>

    <!-- <div class="site-section bg-light counter" id="discover-section">
      <div class="container"> -->
        <!-- <div class="row mb-5 justify-content-center">
          <div class="col-md-7 text-center">
            <div class="block-heading-1">
              <h2 class="text-black text-uppercase">Eğitime Destek</h2>
              <p>Eğitime ve öğrencilerimize değer katıyoruz.</p>
            </div>
          </div>
        </div> -->


        <!-- <div class="row mb-5">

          <div class="col-lg-6 mb-5">
            <img src="images/hero_1_no-text.jpg" alt="Image" class="img-fluid">
          </div>
          <div class="col-lg-5 ml-auto align-self-center">
            <h3 class="text-black text-uppercase mb-4">Eğitime Destek</h3>
            <p class="mb-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam quis, nemo explicabo cupiditate vero fugiat sit eius sequi.</p>

            <div class="row mb-4">
              <div class="col-md-6">
                <div class="block-counter-1 block-counter-1-sm">
                  <span class="number"><span data-number="15">0</span></span>
                  <span class="caption text-black">Schools</span>
                </div>
              </div>
              <div class="col-md-6">
                <div class="block-counter-1 block-counter-1-sm">
                  <span class="number"><span data-number="1039">0</span></span>
                  <span class="caption text-black">Students</span>
                </div>
              </div>
            </div>


          </div>

        </div> -->

        <!-- <div class="row mb-5">
          <div class="col-lg-6 mb-5 order-lg-2">
            <img src="images/hero_2_no-text.jpg" alt="Image" class="img-fluid">
          </div>
          <div class="col-lg-5 mr-auto align-self-center order-lg-1">
            <h3 class="text-black text-uppercase mb-4">Eğitime Tam Destek</h3>
            <p class="mb-5">Eğitime ve öğrencilerimizi destekliyoruz.</p>

            <div class="row">
              <div class="col-md-6">
                <div class="block-counter-1 block-counter-1-sm">
                  <span class="number"><span data-number="313">0</span></span>
                  <span class="caption text-black">Öğrenci</span>
                </div>
              </div>
              <div class="col-md-6">
                <div class="block-counter-1 block-counter-1-sm">
                  <span class="number"><span data-number="38">0</span></span>
                  <span class="caption text-black">Farklı Okul</span>
                </div>
              </div>
            </div>

          </div>
        </div> -->
      <!-- </div>
    </div> -->

    <div class="site-section" id="discover-section">
      <div class="container">
        <div class="row">
          <!-- Title -->
          <div class="col-12 text-center mb-12 text-center mb-5">
            <h2 class="text-black section-title ">Faaliyetlerimiz</h2>
            <p> </p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 col-lg-4 mb-4 text-center">
            <!-- <span class="flaticon-share d-block mb-3 display-3 text-secondary"></span> -->
            <span class="d-block mb-3 display-3 text-secondary">
              <img src="images/sheep.png" alt="kurban" width="90px">
            </span>
            <h3 class="text-primary h4 mb-2">Kurban</h3>
            <p>Kurban hizmeti.</p>
          </div>
          <div class="col-md-6 col-lg-4 mb-4 text-center">
            <span class="flaticon-blood d-block mb-3 display-3 text-secondary"></span>
            <h3 class="text-primary h4 mb-2">Zekat</h3>
            <p>İhtiyaç sahibi öğrenciler için zekatlarınıza talibiz.</p>
          </div>
          <div class="col-md-6 col-lg-4 mb-4 text-center">
            <span class="flaticon-food d-block mb-3 display-3 text-secondary"></span>
            <h3 class="text-primary h4 mb-2">Fitre</h3>
            <p>Fitrelerinizi Ramazan-ı şerifte ihtiyaç sahibi ailelerin iftar sofralarıyla buluşturun.</p>
          </div>

          <div class="col-md-6 col-lg-4 mb-4 text-center">
            <span class="flaticon-donation d-block mb-3 display-3 text-secondary"></span>
            <h3 class="text-primary h4 mb-2">Fidye</h3>
            <p>Oruç ve hac fidyeleriniz ile bir iftarlı'nın iftarını karşılayın.</p>
          </div>
          <div class="col-md-6 col-lg-4 mb-4 text-center">
            <span class="flaticon-dollar d-block mb-3 display-3 text-secondary"></span>
            <h3 class="text-primary h4 mb-2">Kumbara</h3>
            <p>Az sadaka çok belayı def eder. Her evde bir kumbara.</p>
          </div>
          <div class="col-md-6 col-lg-4 mb-4 text-center">
            <span class="flaticon-unity d-block mb-3 display-3 text-secondary"></span>
            <h3 class="text-primary h4 mb-2">İftar</h3>
            <p>İftarlarınızı ihtiyaç sahibi aileler ile buluşturuyoruz.</p>
          </div>

        </div>
      </div>
    </div>

    <!-- <div class="site-section" id="team-section">
      <div class="container"> -->
        <!-- <div class="row mb-5 justify-content-center">
          <div class="col-md-7 text-center">
              <h2 class="text-black text-uppercase section-title">Our Leadership</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut corporis, eius, eos consectetur consequuntur sit. Aut, perspiciatis, reprehenderit.</p>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 col-md-6 mb-4 mb-lg-0" data-aos="fade-up">
            <div class="block-team-member-1 text-center rounded">
              <figure>
                <img src="images/person_1.jpg" alt="Image" class="img-fluid rounded-circle">
              </figure>
              <h3 class="font-size-20 text-white">Jean Smith</h3>
              <span class="d-block font-gray-5 letter-spacing-1 text-uppercase font-size-12 mb-3">Mining Expert</span>
              <p class="px-3 mb-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque, repellat. At, soluta. Repellendus vero, consequuntur!</p>
              <div class="block-social-1">
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-facebook"></span></a>
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-twitter"></span></a>
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-instagram"></span></a>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-4 mb-lg-0" data-aos="fade-up" data-aos-delay="100">
            <div class="block-team-member-1 text-center rounded">
              <figure>
                <img src="images/person_2.jpg" alt="Image" class="img-fluid rounded-circle">
              </figure>
              <h3 class="font-size-20 text-white">Bob Carry</h3>
              <span class="d-block font-gray-5 letter-spacing-1 text-uppercase font-size-12 mb-3">Project Manager</span>
              <p class="px-3 mb-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nihil quia veritatis, nam quam obcaecati fuga.</p>
              <div class="block-social-1">
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-facebook"></span></a>
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-twitter"></span></a>
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-instagram"></span></a>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-4 mb-lg-0" data-aos="fade-up" data-aos-delay="200">
            <div class="block-team-member-1 text-center rounded">
              <figure>
                <img src="images/person_3.jpg" alt="Image" class="img-fluid rounded-circle">
              </figure>
              <h3 class="font-size-20 text-white">Ricky Fisher</h3>
              <span class="d-block font-gray-5 letter-spacing-1 text-uppercase font-size-12 mb-3">Engineer</span>
              <p class="px-3 mb-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas quidem, laudantium, illum minus numquam voluptas?</p>
              <div class="block-social-1">
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-facebook"></span></a>
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-twitter"></span></a>
                <a href="#" class="btn border-w-2 rounded primary-primary-outline--hover"><span class="icon-instagram"></span></a>
              </div>
            </div>
          </div>
        </div> -->
      <!-- </div>
    </div> -->

    <!-- <div class="site-section block-13 overlay bg-image" id="testimonials-section" data-aos="fade" style="background-image: url('images/hero_1_no-text.jpg');">
      <div class="container"> -->

        <!-- <div class="text-center mb-5">
          <h2 class="text-white text-uppercase section-title">Testimonial</h2>
        </div>

        <div class="owl-carousel nonloop-block-13">
          <div>
            <div class="block-testimony-1 text-center">

              <blockquote class="mb-4">
                <p>&ldquo;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem, fugit excepturi sapiente voluptatum nulla odio quaerat quibusdam tempore similique doloremque veritatis et cupiditate, maiores cumque repudiandae explicabo tempora deserunt consequuntur?&rdquo;</p>
              </blockquote>

              <figure>
                <img src="images/person_4.jpg" alt="Image" class="img-fluid rounded-circle mx-auto">
              </figure>
              <h3 class="font-size-20 text-white">Ricky Fisher</h3>
            </div>
          </div>

          <div>
            <div class="block-testimony-1 text-center">
              <blockquote class="mb-4">
                <p>&ldquo;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem, fugit excepturi sapiente voluptatum nulla odio quaerat quibusdam tempore similique doloremque veritatis et cupiditate, maiores cumque repudiandae explicabo tempora deserunt consequuntur?&rdquo;</p>
              </blockquote>

              <figure>
                <img src="images/person_2.jpg" alt="Image" class="img-fluid rounded-circle mx-auto">
              </figure>
              <h3 class="font-size-20 text-white">Ken Davis</h3>
            </div>
          </div>

          <div>
            <div class="block-testimony-1 text-center">
              <blockquote class="mb-4">
                <p>&ldquo;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem, fugit excepturi sapiente voluptatum nulla odio quaerat quibusdam tempore similique doloremque veritatis et cupiditate, maiores cumque repudiandae explicabo tempora deserunt consequuntur?&rdquo;</p>
              </blockquote>

              <figure>
                <img src="images/person_1.jpg" alt="Image" class="img-fluid rounded-circle mx-auto">
              </figure>
              <h3 class="font-size-20 text-white">Mellisa Griffin</h3>
            </div>
          </div>

          <div>
            <div class="block-testimony-1 text-center">
              <blockquote class="mb-4">
                <p>&ldquo;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem, fugit excepturi sapiente voluptatum nulla odio quaerat quibusdam tempore similique doloremque veritatis et cupiditate, maiores cumque repudiandae explicabo tempora deserunt consequuntur?&rdquo;</p>
              </blockquote>

              <figure>
                <img src="images/person_3.jpg" alt="Image" class="img-fluid rounded-circle mx-auto">
              </figure>
              <h3 class="font-size-20 text-white">Robert Steward</h3>
            </div>
          </div>


        </div> -->

      <!-- </div>
    </div> -->

    <div class="site-section" id="blog-section">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-7 text-center mb-5 text-center">
            <h2 class="text-black section-title">Güncel Faaliyetler</h2>
            <p>Yapmış olduğunuz yardımlar, bir neslin ihyasına vesile oluyor. Siz de bu yardım seferberliğine ortak olabilirsiniz.</p>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6">
            <div>
              <a @click="donation()" class="mb-4 d-block"><img src="images/kumanya-demircan.png" alt="Image" class="img-fluid rounded"></a>
              <h2><a @click="donation()">Kumanya Kampanyalarımız</a></h2>
              <p class="text-muted mb-3 text-uppercase small"><span class="mr-2">Nisan 2020</span> - <a @click="donation()" class="by">Hisar</a></p>
              <p>Kumanya yardımlarınızı ulaştırıyoruz.</p>
              <p><a @click="donation()">-</a></p>
            </div>
          </div>
          <div class="col-lg-6">
            <div>
              <a @click="donation()" class="mb-4 d-block"><img src="images/kurban-stock.png" alt="Image" class="img-fluid rounded"></a>
              <h2><a @click="donation()">Kurban</a></h2>
              <p class="text-muted mb-3 text-uppercase small"><span class="mr-2">2020</span> - <a @click="donation()" class="by">Hisar</a></p>
              <p>Yıl boyu akika, şükür ve diğer nafile kurbanlarınızı kestirebilirsiniz.</p>
              <p><a @click="donation()">-</a></p>
            </div>
          </div>

        </div>
      </div>
    </div>

    <!-- Donation -->
    <div class="site-section bg-image overlay" style="background-image: url('images/hero_1_no-text.jpg');" id="donate-section">
      <div class="container">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-6 text-center">
            <h2 class="text-white mb-4">Az sada çok belayı def eder.</h2>
            <p>
              <b>KUVEYTTÜRK DERNEK HESAP NO:</b>

              <h3>
                TR 46 0020 5000 0067 3120 6000 01 (TL) <br><br>

                TR 62 0020 5000 0067 3120 6001 01 ($) <br><br>

                TR 35 0020 5000 0067 3120 6001 02 (€) <br><br>

                Yurt Dışı Havale İçin Svit Kodu ( KTEFTRIS )
              </h3>
              <span>
                Sefaköy Kartaltepe Eğitim Ve Kültüre Hizmet Derneği
                Küçükçekmece Vergi Dairesi
                758 026 3473
              </span>
            </p>
            <p><a @click.prevent="donate()" class="btn btn-primary px-4 py-3 btn-block" style="color: #fff;">BAĞIŞ YAP</a></p>
          </div>
        </div>
      </div>
    </div>

    <div class="site-section bg-light" id="contact-section">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center mb-5">
            <h2 class="text-black section-title">İletişim</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-6 mb-5">
            <form @submit.prevent="handleSubmit" name="contact" method="POST" data-netlify="true" data-netlify-honeypot="bot-field">
              <p class="hidden">
                <label><input name="bot-field"></label>
              </p>
              <input type="hidden" name="contact" value="contact" />
              <div class="form-group row">
                <div class="col-md-6 mb-4 mb-lg-0">
                  <input type="text" class="form-control" v-model="form.name" placeholder="Adınız">
                </div>
                <div class="col-md-6">
                  <input type="text" class="form-control" v-model="form.sname" placeholder="Soyadınız">
                </div>
              </div>

              <div class="form-group row">
                <div class="col-md-12">
                  <input type="text" class="form-control" v-model="form.email" placeholder="Email adresiniz">
                </div>
              </div>

              <div class="form-group row">
                <div class="col-md-12">
                  <textarea name="" id="" class="form-control" v-model="form.message" placeholder="Mesajınız.." cols="30" rows="10"></textarea>
                </div>
              </div>
              <div class="form-group row">
                <div class="col-md-6 ml-auto">
                  <input type="submit" class="btn btn-block btn-primary text-white py-3 px-5" value="Gönder">
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>

    <Footer></Footer>

  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header, Footer
  },
  data () {
   return {
     form: {
       name: '',
       sname: '',
       email: '',
       message: ''
     }
   }
 },
  methods: {
    donate() {
      console.log(' ');
    },
    encode(data) {
      return Object.keys(data).map(key => `${encodeURIComponent(key)}=${encodeURIComponent(data[key])}`).join('&')
    },
    handleSubmit() {
      fetch('/', {
        method: 'post',
        headers: {
          'Content-Type': 'application/x-www-form-urlencoded'
        },
        body: this.encode({'form-name': 'contact', ...this.form})
      })
      .then(() => console.log('başarılı'))
      .catch(e => console.log(e))
    }
  }
}
</script>

<style media="screen">
   @import '../assets/fonts/icomoon/style.css';
   @import '../assets/css/bootstrap.min.css';
   @import '../assets/css/magnific-popup.css';
   @import '../assets/css/jquery-ui.css';
   @import '../assets/css/owl.carousel.min.css';
   @import '../assets/css/owl.theme.default.min.css';
   @import '../assets/css/bootstrap-datepicker.css';
   @import '../assets/fonts/flaticon/font/flaticon.css';
   @import '../assets/css/aos.css';
   @import '../assets/css/style.css';

   .dernek-photo {
     width: 100%;
     box-shadow: 1px 1px 2px rgba(0, 0, 0, .1);
     border: 2px solid #eee;
     @media (min-width: 768px) {
        /* max-width: 400px !important; */
     }
   }
</style>
