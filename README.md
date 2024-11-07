<!DOCTYPE html>
<html>
  <head>
    <title>Title of the documentp</title>
    <style>
      h3 {
        color: #8ebf42;
      }
      .form-container {
        display: table;
        padding: 5px;
        border: 2px #666;
        border-radius: 5px;
        background-color: darkgreen;
        margin: 5px;     
      }
      .form-container > div{
        width: 300px;
        height: 80px;
        background-color: darkgreen;
        color: yellow;
        padding: 5px;
      }
     </style>
     <h3>Fill in your form</h3>
     <form method="" action="" class="form-container">
          <div class>
               <label for="name">Name:</label>
               <input type="text" id="name" placeholder="Name"><br>
          </div>
       <div>
               <label for="address">Address:</label>
               <input type="text" id="address" placeholder="Address"><br><br>
          </div>
       <div>
               <label for="email">Email:</label>
               <input type="text" id="email" placeholder="Email"><br><br>
          </div>
            <div>
               <label for="phone">Telephone:</label>
               <input type="text" id="phone" placeholder="Telephone"><br><br>
          </div>
     
     </form>
    
