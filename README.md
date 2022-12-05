
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="styles.css" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css" />
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    </head>
  <body>
    <div id="blank"></div>
  <!--header-->
    <header id="header">
      <img src="https://cdn.shopify.com/s/files/1/0724/4451/files/Logo_750_1000x.png?v=1614310439" alt="Hampstead Logo" id="header-img" >
      <nav id="nav-bar">
        <ul>
          <li><a class="nav-link" href="#blank">HOME</a></li>
          <li><a  class="nav-link" href="#info">ABOUT</a></li>
          <li><a class="nav-link" href="#others">OTHER PRODUCTS</a></li>
          <li><a class="nav-link" href="#contact-us">CONTACT US</a></li>
          </ul>
        </nav>
      <div id="social-icons">
        <a href="https://www.facebook.com/hampsteadtea">
        <i class="fab fa-facebook-f"></i>
        </a>
        <a href="https://www.instagram.com/hampsteadtea/">
        <i class="fab fa-instagram"></i>
        </a>
        <a href="https://twitter.com/hampsteadtea">
        <i class="fab fa-twitter"></i>
        </a>
        </div>
      </header>
<!--MAIN-->

<main>
  <!--BANNER-->
<div id="banner">
   <p id="product-name">
HAMPSTEAD TEA ORGANIC FAIRTRADE ENGLISH BREAKFAST TEA BAGS</p>
  <div id="award">
    <img id="award-img1" src="https://reports.soilassociation.org/boom-awards/assets/3LeFevKC7D/boom-logo_2021_black_hr-980x1103.png"><h2>Awarded Best Non-Alcoholic Drink at BOOM (Best of the Organic Market) Awards 2021!</h2>
   </div>
   <div id="award-img2">
    <img src="https://cdn.shopify.com/s/files/1/0724/4451/products/hamstead_English_Breakfast_RGB_sml_600x.png?v=1626443359"></div>
</div>

<!--BUY-->
<div id="buy">
  <form id="form" action="https://www.freecodecamp.com/email-submit">
  <label>E-mail <input name="email" type="email" id="email" placeholder="Put your e-mail here." /></label>
  <a href="https://www.freecodecamp.com/email-submit"><input type="submit" id="submit" /></a>
  </form>
  <form id="form2">
    <h2>£2.99</h2>
    <hr>
    <p>Size:</p>
    <p><span id="size">20 Tea Bags</span><p><br>
    <input type="radio" name="plan" /> One-time purchase £2.99
    <br><br><input type="radio" name="plan" /> Subscribe & save 10% £2.69
    <button id="add-to-cart">ADD TO CART</button>
  </form>
</div>

<!--VIDEO BOX-->
<div id="video-box">
  <iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/pas3w6RqPXk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<!--INFO-->
<div id="info">
  <p>
Our Organic and Fairtrade English Breakfast Tea is a full-strength Black Tea that goes well with milk or cream. A robust blend of leaves from India and Africa, areas both famed for their rich succulent Teas. Our English Breakfast Tea is a bold, full-bodied blend with malty tones.<br><br>
<strong>Ingredients:</strong> Organic Fairtrade Black teas
<br><br>
<strong>Enjoy!</strong>
<br><br>
Use one Tea Bag of tea leaves per person. Brew with freshly boiled water and infuse for up to three minutes.<br><br>
<em>Our English Breakfast Tea was previously called Strong English Breakfast - the blend is still the same.</em>  </p>
</div>

</main>
<!--OTHER PRODUCTS-->
<div id="others">
  <div id="product-choices">
    <div class="item one">
      <img src="https://cdn.shopify.com/s/files/1/0724/4451/products/hamstead_Earl_Grey_RGB_webshoppicture_540x.png?v=1607614003" />
      <p>HAMPSTEAD TEA ORGANIC AND FAIRTRADE EARL GREY TEA BAGS<br><br>
<span class="price">£2.99</span>
<button>ADD TO CART</button>
  </div>
   <div class="item two">
      <img src="https://cdn.shopify.com/s/files/1/0724/4451/products/hamstead_LT_pouch_EnglishBreak_rgb_S._540x.png?v=1614230711" />
      <p>HAMPSTEAD TEA ORGANIC ENGLISH BREAKFAST LEAF TEA<br><br>
<span class="price">£2.99</span>
<button>ADD TO CART</button>
  </div>
   <div class="item three">
      <img src="https://cdn.shopify.com/s/files/1/0724/4451/products/Hampstead_Tea_Camomile_RGB_webshoppicture_540x.png?v=1607613755" />
      <p>HAMPSTEAD TEA ORGANIC CAMOMILE TEA BAGS<br><br>
<span class="price">£2.99</span>
<button>ADD TO CART</button>
  </div>
  </div>
  </div>
<footer>
  <div id="contact-us"><p><strong>CONTACT</strong><br><br>
sales@hampsteadtea.com<br><br>

Unit 34 Cranfield Innovation Centre<br>
Cranfield England<br>
MK43 0BT United Kingdom</p></div>
  </footer>
    </body>
  </html>

** end of undefined **

** start of undefined **

* {
  margin: 0 ;
  padding: 0 ;
   box-sizing: border-box ;
}

body {
 min-width: 800px ;

}

h1, label, h3, h2, p {
 font-family: sans-serif ;
}

h3, p {
  color: #636468 ;
}

#blank {
  top: 0 ;
  left: 0 ;
}

#header {
  width:100% ; 
  background-color:#e6e6e6 ;
  padding: 20px ;
  display: grid ;
  grid-template-columns: 1fr 70% 1fr ;
  align-items: end ;
  justify-items: center ;
  position: sticky ;
  top: 0 ;
  z-index: 1 ;

}

#header-img {
  width:150px;
  overflow: hidden;
  grid-column: 1 ;
}

#nav-bar {
  grid-column: 2 / 3 ;
  
}

.nav-link {
  display: inline-block;
  font-family: sans-serif ;
  margin-right: 20px;
  font-size:14px;
}

#social-icons {
  grid-column: 3 / 4 ;
}
li {
  list-style-type: none ;
  display: inline ;
}
.nav-link {
  text-decoration: none ;
  color: #636468 ;
  border-bottom: 1px solid transparent ;
  padding:5px ;
  
}

.nav-link:hover {
  border-bottom: 1px solid gray ;
  padding:5px ;
}

#social-icons a {
  text-decoration: none ;
}
.fab {
  color:gray ;
  margin-left: 10px;
}
.fab:hover {
  color:#E59CA3 ;
}

main {
  width: 80% ;
  margin: 5% auto ;
  display: grid ;
  grid-template-columns: 60% 40% ;
  grid-template-rows: 1fr 1fr ;
  row-gap: 20px ;
  object-fit: contain ;
  
}

#product-name {
  width: 100% ;
  height:100% ;
  position: absolute ;
  width: calc(100% - 275px) ;
  font-size: 1.2rem ;

}
#banner {
  grid-column: 1 / 2 ;
   /*border: 1px solid grey ;*/
  height: 400px ;
  max-height: 600px ;
  display: flex ;
  align-items: center ;
  position: relative ;
}

#award {
  background-color: #D1444C ;
  color: white ;
  width: 100% ;
  max-height:100% ;
  padding: 0 0 20px 20px ;
}

#award-img1 {
  width:100px ;
  margin-bottom: 20px ;
}

#award h2 {
  width: calc(100% - 275px) ;
}

#award-img2 {
  position: absolute ;
  height: 100% ;
  width: 100% ;

}

#award-img2 img {
  height: 100% ;
  width: 275px;
  overflow: hidden ;
  object-fit: cover ;
  position: absolute ;
  right: 0 ;

}

#buy {
  grid-column: 2 / 3 ;
  /*border: 1px solid grey ;*/
  padding: 20px ;
}

#buy label {
  color: #636468 ;
  
}
#email {
  height: 25px ;
  padding: 5px ;
  border-radius: 10px ;
  border: 1px solid grey ;
  margin-left: 5px ;
}
#submit {
  height: 25px ;
  background-color: lightgrey ;
  border: none ;
  width: 70px ;
  margin-left: 10px ;
  border-radius: 10px ;
  color: #636468 ;
}
#submit a {
  text-decoration: none ;
}
#submit:hover {
    background-color: #E6E7E8  ;

}
#form2 {
  width: 100% ;
  height: calc(100% - 20px ) ;
  border: 1px solid grey ;
  margin-top: 20px ;
  padding: 20px ;
  position: relative ;
}
form h2, hr, p {
  margin-bottom: 20px ;

}
form span {
  border: 1px solid grey ;
  padding: 10px ;
  margin-bottom: 20px ;
}
#add-to-cart {
  position: absolute;
  width: 100% ;
  bottom: 0 ;
  left: 0 ;
  background-color: #636468 ;
  border: none ;
  height: 50px ;
  font-size: 18px ;
  color: white ;
  letter-spacing: 5px ;
  overflow: hidden ;
}
#add-to-cart:hover {
  background-color: #E59CA3 ;
}

#video {
  grid-column: 1 / 2 ;
  grid-row: 2 / 3 ;
  height: 400px ;
  display: flex ;
  align-items: center ;
}
#video {
  width: 100% ;
  height: 100% ;
  object-fit: contain ;
}

/*#video {
  grid-column: 1 / 2 ;
  grid-row: 2 / 3 ;
  height: 0 ;
  position: relative ;
  padding-bottom: 56.25% ;

}
#video iframe {
  position: absolute ;
  top: 0 ;
  left: 0 ;
  width: 100% ;
  height: 100% ;
}*/

#info {
  grid-column: 2 / 3 ;
  grid-row: 2 / 3 ;
  height: auto ;
}

#info p {
  margin: 20px 0 0 20px ;
  line-height: 24px ;
}

#others {
  width: 100% ;
  background-color: #c3ddc3 ;
}

#product-choices {
  margin: 0 auto ;
  width: 80% ;
  display: grid ;
  grid-template-columns: 33.33% 33.33% 33.33% ;
  padding: 40px 0 ;
  grid-gap:10px ;
}
.item {
  width: 100% ;
  background-color: white ;
  padding: 20px ;
  position: relative ;
}

.item img {
  margin-bottom: 20px ;
}

.one {
  grid-column: 1 / 2 ;
}

.one img {
  width: 100% ;
}

.two {
  grid-column: 2 / 3 ;
}

.two img {
  width: 100% ;
}

.three {
  grid-column: 3 / 4 ;
}

.three img {
  width: 99% ;
}

.price {
  font-size: 1.4em ;
  font-weight: bold ;
}

.item button {
  margin-top: 20px ;
  left: 0 ;
  background-color: transparent ;
  width: 100% ;
  border: 1px solid #636468 ;
  height: 50px ;
  font-size: 1.1em ;
  color: #636468 ;
  letter-spacing: 2px ;

}
.item button:hover {
  color: #d1d3d4 ;
  background-color: #8d8e91;
  border: none ;
}

footer {
  width: 100% ;
  padding: 50px 0 ;
  background-color:#2f3033 ;     
}


footer  p {
 color: white ;
  text-align: center ;

}

@media only screen and (max-width: 1200px) {
  main {
  width: 80% ;
  margin: 5% auto ;
  display: grid ;
  grid-template-columns: 100% ;
  grid-template-rows: 400px 1fr 1fr 1fr ;
  row-gap: 20px ;
  
}
#banner {
  grid-column: 1 / 2 ;
  grid-row: 1 / 2 ;
}
#buy {
   grid-column: 1 / 2 ;
  grid-row: 2 / 3 ;
}
#info {
   grid-column: 1 / 2 ;
  grid-row: 3 / 4 ;
}
#video-box {
   grid-column: 1 / 2 ;
  grid-row: 4 / 5 ;
}
}

