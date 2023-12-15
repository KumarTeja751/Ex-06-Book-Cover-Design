# Ex-06-Book-Cover-Design

## AIM:
To design a book-cover-design using HTML and CSS.
## DEVELOPED BY: KUMARTEJA NARAMALA
## REGISTER NO: 212223230132
## DEPT: B.Tech(AI&DS)
## DESIGN PROCEDURE:
## STEP 1:
Start define the document type as HTML.

## STEP 2:
Open the HTML structure with necessary head and body sections.In the head section ,set the title as Book Coverpage and define the styles for the bookcover.Use the CSS styles in the code.The styles include:

background-color,

background-image,

background-position,

background-repeat,

padding,

font-size,

font-family,

background-size,

color,

line-height.

## STEP 3:
In the body section ,create a division with the text with respective to the headings:

"EXPERT INSIGHT"

"Responsive Web Design with HTML5 and CSS"

"Develop future-proof responsive websites using the latest HTML5 and CSS techniques"

"EXTENDED EDITION"

"KUMARTEJA NARAMALA"

"SEC>"

## STEP 4:
Close the HTML structure.

## CODE:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(paste.jpg);
            background-size :cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:white;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: "Sans-Serif";
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color:
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            color:white;
            top:155px;
            left:330px;
        }
        .edition{
            color:cyan;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>"Responsive Web Design with HTML5 and CSS"
                </h1>
            </div>
            <div class=subtitle>
               Develop future-proof responsive websites using the latest HTML5 and CSS techniques 
            </div>
            <div class="photo">
                <img src="WhatsApp Image 2023-09-21 at 21.51.37.jpg" width="130" height="145"alt="">
            </div>
            <div class="id">
                <hr style="color:red;">
            </div>
            <div class="author">
               <p><b>KUMARTEJA NARAMALA</b></p>
            </div>
            <div class="publisher">
                SEC>
            </div>
            <div class="edition">
                <b>EXTENDED EDITION</b>
            </div>
            
        </div>
    </body>
</html>
```
## OUTPUT:

![Screenshot 2023-12-15 113220](https://github.com/KumarTeja751/Ex-06-Book-Cover-Design/assets/144947756/d484a8e1-f4fd-49f0-93a9-a5bd9e56ed5b)


## RESULT:
Thus the book-cover-design has been successfully created using HTML and CSS.
