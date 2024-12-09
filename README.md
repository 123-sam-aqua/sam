<html>
<head>
    <title>Driving School</title>
    <link rel="stylesheet" href="task.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <header> 
        <h1>SL Driving School</h1> 
    </header>
    
 <ul>
    <li><a href="abct.html">Breakdown</a></li>
    <li><a href="Insurance">Insurance</a></li>
    <li><a href="Driving school">Drivingschool</a></li>
    <li><a href="Travel">Travel</a></li>
 </ul>    

 <div class="container text-center">
    <div class="row">
      <div class="col">
        <h2>About Us</h2>
        Welcome to AA Driving School, your trusted partner on the road to becoming a skilled, confident, and responsible driver. With years of experience and a team of professional instructors, we are dedicated to providing the highest quality driver education.
        At SL Driving school, we believe that driving is more than just a skill—it's a responsibility. That’s why our expert instructors focus not only on teaching the basics of driving but also on promoting safe driving practices and instilling good habits that will keep you safe on the road for years to come.
      </div>
      <div class="col">
        <h2>Our Services</h2>
        Our mission is simple: to teach safe driving practices that will last a lifetime. Whether you're a new driver, a teenager preparing for your first license, or an adult looking to improve your driving skills, we offer a variety of courses tailored to meet your needs.. Our expert instructors are dedicated to providing top-notch driving lessons tailored to your individual needs.  Whether you're a first-time driver or looking to improve your skills, our expert instructors are here to provide you with the best training experience. 
      </div>
      
    </div>
  </div>
<br></br>
<h2>Contact Us</h2>
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>

  <label for="message">Message:</label>
  <textarea id="message" name="message"></textarea><br><br>

  <input type="submit" value="Submit">
</form>
<br>
</main>
<footer>
    <p>&copy; 2023 My Website | All Rights Reserved</p>
  </footer>
</body>
</html>

CSS

header {
 background-color: #888080;
 text-align: center;
 padding: 10px;
}


li {
    display: inline;
}

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #0c0d04;
}
  
  li {
    float: left;
  }
  
  li a {
    display: block;
    color: rgb(255, 255, 255);
    text-align: center;
    padding: 8px;
    text-decoration: none;
  }

  footer {
    background-color: #888080;
    text-align: center;
    padding: 10px;
  }

