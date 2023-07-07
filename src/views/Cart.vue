<template>
    <div class="cart">
      <div class="left-cart">
        <h3 style="color: blue;">Your Cart</h3>
        <hr style="width: 100%;">
        <div class="main-cart"><br>
          <span style="margin-left: 5px; color: orange;">Item</span>
          <span style="margin-left: 50%; color: orange;">Quantities</span>
          <span style="margin-left: 21%; color: orange;">Price</span>
        </div>
        <hr style="width: 100%;">
          <div class="sub-cart">
            <table>
              <tr>
                <td><img src="../assets/images/image1.jfif" alt=""></td>
                <td>
                  <div class="selection">
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
                </td>
                <td style="padding-left: 3%; color: orange;">$15.00</td>
              </tr>
              <tr>
                <td style="padding: 3%; color: orange;">
                  Nike Drunk High <br>
                  Size: Meduiam <br>
                  Gender: Man
                </td>
              </tr>
            </table><br>
            <hr style="width: 100%;">
            <div class="subtotal" style="float: right; color: orange;">
              SubTotal $15.00
            </div>
            <hr style="width: 100%;">
        </div>
      </div>
      <div class="right-cart">
        <div class="cart-box">
          <b style="padding: 10px; font-size: 20px;">Sumuray(1item)</b>
          <br><br>
          <table>
            <tr>
              <td>Subtotal</td>
              <td style="padding-left: 70%;">$15.00</td>
            </tr>
            <tr>
              <td>Shiping</td>
              <td style="padding-left: 70%;">$1</td>
            </tr>
            <tr>
              <td>Tax</td>
              <td style="padding-left: 70%;">$0.50</td>
            </tr>
          </table>
          <hr style="width: 87%; float: left;">
          <table>
            <tr>
              <td>Total</td>
              <td style="padding-left: 115%;">$16.50</td>
            </tr>
          </table>
          <div class="button">
            <button>Checkout</button>
          </div>
        </div>
      </div>
    </div>
  </template>
<style>
  .cart{
    width: 58%;
    height: 700px;
    background-color: 	#FDF5E6;
    color: orange;
    display: flex;
    justify-content: center;
    justify-content: space-evenly;
    margin: 0 auto;
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 10px;
  }
  .left-cart{
    width: 55%;
    height: 100%;
    color: black;
  }
  .main-cart{
    width: 100%;
  }
  .sub-cart table tr td img{
    width: 230px;
    height: 200px;
    border-radius: 5px;
    -webkit-box-shadow: 0 10px 6px -6px #777;
    -moz-box-shadow: 0 10px 6px -6px #777;
    box-shadow: 0 10px 6px -6px #777;
  }
  .selection select{
    width: 100px;
    height: 33px;
  }
  .right-cart{
    width: 40%;
    height: 100%;
    display: flex;
    justify-content: center;
  }
  .cart-box{
    width: 60%;
    height: 35%;
    margin: 10%;
    background-color: #fff;
    border-radius: 7px;
  }
  .button button{
    padding: 8px;
    width: 60%;
    border-radius: 6px;
    margin-top: 10px;
    margin-left: 6%;
    border: none;
    background-color: blue;
    color: white;
    cursor: pointer;
  }
  table tr td{
    padding-left: 5px;
  }
</style>
  