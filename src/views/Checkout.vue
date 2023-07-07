<template>
  <div class="checkout">
    <div class="check-left">
      <p>Cart> Customer information> Shiping information> Payment method</p>
      <hr style="width: 90%;"><br>
      <p>Customer information</p>
      <div class="email">
        <input type="email" placeholder="Enter email">
      </div><br>
      <hr style="width: 90%;"><br>
      <p>Shiping Address</p>
      <div class="information">
        <input type="first" placeholder="First name">&nbsp;
        <input type="last" placeholder="Last name">
        <input type="company" placeholder="Company (Optional))">
        <input type="address" placeholder="Address">&nbsp;
        <input type="apt" placeholder="Apt (Optional)">
        <div class="country">
          <select name="" id="">
            <option value="cambodia">Cambodia</option>
            <option value="english">English</option>
            <option value="Thailand">Thailand</option>
            <option value="vietnam">Vietnam</option>
            <option value="china">China</option>
          </select>
        </div>
        <div class="state">
          <select name="" id="">
            <option value="cambodia">Khmer</option>
            <option value="english">USA</option>
            <option value="Thailand">Bangkok</option>
            <option value="vietnam">Hanoy</option>
            <option value="china">Hong kong</option>
          </select>
        </div><br>
        <hr style="width: 90%;"><br>
        <RouterLink to="/cart" style="text-decoration: none;">Back to Cart</RouterLink>
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
            <td>Subtotal</td>
            <td style="padding-left: 57%;">$15.00</td>
          </tr>
          <tr>
            <td>Shiping</td>
            <td style="padding-left: 57%;">$1</td>
          </tr><tr>
            <td>Est Taxes</td>
            <td style="padding-left: 57%;">$0.70</td>
          </tr>
        </table>
        <hr style="width: 90%;">
        <p style="padding-left: 5px;">Gift Card or Discount Code</p>
        <div class="card">
          <input type="file">
          <button>Apply</button>
        </div>
        <hr style="width: 90%;">
        <span>Total</span>
        <span style="padding-left: 53%; margin-top: 10%;">$16.70</span>
      </div>
    </div>
  </div>
</template>

<style>
  .checkout{
    width: 55%;
    height: 700px;
    background-color: #FDF5E6;
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
  .information input{
    width: 40.5%;
    padding: 9px;
    margin: 2px;
    border: none;
    border-radius: 5px;
  }
  .information input[type="company"] {
    width: 86.5%;
    padding: 9px;
  }
  .country select{
    width: 44%;
  }
  .state select{
    width: 44%;
  }
  .information input:hover{
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
    background-color: #fff;
    padding-left: 5px;
    border-radius: 8px;
  }
  .card input[type="file"]{
    border: none;
    padding-left: 5px;
  }
  .card button{
    width: 65%;
    margin-top: 15px;
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
</style>
