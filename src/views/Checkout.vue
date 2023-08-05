<template>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
  <div class="checkout">
    <div class="check-left">
      <p>Cart> Customer information> Shiping information</p>
      <hr style="width: 90%;"><br>
      <p>Customer information<span style="padding-left: 24%; color: rgb(156, 152, 152);">Already have an account? <span style="color: blue;">Edit</span></span></p>
      <div class="email">
        <input type="email" placeholder="Enter email">
      </div><br>
      <hr style="width: 90%;"><br>
      <p>Shiping Address</p>
      <div id="information">
        <input type="first" placeholder="First name">
        <input type="last" placeholder="Last name">
        <input type="company" placeholder="Company (Optional))">
        <input type="address" placeholder="Address">
        <input type="apt" placeholder="Apt (Optional)">
        <div id="country">
          <select name="" id="">
            <option value="cambodia">Cambodia</option>
            <option value="english">English</option>
            <option value="Thailand">Thailand</option>
            <option value="vietnam">Vietnam</option>
            <option value="china">China</option>
          </select>
        </div>
        <div id="state">
          <select name="" id="">
            <option value="cambodia">Phnom Penh</option>
            <option value="english">USA</option>
            <option value="Thailand">Bangkok</option>
            <option value="vietnam">Hanoy</option>
            <option value="china">Hong kong</option>
          </select>
        </div><br>
        <hr style="width: 90%;"><br>
        <RouterLink to="/cart" style="text-decoration: none; color: rgb(166, 161, 161);">Back to Cart</RouterLink>
        <div class="ship">
          <button>Continue to shiping</button>
        </div>
      </div>
    </div>
    <div class="check-right">
      <h3 style="padding-left: 10%;">Sumuray(item1)</h3>
      <div class="check-ship">
        <table>
          <tr>
            <td style="padding-left: 8px;">Subtotal</td>
            <td style="padding-left: 65%;">$15.00</td>
          </tr>
          <tr>
            <td style="padding-left: 8px;">Shiping</td>
            <td style="padding-left: 65%;">$1</td>
          </tr><tr>
            <td style="padding-left: 8px;">Est Taxes</td>
            <td style="padding-left: 65%;">$0.50</td>
          </tr>
        </table>
        <hr style="width: 90%;">
        <p style="padding-left: 11px;">Gift Card or Discount Code</p>
        <div class="card">
          <input type="text">
          <button>Apply</button>
        </div>
        <hr style="width: 90%;">
        <span style="padding-left: 10px;">Total</span>
        <span style="padding-left: 54%; margin-top: 10%;">$16.50</span>
      </div>
    </div>
  </div>
  <div id="pay">
      <div class="left-site">
        <div class="message">
          <p>Cart > Customer Information > Shipping information > Payment Method</p><hr>
          <p>Shipping Address 12 Waldo Point Road, Mishauken, Ny 11200</p><hr>
          <p>Shipping Method USP Ground, $16.50</p><hr>
        </div>
        <div id="method">
          <b style="padding-top: 10%;">Payment</b>
          <img src="../assets/images/Discover.png" alt="">
          <img src="../assets/images/visa.png" alt="">
        </div><br><br>
        <div id="lock">
          <input type="cart" placeholder="Cart Number">
          <div id="icon"><i class="fas fa-lock"></i></div>
          <input type="text" placeholder="Name On Cart">
          <input type="date" placeholder="MM/YY/DD">
          <input type="text" placeholder="CW">
        </div><hr style="width: 99%;">
        <b>Billing Address</b><br><br>
        <div class="address">
          <button><input type="radio"><span>Same As Shipping Address</span></button>   
          <button><input type="radio"><span>Use A Different Billing Address</span></button>   
        </div><hr style="width: 99%;">
        <b>Remember Me</b><br><br>
        <div class="note">
          <button><input type="Checkbox"><span>Use A Different Billing Address</span></button>
        </div><hr style="width: 99%;">
        <div class="back">
          <RouterLink to="/Checkout"><p>Return to Customer Information</p></RouterLink>
          <button>Complete Order</button>
        </div>
      </div>
      <div class="check-right">
      <h3 style="padding-left: 10%;">Sumuray(item1)</h3>
      <div class="check-ship">
        <table>
          <tr>
            <td style="padding-left: 8px;">Subtotal</td>
            <td style="padding-left: 65%;">$15.00</td>
          </tr>
          <tr>
            <td style="padding-left: 8px;">Shiping</td>
            <td style="padding-left: 65%;">$1</td>
          </tr><tr>
            <td style="padding-left: 8px;">Est Taxes</td>
            <td style="padding-left: 65%;">$0.50</td>
          </tr>
        </table>
        <hr style="width: 90%;">
        <p style="padding-left: 11px;">Gift Card or Discount Code</p>
        <div class="card">
          <input type="text">
          <button>Apply</button>
        </div>
        <hr style="width: 90%;">
        <span style="padding-left: 10px;">Total</span>
        <span style="padding-left: 54%; margin-top: 10%;">$16.50</span>
      </div>
    </div>
  </div>
  <div id="pay">
      <div class="left-site">
        <div id="success">
          <div id="tick">
            <img src="../assets/images/success-icon-10.png" alt="">
          </div>
          <div id="order">
            <span style="color: rgb(159, 152, 152);">Order 112233</span><br>
            <span style="font-size: 23px;">Thank you, Chhenglong!</span>
          </div>
          <hr style="width: 100%;">
          <div class="get">
            Your Order is Comfirm.<br>
            We are accept yout order and We are getting it ready.
          </div>
          <hr style="width: 100%;">
        </div>
        <div class="customer">
            <div class="c-left">
              <h3>Your Customer Information</h3>
              <span style="font-size: 18px; font-weight: bold;">Shipping Address</span><br><br>
              <span>Chhenglong Ty</span><br>
              <a href=""> #182, 132z, Tekloak1, Toulkork, Phnom Penh</a><br><br>
              <span style="font-size: 18px; font-weight: bold;">Shipping Method</span><br><br>
              <span>UAP Ground (Estimate Ship Time of 3-6 Days)</span>
            </div>
            <div class="c-right">
              <div class="end">
                <span style="font-size: 18px; font-weight: bold;">Billing Address</span><br><br>
                <span>Chhenglong Ty</span><br>
                <a href=""> #182, 132z, Tekloak1, Toulkork, Phnom Penh</a><br><br>
                <span style="font-size: 18px; font-weight: bold;">Payment Method</span><br>
                <div id="ABA">
                  <img src="../assets/images/aba.png" alt=""><br>
                </div>              
                <span>Ending in 3217- $16.50</span>
              </div>
            </div>
          </div>
      </div>
      <div class="check-right">
      <h3 style="padding-left: 10%;">Sumuray(item1)</h3>
      <div class="check-ship">
        <table>
          <tr>
            <td style="padding-left: 8px;">Subtotal</td>
            <td style="padding-left: 65%;">$15.00</td>
          </tr>
          <tr>
            <td style="padding-left: 8px;">Shiping</td>
            <td style="padding-left: 65%;">$1</td>
          </tr><tr>
            <td style="padding-left: 8px;">Est Taxes</td>
            <td style="padding-left: 65%;">$0.50</td>
          </tr>
        </table>
        <hr style="width: 90%;">
        <p style="padding-left: 11px;">Gift Card or Discount Code</p>
        <div class="card">
          <input type="text">
          <button>Apply</button>
        </div>
        <hr style="width: 90%;">
        <span style="padding-left: 10px;">Total</span>
        <span style="padding-left: 54%; margin-top: 10%;">$16.50</span>
      </div>
    </div>
  </div>
</template>
<style>
  .checkout{
    width: 55%;
    height: 700px;
    background-color: 	#5D6D7E;
    border-radius: 8px;
    margin: 0 auto;
    display: flex;
    justify-content: space-evenly;
    font-family: Arial, Helvetica, sans-serif;
    color: orange;
  }
  .check-left{
    width: 65%;
  }
  .check-left hr{
    float: left;
  }
  .email input{
    width: 87%;
    padding: 9px;
    border-radius: 5px;
    border: none;
    margin: 2px;
  }
  .email input[type="email"]:hover{
    border: 1px solid #1b9bee;
  }
  #information input{
    width: 41.3%;
    padding: 9px;
    margin: 2px;
    border: none;
    border-radius: 5px;
  }
  #information input[type="company"] {
    width: 86.5%;
    padding: 9px;
  }
  #country select{
    width: 45%;
    padding: 9px;
    margin: 2px;
    border: none;
    border-radius: 5px;
  }
  #state select{
    width: 45%;
    padding: 9px;
    border: none;
    border-radius: 5px;
    margin: 2px;
  }
  #information input:hover{
    border: 1px solid #1b9bee;
  }
  .ship{
    position: relative;
  }
  .ship button{
    padding: 5px;
    border-radius: 5px;
    border: none;
    background-color: blue;
    color: white;
    position: absolute;
    right: 10%;
    bottom: -3px;
    cursor: pointer;
  }
  .ship button:hover{
    background-color: rgb(13, 13, 240) ;
  }
  .check-right{
    width: 27%;
    height: 45%;
    margin-top: 15px;
    background-color: 	#DCDCDC;
    padding-left: 5px;
    border-radius: 8px;
  }
  .chechk-ship{
    width: 100%;
  }
  .card input[type="text"]{
    margin-left: 24px;
    background-color: #F0F8FF;
    border: none;
    padding: 5px;
    border-radius: 3px;
    cursor: pointer;
  }
  .card button{
    width: 65%;
    margin-top: 10px;
    margin-left: 15%;
    padding: 7px;
    border-radius: 5px;
    border: none;
    background-color:  blue;
    color: white;
    cursor: pointer;
  }
  .card button:hover{
    background-color: rgb(13, 13, 240);
  }
  #pay{
    width: 55%;
    height: 700px;
    background-color:	#5D6D7E;
    color: orange;
    display: flex;
    justify-content: space-evenly;
    margin: 0 auto;
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 10px;
    margin-top: 10px;
  }
  .left-site{
    width: 60%;
    height: 100%;
  }
  .message hr{
    width: 99%;
  }
  #method img{
    float: right;
    width: 70px;
    height: 35px;
    padding: 2px;
  }
  .right-site{
    width: 40%;
    height: 100%;
  }
  #icon{
    position: relative;
  }
  #lock input{
    padding-top: 15px;
  }
  #icon i{
    position: absolute;
    right: 9px;
    bottom: 8px;
    color: black;
  }
  #lock input[type="cart"]{
    width: 96%;
    margin: 2px;
    padding: 8px;
    border-radius: 3px;
    border: none;
  }
  #lock input[type="text"]{
    padding: 9px;
    margin-top: 4px;
    width: 29%;
    margin: 2px;
    border-radius: 3px;
    border: none;
  }
  #lock input[type="date"]{
    padding: 7px;
    width: 30%;
    margin: 2px;
    border-radius: 3px;
    border: none;
  }
  .address{
    margin-top: 10px;
  }
  .address button{
    width: 100%;
    padding: 5px;
    border: none;
    border-radius: 4px;
    margin-top: 5px;
  }
  .address button input[type="radio"]{
    float: left;
    width: 17px;
    height: 17px;
  }
  .address button span{
    font-size: 15px;
    color: gray;
    float: left;
    margin-top: 3px;
  }
  .note button{
    width: 100%;
    margin-top: 10px;
    border: none;
    border-radius: 5px;
    padding: 4px;
  }
  .note button input[type="Checkbox"]{
    float: left;
    width: 17px;
    height: 17px;
  }
  .note button span{
    font-size: 16px;
    float: left;
    margin-top: 3px;
    color: gray;
  }
  .back a{
    text-decoration: none;
    color: rgb(157, 151, 151);
    cursor: pointer;
  }
  .back{
    position: relative;
  }
  .back button{
    padding: 6px;
    border: none;
    border-radius: 4px;
    width: 120px;
    position: absolute;
    right: 2px;
    top: -5px;
    color: white;
    background-color: 	#0000FF;
    cursor: pointer;
  }
  #success #tick  img{
    width: 65px;
    height: 65px;
    margin-top: 30px;
    position: relative;
  }
  #order{
    position: absolute;
    bottom: -100%;
    left: 30%;
  }
  .get{
    color: rgb(159, 152, 152);
    font-size: 16px;
  }
  .customer{
    width: 100%;
    height: 400px;
    display: flex;
  }
  .c-left{
    width: 50%;
    height: 100%;
  }
  .c-left span{
    font-size: 16px;
    color: rgb(159, 152, 152);
  }
  .c-right{
    width: 50%;
    height: 100%;
    margin-top: 11.7%;
  }
  .c-left a{
    color:#1c8fdb;
  }
  .c-right .end{
    padding-left: 13%;
  }
  .c-right a{
    color:#1c8fdb;
  }
  .end #ABA img{
    width: 69px;
    height: 40px;
  }
  .c-right span{
    color: rgb(159, 152, 152);
  }
</style>
