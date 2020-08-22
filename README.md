## Solution task Figure

#### HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style/main.css">
    <title>Figure</title>
</head>
<body>
    <div class="wrap">
        <div class="huge-square"></div>
        <div class="tiny-square"></div>
        <div class="circle circle--top-left"></div>
        <div class="circle circle--top-right"></div>
        <div class="circle circle--bottom-left"></div>
        <div class="circle circle--bottom-right"></div>
    </div>
</body>
</html>
```

#### CSS

```
/* === Config project
   ====================================================== */
body {
    margin: 0;
}

.wrap {
    position: relative;
    width: 1000px;
    height: 1000px;
    margin: 0 auto;
}
/* === Huge square
   ====================================================== */
.huge-square {
    position: absolute;
    top: 25%;
    left: 25%;
    width: 50%;
    height: 50%;
    background: #00a3ff;
    z-index: 10;
}

.huge-square:hover {
    z-index: 20;
    background: #111;
}
/* === Tiny square 
   ====================================================== */
.tiny-square {
    position: absolute;
    top: 37.5%;
    left: 37.5%;
    width: 25%;
    height: 25%;
    background: #f8bb00;
    border-radius: 15%;
    z-index: 15;
}
/* === Circles 
   ====================================================== */
.circle {
    width: 25%;
    height: 25%;
    border-radius: 50%;
    background: #ec2119;
}

.circle--top-left {
    position: absolute;
    top: 12.5%;
    left: 12.5%;
    z-index: 5;
}

.circle--top-left:hover {
    z-index: 20;
    background: #666;
}

.circle--top-right {
    position: absolute;
    top: 12.5%;
    right: 12.5%;
    z-index: 5;
}

.circle--top-right:hover {
    z-index: 20;
    background: #777;
}

.circle--bottom-left {
    position: absolute;
    bottom: 12.5%;
    left: 12.5%;
    z-index: 5;
}

.circle--bottom-left:hover {
    z-index: 20;
    background: #888;
}

.circle--bottom-right {
    position: absolute;
    bottom: 12.5%;
    right: 12.5%;
    z-index: 5;
}

.circle--bottom-right:hover {
    z-index: 20;
    background: #999;
}

```