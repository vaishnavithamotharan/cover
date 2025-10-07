# Ex.06 Book Front Cover Page Design
## Date:07.10.2025

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
cover.html

<html>
    <head>
        <title>MYBOOK
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page">
            
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
                PROGRESSIVE WEB APPS
            </div>
            <div class="subtitle">
              Core PWA Features and Implementation and Advanced PWA Topics<br>
              Top Seller of 2025
            </div>
            <div class="edit">
             PREMIUM EDITION
             </div>
             <br><hr>
              <div class="name">
                VAISHNAVI T
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

style.css

body{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 100vh;
}
.page{
    width: 500px;
    height: 600px;
    background-image: url(background.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 20px solid rgb(119, 205, 237);
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
       
}

.insights{
   color: #909be2;
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 10px;
}
.hr{
    color: rgb(210, 143, 254);
    width: 120px;
    right: 200%;
    

}
.title{
    color: #1118ea;
    font-size: 45px;
     margin: 13px 0 15px 0;
    
   font-weight: bold;
    text-align: center;
    
}
.subtitle{
    color: #390c92;
    font-size: 18px;
    margin-bottom: 40px;
}
.edit{
    color: #0e8cc6;
    font-size: 18px;
    font-weight: bold;
    margin-top: 200px;
}
.name{
    color: #0a8dce;
    font-size: 16px;
    font-weight: bold;
    margin-top: 5px;
   
}
.bottom{
    color: #4b0ecf;
    position: absolute;
    bottom: 50px;
    right: 60px;
    font-weight: bold;
}
.pic{
    position: absolute;
    bottom:90px;
    left: 75%;
    width: 100px;
    height:100px;
    background:url(mypic.jpg) no-repeat;
    background-size: 80px;
}

```

## OUTPUT:
![alt text](<Screenshot (40).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
