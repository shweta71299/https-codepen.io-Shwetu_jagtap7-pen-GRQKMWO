<!DOCTYPE html>
<html lan="en" and dir="Itr">
  <head>
    
    <meta charset ="utf-8">
    <title> Interactive login form </title>
    <link rel="stylesheet" href="style2.css">
    <script src ="login2.js"> </script>
    
  </head>
  
  <body>
  
    <form class="box" action ="login.html" method="POST">
      <h1>
      
        Login
        
      </h1>
      
     <input type="text" name="" placeholder="Enter Username" id="Username">
        <input type="Password" name="" placeholder="Enter Password" id="Password">
  <input type="Submit" name="" value="Login" onclick ="validate()" >
  
  </form>
  
  </body>
  
  </html>
  
  
  
  
  body{
  margin : 0;
  padding : 0;
  font-family : sans-serief;
  background : url(back.jpg);
  background-size : cover;
  background: url(back.jpg);
  background size : cover;
}
.box{
  width : 300px;
  padding : 30px;
  position : absolute;
  top : 50%;
  left : 50%;
  transform : translate(-50%,-50%);
  background : rgba(0,0,00.4);
  text-align : center;
  }
.box h1
{
  color : white;
  text-transform : uppercase;
  font-weight : 700;
  }
.box input[type="text"],.box input[type="password"]
{
  border : 0;
  background : none;
  display : block;
  margin : 20px auto;
  text-align : centre;
  border : 3px solid #0367fd;
  padding : 14px 10px;
  width : 220px;
  outline : none;
  color : white;
  border-radius : 24px;
  transition : 0.25px;
  }
.box input[type="text"]:focus,.box input[type="password"]:focus{
  
  width : 270px;
  border-color : #ffc400ec;
  }
.box input[type="submit"]{
  
  border : 0;
background : none;
  display : block;
  margin : 20px auto;
  text-align : centre;
  border : 3px solid #ffc400ec;
  padding : 14px 35px;
  outline : none;
  color : white;
  border-radius : 24px;
  transition : 0.25px;
  cursor : pointer;
}
.box input[type="submit"]:hover{
  background : #ffc400ec;
}
  

  
  
  
  function validate()
{
var username = document.getElementById("Username").value;
var password = document.getElementById("Password").value;
  if(username=="admin" && password=="user")
    {
      alert("login successfully");
      return false;
    }
  else
    {
      alert("login failed");
    }
  
  
}
  
  
  
  
      
                        
                        
      
