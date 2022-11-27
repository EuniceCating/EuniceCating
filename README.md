<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

body {
  font-family: Consolas, monaco, monospace;
  color: #0f82ef;
  padding: 20px;
    background-image: url('bg.gif');
    background-position: center center;
    background-attachment: fixed;
    background-size: cover;
    background-repeat: no-repeat;
   
}

.header {
  overflow: hidden;
  background-color: #f1f1f1;
  padding: 20px 10px;
}

.header a {
  float: left;
  color: #0f82ef;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

h1, h2, h3, h4, h5, h6 {
    
color: #0f82ef;
text-align: center;
}
p {
background-color:white;
text-align: center;

}

.header a.logo {
  font-size: 25px;
  font-weight: bold;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: dodgerblue;
  color: white;
}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  .header-right {
    float: none;
  }
}

.column2 {
    float: left;
    width: 32%;
    padding: 5px;
}

/* Clearfix (clear floats) */
.row2::after {
    content: "";
    clear: both;
    display: table;
}


.header2 {
    text-align: center;
    background-color: white;
}

input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
}

input[type=submit] {
    background-color: #0f82ef;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: #45a049;
}

.container2 {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
}


.footer {
    font-size: 18px; 
   width: 100%;
   background-color: white;
   text-align: center;
}
</style>
</head>
<body>

<div class="header">
  <a href="#default" class="logo">Welcome to My Personal Website</a>
  <div class="header-right">
    <a class="active" href="#about">About</a>
    <a href="#contact">Contact</a>
  </div>
</div>
<br>

   
    
<div class="row2" id="about">
  <div class="column2">
    <img src="3.jpg" style="height: 500px;" alt="Avatar">
  </div>

    <div class="column2">
    <img src="5.jpg" style="height: 500px;" alt="Avatar">
  </div>



      <div class="column2">
    <img src="4.jpg" style="height: 500px;" alt="Avatar">
  </div>
</div>

      <h2 style="background-color: white;">My name is Eunice Stephanie Claire Cating, 20 years old I live in San Jose Sico Batangas City my hobbies are playing volley, play music and watching kdrama and I graduated in paharang Integrated School.And now I currently taking (BSIT) in Batangas States University The National Engineering University</h2>


    



<hr>

<br>
<br>
<h2 id="contact">Contact</h2>
<div class="container2">
  <form action="https://www.w3schools.com/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">


    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>

<div class="footer">
  <p> 2022 | Eunice</p>
</div>
</body>

<!-- Mirrored from www.w3schools.com/howto/tryit.asp?filename=tryhow_css_sidenav_fixed2 by HTTrack Website Copier/3.x [XR&CO'2014], Mon, 30 Jul 2018 02:09:39 GMT -->
</html> 
