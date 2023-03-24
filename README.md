# AI_Mern_Image_Generation
MidJourney and DALL-E are taking over social media. Dive into the world of artificial intelligence and build your own version of these tools that can generate everything from memes and art to beautiful UI/UX designs!

![Image Generation App](https://articles-img.sftcdn.net/f_auto,t_article_cover_xl/auto-mapping-folder/sites/3/2023/02/IA-generadoras-imagenes.jpeg)

<div style="margin-top: 1rem; text-align: center;margin-right: 25px; align-items:center; justify-content:center; display:flex">
    <img src="./client/public/crul.svg" style="width: 50px" alt="CRUL" />
    <p>+</p>
    <img style="width: 50px; margin-left: 20px" src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="SvelteKit">
</div>
    <p style="font-size: 2rem; font-weight: 700; text-align: center; margin-top: .9rem">CRUL + ReactJs</p>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#demo">Demo</a>
    </li>
        <li><a href="#built-with">Built With</a></li>
    <li>
      <a href="#dependencies">Required Dependencies</a>
    </li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#configuration">Configuration</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#open-source-licensing-info">License</a></li>
    <li><a href="#credits-and-references">Credits & References</a></li>
  </ol>
</details>
<br/>
This is an AI Image Generator that uses OpenAi's DALL-E and text-davincii-3. It generates an image out of the provided prompt. This is a game-changing software, it uses text-davincii-3 to suggest prompts for you.

## Demo
https://user-images.githubusercontent.com/79797604/219990531-af5d3224-30c3-40d9-84c1-bc5b28ca022e.mp4
<br/>
<br/>
### Built With

 [![React][React.js]][React-url]
 [![NodeJs][NodeJs]][NodeJs-url]
 [![MongoDb][MongoDB]][MongoDB-url]
 [![Express.js][ExpressJs]][ExpressJs-url]

<br/>

**Status**:  Alpha v1.2.1, 
<br/>

## Dependencies

The following dependencies must be installed in order for the software to work:
<br/>
    **Frontend (Client folder)**:
        - React
        - React-icons
        - File-saver
        - React-dom
        - React-router-dom
        - Lodash
        - React-helmet
        <br/>
    **Backend (Server folder)**:
        - Express
        - Nodemon
        - Mongoose
        - Dotenv
        - Cors
        - Openai
        - Cloudinary
<br/>

## Installation

To use this software, open your terminal and run 

```sh
cd server
```

```sh
npm install
```
once all the dependencies are done installing, run

```sh
npm run start
 ```

    open a new terminal and run

```sh
cd client
```

```sh
 npm i
```

    then start the frontend by running


```sh
npm run start

``` 
<br/>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<br/>

## Configuration

Cd into the server folder and create a `.env` file and fill it with your credentials from openai, mongodb and cloudinary.

```sh
    MONGODB_URL=""
    OPENAI_API_KEY=""
    CLOUDINARY_CLOUD_NAME=""
    CLOUDINARY_API_KEY=""
    CLOUDINARY_API_SECRET=""

```
<br/>

## Usage

Visit [http://localhost:5173](http://localhost:5173)

You can go to `/generate-image` route to generate your AI image.
You can also visit the `/showcase` route to view all the AI generated images 
<br/>

<br/>


