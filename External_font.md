
## External Font In CSS
- #### Using Link And Importing 


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- This is link of external font -->
    <link href="https://fonts.googleapis.com/css2?family=Baloo+2&family=Piazzolla:opsz,wght@8..30,200;8..30,300;8..30,400;8..30,900&display=swap" rel="stylesheet">
    
    <title>Document</title>

    <style>
        h1{
            font-family: 'Baloo 2', "cursive";
        }
    </style>
</head>
<body>
    <h1>Using External font </h1>
</body>
</html>
}
```



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- This is link of external font -->
    <title>Document</title>
    <style>
        /* importing the link in stle sheet */
        @import url('https://fonts.googleapis.com/css2?family=Baloo+2&family=Piazzolla:opsz,wght@8..30,200;8..30,300;8..30,400;8..30,900&display=swap');
        h1{
            font-family: 'Baloo 2', "cursive";
        }
    </style>
</head>
<body>
    <h1>Using External font </h1>
</body>
</html>

<-----------Same Output------->
```
## Output

![Output](https://github.com/Aman1143/Analog-Clock/blob/master/output3.png?raw=true)


