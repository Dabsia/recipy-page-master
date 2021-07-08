<!-- Please update value in the {}  -->

<h1 align="center">{Your project name}</h1>

<div align="center">
   Solution for a challenge from  <a href="http://devchallenges.io" target="_blank">Devchallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://{your-demo-link.your-domain}">
      Demo
    </a>
    <span> | </span>
    <a href="https://{your-url-to-the-solution}">
      Solution
    </a>
    <span> | </span>
    <a href="https://{your-url-to-the-challenge}">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [Built With](#built-with)
- [Features](#features)
- [How to use](#how-to-use)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- OVERVIEW -->

## Overview

![screenshot](https://user-images.githubusercontent.com/16707738/92399059-5716eb00-f132-11ea-8b14-bcacdc8ec97b.png)

Introduce your projects by taking a screenshot or a gif. Try to tell visitors a story about your project by answering:

- Where can I see your demo?
- What was your experience?
- What have you learned/improved?
- Your wisdom? :)

### Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- [React](https://reactjs.org/)
- [Vue.js](https://vuejs.org/)
- [Tailwind](https://tailwindcss.com/)

## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges) challenge. The [challenge](https://devchallenges.io/challenges/TtUjDt19eIHxNQ4n5jps) was to build an application to complete the following user stories:

- [x] User story: This is a completed user stories
- [ ] User story: This is a incompleted user stories
- [ ] User story: This is a incompleted 2nd user stories

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/your-user-name/your-project-name

# Install dependencies
$ npm install

# Run the app
$ npm start
```

## Acknowledgements

<!-- This section should list any articles or add-ons/plugins that helps you to complete the project. This is optional but it will help you in the future. For exmpale -->

- [Steps to replicate a design with only HTML and CSS](https://devchallenges-blogs.web.app/how-to-replicate-design/)
- [Node.js](https://nodejs.org/)
- [Marked - a markdown parser](https://github.com/chjj/marked)

## Contact

- Website [your-website.com](https://{your-web-site-link})
- GitHub [@your-username](https://{github.com/your-usermame})
- Twitter [@your-twitter](https://{twitter.com/your-username})


<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Recipe app</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='css/styles.css'>
    
    <!-- type faces -->
    <link href="https://fonts.googleapis.com/css?family=Montserrat:100,100italic,200,200italic,300,300italic,regular,italic,500,500italic,600,600italic,700,700italic,800,800italic,900,900italic" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display:regular,500,600,700,800,900,italic,500italic,600italic,
    700italic,800italic,900italic" rel="stylesheet" />
    <!-- icons -->

    <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
</head>
<body>

    <div class="container">
        <h1>Classic Cheesecake Recipe</h1>

        <div class="subheading">
            <svg width="13" height="8" viewBox="0 0 13 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                <circle cx="1.5" cy="1.5" r="1.5" fill="#C4C4C4"/>
                <circle cx="1.5" cy="6.5" r="1.5" fill="#C4C4C4"/>
                <circle cx="6.5" cy="1.5" r="1.5" fill="#C4C4C4"/>
                <circle cx="6.5" cy="6.5" r="1.5" fill="#C4C4C4"/>
                <circle cx="11.5" cy="1.5" r="1.5" fill="#C4C4C4"/>
                <circle cx="11.5" cy="6.5" r="1.5" fill="#C4C4C4"/>
                </svg>
                <p>Look no further for a creamy and ultra smooth classic cheesecake recipe! Paired with a buttery graham cracker crust, no one can deny its simple decadence.
                     For the best results, bake in a water bath.</p>
        </div>
        <div class="image-holder">
            <img src="image/photo1.png" alt="piece of cake">
        </div>
        <div class="recipe-infos-box">
            <div class="info-category">
              <div class="recipe-info">
                <span class="material-icons info-icon">local_dining</span>
                <p class="info-name">Yields</p>
                <p class="info-value">12 servings</p>
              </div>
            </div>
            <div class="info-category flex jc-sb">
              <div class="recipe-info">
                <span class="material-icons info-icon r-span-2">schedule</span>
                <p class="info-name">Prep time</p>
                <p class="info-value"><time datetime="PT45M">45 minutes</time></p>
              </div>
              <div class="recipe-info">
                <span class="material-icons info-icon">schedule</span>
                <p class="info-name">Cook time</p>
                <p class="info-value"><time datetime="PT1H">1 hour</time></p>
              </div>
              <div class="recipe-info">
                <span class="material-icons info-icon">schedule</span>
                <p class="info-name">Total time</p>
                <p class="info-value"><time datetime="PT7H45M">7,75 hours</time></p>
              </div>
            </div>
          </div>










          *{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}
h1{
    font-family: Playfair Display;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 32px;

    color: #000000;
    margin: 32px auto auto 11px;

}
.subheading p{
    
    font-family: Montserrat;
font-style: italic;
font-weight: 500;
font-size: 12px;
line-height: 15px;

/* Gray 2 */

color: #4F4F4F;

}
.subheading{
    display: flex;
    margin: 12px auto auto 11px;
  
}
.image-holder img{
    width: 352px;
    height: 202px;
    margin: 12px auto auto 12px;
}



