<template>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
  <div class="product">
    <div class="Container">
        <div class="contents">
          <div class="images"><img src="../assets/images/logo.png" alt=""></div>
            <div class="texts">SHOES SHOP</div>
            <div class="wrapper">
              <nav>
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About</RouterLink>
                <RouterLink to="/product">Product</RouterLink>
                <button @click="$emit('checkout')">Go to checkout</button>
              </nav>
            </div>
            <div class="icons">
              <span><i class="fas fa-search"></i></span>
              <p><i class="fas fa-shopping-cart"></i></p>
              <input type="text" placeholder="Search product">
              <nav>Cart(0)</nav>
            </div>
        </div>
        <div class="mains">
          <div class="sub-box1">
            <RouterLink to="/"><a href="">Home</a>></RouterLink>
            <a href="">Nike</a>
          </div>
          <div class="sub-box2">
            <div class="box-left">
              <div class="goods">
                <div class="goods-a">
                  <img src="../assets/images/image1.jfif" alt="">
                </div>
                <div class="goods-b">
                  <div class="goods1"><img src="../assets/images/shoes1.jfif" alt=""></div>
                  <div class="goods1"><img src="../assets/images/shoes2.jfif" alt=""></div>
                  <div class="goods1"><img src="../assets/images/shoes3.jfif" alt=""></div>
                  <div class="goods1"><img src="../assets/images/shoes4.jfif" alt=""></div>
                </div>
              </div>
            </div>
            <div class="box-right">
              <p>Nike Dunk Hight<span>105$</span></p>
              <p>Gose Here</p>
              <hr><br>
              <div class="size">Size <span>Size Chart</span></div>
              <div class="button">
                <form action="">
                  <input type="radio" id="male" value="male" checked>
                  <label for="male">Male</label>
                  <input type="radio" id="female" value="female" style="margin-left: 12%;">
                  <label for="female">Female</label>
                </form>
              </div>
              <select name="size" id="size" style="margin-top: 13px;">
                <option value="large">Large</option>
                <option value="meduiam">Mediuam</option>
                <option value="small">Small</option>
              </select>
              <br><br><hr><br>
              Quantity <br>
              <select name="quantity" id="quantity">
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
                <!-- <option value="11">11</option>
                <option value="12">12</option>
                <option value="13">13</option>
                <option value="14">14</option>
                <option value="15">15</option>
                <option value="16">16</option>
                <option value="17">17</option>
                <option value="18">18</option>
                <option value="19">19</option>
                <option value="20">20</option> -->
              </select><br><br>
              <hr><br><br>
              <div class="button1"><button>Add to Cart</button></div><br>
              <hr><br>
              <div class="detail">
                <p>Air Jordan is a line of basketball 
                  shoes and athletic apparel produced
                  by American corporation Nike, Inc.
                </p>
              </div>
            </div>
          </div>
          <br><hr style="width: 73%; margin-left: 9%;">
          <p style="margin-left: 9%; font-size: 18px; font-family: Arial, Helvetica, sans-serif;">Related Products</p>
          <div class="sub-box3">
            <div class="tail">
              <div class="tail1"><img src="../assets/images/image10.avif" alt=""></div>
              <div class="tail1"><img src="../assets/images/image12.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image14.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image16.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image15.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image11.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image13.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image10.avif" alt=""></div>
              <div class="tail1"><img src="../assets/images/image12.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image14.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image16.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image15.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image11.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image13.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image10.avif" alt=""></div>
              <div class="tail1"><img src="../assets/images/image12.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image14.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image16.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image15.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image11.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image13.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image10.avif" alt=""></div>
              <div class="tail1"><img src="../assets/images/image12.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image14.jpg" alt=""></div>
              <div class="tail1"><img src="../assets/images/image16.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image15.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image11.webp" alt=""></div>
              <div class="tail1"><img src="../assets/images/image13.jpg" alt=""></div>
            </div>
          </div>
        </div>
      </div>
      <footer>
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

<style>
  .Container{
    width: 99%;
    height: auto;
  }
  .contents{
    width: 100%;
    height: 100px;
    background-color: 	#B0C4DE;
    display: flex;
    position: sticky;
    top: 0px;
    z-index: 999;
    align-items: center
  }
  .images{
    width: 70px;
    height: 70px;
    background-color: 	#7DFDFE;
    border-radius: 50%;
    margin-left: 10px;
  }
  .images img{
    width: 80%;
    height: 80%;
    margin: 6px;
  }
  .texts{
      font-weight: bold;
      font-size: 23px;
      width: 15%;
      height: 100%;
      margin-left: 5px;
      display: flex;
      align-items: center;
      color: #FF3399;
    }
    .wrapper{
      width: 40%;
      height: 100%;
      margin-left: 40px;
      display: flex;
      align-items: center;
  }
  .wrapper nav{
    padding: 20px;
    font-size: 20px;
    text-decoration: none;
  }
  .icons{
    position: relative;
    cursor: pointer;
  }
  .icons span i{
    font-size: 25px;
    position: absolute;
    top: 10%;
  }
  p i{
    font-size: 25px;
    position: absolute;
    left: 34px;
    top: 2%;
  }
  .icons>input{
    width: 15rem;
    height: 23px;
    padding: 2px;
    background-color: azure;
    border-radius: 10px;
    position: absolute;
    left: 75px;
    top: -4%;
    appearance: none;
    background: none;
  }
  .icons>nav{
    font-size: 25px;
    position: absolute;
    left: 340px;
    top: 2%;
  }
  .mains{
    width: 100%;
    height: 900px;
    color: orange;
    background-color: 	#C2DFFF;
    display: flex;
    flex-direction: column;
  }
  .sub-box1{
    width: 100%;
    height: 12%;
    display: flex;
    margin-left: 8%;
    margin-top: 30px;
  }
  .sub-box1 a{
    color: orange;
    font-size: 17px;
    margin: 10px;
    text-decoration: none;
    font-family: Arial, Helvetica, sans-serif;
  }
  .sub-box2{
    width: 100%;
    height: 60%;
    display: flex;
  }
  .box-left{
    width: 60%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .goods{
    width: 70%;
    height: 98%;
    background-color: 	#F5FFFA;
    border: 1px solid orange;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    -webkit-box-shadow: 0 10px 6px -6px #777;
    -moz-box-shadow: 0 10px 6px -6px #777;
     box-shadow: 0 10px 6px -6px #777;

  }
  .goods-a{
    width: 80%;
    height: 70%;
    background-color: aqua;
  }
  .goods-a img{
    width: 100%;
    height: 100%;
  }
  .goods-b{
    width: 100%;
    height: 30%;
    background-color:		#B0C4DE;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    cursor: pointer;
  }
  .goods1{
    width: 23%;
    height: 90%;
    border: 1px solid orange;
  }
  .goods1 img{
    width: 100%;
    height: 100%;
  }
  .box-right{
    width: 40%;
    height: 100%;
    font-family: Arial, Helvetica, sans-serif;
  }
  .box-right p span{
    margin-left: 29%;
    color: orange;
  }
  .size span{
    margin-left: 35%;
  }
  hr{
    width: 55%;
    float: left;
  }
  .button{
    margin-top: 9px;
  }
  .button form input{
    width: 17px;
    height: 17px;
  }
  .button form label{
    font-size: 18px;
    padding-left: 5px;
  }
  select{
    padding: 9px;
    margin-top: 5px;
    border-radius: 5px;
    cursor: pointer;
  }
  #size{
  width:200px;   
  }
  #size option{
  width:100px;   
  }
  #quantity{
  width:200px;   
  }
  #quantity option{
    width: 150px;
  }
  .button1 button{
    background-color: #1E90FF;
    width: 220px;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
    color: aliceblue;
    margin-left: 12%;
  }
  .detail{
    width: 50%;
    height: 10%;
    float: left;
  }
  .detail p{
    color: #A9A9A9;
  }
  .sub-box3{
    width: 100%;
    height: 40%;
  }
  .tail{
    width: 90%;
    height: 40%;
    background-color: #F8F8FF;
    margin-left: 9%;
    overflow: auto;
    width: 73.3%;
    height: 45%;
    display:inline-block;
  }
  .tail1{
    width: 14%;
    height: 80%;
    margin-top: 7px;
    background-color: 	#F8F8FF;
    border: 1px solid orange;
    display:inline-block;
  }
  .tail1 img{
    width: 100%;
    height: 100%;
  }
  footer{
      background-color: #FFFFF0;
      width: 100%;
      height:300px;
      display: flex;
  }
  .footer_box{
      width: 33.33%;
      height: 40%;
      margin-left: 50px;
  }
  .footer_box img{
    margin: 6px;
    width: 80%;
    height: 80%;
  }
  .footer_box .images{
    margin-top: 8px;
    margin-left: 35px;
  }
  .footer_box a{
      color: black;
      text-decoration: none;
  }
  .footer_box h2{
      color: black;
  }
  .footer_box nav i{
      font-size: 25px;
      padding: 5px;
  }
  .footer_box p{
      display: flex;
  }
  .footer_box p img{
      width: 40px;
      padding: 5px;
  }
</style>
