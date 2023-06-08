<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Height, Width, Borders and Background color</title>
    <style>
        #class {
            font-size: 35px;
            background-color: aqua;
            height: 100px;
            width: 400px;


        }

        #college {
            font-family: 'Courier New', Courier, monospace;
            font-size: 20px;
            height: 100px;
            width: 400px;
            font-style: italic;
            position: 50px;


            border-top: 10px greenyellow solid;
            border-top-width: 10px;
            border-top-left-radius: 10px;
            border-top-right-radius: 20px;
            border-bottom: 10px green solid;


            border-left: 10px solid blue;

            border-right: 10px skyblue solid;
        }

        #image {
            background-image: url(https://www.simplilearn.com/ice9/free_resources_article_thumb/what_is_image_Processing.jpg);
            height: 300px;
            width: 800px;


            border-style: solid;
            border-width: 20px;
            border-color: green;
            border-radius: 10px;

        }
    </style>
</head>

<body>
    <p id="class">Only background color add </p>
    <p id="college">Only border </p>

    <p id="image"> for image attach</p>
</body>

</html>
