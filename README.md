# demo-profile
<!-- creating my proifile -->
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sohail's Profile</title>
    <style>
        #first {
            border-radius: 30%;
        }

        * {
            padding: 20px 10px 10px 20px;
        }

        input,
        select {
            width: 100%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        input[type=submit] {
            width: 100%;
            background-color: #b5e040;
            color: Black;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type=submit]:hover {
            background-color: #4dd9b6;
        }

        div {
            border-radius: 5px;
            background-color: #e9ba53;
            padding: 20px;
        }
    </style>
</head>

<body style="background-color: rgb(255, 255, 0);">
    <center>
        <br>
        <h1 style="font-size: 65px; background-color: aquamarine; border:2px solid black;">Welcome to my Landing Page
        </h1>
        <!-- <hr><br> -->
    </center>
    <div style="border:2px solid black;">
        <img id="first" align="right" src="cccc.jpg" alt="" height="350" width="350">
    </div>
    <h2 style="color:#00a2ffe8; font-size: 40px;">I am AAAA BBBB.</h2>
    <p align="left" style="font-size: 25px;">If you're looking for random paragraphs, you've come to the right place.
        <br>
        When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph.
        <br>
        We created the Random Paragraph Generator with you in mind. The process is quite simple. <br>
        Choose the number of random paragraphs you'd like to see and click the button. <br>
        Your chosen number of paragraphs will instantly appear.
    </p><br>
    <hr> <br>
    <h2>My Skills - </h2>
    <ul style="font-size: 25px;">
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ul>
    <hr><br>

    <form>
        <h4>Contact Me</h4>
        <!-- Input from User -->
        <input type="text" placeholder='Name' id="name"><br>
        <input type="email" placeholder='Email' id="email"><br>
        <input id='btn' type="submit" placeholder='Register' onclick="register(event)">
    </form>
    
</body>

</html>
