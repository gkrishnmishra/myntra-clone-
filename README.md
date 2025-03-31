# myntra-clone-
this is my first project
Author-Gaurav Mishra
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>nyntra clone</title>
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=search" />
    <style>
      * {
    margin: 0;
    padding: 0;
    font-family:  Assistant, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif;;
    box-sizing: border-box;
    
}

header {
    display: flex;
    background-color: #ffffff;
    height: 80px;
    justify-content: space-between;
    border-bottom: 1px solid #b6b1b1;
    
}
.logo_container {
    margin-left: 4%;
}
.nav_bar {
    display: flex;
    min-width: 500px;
    justify-content: space-evenly;
}
.nav_bar a {
    font-size: 14px;
    letter-spacing: 3px;
    color: #282c3f;
    font-weight: 700;
    text-transform: uppercase;
    text-decoration: none;
    padding: 30px 0;
}
.nav_bar a sup {
    color: #ff3f6c;
    font-size: 10px;

}
.search_bar {
height: 40px;
min-width: 200px;
width: 30%;
display: flex;
align-items: center;
}
.search icon {
box-sizing: content-box;
height: 20px;
padding: 10px;
background-color: #f5f5f6;
color: #282c3f;
font-weight: 300;
border-radius: 4px 0 0 4px;
}
.search-input {
color: #696e79;
background-color: #f5f5f6;
flex-grow: 1;
height: 40px;
border: 0;
border-radius:0 4px  4px 0;
}
.action_bar {
    display: flex;
    min-width: 200px;
    justify-content: space-evenly;
}
.actoin_container {
    display: flex;
    flex-direction: column;
    align-items: center;
}
.nav_bar a:hover {
    border-bottom: 5px solid #f54e77;
}
.Banner_image {
    width: 100%;

}
.Banner_container {
    margin: 40px 0;
}
.catogary_heading {
    text-transform: uppercase;
    color: #3e4152;
    letter-spacing: 15em;
    font-size: 1.8em;
    margin: 50px 0  10px 30px;
    max-height: 5em;
    font-weight: 700;
}
.cotegry_items {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
.sale_items {
width: 250px;
}
    </style>
</head>

<body>
    <header>
        <div class="logo_container">
            <a href="#"><img  class="myntra_home" src="https://images.indianexpress.com/2021/01/myntra.png" alt="myntra_home" height="45px"></a>
        </div>

        <nav class="nav_bar">
            <a href="#">Home &nbsp </a>
            <a href="#">Men  &nbsp </a>
            <a href="#">Women  &nbsp </a>
            <a href="#">Kids &nbsp  </a>
            <a href="#">Home &living  &nbsp</a>
            <a href="#">Beauty  &nbsp  </a>
            <a href="#">Studio <sup >new</sup></a>

        </nav>
        <div class="search_bar">
            <span class="material-symbols-outlined search icon" >search</span> 
            <input class="search_input" placeholder="search for products,brands and more">
        </div>
        <div class="action_bar">  
            <div class="actoin_container">
                <span class="material-symbols-outlined
                action_icon">Person</span>    
                <span class="action_name">Profile</span>
            </div>
            <div class="actoin_container">
                <span class="material-symbols-outlined action_icon">wishlist</span> 
                <span class="action_name">Wishlist</span>
            </div>
            <div class="actoin_container">
                <span class="material-symbols-outlined action_icon">shopping_bag</span>    
                <span class="action_name">bag</span>
            </div>
        </div>
    </header>
    <main> 
        <div class="Banner_container">
            <img class="Banner_image" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\img5.png" alt="Main Banner">
        </div>
        <div class="catogary_heading"> MEDAL WORTHY BRANDS TO BAG</div>
        <div class="cotegry_items">
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\radhe1.png "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\radhe2.png "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\radhe3.png "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\radhe4.png "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\radhe5.png "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\radhe6.png "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\img3.jpg "></a>
            <a href="#"><img  class="sale_items" src="C:\Users\Ayush Mishra\Desktop\gaurav.html\img4.jpg "></a>
            <a href="#"><img  class="sale_items" src=" C:\Users\Ayush Mishra\Desktop\gaurav.html\img6.png"></a>
            <a href="#"><img  class="sale_items" src=" C:\Users\Ayush Mishra\Desktop\gaurav.html\img7.png"></a>

        </div>]
    </main>
   <footer>
    <div class="Footer_Container">
        <div class="Footer_column"></div>
        <h3>Online shopping</h3>

        <a href="#">Home &nbsp </a>
        <a href="#">Men  &nbsp </a>
        <a href="#">Women  &nbsp </a>
        <a href="#">Kids &nbsp  </a>
        <a href="#">Home &living  &nbsp</a>
        <a href="#">Beauty  &nbsp  </a>
        <a href="#">Studio <sup >new</sup></a>
    </div>
   </footer>
</body>
</html>
