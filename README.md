# Ex.08 Design of Interactive Image Gallery
# Date:
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Toothless</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Satisfy&family=Roboto:wght@400;700&display=swap"
    rel="stylesheet">
  <style>
    body {
        font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      background: url(back.jpg);
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      background-attachment: fixed;
      flex-direction: column;
      align-items: center;
      background-color: #f9f9f9;
      color: #333;
    }

    h1 {
      font-family: 'Satisfy', cursive;
      font-size: 3em;
      margin: 20px;
      color: #42084d;
      text-align: center;

    }

    h2 {
      font-family: 'Satisfy', cursive;
      font-size: 3em;
      margin: 20px;
      color: #7e3305;
      text-align: center;
    }

    .gallery {
      display: flex;
      gap: 15px;
      max-width: 1200px;
      padding: 10px;
      justify-content: center;
    }



    .item img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-bottom: 1px solid #ddd;
    }

    
    #image {
      z-index: 100;
      display: none;
      background: rgba(0, 0, 0, 0.5);
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      bottom: 0;
      align-items: center;
      justify-content: center;
    }

    #image img {
      width: 600px;
      height: auto;
    }
  </style>
</head>

<body>
  <h1>Image Gallery</h1>
  <h2>by Aswin (24003348)</h2>
  <section id="image">
    <img src="Screenshot 2024-12-15 210708.png" alt="" id="display"
      onclick="closes()">
  </section>
  <div class="gallery">
    <div class="item"><img src="Screenshot 2024-12-15 210708.png"
        onclick="opens(this.src)" alt="Image 1"></div>
    <div class="item"><img src="sachin.webp" onclick="opens(this.src)" alt="Image 2">
    </div>
    <div class="item"><img src="viv.webp" onclick="opens(this.src)" alt="Image 3">
    </div>
    <div class="item"><img src="Kane-Williamson.webp" onclick="opens(this.src)"
        alt="Image 4"></div>
    <div class="item"><img src="smith.jpg" onclick="opens(this.src)" alt="Image 5">
    </div>
  </div>
  <div class="gallery">
    <div class="item"><img src="boss.webp" onclick="opens(this.src)" alt="Image 6">
    </div>
    <div class="item"><img src="Screenshot 2024-12-15 215302.png"
        onclick="opens(this.src)" alt="Image 7"></div>
    <div class="item"><img src="Joe-Root.webp" onclick="opens(this.src)"
        alt="Image 8"></div>
    <div class="item"><img
        src="1022.6666666666666x767__origin__0x0_Dale_Steyn_fielding.jpg"
        onclick="opens(this.src)" alt="Image 9"></div>
    <div class="item"><img
        src="Shoaib-Akhtar-Announces-Biopic-Details-Inside1200_62de8f281eef5.jpeg"
        onclick="opens(this.src)" alt="Image 10"></div>
  </div>
  </div>
  <script>
    var a = document.getElementById("image");
    var b = document.getElementById("display");
    function opens(c) {
      a.style.display = 'flex';
      b.src = c;
    }
    function closes() {
      a.style.display = 'none';
    }
  </script>
</body>

</html>

```
# OUTPUT:
![Screenshot 2024-12-15 233242](https://github.com/user-attachments/assets/2f4bc68a-e370-49c7-9022-74ef895b1b6e)
![Screenshot 2024-12-15 233334](https://github.com/user-attachments/assets/02f57c8f-e0e1-4fe1-93c3-7d1f91cce395)
![Screenshot 2024-12-15 233351](https://github.com/user-attachments/assets/5ae02c6f-3b62-4f9a-9f2b-5a3c00ba0b13)

![Screenshot 2024-12-15 233515](https://github.com/user-attachments/assets/192a40cd-417a-4990-a92f-8d456390666f)



# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
