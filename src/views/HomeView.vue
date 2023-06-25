
<template>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
  <div class="home">
    <div class="content">
      <div class="image"><img src="../assets/images/logo.png" alt=""></div>
      <div class="text"><p>SHOES SHOP</p></div>
      <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/product">Product</RouterLink>
        <button @click="$emit('checkout')">Go to checkout</button>
      </nav>
    </div>
    <div class="icon">
      <span><i class="fas fa-search"></i></span>
      <p><i class="fas fa-shopping-cart"></i></p>
      <input type="search" placeholder="Search product" id="search">
      <nav>Cart(0)</nav>
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
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
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
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
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
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
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
        <button style="margin-left: 65%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: SOB</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
      <div class="text1">
        <p>Model: Nike</p>
        <span>Price: 10$</span>
        <button style="margin-left: 70%;">Buy</button>
      </div>
    </div>
    <footer style="margin-top: 3%;">
        <div class="footer_box">
          <div class="images"><img src="../assets/images/logo.png" alt=""></div>
                <p style="margin-left: 8px; color: #FF3399; font-weight: bold; font-size: 20px;">SHOSE SHOP</p>
                <span>​© រក្សា​សិទ្ធិ​គ្រប់​យ៉ាង​ដោយ​ Sabay ឆ្នាំ​២០១៦</span><br>
                <a href="">គោលការណ៍​ភាព​ឯកជន | Privacy Policy</a><br>
                <span>អាសយដ្ឋាន <br>
                    អគារ​លេខ ៣០៨ មហាវិថីព្រះមុន្នីវង្ស
                    សង្កាត់បឹងរាំង ខណ្ឌដូនពេញ
                </span>
            </div>
            <div class="footer_box">
                <h2>អំពីយើង</h2>
                <span>
                    SHOES SHOP យើងខ្ញុំគឺជាហាងដែលមានទុកចិត្តក្នុងការប្រើប្រាស់និង​ឈាន​មុខ​គេ​នៅ​កម្ពុជា។ ព័ត៌មាន​បន្ថែម<br>
                    ផលិត​ផល​ សេវាកម្ម និង​ ​ធានាគុណភាព។
                </span>
            </div>
            <div class="footer_box" align="center">
                <h2>ជួបគ្នានៅបណ្តាញសង្គម</h2>
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
  
