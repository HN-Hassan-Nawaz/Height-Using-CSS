<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Height,Border,Width, and backgrounds</title>
    <style>
        #firstpara {
            background-color: red;
            height: 100px;
            width: 455px;
            border: 4px solid green;
            border-radius: 11px;
        }

        #secondpara {
            background-color: rgb(195, 98, 29);
            height: 100px;
            width: 455px;
            border-top: 4px solid rgb(107, 32, 212);
            border-bottom: 6px solid rgb(173, 14, 27);
            border-left: 5px solid rgb(165, 33, 145);
            border-right: 8px solid rgb(16, 217, 32);
            border-top-left-radius: 10px;
            border-top-right-radius: 12px;
            border-bottom-left-radius: 14px;
            border-bottom-right-radius: 15px;
        }

        #thirdpara {
            height: 300px;
            width: 455px;
            background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSr4ISVcXgykdMnPuRPFdIhH4cJpVxhbd6i0w&usqp=CAU);
            border: 2px solid green;
            background-repeat: no-repeat;
            /* background-position: top center; */
            /* background-position: bottom center; */
            /* background-position: top left; */
            /* background-position: top right; */
            /* background-position: bottom right; */
            background-position: center center;
        }
    </style>
</head>

<body>
    <h3>This is first heading</h3>
    <p id="firstpara">This is my first paragraph</p>

    <h3>This is second heading</h3>
    <p id="secondpara">This is my second paragraph</p>

    <h3>This is third heading</h3>
    <p id="thirdpara">This is my third paragraph</p>
</body>

</html># Height-Using-CSS
