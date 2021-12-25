# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Home Page:

~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Shriram Indusries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Shriram Industries Private Limited </div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us :</h1>
          <img src=	"./img/s1.jpg"  alt="Building" />
          <div class="contenttext">
            Shriram Industries Private Limited is a global leader in next-generation digital services and consulting. We enable 
            clients in more than 200 countries to navigate their digital transformation, Whcih will be very usefull for them.
            <br/>
            We have five decades of experience in managing the systems and workings of global enterprises, 
            we expertly steer our clients through their digital journey, which will be comfortable for them. We do it by enabling the enterprise 
            with an AI-powered core that helps prioritize the execution of change. We also empower the business 
            with agile digital at scale to deliver unprecedented levels of performance and customer delight. Our 
            always-on learning agenda drives their continuous improvement through building and transferring digital skills, 
            expertise, and ideas from our innovation ecosystem.


            <br />
            In Shriram Indusries Private Limited, we believe that technology should simplify businesses, not complicate them;
             it should free you, not tie you down. It is the philosophy that has been the driving force behind all our
              innovations and product developments. Since our foray into the Enterprise Applications market in the nineties, 
              our company has come a long way. Today, Shriram Indusries Private Limited is a force to reckon with in the Global Cloud Enterprise 
              Applications market. Trusted by millions of clients across verticals, we are the Number 1 choice of clients looking for 
              future-ready enterprise applications.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by Shriram.R
      </div>
    </div>
  </body>
</html>
~~~

### Product Page:

~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Shriram Indusries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Shriram Indusries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Softwares We Offer :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/h1.png" alt="product image">
                  </div>
                  <div class="itemname">Hum</div>
                  <div class="itemprice">Price: Rs.50,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">PDI</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p2.png"  alt="product image">
                  </div>
                  <div class="itemname">Progress</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/s2.jpg."  alt="product image">
                  </div>
                  <div class="itemname">Newage</div>
                  <div class="itemprice">Price: Rs.17,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/v1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Vanenburg</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/a1.png"  alt="product image">
                  </div>
                  <div class="itemname">ABBYY</div>
                  <div class="itemprice">Price: Rs.29,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/i1.png"  alt="product image">
                  </div>
                  <div class="itemname">INFINITI</div>
                  <div class="itemprice">Price: Rs.14,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/O1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">OCEAN</div>
                  <div class="itemprice">Price: Rs.35,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/k1.png"  alt="product image">
                  </div>
                  <div class="itemname">KR</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/s3.png"  alt="product image">
                  </div>
                  <div class="itemname">stypi</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/h2.png"  alt="product image">
                  </div>
                  <div class="itemname">Hour Book</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/u1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">U Lab</div>
                  <div class="itemprice">Price: Rs.30,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Shriram Indusries Private Limited, Developed by Shriram.R
      </div>
    </div>
  </body>
</html>
~~~

### People Page: 

~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Shriram Industries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Shriram Industries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Board Of Directors :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/kr1.jpg"
                   alt="People">
                  </div>
                  <div class="itemname">Mr.Keanu Reeves</div>
                  <div class="itemprice">Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/d1.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr.Dwyane Johnson</div>
                  <div class="itemprice">Co-Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/n1.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Nick Johnas</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/c1.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Chris Evans</div>
                  <div class="itemprice"> Joint-Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/t1.jpeg" alt="People">
                  </div>
                  <div class="itemname">Mr. Tom Holland</div>
                  <div class="itemprice"> CEO </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/c2.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Chris Hemsworth</div>
                  <div class="itemprice"> Chief Technical Officer </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by Shriram.R
      </div>
    </div>
  </body>
</html>
~~~

### Contact Us: 

~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Shriram Indusries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Shriram Indusries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1>
          <img src="./img/f1.jpg" alt="Building" />
          <div class="contenttext">
            Adyar Shasthri nagar, Adayar, Chennai-600028
          </div>
          <h1>Phone:</h1>
          <div class="contenttext">
              Mr.Rajesh(HR):8569741230<br/>
              Mr.Praneet(Assistant HR):9865327415
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              Sales:sales@Shriram Indusries Private Limited.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by Shriram.R
      </div>
    </div>
  </body>
</html>
~~~

### Layout CSS
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(17, 2, 2);
  color: white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px black;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-color: black;
  font-family: 'Times New Roman', Times, serif;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px ;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #59ccdbf1;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: black;
}

.menuitem a {
  text-decoration: none;
  color: #000000;
}

.content {
  display: block;
  width: 100%;
  background-image: ("./img/b1.jpg");
  font-family: cursive;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}
.homecontent h2{
  text-align: left;
}
.contenttext {
  text-align: justify;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color: white;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: white;
}
.productitem .itemprice {
  display: block;
  color: white;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #59ccdbf1;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: black;
}
~~~

## OUTPUT:

### Home Page:

![output](home.png)

### Product Page:

![output1](product.png)

### People Page:

![output2](people.png)

### Contact Us:

![output3](contact.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
