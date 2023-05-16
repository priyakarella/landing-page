# landing-page
<!DOCTYPE html>
<html>
<head>
  <title>Toyland - Your One-Stop Toy Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    .header {
            background-color:rgba(89, 74, 255, 0.6)
            padding: 40px;
      text-align: center;
           background-color:rgba(168, 220, 255, 1);
    }
    
    .header h1 {
      color: #333333;
      margin: 0;
    }
    
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
      background-color:rgba(89, 74, 255, 0.6);
    }
    
    .column {
      width: 300px;
      margin: 10px;
      padding: 20px;
      background-color:rgba(168, 220, 255, 1);
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
      text-align: center;
    }
    
    .section {
       background-color:rgba(168, 220, 255, 1);
      padding: 40px;
      text-align: center;
    }
    
    .section h2 {
      color: #333333;
    }
    
    .section img {
      max-width: 100%;
      margin-top: 20px;
      border-radius: 5px;
    }
    
    .footer {
      background-color: #333333;
      padding: 20px;
      text-align: center;
    }
    
    .footer p {
      color: #FFFFFF;
      margin: 0;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Welcome to Toyland</h1>
  </div>
  
  <div class="container">
    <div class="column">
      <h2>Popular Toys</h2>
      <img src="C:\Users\lakshmi\Downloads\toy.jpg" alt="Toy 1">
      <p>Description of Toy 1</p>
    </div>
    
    <div class="column">
      <h2>New Arrivals</h2>
      <img src="C:\Users\lakshmi\Downloads\toy3.jpg" alt="Toy 2">
      <p>Description of Toy 2</p>
    </div>
    
    <div class="column">
      <h2>Special Offers</h2>
      <img src="C:\Users\lakshmi\Downloads\toy4.jpg" alt="Toy 3">
      <p>Description of Toy 3</p>
    </div>
  </div>
  
  <div class="section">
    <h2>About Us</h2>
    <p> This section contains details about the Toyland.</p>
    <img src="C:\Users\lakshmi\Downloads\toy2.jpg" alt="Toy 4">
  </div>
  
  <div class="footer">
    <p>&copy; 2023 Toyland. All rights reserved.</p>
  </div>
</body>
</html>
