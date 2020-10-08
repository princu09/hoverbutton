## Hover Button CSS Layout Free Source Code By NorthFox Developers

##### 📫 Connect with me here:<br />
 <br />
 <p>
  <a target="_blank" href="https://www.instagram.com/princu.09">
    <img src="https://img.shields.io/badge/princu.09-386938188?style=flat&logo=instagram&color=black">
  </a> &nbsp; 
  <a target="_blank" href="https://twitter.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=twitter&color=black">
  </a>&nbsp; 
  <a target="_blank" href="https://github.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=github&color=black">
  </a>&nbsp;
    <a target="_blank" href="https://www.t.me/proghub09">
    <img src="https://img.shields.io/badge/ProgHub09-386938188?style=flat&logo=telegram&color=black">
  </a>
</p>

![Video Here](HoverButton.gif)

#### HTML File

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Hover</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="header">
            <h1>NorthFox Developers</h1>
        </div>
        <div class="btn">
            <a href="">
                <span></span>
                <span></span>
                <span></span>
                <span></span> Hover Me
            </a>
        </div>
    </div>
</body>

</html>
```


#### CSS File

```
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');

/* Created By NorthFox Group */

html {
    font-size: 10px;
    scroll-behavior: smooth;
}

* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}

.container {
    background: #000919;
    width: 100vw;
    height: 100vh;
    justify-content: center;
    align-items: center;
    display: flex;
    flex-direction: column;
}

.container .header h1 {
    text-align: center;
    margin: 50px;
    font-size: 5em;
    color: #14bfe6;
    font-weight: 500;
}

.btn a {
    font-size: 4em;
    text-decoration: none;
    color: white;
    padding: 15px 30px;
    overflow: hidden;
    transition: 0.2s;
    display: inline-block;
    border-radius: 50px;
    position: relative;
}

a:hover {
    background: darkorange;
    border-radius: 50px;
    box-shadow: 0 0 30px darkorange, 0 0 30px darkorange, 0 0 100px darkorange;
    transition-delay: 1s;
}

a span {
    position: absolute;
    display: block;
}

a span:nth-child(1) {
    border-radius: 50px;
    top: 0;
    left: -100%;
    width: 100%;
    height: 2px;
    background: linear-gradient(90deg, transparent, darkorange);
}

a:hover span:nth-child(1) {
    border-radius: 50px;
    left: 100%;
    transition: 1s;
}

a span:nth-child(3) {
    border-radius: 50px;
    bottom: 0;
    right: -100%;
    width: 100%;
    height: 2px;
    background: linear-gradient(270deg, transparent, darkorange);
}

a:hover span:nth-child(3) {
    border-radius: 50px;
    right: 100%;
    transition: 1s;
    transition-delay: 0.5s;
}

a span:nth-child(2) {
    border-radius: 50px;
    top: -100%;
    right: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(180deg, transparent, darkorange);
}

a:hover span:nth-child(2) {
    border-radius: 50px;
    top: 100%;
    transition: 1s;
    transition-delay: 0.25s;
}

a span:nth-child(4) {
    border-radius: 50px;
    bottom: -100%;
    left: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(360deg, transparent, darkorange);
}

a:hover span:nth-child(4) {
    border-radius: 50px;
    bottom: 100%;
    transition: 1s;
    transition-delay: 0.75s;
}

@media screen and (max-width:963px) {
    .container .header h1 {
        text-align: center;
        margin: 50px;
        font-size: 4em;
        color: #14bfe6;
        font-weight: 500;
    }
}
```
