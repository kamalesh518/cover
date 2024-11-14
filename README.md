# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <style>
        .box{
            height: 700px;
            width: 500px;
            margin:auto;
            position: relative;
            
        }
        .title{
            font-size: xx-large;
            font-weight: 400;
            font-style: italic;
            top:0%;
            left:10%;
            color: maroon;
            position: absolute;
            
        }
        .caption{
            font-size: x-large;
            font-weight: 1000;
            font-style: oblique;
            color:black;

            top:40%;
            right:22px;
            position:absolute;
        }
        .author{
            
            
           
            right: 0%;
            bottom: 0px;
            position: absolute;
            
           
        }
        .name{
            font-size: large;
            font-weight: 900;
            font-style: initial;
            position: absolute;
            right: 4%;
            bottom :10%;
            color: rgb(100, 0, 7);

        }

        
   
        .bottom-bar {
            position: absolute;
            bottom: 10px;
            left: 20px;
            font-size: medium;
        }
        .publisher, .date {
            display: inline-block;
            margin-right: 10px;
            font-weight: 600;
            color: rgb(139, 0, 56);

        }
       



    </style>
    <body>
        <div class="box">
            
            <center>
                <img src="C:\Users\admin\OneDrive\Pictures\josh-felise-a7HJsX8HiuM-unsplash.jpg" width="100%" height="100%">
            </center>
           
            <div class="title" >
                <h1>Java Script For Beginners</h1>
                

            </div>
            

            
            <div class="caption">
                <p>"Empowering Web Development With Code." 

                </p>
            </div>
            <hr>
            <div class="name">
                <p>KAMALESH Y</p>
            
            </div>
            
            <div class="author">
                
                <img src="C:\Users\admin\OneDrive\Documents\WhatsApp Image 2024-11-14 at 05.16.34_dd3a0909.jpg" width="85" height="85">
            </div>
    
            <div class="bottom-bar">
                <div class="publisher">Publisher: SimpleBooks</div>
                <div class="date">2024</div>
              
            </div>
            
            
            <div class="strip"></div>
        </div>
    
    
    </body>
</html>
```

## OUTPUT:
![Screenshot 2024-11-14 053458](https://github.com/user-attachments/assets/70ad6772-af3c-4fcc-9f7c-80637ebf64e2)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
