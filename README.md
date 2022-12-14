# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](./design/preview.jpg)

## Welcome! 👋

This a Frontend Mentor, coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

## The challenge

The Challenge was to build out this QR code component and get it looking as close to the design as possible.

I used CSS, HTML and Google fonts, there is nothing crazy!

## Where to find everything

Your task is to build out the project to the designs inside the `/design` folder. You will find both a mobile and a desktop version of the design. 

The designs are in JPG static format. Using JPGs will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. 

You will find all the required assets in the `/images` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

## Building This project!
# The html code:
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
    <title>Frontend Mentor | QR code component</title>

    </head>
    <body>  
    <div id="container">
        <img src="/images/image-qr-code.png" alt="frontEndmenter-qr-code" id="qr-code-image">
        <h2>Improve your front-end skills by building projects</h2>
        <p>Scan the QR code to visit FrontEnd Mentor and take your coding skills to the next level</p>
    </div>
    </body>
    </html>
```
# CSS Code
```
    /* Designed by Simel */
    @import url('https://fonts.googleapis.com/css?family=Outfit');

    :root {
        --body-font: "Outfit", sans-serif;
        --white: hsl(0, 0%, 100%);
        --light-gray: hsl(212, 45%, 89%);
        --grayish-blue: hsl(220, 15%, 55%);
        --dark-blue: hsl(218, 44%, 22%);
    }

    * {
        box-sizing: border-box;
        margin: 0px;
        padding: 0px;
    }
    body{
        font-family: var(--body-font);
        font-weight: 400, 700;
        background-color: var(--light-gray);
        max-width: 1440px;
        font-size: 15px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    #container {
        background-color: var(--white);
        display: flex;
        border-radius: 8px;
        flex-direction: column;
        padding: 10px 15px;
        text-align: center;
        width: 20%;
        margin-top: 10%;
        
    }
    #container > h2 {
        font-weight: bold;
        margin-bottom: 8%;
        text-align: left;
        text-indent: 0.2em;
        font-size: 21px;
        font-family: Outfit;
        color: var(--dark-blue);
    }
    #container > p{
        font-weight: 590;
        margin-bottom: 8%;
        font-family: Outfit;
        color: var(--grayish-blue);
    }

    #qr-code-image{
        border-radius: 8px;
        margin-bottom: 10%;
        
    }

    @media screen and (max-width: 1020px) {
            
        #container {
            margin-top: 10%;
            width: 5rem;

        } 
    }
```

## I deployed the project on:

- [Netlify](https://bestqrcode-frontend-mentor.netlify.app/)

## Got feedback for Me?

I love receiving feedback! I am always looking to improve our challenges and our platform. So if you have anything you'd like to mention, please email jameskarinosimel@gmail.com. 

This challenge is completely free. Feel free to try at it at [Frontend Mentor site](https://www.frontendmentor.io).

**Have fun building!** 🚀
