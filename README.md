# HTML :

## First create a html page:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>

```

## head tag and paragraph

``` 
   <h1>hello world</h1>
    <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit.
    </p>
```
 <h1>hello world</h1>
    <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit.
    </p>

## break
```
    <br> 
```
## Attributes(hyperlink & image):
```
<a href="#">link name</a>
<img src="#" alt="">
```

## Navbar
```
 <nav></nav>
```
- eg :
```
<nav>
    <ul>
        <li><a href="#"></a>Home</li>
        <li><a href="#"></a>About</li>
        <li><a href="#"></a>contact</li>
        <li><a href="#"></a>theme</li>
    </ul>
</nav>

```
<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Theme</a></li>
    </ul>
</nav>


## list items
### Unorder list
```
<ul>
    <li>ABCD</li> 
    <li>QWERTY</li> 
    <li>ZXCVB</li> </ul>
```
<ul>
    <li>ABCD</li> 
    <li>QWERTY</li> 
    <li>ZXCVB</li> 
</ul>

### Ordered list

```
<ol>
     <li>ABCD</li> 
    <li>QWERTY</li> 
    <li>ZXCVB</li> 
</ol> 
```
<ol>
     <li>ABCD</li> 
    <li>QWERTY</li> 
    <li>ZXCVB</li> 
</ol> 

## Block element:
```
<div>Hello world</div>
```
- eg :
```
<div>
    <img src="#" alt="">
    <h2>My team</h2>
    <p>Lorem ipsum dolor sit amet.</p>
</div>
```

## Table:
```
<table>
    <tr>
        <th>Name</th>
        <th>contact</th>
        <th>country</th>
    </tr>
    <tr>
        <td>asdf</td>
        <td>asdf</td>
        <td>asdf</td>
    </tr>
    <tr>
        <td>qwerty</td>
        <td>qwerty</td>
        <td>qwerty</td>
    </tr>
</table>

```

<table>
    <tr>
        <th>Name</th>
        <th>contact</th>
        <th>country</th>
    </tr>
    <tr>
        <td>asdf</td>
        <td>asdf</td>
        <td>asdf</td>
    </tr>
    <tr>
        <td>qwerty</td>
        <td>qwerty</td>
        <td>qwerty</td>
    </tr>
</table>

### form :

```
<form>
  <label for="">First name:</label><br>
  <input type="text" id="" name=""><br>
  <label for="">Last name:</label><br>
  <input type="text" id="" name="">

//-----This code only for radio button----
  <input type="radio" id="" name="fav_language" >
  <label for="male">male</label><br>
  <input type="radio" id="" name="fav_language" >
  <label for="female">female</label>
</form>

```

 <form>
        <label for="">First name:</label><br>
        <input type="text" id="" name=""><br>
        <label for="">Last name:</label><br>
        <input type="text" id="" name=""><br>
        <input type="radio" id="" name="fav_language" >
        <label for="male">male</label><br>
        <input type="radio" id="" name="fav_language" >
        <label for="female">female</label>
      </form>


### body part:

```
<header></header>
<section></section>
<footer></footer>
```

### class

```
 <div class="city">
    <h2>lorem</h2>
    <p>Lorem ipsum dolor sit amet.</p>
  </div>
```

### id
```
<h2 id="head">Lorem ipsum dolor sit.</h2>
```

### Button:
```
<button>submit</button>
```
<button>submit</button>


## CSS:
### Internal css
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
            color: green;
        }
    </style>
</head>
<body>
<h1>Hello-world</h1>
</body>
</html>
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
            color: green;
        }
    </style>
</head>
<body>
<h1>Hello-world</h1>
</body>
</html>

### Inline css

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<h1 style="color: red;">Hello-world</h1>
</body>
</html>
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<h1 style="color: red;">Hello-world</h1>
</body>
</html>

### External css
#### create a css file in external, and give the name to `(css-file-name).css` as `style.css`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<h1>Hello-world</h1>
</body>
</html>
```


## CSS topic

1. color
2. background
3. border
4. height
5. weight
6. margin
7. padding
8. outline
9. text
10. font
11. display
12. justify
13. align
14. overflow
15. z-index
16. opacity
17. url()
18. hover
19. focous
20. gradient
21. box-shadow
22. blur
23. object fit
24. units
25. translate
26. rotate
27. Animation

## 1.color
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            color: red;
        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur.</h2>
</body>
</html>
```
## 2.backgorund
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            background: green;
            background-color: aqua;

        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur.</h2>
</body>
</html>
```
## 3.border
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            border: 2px solid red; 
            border: 2px dashed red;
            border: 2px dotted red;
            border-bottom: 2px solid red;
            border-top: 2px solid red;
            border-right: 2px solid red;
            border-left: 2px solid red;
            border: none;
            
        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur.</h2>
</body>
</html>
```
## 4.height & weight
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        div{
            height: 100px;
            width: 200px;
            border: 2px solid red;
        }
    </style>
</head>
<body>
    <div></div>
</body>
</html>
```
## 5.text & font
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            text-align: center;
            font-size: 15px;
            font-family: serif;
            font-weight: 500;
            font-style: italic;
        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet.</h2>
</body>
</html>
```
## 6.margin
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            margin: 50px;
            margin-top: 50px;
            margin-bottom: 50px;
            margin-right: 50px;
            margin-left: 50px;            
        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur.</h2>
</body>
</html>
```
## 7.padding
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            padding: 50px;
            padding-top: 50px;
            padding-bottom: 50px;
            padding-right: 50px;
            padding-left: 50px;
            border: 2px solid red;

        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur.</h2>
</body>
</html>
```
## 8.outline
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            outline: 2px solid red;
            outline: none;
            
        }
    </style>
</head>
<body>
    <h2>Lorem ipsum dolor sit amet consectetur.</h2>
</body>
</html>
```

## 9.display
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            display: flex;
            display: grid;
            display: block;
            display: inline;
            border: 2px solid red;
            
            
        }
    </style>
</head>
<body>
   <h2>Lorem ipsum dolor sit amet.</h2>
</body>
</html>
```
## 10.justify
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            display: flex;
            justify-content: center;
            justify-content: start;
            justify-content: end;
            justify-content: space-around;
            justify-content: space-between;
            justify-content: space-evenly;
            
            justify-items: center;
            justify-items: start;
            justify-items: end;
            justify-items: space-around;
            justify-items: space-between;
            justify-items: space-evenly;
            
            
            
        }
    </style>
</head>
<body>
   <h2>Lorem ipsum dolor sit amet.</h2>
</body>
</html>
```
## 11.align
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        h2{
            display: flex;
            align-content: center;
            align-content: start;
            align-content: end;
            align-content: space-around;
            align-content: space-between;
            align-content: space-evenly;
            
            align-items: center;
            align-items: start;
            align-items: end;
            align-items: space-around;
            align-items: space-between;
            align-items: space-evenly;
            
            
            
        }
    </style>
</head>
<body>
   <h2>Lorem ipsum dolor sit amet.</h2>
</body>
</html>
```

## 14.overflow
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        div{
            width: 150px;
            height: 70px;
            border: 2px red solid;
            overflow: scroll;
            overflow-x:scroll ;
            overflow-y: scroll;
            overflow: hidden;
        }
    </style>
</head>
<body>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem numquam labore veniam.</p>
    </div>
</body>
</html>
```

## 15.z-index
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
      
        .div1{
            background: green;
            position: relative;
            z-index: 1;
            width: 200px;
            height: 200px;
        }
        .div2{
            background: red;
            position: absolute;
            width: 250px;
            height: 250px;
            z-index: -1;
        }
    </style>
</head>
<body>
    <div class="div1"></div>
    <div class="div2"></div>
</body>
</html>
```
## 16.opacity
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
      img{
        width: 250px;
        height: 250px;
        opacity: 0.2;
        opacity: 0.5;
        opacity: 1;
      }
    </style>
</head>
<body>
   <img src="https://static.vecteezy.com/system/resources/previews/024/212/465/non_2x/blue-cat-robot-and-a-boy-watching-the-dusk-sky-free-vector.jpg" alt="">
</body>
</html>
```
## 17.url()
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
      .div1{
        width: 500px;
        height: 500px;
        background: url(https://static.vecteezy.com/system/resources/previews/024/212/465/non_2x/blue-cat-robot-and-a-boy-watching-the-dusk-sky-free-vector.jpg);

    }
    </style>
</head>
<body>
   <div class="div1"></div>
</body>
</html>
```
## 18.hover
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        button{
            width: 200px;
            height: 50px;
            background: #000;
            color: white;
        }
        button:hover{
            background: red;
            color: black;
        }
     
    </style>
</head>
<body>
<button>button</button>

</body>
</html>
```
## 19.focus
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        button{
            width: 200px;
            height: 50px;
            background: #000;
            color: white;
        }
        button:focus{
            background: red;
            color: black;
        }
     
    </style>
</head>
<body>
<button>button</button>

</body>
</html>
```
## 20.gradient
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        button{
            width: 200px;
            height: 50px;
            background-image:linear-gradient(green,blue,red) ;
            background-image:linear-gradient(to right,green,blue,red) ;
            color: white;
        }
        
     
    </style>
</head>
<body>
<button>button</button>

</body>
</html>
```
## 21.boxshadow
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 100vh;
        }
        div{
            width: 200px;
            height: 200px;
            background: red;
            box-shadow: 1px 1px 60px blue;
        }
        
    </style>
</head>
<body>
    <div ></div>
</body>
</html>
```
## 22.blur
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        div{
            
            background: url(https://static.vecteezy.com/system/resources/previews/024/212/465/non_2x/blue-cat-robot-and-a-boy-watching-the-dusk-sky-free-vector.jpg);
            width: 700px;
            height: 500px;
            display: flex;
            justify-content: center;
            align-items: center;
        
        }
        button{
            width: 250px;
            height: 100px;
            color: black;
            background: transparent;
            backdrop-filter: blur(10px);
        }
        
     
    </style>
</head>
<body>
    <div>

        <button>button</button>
    </div>

</body>
</html>
```
## 23.object-fit
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        div{
            
            
            display: flex;
            justify-content: center;
            align-items: center;
        
        }
        img{
            width: 250px;
            height: 350px;
            object-fit: contain;
            object-fit: cover;
            object-fit: fill;
            border: 2px solid red;
        }
       
     
    </style>
</head>
<body>
    <div>

       <img src="https://static.vecteezy.com/system/resources/previews/024/212/465/non_2x/blue-cat-robot-and-a-boy-watching-the-dusk-sky-free-vector.jpg" 
       width="400" height="500"
       alt="">
    </div>

</body>
</html>
```
## 24.units
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fun coding</title>
    <style>
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        h2{
            font-size: 4px;
            font-size: 4rem;
            font-size: 4em;
            
        }
       div{
        height: 100vh;
        width: 100vw;
        height: 100svh;
        width: 100svw;
        height: 100lvh;
        width: 100lvw;
        height: 100dvh;
        width: 100dvw;

       }
        
       
     
    </style>
</head>
<body>

      <h2>Lorem ipsum dolor sit amet consectetur.</h2>
        <div></div>
</body>
</html>
```
## 25.translate
```

```
## 26.transform
```

```
## 27.rotate
```

```
## 28.Animation
```

```


## How to setup tailwindcss in html


### Step 1 :  Install tailwindcss

```
npm install -D tailwindcss
```
```
npx tailwindcss init
```
### Step 2 : Add the paths to tailwind.config.js file.

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### Step 3 : Create src/input.css and add it.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

#### Step 4 : Run your CSS.

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### Step 5 : Add your output.css into your html file ,the output.css is generated after the step4

```
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="./output.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>

```
