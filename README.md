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

