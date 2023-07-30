
<template>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
  <div class="home">
    <div class="content">
      <div class="image"><img src="../assets/images/logo.png" alt=""></div>
      <div class="text"><p>SHOES SHOP</p></div>
      <div class="wrapper">
      <nav>
        <RouterLink to="/"><i class="fas fa-home"></i> Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/product">Product</RouterLink>
        <RouterLink to="/Checkout">Checkout</RouterLink>
        <RouterLink to="/cart"><i class="fas fa-shopping-cart"></i> Cart</RouterLink>
      </nav>
    </div>
    <div class="icon">
      <form class="form">
        <label for="search">
            <input class="input" type="text" required="" placeholder="Search shoes" id="search">
            <div class="fancy-bg"></div>
            <div class="search">
                <svg viewBox="0 0 24 24" aria-hidden="true" class="r-14j79pv r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-4wgw6l r-f727ji r-bnwqim r-1plcrui r-lrvibr">
                    <g>
                        <path d="M21.53 20.47l-3.66-3.66C19.195 15.24 20 13.214 20 11c0-4.97-4.03-9-9-9s-9 4.03-9 9 4.03 9 9 9c2.215 0 4.24-.804 5.808-2.13l3.66 3.66c.147.146.34.22.53.22s.385-.073.53-.22c.295-.293.295-.767.002-1.06zM3.5 11c0-4.135 3.365-7.5 7.5-7.5s7.5 3.365 7.5 7.5-3.365 7.5-7.5 7.5-7.5-3.365-7.5-7.5z"></path>
                    </g>
                </svg>
            </div>
            <button class="close-btn" type="reset">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path>
                </svg>
            </button>
        </label>
      </form>
    </div>
    <div class="log">
        <form action="">
          <button>Login</button>
        </form>
    </div>
  </div>
    <div class="main">
      <div class="box"><img src="../assets/images/shop.png.jpg" alt=""></div>
    </div>
    <div class="sub_main">
      <div class="sub_a">
        <div class="boxa"><img src="../assets/images/image1.jfif" alt=""></div>
        <div class="boxa"><img src="../assets/images/image2.png" alt=""></div>
        <div class="boxa"><img src="../assets/images/image3.webp" alt=""></div>
        <div class="boxa"><img src="../assets/images/image4.jpg" alt=""></div>
      </div>
    </div>
    <div class="text_a">
      <div class="text1">
        <p>Model: Jordan</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
    </div>
    <div class="sub_main">
      <div class="sub_a">
        <div class="boxa"><img src="../assets/images/image5.jpg" alt=""></div>
        <div class="boxa"><img src="../assets/images/image6.jpg" alt=""></div>
        <div class="boxa"><img src="../assets/images/image7.jpg" alt=""></div>
        <div class="boxa"><img src="../assets/images/image8.jfif" alt=""></div>
      </div>
    </div>
    <div class="text_a">
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
    </div>
    <div class="sub_main">
      <div class="sub_a">
        <div class="boxa"><img src="../assets/images/image21.webp" alt=""></div>
        <div class="boxa"><img src="../assets/images/image22.jpg" alt=""></div>
        <div class="boxa"><img src="../assets/images/image23.webp" alt=""></div>
        <div class="boxa"><img src="../assets/images/image4.jpg" alt=""></div>
      </div>
    </div>
    <div class="text_a">
      <div class="text1">
        <p>Model: Jordan</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
    </div>
    <div class="sub_main">
      <div class="sub_a">
        <div class="boxa"><img src="../assets/images/image17.webp" alt=""></div>
        <div class="boxa"><img src="../assets/images/image18.jpg" alt=""></div>
        <div class="boxa"><img src="../assets/images/image19.webp" alt=""></div>
        <div class="boxa"><img src="../assets/images/image24.webp" alt=""></div>
      </div>
    </div>
    <div class="text_a">
      <div class="text1">
        <p>Model: Jordan</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <RouterLink to="/product"><button style="margin-left: 200px;"><i class="fas fa-shopping-cart"></i> Buy</button></RouterLink>
      </div>
    </div>
    <footer>
        <div class="footer_box">
          <div class="images"><img src="../assets/images/logo.png" alt=""></div>
                <p style="margin-left: 8px; color: #FF3399; font-weight: bold; font-size: 20px;">SHOSE SHOP</p>
                <span>​© រក្សា​សិទ្ធិ​គ្រប់​យ៉ាង​ដោយ​ Sabay ឆ្នាំ​២០១៦</span><br>
                <a href="" style="color: aliceblue;">គោលការណ៍​ភាព​ឯកជន | Privacy Policy</a><br>
                <span>អាសយដ្ឋាន <br>
                    អគារ​លេខ ៣០៨ មហាវិថីព្រះមុន្នីវង្ស
                    សង្កាត់បឹងរាំង ខណ្ឌដូនពេញ
                </span>
            </div>
            <div class="footer_box">
                <h2 style="color: aliceblue;">អំពីយើង</h2>
                <span>
                    SHOES SHOP យើងខ្ញុំគឺជាហាងដែលមានទុកចិត្តក្នុងការប្រើប្រាស់និង​ឈាន​មុខ​គេ​នៅ​កម្ពុជា។ ព័ត៌មាន​បន្ថែម<br>
                    ផលិត​ផល​ សេវាកម្ម និង​ ​ធានាគុណភាព។
                </span>
                <h3>Payment</h3>
                <div class="payment" style="color: orange;">
                  <div class="box2"><img src="../assets/images/aba.png" alt=""></div>
                  <div class="box2"><img src="../assets/images/acilida.jpg" alt=""></div>
                  <div class="box2"><img src="../assets/images/wing.png" alt=""></div>
                </div>
            </div>
            <div class="footer_box" style="align-items: center;">
                <h2 style="color: aliceblue;">ជួបគ្នានៅបណ្តាញសង្គម</h2>
                <nav>
                    <i class="fab fa-facebook"></i>
                    <i class="fab fa-telegram"></i>
                    <i class="fab fa-youtube"></i>
                    <i class="fab fa-instagram"></i>
                </nav> <br>
                <span>
                    ទំនាក់ទំនង <br>
                    tychhenglong1@gmail.com <br>
                    097 27 7777 <br>
                </span>
            </div>
      </footer>
  </div>
</template>

  
