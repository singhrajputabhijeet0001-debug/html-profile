# html-profile
A clean, responsive personal profile webpage built with HTML and CSS. Features a grid layout, styled sections, and contact links — perfect for showcasing basic web design and layout skills.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      body {
        margin: 0px;
      }
      .grid_container {
        
        border: 2px solid black;
        border-radius: 5px;
        margin-top: 10px;
        margin-left: 500px;
        margin-right: 500px;
        padding: 20px;

        display: grid;
        
        background-color: lightblue;
        grid-template-columns: auto;
        grid-template-areas: "h" "n" "s" "f" "p";
      }

      #first1 {
        margin-bottom: 20px;
        background-color: #6BBE44;
        border-radius: 5px;
        padding: 20px;
        align-items: center;

        grid-area: h;
      }

      #first2 {
        
        margin-bottom: 20px;
        border-radius: 5px;
        color: white;
        padding: 20px;
        background-color: #3498DB;

        grid-area: n;
      }
      #first3 {
        
        margin-bottom: 20px;
        padding: 20px;
        color: white;
        background-color: rgb(221, 194, 42);
        border-radius: 5px;

        grid-area: s;
      }
      #first4 {
        
        background-color: #7D3C98;;
        border-radius: 5px;
        margin-bottom: 20px;
        color: white;
        padding: 20px;
        font-size: 15px;

        grid-area: f;
      }
      #first5 {
        
        padding: 20px;
        background-color: #E67E22;
        border-radius: 5px;

        grid-area: p;
      }
      a{
        text-decoration: none;
      }
      img{
        border-radius: 100%;
      }
      .first-two{
        color: gold;
      }
      .last-two{
        color: gold;
      }
    </style>
  </head>
  <body>
    <div class="grid_container">
      <div class="items" id="first1">
        <img src="3146.png_860.png" alt="logo" width="100" height="100"/>
      </div>
      <div class="items" id="first2">
        <h2>Abhijeet singh</h2>
        <span class="first-two">Web Developer</span> at
        <span class="last-two">Tech Solutions</span>
      </div>
      <div class="items" id="first3">
        <p>
          Passionate about creating innovative web solutions that enhance user
          experience and functionality. Experienced in HTML, CSS, JavaScript and
          responsive design
        </p>
      </div>
      <div class="items" id="first4">
        Email: singhrajputabhijeet0001.com<br /><br />Phone: 9973320233
      </div>
      <div class="items" id="first5">
        <a href="#" style="color: white">Twitter</a
        ><a href="#" style="color: white; padding-left: 20px">Linkedin</a>
      </div>
    </div>
  </body>
</html>
