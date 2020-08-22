## Solution task Figure

[Watch result here 😊](https://oleg-kolosov.github.io/TMS-Lessons-Figure/)

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
        <div class="figure">
            <div class="figure__square-huge"></div>
            <div class="figure__square-tiny"></div>
            <div class="figure__circle figure__circle--top-left"></div>
            <div class="figure__circle figure__circle--top-right"></div>
            <div class="figure__circle figure__circle--bottom-left"></div>
            <div class="figure__circle figure__circle--bottom-right"></div>
        </div>
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
    width: 1000px;
    height: 1000px;
    margin: 0 auto;
}

.figure {
    position: relative;
    height: 100%;
    width: 100%;
}

/* === Huge square
   ====================================================== */
.figure__square-huge {
    position: absolute;
    top: 25%;
    left: 25%;
    width: 50%;
    height: 50%;
    background: #00a3ff;
    z-index: 10;
}

.figure__square-huge:hover {
    z-index: 20;
    background: #111;
}

/* === Tiny square 
   ====================================================== */
.figure__square-tiny {
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
.figure__circle {
    width: 25%;
    height: 25%;
    border-radius: 50%;
    background: #ec2119;
}

.figure__circle--top-left {
    position: absolute;
    top: 12.5%;
    left: 12.5%;
    z-index: 5;
}

.figure__circle--top-left:hover {
    z-index: 20;
    background: #666;
}

.figure__circle--top-right {
    position: absolute;
    top: 12.5%;
    right: 12.5%;
    z-index: 5;
}

.figure__circle--top-right:hover {
    z-index: 20;
    background: #777;
}

.figure__circle--bottom-left {
    position: absolute;
    bottom: 12.5%;
    left: 12.5%;
    z-index: 5;
}

.figure__circle--bottom-left:hover {
    z-index: 20;
    background: #888;
}

.figure__circle--bottom-right {
    position: absolute;
    bottom: 12.5%;
    right: 12.5%;
    z-index: 5;
}

.figure__circle--bottom-right:hover {
    z-index: 20;
    background: #999;
}
```
