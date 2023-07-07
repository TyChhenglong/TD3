<template>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
  <div class="product">
    <div class="Container">
        <div class="contents">
          <div class="image"><img src="../assets/images/logo.png" alt=""></div>
            <div class="texts">SHOES SHOP</div>
            <div class="wrapper">
              <nav>
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About</RouterLink>
                <RouterLink to="/product">Product</RouterLink>
                <RouterLink to="/cart">Cart</RouterLink>
                <RouterLink to="/Checkout">Checkout</RouterLink>
              </nav>
            </div>
            <div class="icon" style="margin-top: 1px;">
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
              <div class="shiping">
                <p>Nike Dunk Hight<span>105$</span></p>
                <p>Gose Here</p>
                <hr><br>
                <div class="size">Size <span>Size Chart</span></div>
                <div class="button">
                    <input type="radio">Man
                    <input type="radio" style="margin-left: 22%;" >Woman
                </div>
                <select name="size" id="size" style="margin-top: 1px;">
                  <option value="large">Large</option>
                  <option value="meduiam">Mediuam</option>
                  <option value="small">Small</option>
                </select>
                <br><br><hr><br>
                Quantity <br>
                <div class="option">
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
                </select>
                </div>
                <br><br>
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
      <div class="footer">
          <div class="footer_box">
          <div class="image"><img src="../assets/images/logo.png" alt=""></div>
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
                <h3>Payment</h3>
                <div class="payment" style="color: orange;">
                  <div class="box2"><img src="../assets/images/aba.png" alt=""></div>
                  <div class="box2"><img src="../assets/images/acilida.jpg" alt=""></div>
                  <div class="box2"><img src="../assets/images/wing.png" alt=""></div>
                </div>
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
      </div>    
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
    background-color: #a3bde0;
    display: flex;
    position: sticky;
    top: 0px;
    z-index: 999;
    align-items: center
  }
  .image{
    width: 70px;
    height: 70px;
    background-color: 	cadetblue;
    border-radius: 50%;
    margin-left: 10px;
    margin-bottom: 12px;
  }
  .image img{
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
/* this is a recreation of twitter search in css */
.icon.form {
  --input-text-color: black;
  --input-bg-color: #fff;
  --focus-input-bg-color: transparent;
  --text-color: #949faa;
  --active-color: #1b9bee;
  --width-of-input: 300px;
    height: 45px;
  --inline-padding-of-input: 1rem;
  --gap: 0.9rem;
  cursor: pointer;
}
/* form style */
.icon .form {
  font-size: 0.9rem;
  display: flex;
  gap: 0.5rem;
  align-items: center;
  width: var(--width-of-input);
  position: relative;
  isolation: isolate;
}
/* a fancy bg for showing background and border when focus. */
.fancy-bg {
  position: absolute;
  width: 100%;
  inset: 0;
  background: var(--input-bg-color);
  border-radius: 30px;
  height: 100%;
  z-index: -1;
  pointer-events: none;
  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
}
/* label styling */
label {
  width: 100%;
  padding: 0.8em;
  height: 40px;
  padding-inline: var(--inline-padding-of-input);
  display: flex;
  align-items: center;
}

.search,.close-btn {
  position: absolute;
}
/* styling search-icon */
.search {
  fill: var(--text-color);
  left: var(--inline-padding-of-input);
}
/* svg -- size */
svg {
  width: 17px;
  display: block;
}
/* styling of close button */
.close-btn {
  border: none;
  right: var(--inline-padding-of-input);
  box-sizing: border-box;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  padding: 0.1em;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background: var(--active-color);
  opacity: 0;
  visibility: hidden;
}
/* styling of input */
.input {
  color: var(--input-text-color);
  width: 100%;
  margin-inline: min(2em,calc(var(--inline-padding-of-input) + var(--gap)));
  background: none;
  border: none;
}

.input:focus {
  outline: none;
}

.input::placeholder {
  color: var(--text-color)
}
/* input background change in focus */
.input:focus ~ .fancy-bg {
  border: 1px solid var(--active-color);
  background: var(--focus-input-bg-color);
}
/* search icon color change in focus */
.input:focus ~ .search {
  fill: var(--active-color);
}
/* showing close button when typing */
.input:valid ~ .close-btn {
  opacity: 1;
  visibility: visible;
}
/* this is for the default background in input,when selecting autofill options -- you can remove this code if you do not want to override the browser style.  */
input:-webkit-autofill,
input:-webkit-autofill:hover,
input:-webkit-autofill:focus,
input:-webkit-autofill:active {
  -webkit-transition: "color 9999s ease-out, background-color 9999s ease-out";
  -webkit-transition-delay: 9999s;
}
  .mains{
    width: 100%;
    height: 900px;
    color: orange;
    background-color: #B0C4DE;
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
  }
  .goods-a img{
    width: 100%;
    height: 100%;
  }
  .goods-b{
    width: 100%;
    height: 30%;
    background-color:		#B0C4DE;
    border-radius: 7px;
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
  .shiping{
    width: 350px;
    height: 100%;
    padding-left: 10%;
    background-color: 	#FDF5E6;
    border: 1px solid black;
    border-radius: 7px;
  }
  .box-right p span{
    margin-left: 29%;
    color: orange;
  }
  .size span{
    margin-left: 35%;
  }
  hr{
    width: 73%;
    float: left;
  }
  .button{
    width: 300px;
    height: 60px;
    padding-top: 15px;
  }
  .button input{
    width: 13px;
    height: 13px;
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
    margin-left: 6%;
    border: none;
  }
  .button1 button:hover{
    background-color: #2d8eef;
  }
  .detail{
    width: 75%;
    height: 10%;
    float: left;
  }
  .detail p{
    color: #A9A9A9;
    font-size: 13px;
  }
  .sub-box3{
    width: 100%;
    height: 350px;
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
    height: 75%;
    margin-top: 7px;
    background-color: 	#F8F8FF;
    border: 1px solid orange;
    display:inline-block;
  }
  .tail1 img{
    width: 100%;
    height: 100%;
  }
  .footer{
      background-color: #FFFFF0;
      width: 100%;
      height:300px;
      display: flex;
  }
  .footer .footer_box{
      width: 33.33%;
      height: 40%;
      margin-left: 50px;
  }
  .footer .footer_box img{
    margin: 6px;
    width: 80%;
    height: 80%;
  }
  .footer .footer_box .image{
    margin-top: 10px;
    margin-left: 35px;
    border-radius: 50%;
    padding: 2px;
    background-color: cadetblue;
  }
  .footer .footer_box a{
      color: black;
      text-decoration: none;
  }
  .footer.footer_box h2{
      color: black;
  }
  .payment{
    width: 250px;
    height: 50px;
    display: flex;
    justify-content: space-between;
  }
  .box2{
    width: 32%;
    height: 100%;
  }
  .box2 img{
    width: 100%;
    height: 100%;
  }
  .footer.footer_box nav i{
      font-size: 25px;
      padding: 5px;
  }
  .footer.footer_box p{
      display: flex;
  }
  .footer.footer_box p img{
      width: 40px;
      padding: 5px;
  }
</style>
