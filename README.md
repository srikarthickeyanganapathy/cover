# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the github repository and create a Django admin interface
### Step 2:

## Code:
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
            color:yellowgreen;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Serif', 'Arial Narrow  Bold', Arial, sans-serif;
            background-image: url(/static/images/op2.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: whitesmoke;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(119, 21, 21);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(0, 0, 0);
            font-size: large;
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
        .mypic{
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
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 0, 0);">
            </div>
            <div class="booktitle">
                <h1>THE PSYCHOLOGY OF MONEY</h1></div>
            <div class="subtitle">
                Timeless lessons on Wealth,Greed and Happiness 
            </div>
            <div class="mypic">
                <img src="/static/images/op3.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:yellow;">
            </div>
            <div class="author">
               <p><b>Sri Karthickeyan Ganapathy</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>First Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
Include your output screenshot here

## Result:
Write your result
